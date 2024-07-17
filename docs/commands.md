## Hammer
| Command                          | Description             |
|----------------------------------|-------------------------|
| **/hammer <help\|info\|reload>** | Main command of hammer. |

## TPA
| Command               | Description                                                                                      |
|-----------------------|--------------------------------------------------------------------------------------------------|
| **/tpa [player]**     | Request to teleport to a player.                                                                 |
| **/tpahere [player]** | Request to teleport a player to you.                                                             |
| **/tpaccept**         | Accept a TPA request.                                                                            |
| **/tpdeny**           | Deny a TPA request.                                                                              |
| **/tpcancel**         | Cancels a TPA request.                                                                           |

## Home
| Command              | Description                                                                                      |
|----------------------|--------------------------------------------------------------------------------------------------|
| **/sethome [name]**  | Set a home.                                                                                      |
| **/home [name]**     | Teleport to a home.                                                                              |
| **/delhome [name]**  | Delete a home.                                                                                   |

## Chat
| Command                         | Description                                                                                                                                              |
|---------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------|
| **/chat [user] [optional:msg]** | Sends a private message. If no message is provided, it toggles automatic private chat. <br> **NOTE: This also replaces vanilla MC's /msg, /tell and /w** |
| **/reply [message]**            | Replies to a message sent to you.                                                                                                                        |
| **/r [message]**                | Replies to a message sent to you.                                                                                                                        |

### Chat → Spy
| Command            | Description                                                                                      |
|--------------------|--------------------------------------------------------------------------------------------------|
| **/msgspy**        | Toggles message spy.                                                                             |
| **/teamspy**       | Toggles team spy.                                                                                |

### Chat → Ignore
| Command                | Description                         |
|------------------------|-------------------------------------|
| **/ignore [player]**   | Ignores (blocks) a player.          |
| **/unignore [player]** | Un-ignores (unblocks) a player.     |

## Teams
| Command                             | Description                                                                                    |
|-------------------------------------|------------------------------------------------------------------------------------------------|
| **/teams create [name]**            | Creates a team with the specified name.                                                        |
| **/teams invite [player]**          | Sends an invite to the specified player.                                                       |
| **/teams chat [optional:msg]**      | Sends a message to team chat. <br>If no message is provided it will toggle automatic team chat |
| **/teams disband [team name]**      | Disbands the specified team. Player must be leader of specified team to disband it.            |
| **/teams invitation [accept/deny]** | Accepts to denies invitation to team.                                                          |
