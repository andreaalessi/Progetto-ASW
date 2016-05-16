# Progetto-ASW
Repository progetto Architetture Software

Preparazione: 

1. scaricare Apache Plume dal link: http://apache.panu.it/tomee/tomee-1.7.4/apache-tomee-1.7.4-plume.zip
2. estrarre il file .zip e rinominarlo in "apache-plume" posizionare tale cartella all'interno di progetto_alessi_dolce/shared/resources
3. copiare file tomee.xml e sostituirlo al file presente in progetto_alessi_dolce/shared/resources/apache-plume/conf
4. copiare file GameShop.war ed incollarlo nella cartella progetto_alessi_dolce/shared/resources/apache-plume/webapps

Avvio: 

1. per la creazione dell'ambiente posizionarsi nella directory ambiente ed effettuare il comando vargant up
2. per accedere all'applicazione sul server remoto da browser su macchina host digitare l'indirizzo: http://192.168.1.10:8080/GameShop/index.html
