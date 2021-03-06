# wpe alpha apps init

## Description
Generate a `wpe.json` file for deploying a new WP Engine Headless Application

## Usage

```bash
$ wpe alpha apps init [OPTIONS]
```

## Extended Description

The `wpe alpha apps init` command provides takes you through a series of prompts in order to generate a `wpe.json` for a WP Engine Headless Application. You can then use the generated `wpe.json` file with the [`wpe alpha apps create`](/reference/cli/wpe/alpha/apps/create) command to deploy your app.

>> **NOTE:** You need to have a GitHub repository with an app ready to be deployed in order to make this command work properly.

## Options

| Name, shorthand | Description |
|:-------------|:---------------|
| `--help, -h` | Help for list  |

## Parent Command
| Command                                         | Description                                         |
|:------------------------------------------------|:----------------------------------------------------|
| [wpe alpha apps](/reference/cli/wpe/alpha/apps) | The base command for interacting with your WPE apps |
