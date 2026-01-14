SteamLibrary - steam folder

rm -rf /SteamLibrary/steamapps/compatdata/244210

# game
1 start the game using Proton 5.0-10 and let it run until it crashes

2 switch to proton 9

3 dbus-launch protontricks 244210 dotnet452 vcrun2015 d3dcompiler_47 dxvk corefonts

4 dbus-launch protontricks 244210 winecfg

add dwrite to libs

# cm
1 copy "Content Manager.exe" to game folder

2 Rename AssettoCorsa.exe to AssettoCorsa_origibal.exe and Content Manger.exe to AssettoCorsa.exe

3 link steam profile

ln -s "$HOME/.steam/root/config/loginusers.vdf" '/SteamLibrary/steamapps/compatdata/244210/pfx/drive_c/Program Files (x86)/Steam/config/loginusers.vdf'

5 prepare game folder path

Z:\SteamLibrary\steamapps\common\assettocorsa

launch game + install 7z
# csp
download 0.2.2 from of site 

from cm -> install from file -> select 0.2.2 csp ver that you download -> install -> manually unzip csp 0.2.2 and copy dwrite ONLY to game folder 

# note: 
first launch will ask for fonts content manager will provide link to download. 
