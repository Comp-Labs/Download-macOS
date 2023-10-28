# macOS Downloader

Download any macOS Release without needing a Mac! Download in DMG, ISO, or ZIP File Format.

## Warning ⚠️

**Some Beta Versions may not work because Apple has deprecated `seedutil`. However, stable versions will work normally like before.**

## Notice ⚠️

**As a precaution, we request you to not fork this repository to prevent the violation of GitHub's Terms of Service. As an alternative, follow the new steps as stated below:**

## Steps to Start...

- Click on the `Use This Template` button available above the commit status.
- Click on `Create a new repository`.
- Enter the Repository Name as `Download-macOS`.
- Click on the `Create repository` button.
- Go to the **Actions** Tab.
- Select `Generate macOS Installer`
- Click on **Run workflow**. Select the desired options and click on **Run workflow**.

## Known Issues

- Sometimes you may be getting an error saying `Update Not Found`. The workaround is nothing but to try again.
- Sometimes you may be getting an error saying `hdiutil: couldn't eject "disk2" - Resource busy`. Workaround is nothing but to try again
- Sometimes you may be trying to extract the Downloaded ZIP File but it will say 'Corrupted'. Workaround is to re-run the Job and it should work. No Possible Fixes are Available.
