# MicroBlog

## Project Description

MicroBlog is an ASP.NET Core Razor Pages application that allows users to create and view simple blog posts. The project demonstrates the use of Razor Pages, layouts, partial views, models, and JSON data storage.

Posts are stored in a JSON file so that the information can be saved and loaded when the application runs.

## Features

* View blog posts on the Index page
* Create new blog posts
* View individual posts on the Details page
* Store posts in a JSON file
* Use a shared layout for consistent navigation
* Use the `_PostCard` partial view to display post summaries
* Use Razor Pages and C# models

## How to Run

1. Open the MicroBlog project in Visual Studio 2022.
2. Build the project.
3. Run the application using the green Start button.
4. The MicroBlog home page will open in a web browser.
5. Use the navigation links to view posts and create new posts.

## Project Structure

* `Models/Post.cs` - Contains the Post model.
* `Pages/Index.cshtml` - Displays the blog posts.
* `Pages/Create.cshtml` - Provides a form for creating a new post.
* `Pages/Details.cshtml` - Displays an individual post.
* `Pages/Shared/_Layout.cshtml` - Provides the shared page layout and navigation.
* `Pages/Shared/_PostCard.cshtml` - Displays a summary of a blog post.
* `data/posts.json` - Stores the blog post data.
<img width="521" height="420" alt="image" src="https://github.com/user-attachments/assets/85a74c65-a456-4370-a835-cf4bbfb03814" />
<img width="296" height="331" alt="image" src="https://github.com/user-attachments/assets/318a781d-62a3-45f5-9d98-12c07f7b7172" />

