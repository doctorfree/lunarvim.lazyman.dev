---
layout: post
title: LunarVim Configurations
toc: true
post_style: page
---

<h2>Lazyman Supported LunarVim Neovim Configurations</h2>

The following are [Lazyman](https://lazyman.dev) supported
[LunarVim](https://lunarvim.org) based Neovim configurations:

| LunarVim |        | Configurations |
| :------- | :----: | -------------: |
| [LunarVim](https://lunarvim.lazyman.dev/posts/LunarVim) | [Daniel](https://lunarvim.lazyman.dev/posts/Daniel) | [JustinLvim](https://lunarvim.lazyman.dev/posts/JustinLvim) |
| [LunarIde](https://lunarvim.lazyman.dev/posts/LunarIde) | [LvimAdib](https://lunarvim.lazyman.dev/posts/LvimAdib) | [Shuvro](https://lunarvim.lazyman.dev/posts/Shuvro) |

Install all Lazyman supported LunarVim configurations with the command `lazyman -i lunarvim`.

## What is LunarVim

[LunarVim](https://lunarvim.org) is one of the most popular Neovim "distributions"
along with [LazyVim](https://lazyvim.lazyman.dev),
[AstroNvim](https://astronvim.lazyman.dev), and
[NvChad](https://nvchad.lazyman.dev). These aren't really distributions,
they do not include Neovim, but that is what they are called. They are more
accurately described as "Neovim configuration frameworks". In most cases they
provide some pre-configuration of plugins as well as an easy way to extend
the base configuration.

A Neovim configuration framework can be of considerable assistance in managing
the exploding Neovim plugin ecosystem, quickly and easily incorporating
advanced features, and maintaining an up-to-date Neovim configuration.

Features that distinguish LunarVim include:

- Well maintained and mature
- Custom installation processs installs LunarVim in an isolated location
- Been around a while, large community, widespread presence on the web

Read our overview and comparison of
[Neovim configuration distributions](https://lazyman.dev/posts/Configuration-Distributions).

## Opinionated

LunarVim ships with a sane default config for you to build on top of.
Features include autocompletion, integrated terminal, file explorer,
fuzzy finder, LSP, linting, formatting and debugging.

## Extensible

Just because LunarVim has an opinion doesn't mean you need to share it.
Every builtin plugin can be toggled on or off in the config.lua file.
This is the place to add your own plugins, keymaps, autocommands, leader
bindings and all other custom settings.

## Fast

LunarVim lazyloads plugins wherever possible to maximize speed. Disabled
plugins also will not decrease speed due to the plugin list being compiled
with only the active plugins. This strategy allows LunarVim to not have to
choose between features and speed.

## Core Plugins List

See the LunarVim [core plugins list](https://www.lunarvim.org/docs/features/core-plugins-list)

<div align="center">
  <p align="center">
    <a href="https://ronrecord.com" target="_blank" rel="noopener">
      <img align="center"
      style="width:40px;height:40px"
      alt="domain"
      src="https://raw.githubusercontent.com/doctorfree/doctorfree/master/icons/domain.png"
    /></a>
    <a href="https://www.reddit.com/user/No-Blackberry-3160" target="_blank" rel="noopener">
      <img align="center"
      style="width:40px;height:40px"
      alt="reddit"
      src="https://raw.githubusercontent.com/doctorfree/doctorfree/master/icons/reddit.png"
    /></a>
    <a href="https://github.com/doctorfree" target="_blank" rel="noopener">
      <img align="center"
      style="width:40px;height:40px"
      alt="github"
      src="https://raw.githubusercontent.com/doctorfree/doctorfree/master/icons/github.png"
    /></a>
    <a href="https://gitlab.com/doctorfree" target="_blank" rel="noopener">
      <img align="center"
      style="width:40px;height:40px"
      alt="gitlab"
      src="https://raw.githubusercontent.com/doctorfree/doctorfree/master/icons/gitlab.png"
    /></a>
    <a href="https://twitter.com/ronrecord" target="_blank" rel="noopener">
      <img align="center"
      style="width:40px;height:40px"
      alt="twitter"
      src="https://raw.githubusercontent.com/doctorfree/doctorfree/master/icons/twitter.png"
    /></a>
    <a href="https://youtube.com/c/doctorfree" target="_blank" rel="noopener">
      <img align="center"
      style="width:40px;height:40px"
      alt="youtube"
      src="https://raw.githubusercontent.com/doctorfree/doctorfree/master/icons/youtube.png"
    /></a>
    <a href="https://linkedin.com/in/ronrecord" target="_blank" rel="noopener">
      <img align="center"
      style="width:40px;height:40px"
      alt="linkedin"
      src="https://raw.githubusercontent.com/doctorfree/doctorfree/master/icons/linkedin.png"
    /></a>
    <a href="https://instagram.com/doctorfree" target="_blank" rel="noopener">
      <img align="center"
      style="width:40px;height:40px"
      alt="instagram"
      src="https://raw.githubusercontent.com/doctorfree/doctorfree/master/icons/instagram.png"
    /></a>
    <a href="https://noc.social/@doctorwhen" target="_blank" rel="noopener">
      <img align="center"
      style="width:40px;height:40px"
      alt="mastodon"
      src="https://raw.githubusercontent.com/doctorfree/doctorfree/master/icons/mastodon.png"
    /></a>
    <a href="https://en.wikipedia.org/wiki/User:Doctorfree" target="_blank" rel="noopener">
      <img align="center"
      style="width:40px;height:40px"
      alt="wikipedia"
      src="https://raw.githubusercontent.com/doctorfree/doctorfree/master/icons/wikipedia.png"
    /></a>
  </p>
</div>
