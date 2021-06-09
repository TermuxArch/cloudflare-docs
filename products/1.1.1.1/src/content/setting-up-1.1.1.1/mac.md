---
pcx-content-type: how-to
---

import CaptivePortals from "../_partials/_captive-portals.md"

# macOS

<StreamVideo id="b95943849d53350130ba22d039fa6faf"/>

1. Go to **System Preferences**. You can find it by pressing <kbd>Command</kbd> + <kbd>Space</kbd> on your keyboard and typing `System Preferences`.
1. Click on the **Network** icon.
1. Click **Advanced**.
1. Select the **DNS** tab. Remove any IP addresses that may be already listed and in their place add:

    ```txt
    1.1.1.1
    1.0.0.1
    2606:4700:4700::1111
    2606:4700:4700::1001
    ```

1. Click **OK** > **Apply**.

<CaptivePortals/>