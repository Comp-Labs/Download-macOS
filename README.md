# macOS Downloader

Download any macOS Release without needing a Mac! Download in DMG, ISO, or ZIP File Format.

## Warning ⚠️

**Some Beta Versions may not work because Apple has deprecated `seedutil`. However, stable versions will work normally like before.**

## Notice ⚠️

**As a precaution, we request you to not fork this repository to prevent the violation of GitHub's Terms of Service. As an alternative, follow the new steps as stated below:**

## Steps to Start

- Click the `Use This Template` button above the commit status.
- Click on `Create a new repository`.
- Enter the Repository Name as `Download-macOS`.
- Click on the `Create Repository` button.
- Before running, modify [this line](https://github.com/Comp-Labs/Download-macOS/blob/a4e8e6849d7bd9563638d46e6db843e109e8156c/.github/workflows/generate-installer.yml#L36) to your repository link to prevent any errors.
- Go to the **Actions** Tab.
- Select `Generate macOS Installer`
- Click on **Run workflow**. Select the desired options and click on **Run workflow**.

## Older macOS Installers

### Older than Monterey

On updating the GitHub Actions Runner to `macos-latest (macos-14)`, versions older than Monterey are on longer available.

### Older than High Sierra

macOS Installers older than High Sierra can be downloaded through the links below:

- [Sierra 10.12](http://updates-http.cdn-apple.com/2019/cert/061-39476-20191023-48f365f4-0015-4c41-9f44-39d3d2aca067/InstallOS.dmg)
- [EI Captain 10.11](http://updates-http.cdn-apple.com/2019/cert/061-41424-20191024-218af9ec-cf50-4516-9011-228c78eda3d2/InstallMacOSX.dmg)
- [Yosemite 10.10](http://updates-http.cdn-apple.com/2019/cert/061-41343-20191023-02465f92-3ab5-4c92-bfe2-b725447a070d/InstallMacOSX.dmg)
- [Mountain Lion 10.8](https://updates.cdn-apple.com/2021/macos/031-0627-20210614-90D11F33-1A65-42DD-BBEA-E1D9F43A6B3F/InstallMacOSX.dmg)
- [Lion 10.7](https://updates.cdn-apple.com/2021/macos/041-7683-20210614-E610947E-C7CE-46EB-8860-D26D71F0D3EA/InstallMacOSX.dmg)

In case any of the links don't work, try going [here](https://support.apple.com/en-in/102662#browser) and download them using a Safari browser.

## Known Issues

- Sometimes you may get an error saying `Update Not Found`. The workaround is nothing but to try again.
- Sometimes you may get an error saying `hdiutil: couldn't eject "disk2" - Resource busy`. Workaround is nothing but to try again
- Sometimes you may be trying to extract the Downloaded ZIP File but it will say 'Corrupted'. Workaround is to re-run the Job and it should work. No Possible Fixes are Available.

## To-Do

- Add Option for user to enter versions manually
