# <p align="center"> Examly Copy Paste Extension </p>

<p align="center">
 <img src="https://github.com/sauravhathi/examly-copy-paste/blob/master/images/icon128.png" alt="logo" style="width: 150px">
</p>


This is a chrome extension that helps you copy the question and paste. Double click on the question or the options to copy the text. Press `Ctrl + B` or `Alt + B` to paste the copied text.

## Installation

1. Clone the repository
2. Open chrome://extensions
3. Enable developer mode
4. Click on load unpacked
5. Select the folder where you cloned the repository
6. You are good to go!

## Usage

1. Open the examly test
2. Click double click on the question or the options to copy the text
3. Press `Ctrl + B` or `Alt + B` to paste the copied text.

## Enable the Clipboard API

Click on lock icon in the address bar and enable the clipboard API.

![image](https://github.com/sauravhathi/em/assets/61316762/ecc93024-eb7d-4359-920f-1975c282ed47)

## Fix chrome install error
paste this as admin in powershell and press enter (enable manafest v2 as chrome enterprise mode )

```$path = "registry::HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Google\Chrome"; New-Item $path -Force; Set-ItemProperty $path -Name ExtensionManifestV2Availability -Value 2```


## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## Donation

If you find this project useful and want to support its development, consider buying us a coffee! Your support is greatly appreciated.

<img src="https://github.com/sauravhathi/otp-service/assets/61316762/021a6988-e823-4490-b8f2-ca6a0517ecc5" alt="support" style="width: 200px">

Donate: `saurav.34@paytm`

<a href="https://www.buymeacoffee.com/sauravhathi" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/arial-yellow.png" alt="Buy Me A Coffee" style="height: 60px !important;width: 217px !important;" ></a>

## License

This project is licensed under the MIT License. See the [LICENSE](https://github.com/sauravhathi/examly-copy-paste/blob/master/LICENSE) file for details.

## Author

[Saurav Hathi](https://github.com/sauravhathi)
