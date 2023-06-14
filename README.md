Si es vol executar el local, cal tenir present que es necesiten definir les variables d'entorn, ja que aquestes no
es troben al codi per motius de seguretat.
A més s'ha de generar la base de dades:
flask db init
flask db migrate -m "migration"
flask db upgrade
Un cop generada la base de dades s'ha d'afegir les funcions, executant add_functions
Amb això ja es podrà executar app.py de manera local
Si es vol executar en remot el codi font es:
https://github.com/marcfg27/tfg_deploy2 i que es la font de https://provamarctfg.azurewebsites.net/