# MacBook Config
## System Preferences
* Dock & Menu Bar > Automatically hide and show the Dock: 체크
* Mission Control > Automatically rearrange Spaces based on most recent use: 체크 해제
* Language & Region > Preferred languages: 1. English > 2. 한국어 (드래그로 순서 조정)
* Security & Privacy > General > Require password: immediately
* Security & Privacy > General > Show a message when the screen is locked: 전화번호 / 이름
* Security & Privacy > FileVault: Turn On FileVault
* Keyboard > Text: 모든 자동 변경 옵션 끄기
* Keyboard > Shortcut > Use keyboard navigation to move focus between controls : 체크함
* Trackpad > Point & Click > Tab to click: 체크함
* Accessibility > Pointer Control > Trackpad options...: Enable dragging - three finger drag
## Finder
* General > New Finder windows show: (home folder)
* Advanced > Show all filename extensions: 체크
* View > Show Path Bar
* Downloads Folder - Group By:Date added, Sort By:Name

## Install
* homebrew
* git
* iterm2
  * Appearance > Theme: Minimal or Dark
  * Appearance > Windows > Show line under title bar when the tab bar is not visible: 체크 안함    
  * Profiles > Text: 폰트사이즈 12로 변경, n/n 줄간격 110으로 변경
  * Advanced > Height of top and bottom margins in terminal panes: 10
  * Advanced > Width of left and right margins in terminal panes: 12
  * Advanced > In minimal tab style, how prominent should the tab outline be?: 0
  * Profiles > Text > Unicode normalization form: NFC
  * Profile > Session: Status bar enabled 체크
* zsh, zsh-completions
  * oh-my-zsh
  ``` bash
  sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
  ```
  * plugin
  ``` bash
  # zsh-syntax-highlighting
  git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting

  # zsh-autosuggestions
  git clone git://github.com/zsh-users/zsh-autosuggestions $ZSH_CUSTOM/plugins/zsh-autosuggestions
  ```
