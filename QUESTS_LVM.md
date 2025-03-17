## Utilisateur en administrateur ROOT 

## ajouter un disque physique ( 1go ) 

fdisk /dev/sdb 
nouvelle partition : n
créer une partition primaire : p 

ecrire les changements : w

pvdisplay
pvs

vgcreate debian-vg /dev/sdb1
vgdisplay
