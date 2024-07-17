# Tags
These tags can be used in any message, and are used for formatting messages. Right now, you can't add custom tags for custom colors
and/or symbols yet, however this will be possible in later versions.

Some tags like **{PLAYER}** and **{TARGET}** have some styles applied to them automatically (**{C:player}**). If you want to use 
different colors for this, you can use **{PLAYER:UNFORMATTED}** and **{TARGET:UNFORMATTED}**. This will return just the value with 
no colors.

Also do note, you can't use tags such as **{PLAYER}** or **{TARGET}** (or their unformatted counterpart) in every message. They can 
only be used in the messages that use them already.

### Symbols
| Tag             | Default Value | Description    |
|-----------------|---------------|----------------|
| **{S:warn}**    | ⚠             | Warn symbol    |
| **{S:error}**   | ✖             | Error symbol   |
| **{S:success}** | ✔             | Success symbol |

### Colours
| Tag             | Default Value | Description |
|-----------------|---------------|-------------|
| **{C:primary}** | &e            | Yellow      |
| **{C:divider}** | &8            | Gray        |
| **{C:success}** | &a            | Lime        |
| **{C:error}**   | &c            | Red         |
| **{C:player}**  | &b            | Aqua/Cyan   |

### Players
| Tag                      | Default Value | Description                                                                                  |
|--------------------------|---------------|----------------------------------------------------------------------------------------------|
| **{PLAYER}**             | None          | Returns the primary player (usually the player than ran the command or triggered the event). |
| **{PLAYER:UNFORMATTED}** | None          | Returns the primary player without the default player colour.                                |
| **{TARGET}**             | None          | Returns the target player                                                                    |
| **{TARGET:UNFORMATTED}** | None          | Returns the target player without the default player colour.                                 |
| **{MESSAGE}**            | None          | Returns the message. Mainly used for /chat and the custom chat format.                       |