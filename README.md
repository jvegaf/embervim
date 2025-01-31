<h1 align="center">embervim</h1>

<!-- <div align="center">  -->
<!--    <a href="https://github.com/danlikestocode/embervim#Info"> -->
<!--    Info -->
<!--    </a>  -->
<!--    <span> • </span> -->
<!---->
<!--    <a href="https://github.com/danlikestocode/embervim#Install"> -->
<!--    Install -->
<!--    </a>  -->
<!--    <span> • </span> -->
<!---->
<!--    <a href="https://github.com/danlikestocode/embervim#Usage"> -->
<!--    Usage -->
<!--    </a>  -->
<!--    <span> • </span> -->
<!---->
<!--    <a href="https://dotfyle.com/danlikestocode/embervim-nvim"> -->
<!--    Plugin List -->
<!--    </a> -->
<!-- </div> -->
<!---->

<div align="center">
 
[![Neovim Minimum Version](https://img.shields.io/badge/Neovim-0.9.0-blueviolet.svg?style=flat-square&logo=Neovim&color=90E59A&logoColor=white)](https://github.com/neovim/neovim)
[![GitHub Issues](https://img.shields.io/github/issues/danlikestocode/embervim.svg?style=flat-square&label=Issues&color=d77982)](https://github.com/NvChad/NvChad/issues)

</div>

## :camera: Showcase
#### Dashboard 🌿
Organic & GMO-Free (Holisitic).
  
![Homepage](./assets/showcase/sc-dashboard.png)

#### Butter Scrolling 🧈
Your eyes can thank you later.  
  
![ButterScroll](./assets/showcase/gif-butterscroll-goodness.gif)

<h4>Zen-Mode 😌</h4>
<div>Get rid of the distractions, live a better life.</div>
<br>
<img src="./assets/showcase/sc-zen-mode.png">

### 🔥 Full Showcase 🔥
<details>
<summary>Extended Embervim Showcase</summary>

<h4>Keybind Reference 😖</h4>
<div>Just incase you forget a keybind!</div>
<br>
<img src="./assets/showcase/sc-keybind-reference.png">

<h4>Markdown Preview 😎</h4>
<div>Write beautiful markdown documents.</div>
<br>
<img src="./assets/showcase/sc-markdown-preview.png">

<h4>Mermaid Support (And More!) 🧜</h4>
<div>Throw some graphs in there!</div>
<br>
<img src="./assets/showcase/sc-mermaid.png">

<h4>LSP Wizardry 🧙</h4>
<div>Make your life easier, a step at a time.</div>
<br>
<img src="./assets/showcase/sc-lsp-finder.png">

<h4>File Explorer 🤓</h4>
<div>Edit your filesystem just like a buffer!</div>
<br>
<img src="./assets/showcase/sc-file-explorer.png">

<h4>Fuzzy File Finder 🔭</h4>
<div>Move through your codebase like a ninja.</div>
<br>
<img src="./assets/showcase/sc-fuzzy-file-find.png">

<h4>Floating Terminal ☁️<</h4>
<div>A terminal that is just one keybind away.</div>
<br>
<img src="./assets/showcase/sc-floating-terminal.png">

<h4>Sleek UI 👽</h4>
<div>A neovim commandline that doesn't compromise.</div>
<br>
<img src="./assets/showcase/sc-moden-commandline.png">

<h4>Theme Switcher 🎨</h4>
<div>Swap your clown barf to other clown barf.</div>
<br>
<img src="./assets/showcase/sc-theme-switcher.png">

<h4>Package Mangement 🧳</h4>
<div>One keystroke installs of LSPs/Formatters.</div>
<br>
<img src="./assets/showcase/sc-mason.png">
</details>



## :mag: Info

Embervim is yet again another neovim configuration designed to make it easy
for users not familiar with neovim to expand their own configuration. Time and 
time again I found myself switching between VSCode and neovim. I loved neovim
for its extensibility, but found that setting up LSP+Linting+Formatting was
often a headache not worth the time. So I set out to write a neovim configuration
that doesn't compromise and is easy to understand.

This configuration has a **lot** of features out of the box, that just **work**.
On top of that, this configuration was built with **Linx/Windows/MacOS** cross-compatiblity
in mind. Files are organized in a sensible fashion, without too much overhead.
Configuration files are split into a different folder for ease of use. Embervim
does not use any custom lua directory loading or any fancy handling of plugins. 
This **isn't meant to be a framework**, rather a configuration that users can build
upon. 

While switching back and forth between VSCode and neovim I found myself missing some
features of VSCode... such as the file tree. I kept installing different neovim
plugins to try to emulate that file tree behavior. Embervim does *not* ship with 
a traditional "file-tree" and that is for a good reason. It just *doesn't* work with
neovim. The way neovim is laid out with its tab structures makes implementing
a file tree that sticks on top of your screen a non-trivial task. Moreover, after
looking for different ways of doing things I found that a lot of neovim users navigate
files by sort of "bookmarking" them. The way you can navigate a codebase with fuzzy-finding
and bookmarking is just *superior* to a file tree. It almost makes a file tree seem
like an anti-pattern. So for that reason, embervim will *not* include a file tree, and
I believe that if you are subscribing to neovim you should also subscribe to doing things
the "neovim" way and not try to make neovim into VSCode.

#### Features
- Windows + MacOS + Linux cross-compatiblity
- Lazy loading capabilities
- Github Co-pilot integration
- Modern UI
- Modern Animations
- Fuzzy finding
- Safe buffer deleting
- Auto-complete + Intellisense
- Extensibility
> Full plugin list available [here](https://dotfyle.com/danlikestocode/embervim-nvim)

## :rocket: Install
#### **Pre-requisites**  
Please make sure to install the following dependencies:

- [Neovim](https://github.com/neovim/neovim)
- [Any Nerd Font](https://www.nerdfonts.com/)
- [Node](https://npm.github.io/installation-setup-docs/installing/using-a-node-version-manager.html)
- [Ripgrep](https://github.com/BurntSushi/ripgrep) --- *Optional*
- [LazyGit](https://github.com/jesseduffield/lazygit) --- *Optional*

> The only dependency that you *really* need to use this configuration is neovim,
however if you would like to use the full feature set, *Node* is recommended. 
(LSP's and Formatters generally rely upon Node) LazyGit is used for `<leader>gs`.

#### Install
Embervim does not provide any installation scripts or programs that will install
this configuration for you. Configuration directories often live in different places
for different operating systems. Fret not, embervim is *really* easy to install:

1. run the installer in terminal
```bash
bash <(curl -s https://raw.githubusercontent.com/jvegaf/embervim/install-script/linux_installer)
```
3. Launch neovim

Thats it, you're ready to go!

## :gear: Usage
Configuration with embervim is generally *really* simple. The file structure is
as follows:
- Plugin configuration goes in `after/plugins`
- Keybinds are in `lua/embervim/keybinds.lua`
- Plugin *installation* goes in `lua/embervim/plugins.lua`  
  
Thats it! You can look at the file structure and generally figure out what
goes where. You also don't have to adhere to this specific layout but it generally
helps to have plugin configuration in the `after` directory.

Some helpful commands:
- :Mason --- *Opens up LSP install menu*
- :Lazy --- *Opens up Plugin menu*

## :white_check_mark: To-Do
- [x] Move to Lazy instead of Packer 
- [x] Move to Oil for filesystem actions 
- [x] Implement null-ls for prettier/general formatting support
- [x] Move away from sexyscroller (lots of issues)
- [x] Integrate some sort of color changing statusline
- [ ] Implement null-ls/LSP format on save asynchronously
- [ ] Make setup/walkthrough video
- [ ] Implement debugging with DAP (Currently Broken)

## :newspaper: Notes
While embervim is generally a work in progress, it is **not** a framework, so breaking
changes will not affect the user. The recommended use for embervim is to copy the configuration
and use it as a *starting point* for your *own* configuration. Thanks for coming by
and checking this project out! Also if anything is missing from the docs, feel free
to submit an issue or a PR to get it sorted. :heart:    

## 👮 DISCLAIMER
Embervim is heavily inspired by [this](https://www.youtube.com/watch?v=f8h0iHg1wDg).
I am not a lawyer and this is not legal advice.

