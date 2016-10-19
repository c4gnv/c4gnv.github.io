---
title: Writing a post
---
We use [Hexo](https://hexo.io/) for our blogging platform.

## Setup
1. Install Hexo with `npm install hexo-cli -g`
2. Clone this repository and checkout the `develop` branch.
3. Run `npm install`

## Writing
1. Generate your new post with `hexo new "<post name>"`
2. Run local server to see your post with `hexo server`
3. Posts are stored as markdown in the `source/_posts` folder.
4. If you have additional assets needed for your post, look for the folder created inside of `source/_posts` that has the same name as your blog post. You can reference these assets as relative URLs from your blog post.

### Deploying

1. You must have push permissions to the `master` branch of `https://github.com/c4gnv/c4gnv.github.io`
2. Run `hexo generate`
3. Run `hexo deploy`
