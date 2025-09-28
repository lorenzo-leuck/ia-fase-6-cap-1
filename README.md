# Fiap IA - Fase 6 - Cap 1 - Despertar da rede neural

## Autor

Lorenzo Leuck - RM561682

## Descrição do Projeto

Sistema de visão computacional com YOLO (You Only Look Once) e CNN (Convolutional Neural Network) voltado para saúde dos animais na fazenda. 

O projeto inclui:

1. Organização de um dataset com imagens de cavalos e gados
2. Rotulação das imagens utilizando código Python
3. Treinamento de um modelo YOLO customizado com diferentes épocas
4. Comparação com o YOLO padrão
5. Implementação de uma CNN do zero para classificação
6. Análise comparativa das três abordagens

## Estrutura do Repositório

- `notebook.ipynb`: Notebook principal contendo todo o código e documentação do projeto
- `README.md`: Este arquivo, com informações gerais sobre o projeto

## Notebook Principal

O notebook principal (`notebook.ipynb`) contém todas as etapas do projeto, incluindo:

1. **Preparação do Ambiente**: Configuração do ambiente de desenvolvimento e instalação das dependências necessárias.
2. **Organização do Dataset**: Coleta e organização de imagens de cavalos e gado para treinamento, validação e teste.
3. **Rotulação de Imagens**: Processo de rotulação das imagens utilizando código Python.
4. **Treinamento do Modelo YOLO Customizado**: Implementação e treinamento do modelo YOLO com diferentes parâmetros.
5. **Validação e Teste**: Avaliação do desempenho do modelo treinado.
6. **Comparação com YOLO Padrão**: Comparação entre o modelo customizado e o modelo padrão.
7. **CNN do Zero**: Implementação e treinamento de uma CNN para classificação.
8. **Comparação das Três Abordagens**: Análise comparativa detalhada das três abordagens.
9. **Conclusões**: Análise crítica dos resultados e considerações finais.

## Como Executar

Para executar o código deste projeto localmente:

1. Clone este repositório
2. Crie um ambiente virtual Python (recomendado)
   ```bash
   python -m venv venv
   source venv/bin/activate  # No Windows: venv\Scripts\activate
   ```
3. Instale as dependências necessárias
   ```bash
   pip install ultralytics opencv-python scikit-learn numpy pandas matplotlib torch torchvision pillow
   ```
4. Prepare a estrutura de diretórios e os dados conforme descrito no notebook
5. Execute os blocos de código em um ambiente Python local, como um notebook Jupyter ou script Python

Esta abordagem local oferece maior controle sobre o ambiente de execução e elimina limitações de tempo e recursos impostas por serviços em nuvem gratuitos.

## Requisitos

- Python 3.7+
- PyTorch e torchvision
- OpenCV (opencv-python)
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Ultralytics (YOLOv8)
- Pillow (PIL)

## Abordagem Local

A implementação deste projeto é 100% local, sem o uso de serviços do Google e Make Sense IA como sugerido no briefing. Essa abordagem oferece diversas vantagens:

1. **Controle Total**: Acesso completo a todos os aspectos do pipeline de processamento e treinamento.
2. **Sem Limitações de Tempo**: Evita as restrições de tempo de execução impostas por plataformas como Google Colab.
3. **Segurança de Dados**: Os dados sensíveis permanecem no ambiente local, sem necessidade de upload para serviços em nuvem.
4. **Aprendizado**: Compreensão completa da infraestrutura necessária para sistemas de visão computacional.

## Vídeo de Demonstração

https://youtu.be/waJ5WEghFsA

## Referências

1. Redmon, J., Divvala, S., Girshick, R., & Farhadi, A. (2016). You Only Look Once: Unified, Real-Time Object Detection.
2. Ultralytics. (2023). YOLOv8 Documentation. https://docs.ultralytics.com/
3. PyTorch. (2023). PyTorch Documentation. https://pytorch.org/docs/stable/index.html
4. OpenCV. (2023). OpenCV Documentation. https://docs.opencv.org/
5. Scikit-learn. (2023). Scikit-learn: Machine Learning in Python. https://scikit-learn.org/stable/
