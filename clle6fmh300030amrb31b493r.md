---
title: "Difference Between Authorization and Authentication"
seoTitle: "Difference Between Authorization and Authentication"
seoDescription: "Difference Between Authorization and Authentication"
datePublished: Wed Aug 16 2023 20:20:08 GMT+0000 (Coordinated Universal Time)
cuid: clle6fmh300030amrb31b493r
slug: difference-between-authorization-and-authentication
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1694383966610/5000d3ea-547b-4ad5-914a-13ec3a433618.jpeg
ogImage: https://cdn.hashnode.com/res/hashnode/image/upload/v1692217067724/ac134d93-8917-40e4-ab70-3538d824a133.png
tags: authentication-vs-authorization

---

This clarifies the distinction between authorization and authentication and provides a general understanding of how they operate. We’ll discuss what they actually accomplish and how they use cloud computing in this piece.

***Authentication: What is it***

Verifying a user’s identity on a system or application usually requires giving the system or application the necessary user data, such as their login, password, answers to security questions, and any order information required to access the application. Consider Facebook as an example. When you visit Facebook and enter your email address, password, and other necessary details, authentication will be requested. Facebook will go through the process of confirming your identity based on the information you supplied; if Facebook cannot identify you based on the information you gave, an error will be returned; otherwise, the authentication will be successful.

***What authenticating does in practice***

1) Authentication verifies that users are who they say they are, and

2) Requires users to verify credentials using passwords and facial recognition

3) Typically, sends an ID Token.

***Authorization: What is it?***

is the process of deciding what a user or device who has been authenticated may do or perform. By ensuring that users only have access to the data and features that are appropriate for their privileges or position, authorization helps enforce security by defining the permission and level you have as a user within a system or application.

***Exactly what authorization does***

1) Authorization establishes what users may and cannot do;

2) policies confirm whether users are permitted;

3) Typically sends data via an access token

***What Connects Authorization and Authentication?***

Since both terms have the same “auth” acronym, authorization and authentication are frequently confused since they represent two parts of the access process for a system or application. Another similarity between authorization and authentication is the way they both use identity.

***Cloud computing authorization and authentication***

In any system that uses cloud computing, security is crucial. Due to the shared access paradigm that these services offer, everything runs on the same system. To accomplish these security objectives, cloud service providers use permission and authentication. For instance, the system may ask a user to submit a username, password, and other details when they attempt to access a certain cloud service. The cloud platform will then perform authorisation to make sure the user can only access their systems and data when the user successfully authenticates.

***Authorization or Authentication: Which Comes First?***

In the security process, authorization usually comes before authentication. Verifying a user’s identity through authorization is a procedure that frequently involves the use of a username, password, or other elements. Based on their role.