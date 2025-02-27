``sudo curl -fsSLo /usr/share/keyrings/mullvad-keyring.asc https://repository.mullvad.net/deb/mullvad-keyring.asc``

``echo "deb [signed-by=/usr/share/keyrings/mullvad-keyring.asc arch=$( dpkg --print-architecture )] https://repository.mullvad.net/deb/stable jammy main" | sudo tee /etc/apt/sources.list.d/mullvad.list``

``sudo apt update``

``sudo apt install mullvad-vpn``