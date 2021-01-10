# Nedwin's blog

This is Ned's blog running on Github Pages using the Jekyll framework.

It's hosted at https://neddwyer.com/blog which is actually a custom domain for https://nedwin.github.io/blog

## Local development

To run this locally on a unix-based machine, ensure Ruby and Bundler are installed. Then you can use the following commands:

```
bundle install
bundle exec jekyll serve --baseurl ""
open http://localhost:4000
```

## Writing a blog

Create a new file in the `_posts` directory using the `YYYY-MM-DD-<title>.md` filename convention. 

Images you'd like to include should be placed in the `assets/images` folder.

Commit your blog to the `main` branch and they will be live!