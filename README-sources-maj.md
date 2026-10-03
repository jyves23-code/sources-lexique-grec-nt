# Sources nettoyées — Lexique grec maître (Jean-Yves)

Sources (textes OCR nettoyés, EPUB et données structurées) utilisées pour l'enrichissement lemme par lemme du lexique grec du NT (corpus paulinien + Hébreux : 13 épîtres de Paul et Hébreux).

## Lexiques et usuels

| Fichier | Ouvrage | Qualité grec/hébreu | Notes |
|---|---|---|---|
| `thayer_grimm_greek_lexicon_cleaned.txt` | J.H. Thayer (d'après Grimm-Wilke), *Greek-English Lexicon of the New Testament* | Grec unicode réel (~110 000 occurrences) ; hébreu mal océrisé | Source lexicale principale : squelette des définitions |
| `LSJ_8th_Edition.txt.gz` | Liddell & Scott, *A Greek-English Lexicon*, 8e éd. (1897) | Grec unicode réel | Éventail des sens classiques (arrière-plan) ; extraction réalisée (114 186 entrées). Attention : ce n'est PAS le LSJ 9e éd., sous droit US jusqu'en 2036 |
| `vocabularyofgreek_Moulton-Milligan.epub` | Moulton & Milligan, *The Vocabulary of the Greek Testament* (1914–1929) | Grec unicode réel | Attestations papyri datées — source n° 1 pour l'usage au Ier siècle |
| `Trench_Synonyms.epub` | R.C. Trench, *Synonyms of the New Testament*, 12e éd. corrigée (1894) | Grec unicode réel | Paires de synonymes → champ « à distinguer de » des notices |
| `Word-Studies-in-the-New-Testament-Vol-3&4-Marvin-R-Vincent.pdf` | M.R. Vincent, *Word Studies in the New Testament*, vol. 3–4 (1887) | Grec en encodage de police historique (décodable) | Couvre exactement le corpus ; notes d'emploi par verset — enrichissement ciblé |
| `hatch_redpath_concordance_vol1_cleaned.txt` | Hatch & Redpath, *A Concordance to the Septuagint*, Vol. I (1897) | Grec unicode réel (~697 000 occurrences) | Attestations LXX (vol. I seul : alphabet partiel) |
| `bdb_entries.json` | BDB, version structurée unfoldingWord (Enhanced) | Hébreu unicode pointé réel | 10 022 entrées (sens, catégorie grammaticale, gloses) ; licence CC BY — attribution requise (voir README-BDB.md) |
| `bdbToStrongsMapping.csv` | unfoldingWord | — | 10 637 correspondances entrée BDB ↔ numéro Strong hébreu |
| `hebrew_chaldee_origin_greek_nt_words.csv` | Extrait structuré du Strong's Greek Dictionary (1890) | Translittération/anglais fiables ; grec natif corrompu | Mots du NT tagués « of Hebrew/Chaldee origin » — à filtrer sur Paul/Hébreux |
| `concepts_juifs_paul_hebreux.md` | Compilation thématique | — | Vocabulaire paulinien à arrière-plan hébraïque, par thème (brouillon à valider) |
| `inscription_priene_texte_grec.md` | Inscription de Priène, ~9 av. J.-C. | Grec unicode réel | Modèle d'attestation datée (ex. εὐαγγέλιον) |

## Grammaires (appoint)

| Fichier | Ouvrage | Qualité grec | Notes |
|---|---|---|---|
| `robertson_grammar_3rd_edition_cleaned.txt` | A.T. Robertson, *A Grammar of the Greek New Testament*, 3e éd. (1919) | Grec translittéré, non unicode | Texte anglais propre ; ne pas citer le grec tel quel |
| `blass_grammar_nt_greek_cleaned.txt` | F. Blass (trad. Thackeray), *Grammar of New Testament Greek* (1898) | Grec unicode réel (~33 000 occurrences) | Fiable pour citations grecques |
| `winer_grammar_nt_idiom_cleaned.txt` | G.B. Winer, *A Grammar of the Idiom of the New Testament*, 7e éd. (1883) | Grec unicode par endroits | — |
| `burton_syntax_5th_edition_cleaned.txt` | E.D. Burton, *Syntax of the Moods and Tenses*, 5e éd. (1903) | Bon dans le corps ; index final dégradé | Utile pour les verbes (modes/temps) |

## Contexte Ier siècle

| Fichier | Ouvrage | Qualité grec | Notes |
|---|---|---|---|
| `deissmann_light_ancient_east_cleaned.txt` | A. Deissmann (trad. Strachan), *Light from the Ancient East* | Grec unicode réel (~12 400 occurrences) | Exemples papyrologiques, contexte socio-linguistique |
| `deissmann_bible_studies_cleaned.txt` | A. Deissmann (trad. Grieve), *Bible Studies* (1901) | Grec unicode réel (~11 000 occurrences) | Idem |

## Fichiers testés et écartés

- 9e édition du LSJ (1940) : sous droit d'auteur aux USA jusqu'en 2036.
- *Vines' Expository Dictionary* (1940) : sous droit US jusqu'en 2036 ; usage restreint.
- Scans EPUB de Thayer (T. & T. Clark, American Book Co.) : grec passé en sosies latins, inexploitable.
- Vincent vol. II (écrits de Jean) : hors corpus.
- Anciens scans Liddell-Scott XIXe s. et hOCR Moulton-Milligan : remplacés par les versions ci-dessus.
- *BDAG* : exclu pour droits d'auteur.

## Utilisation

Pour toute session future de travail sur le lexique : cloner ce dépôt pour un accès direct aux sources, plutôt que de re-téléverser les fichiers un par un.

Chaînage du champ « lien hébreu » des notices : Strong grec → `hebrew_chaldee_origin_greek_nt_words.csv` → Strong hébreu → `bdbToStrongsMapping.csv` → `bdb_entries.json`.
