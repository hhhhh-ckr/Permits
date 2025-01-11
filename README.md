![Permits Title Art](https://cdn.modrinth.com/data/cached_images/e02c0305c5d8b549698391b47def637e790eec56.png)

Inspired by [HermitCraft](https://hermitcraft.com/), designed to have permits for your shops or roleplaying.

The main idea is that players need permits to open shops and cannot open shops for items, blocks that they do not have permits for.

# How to use?
It can be used in **two ways**, with **Vanilla Minecraft** method or **CIT (Custom Item Texture)** method

<details>
  <summary>Vanilla Minecraft method</summary>

  You need to change the `custom_model_data` value of the Paper <a href="https://minecraft.wiki/w/Paper" target="_blank"><img src="https://cdn.modrinth.com/data/cached_images/e9cb2f47970f2b77c83258586fc8be9858773250.png" alt="Minecraft Paper" width="20"></a> item according to the values ​​in the list below.

  | Rank →<br>Type ↓  	|     Blank     	|    Regular    	|      Iron     	|     Gold    	|    Diamond    	|     Joker     	|
|:----------:	|:-------------:	|:-------------:	|:-------------:	|:-------------:	|:-------------:	|:-------------:	|
|   Default  	|  <a href="https://cdn.modrinth.com/data/cached_images/f2f019ad56231eaa82f2383906180bc87defe150.png" target="_blank"><img src="https://cdn.modrinth.com/data/cached_images/f2f019ad56231eaa82f2383906180bc87defe150.png" alt="Default Blank Permit" width="48"></a><br>770 	|    <a href="https://cdn.modrinth.com/data/cached_images/5a73d6883886055da1160438925068b3b894fa42.png" target="_blank"><img src="https://cdn.modrinth.com/data/cached_images/5a73d6883886055da1160438925068b3b894fa42.png" alt="Default Regular Permit" width="48"></a><br>771   	|    <a href="https://cdn.modrinth.com/data/cached_images/527fed0647cbada3e78922e42370b29cc9d031e0.png" target="_blank"><img src="https://cdn.modrinth.com/data/cached_images/527fed0647cbada3e78922e42370b29cc9d031e0.png" alt="Default Iron Permit" width="48"></a><br>772   	|  <a href="https://cdn.modrinth.com/data/cached_images/301507ae622138df6d6902a932ce480c4a4ab872.png" target="_blank"><img src="https://cdn.modrinth.com/data/cached_images/301507ae622138df6d6902a932ce480c4a4ab872.png" alt="Default Gold Permit" width="48"></a><br>773 	|  <a href="https://cdn.modrinth.com/data/cached_images/1a292c97ca143c02ef63765ae64f826ee805dbd8.png" target="_blank"><img src="https://cdn.modrinth.com/data/cached_images/1a292c97ca143c02ef63765ae64f826ee805dbd8.png" alt="Default Diamond Permit" width="48"></a><br>774 	|  <a href="https://cdn.modrinth.com/data/cached_images/1627c510eaeaa37f97b6a1ee79dcf30f6e2a42fb.png" target="_blank"><img src="https://cdn.modrinth.com/data/cached_images/1627c510eaeaa37f97b6a1ee79dcf30f6e2a42fb.png" alt="Default Joker Permit" width="48"></a><br>775 	|
|   Worned   	| <a href="https://cdn.modrinth.com/data/cached_images/76c23f51d1422d6cb8be51c23bb8a6d6e35d7571.png" target="_blank"><img src="https://cdn.modrinth.com/data/cached_images/76c23f51d1422d6cb8be51c23bb8a6d6e35d7571.png" alt="Worned Blank Permit" width="48"></a><br>7770 	| <a href="https://cdn.modrinth.com/data/cached_images/894fd1d733eff393d5b9f4674b5f1953348175ed.png" target="_blank"><img src="https://cdn.modrinth.com/data/cached_images/894fd1d733eff393d5b9f4674b5f1953348175ed.png" alt="Worned Regular Permit" width="48"></a><br>7771 	| <a href="https://cdn.modrinth.com/data/cached_images/7bbd56e4e355ddf14e3b3b1cb4b595e41b1e81a7.png" target="_blank"><img src="https://cdn.modrinth.com/data/cached_images/7bbd56e4e355ddf14e3b3b1cb4b595e41b1e81a7.png" alt="Worned Iron Permit" width="48"></a><br>7772 	| <a href="https://cdn.modrinth.com/data/cached_images/5b73f93fc31d96000dbd01ca0afb13368500db51.png" target="_blank"><img src="https://cdn.modrinth.com/data/cached_images/5b73f93fc31d96000dbd01ca0afb13368500db51.png" alt="Worned Gold Permit" width="48"></a><br>7773 	| <a href="https://cdn.modrinth.com/data/cached_images/0c80139af65d847a06c81852ad606c3efdfa68bd.png" target="_blank"><img src="https://cdn.modrinth.com/data/cached_images/0c80139af65d847a06c81852ad606c3efdfa68bd.png" alt="Worned Diamond Permit" width="48"></a><br>7774 	| <a href="https://cdn.modrinth.com/data/cached_images/186c3c385a2eb174c5315c365971c1fa95b8bc69.png" target="_blank"><img src="https://cdn.modrinth.com/data/cached_images/186c3c385a2eb174c5315c365971c1fa95b8bc69.png" alt="Worned Joker Permit" width="48"></a><br>7775 	|

<details>
  <summary>By using commands</summary>

  <details>
  <summary>For 1.21.4+ and upper versions</summary>
  
  -   1.21.4+: `/give @s paper[custom_model_data={floats:[770]}]`
  </details>

  <details>
  <summary>For 1.21.3- and lower versions</summary>
  
  - 1.20.5 - 1.21.3: `/give @s paper[custom_model_data=770]`
  - 1.14.x - 1.20.4: `/give @s paper{CustomModelData:770}`
  </details>
</details>

<details>
  <summary>By using datapacks</summary>

  - <a href="https://www.curseforge.com/minecraft/customization/custom-roleplay-data-datapack/files/all" target="_blank">Custom Roleplay Data</a>: `/trigger CustomModelData set 770`
  - <a href="https://modrinth.com/datapack/item-name-+-custome-model-data-modifier/versions" target="_blank">Item Name + Custom Model Data Modifier</a>: `/trigger cmd set 770`<br>also have support for changing items name and lore
  - <a href="https://modrinth.com/datapack/add_custom_model_data/versions" target="_blank">add_custom_model_data</a>: `/trigger add_custom_model_data set 770`
</details>

If you want to change the **name** and **lore** of the item, I can recommend these resources:<br>
For command: <a href="https://mcstacker.net" target="_blank">MCStacker</a><br>
For datapack: <a href="https://www.curseforge.com/minecraft/customization/name-formatting-station-datapack/files/all" target="_blank">Name Formatting Station</a>
</details>
</details>

<details>
  <summary>CIT (Custom Item Texture) method</summary>

  **Important**: To use CIT you need a <a href="https://optifine.net/home" target="_blank">Optifine</a> or separate mod such as <a href="https://modrinth.com/mod/cit-resewn" target="_blank">CIT Resewn</a> etc.

  You need to change the `name` of the Paper <a href="https://minecraft.wiki/w/Paper" target="_blank"><img src="https://cdn.modrinth.com/data/cached_images/e9cb2f47970f2b77c83258586fc8be9858773250.png" alt="Minecraft Paper" width="20"></a> item according to the values ​​in the list below.<br>
  - You can change the name of the item with Anvil <a href="https://minecraft.wiki/w/Anvil" target="_blank"><img src="https://cdn.modrinth.com/data/cached_images/122bc528fa1d542da9ea7e0dbaa8dceffbe26bae.png" alt="Minecraft Anvil" width="20"></a> or <a href="https://www.curseforge.com/minecraft/customization/name-formatting-station-datapack/files/all" target="_blank">datapack</a>.
  - There can be text before and after the name, the important thing is to have the text indicating the permit.<br>Example name: `» Copper « - ·DiAmond woRneD perMit·`
  - Non case sensitive!

  | Rank →<br>Type ↓  	|     Blank     	|    Regular    	|      Iron     	|     Gold    	|    Diamond    	|     Joker     	|
|:----------:	|:-------------:	|:-------------:	|:-------------:	|:-------------:	|:-------------:	|:-------------:	|
|   Default  	|  <a href="https://cdn.modrinth.com/data/cached_images/f2f019ad56231eaa82f2383906180bc87defe150.png" target="_blank"><img src="https://cdn.modrinth.com/data/cached_images/f2f019ad56231eaa82f2383906180bc87defe150.png" alt="Default Blank Permit" width="48"></a><br>Blank Permit 	|    <a href="https://cdn.modrinth.com/data/cached_images/5a73d6883886055da1160438925068b3b894fa42.png" target="_blank"><img src="https://cdn.modrinth.com/data/cached_images/5a73d6883886055da1160438925068b3b894fa42.png" alt="Default Regular Permit" width="48"></a><br>Regular Permit   	|    <a href="https://cdn.modrinth.com/data/cached_images/527fed0647cbada3e78922e42370b29cc9d031e0.png" target="_blank"><img src="https://cdn.modrinth.com/data/cached_images/527fed0647cbada3e78922e42370b29cc9d031e0.png" alt="Default Iron Permit" width="48"></a><br>Iron Permit   	|  <a href="https://cdn.modrinth.com/data/cached_images/301507ae622138df6d6902a932ce480c4a4ab872.png" target="_blank"><img src="https://cdn.modrinth.com/data/cached_images/301507ae622138df6d6902a932ce480c4a4ab872.png" alt="Default Gold Permit" width="48"></a><br>Gold Permit 	|  <a href="https://cdn.modrinth.com/data/cached_images/1a292c97ca143c02ef63765ae64f826ee805dbd8.png" target="_blank"><img src="https://cdn.modrinth.com/data/cached_images/1a292c97ca143c02ef63765ae64f826ee805dbd8.png" alt="Default Diamond Permit" width="48"></a><br>Diamond Permit 	|  <a href="https://cdn.modrinth.com/data/cached_images/1627c510eaeaa37f97b6a1ee79dcf30f6e2a42fb.png" target="_blank"><img src="https://cdn.modrinth.com/data/cached_images/1627c510eaeaa37f97b6a1ee79dcf30f6e2a42fb.png" alt="Default Joker Permit" width="48"></a><br>Joker Permit 	|
|   Worned   	| <a href="https://cdn.modrinth.com/data/cached_images/76c23f51d1422d6cb8be51c23bb8a6d6e35d7571.png" target="_blank"><img src="https://cdn.modrinth.com/data/cached_images/76c23f51d1422d6cb8be51c23bb8a6d6e35d7571.png" alt="Worned Blank Permit" width="48"></a><br>Blank Worned Permit 	| <a href="https://cdn.modrinth.com/data/cached_images/894fd1d733eff393d5b9f4674b5f1953348175ed.png" target="_blank"><img src="https://cdn.modrinth.com/data/cached_images/894fd1d733eff393d5b9f4674b5f1953348175ed.png" alt="Worned Regular Permit" width="48"></a><br>Regular Worned Permit 	| <a href="https://cdn.modrinth.com/data/cached_images/7bbd56e4e355ddf14e3b3b1cb4b595e41b1e81a7.png" target="_blank"><img src="https://cdn.modrinth.com/data/cached_images/7bbd56e4e355ddf14e3b3b1cb4b595e41b1e81a7.png" alt="Worned Iron Permit" width="48"></a><br>Iron Worned Permit 	| <a href="https://cdn.modrinth.com/data/cached_images/5b73f93fc31d96000dbd01ca0afb13368500db51.png" target="_blank"><img src="https://cdn.modrinth.com/data/cached_images/5b73f93fc31d96000dbd01ca0afb13368500db51.png" alt="Worned Gold Permit" width="48"></a><br>Gold Worned Permit 	| <a href="https://cdn.modrinth.com/data/cached_images/0c80139af65d847a06c81852ad606c3efdfa68bd.png" target="_blank"><img src="https://cdn.modrinth.com/data/cached_images/0c80139af65d847a06c81852ad606c3efdfa68bd.png" alt="Worned Diamond Permit" width="48"></a><br>Diamond Worned Permit 	| <a href="https://cdn.modrinth.com/data/cached_images/186c3c385a2eb174c5315c365971c1fa95b8bc69.png" target="_blank"><img src="https://cdn.modrinth.com/data/cached_images/186c3c385a2eb174c5315c365971c1fa95b8bc69.png" alt="Worned Joker Permit" width="48"></a><br>Joker Worned Permit 	|
  
</details>