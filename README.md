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
- [bat](https://github.com/sharkdp/bat) - *a cat clone with syntax highlighting and Git integration*
- [exa](https://github.com/ogham/exa) - *ls modern replacement*
- [htop](https://github.com/htop-dev/htop) - *an interactive process viewer*
- [httpie](https://github.com/httpie/httpie) - *human-friendly CLI HTTP client for the API era*
- [wtfutil](https://github.com/wtfutil/wtf) - *the personal information dashboard for your terminal*
- [ansiweather](https://github.com/fcambus/ansiweather) - *weather in terminal, with ANSI colors and Unicode symbols*
- [thefuck](https://github.com/nvbn/thefuck) - *magnificent app which corrects your previous console command*
- [lazygit](https://github.com/jesseduffield/lazygit) - *simple terminal UI for git commands*
- [how2](https://github.com/santinic/how2) - *stackoverflow from the terminal*
- [autojump](https://github.com/wting/autojump) - *a cd command that learns - easily navigate directories from the command line*
- [neofetch](https://www.cyberciti.biz/howto/neofetch-awesome-system-info-bash-script-for-linux-unix-macos/) - *display what operating system you are using including theme, icons, hardware config and more*
- [ani-cli](https://github.com/pystardust/ani-cli) - *a cli tool to browse and play anime*
- [mangal](https://github.com/metafates/mangal) - *manga browser and downloader for Linux, Windows & MacOS*
- [telnet](https://formulae.brew.sh/formula/telnet) - *telnet towel.blinkenlights.nl - star wars 4*

### Development Applications
- [Zeplin](https://zeplin.io)
- [VSCode](https://code.visualstudio.com/Download)
- [Slack](https://slack.com/intl/es/downloads/osx)
- [Firefox](https://www.mozilla.org/ro/firefox/)
- [Google Chrome](https://www.google.com/chrome/)
- [Postman](https://www.postman.com/)
- [Android Studio](https://developer.android.com/studio)
- [Xcode](https://developer.apple.com/xcode/)
- [TextMate](https://macromates.com/)
- [VirtualBox](https://www.virtualbox.org/)
- [LICEcap](https://www.cockos.com/licecap/)
- [Reactotron](https://github.com/infinitered/reactotron)
- [Flipper](https://fbflipper.com/)
- [GraphiQL](https://www.electronjs.org/apps/graphiql)

### VSCode Extensions
- Managed trough [Settings Sync](https://code.visualstudio.com/docs/editor/settings-sync) in VSCode

### Font
- Use the [Fira Code font](https://github.com/tonsky/FiraCode) from [tonsky](https://tonsky.me/). 
- After downloading the .tff  install the font on your Mac by opening the file, and then use [these instructions](https://github.com/tonsky/FiraCode/wiki/VS-Code-Instructions) to add Fira Code to VSCode

### Personal Applications
- [VLC](https://www.videolan.org/vlc/download-macosx.en-GB.html)
- [Calibre](https://calibre-ebook.com/)
- [Transmission](https://transmissionbt.com/)
- [SoulSeekQT](http://www.slsknet.org/news/) - *an ad-free, spyware free, just plain free file sharing network for Windows, Mac and Linux (much like DC++)*
- [Traktor 3](https://www.native-instruments.com/en/products/traktor/dj-software/traktor-pro-3/)
- [Spotify](https://www.spotify.com/)
- [GeForce Now](https://www.nvidia.com/en-eu/geforce-now/) - *Cloud Gaming*
- [Signal](https://signal.org/)
- [Tor](https://www.torproject.org/download/)

### Extensions
- [Vanilla](https://matthewpalmer.net/vanilla/)
- [Amphetamine](https://apps.apple.com/us/app/amphetamine/id937984704)
- [rocket](https://matthewpalmer.net/rocket/)
- [f.lux](https://justgetflux.com)
- [Shazam for Mac](https://apps.apple.com/us/app/shazam/id897118787)
- [Scroll Reverser](https://pilotmoon.com/scrollreverser/)
