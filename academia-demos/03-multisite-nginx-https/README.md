nginx https multisite
nota important
els dominis que s'empraran seran els que segueixen aquest patró:

acaba-amb-traefikpuntme-enangles-traefikdotme-i-posa-tot-el-que-vulgues-separat-per-guions-abans-de-la-ip-10-5-1-11.traefik.me
Si volem dotar de privacitat en les comunicacions entre el navegador i el servidor web cal fer un xifrat de les comunicaions. Això s'aconsegueix instal·lant els certificats de les webs que presentem i les seves claus privades.

Aquesta és una de les vies més ràpides: traefik.me

ens proporciona la resolució de noms
tenim els certificats generats a la seva web (compte que caduquen i caldrà tornar a baixar-los)
els certificats de domini incloen subdominis (sols de 1er nivell).
Propostes de evolució/millora:

generar nosatres el certificat
generació automàtica del certificat (let's encrypt)
resolució de noms local amb noms de domini locals
Referències
demo
nginx official
nginx samples
cas pràctic
documentació nginx
nginx hack - site enabler
traefik.me
generació automàtica certificats autosignats
bastion host explained
