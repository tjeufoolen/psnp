# psnppgl

My personal collection of game lists for [PSNProfiles](https://psnprofiles.com), made for use with the PSNP+ browser extension.

## What is PSNP+?

PSNP+ is a browser extension that adds extra features to PSNProfiles, the trophy tracking site for PlayStation. It runs entirely in your browser on top of the regular site, so you need the extension installed for anything in this repository to be useful.

## What are gamelists?

Gamelists are one of the PSNP+ features: custom lists of games that you manage yourself, such as a backlog, a series you want to finish, or a set of recommendations. Each game in a list keeps its trophy counts, platforms and completion rates, and a list can be sorted and set to automatically drop games once you have completed them.

A gamelist can be exported as a JSON file and imported from a URL. That is what this repository is for: every `.json` file here is a gamelist that anyone with PSNP+ can import.

## Available gamelists

| List                          | Description                     | Quick add                                                                                                                                                                                          |
| ----------------------------- | ------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [WTP](psnpp-wtp.json)         | My personal "Want to Play" list | [Add to PSNP+](https://psnprofiles.com/#profile?hash=gamelists?import=https%253A%252F%252Fraw.githubusercontent.com%252Ftjeufoolen%252Fpsnppgl%252Frefs%252Fheads%252Fmain%252Fpsnpp-wtp.json)     |
| [Cleanup](psnpp-cleanup.json) | Cleanup (DLC and/or 100%)       | [Add to PSNP+](https://psnprofiles.com/#profile?hash=gamelists?import=https%253A%252F%252Fraw.githubusercontent.com%252Ftjeufoolen%252Fpsnppgl%252Frefs%252Fheads%252Fmain%252Fpsnpp-cleanup.json) |

### WTP (Want to play)

Sorted alphabetically, and games are removed from the list once completed. It mostly consists of series I want to work through.

## Adding a gamelist

1. Install PSNP+ and sign in to PSNProfiles.
2. Click the **Add to PSNP+** link of the list you want.
3. Confirm the import on the gamelists page that opens.

You can also import manually by pasting the raw URL of a list into the import option on your gamelists page:

```
https://raw.githubusercontent.com/tjeufoolen/psnppgl/refs/heads/main/psnpp-wtp.json
```
