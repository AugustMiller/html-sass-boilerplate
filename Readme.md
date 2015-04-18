# HTML & Sass Boilerplate

I was frustrated having to rebuild this folder structure every time I wanted to hack around, so here we are.

## Getting Started

You'll need to make sure you've got Ruby and Sass installed.

```
$ which sass
```

Then, dive into the `assets` folder:

```
$ cd /path/to/your/project/assets/
```

Use `sass` to compile the stylesheet, and you'll be on your way:

```
$ sass --update sass/main.sass:css/main.css
```

If you don't want to have to run that every time, use Sass’s `watch` option, instead:

```
$ sass --watch sass/main.sass:css/main.css
```
