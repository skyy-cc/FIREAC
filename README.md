<h1 align='center'><center><img src="https://github.com/AmirrezaJaberi/AmirrezaJaberi/blob/main/assist/logo/fireac.png" alt="FIREAC logo" height="20" width="20"></center>   FIREAC   <center><img src="https://github.com/AmirrezaJaberi/AmirrezaJaberi/blob/main/assist/logo/fireac.png" alt="FIREAC logo" height="20" width="20"></center></a></h1>
<p align='center'><b><a href='https://discord.gg/uvccDWtqhv'>Discord</a> - <a href='https://amirrezajaberi.ir/fireac'>Website</a></b></h5>

---

FIREAC is the best free FiveM anti-cheat made by Amirreza Jaberi for free for you FiveM server owners and developers, this anti-cheat will help you get rid of cheaters and make a fair game for your players.

---

### Requirements :

<table align='center'>
<tr>
<td align='center'>
<a href="https://github.com/ThymonA/menuv/releases">menuv</a><br>For admin menu
</td>
<td align='center'>
<a href="https://github.com/jaimeadf/discord-screenshot/releases">discord-screenshot</a><br>For take screenshot
</td>
</tr>
<td align='center'>
<a href="https://github.com/overextended/oxmysql/releases">oxmysql</a><br>For save sql data
</td>
</tr>
</table>

---

### Features :

<table><tr><td><h4 align='center'>Client Side Protecet</h4></tr></td>
<tr><td>

- Anti Track Player's
- Anti Health Hack
- Anti Armor Hack
- Anti Infinity Ammo
- Anti Spectate
- Anti Ragdoll
- Anti Menyoo
- Anti Aim Assist
- Anti Infinite Stamina
- Anti Aim Bot
- Anti Black List Weapon
- Anti Add Weapon
- Anti Remove Weapon
- Anti God Mode
- Anti Noclip
- Anti Rainbow Vehicle
- Anti Teleport Vehicle
- Anti Teleport Ped
- Anti Invisble
- Anti Change Speed
- Anti Free Camera
- Anti Plate Changer
- Anti Night Vision
- Anti Thermal Vision
- Anti Super Jump
- Anti Suicide

</td></tr></table>

<table><tr><td><h4 align='center'>Server Side Protecet</h4></tr></td>
<tr><td>

- Anti Spam Chat
- Anti Black List Commands
- Anti Weapon Damage Changer
- Anti Vehicle Damage Changer
- Anti Black List Word
- Anti Bring All
- Anti Black List Trigger
- Anti Spam Trigger
- Anti Clear Ped Tasks
- Anti Taze Players
- Anti Inject
- Anti Black List Explosion
- Anti Explosion Spam
- Anti Black List Object
- Anti Black List Ped
- Anti Black List Vehicle
- Anti Spam Vehicle
- Anti Spam Ped
- Anti Spam Object
- Anti Change Perm
- Anti Play Sound

</td></tr></table>

---

### Inject Protect :

<table align='center'><tr><td><h4 align='center'>Server Side Protecet</h4></tr></td>
<tr><td>

- Anti Resource Start / Stop / Restart
- Anti Add Command

</td></tr></table>

---

### Connection Protect :

<table align='center'><tr><td><h4 align='center'>Server Side Protecet</h4></tr></td>
<tr><td>

- Anti VPN
- Anti Hosting
- Anti Black List Name

</td></tr></table>

---

### Ban Method :

<table align='center'><tr><td><h4 align='center'>identifiers</h4></tr></td>
<tr><td>

- FiveM License
- Steam Identifier
- IP Address
- Microsoft ID(LIVE ID)
- Xbox Live ID (XBL ID)
- Discord ID
- FiveM Player Token's

</td></tr></table>

---

### Log's :

<table align='center'>
<tr><td>

- Console
- Discord
- Chat
- Screenshot

</td></tr></table>

---

### Installation :

- Add this text in your `server.cfg` :

```
ensure FIREAC
ensure menuv
ensure screenshot-basic
ensure discord-screenshot
```

---

### Whitelist :

- You can add your users identifiers by admin menu

---

#### Exports :

### (Server Side) :

- `FIREAC_CHANGE_TEMP_WHHITELIST` This export only for add and remove player from `Temporary whitelist`
  for example :

```
Add :
exports['FIREAC']:FIREAC_CHANGE_TEMP_WHHITELIST(source, true)

Remove :
exports['FIREAC']:FIREAC_CHANGE_TEMP_WHHITELIST(source, false)
```

- `FIREAC_CHECK_TEMP_WHITELIST` This export only for check player from `Temporary whitelist` and get your result
  for example :

```
for check :
exports['FIREAC']:FIREAC_CHECK_TEMP_WHITELIST(source)
```

- `FIREAC_ACTION` This export is for `BAN` or `KICK` or `WARN` the player
  for example :

```
for BAN :
exports['FIREAC']:FIREAC_ACTION(source, "BAN", reason, details)

for KICK :
exports['FIREAC']:FIREAC_ACTION(source, "KICK", reason, details)

for WARN :
exports['FIREAC']:FIREAC_ACTION(source, "WARN", reason, details)
```

### (Client Side) :

- `FIREAC_CHANGE_TEMP_WHHITELIST` This export only for add and remove player from `Temporary whitelist`
  for example :

```
Add :
exports['FIREAC']:FIREAC_CHANGE_TEMP_WHHITELIST(true)

Remove :
exports['FIREAC']:FIREAC_CHANGE_TEMP_WHHITELIST(false)
```

- `FIREAC_CHECK_TEMP_WHITELIST` This export only for check player from `Temporary whitelist` and get your result
  for example :

```
for check :
exports['FIREAC']:FIREAC_CHECK_TEMP_WHITELIST()
```

- `FIREAC_ACTION` This export is for `BAN` or `KICK` or `WARN` the player
  for example :

```
for BAN :
exports['FIREAC']:FIREAC_ACTION("BAN", reason, details)

for KICK :
exports['FIREAC']:FIREAC_ACTION("KICK", reason, details)

for WARN :
exports['FIREAC']:FIREAC_ACTION("WARN", reason, details)
```

---

### Command :

<table align='center'>
<tr>
<td align='center'>

`/funban [Ban ID]`<br>This command unban user from database by admins (with console for in game)

</td>
<td align='center'>

`/addadmin [ID]`<br>This command add admin to database and so that can open admin menu (with console for in game)

</td>
</tr>
<td align='center'>

`/addwhitelist [ID]`<br>This command add admin to database and so that can do anything in server (with console for in game)

</td>
</tr>
</table>


---

### Tutorial :

You can install anti-cheat with tutorial of FIREAC website in **https://amirrezajaberi.ir/fireac**

---