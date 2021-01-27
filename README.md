# My Own Dmenu Setup
The only reason having this repo is for my own convenience. Credits to all those wonderful people from [Suckless](https://suckless.org).

## Patches Applied
* dmenu-border-4.9.diff
* dmenu-caseinsensitive-5.0.diff
* dmenu-center-4.8.diff
* dmenu-grid-4.9.diff
* 
### Fuzzy
* dmenu-fuzzymatch-4.9.diff
* dmenu-fuzzyhighlight-4.9.diff
> In **dmenu.c** change `if (*highlight == text[i]) {` into `if (!fstrncmp(&(*highlight), &text[i], 1)) {` to support case-insensitive feature.
