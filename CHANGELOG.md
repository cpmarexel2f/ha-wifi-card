# Changelog

## 1.2.0

### Nouveautés
- Éditeur visuel de la carte : titre, SSID, mot de passe, sécurité, taille du QR code et langue, sans passer par le YAML. Libellés en français et en anglais.
- Sécurité WPA3 (`SAE`) proposée dans l'éditeur.
- Réseau ouvert (`security: nopass`) : le mot de passe n'est plus obligatoire et la carte affiche « Réseau ouvert » à la place.
- Aperçu de la carte dans le sélecteur de cartes.

## 1.1.0

### Nouveautés
- Clic ou appui sur le QR code pour l'afficher en plein écran (nouveau clic, clic à côté ou Échap pour fermer), accessible au clavier avec Entrée ou Espace.
- Taille par défaut `qr_size` de 200 px, zone blanche incluse, comme la carte Wero.

## 1.0.0

Première version publique.

- QR code WiFi généré en JavaScript pur, sans dépendance ni CDN.
- Mot de passe masqué par défaut, affichable d'un clic.
- Langue détectée depuis Home Assistant (français / anglais).
- Compatible thème clair et sombre, installable via HACS.
