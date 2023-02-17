# the3s
The 3S! Safe Smoothie Solution is a GUI for the safe network! made with tauri (rust + html/css/vanilla js)

I introduce The 3S! Safe Smoothie Solution!

your one stop for all your safe needs

currently: prerelease v0.0.8 try it now: Releases · smoothoperatorgr/the3s (github.com)

Implimented (for windows now):

Setup
latest safe installation through maidsafe script
delete safe.exe
latest safe node installation through safe node install
delete sn_node.exe
it pulls the “known” testnet config URLs from a gist and you can select it in the drop down menu and add it in the safe networks (if the testnets are not online it will fail)
add your custom testnet by proviging testnet name and config URL
check safe version
check node version
show safe networks
clear output of the output box
Setup Local Baby Fleming
check running local-baby-fleming (it shows how many nodes there are
kill local baby fleming (safe node killall)
clean up local baby fleming (rm ~/.safe/cli/config / rm -f ~/.safe/network_contacts / rm -f ~/.safe/node/baby-fleming-nodes )
run local baby fleming (11 nodes / safe node run-baby-fleming)
for the rest of the commands open a powershell window and use ~/.safe/cli/safe.exe <safe commands> or add to PATH variable the folder ~/.safe/cli/ and run commands with safe.exe <safe commands>

checks for updates when launching The 3S! and by clicking yes it initiates the update process and relaunches The 3S!
WIP:

implement all safe commands
