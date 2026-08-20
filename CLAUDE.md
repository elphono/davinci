# Ce dossier a déménagé

Le projet du teaser 88 MPH vit désormais dans **`E:\WORK\VIDEO\teaser88`**,
soit **`/mnt/e/WORK/VIDEO/teaser88`** depuis WSL. Déplacé le 4 août 2026.

Documentation, médias, rendus et dossier de travail y sont regroupés. Il ne
reste rien d'utile ici : ce fichier n'existe que pour éviter qu'on reprenne le
travail au mauvais endroit et qu'une doc divergente apparaisse.

**Relancer Claude Code depuis le nouveau dossier :**

```bash
cd /mnt/e/WORK/VIDEO/teaser88 && claude
```

Le `.mcp.json` qui enregistre le serveur `davinci-resolve` s'y trouve aussi —
c'est le fichier que Claude Code lit au démarrage, donc il faut être dans ce
dossier pour disposer des outils Resolve.

Raison du déménagement : Resolve **plante** s'il doit écrire vers un chemin UNC
(`\\wsl.localhost\...`), et les médias de la timeline vivaient sous
`C:\Users\elphono\Downloads`, à un nettoyage de machine de tout casser.
Détail dans `ETAT.md`, section « Fragilité traitée le 4 août ».
