# google-photo-synology
installer python 3 via les paquets

# ATTENTION
a chaque mise a jour de python 3 google-photo sera reset, il faut que je modifie cela

# configration
Creer un client id oAuth pour " Entrée TV et limitée "	et recuperer son json

# installation
sudo /volume1/@appstore/python3/bin/python3.7 -m pip install gphotos-sync

# exemple d'utilisation
/volume1/@appstore/python3/bin/gphotos-sync --secret /volume1/google_photo/secret.json /volume1/google_photo/backup/

# nouivelle install avec DSM7 :
/var/services/homes/veka/.local/bin/gphotos-sync  --secret /volume1/google_photo/secret.json /volume1/google_photo/backup/
