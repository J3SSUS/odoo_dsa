sudo find addons/  -type d -exec chmod 755 {} \;
sudo find addons/  -type f -exec chmod 644 {} \;
sudo find addons/  -type d -exec chown daniel:daniel {} \;
sudo find addons/  -type f -exec chown daniel:daniel {} \;
-------------- aplicacion web para generar Expresiones Regulares ----
https://regex101.com/
----------------------------
Regular Expresion for :
------------------------------------------------------------------------------------
email : RegExp("^\\w+@[a-zA-Z_]+?\.[a-zA-Z]{2,3}$");

card number : RegExp("^(?:4[0-9]{12}(?:[0-9]{3})?|[25][1-7][0-9]{14}|6(?:011|5[0-9][0-9])[0-9]{12}|3[47][0-9]{13}|3(?:0[0-5]|[68][0-9])[0-9]{11}|(?:2131|1800|35\d{3})\d{11})$");

expiration date : RegExp("^(0[1-9]|1[0-2])\/?([0-9]{4}|[0-9]{2})$", 'g');

cvv : RegExp("^[0-9]{3,4}$");

#Desarrollo Adaptativo de Software
------------------------------------------------------------------------------------