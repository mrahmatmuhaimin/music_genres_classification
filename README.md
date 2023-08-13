---
license: apache-2.0
metrics:
- accuracy
- roc_auc
---
[Music genre](https://en.wikipedia.org/wiki/Music_genre) classification is a fundamental and versatile application in many various domains. Some possible use cases for music genre classification include:

- music recommendation systems;
- content organization and discovery;
- radio broadcasting and programming;
- music licensing and copyright management;
- music analysis and research;
- content tagging and metadata enrichment;
- audio identification and copyright protection;
- music production and creativity;
- healthcare and therapy;
- entertainment and gaming.

The model is trained based on publicly available dataset of labeled music data — [GTZAN Dataset](https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification) — that contains 1000 sample 30-second audio files evenly split among 10 genres:

- blues;
- classical;
- country;
- disco;
- hip-hop;
- jazz;
- metal;
- pop;
- reggae;
- rock.

The final code is available as a [Kaggle notebook](https://www.kaggle.com/code/dima806/music-genre-classification-wav2vec2-base-960h).
See also [my Medium article](https://medium.com/data-and-beyond/building-a-free-advanced-music-genre-classification-pipeline-using-machine-learning-654b0de7cc3e)  for more details.