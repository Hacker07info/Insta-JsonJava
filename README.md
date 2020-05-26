# Insta JSON Parser JAVA
Parsing json from Instagram API...

Ho fatto una richiesta di feed di un utente di instagram con python...
Per semplciità di cose ho preso il response che otterrai con il tuo amico e l'ho messo dentro un file chiamato
--- "response.json" ---
che contiene proprio il json di risposta dalle API Instagram.

Nel repository c'è anche un file ip che contiene un jar. E' un pacchetto con alcune classi che ti servono per fare il parsing json, non a caso, nel codice ho importato quelle librerie

	***> import org.json.simple.JSONArray;***

	***> import org.json.simple.JSONObject;***

	***> import org.json.simple.parser.*;***

Ovviamente estratto il pacchetto jar, devi importarlo del tuo progetto, non ho dimestichezza con netbeans, ma oltre ad importare il JRE normale, aggiungi anche questo JAR.

Il codice è commentato tutto quanto per intero, non dovresti avere problemi a modificarlo con questa struttura base...
Ti lascio un po' di link utili!

		//http://www.unit-conversion.info/texttools/replace-text/
		//http://json.parser.online.fr/
		//https://www.unixtimestamp.com/index.php
		//https://www.w3schools.com/java/java_arraylist.asp

Consiglio sfrenato. Quando operi con il JSON, chiavi e valori sono messi tra doppie virgolette:
E.g "key": "value"
L'unico parser online che "funziona" anche con i singoli quotes ovvero, l'apostrofo (') è questo:
**_http://json.parser.online.fr/_**

Ciauz!
