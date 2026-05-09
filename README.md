# Détection des Sons d'Urgence — Deep Learning

## Description
Projet de classification binaire des sons urbains visant à détecter 
automatiquement les sons d'urgence (sirènes, coups de feu) dans un 
environnement urbain bruité, en utilisant le modèle 
Audio Spectrogram Transformer (AST).

## Dataset
UrbanSound8K — 8732 fichiers audio répartis en 10 classes sonores.

## Modèle
- Architecture : Audio Spectrogram Transformer (AST)
- Pré-entraîné sur AudioSet
- Fine-tuning progressif en 3 phases

## Résultats
| Métrique | Valeur |
| Accuracy | 97% |
| F1-score Urgence | 89% |
| Recall Urgence | 81% |

## Contenu du repository
- `projet_dl_final.ipynb` — Notebook complet (EDA, entraînement, évaluation, interface Gradio)

## Réalisé par
- Sid Massilya
- Stambouli Ines

Université A/Mira de Béjaïa — Département d'Informatique  
Année académique 2025/2026
