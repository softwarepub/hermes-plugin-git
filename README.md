NOTE: This repository is deprecated.
As of hermes v0.10, the git plugin is part of the hermes codebase.
It can be configured by adding the following code to your `hermes.toml` file:

``` toml
[harvest]
sources = [ "git" ]
```

No further installation is required.
Please remove any `pip install` calls for `git+https://github.com/softwarepub/hermes-plugin-git` from your publication workflow.
