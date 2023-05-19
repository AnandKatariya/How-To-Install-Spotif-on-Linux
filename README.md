<p align="center"><img src="https://user-images.githubusercontent.com/73893201/219341706-2dc1f1a2-a49e-4d20-bacd-f1643ce32b26.gif" hight='400' width= '400' align='center'/>
</p>
<h1 align="center">Welcome to How to install spotify on kali linux 👋</h1>
<p>
  <img src="https://img.shields.io/badge/version-0.1-blue.svg?cacheSeconds=2592000" />
</p>
### 🏠 [Homepage](https://github.com/AnandKatariya?tab=repositories)

## Install snap on linux
```sh
sudo apt install snapd
```
## Configure debian repository
```sh
curl -sS https://download.spotify.com/debian/pubkey_7A3A762FAFD4A51F.gpg | sudo gpg --dearmor --yes -o /etc/apt/trusted.gpg.d/spotify.gpg
echo "deb http://repository.spotify.com stable non-free" | sudo tee /etc/apt/sources.list.d/spotify.list
```

## Install the Spotify client
```sh
sudo apt-get update && sudo apt-get install spotify-client
```
<h3> After installation just login it and have fun with spotify. </h3>
## Author

👤 **Anand Katariya**
* Github: [@AnandKatariya](https://github.com/AnandKatariya)

## 🤝 Contributing

Contributions, issues and feature requests are welcome!<br />Feel free to check [issues page](https://github.com/AnandKatariya/How-To-Install-Spotif-on-Linux/issues).

## Show your support

Give a ⭐️ if this project helped you! <br>
Stay tuned for more updates

