# Jira Integration

Jira Command line client used to drive jira REST api.

## Usage:
```
jira-cli <command> [options] [arguments]
```
- filter               print filtered issues
- filters              print current user existing filters
- issue                print information about specified issue
- issue_transitions    list available transitions for specified issue
- myself               print print information about current user
- show_filter          print information about the informed filter
- transition           transition a issue to another state

## Installation:

clone repository
bundle install
edit config/environments.yml
add it to your PATH.

## Notes:
Still in development: but it will be finished very soon.
Expect change in the `issue` command params and output of all commands.
