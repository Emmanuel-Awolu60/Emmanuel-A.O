---
title: "Elevate Your Artistic Creativity with Flexbox"
seoTitle: "Elevate Your Artistic Creativity with Flexbox"
datePublished: Wed Nov 22 2023 10:17:43 GMT+0000 (Coordinated Universal Time)
cuid: clp9m2e6p00060ajlhnt64ojf
slug: elevate-your-artistic-creativity-with-flexbox
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1700598317232/e4b8c252-8e81-40ba-883a-815db6f35ac0.png
ogImage: https://cdn.hashnode.com/res/hashnode/image/upload/v1700648226791/50a8ce37-b4da-434b-8eea-7fefbc72227d.png
tags: css, javascript, html5, frontend-development

---

After having a basic understanding of HTML and CSS, you have the bedrock for a lot of design potential right next to you. However, that’s not the end of the road for the tools available to you. Having a good knowledge of the concepts and power of Flexbox will surely take you further.

**What exactly is Flexbox?**

Where basic CSS will let you style a webpage, Flexbox on the other hand adds in its namesake by giving the webpage the option of flexibility. Think of Flexbox as a way to have extended ease for organized control on the layout of a webpage. Flexbox is not meant for the entire page design, but rather contained element design in a single dimension, (row or column).

To give you an understanding of how the idea works, picture a box on the page. This box will contain the items or elements you place within it. These are your flex items. The flex items themselves will be placed on organized rows or columns. Consider your items being contained within a table of sorts. The items contained can now take definition from flex context, Directly put, this gives you a strong ease of control on how to display the content itself.

**Why bother with Flexbox so early on?**

As noted, Flexbox gives you another tool for design. More than that it allows for better ease of that design. As an emerging web developer, you are bound to run into some share of hair-pulling issues that draw valuable time from progress. While not go with the perfect option, Flexbox does provide a direct solution to matters of specific alignment issues that you may come across.

**How do I get started with Flexbox?**

Since Flexbox's original designs in early 2009, it has become widely used and accepted by web developers. 

To get started, you simply need to learn the syntax as you possibly did with HTML and CSS. There is no need to use or switch to a new code editor. Many of the popular editors will either already have support for the syntax or have plugins readily available.

With the knowledge that a modern browser is ready for your designs and your code editor of choice is up to the task, let's start diving into Flexbox concepts right away!

**Flexbox in action**

One of the most direct pickup methods used to learn Flexbox was by styling a basic site navigation element  It’s a common use case for Flexbox and a great introduction to basic syntax itself. In the example below, you can see a quick navigation element setup in HTML.

`<nav class=”navigator”>`

   `<div id=’home’><h2>Home<h2></div>`

     `<div id=’menu’><h2>Menu<h2></div>`

     `<div id=’events’><h2>Events<h2></div>`

     `<div id=’contact’><h2>Contact<h2></div>`

     `<div id=’’><h2><h2></div>`

`</nav>`

*This will be the output of on the page (some very basic styling was applied for visual ease)*

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1700571386235/aa294c17-cf62-4e82-a8ec-d40611c59d7a.jpeg align="center")

*We can move over to the CSS to apply the Flexbox syntax to get started.*

`.navigator{`

      `display: flex;`

`}`  
*This simple entry now changes the navigation element to appear like this*:

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1700571482133/ab675d35-2ece-44ea-be4f-f0f82960b992.jpeg align="center")

You are going to notice that the individual divs were able to contain themselves in a more manageable form. Consider the elements on a line here. This is the default setup when you apply no other arguments to the flex option. The items are arranged in the “flex-start” position. Each element is packed into the start of the line. You can see this modified when you apply the justify-content option “flex-end” as seen below in the CSS.

`.navigator{`

      `display: flex;`

      `justify-content: flex-end;`

`}`

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1700571619207/ff24f188-af1f-488f-8395-afe1aef86a85.jpeg align="center")

  

Notice the divs were moved to the end of the “line” as opposed to the front as you saw above. You can utilize other options to the justify-content area for alignments that fit your design needs. Take a look at these other options and how they appear on the page.

`justify-content: center`  

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1700571654714/c771bdf7-fb9d-4612-8a43-1df47daac7db.jpeg align="center")

  
`justify-content: space-around`

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1700571694850/0043c683-b00b-4df3-9e26-2e8d600a9e39.jpeg align="center")

  
`justify-content: space-between`

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1700571735010/b7f15c4e-fd5d-421d-a163-6b37dc030267.jpeg align="center")

As you can see, with just a simple switch of light syntax, the position, alignment, and general appearance of the navigation element was changed. These changes were all done within the span of a few minutes. While the provided example does not win any design awards, it does show just how easy modifying designs can be with the use of Flexbox. 

  
  

**Where Do I Go From Here?**

Where Do I Go From Here? Flexbox can be an amazing tool in your web-dev toolkit. The concepts covered in this very brief introduction are just the proverbial tip. There is much more you can accomplish with the other options Flexbox provides. I encourage you to explore the deeper concepts available to see where these abilities fit your designs. Note that while Flexbox provides some amazing avenues for designers, it is not always the best go-to tool. Other options like CSS Grid enable truly awesome frameworks to build responsive and beautiful sites. I like to champion the idea that there is not a definite one over the other use for Grid or Flexbox. I would instead like to encourage you to understand the “why” over the “how” of the tools to use. It’s a wide world of tech out there, don’t limit yourself.