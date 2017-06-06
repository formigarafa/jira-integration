# Jira Integration

Jira Command line client used to drive jira REST api.

## Usage:
```
jira-cli <command> [options]
Commands:
  jira-cli filter <filter_id>                             # print filtered issues
  jira-cli filters                                        # print current user existing filters
  jira-cli help [COMMAND]                                 # Describe available commands or one specific command
  jira-cli issue <issue_id>                               # print information about specified issue
  jira-cli issue_transitions <issue_id>                   # list available transitions for specified issue
  jira-cli myself                                         # print print information about current user
  jira-cli show_filter                                    # print information about the informed filter
  jira-cli transition <issue_id> <transition id or name>  # transition a issue to another state

Options:
  [--format=FORMAT]  # output format for query commands: json, yaml, kv or tp
                     # Default: kv
```

## Installation:

clone repository
bundle install
edit config/environments.yml
add it to your PATH.

## Notes:
Still in development: but it will be finished very soon.
Expect change in the `issue` command params and output of all commands.
