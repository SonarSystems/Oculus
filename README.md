# Oculus

## Install Doom3Quest On Linux

### Install Doom 3 On Steam

echo '"AppState" { "AppID" "9050" "Universe" "1" "installdir" "DOOM 3" "StateFlags" "1026" }' > "${HOME}/.steam/steamapps/appmanifest_9050.acf"

## Install Doom3Quest On Mac

### Install Doom 3 On Steam

echo '"AppState" { "AppID" "9050" "Universe" "1" "installdir" "DOOM 3" "StateFlags" "1026" }' > "${HOME}/Library/Application Support/Steam/steamapps/appmanifest_9050.acf"

mv "${HOME}/Library/Application Support/Steam/steamapps//common/DOOM 3" "${HOME}/Documents/"; rm "${HOME}/Library/Application Support/Steam/steamapps/appmanifest_9050.acf"

## Install Lambda1VR On Mac

### Install Half-Life On Steam

echo '"AppState" { "AppID" "10" "Universe" "1" "installdir" "HALF-LIFE" "StateFlags" "1026" }' > "${HOME}/Library/Application Support/Steam/steamapps/appmanifest_10.acf"

mv "${HOME}/Library/Application Support/Steam/steamapps//common/HALF-LIFE" "${HOME}/Documents/"; rm "${HOME}/Library/Application Support/Steam/steamapps/appmanifest_10.acf"
