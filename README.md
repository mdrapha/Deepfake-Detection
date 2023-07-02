# Algoritmo para Detecção de Deepfakes
Autores: Raphael Damasceno R. de Moraes e Marco Antonio Coral dos Santos


Diante a problemática do uso indevido das tecnologias generativas para produção de Deepfakes; vê-se necessário a criação de mecanismos para combate de tais problemas.

Este projeto em questão tem como objetivo a utilização de um famoso [dataset](/data/README.md) de deepfakes, com excelente qualidade de produção, produzidas por StyleGAN's, para criação de um modelo capaz de classificar as imagens como reais e falsas.

Lidando com a tamanha importância da necessidade de popularização de mecanismos de combate como estes, afim de inibir a utilização imprópria de tecnologias que deveriam auxiliar a sociedade ao invés de prejudicar.

# Resultados obtidos

O modelo treinado foi capaz de obter uma acurácia média de 99.88% na classificação de imagens reais e falsas do dataset principal, ultrapassando o antigo baseline que tinha um resultado médio de 99% de acurácia. Ainda que o baseline ja se tratasse de um resultado satisfatório, o modelo em questão desenvolvido se demonstrou mais eficaz em cenários mais generalistas diante dos métodos de aumento de dados aplicados em seu treinamento, possibilitando sua utilização com poucos ajustes em cenários diveros de deepfakes.
