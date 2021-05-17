# History

- 2021-05-17:
  1. forked from github.com/moriakaice/bitburner
  2. added install.ns into the repostory

# Bitburner scripts collection

Welcome to my log of [Bitburner](https://danielyxie.github.io/bitburner/)
scripts. They are written using the in-game language of NetscriptJS, which is a
mutation of Javascript.

If you want to play the game itself - click on the name above.

## Requirements

The script has been modified to be able to start on 8 GB (the default starting RAM for a player) on the `home` server. Obviously, when you expand the memory available, you'll get extra perks - being able to buy and manage player-owned servers, as well as using spare RAM to do actions.

The script can be slow to get going, but it'll get there eventually. Getting access to more port hackers will improve the performance.

## Instalation

1. Create a new script called `start.ns` by issuing the following command: `nano start.ns`. Make sure you're on your home server if you're not (you can quickly go home by running `home` in the console).
2. Write into console: `nano install.ns`
3. Delete existing text (Ctrl-A, DEL)
4. Paste the following contents of [install.ns](https://raw.githubusercontent.com/holgerschurig/bitburner-scripts/master/src/install.ns) into the editor (Ctrl-C in browser, Ctrl-V in Bitburner's nano)
5. Exit nano (Ctrl-B)
6. Run the installer: `run install.ns`
