# Notes d'adaptation — 30-Days-Of-Python

Pour : **2ème Sciences → 3ème Math → 4ème Math** 
Les 30 jours sont le guide original **mot pour mot** ; seuls des emojis ont été ajoutés.

## Modules prédéfinis au programme (3AS)
Le programme dit « utiliser des modules prédéfinis » sans les nommer ; en classe : `random` (jeux/simulations) et `math` (sqrt…). Le guide couvre `random` (Jour 12) ; `math` n'y figure pas → doc officielle Python. os/sys/statistics = 🟡 bonus.

## Légende
- ✅ = exercice au programme · *(rien)* = contenu au programme
- 🟡 = bonus facultatif — peut t'aider, ne blesse jamais
- 🔴 = hors programme / interdit en examen — sache que ça existe, n'emploie pas en devoir

## Règles d'examen
1. 🔴 `break` est interdit par le programme officiel. Conçois des conditions d'arrêt propres.
2. Tris et recherches **codés à la main** (tri à bulles 3AS ; sélection + insertion 4AS ; recherche séquentielle puis dichotomique). `.sort()` sur un exercice de tri ≈ 0.
3. 🔴 Pas de dict / set / comprehension / lambda dans une copie.
4. L'écrit note l'**analyse** : pseudocode (`Algorithme … Début … Fin`), entrées/sorties/traitements, tournage à la main. D'abord l'algorithme, ensuite le Python.
5. `input()` renvoie toujours une chaîne → `int()` / `float()`.
6. **Répéter…Jusqu'à** → `while not condition:` (jamais avec `break`).
7. Commente tes solutions.

## Carte des jours
| Jour | Sujet | Statut | Année |
|------|-------|--------|-------|
| 01 | Introduction | ✅ | 1AS |
| 02 | Variables, built-ins | ✅ | 2AS |
| 03 | Opérateurs | ✅ | 2AS |
| 04 | Chaînes | 🟡 cœur seulement | 2AS |
| 05 | Listes (tableau 1D) | ✅ | 3AS/4AS |
| 06–08 | Tuples, Sets, Dicts | 🔴 | — |
| 09 | Conditionnelles | ✅ progressive | 1AS→4AS |
| 10 | Boucles | ✅ progressive | 2AS→3AS |
| 11 | Fonctions (modules) | ✅ | 3AS |
| 12 | Modules prédéfinis | ✅ (`random`) · 🟡 os/sys/statistics | 3AS |
| 13–29 | le reste | 🔴 | — |
| 30 | Conclusion | ℹ️ | — |

## Ce que ce guide ne couvre pas (à travailler à part)
Pseudocode & tournage à la main · tris et recherches manuels · PGCD/PPCM/premiers ·
GUI QtDesigner (.text, .setText, .clear, .show, .clicked) · MicroPython/ESP32/IoT · portée des variables (`global`).
