# Discord themes

- Discord+.theme.css: Primary theme, contains message bubbles, dark/light mode support, changes a lot of things
    - This theme does NOT have good support for Dark mode users because they bully me so it's light mode only
- OldProfile.theme.css: recreates the old Discord user profile

I'll add image previews later, I'm updating some of my themes quite a bit right now

---

### Support for Discord versions (Discord+)

| Feature| Windows  | macOS | Linux | Web |
| ------------- | ------------- |:-------------:| ------------- |------------- |
| Remove titlebar      | Works      | supported in an older version, untested right now     | Untested     | Works   |
| Fonts (Inter, Consolas) [0]      | Works      | Works     | Untested     | **Not supported**     |
| Old user area      | Works      | Works     | Untested     | Works     |
| Message bubbles [1] | Works | Works | Probably doesn't work | Works |


[0] Does not work on web because requests to Google Fonts (Inter) are blocked. At least, that's what Firefox does. 

[1] Message bubbles require the use of the "Theme Attribute" plugin in Vencord, or the equivalent in BetterDiscord or any client mod you use. Or, you can modify the source code which probably works better. 

### Support for Discord versions (OldProfile)

Have only tested on macOS and Windows, everything works there. Should theoretically work on all Discord versions, but I don't know. 
