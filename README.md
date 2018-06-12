
To add a new post, copy `templates/yyyy-mm-dd-author-title.markdown` into the `_posts` directory.
Keep to this naming convention so we don't end up with file name clashes when pushing to the repo.
Commit and push to the `master` branch to get a post up on the site.

You'll need `ruby` and `bundler` installed to preview things.
You can build the site locally to view it with `bundle exec jekyll serve`.
Any posts in the `_drafts` folder will not appear on the main site - they can be built locally using `bundle exec jekyll serve --drafts`.

Check out the [Jekyll docs][jekyll-docs] for more info.

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
