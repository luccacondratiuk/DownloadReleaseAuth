# DL-Release
___
## [EN]
This script downloads an asset from the latest or specific Github release of a private repo.
Feel free to modify. Forked from [Maxim - gh-dl-release](https://gist.github.com/maxim/6e15aa45ba010ab030c4)

### Prerequisites
- curl
- wget
- jq

### Usage 

Set the variables inside: TOKEN, REPO, FILE
<br>
<br>

Give execution permission: <br>
`chmod +x dl-release.sh`
<br>
<br>

Execute the script passing the version as an argument

`dl-release 2.1.1 my_app.tar.gz` <br>
 to download latest version: <br>
`gh-dl-release latest latest.tar.gz`

<br>
<br>
If your version/tag doesn't match, the script will exit with error.

___

