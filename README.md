!!!在新电脑上我已经改为使用 [LazyVim](https://www.lazyvim.org/)，并且非常推荐你使用!!!

---

> This is a [VapourNvim](https://github.com/VapourNvim/VapourNvim) configuration repository modified by Augists
>
> The original project seems to have been abandoned, and the functions in the plugin that are no longer in use have not been updated. The original repository has not been updated for 9 months, and the main contributor has quit maintaining it for academic reasons
>
> I have modified the functions of the null-ls plugin that have been abandoned, added copilot and other plugins, and modified the configuration a little bit according to my usage habits, you can continue to make changes in the `lua/Vapour/` directory
>
> Other issues and features will continue to be modified and updated as I use them


> 这是一个由 Augists 修改过的 [VapourNvim](https://github.com/VapourNvim/VapourNvim) 配置仓库
>
> 原项目似乎已被放弃，对于插件中已经不再使用的函数并没有修改，截止目前原仓库已经9个月没有更新，主要贡献者也因学业原因退出维护
>
> 我修改了 null-ls 插件已经被放弃的函数，并添加了 copilot 等插件，并按照我的使用习惯修改了一点配置，你可以在 `lua/Vapour/` 目录下继续进行修改
>
> 其他问题和特性还会根据我的使用继续修改和更新

---

<div align="center">
  <h1 align="center">VapourNvim</h1> 
	<a href="https://github.com/hackorum/VapourNvim/#features">✨ Features</a>
  <span> • </span>
	<a href="https://github.com/hackorum/VapourNvim/#installation">📦 Installation</a>
  <span> • </span>
	<a href="https://github.com/hackorum/VapourNvim/wiki">📚 Wiki</a>
  <span> • </span>
	<a href="https://github.com/hackorum/VapourNvim/wiki/Screenshots">📷 Screenshots</a>
  <p></p>
</div>


![VapourNvim Image](https://raw.githubusercontent.com/VapourNvim/VapourNvim/main/assets/screenshot.png)

## Introduction

The goal of this project is to simply *get work done* quickly.

This project is built to be:
* **Functional**. The core of an ideal IDE is functionality. If there is anything you want to add, please consider contributing
* **Minimal**. VapourNvim gives you what you need. Not too much, not too less.
* **Fast**. VapourNvim loads as smooth as butter with an optimum amount of plugins and lazy loading.
* **Easy to Configure**. If there's anything extra that you want to add or something you'd like to tweak, VapourNvim has an awesome [configuration system](https://github.com/hackorum/VapourNvim/wiki/User-Configuration) built in. 

## Features

* Easy to install and use
* Written in an efficient programming language
* Extensible package management system
* Very elegant and clean look
* Beautiful syntax highlighting with treesitter
* Language support and Code Autocompletion
* Great support for version control
* Terminal integration
* Efficient file navigation
* Autoformatting
* Awesome user configuration system


## Requirements

* [Neovim Version > 0.5](https://github.com/neovim/neovim/releases/tag/v0.5.0) - Required - For lua configuration
* [NodeJS](https://nodejs.org) - Required - For LSP
* [Lazygit](https://github.com/jesseduffield/lazygit) - Optional - For git integration
* [RipGrep](https://github.com/BurntSushi/ripgrep) - Optional - For telescope live grep

## Installation

Make sure you have curl and bash installed before you run this script.

```bash
curl -s https://raw.githubusercontent.com/VapourNvim/VapourNvim/main/install.sh | bash -s
```

## Manual Installation
```
git clone https://github.com/VapourNvim/VapourNvim ~/.config/nvim
nvim +PackerSync
```

## After Installation
You almost certainly want to add some plugins of your own. You can do it by making your own [config file](https://github.com/hackorum/VapourNvim/wiki/User-Configuration)
Please read the [wiki](https://github.com/VapourNvim/VapourNvim/wiki) for [Keybindings](https://github.com/hackorum/VapourNvim/wiki/Keybindings), [Language Servers](https://github.com/hackorum/VapourNvim/wiki/Language-Servers), [Plugins](https://github.com/hackorum/VapourNvim/wiki/Plugins) and [Screenshots](https://github.com/hackorum/VapourNvim/wiki/Screenshots).
After making VapourNvim your own, consider posting some screenshots [here](https://github.com/hackorum/VapourNvim/issues/20).

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the GPL-3.0 license.
