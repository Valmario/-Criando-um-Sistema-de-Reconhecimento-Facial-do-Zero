# Criando um Sistema de Reconhecimento Facial do Zero

## Sobre o Projeto

Este projeto tem como objetivo desenvolver um sistema de detecção e reconhecimento facial utilizando o framework TensorFlow, juntamente com outras bibliotecas essenciais para o processamento e classificação de imagens.

O sistema deve ser capaz de detectar múltiplas faces simultaneamente e classificá-las corretamente, garantindo um alto nível de precisão no reconhecimento facial.

## Tecnologias Utilizadas

- **TensorFlow** - Framework principal para a implementação da rede neural.
- **OpenCV** - Para processamento de imagens e detecção de rostos.
- **Keras** - Para construção e treinamento de redes neurais.
- **dlib** - Para aprimoramento da detecção facial.
- **NumPy** - Manipulação de arrays e cálculos matemáticos.
- **Matplotlib** - Visualização dos resultados.

## Funcionalidades

- Detecção de múltiplas faces em tempo real ou em imagens estáticas.
- Classificação das faces detectadas utilizando redes neurais.
- Uso de modelos pré-treinados para detecção e reconhecimento facial.
- Implementação de um pipeline para treinamento e teste do modelo.

## Estrutura do Projeto

```
├── dataset/                # Conjunto de dados utilizado para treinamento
├── models/                 # Modelos treinados salvos
├── src/                    # Código-fonte do projeto
│   ├── detection.py        # Código para detecção facial
│   ├── recognition.py      # Código para reconhecimento facial
│   ├── train.py            # Script para treinamento da rede
│   ├── test.py             # Script para teste e avaliação do modelo
├── requirements.txt        # Bibliotecas necessárias para o projeto
├── README.md               # Documentação do projeto
```

## Como Executar o Projeto

### 1. Clone o repositório

```bash
git clone https://github.com/Valmario/-Criando-um-Sistema-de-Reconhecimento-Facial-do-Zero.git
cd -Criando-um-Sistema-de-Reconhecimento-Facial-do-Zero
```

### 2. Instale as dependências

```bash
pip install -r requirements.txt
```

### 3. Execute a detecção facial

```bash
python src/detection.py
```

### 4. Execute o reconhecimento facial

```bash
python src/recognition.py
```

## Resultados Esperados

O sistema deve ser capaz de detectar e reconhecer múltiplas faces simultaneamente, fornecendo uma saída semelhante à Figura 1 mencionada no desafio original.

