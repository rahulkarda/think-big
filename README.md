# think-big

## Pre-requisites

This repo requires the use of [`pnpm`](https://pnpm.io/). To install, run the command:

```bash
npm -g install pnpm
```

or follow the instructions on [pnpm's installation page](https://pnpm.io/installation).

If you are using [VS Code](https://code.visualstudio.com/), the `think-big.code-workspace` file will suggest some extensions to use along with this development environment and break out the folder structure based on components.

## Getting Started

To install the required packages & dependencies, run

```bash
pnpm install
```

and then run

```bash
pnpm dev
```

to start the development live server.

## Contributing

### Commiting Code

This repo has a hook workflow to assist in the generation of [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/). When you wish to commit, please run the `git commit` command from the terminal and not the GUI. You will be prompted for information to build the commit. After you complete the prompts, the commit message will be opened in the designated editor in your `git` settings for you to preview before the code is committed.

If you don't want to constantly get stuck in `vi` hell, follow [these instructions](https://docs.github.com/en/get-started/getting-started-with-git/associating-text-editors-with-git) to change the default editor that `git` uses.

### Branch naming & pull requests

This repo is set up to not allow any commits to be pushed directly to the `main` or `develop` branches.

Create a new branch using the format `YourUserName/very-short-description`.
When you're ready to submit a pull request, you will want to merge it in to `develop`. Ideally, this pull request will correspond with one or more [Issues](https://github.com/100Devs-ADHD/think-big/issues).

We will submit pull requests from `develop` to `main` when we have enough meaningful changes committed.
