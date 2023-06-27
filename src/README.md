# Modelos

Para a realização do projeto foram utilizados duas diferentes arquiteturas:

- ConvNeXt;
- ViT (Vision Transformer).

Que foram utilizadas com sua rede pré-treinada; de modo que os saves utilizados para o instanciamento inicial das redes e os saves de cada experimento se encontram nos [outputs](https://www.kaggle.com/code/raphaeldamasceno/deepfakes-recognition/output) do modelo, disponíveis na plataforma Kaggle.

Diante dos cenários de teste realizados; os melhores resultados de cada rede foram os dos seguintes experimentos:

-ConvNeXt: Experimento 6 (Com fine-tuning e RandAugment);

-ViT: Experimento 2 (Com fine-tuning e sem aumento de dados).
