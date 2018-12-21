#Il Bootstrap è la sorgente dove si prende il sistema operativo desiderato
Bootstrap: yum
OSVersion: 6
MirrorURL: http://mirror.centos.org/centos-%{OSVERSION}/%{OSVERSION}/os/$basearch/
Include: yum

#Help ci dice il messaggio di aiuto incluso nel contenitore,
#serve a comunicare all'utilizzatore eventuali comunicazioni importanti

%help
Hai chiesto aiuto all'immagine di centOS 6.Quando usi questa immagine
puoi considerare il fatto di trovarti in una versione di CentOS 6 con installate
tutte le dipendenze necessarie per svolgere i tuoi job.

#Setup agisce prima dell'etichetta %post,ed installa eventuali software o crea
#file,mentre si sta scaricando e formanto il sistema operativo e aggiunge i file 
#e i software indicati nella root dell'immagine
%setup
touch ${SINGULARITY_ROOTFS}/daleggere.txt
touch ${SINGULARITY_ROOTFS}/singrc.sh
touch nondeveesserci.txt

#File aggiunge file all'immagine prima  

