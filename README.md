# Packet Experiments

Use this repository to expand your understanding of Spigot packets. Find new uses and innovate beyond what's been seen before.

If you haven't seen this before, the most helpful tool you could **ever** have in the use of packets, will always be [WIKI.VG](http://wiki.vg/Protocol). This is a list of ALL packets ever used in client/server interaction in "Notchian" Minecraft. (Also: Spigot maintains all of these packets, and doesn't really change anything, so this also stands for "Spigot" and "Craftbukkit" Minecraft)

You can use the WIKI on this to learn more about packets without deciphering Java, even though we try to maintain very clear comments and well formatted code so that it is easy to understand what is hapenning.


### Most Useful Packets

There are over 70 packets to choose from, but here are some of the most useful and helpful ones that you'll want to keep in mind for your next plugin.

#### TitlePacket

This packet is the most widely used packet, and you can use it to send titles to be displayed on player's screens. This is widely used in some well known plugins, for instance, TitleManager.

![http://wiki.vg/Protocol][TitlePacket]

#### BossBarPacket

This packet is another really common packet that is used once again, in many plugins. A good example of how a plugin uses this is, once again, TitleManager. Also BossBarPlus is another plugin that has been built around this packet.

![http://wiki.vg/Protocol#Boss_Bar][BossBarPacket]

#### Tab-CompletePacket

This packet is not widely used among basic plugins, but it is very useful to know, because you can make your plugin super user-friendly. You can use this packet to tab-complete options for your commands! A good example of a plugin with tab-complete is PermissionsEX. Also, EssentialsX has a good use of it that's easy to understand.

![http://wiki.vg/Protocol#Tab-Complete_.28clientbound.29][Tab-CompletePacket]

#### ChatMessagePacket

This packet is very useful for chat plugins, as well as almost any other plugin. You can use this to send special JSON-Altered messages to players. For instance, you can send a Join Now! announcement, and make it so that when the player clicks it, they teleport to a minigame's lobby. A great example of an open-source plugin that does this is Kangarkoo's ChatControl.

![http://wiki.vg/Protocol#Chat_Message_.28clientbound.29][ChatMessagePacket]

[TitlePacket]: https://i.imgur.com/pInQ9VQ.png
[BossBarPacket]: https://i.imgur.com/kdEro01.png
[Tab-CompletePacket]: https://i.imgur.com/eKvYxWt.png
[ChatMessagePacket]: https://i.imgur.com/4VfI2SN.png
