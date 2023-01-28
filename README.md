# jackett-openrc


A jackett openrc init script with some extra doodads

**WARNING:** Everything in this repository comes with ABSOLUTELY NO WARRANTY, and I will take NO RESPONSIBILITY for the misuse of the files provided here. They are provided as is for educational purposes. Any and all misuse will be entirely your responsibility, in addition to the consequences that may ensue. You have been warned.

## Installation
***Note:** This installation guide assumes you have already installed jackett, preferably through the AUR*

Clone the jackett-openrc repository

```bash
git clone "https://github.com/deltainium/jackett-openrc.git"
```
Change into your newly cloned directory
```bash
cd jackett-openrc/
```
Copy the .initd file to your OpenRC init.d directory
```bash
sudo cp jackett.initd /etc/init.d/
```
Enable the script through OpenRC
```bash
sudo rc-update add jackett.initd
```
**(Optional)** If you want to start jackett without having to restart your computer, start the service through OpenRC manually
```bash
sudo rc-service jackett.initd start
```


## License

[MIT](https://choosealicense.com/licenses/mit/)
