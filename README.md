# readme2gh - Updates your gh sites pages based on README.md

This tool updates the contents of your gh-pages index.html based on your
projects's README.md at master branch. Effectively this makes it really easy
to keep your project info in sync in case you happen to use README.md and
index in tandem.

## Usage

1. `sudo npm install -g` to install the script
2. Create index.tpl and place `{{ content }}` tag in place of current README
content. The tool will inject your README there.
3. Execute `readme2gh`. This will update your index.html based on your
index.tpl.
4. Preview the changes locally, commit and push.

Set up a cronjob or something if you want to be truly lazy.

## License

ghw is available under MIT. See LICENSE for more details.

