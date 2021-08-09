# Mountain_Guarder
Meadow Guarder's sister game!

***

# How to Play

### Installation
##### Manual Installation
I cannot distribute node.js as I do not own any rights to it, but visiting [their website](https://nodejs.org/) you can download the latest (not LTS) and install it, **checking the box "Automatically install necessary tools"**. Wait for the installation to finish, then [download the code](https://github.com/definitely-nobody-is-here/Mountain_Guarder/archive/refs/heads/master.zip) and unzip it into any folder. Run Config.bat or Config.sh (depending on system). Then simply double-click on Start.bat or Start.sh and the server is running! (those last two sentences don't apply)

To stop the server, type "stop" into the server console.
For help, type "help" into server console. (also doesn't apply)

##### Heroku Installation
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/definitely-nobody-is-here/Mountain_Guarder)

### Joining the Game
Once the server is started, you can find your computer's name (available in Windows>System>About as "Device name"), or simply search [what's my ip](http://google.com/search?q=whats+my+ip) or click the link. The server console will tell you what port to visit and you can type either the ip address or computer name on the client side **connected to the same network as the host** and then followed by a ":" and then the port number. Example: 111.22.33.444:2000 or hostcomputer:1100

### Gameplay
Visit the [wiki](https://github.com/definitely-nobody-is-here/Mountain_Guarder/wiki) for more information.

***

# Troubleshooting
#### My Server Crashed
aaaaa
#### I can't Connect to the Server (ERROR_Connection_Refused)
If you can't connect to the server, verify that:
 - The server is running
 - You have entered the correct port number
 - You have entered the correct computer name or IP adress
 - You are connected to the same WiFi network as the server
If you have verified all four of the above, try restarting the server. If your server is running on a dedicated server (like Heroku) check that your link is correct.
#### The Server is Slow
There is nothing we can do about this. It could be your connection speed or a slow server unable to run the game at full speed. Press "backslash" ("\\") ingame and in the top-right corner it should list TPS and Ping. If your Ping is high then that is likely the source of your lag. If you TPS is low then the server is lagging. Check that there is nothing eating your computer's resources by opening Task Manager (Windows) by pressing Ctrl+Shift+Esc.

If you can't resolve your problem after trying these solutions or your problem is not on this page, go to the [Issues](https://github.com/definitely-nobody-is-here/BattleBoxes_Multiplayer/issues) page and [submit a bug report](https://github.com/definitely-nobody-is-here/BattleBoxes_Multiplayer/issues/new?assignees=&labels=bug&template=bug-report.md&title=BUG+-+%5BSummary+here%5D).

***

# Changelog

| Version | Changes                      |
| ------- | ---------------------------- |
| v0.0.1  | <ul><li>Added base game functionality</li></ul> |

***

# License

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version. This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU General Public License for more details. You should have received a copy of the GNU General Public License along with this program.  If not, see <https://www.gnu.org/licenses/>.

Full license can be found in the LICENSE file.

***

# Credits

##### Contributors:
- [Radioactive64](https://github.com/definitely-nobody-is-here) (hey look me!)
- [Maitian-352](https://github.com/maitian352)

##### Resources:
- Various articles on the internet
- [ScriptersWar](https://www.youtube.com/channel/UC8Yp-YagXZ4C5vOduEhcjRw) [tutorial series](https://www.youtube.com/playlist?list=PLcIaPHraYF7k4FbeGIDY-1mZZdjTu9QyL)
- [Meadow Guarder](https://github.com/maitian352/Meadow-Guarder)

***

## Want to Contribute?

If you would like to contribute to this game, visit the [Github](https://github.com/definitely-nobody-is-here/Mountain_Guarder) where you can send a pull request with an application request stating your reason to create a pull request in the "comments" section along with it. If you would like to submit a suggestion then too bad there's no suggestion form. Please refrain from modifying any code that is related to the database, global data structure, or encryption. Modifying such code may and can result in: Account and/or database corruption; data loss; violation of the security policy.