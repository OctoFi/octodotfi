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

Blog posts are stored in the [_posts](/_posts) directory. Create a new file with the current date followed by a short title `YYYY-MM-DD-blog-post-title.md`. At the top of the file, paste the content below and update the title, date, author, and image. Author should correspond to a person in the [_data/people.yml](/_data/people.yml) file. i.e. doc, marco, ak88, etc. And images should be stored in the [images](/images) directory. Here is a helpful [Markdown Guide](https://guides.github.com/features/mastering-markdown/) for blog post content.

```
---
layout: post
title: Your Blog Post Title
date: 2020-08-16 00:00:00
author: doc
image: '/images/1.jpg'
---

Insert blog content here using markdown syntax
```

## Managing Team Members

### New Member

Add a new file to the [_team](/_team) directory and name it using the format `YYYY-MM-DD-personname.md`. Paste the following content and update person and date. `personname` should be replaced with a lowercased single word, such as `octopuslover`.

```
---
person: personname
date: 2021-03-22 08:01:35 +0300
published: true
---
```

Create a corresponding person in [_data/people.yml](/_data/people.yml) with the content below and update all fields. `personname` should match the lowercased single word chosen in the previous step. If the person doesn't have a twitter account, remove `external_url: https://twitter.com/twitterhandle`.

```
personname:
  title: Name of Person
  subtitle: Role on Team
  image: '/images/team/personname.jpg'
  external_url: https://twitter.com/twitterhandle
```

Team member images are stored in the [images/team](/images/team) directory.

### Remove Member

If a team member needs removed, simply update the team member file in [_team](/_team) with a `published: false` so they are no longer displayed on the site. This allows us to remove team members without breaking links to authors in old blog posts.
