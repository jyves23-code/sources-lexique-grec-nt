# Sources nettoyées — Lexique grec maître (Jean-Yves)

Fichiers texte OCR nettoyés (en-têtes de bibliothèque/scan retirés, artefacts d'encodage supprimés), utilisés comme sources pour l'enrichissement lemme par lemme du lexique grec du NT.

| Fichier | Ouvrage | Qualité grec | Notes |
|---|---|---|---|
| `robertson_grammar_3rd_edition_cleaned.txt` | A.T. Robertson, *A Grammar of the Greek New Testament in the Light of Historical Research*, 3e éd. (1919) | Grec translittéré, non unicode | Texte anglais propre ; ne pas citer le grec tel quel |
| `blass_grammar_nt_greek_cleaned.txt` | F. Blass (trad. Thackeray), *Grammar of New Testament Greek* (1898) | Grec unicode réel (~33 000 occurrences) | Fiable pour citations grecques |
| `moulton_grammar_nt_greek_cleaned.txt` | J.H. Moulton, *A Grammar of New Testament Greek*, Prolegomena, 2e éd. (1906) | Mixte | Boilerplate Google Books retiré |
| `winer_grammar_nt_idiom_cleaned.txt` | G.B. Winer (éd. Lünemann, trad. Draper), *A Grammar of the Idiom of the New Testament*, 7e éd. (1883) | Grec unicode par endroits | — |
| `burton_syntax_5th_edition_cleaned.txt` | E.D. Burton, *Syntax of the Moods and Tenses in New Testament Greek*, 5e éd. (1903) | Bon dans le corps ; index final dégradé | Index des passages cités peu fiable |
| `thayer_grimm_greek_lexicon_cleaned.txt` | J.H. Thayer (d'après Grimm-Wilke), *Greek-English Lexicon of the New Testament* | Grec unicode réel (~110 000 occurrences) ; hébreu mal océrisé | Source lexicale principale |
| `hatch_redpath_concordance_vol1_cleaned.txt` | Hatch & Redpath, *A Concordance to the Septuagint*, Vol. I (1897) | Grec unicode réel (~697 000 occurrences) | Excellent pour attestations LXX |
| `deissmann_light_ancient_east_cleaned.txt` | A. Deissmann (trad. Strachan), *Light from the Ancient East* | Grec unicode réel (~12 400 occurrences) | Contexte papyrologique |
| `deissmann_bible_studies_cleaned.txt` | A. Deissmann (trad. Grieve), *Bible Studies* (1901) | Grec unicode réel (~11 000 occurrences), constant | Contexte papyrologique |
| `hebrew_chaldee_origin_greek_nt_words.csv` | Extrait structuré du Strong's Greek Dictionary | Translittération/anglais fiable ; grec natif corrompu | Mots du NT entier tagués « of Hebrew/Chaldee origin » par Strong — à filtrer pour Paul/Hébreux |
| `concepts_juifs_paul_hebreux.md` | Compilation thématique (Claude) | — | Vocabulaire grec paulinien à arrière-plan hébraïque, organisé par thème |

## Ouvrages testés et écartés (grec non exploitable)

Non inclus ici faute de grec/hébreu unicode fiable : Mayser (*Grammatik der griechischen Papyri*, tous volumes/scans testés), Strong's Greek Dictionary (texte brut), Strong's Hebrew Dictionary, Gesenius/BDB Hebrew-English Lexicon, Gesenius *Thesaurus* (latin). Pour l'hébreu, préférer le dépôt [unfoldingWord/Brown-Driver-Briggs-Enhanced](https://github.com/unfoldingWord/Brown-Driver-Briggs-Enhanced) (JSON, hébreu unicode fiable).

## Utilisation

Pour toute session future de travail sur le lexique : cloner ce dépôt pour un accès direct aux sources, plutôt que de re-téléverser les fichiers un par un.
