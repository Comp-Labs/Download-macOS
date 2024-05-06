# macOS Downloader

Download any macOS Release without needing a Mac! Download in DMG, ISO, or ZIP File Format.

## Warning ⚠️

**Some Beta Versions may not work because Apple has deprecated `seedutil`. However, stable versions will work normally like before.**

**Versions older than Big Sur cannot be downloaded because Apple discontinued them. We'll find a fix for it soon.**

## Notice ⚠️

**As a precaution, we request you not to fork this repository to prevent the violation of GitHub's Terms of Service. As an alternative, follow the new steps as stated below:**

## Steps to Start...

- Click on the `Use This Template` button available above the commit status.
- Click on `Create a new repository`.
- Enter the Repository Name as `Download-macOS`.
- Click on the `Create repository` button.
- Before running, modify [this line](https://github.com/Comp-Labs/Download-macOS/blob/a4e8e6849d7bd9563638d46e6db843e109e8156c/.github/workflows/generate-installer.yml#L36) to your own repository link to prevent any error.
- Go to the **Actions** Tab.
- Select `Generate macOS Installer`
- Click on **Run workflow**. Select the desired options and click on **Run workflow**.

## Known Issues

- Sometimes you may be getting an error saying `Update Not Found`. The workaround is nothing but to try again.
- Sometimes you may be getting an error saying `hdiutil: couldn't eject "disk2" - Resource busy`. Workaround is nothing but to try again
- Sometimes you may be trying to extract the Downloaded ZIP File but it will say 'Corrupted'. Workaround is to re-run the Job and it should work. No Possible Fixes are Available.
