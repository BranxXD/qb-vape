
## Dependencies
* [qb-core](https://github.com/qbcore-framework/qb-core)

## Setup
* Install into resources/[QBCore]
* Add /[qb-vape\images] In Your Inventory Script 
* Add :
```
['vape']              = {['name'] = 'vape',                 ['label'] = 'Vape',                 ['weight'] = 500,         ['type'] = 'item',         ['image'] = 'vape.png',         ['unique'] = false,         ['useable'] = true,     ['shouldClose'] = true,       ['combinable'] = nil,   ['description'] = 'Blow clouds'},
```
In Your /[qb-core\shared\items.lua]
* Add the following line to your server.cfg
```
ensure qb-vape
```
## Owner 
* For More Information Contact : [Branx#5066](https://discord.gg/TcNXN28n9c)