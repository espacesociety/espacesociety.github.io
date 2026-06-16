# E-Space Society — The Macropedia

This repository holds the source for **[espacesociety.org](https://espacesociety.org)**, the
archive of the **Macropedia**: a fictitious, mock-encyclopedia of a far-future
human society and the collapse of its Imperium.

The Everyspace Society began as a group of authors who met online and wanted to
build a science-fiction milieu broad enough to span most of the genre's trends
across time and space. Finding that the [Fudge RPG](http://www.fudgerpg.com/)
lacked a science-fiction setting, they wrote one. The result is the Macropedia,
written in the voice of Scholars at the fall of the Imperium attempting to
summarize their society and the causes of its decline.

The site is a [Jekyll](https://jekyllrb.com/) build of that wiki, migrated from
its original PmWiki and Octopress incarnations and now published through GitHub
Pages.

## Authors

The Macropedia was created by three authors, who hold its copyright jointly:

- **Aaron Clausen**
- **John Ughrin**
- **Ben Wilson**

Mateusz Czaplinski and others have contributed editorial and worldbuilding work
over the years.

## Copyright

The Macropedia is **© Aaron Clausen, John Ughrin, and Ben Wilson**.

Copyright is held **jointly and non-exclusively** by the three authors. Each
author retains a non-exclusive copyright in the collective work and is free to
use, reproduce, adapt, and license their own contributions and the shared
material independently of the others, without any one author's consent being
required and without granting any author exclusive rights over the whole.

Some material carries additional or different terms:

- Pages adapted from [Orion's Arm](http://www.orionsarm.com) are licensed under
  Creative Commons
  [Attribution-NonCommercial-ShareAlike](http://creativecommons.org/licenses/by-nc-sa/2.0/),
  unless otherwise noted.
- Pages authored by Ben Wilson are additionally available under Creative Commons
  [Attribution-NonCommercial-NoDerivs](http://creativecommons.org/licenses/by-nc-nd/2.0/).

See [main/copyrights.md](main/copyrights.md) for the canonical statement.

## Building locally

The site requires Ruby and [Bundler](https://bundler.io/).

```sh
bundle install        # install Jekyll and plugins
bundle exec jekyll serve   # build and serve at http://localhost:4000
```

Content lives in collection and section directories at the repository root —
most notably `_macropedia/` (the encyclopedia itself), alongside `chronology/`,
`star-systems/`, `technology/`, and the other thematic sections. Layouts are in
`_layouts/`, shared partials in `_includes/`, and site configuration in
`_config.yml`.

## Contributing

The setting has been largely dormant since 2010, but new authors are welcome.
See [main/notes-for-contributers.md](main/notes-for-contributers.md) and
[main/get-engaged.md](main/get-engaged.md) for how to get involved.
