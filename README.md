
# My CSS edit of [qb-menu](https://github.com/qbcore-framework/qb-menu)
Things i did
* I Renewed the CSS


# Previews
### With Icons
![icons](https://i.imgur.com/GaH2Amk.png)
### Without Icons
![no-icons](https://i.imgur.com/Xbn3EnT.png)


# With icons example:
```
RegisterNetEvent('wlfv-cityhall:client:CityHallMenu', function()
    exports['wlfv-menu']:openMenu({
        {
            header = 'Gemeentehuis',
            icon = 'fas fa-building',
            isMenuHeader = true,
        },
        {
            header = 'Identiteit',
            txt = 'Pasjes aanvragen',
            icon = 'fas fa-address-card',
            params = {
                event = 'wlfv-cityhall:client:CardsMenu',
            }
        },
        {
            header = 'ARBEIDSBUREAU',
            txt = 'Zoek een leuke baan',
            icon = 'fas fa-briefcase',
            params = {
                event = 'wlfv-cityhall:client:JobMenu',
            }
        },
        {
            header = 'Sluiten',
            txt = '',
            icon = 'fas fa-x',
            params = {
                event = 'wlfv-menu:client:closeMenu',
            }
        },
    })
end)

```
