# Sistemas_Multimidias
Trabalho para a disciplina de Sistemas Multimídias 2025.1 utilizando um método de processamento de áudio e vídeo e incluindo uma técnica de Inteligência Artificial. O grupo do trabalho é composto por:

- Gabriel Evaristo Carlos (201965034B)
- Israel Louback Ribeiro Júnior (202065515B)

## Objetivo

O trabalho realizado consiste em utilizar o FFMPEG para manipulação de vídeo e áudio e após isso utilizar o modelo de Inteligência Artificial YOLO para detecção dos objetos presentes no vídeo, permitindo analisar e identificar elementos de interesse nas cenas processadas


## Ferramentas Utilizadas

- **Python 3.10.12**: Linguagem de programação utilizada no projeto.
- **FFMPEG**: Para captura, leitura e processamento de vídeo e áudio.
- **YOLO (You Only Look Once)**: Modelo de detecção de objetos em tempo real.


## Estrutura do Projeto

Sistemas_Multimidias/
│
├─ main.ipynb # Notebook principal com o código
├─ runs/ # Pasta para armazenar os pesos do YOLO
├─ requirements.txt # Bibliotecas necessárias para compilar e executar o projeto
└─ README.md # Documentação do projeto


## Funcionalidades

1. **Leitura de vídeo e áudio**:
   - O FFMPEG é utilizado para extrair frames do vídeo e o áudio.
2. **Processamento de frames**:
   - Cada frame do vídeo é processado para detecção de objetos usando YOLO.
3. **Detecção de objetos**:
   - YOLO identifica e marca objetos em cada frame.
4. **Exportação do vídeo final**:
   - Os frames processados são recombinados em um novo vídeo com os objetos destacados. Adicionando o áudio original

## Execução

A execução do projeto se dá pela execução das células do arquivo main.ipynb. Como resultado final, terá um arquivo chamado "Video_final.mp4" no diretório de onde está o código


















