# macOS Downloader

Download any macOS Release without needing a Mac! Download in DMG, ISO, or ZIP File Format.

## Warning ⚠️

**As Apple has deprecated `seedutil`, macOS `Beta` Versions from macOS Sonoma 14 will no longer be available in `seedutil` and `seedutil` will no longer be included in macOS Ventura 13.5.1+. You can use this tool but you can only download ISO, DMG, and ZIP files of macOS High Sierra to macOS Ventura 13.5 Beta and any 
other stable versions.**

## Notice ⚠️

**As a precaution, we request you to not fork this repository to prevent the violation of GitHub's Terms of Service. As an alternative, follow the new steps below:**

## Steps to Start...

- Click on the `Use This Template` button available above the commit status.
- Click on `Create a new repository`.
- Enter the Repository Name as `Download-macOS`.
- Click on the `Create repository from template` button.
- Go to the **Actions** Tab.
- Select the desired macOS Format you want to generate from the sidebar.
- Click on **Run workflow**. Select the desired options and Click on **Run workflow**.

## Known Issues

- Sometimes you may be getting an error saying `Update Not Found`. Workaround is... nothing! We've now added a feature to re-run the job automatically until it succeeds.
- Sometimes you may be trying to extract the Downloaded ZIP File but it will say 'Corrupted'. Workaround is to re-run the Job and it should work. No Possible Fixes are Available.
