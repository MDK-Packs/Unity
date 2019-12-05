# Unity
This repo frames the Unity as a CMSIS-PACK (upstream: https://github.com/ThrowTheSwitch/Unity)

# Instructions
1) open a bash compatible shell
2) clone repository: git clone https://github.com/MDK-Packs/Unity.git
3) run ./get_upstream.sh
4) run ./add_merge.sh to copy files from contributions to 'local' directory

a) Creating the CMSIS pack:
   1) run ./gen_pack.sh
   2) install the pack created in ./pack directory (e.g. double click on the pack file)

b) Making changes to the CMSIS pack:  
   You can develop and extend this pack further by contributing via GitHub:  
   https://github.com/MDK-Packs/Unity  
   All contributions shall be placed in either:  
   i)  contributions/add (additional content)  
   ii) contributions/merge (changed content)  
   To update your local pack content run ./add_merge.sh.  
   You can add the .../local/Arm-Packs.Unity.pdsc to the list of local repositories in the PackInstaller.  
   This way you avoid to create and install a new pack after modifications.
