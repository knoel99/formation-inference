# formation-inference

Formation **inférence** from first principles.

Objectif : répondre à des questions d’interview d’*inference engineering* (tokenisation → CPU → RAM → GPU → transformers → serving / KV-cache).

## Structure

| Dossier | Étape |
| --- | --- |
| `00-first-principles/` | Ancrage notebook (NumPy → CuPy), sans framework |
| `01-tokenisation/` | Tokenisation |
| `02-cpu/` | Fonctionnement CPU |
| `03-ram/` | RAM / hiérarchie mémoire |
| `04-gpu/` | GPU / CUDA |
| `05-transformers/` | Architectures transformers |
| `06-inference/` | Inférence (KV-cache, batching, serving) |

Le notebook de départ est `00-first-principles/training_digits.ipynb` (copie depuis [knoel99/epf](https://github.com/knoel99/epf/blob/master/training_digits.ipynb)).
