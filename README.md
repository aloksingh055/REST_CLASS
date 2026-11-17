# Quora Posts - RESTful API CRUD App

A simple and clean web application built using **Node.js**, **Express.js**, and **EJS** that demonstrates RESTful routing and complete CRUD (Create, Read, Update, Delete) operations.

## 🚀 Features

- **View All Posts (`GET /posts`):** Displays a feed of all user posts.
- **Create New Post (`GET /posts/new` & `POST /posts`):** Allows users to add a new post with a username and content.
- **View Single Post (`GET /posts/:id`):** Shows detailed view of an individual post using its unique ID (`uuid`).
- **Edit Post (`GET /posts/:id/edit` & `PATCH /posts/:id`):** Enables updating the content of an existing post.
- **Delete Post (`DELETE /posts/:id`):** Removes a post from the feed using `method-override`.

## 🛠️ Tech Stack

- **Backend:** Node.js, Express.js
- **Templating Engine:** EJS (Embedded JavaScript)
- **Styling:** HTML5, CSS3
- **Packages Used:** `express`, `ejs`, `uuid`, `method-override`


