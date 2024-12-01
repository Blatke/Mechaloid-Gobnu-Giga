# Mechaloid-Gobnu-Giga
A HS2 / AI-Shoujo Studio Item.

![AI_2024-12-01-23-33-20-828](https://github.com/user-attachments/assets/6b0645e8-b5f8-4214-91b2-d8e6a6af8776)

## How to Use
Download both the .zipmod and .png files for the latest version from the [Release](https://github.com/Blatke/Mechaloid-Gobnu-Giga/releases) page. Drag and drop the .png file, which is a scene card, into your **\UserData\Studio\scene** folder, and the .zipmod file into your **\mods\** folder.

In Studio, open or import this .png file of scene card. Then you can see in the scene there are an item of Giga the monster under which a character is also placed. The monster is linked to the character by NodeConstraints. Make poses to the character, so the monster follows. It means you don't need to rotate each FK node of the monster to get a pose, instead you can manipulate the character by IK to indirectly control the monster.

![AI_2024-12-01-23-40-41-475](https://github.com/user-attachments/assets/32b72049-54f9-44ad-bedb-6155eaf3ddd2)

![AI_2024-12-01-23-41-11-858](https://github.com/user-attachments/assets/46eac551-26fa-4313-9072-02531317ac44)

![AI_2024-12-01-23-41-42-042](https://github.com/user-attachments/assets/852c6849-5f9e-4b97-8904-baa78106c521)

> [!NOTE]
> To make this sort of link possible, you must make sure that NodeConstraints (https://www.patreon.com/posts/hs-kk-ai-hs2-1-2-40763065) the plugin has been installed and functional in your Studio. 
