# wot-traaash-names-mod
This mod for World of Tanks changes names of some tanks to fit [GARBG] clan

All you have to do is to upload a `WorldOfTanks/res/text/lc_messages/gb_vehicles.mo` file from newer version into the git folder `original-translations/<version>/gb_vehicles.mo` (for example `original-translations/1.23.1.0/gb_vehicles.mo`) and then wait for about a minute or two for the GITHUB Action to patch the file.

To upload the file: 
  - Locate the `gb_vehicles.mo` file and copy it to folder named after the current version of WoT: `<WoT-version>/gb_vehicles.mo`
  - On web - go to wot-traaash-names-mod/original-translations/
  - On web - click `new file` and then drag & drop the whole folder `<WoT-version>`, write reasonable commit message ("Uploads <WoT-version> translation files")
  - Profit

Then you can find the final mod for the new version of World Of Tanks in the releases on the right side of the repository on github.com.

Another way to trigger the update is to update the `patch-translations/gb_vehicles-patch.po` file. Be aware, that only the newest patch will be produced (the latest uploaded gb_vehicles.mo file)
