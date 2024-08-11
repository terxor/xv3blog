The website contains the following pages:
- Home page: shows a number of latest blog posts.
- Blog list page: shows all blog posts from latest to earliest.
- Categories: shows categories of blogs (to search by category)
- Team: A page which shows authors and their customized pages (and to group posts by author).

## Base changes

- See `team_label` under `_data/vars.yml`. This appears in the navbar and few other places.
- See `baseurl` and `url` under `_config.yml`

> Note: for local render, set `baseurl` to `""`

## Authors

To add authors, create an file named `[author-alias].md` under `_authors`.
This alias should match the one mentioned in the file itself.
See examples.

You can also add an image of the auther under `assets/images`.

## Categories

Posts are organized per category within `categories` directory. To view/add categories,
you need to add the entry under `_data/categories.yml`.

While adding a new category, create a directory with category name under `categories` and also
add `index.md` (see example).

## Blog posts

See example blog post and extend the same concept.
