# 24SJU Kampanjskyltar

Appen där butikerna gör kampanjskyltar: välj skylt, fyll i varan och priset och ladda ner en utskriftsklar PDF.

Sidan hämtar kampanjer, produktregistret och produktbilder från kalkylarket Skyltcentralen (Google) via adressen i
`config.js`, och loggar varje nedladdad skylt där. Anropen görs utan inloggning, så det spelar ingen roll vilket
Google-konto butiken är inloggad med.

Filerna här byggs ur källkoden (`node build/build.js` → `dist/webb/`) – ändra inte i `index.html` för hand.
