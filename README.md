# LESS Test

This is an example of using LESS in action.

LESS is a CSS pre-processor; aka, this means that you write LESS, compile it,
and then the compiler generates a CSS file.

LESS is used because it gives you more control than CSS, and gives you more
powerful features such as use of variables and mixins (styles that you can
reuse).

## Use

If you haven't installed LESS before, you'll need to install it globally using:

```
npm install -g less
```

Once this is done, you can start to write LESS, in a file with the `.less`
extension. For instance, `style.less`. To compile this into CSS, run:

```
lessc style.less style.css
```

where `style.less` is the name of the file you want to compile, and `style.css`
is the name of the output CSS file. You can also output a minified version by
adding the `--clean-css` flag.

Read more [here](http://lesscss.org).

You will need to re-compile your LESS code every time you make changes. There
are ways to make this more efficient, such as using a task runner like Grunt.
