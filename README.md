# Extension CLI 

This is a command-line utility package that helps chrome extension development by providing
systematic way to build, test and document an extension project.


## Available Commands

Note that for each command `--help` or `--version` are also valid

#### run builds

```
xt-build --config --env --watch
``` 

This command will build the extension project; use:

- `-e prod` for production build (minified)
- `-e dev` for development build 

#### generate docs

```
xt-docs --config
```

Generate documentation for extension project. 

Uses [jsdoc](https://jsdoc.app/index.html) syntax.

#### sync project configs:

```
xt-sync --ci --lint --gitignore --all
```

Update configuration files to current defaults supplied by this CLI

#### clean working directory

```
xt-clean --modules --idea
```

Removes automatically generated files; include --modules flag to remove node_modules

#### run tests 
```
xt-test --watch
```

Execute tests


## Future Commands

[ ] `xt-init` -- create new project


---

**LICENSE** MIT
