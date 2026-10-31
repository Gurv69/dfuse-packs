# D.FUSE · pack « Avatar 3D »

Fichiers téléchargés par D.FUSE (PC et tablette) la première fois qu'on ouvre le Personnage 3D du studio Avatar.
Ils ne contiennent que des données (modèle, peaux, cheveux, accessoires) : tout le code reste dans D.FUSE.

- `avatar3d.json` + `avatar3d.json.sig` : manifeste signé (ECDSA P-256) ; D.FUSE refuse un manifeste mal signé.
- `avatar3d-<morceau>-<empreinte>.zip` : un zip par morceau (base, skins, hair, acc), vérifié par son SHA-256.

Fabriqués par `tools/build_pack.py` du dépôt D.FUSE. Licences : modèle MPFB et peaux MakeHuman en CC0 ; cheveux et
accessoires en CC0 ou CC-BY (auteurs et licences dans `hair/LISEZMOI.md`, `hair/credits.json`, `acc/LISEZMOI.md`,
`acc/credits.json`, à l'intérieur des zips).

Ce dépôt ne contient aucun code. Les fichiers servent uniquement à D.FUSE ; sauf les modèles sous CC0/CC-BY
(qui gardent leur licence d'origine), tous droits réservés.
