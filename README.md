# Import_SQL_ESX
Ordre d’importation des SQL et placement dans le server.cfg

Version '1.0.4'

Note : esx_voice n'est pas ajouté dans le server.cfg, il y a déjà client_base, faites le changement suivant le script que vous utilisez.

Dernière(s) modification(s) :

esx_cron est déplacé en 1er, afin d'être démarré avant les scripts qui en ont besoin (Par exemple esx_society pour le blanchiment)).
