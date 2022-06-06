# Dalamud FAQ

## Table of Contents

### Info

- [How do I install/enable plugins?](#q-how-do-i-installenable-plugins)
- [How do I enable plugin test builds?](#q-how-do-i-enable-plugin-test-builds)
- [What is the command for \<insert plugin here\>?](#q-what-is-the-command-for-insert-plugin-here)
- [How do I turn Dalamud Staging on or off?](#q-how-do-i-turn-dalamud-staging-on-or-off)
- [How do I reset dalamud/plugin window locations?](#q-how-do-i-reset-dalamudplugin-window-locations)
- [How do I manually delete plugins?](#q-how-do-i-manually-delete-plugins)

### Troubleshooting

- [I get an error message when trying to install/update/disable a plugin](#q-i-get-an-error-message-when-trying-to-installupdatedisable-a-plugin)
- [Reshade and its variants don't work or Dalamud UI fails](#q-reshade-and-its-variants-dont-work-or-dalamud-ui-fails)
- [How do I fix plugins that rely on Dalamud provided opcodes?](#q-how-do-i-fix-plugins-that-rely-on-dalamud-provided-opcodes)
- [All my plugins basically stopped working](#q-all-my-plugins-basically-stopped-working)

### Misc

- [Do not expect XL/Dalamud/Plugin updates on patch day releases](#do-not-expect-xldalamudplugin-updates-on-patch-day-releases)
- [Remember the patches, no matter how small, can break plugins](#remember-the-patches-no-matter-how-small-can-break-plugins)

---

### Q: How do I install/enable plugins?

In order to install and enable plugins, you must first download a plugin manager such as FFXIV Plugin. Once you have downloaded and installed the plugin manager, you can then download plugins from online resources such as the FFXIV Reddit Plugin Repository. To install a plugin, simply extract the contents of the plugin into your "plugins" folder within the FFXIV Plugin directory. Once you have done this, the plugin should be enabled and functional ingame.

---

### Q: How do I enable plugin test builds?

To enable plugin test builds, you will need to go into your XIVLauncher settings and check the "Enable Plugin Test Builds" option.

---

### Q: What is the command for \<insert plugin here\>?

The command for the plugin you are looking for is "/<insert plugin name here>".

---

### Q: How do I turn Dalamud Staging on or off?

#### In game (if you can still launch)

Dalamud Staging is turned on and off through a chat command. To enable Dalamud Staging, type "/dalamud staging on". To disable Dalamud Staging, type "/dalamud staging off".

#### Out of game (when you get crashes)

You can turn Dalamud Staging on or off in the XIVLauncher settings menu.

---

### Q: How do I reset dalamud/plugin window locations?

There is no built-in way to reset the window locations of dalamud or its plugins. However, you can reset the locations by deleting the relevant files in the dalamud installation directory. For dalamud, delete the file "dalamud.pos" and for plugins, delete the file "pluginname.pos" in the "PluginData" directory.

---

### Q: How do I manually delete plugins?

To delete a plugin, simply delete the plugin's folder from your Plugins directory.

---

### Q: I get an error message when trying to install/update/disable a plugin

Please check the plugin's official page or support site for more information. If the plugin author has not provided a solution, you may be able to find a fix by searching online.

---

### Q: Reshade and its variants don't work or Dalamud UI fails

There are a couple of things that could be causing this issue. First, make sure you have the latest version of Reshade installed. If you're still having issues, try disabling any other mods or plugins you have running. If that doesn't work, try running the game in windowed mode. Lastly, if all else fails, you can try deleting the Reshade folder from your game directory and starting fresh.

---

### Q: How do I fix plugins that rely on Dalamud provided opcodes?

Any plugin that uses an opcode provided by Dalamud will need to be updated to use the new opcodes provided by XIVLauncher.

---

### Q: All my plugins basically stopped working

There could be a few different reasons for this. One possibility is that the plugin is outdated and is no longer compatible with the current version of the game. Another possibility is that the plugin is conflicting with another plugin or with the game itself. If you are using multiple plugins, try disabling them one at a time to see if that resolves the issue. If you are still having trouble, you can try contacting the plugin author or posting in the plugin support forum for help.

---

### Do not expect XL/Dalamud/Plugin updates on patch day releases

Do not expect XL/Dalamud/Plugin updates on patch day releases. The reason for this is because the team is focused on getting the game client updated and patched first and foremost. Once that is completed, they will then turn their attention to updating the launcher and plugins.

---

### Remember the patches, no matter how small, can break plugins

There's no easy answer to this question. While it's true that patches, no matter how small, can break plugins, there's also no guarantee that a plugin will work with every single patch. There's always a chance that a plugin will stop working after a patch is released, and there's always a chance that a new patch will break a plugin.

The best thing you can do is to keep an eye on the plugin's page (if it has one) and on the forums for any mention of compatibility issues. If you see that a plugin is no longer working after a patch, you can try reaching out to the plugin's author and see if they know of a fix. And if you see that a new patch has broken a plugin, you can try contacting the author and see if they are working on an update.

---

Want to add a new FAQ entry? Please use the template below and PR to the main [FAQ repo](https://github.com/goatcorp/faq):

```md
### Q: Basic Title

(FAQ content)

---
```

Then add it to the Table of Contents using `- [Name / Title here](#anchor here)`.

[Return to the top](#table-of-contents)\
[Return to the main FAQ](https://goatcorp.github.io/faq)
