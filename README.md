Modified Readme for Notes-to-Self

### 3. Publish your first blog post

Delete all files from `_posts`directory and create a new file called `/_posts/2019-2-13-Hello-World.md` to publish your first blog post. That's all you need to do to publish your first blog post! This [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) might come in handy while writing the posts.

> You can add additional posts in the browser on GitHub.com too! Just hit the <kbd>Create new file</kbd> button in `/_posts/` to create new content. Just make sure to include the [front-matter](http://jekyllrb.com/docs/frontmatter/) block at the top of each new blog post and make sure the post's filename is in this format: year-month-day-title.md

## Using Categories in Reverie

You can categorize your content based on `categories` in Reverie. For this, you just need to add `categories` in front matter like below:

For adding single category:

```md
categories: JavaScript
```

For adding multiple categories:

```md
categories: [PHP, Laravel]
```

The categorized content can be shown over this URL: <https://yourgithubusername.github.io/categories/>

## Pagination

Pagination of posts in Reverie works out-of-the-box. You only need to specify the number of posts you want on a single page in `_config.yml` and Reverie will take care of the rest.

```yml
paginate: 6
```

## RSS

Reverie comes with a [RSS feed](https://en.wikipedia.org/wiki/RSS) in-built. The generated RSS Feed of your blog can be found at <https://yourgithubusername.github.io/feed>. You can see the example RSS feed over [here](https://reverie-jekyll.netlify.app/feed.xml).

## Sitemap

The generated sitemap of your blog can be found at <https://yourgithubusername.github.io/sitemap>. You can see the example sitemap feed over [here](https://reverie-jekyll.netlify.app/sitemap).

## The name?

reverie - _a state of being pleasantly lost in one's thoughts; a daydream._<br><sup>/ˈrɛv(ə)ri/</sup> 
