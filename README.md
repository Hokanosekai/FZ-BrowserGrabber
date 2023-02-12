# BrowserGrabber

BrowserGrabber is a tool to grab credentials from browsers for an usage with a FlipperZero.

## Supported Browsers

- Chrome
- Firefox
- Edge
- Brave
- Opera

## Usage

1. Have a domain name and hosting + a FlipperZero
2. Clone this repo
3. Create a Discord webhook then replace the url in the [uploader.ps1](uploader.ps1) file
4. Update the url to download the [uploader.ps1](uploader.ps1) file in the [BrowserGrabber.txt](BrowserGrabber.txt)) file
5. Update the url to download the [payload.exe](payload.exe) file in the [uploader.ps1](uploader.ps1) file
6. Place the [BrowserGrabber.txt](BrowserGrabber.txt) file in your FlipperZero in the folder `badusb`
7. Host the [payload.exe](payload.exe) and the [uploader.ps1](uploader.ps1) file on your hosting
8. Check the availability of the files by your domain name
9. Launch the attack

## Data Exfiltrated

- Chrome
  - Cookies
  - Passwords
  - History
- Firefox
  - Cookies
  - Passwords
  - History
- Edge
  - Cookies
  - Passwords
  - History
- Brave
  - Cookies
  - Passwords
  - History
- Opera
  - Cookies
  - Passwords
  - History

## Disclaimer

This tool is for educational purposes only. I am not responsible for any misuse or damage caused by this tool.

## Credits

- [**s4dic**](https://github.com/s4dic) for the idea
- [**Zyksa**](https://github.com/Zyksa) for the FlipperZero

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Authors

- [**Zyksa**](https://github.com/Zyksa) - *Initial work*
- [**Hokanosekai**](https://github.com/Hokanosekai) - *Initial work*

## Acknowledgments

- [FlipperZero/BadUsb/DiscordGrabber](https://github.com/s4dic/FlipperZero/tree/main/BadUsb/DiscordGrabber)