# `raco new`

[![Racket Discourse](https://img.shields.io/discourse/users?label=Discuss%20on%20Racket%20Discourse&logo=racket&server=https%3A%2F%2Fracket.discourse.group)](https://racket.discourse.group/) [![Racket Discord](https://img.shields.io/discord/571040468092321801?label=Chat%20on%20Racket%20Discord&logo=racket)](https://discord.gg/6Zq8sH5)

This package `new` allows users to quickly set up a working template for a variety of Racket projects.
It works by adding a new `raco` command `raco new` that downloads a repo from 
[github.com/racket-templates](https://github.com/racket-templates) and removing the git history 
from the project so you get a fresh start.

Install it to use Racket Templates or use it as a template for your own `raco` command line tool.

# Install

1. [Set your PATH environment variable](https://github.com/racket/racket/wiki/Set-your-PATH-environment-variable) 
so you can use `raco` and other Racket command line functions.
2. either look for `new` in the DrRacket menu **File|Package Manager**, or run the `raco` command:
```bash
raco pkg install new
```

# Usage 

`raco new` will list the available templates.

`raco new <template-name>` will set up the template in the current directory

`raco new <template-name> <destination-dir>` will set up the template in the specified directory

# Contributing to this project

Contibutions to both this tool and the collection of templates is welcome.

Contribute to this project by submitting a pull request or reporting an issue. 

Discussion on [Racket Discussions (Discourse forum/mailing list)](https://racket.discourse.group/) or [Racket Discord](https://discord.gg/6Zq8sH5).

# License

This package is free software, see [LICENSE](LICENSE) for more details.

By making a contribution, you are agreeing that your contribution is licensed under the Apache 2.0 license and the MIT license.

## get started contributing

Clone this repo, and install locally; 
```
git clone https://github.com/racket-templates/new.git
cd new 
raco pkg install
```
