# Screen Host

## Situation
updating my ubuntu 24 lts to 26 lts remotely. the ssh connection is failed mid update.
tried ssh using port 22/1022 failed. Somehow my homelab stack still accessible.
ask gemini if it's possible to access screen on the host OS. Because ubuntu use screen when do-release-upgrade.

the update process actually stalled and waiting for user input. but i don't know how to access it remotely
since the ssh is dead.

use this compose file to access the host process then reattach screen then continue the upgrade process.
