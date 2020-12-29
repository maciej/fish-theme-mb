> Default theme for [Oh My Fish][omf-link] with adjustments

## Install

```fish
$ omf install https://github.com/maciej/fish-theme-mb
$ omf theme fish-theme-mb
```

## Features

* All the things you need to know about Git in a glance.
* A subtle timestamp hanging out off to the right.
* Previous command status.
* Displays user@host

## Screenshot

<p align="center">
<img src="https://cloud.githubusercontent.com/assets/526122/9604024/ac338638-50ac-11e5-874a-70fa9287db93.png">
</p>

## Configuration

Only display the folder name:
```
  set -g theme_short_path yes
```

Hide user@host:
```
  set -g theme_hide_userhost yes
```

# License

[MIT][mit] © [bpinto][author] et [al][contributors]


[mit]:            http://opensource.org/licenses/MIT
[author]:         http://github.com/bpinto
[contributors]:   https://github.com/oh-my-fish/theme-default/graphs/contributors
[omf-link]:       https://www.github.com/fish-shell/oh-my-fish

[license-badge]:  https://img.shields.io/badge/license-MIT-007EC7.svg?style=flat-square
[travis-badge]:   http://img.shields.io/travis/oh-my-fish/theme-default.svg?style=flat-square
[travis-link]:    https://travis-ci.org/oh-my-fish/theme-default
