
This [Jekyll](https://jekyllrb.com/) site uses the [multiple-languages-plugin](https://github.com/Anthony-Gaudino/jekyll-multiple-languages-plugin) which is [not currently supported](https://pages.github.com/versions/) by [GitHub Pages](https://pages.github.com/). It may be supported when you edit this site so you can revert this unfortunate workaround.

Here's a link to the GitHub Pages Issue:  
https://github.com/github/pages-gem/issues/401

### Workaround

We can upload the generated `_site` folder. Thus I suggest you clone this repo twice. Then checkout the `src` branch in the first clone, and keep ther other clone at the `master` branch. In the `src` branch, edit the jekyll cod there. When you're ready to release, copy the contents of `_site` to the `master` branch clone folder.
