# Clean Zendesk Deleted Tickets

## Why this repo
When you have a custom view with tickets, you cannot mass delete 'closed' tickets because the checkbox for those tickets is disabled.

## How install
The `clean-zendesk-deleted-tickets` file contains a script you can install locally. 

Make sure you make the file executable: `chmod +x clean-zendesk-deleted-tickets`

## Usage
```
clean-zendesk-deleted-tickets [-g] [-h] [-s] [-u]

Arguments:
  -g  set the group where you want to clean the tickets from
  -h  show this help text
  -s  set the ZenDesk subdomain
  -u  set the username for your ZenDesk account (must have admin rights)
```


### Prerequisites
The account you will be using to do the cleaning will need admin rights on your Zendesk environment.

## Please note
This has only be tested on Ubuntu
