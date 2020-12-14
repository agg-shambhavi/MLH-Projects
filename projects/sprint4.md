---
title: Sprint 4 Project
layout: page
---

## Gitg0 🚀

[![NPM](https://nodei.co/npm/gitg0.png)](https://npmjs.org/package/gitg0)

![NodeJS CI Tests](https://github.com/dotrachit/gitg0/workflows/Node.js%20CI/badge.svg)
![Synk](https://github.com/dotrachit/gitg0/workflows/Snyk/badge.svg)
![Prettier Linter](https://github.com/dotrachit/gitg0/workflows/Prettier%20Linter/badge.svg)

**Gitg0 generates commit titles (with relevant emojis) and branch names for you.** You have the ability to configure the format of the Sugggested Commit Titles and Branch Names, and change emojis according to your preference in the `.gitgo` file.

## Usage

## Installation

The tool is available as an NPM package over [here](https://www.npmjs.com/package/gitg0).

Before installing the package, [download and install Node.js](https://nodejs.org/en/download/).

Then, you can install it by simple running the following command:

```bash
npm i -g gitg0
```

## Commands

Currently, we have the following 7 commands:

#### `gtg config`

Use this to set up your project's gitgo configuration. You will be asked certain questions regarding your commit and emoji preferences.

#### `gtg version`

Use this to check the version of your installed gitg0 package.

#### `gtg whoami`

Use this to get the list of commands along with their functions.

#### `gtg start`

Use this before you you start working on a new issue so that we can suggest the branch names and commit messages automatically.

#### `gtg display`

Use this to view the suggested branch name and commit title. You can also edit the suggested text based on your preference. This command should be run after `gtg start`.

#### `gtg checkout`

This is a replacement for `git checkout -b` and will simply checkout with gitgo's suggested branch name.

#### `gtg commit`

This is a replacement for `git commit -m` and will commit your files once added with gitgo's suggested commit message.

## Maintainers

- [Yash Khare](https://github.com/yashk2000)
- [Rachit Gupta](https://github.com/dotrachit)
- [Shambhavi Aggarwal](https://github.com/agg-shambhavi)
- [Preet Shah](https://github.com/shahpreetk)
