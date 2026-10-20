## 💜 What's new in v1.3.2

- Renamed the mod to **IridiumX Client** throughout the interface, window title, mod metadata, README, and LICENSE.
- New build filenames: **`iridiumx-client-{mod_ver}+{mc_ver}.jar`**.
- Added the purple crystal logo as the Minecraft window icon.
- Updated the window title to **`Minecraft* {version} - IridiumX Client`**.
- Added **Discord Rich Presence from game launch**, including the main menu:
  - **IridiumX Client**
  - **User  : {user_ign}**
  - **Version {mc_ver} • {mod_ver}**
- Fixed Windows Discord IPC reads blocking activity updates; added incremental frame parsing, reconnection, refreshes, and acknowledgement logs.
- Retained **OP-only access** for administration and log capture. Cosmetic Rich Presence can display without OP.
- Included the **Custom Use-Only License** in every JAR: free to use; modification and redistribution require written permission, subject to the full license.

**Minecraft:** 1.21.11 · 26.1 · 26.1.1 · 26.1.2 · 26.2  
**Requires:** Fabric Loader 0.19.5+ and matching Fabric API. Windows desktop Discord is needed for Rich Presence.

Install **one matching JAR** and remove the previous panel/client JAR before restarting Minecraft. Existing settings and history paths are preserved.

Unofficial community project by **_0xi1**.
