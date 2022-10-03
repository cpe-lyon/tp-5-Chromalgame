# TP 5 - Systèmes de fichiers, partitions et disques
## Exercice 1. Disques et partitions
1. Il suffit d'aller dans la config vSphere et ajouter un disque.
2. Pour vérifiez que ce nouveau disque dur est bien détecté par le système il faut faire la commande `lsblk`.
3. `sudo fdisk /dev/sdb` écrire `n` puis `p` puis `1` puis `2048` puis `+2G` la première partition est créer. Pour changer le type de la partition il faut faire `sudo fdisk /dev/sdb` puis `t` puis `2` puis `7`.
4. Pour formater il faut faire `sudo mkfs.ext4 /dev/sdb1`.
5. Il affiche `xfs` et `vfat` donc la commande fonctionne.
6. 
