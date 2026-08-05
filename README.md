# Pneumonia Detection via CNN (PyTorch)

## 📌 Sobre o Projeto
Este projeto desenvolve uma solução de **Inteligência Artificial** voltada para a área da saúde (*HealthTech*), focada na **detecção automatizada de pneumonia a partir de imagens médicas de Raio-X do tórax (Chest X-Ray)**. 

O núcleo do projeto consiste no desenvolvimento e treinamento de uma **Rede Neural Convolucional (CNN)** utilizando técnicas de *Deep Learning* (Aprendizado Profundo) para realizar a classificação binária das imagens em duas categorias: **Saudável (Normal)** ou **Com Pneumonia**.

---

## 🏗️ Arquitetura e Estrutura Técnica
O pipeline foi construído seguindo as melhores práticas de desenvolvimento em Machine Learning:

*   **Linguagem principal:** Python
*   **Framework de Deep Learning:** PyTorch (`torch`, `torch.nn`, `torch.optim`)
*   **Manipulação de Imagens:** Torchvision (aplicação de transformações, normalizações e redimensionamento de imagens)
*   **Gestão de Dados:** `DataLoader` estruturado para otimizar o consumo de memória durante as etapas de treino e validação.

---

## 📊 Origem dos Dados e Métricas
*   **Dataset:** Imagens obtidas diretamente da plataforma Kaggle (`chest-xray-pneumonia`) de forma automatizada através da biblioteca `kagglehub`.
*   **Desempenho:** Na etapa de validação, utilizando o bloco de avaliação e congelamento de gradientes (`torch.no_grad()`), o modelo registrou uma **precisão/acurácia final de 68,9%**.

---
### 🎬 Demonstração do Treinamento em Tempo Real
![Demosntração do Treinamento](https://github.com/user-attachments/assets/e5be8fb0-1ade-491c-bc5b-ebfa4546eb80)
---
## 🚀 Como Executar o Projeto

### 1. Pré-requisitos
Certifique-se de ter o Python instalado na sua máquina. Em seguida, clone este repositório e instale as dependências contidas no arquivo `requirements.txt`:

```bash
pip install -r requirements.txt
```

### 2. Executando o Treinamento
Para iniciar o download do dataset via API e disparar o loop de treinamento da rede neural, execute o arquivo principal:

```bash
python CNNs.ipynb
```

---

## 🛠️ Status do Projeto
⚠️ **Em Desenvolvimento**
*   [x] Configuração do ambiente e download automatizado do dataset.
*   [x] Estruturação das camadas da Rede Neural Convolucional (CNN).
*   [x] Implementação do loop de treino e validação inicial (Acurácia de 68,9%).
*   [ ] Aplicação de técnicas de *Data Augmentation* para balanceamento das classes.
*   [ ] Otimização de hiperparâmetros (ajuste de *learning rate* e épocas) para aumentar a precisão.
```bash
Git clone [https://github.com/Lucas-ui63/Classifica-o_de_Pneumonia_com_Deep_Learning]
```
