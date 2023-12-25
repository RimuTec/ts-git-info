# ts-git-info

Welcome! This nodejs library `ts-git-info` is a simple wrapper around the `git` command line tool. It provides a simple interface to get information about the current git repository.


It is meant to be a TypeScript equivalent for [`node-git-info`]](https://www.npmjs.com/package/node-git-info) which is written in JavaScript but hasn't been upgraded since November 2016.

## Dev Environment

### All Host OSes

Prereqwuisites:
1. VS Code with extention "Remote Development"
2. Docker Desktop
3. Git command line interface (CLI)

### Windows Only

If your host computer uses Windows, then you need to install WSL2 with a Linux distro. Generally, I use the latest LTS version of Ubuntu (22.04 as of writing).

Also, if you are on Windows, then you need to clone the repo into the Linux file system. If you don't then you are likely to encounter problems such as synchronization issues.

To check whether you've clone into a Linux files system on Windows, run the following command in the terminal:

```bash
pwd
```

If the output starts with `/home`, then you are in the Linux file system. If it starts with `/mnt` or `/c`, then you are in the Windows file system.

Note that Mingw64 for Windows will not suffice either, even though their bash implementation is quite good.
