# Contributing

Anyone can fork this repository, create a new branch, and submit a pull request for our team to review.

## Development

If you're interested in running the site locally, then this info will get you started.

### Requirements
* [Ruby](https://www.ruby-lang.org/en/)
* [Bundler](http://bundler.io/)
* [Jekyll](https://jekyllrb.com/)

### Get started

```ruby
bundle install
bundle exec jekyll serve
```

## Creating Blog Posts

Blog posts are stored in the [_posts](/_posts) directory. Create a new file with the current date followed by a short title `YYYY-MM-DD-blog-post-title.md`. At the top of the file, paste the content below and update the title, date, author, and image. Author name should correspond to the title of one of the [Team Members](/_team). And images should be stored in the [images](/images) directory. Here is a helpful [Markdown Guide](https://guides.github.com/features/mastering-markdown/) for blog post content.

```
---
layout: post
title: Your Blog Post Title
date: 2020-08-16 00:00:00
author: Team Member Name
image: '/images/1.jpg'
---

Insert blog content here using markdown syntax
```

## Managing Team Members

Team members are created by adding a new file to the [_team](/_team) directory. Team member images are stored in the [images/team](/images/team) directory. If a team member becomes inactive, update the team member file with an `active: false` so they are no longer displayed on the site.
