# NPM Install Private

Seeing if I can `npm install` a Git referenced package repository which is
private on GitHub.

```
npm i https://github.com/tomashubelbauer/email
```

Turns out the answer is **yes**. As long as Git on the system can access the
private repository (because it is authenticated using a PAT with a scope which
allows it for a password), NPM can indeed install the package repository, too.
