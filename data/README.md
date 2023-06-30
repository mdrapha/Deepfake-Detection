# Datasets utilizados

Para este projeto foram utilizados dois diferentes Datasets;

- [140K Real and Fake faces](https://www.kaggle.com/datasets/xhlulu/140k-real-and-fake-faces), que se encontra disponível na plataforma Kaggle, que se consiste em imagens de faces reais e falsas, sendo que as falsas foram geradas por StyleGAN's da Nvidea e as reais foram retiradas do Flickr.
- [FaceForensics](https://github.com/ondyari/FaceForensics), que se encontra no Github, que se consiste frames de vídeos de faces falsas, produzidas por diferentes tecnologias generativas retiradas de vídeos da plataforma Youtube.

De modo que para o treinamento e teste principal da rede foi utilizado o dataset 140k Real and Fake faces. E para uma validação da aplicação final do melhor modelo foi criado um dataset experimental com uma mistura dos dois datasets, com objetivo de testar o funcionamento do modelo para contextos generalizados.
