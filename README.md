# Professional résumé site

A lightweight, data-driven Jekyll site designed for GitHub Pages.

## Personalise the site

Edit `_data/resume.yml`. The page layout reads all résumé content from that one file.
Update `title`, `description`, `url`, and `baseurl` in `_config.yml` before publishing.

For a user/organisation site (`username.github.io`), leave `baseurl` empty. For a
project site (`username.github.io/repository-name`), set it to `/repository-name`.

## Run locally

```powershell
bundle install
bundle exec jekyll serve --livereload
```

Then open <http://127.0.0.1:4000>.

## Publish with GitHub Pages

Push the project to GitHub, then choose the repository's publishing source under
**Settings → Pages**. GitHub Pages will build the site with Jekyll.

## Licence

Copyright (c) 2026 **Lukasz Dziedziczak**. All rights reserved.

This repository is proprietary. Access does not grant permission to use, copy, modify, merge, publish, distribute, sublicense, sell, or publicly disclose its original contents without prior written permission from Lukasz Dziedziczak. See [LICENSE](LICENSE).

Third-party code and assets remain subject to their respective licences.
