# dev-setup-macos
MacOS configuration for development

# Homebrew package manager
Official documentation: https://brew.sh/
1. Install Homebrew: `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`

# Code editor
Install text/code editor for editing files:
- Neovim `brew install neovim`: https://neovim.io/
- Brackets `brew install --cask brackets`: https://brackets.io/
- Geany `brew install --cask geany`: https://www.geany.org/
- TextMate `brew install --cask textmate`: https://macromates.com/
- Textadept: https://orbitalquark.github.io/textadept/


# iTerm2
Official documentation: https://iterm2.com/

1. Install iTerm2: `brew cask install iterm2`
2. Install AI plugin: https://iterm2.com/ai-plugin.html
3. Make iTerm2 as default terminal: _Menu -> Make iTerm2 Default Term_
4. Set profile and working directory: _Settings -> Profile -> General -> Working Directory_
5. Set blinking cursor: _Settings -> Profile -> Text -> Blinking cursor_
6. Set scrollback lines: _Settings -> Profile -> Terminal_
7. Change Right Option key to ESC+: _Settings -> Profile -> Keys -> General_ (it enable to use Option + Delete to remove whole words in terminal)
8. Enable backward and forward navigation between words: https://danicfilip.com/2018/how_to_use_alt_arrows_to_navigate_between_words_in_iterm2/
9. Set keys bindings: _Settings -> Profile -> Keys_ | _Settings -> Keys_
10. Show Timestmps: _Menu -> View -> Show Timestamps_

# Git
1. Install git: `brew install git`
2. Configure git, username, email, editor: https://git-scm.com/book/en/v2/Customizing-Git-Git-Configuration
3. Configure SSH key: https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent

# zsh
1. Install zsh: `brew install zsh`

# oh-my-zsh
Official documentation: https://ohmyz.sh/
1. Install oh-my-zsh: `sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"`
2. Wiki: https://github.com/ohmyzsh/ohmyzsh/wiki

# oh-my-zsh plugins
The list of available oh-my-zsh plugins: https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins
1. Install zsh-autosuggestion: https://github.com/zsh-users/zsh-autosuggestions/blob/master/INSTALL.md#oh-my-zsh
2. Install zsh-syntax-highlighting: https://github.com/zsh-users/zsh-syntax-highlighting/blob/master/INSTALL.md#oh-my-zsh
3. Some useful plugins: ```
   plugins=(
   aliases
   brew
   command-not-found
   copybuffer
   copyfile
   copypath
   dirhistory
   docker
   extract
   git
   gitignore
   gradle
   history
   history-substring-search
   jira
   kubectx
   macos
   npm
   postgres
   pip
   python
   redis-cli
   ssh-agent
   sublime
   sudo
   web-search
   z
   zsh-autosuggestions
   zsh-syntax-highlighting
   )```

# oh-my-zsh themes
ohmyzsh themes: https://github.com/ohmyzsh/ohmyzsh/wiki/Themes

To install for example Powerlevel9k, follow instruction:
1. https://github.com/romkatv/powerlevel10k?tab=readme-ov-file#oh-my-zsh

# IDE
Install IDE:
- IntelliJ: https://www.jetbrains.com/idea/download/
- PyCharm: https://www.jetbrains.com/pycharm/download/
- WebStorm: https://www.jetbrains.com/webstorm/download/
- Visual Studio Code: https://code.visualstudio.com/Download
- Atom: https://atom-editor.cc/

# Others tools and libraries
- curl: `brew install curl`
- jq: `brew install jq`

# Useful MacOS keyboard shortcuts
- Show hidden files: CMD + Shift + .
- Screenshots: CMD + Shift + 3; CMD + Shift + 4; CMD + Shift + 5
- Screen lock: CMD + Ctrl + Q
  https://support.apple.com/en-us/102650

# Links:
https://github.com/ohmyzsh/ohmyzsh/wiki/Plugins-Overview
https://github.com/ohmyzsh/ohmyzsh/wiki/Themes
https://github.com/ohmyzsh/ohmyzsh/wiki/Plugins
https://github.com/ohmyzsh/ohmyzsh/wiki/Cheatsheet
https://github.com/romkatv/powerlevel10k
https://dev.to/equiman/why-oh-my-zsh-is-so-cool-31gd
https://travis.media/top-10-oh-my-zsh-plugins-for-productive-developers/
https://kapeli.com/cheat_sheets/Oh-My-Zsh_Git.docset/Contents/Resources/Documents/index

