# Clean Zendesk Closed Tickets

## Why this repo
When you have a custom view with tickets, you cannot mass delete 'closed' tickets because the checkbox for those tickets is disabled.

## How install
The `clean-zendesk-closed-tickets` file contains a script you can install locally. 

Make sure you make the file executable: `chmod +x clean-zendesk-closed-tickets`

## Usage
```
clean-zendesk-closed-tickets [-g] [-h] [-s] [-u]

Arguments:
  -g  set the group where you want to clean the tickets from
  -h  show this help text
  -s  set the ZenDesk subdomain
  -u  set the username for your ZenDesk account (must have admin rights)
```


### Prerequisites
1. The account you will be using to do the cleaning will need admin rights on your Zendesk environment.
2. You must have `jq` installed for processing the `json` response, see [https://stedolan.github.io/jq/](https://stedolan.github.io/jq/).

## Please note
This has only be tested on Ubuntu
