# BDB structuré (unfoldingWord)

Source : [unfoldingWord/Brown-Driver-Briggs-Enhanced](https://github.com/unfoldingWord/Brown-Driver-Briggs-Enhanced)
récupéré le 2026-10-02.

## Contenu
- `json_output/` : 10 022 entrées BDB en JSON (hébreu unicode pointé, catégorie
  grammaticale, gloses principales, sens délimités).
- `bdbToStrongsMapping.csv` : 10 637 correspondances entrée BDB ↔ numéro Strong
  hébreu (colonnes : bdb, strongs, LemmaGuess).

## Licence
Le lexique BDB est dans le domaine public. Les enrichissements (délimitation
des sens, gloses) sont sous licence CC BY : toute utilisation doit inclure
un lien vers le dépôt source ci-dessus.

## Usage prévu (lexique grec du NT, corpus paulinien + Hébreux)
Chaînage pour le champ « lien hébreu » des notices :
Strong grec → `hebrew_chaldee_origin_greek_nt_words.csv` → Strong hébreu →
`bdbToStrongsMapping.csv` → entrée JSON correspondante.
