<img src="https://cdn.rawgit.com/oh-my-fish/oh-my-fish/e4f1c2e0219a17e2c748b824004c8d0b38055c16/docs/logo.svg" align="left" width="144px" height="144px"/>

#### Fish cook's theme 
> A Powerline-style, Git-aware theme for [Oh My Fish][omf-link] based on [FishFace](https://github.com/oh-my-fish/theme-fishface) and [es](https://github.com/oh-my-fish/theme-es) theme.
Broken up to two lines: information about duration of last command, shortened current location and git status on line one and line two consisting of user input all finished with a fish worthy pleasing appearance. 

[![MIT License](https://img.shields.io/badge/license-MIT-007EC7.svg?style=flat-square)](/LICENSE) [![Fish Shell Version](https://img.shields.io/badge/fish-v2.2.0-007EC7.svg?style=flat-square)](http://fishshell.com) [![Oh My Fish Framework](https://img.shields.io/badge/Oh%20My%20Fish-Framework-007EC7.svg?style=flat-square)](https://www.github.com/oh-my-fish/oh-my-fish)

<br/>

## Install
Make sure you have [Oh My Fish][omf-link] installed. Get repo and extract folder (`NAME`) to `/home/$USER/.local/share/omf/themes/`

## Requirements
* Latest fish version with a builtin `string` function (above `2.2.0`, so please get the latest version from  `HEAD`)
* Powerline-patched font

## Features
* Two lines: First giving useful information, second: containing user inpit. Both connected by a fish worthy pleasing appearance. 
* Git-aware theme with detailed __Git status__ in the left prompt (added, removed, modified, renamed, unstaged, stashed)
* __Node/Python/Ruby@gemset__ current version inside a git folder in the right prompt if respective virtual environment manager is installed (nvm, pyenv, rbenv)
* __Error status__ (if needed) and __duration of last command__ in the right prompt
* Mac-notifications on completion of long commands (10+&nbsp;seconds by default) if terminal (iTerm and Terminal) is out of focus
* Limits path to __two last folders__ for better visibility, with `$HOME` directory abbreviated to `~`
* 

## Screenshot

### __Git folder__
<p align="center">
<img src="https://github.com/oh-my-fish/theme-es/blob/master/Fish%20Prompt%20Git-es.png?raw=true">
</p>

### __Normal folder (no Git)__
<p align="center">
<img src="https://github.com/oh-my-fish/theme-es/blob/master/Fish%20Prompt%20NoGit-es.png?raw=true">
</p>

### __Normal read-only folder (no Git)__
<p align="left">
<img src="https://github.com/oh-my-fish/theme-es/blob/master/Fish%20Prompt%20NoGit%20Read-only-es.png?raw=true" width="280">
</p>

# License

[MIT][mit] © [eugenesvk][author]


[mit]:            http://opensource.org/licenses/MIT
[author]:         http://github.com/oparilames
[credits]:        FishFace authors ([Justin Hileman](https://github.com/bobthecow), [Kris Leech](https://github.com/krisleech), [Aaron DeVore](https://github.com/adevore)) and es theme authors ([Evgeny]() and again [Justin Hileman](https://github.com/bobthecow)) 
[omf-link]:       https://www.github.com/oh-my-fish/oh-my-fish

[license-badge]:  https://img.shields.io/badge/license-MIT-007EC7.svg?style=flat-square
