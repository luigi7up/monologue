# About

This repo is a fork of the orginal [Monologue](https://github.com/jipiboily/monologue/) blogging engine for Rails. The original project got abandoned, but I was using it in www.pinabox.com. When we decided to upgrade rails from 5.0 beta to 5.2.X.X Monologue dependecies were blocking the upgrade:

Monologue gems causing problems:
- `responders`
- `sass-rails`

Also, the project needed switch form `before_filter` to `before_action` introduced in newer Rails versions

The solution was forking the project and changing the dependency versions to something newer and changing the `before_filter` to `before_action`
