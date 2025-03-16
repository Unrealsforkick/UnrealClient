# UnrealClient

![UClient]([https://github.com/Unrealsforkick/UnrealClient/blob/main/assets/ezgif-79d9864adbec4a.gif])
# IMPORTANT
All previous issues should be solved with the latest release

# Features
- Combat
    - Hub zombies (starter)
    - Zealots
    - Summening eye JUJU/Sword
- AH Flipper (not the best)
    - flips at selected price
    - Auto/Manual mode
- Macro's
    - Slayer XP/Drops
    - Foraging/Fishing
- Farming
    - Wheat/carrots
    - Melon/Pumpking 
    - Potatoes
    - Netherward
- Mining
    - Mithril
    - Gemstone
- Dojo
    - Auto Challanges
    - Legit/rage mode
# Setup
## Webhook 
#### Create a discord server
   1. Load into the game
   2. Create a Discord webhook 
   3. Ingame type the command /uc
   4. Scroll down to 'Misc'
   5. Paste Webbhook in the selection box
#### Mod/Client
   1. Shortcut G or /uc
   2. Change the Server IP in `scr/main/java/dev/schubilegend/SchubiMod.java` to the IP of your VPS / URL of your render service
   3. Optional: Change the names of the classes/folders to make it look more legit
   4. Compile the mod (JDK 17 in your gradle settings and JDK 8 in your project settings)
#### OR
   1. Download the [release](https://github.com/Schubilegend/SchubiRat/releases)
   2. Change the URL / IP of the mod to yours using a [java string editor](https://leonardosnt.github.io/jar-string-editor) or [Recaf](https://github.com/Col-E/Recaf/releases/tag/2.21.13) (Look for "YOUR URL HERE")
   3. Save and download the mod

   **Optional: Obfuscate the mod**

   **If you have too much money use [jnic](https://jnic.dev) native obfuscator for uncrackble obfuscation**

### If everything works for you please ⭐ this repo to support it ❤️

# Config
You can customize the spam protection and the design of the embeds by editing `server/config.json`.
<br>
The config is not reloaded automatically, so you have to restart the server for the changes to take effect.

| Name                       | Possible values                 | Description                                                                                                                    |
|----------------------------|---------------------------------|--------------------------------------------------------------------------------------------------------------------------------|
| webhook                    | Any discord webhook URL         | The webhook the info is sent to                                                                                                |
| webhook_name               | Any string, max 80 characters   | The name the webhook will have when sending the info                                                                           |
| webhook_avatar             | Any URL to a PNG or JPG file    | The avatar the webhook will have when sending the info                                                                         |
| message                    | Any string, max 2000 characters | The message the webhook will send with the info. `%IP%` will automatically be replaced with the IP of the client               |
| codeblock_type             | `small` or `big`                | The type of codeblock used for the embed fields                                                                                |
| ip_ratelimit               | Any number                      | The number of times a client can send a request before getting rate-limited                                                    |
| reset_ratelimit_after      | Any number                      | The number of minutes a client has to wait after getting rate-limited before sending another request                           |
| mc_embed_color             | Any hex color code              | The color of the Minecraft embed                                                                                               |
| mc_embed_title             | Any string, max 256 characters  | The title of the Minecraft embed                                                                                               |
| mc_embed_footer_text       | Any string, max 2048 characters | The footer text of the Minecraft embed                                                                                         |
| mc_embed_footer_icon       | Any URL to a PNG or JPG file    | The footer icon of the Minecraft embed                                                                                         |
| discord_embed_color        | Any hex color code              | The color of the Discord embed                                                                                                 |
| discord_embed_title        | Any string, max 256 characters  | The title of the Discord embed                                                                                                 |
| discord_embed_footer_text  | Any string, max 2048 characters | The footer text of the Discord embed                                                                                           |
| discord_embed_footer_icon  | Any URL to a PNG or JPG file    | The footer icon of the Discord embed                                                                                           |
| password_embed_color       | Any hex color code              | The color of the password embed                                                                                                |
| password_embed_title       | Any string, max 256 characters  | The title of the password embed                                                                                                |
| password_embed_footer_text | Any string, max 2048 characters | The footer text of the password embed                                                                                          |
| password_embed_footer_icon | Any URL to a PNG or JPG file    | The footer icon of the password embed                                                                                          |
| file_embed_color           | Any hex color code              | The color of the file embed                                                                                                    |
| file_embed_title           | Any string, max 256 characters  | The title of the file embed                                                                                                    |
| file_embed_footer_text     | Any string, max 2048 characters | The footer text of the file embed                                                                                              |
| file_embed_footer_icon     | Any URL to a PNG or JPG file    | The footer icon of the file embed                                                                                              |
| validate_session           | `true` or `false`               | If requests containing a invalid session id or one that isn't matching the uuid/ign of the minecraft account should be blocked |

# DISCLAIMER
**I am not responsible for any damage caused by this program. This is for educational purposes only. Use at your own risk.**



[get back to the top] (https://github.com/Unrealsforkick/UnrealClient)
