# Thèmes OSAI

Déposer les paquets `.them` dans ce dossier avant compilation. Ils sont installés dans `/usr/share/osai/themes/` et apparaissent dans la galerie avec leur aperçu. Le thème clair intégré utilise directement `../images/` et reste le thème par défaut.

Les thèmes personnels installés depuis l’interface restent dans `~/.local/share/osai/themes/`. À identifiant identique, un thème personnel est prioritaire sur un thème livré par le système. Le dossier historique `~/.local/share/osai-shell/themes/` reste reconnu.

Les couleurs des thèmes existants restent compatibles. Les nouveaux jetons facultatifs `surface`, `surfaceAlt`, `overlay`, `onAccent` et `backgroundBase` permettent de régler également les panneaux, champs, voiles et boutons. Les valeurs de couleur sont au format `#RRGGBB` ou `#AARRGGBB`.
