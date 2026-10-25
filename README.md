# Mortality Setup

Download **Mortality-Headset-Setup.apk** from [the latest release](https://github.com/offset1235/airsoft-mortality/releases/latest).

Setup is a separate app and stays installed alongside Airsoft Allstars. It installs the companion-enabled game, then transfers verified assets without root. Existing matching assets are reused. Allow approximately 10 GB free for a fresh installation. Approve Android installation prompts and return to Setup to finish if needed.

**Game logs** provides Refresh, Copy and Save for the game's own diagnostics. Save writes to Downloads/Mortality. System and separate Meta-service logs are excluded. No broad device-log permission is requested. A same-signature provider in the modified game handles assets and logs.

The official game and older builds do not expose this companion interface. The official store build has a different signing certificate; Android cannot update it directly with the modified game. Uninstalling an app can remove saves.

This release adds diagnostics; it does not bypass or resolve Meta authentication checks. Inspect logs before sharing them.
