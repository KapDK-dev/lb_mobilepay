# lb_mobilepay

__-- Kap --__

_Version 1.0.0_
Forfatter: Kap
Kommentar: Første script til LB Phone, skrevet fra bunden, IKKE testet.

Dette script er et Gratis script. 
Vær varsom, og sælg ikke koden videre! Lad den være gratis for alle der kan bruge den, så vi alle kan bruge det til noget godt.


__App tilføjelse til lb_phone:__

Smid ind i client/apps-lua ELLER client/main.lua (Afhængig af din version)


TriggerEvent('lb-phone:registerApp', {
    app = 'mobilepay',
    name = 'MobilePay',
    description = 'Overfør penge med telefonnummer',
    developer = 'Kap - Må gerne ændres :)',
    defaultApp = false,
    size = 59875, -- vilkårligt unikt ID
    icon = 'https://i.imgur.com/YOUR_ICON.png', -- skift til dit eget logolink, hvis du har et
    color = '#2980b9',
    ui = 'http://lb_mobilepay/html/ui.html' -- husk at skifte "lb_mobilepay" til det faktiske navn på din resource, men det er bedst ikke at ændre navnet.
})
