# Win10Light
Windows10 bertsio arina
Lan honen helburua Ikastetxerako Windows 10 .iso arin bat egitea da. Beharrezko elementuekin bakarrik.
Yout tubeko biedo honekin hasi naiz:
https://www.youtube.com/watch?v=x27ebzuQcHM

Behin ISO irudia izanda, install.esd fitxategia wim formatura pasatuko dugu.
Horretarako power shell-ean agindu batzuk idatzi beharko ditugu:
DISM /Get-WimInfo /wimfile:install.esd

DISM /export-image /sourceimagefile:install.esd /sourceindex:1 /destinationimagefile:install.wim /compress:max /checkintegrity

Wintoolkit deskargatzea eskatzen du gero fitxategi horretan nahi ditugun aldaketak egiteko. 
https://www.youtube.com/redirect?q=https%3A%2F%2Fwww.majorgeeks.com%2Ffiles%2Fdetails%2Fwin_toolkit.html&v=x27ebzuQcHM&event=video_description&redir_token=QUFFLUhqa2c2SEpNMTMyc3FydHRqZVJubTVtdmttbnZxUXxBQ3Jtc0tsdW9FLWw2ZkRnZDZxQ0N6Q2owbS14d2JfWkdHbXE1SmZBU25wU182R2g3ZzVoaXBlM1Q3QzVaRS11NUJBQTJ5U1dBU2gxWWhwanhEZFpZZHEtbFZtZW5TQ1RpVzczU1M3OENTWllXTmQ4Qm44cC1DRQ%3D%3D

Behin ori eginda .ISO bezala enpaketatu eta gero usb batean jarri.

