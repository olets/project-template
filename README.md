# REPLACEMEREPO ![GitHub release (latest by date)](https://img.shields.io/github/v/release/olets/REPLACEMEREPO)

<!-- Begin meta notes -->
1. Initialize a Git repository
1. Add this repository as a remote named `project-template`
1. Add all files from this repository
    ```shell
    git cherry-pick -n $(git log --pretty=format:'%h' project-template/main | tail -1)..project-template/main
    ```
1. Remove the remote
    ```shell
    git remote remove project-template
    ```
1. Remove any unwanted parts of README.md
1. Remove package.json if not needed
1. Replace all instances of REPLACEMEREPO with the repo name
1. Replace all instances of REPLACEMEYEAR with the year
1. Replace all instances of REPLACEMEMETHOD with the recommended installation method
1. Replace all instances of REPLACEMEDESCRIPTION with the description
1. Remove these meta notes
1. Add all files and commit
1. Fill out README.md and, if applicable, package.json
<!-- End meta notes -->

<!-- TOC -->
- [Requirements](#requirements)
- [Installation](#installation)
    - [Homebrew](#homebrew)
    - [With a shell plugin manager](#with-a-shell-plugin-manager)
    - [Manual](#manual)
- [Usage](#usage)
    - [Examples](#examples)
    - [Options](#options)
- [Contributing](#contributing)
- [License](#License)

## Requirements



## Installation

REPLACEMEMETHOD is the recommended installation method.

### Homebrew

```shell
brew install olets/tap/REPLACEMEREPO
```

### With a shell plugin manager

1. Install REPLACEMEREPO with a zsh plugin manager. Each has their own way of doing things. See your package manager's documentation or the [zsh plugin manager plugin installation procedures gist](https://gist.github.com/olets/06009589d7887617e061481e22cf5a4a). If you're new to zsh plugin management, at this writing zinit is a good choice for its popularity, frequent updates, and great performance.

    After adding the plugin to the manager, restart zsh:

    ```shell
    exec zsh
    ```

### Manual

1. Download [the latest `REPLACEMEREPO` binary](https://github.com/olets/REPLACEMEREPO/releases/latest)
1. Put the file `REPLACEMEREPO` in a directory in your `PATH`

## Usage



### Examples



### Options




## Contributing

Thanks for your interest. Contributions are welcome!

> Please note that this project is released with a [Contributor Code of Conduct](CODE_OF_CONDUCT.md). By participating in this project you agree to abide by its terms.

Check the [Issues](https://github.com/olets/REPLACEMEREPO/issues) to see if your topic has been discussed before or if it is being worked on.

Please read [CONTRIBUTING.md](CONTRIBUTING.md) before opening a pull request.

## License

<p xmlns:dct="http://purl.org/dc/terms/" xmlns:cc="http://creativecommons.org/ns#" class="license-text"><a rel="cc:attributionURL" property="dct:title" href="https://www.github.com/olets/REPLACEMEREPO">REPLACEMEREPO</a> by <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://www.github.com/olets">Henry Bley-Vroman</a> is licensed under <a rel="license" href="https://creativecommons.org/licenses/by-nc-sa/4.0">CC BY-NC-SA 4.0</a> with a human rights condition from <a href="https://firstdonoharm.dev/version/2/1/license.html">Hippocratic License 2.1</a>. Persons interested in using or adapting this work for commercial purposes should contact the author.</p>

<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1" /><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1" /><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/nc.svg?ref=chooser-v1" /><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/sa.svg?ref=chooser-v1" />

For the full text of the license, see the [LICENSE](LICENSE) file.
