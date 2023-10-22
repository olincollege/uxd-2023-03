---
published: false
---
# Team Hippogriff website

## Running via Docker

Requires `docker` installed on your machine.

```bash
$ make docker
```

The site will be available at http://localhost:4000.

## Running locally (not recommended)

Requires `rbenv`, a Ruby version manager. Without Ruby experience, this is not recommended.

```bash
$ rbenv install
$ make start
```

The site will auto reload when you make changes to the source files.

## Theme

The theme is based on [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/).

### Layouts

Jekyll layouts are templates that define the structure of a page or post in a website built with Jekyll.

We can use the following layouts, [click here to see more](https://mmistakes.github.io/minimal-mistakes/docs/layouts/):

| Layout          |
|-----------------|
| archive         |
| archive-taxonomy|
| search          |
| single          |
| splash          |
| home            |
| posts           |
| categories      |
| category        |
| tags            |
| tag             |
