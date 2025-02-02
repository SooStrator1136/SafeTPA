# SafeTPA

[![DL](https://img.shields.io/github/downloads/nothub/SafeTPA/total?label=DL&style=popout-square)](https://github.com/nothub/SafeTPA/releases/latest)
[![LoC](https://img.shields.io/tokei/lines/github/nothub/SafeTPA?label=LoC&style=popout-square)](https://github.com/nothub/SafeTPA)

Minecraft self-service Teleport Requests

---

##### Command Usage

|||
| ------------- | --------------- |
| `/tpa <NAME>` | Send Request    |
| `/tpy <NAME>` | Accept Request  |
| `/tpn <NAME>` | Deny Request    |
| `/tpt`        | Toggle Ignore   |

---

##### Config defaults

```
allow-multi-target-request: true
request-timeout-seconds: 60
unvanish-delay-ticks: 20
spawn-tp-deny: true
spawn-tp-deny-radius: 1500
distance-limit: false
distance-limit-radius: 10000
```

---

Uses [vanish](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/entity/Player.html#hidePlayer(org.bukkit.plugin.Plugin,org.bukkit.entity.Player)) to mitigate [Coordinate Exploitation](https://2b2t.miraheze.org/wiki/Coordinate_Exploits#Debug_Exploit/).

---
This Project uses [PaperLib](https://github.com/PaperMC/PaperLib) and [bStats](https://bstats.org/plugin/bukkit/SafeTP/11798).
