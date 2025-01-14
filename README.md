# Project Database YOLO

Este repositório contém o design e treinamento de uma base de dados utilizando a rede YOLO (You Only Look Once). Ele foi criado para simplificar o processo de anotação de imagens e treinamento de modelos YOLO.

---

## Índice
- [Descrição](#descrição)
- [Pré-requisitos](#pré-requisitos)
- [Instalação](#instalação)
- [Dataset](#dataset)
- [Uso](#uso)
- [Contribuições](#contribuições)
- [Licença](#licença)

---

## Descrição

A YOLO é uma das arquiteturas mais rápidas e precisas para detecção de objetos. Este projeto tem como objetivo preparar e treinar um modelo YOLO utilizando um dataset de classificação de imagens. As ferramentas aqui disponíveis permitem desde a anotação das imagens até o treinamento do modelo.

---

## Pré-requisitos

Antes de começar, certifique-se de ter as seguintes dependências instaladas:
- Python 3.11.9
- `pip` (gerenciador de pacotes do Python)

---

## Instalação

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/project-database-yolo.git
   cd project-database-yolo
   ```

2. Instale as dependências necessárias:
   ```bash
   pip install pyqt5
   pip install lxml
   ```

3. Clone o repositório do [LabelImg](https://github.com/HumanSignal/labelImg.git) para anotar as imagens:
   ```bash
   git clone https://github.com/HumanSignal/labelImg.git
   cd labelImg
   python labelImg.py
   ```

---

## Dataset

As imagens utilizadas no treinamento são provenientes do dataset [CIFAR-10 Classification](https://www.kaggle.com/datasets/gazu468/cifar10-classification-image). Certifique-se de fazer o download e organizá-las antes de iniciar o processo de anotação ou treinamento.

---

## Uso

1. **Anote as imagens**:
   Utilize o [LabelImg](https://github.com/HumanSignal/labelImg.git) para criar as anotações necessárias para o treinamento.

2. **Treine o modelo YOLO**:
   Após organizar os dados anotados, inicie o treinamento do modelo YOLO. 

   Para mais informações sobre como treinar o modelo, consulte a [documentação oficial da YOLO](https://github.com/ultralytics/yolov5) ou substitua pelo framework específico utilizado no projeto.

---

## Contribuições

Contribuições são bem-vindas! Se você deseja melhorar o projeto ou adicionar novas funcionalidades, siga os passos:
1. Faça um fork do repositório.
2. Crie uma branch para sua feature:
   git checkout -b minha-feature

3. Faça o commit das suas alterações:
   git commit -m "Adicionei uma nova feature"

4. Envie as alterações para o repositório remoto:
   git push origin minha-feature
   
5. Abra um Pull Request.

---

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).
