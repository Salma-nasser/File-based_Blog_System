# File-based_Blog_System
Overview

A lightweight, file-based blogging system built on ASP.NET Core 10 Preview 4 Minimal API that stores content as files rather than in a database.

Core Features

Content Management

Blog Posts: Support for title, description, body, published date, and modification date
Metadata: Support for tags and categories for each post
Media: Image and file upload capabilities with automatic resizing options for images
Custom URLs: Ability to define custom slugs/URLs for each post
File Storage: All content stored in a structured file system rather than a database
Authentication & Authorization

Secure login system for content authors and administrators
Role-based permissions (Admin, Author, Editor)
JWT-based authentication for API access
Front End Features

Home page showing recent posts with pagination
Category-based listing pages with pagination
Tag-based filtering
Responsive design for mobile and desktop views
Search functionality across all posts
Publishing

XML publishing support (RSS/Atom feeds)
Scheduled publishing of posts
Draft/published status for posts
Technical Requirements

ASP.NET Core 10 Preview 4 Minimal API architecture
No database dependencies (file-based storage)
Markdown or HTML support for content editing
Optimized asset delivery (images, CSS, JS)
SEO-friendly URL structure
