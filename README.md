# [M365Bass.github.io](https://M365Bass.github.io)

# Test H1 - take 2

Minimalist blogging at its finest

[2021-04-22 (Alias for nvm-windows) Quickly switch node version without having to memorise the exact node version](posts/2021-04-22.md)

[2021-04-13 (Add CSS to modern SharePoint page) But just because you can doesn't mean you should..](posts/2021-04-13.md)

[2021-04-09 (Google is your friend) What I searched for (9 April 2021)](posts/2021-04-09.md)

[2021-04-06 (Desk setup - Bose NC700) How to use the mute function](posts/2021-04-06.md)

[2021-04-02 (Custom themes for Github pages) How to link a remote theme with minimal effort](posts/2021-04-02.md)

[2021-04-01 (Not April Fool's) Turn off the Azure AD “Stay signed in?” page](posts/2021-04-01.md)

[2021-03-31 (Git - rewrite history) Squash commits on remote](posts/2021-03-31_2.md)

[2021-03-31 (Azure Bot - connectivity issues) Error sending this message to your bot: HTTP status code Forbidden](posts/2021-03-31_1.md)

## Minis

[April minis](minis/2021-04.md)

[March minis](minis/2021-03.md)

### Dev setup

#### Azure VM

1. Standard DS11 v2 (2 vcpus, 14 GiB memory) - additional data disk (16GB), now removed but not deleted
   - To save on cost, did a second one with the same DS11 but this time went with a Standard SSD and a spot instance. Performance is noticeably much worse from the get go - will keep monitoring to see if that's the spot instance varying on performance depending on availability or if Standard and Premium SSDs matter that much - it's a windows 10 preview but I doubt that's the culprit, everything else is the same.
1. Download and install nvm for windows
1. Install node 10 (SP Dev) and latest (General use inc. Azure)
1. `npm install gulp yo @microsoft/generator-sharepoint --global`
1. Install browsers, git and vscode
1. Git verified (gpg)

#### Fresh Dev Tenant

1. Change AAD login background and logo
1. Disable `Security defaults` and replace with Conditional Access policies
