# GPT3 Powered CLI

Get answers for CLI commands from GPT3 right from your terminal

[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/@abhagsain/ai-cli.svg)](https://npmjs.org/package/@abhagsain/ai-cli)
[![Downloads/week](https://img.shields.io/npm/dw/@abhagsain/ai-cli.svg)](https://npmjs.org/package/@abhagsain/ai-cli)

Usage 
```
$ ai ask "Check process running on port"
```


Auto generated documentation

<!-- toc -->
* [GPT3 Powered CLI](#gpt3-powered-cli)
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->

# Usage

<!-- usage -->
```sh-session
$ npm install -g @abhagsain/ai-cli
$ ai COMMAND
running command...
$ ai (--version)
@abhagsain/ai-cli/1.0.1-0 darwin-x64 node-v14.18.3
$ ai --help [COMMAND]
USAGE
  $ ai COMMAND
...
```
<!-- usagestop -->

# Commands

<!-- commands -->
* [`ai ask [question]`](#ai-ask-question)
* [`ai auth`](#ai-auth)
* [`ai help [COMMAND]`](#ai-help-command)

## `ai ask [question]`

Ask question to GPT3 from your terminal

```
USAGE
  $ ai ask [question]

ARGUMENTS
  QUESTION  Your question

DESCRIPTION
  Ask question to GPT3 from your terminal

EXAMPLES
  $ ai ask "Check running process on port 3000"
```

_See code: [dist/commands/ask.ts](https://github.com/abhagsain/ai-cli/blob/v1.0.1-0/dist/commands/ask.ts)_

## `ai auth`

Update existing or add new OpenAI API Key

```
USAGE
  $ ai auth

DESCRIPTION
  Update existing or add new OpenAI API Key

EXAMPLES
  $ ai auth (Follow the prompt)
```

_See code: [dist/commands/auth.ts](https://github.com/abhagsain/ai-cli/blob/v1.0.1-0/dist/commands/auth.ts)_

## `ai help [COMMAND]`

Display help for ai.

```
USAGE
  $ ai help [COMMAND] [-n]

ARGUMENTS
  COMMAND  Command to show help for.

FLAGS
  -n, --nested-commands  Include all nested commands in the output.

DESCRIPTION
  Display help for ai.
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v5.1.17/src/commands/help.ts)_
<!-- commandsstop -->
