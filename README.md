# My Own Dmenu Setup
The only reason having this repo is for my own convenience. Credits to all those wonderful people from [Suckless](https://suckless.org).

## Patches Applied
* dmenu-border-4.9.diff
* dmenu-caseinsensitive-5.0.diff
* dmenu-center-4.8.diff
* dmenu-highpriority-4.9.diff
* dmenu-numbers-4.9.diff
* dmenu-rejectnomatch-4.7.diff
* dmenu-scroll-20180607-a314412.diff
### Grid
* dmenu-grid-4.9.diff
* dmenu-gridnav-5.0.diff
### Fuzzy
* dmenu-fuzzymatch-4.9.diff
* dmenu-fuzzyhighlight-4.9.diff
> In **dmenu.c** change `if (*highlight == text[i]) {` into `if (!fstrncmp(&(*highlight), &text[i], 1)) {` to support case-insensitive feature.
