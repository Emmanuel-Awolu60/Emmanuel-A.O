---
title: "How I Built My First API (and Why My GitHub History Looks Like a Diary)"
seoTitle: "My First API Adventure and GitHub Journey"
seoDescription: "Build your first API, understand GitHub commits, and document your coding journey with this beginner-friendly guide"
datePublished: Fri Aug 15 2025 20:59:34 GMT+0000 (Coordinated Universal Time)
cuid: cmedba78x000202lbaem9c6cn
slug: how-i-built-my-first-api-and-why-my-github-history-looks-like-a-diary
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1755291486100/d9013cb9-5aa6-42fe-acb1-b6dc32d2b389.webp
ogImage: https://cdn.hashnode.com/res/hashnode/image/upload/v1755291556597/0e937afd-4ca0-4ee9-9ca6-f42dff0b9832.webp
tags: programming-blogs, github, python, apis, beginners

---

At some point, every beginner coder hits the same wall: *"Okay… I can build a calculator. Now what?"*

For me, the next step was an API. Why? Because APIs are like the secret tunnels of the internet — invisible to most people but absolutely essential for getting anything done.

This post isn’t just about *making* an API. It’s about documenting the process in a way that future-me (and maybe a recruiter one day) can actually understand. Spoiler: the trick is **GitHub commits**.

---

### First, What Even *Is* an API?

Forget the corporate definition. Imagine you’re at a restaurant. You sit at your table, look at the menu, and order a burger. You do **not** storm into the kitchen to sear your own patty (unless you want to get thrown out). Instead, you tell the waiter, who passes your request to the kitchen.

That waiter? That’s your API. You tell it what you want, it goes to the kitchen (database), and comes back with exactly what you ordered — assuming you asked for something that exists.

You can build one for anything: to-do lists, weather reports, recipes, bad dad jokes…

---

### Why I Care About GitHub Commits (And Why You Should Too)

A commit is basically a “save point” in your code’s timeline. But it’s more than just a backup.

It’s a little note to yourself that says:

* “Here’s what I just changed.”
    
* “Here’s when I changed it.”
    
* “Here’s how far I got before I broke everything.”
    

Plus, employers can read your commit history and see your thought process. Or, if you’re like me, they’ll see a few messages like *"temp fix lol"* and know you’re a real human.

---

### Step 1: Pick a Simple API Idea

I went with a Books API. Keep it small. Keep it manageable. The features:

* Add a book
    
* List all books
    
* Get a book by ID
    
* Delete a book
    

**Endpoints:**

```json
POST /books  
GET /books  
GET /books/:id  
DELETE /books/:id
```

💾 Commit:

```json
git commit -m "Initial project setup and API planning"
```

---

### Step 2: Make a Folder, Make It Real

```json
mkdir books-api
cd books-api
git init
```

I used Node.js + Express because they’re basically the peanut butter and jelly of beginner backend projects.

```json
npm init -y
npm install express
```

💾 Commit:

```json
git commit -m "Setup Node.js project and installed Express"
```

---

### Step 3: The “Hello World” of APIs

Here’s the starting point in `index.js`:

```javascript
const express = require('express');
const app = express();
app.use(express.json());

app.get('/', (req, res) => {
    res.send('Welcome to the Books API!');
});

app.listen(3000, () => {
    console.log('Server running on port 3000');
});
```

Run it:

```json
node index.js
```

If you see *"Server running on port 3000"* in your terminal, you’re officially a backend developer (sort of).

💾 Commit:

```json
git commit -m "Created basic Express server with welcome route"
```

---

### Step 4: Give It Some Functionality

```javascript
let books = [];

app.post('/books', (req, res) => {
    const book = { id: books.length + 1, title: req.body.title };
    books.push(book);
    res.status(201).json(book);
});

app.get('/books', (req, res) => {
    res.json(books);
});

app.get('/books/:id', (req, res) => {
    const book = books.find(b => b.id == req.params.id);
    book ? res.json(book) : res.status(404).send('Book not found');
});

app.delete('/books/:id', (req, res) => {
    books = books.filter(b => b.id != req.params.id);
    res.status(204).send();
});
```

💾 Commit:

```json
git commit -m "Added CRUD routes for books"
```

---

### Step 5: Test Like You’re Trying to Break It

Some people use Postman, others use curl. I like curl because it makes me feel like I’m hacking in a movie:

```json
curl -X POST http://localhost:3000/books \
-H "Content-Type: application/json" \
-d '{"title":"The Great Gatsby"}'
```

If your API politely hands you back a JSON object with your book, you win.

💾 Commit:

```json
git commit -m "Tested all routes successfully"
```

---

### Step 6: Send It to GitHub

```json
git remote add origin https://github.com/yourusername/books-api.git
git branch -M main
git push -u origin main
```

Boom. Your project now lives online. Anyone can see your progress, and you can look back at it in six months and think, *“Wow… my code was so innocent back then.”*

---

### Where I’d Go Next

* Add a real database (MongoDB, Postgres, whatever makes you happy).
    
* Lock it down with authentication so no one can delete your books except you.
    
* Deploy it somewhere so you can show friends.
    
* Write tests so you don’t wake up to broken code.
    

And — **commit often**. Your GitHub history is more than a timeline. It’s the story of how you learned to build, debug, and improve something from nothing.