# WireSockUI

WireSockUI is an innovative user interface for the [WireSock VPN Client](https://www.wiresock.net), offering a seamless and intuitive control experience directly from the Windows system tray. This project is a transformative evolution of the original [EpexGUI](https://github.com/Epenko1337/EpexGUI), reimagined and rewritten to enhance functionality and user experience.

## AntiRKN

Для того чтобы воспользоваться обходом блокировки выберите тоннель и нажмите кнопку "ANTIRKN", тоннель автоматически запустится и будет работать.
|
To use the bypass blocking, select the tunnel and press the "ANTIRKN" button, the tunnel will automatically start and work.

## Special Acknowledgements

A heartfelt thanks to [robvanoostenrijk](https://github.com/robvanoostenrijk/WireSockUI) for his exceptional dedication and skill in rewriting the original interface of EpexGUI. His contributions have been pivotal in transforming WireSockUI into a more robust, user-friendly, and feature-rich application. Thanks to his efforts, the interface design of WireSockUI now closely aligns with the official [WireGuard for Windows](https://www.wireguard.com/install/#windows-7-81-10-11-2008r2-2012r2-2016-2019-2022) interface, offering an intuitive and familiar user experience.

### Main screen

![main-interface](https://user-images.githubusercontent.com/6480052/230771736-d467ea72-aa16-46bc-9cbd-8477dcf4c2bb.png)

The main screen shows the configured tunnel interface, peer information and tunnel state on the right-hand side.

### Edit screen

Through `add tunnel`, a new tunnel can be created from scratch or loaded from a file:

![new-profile](https://user-images.githubusercontent.com/6480052/230771804-db5494f1-198e-4238-900f-abb95f94bbac.png)

Existing tunnels can be edited by selecting the tunnel in the tunnel list and clicking `Edit`:

![edit-profile](https://user-images.githubusercontent.com/6480052/230771826-ae3cf5ee-f6d4-411c-a69c-6eb805def928.png)

WireSockUI offers syntax highlighting while creating new or editing tunnel profiles. It will validate both the format of the profile configuration in terms of sections and keys as well as the actual key values (Numbers, IP Addresses, CIDR masks).

### Process screen

You can use the `Process` button on the edit screen, to easily select a process name to insert into the profile for the WireSock AllowedApps or DisallowedApps keys.

![select-process](https://user-images.githubusercontent.com/6480052/230771894-b907c183-cdb2-48f2-8d58-03223b4c1ff8.png)

### Settings screen

Additionally WireSockUI supports a number of settings to allow it to start-up with Windows, automatically re-connect to your last active tunnel or minimize to system tray on startup. You can also open the folder where WireSockUI saves the profile configurations from here.

![settings](https://github.com/wiresock/WireSockUI/assets/20592735/5e389ab5-4e80-42f3-8b4d-1f92285f69c2)


------

New builds are automatically generated by GitHub Actions and made available as a release. The workflow logs can be viewed publicly, allowing potential applications to validate both the source code and the resulting artifact(s).
