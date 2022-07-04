<div align="center" margin="0 auto 20px">
  <h1>💻 machine setup</h1>
  <p>intended for macOS, but most applications and tools are available on other operating systems
</div>

### Homebrew
- [Brew homepage](https://brew.sh/) <br>
`/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`

### Xcode CLI Development Tools
- `xcode-select --install`

### Git
- `brew install git`
- Configure git to always use SSH when dealing with HTTPS GitHub repos <br>
`git config --global url."git@github.com:".insteadOf https://github.com/`

#### GitHub Command-Line SSH Authentication
- [Generate an SSH key for your new computer](https://help.github.com/en/github/authenticating-to-github/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)
- [Add the SSH public key to your Github account](https://help.github.com/en/github/authenticating-to-github/adding-a-new-ssh-key-to-your-github-account)

### Node.js
- Check if Node is already installed, and uninstall it first <br>
`brew uninstall --ignore-dependencies node && brew uninstall --force node`

- Update the Homebrew package list and install NVM <br>
`brew update` <br>
`brew install nvm`

- Create a directory for NVM at home <br>
`mkdir ~/.nvm`

- Now, configure the required environment variables. Edit the following configuration file in your home directory <br>
`nano ~/.zshrc` <br>
And add the following lines <br>
`export NVM_DIR=~/.nvm` <br>
`source $(brew --prefix nvm)/nvm.sh`

- Install Node using NVM <br>
 `nvm install node`

### Yarn 
- [Install Yarn with Homebrew](https://formulae.brew.sh/formula/yarn) <br>
`brew install yarn`

### Python
- [Install Python with Homebrew](https://docs.brew.sh/Homebrew-and-Python)

### iTerm2
- [iTerm2](https://www.iterm2.com)

### zsh + oh my zsh
- [zsh](https://ohmyz.sh)
- [oh my zsh](https://ohmyz.sh/)
- `plugins=(git gitfast git-extras dirhistory zsh-autosuggestions zsh-syntax-highlighting)`
- [powerlevel10k](https://github.com/romkatv/powerlevel10k)

### Command Line Tools
- [ani-cli](https://github.com/pystardust/ani-cli) - *a cli tool to browse and play anime*
- [ansiweather](https://github.com/fcambus/ansiweather) - *weather in terminal, with ANSI colors and Unicode symbols*
- [autojump](https://github.com/wting/autojump) - *a cd command that learns - easily navigate directories from the command line*
- [bat](https://github.com/sharkdp/bat) - *a cat clone with syntax highlighting and Git integration*
- [exa](https://github.com/ogham/exa) - *ls modern replacement*
- [fig.io](https://fig.io/) - *IDE-style autocomplete & intellisense to your existing terminal*
- [how2](https://github.com/santinic/how2) - *stackoverflow from the terminal*
- [htop](https://github.com/htop-dev/htop) - *an interactive process viewer*
- [httpie](https://github.com/httpie/httpie) - *human-friendly CLI HTTP client for the API era*
- [lazygit](https://github.com/jesseduffield/lazygit) - *simple terminal UI for git commands*
- [mangal](https://github.com/metafates/mangal) - *manga browser and downloader for Linux, Windows & MacOS*
- [neofetch](https://www.cyberciti.biz/howto/neofetch-awesome-system-info-bash-script-for-linux-unix-macos/) - *display what operating system you are using including theme, icons, hardware config and more*
- [telnet](https://formulae.brew.sh/formula/telnet) - *telnet towel.blinkenlights.nl - star wars 4*
- [thefuck](https://github.com/nvbn/thefuck) - *magnificent app which corrects your previous console command*
- [wtfutil](https://github.com/wtfutil/wtf) - *the personal information dashboard for your terminal*

### Development Applications
- [Android Studio](https://developer.android.com/studio)
- [Firefox](https://www.mozilla.org/ro/firefox/)
- [Flipper](https://fbflipper.com/)
- [Google Chrome](https://www.google.com/chrome/)
- [GraphiQL](https://www.electronjs.org/apps/graphiql)
- [LICEcap](https://www.cockos.com/licecap/)
- [Postman](https://www.postman.com/)
- [Reactotron](https://github.com/infinitered/reactotron)
- [Slack](https://slack.com/intl/es/downloads/osx)
- [TextMate](https://macromates.com/)
- [VSCode](https://code.visualstudio.com/Download)
- [VirtualBox](https://www.virtualbox.org/)
- [Xcode](https://developer.apple.com/xcode/)
- [Zeplin](https://zeplin.io)

### VSCode Extensions
- Managed trough [Settings Sync](https://code.visualstudio.com/docs/editor/settings-sync) in VSCode

### Font
- Use the [Fira Code font](https://github.com/tonsky/FiraCode) from [tonsky](https://tonsky.me/). 
- After downloading the .tff  install the font on your Mac by opening the file, and then use [these instructions](https://github.com/tonsky/FiraCode/wiki/VS-Code-Instructions) to add Fira Code to VSCode

### Personal Applications
- [Calibre](https://calibre-ebook.com/)
- [GeForce Now](https://www.nvidia.com/en-eu/geforce-now/) - *Cloud Gaming*
- [Signal](https://signal.org/)
- [SoulSeekQT](http://www.slsknet.org/news/) - *an ad-free, spyware free, just plain free file sharing network for Windows, Mac and Linux (much like DC++)*
- [Spotify](https://www.spotify.com/)
- [Tor](https://www.torproject.org/download/)
- [Traktor 3](https://www.native-instruments.com/en/products/traktor/dj-software/traktor-pro-3/)
- [Transmission](https://transmissionbt.com/)
- [VLC](https://www.videolan.org/vlc/download-macosx.en-GB.html)

### MacOS Exclusive
- [Amphetamine](https://apps.apple.com/us/app/amphetamine/id937984704)
- [Scroll Reverser](https://pilotmoon.com/scrollreverser/)
- [Shazam for Mac](https://apps.apple.com/us/app/shazam/id897118787)
- [Vanilla](https://matthewpalmer.net/vanilla/)
- [amethyst](https://ianyh.com/amethyst/)
- [cakebrew](https://www.cakebrew.com/)
- [f.lux](https://justgetflux.com)
- [rocket](https://matthewpalmer.net/rocket/)
