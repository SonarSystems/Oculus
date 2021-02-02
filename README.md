# Oculus

## Install Doom3Quest On Linux

### Install Doom 3 On Steam

echo '"AppState" { "AppID" "9050" "Universe" "1" "installdir" "DOOM 3" "StateFlags" "1026" }' > "${HOME}/.steam/steamapps/appmanifest_9050.acf"

## Install Doom3Quest On Mac

### Install Doom 3 On Steam

echo '"AppState" { "AppID" "70" "Universe" "1" "installdir" "HALF-LIFE" "StateFlags" "1026" }' > "${HOME}/Library/Application Support/Steam/steamapps/appmanifest_70.acf"

mv "${HOME}/Library/Application Support/Steam/steamapps//common/HALF-LIFE" "${HOME}/Documents/"; rm "${HOME}/Library/Application Support/Steam/steamapps/appmanifest_70.acf"
