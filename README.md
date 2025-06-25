# M.H. Majumdar Portfolio & Blog

This repository contains the source code for the personal portfolio and blog website of M.H. Majumdar. The website is built using Jekyll, HTML, and CSS, and it serves as a place to showcase photography work, share blog posts, and display personal projects. The website is hosted on GitHub Pages.

## Description

The M.H. Majumdar Portfolio & Blog is a simple yet elegant website created using **Jekyll**, a static site generator, combined with **HTML** and **CSS**. The website features a blog where posts can be written and shared, a photography portfolio gallery, and personal project showcases. The theme is designed to be clean, minimal, and fully responsive.

## Features

- **Responsive Design**: The site adjusts seamlessly to different screen sizes, providing a user-friendly experience on both desktop and mobile devices.
- **Jekyll Powered**: The site is built using Jekyll, enabling easy management of blog posts, categories, and custom pages.
- **Photography Portfolio**: Showcases photography work in a visually appealing layout with options to add captions and images.
- **Social Media Sharing**: Each blog post includes shareable links for Facebook, Twitter, and email.
- **Tagging System**: Posts are categorized by tags, making it easier for visitors to explore similar content.
- **SEO Optimized**: The site includes Open Graph and Twitter card meta tags for better social media visibility.

## Project Folder Architecture

Here’s a breakdown of the folder structure:

```
/mh-majumdar-blog
├── _config.yml          # Site configuration file
├── _includes            # Contains reusable components (e.g., header, footer, etc.)
├── _layouts             # Contains layout files (e.g., default, post, etc.)
├── _posts               # All blog posts are stored here
├── assets
│   ├── css              # Stylesheets
│   ├── images           # Images used across the site
│   └── js               # JavaScript files
├── blog                 # Contains all the posts with URL structure
│   └── 2025
│       └── 03
│           └── 25
│               └── Bazra-Shahi-Masjid.md   # Example post file
├── index.html           # Homepage of the portfolio
└── README.md            # This file
```

- **\_config.yml**: This is the main configuration file where site-wide settings like title, URL, base URL, and other configurations are defined.
- **\_includes/**: Contains snippets for reusable sections such as the header, footer, and meta tags.
- **\_layouts/**: Holds layout files for different types of pages. For example, `default.html` for the general page structure, and `post.html` for the blog post page layout.
- **\_posts/**: Stores all the markdown files for blog posts. Each file should be named following the `YEAR-MONTH-DAY-title.md` format.
- **assets/css/**: Contains all the custom CSS files used to style the site.
- **assets/images/**: Stores images for the site, such as logos, background images, and post images.
- **blog/**: Contains individual blog posts organized by year, month, and day in markdown files.

## How to Use

### 1. Clone the Repository

To get started, clone this repository to your local machine:

```bash
git clone https://github.com/mh-majumdar/mh-majumdar-blog.git
```

### 2. Install Jekyll

If you don’t have Jekyll installed, you can install it by running:

```bash
gem install jekyll bundler
```

If you're using a local development environment with a package manager like `brew`, you can also install it using:

```bash
brew install jekyll
```

### 3. Install Dependencies

Once Jekyll is installed, navigate to the project folder and run:

```bash
bundle install
```

This will install all the necessary dependencies specified in the `Gemfile`.

### 4. Run the Site Locally

After the dependencies are installed, you can run the site locally by executing:

```bash
bundle exec jekyll serve
```

By default, the site will be accessible at `http://localhost:4000`.

### 5. Adding New Posts

To add a new blog post, simply create a new markdown file in the `_posts/` directory. The file name should follow the format `YEAR-MONTH-DAY-title.md`. Here’s an example:

```markdown
---
layout: post
title: "My New Blog Post"
date: 2025-03-28 12:00:00 +0000
categories: blog
tags: photography
thumbnail: /assets/images/cover.jpg
---

This is the content of my new blog post. Add markdown content here...
```

### 6. Customizing the Site

You can customize various aspects of the site by editing the following files:

- **\_config.yml**: Modify site-wide settings like title, URL, and other configurations.
- **assets/css/**: Edit the CSS files to customize the appearance of your site.
- **\_layouts/**: Modify the layout files to change the structure of the pages.

### 7. Deploy to GitHub Pages

Once you're satisfied with the local version of the site, you can push the changes to GitHub. The site is already configured to be deployed on GitHub Pages. When you push to the repository, GitHub will automatically build and deploy the site.

The website will be accessible at the URL specified in `config.yml`, such as `https://mh-majumdar.github.io/mh-majumdar-blog`.
