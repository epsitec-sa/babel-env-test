# Test for babel-env

This project is an example of how `babel-env` can be used to
automatically install all Babel-related npm packages, and also
produce a default `.babelrc` in the root of the project.

```
npm install --save-dev babel-env
```

This will produce the initial `.babelrc` and, most importantly,
it will also update it as needed in the future. This allows us
to share a consistent Babel configuration across all projects.
