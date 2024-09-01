# Detecção de Tipo Sanguíneo com C# e OpenCvSharp

## Descrição do Projeto

Este projeto tem como objetivo desenvolver um **sistema automatizado para identificar o tipo sanguíneo** com base em **imagens de testes sanguíneos realizados em laboratório**. Utilizando C# como linguagem de programação e a biblioteca **OpenCvSharp**, o sistema será capaz de **processar imagens dos testes** e determinar o tipo sanguíneo (A, B, AB, O) e o fator Rh (positivo ou negativo) de forma precisa.

## Objetivo

Criar uma aplicação que **capture e analise imagens de reações de sangue a diferentes reagentes** (anti-A, anti-B, anti-D, etc.), determinando automaticamente o **tipo sanguíneo com base nas aglutinações observadas**. O objetivo é fornecer um método rápido e eficiente para auxiliar laboratórios, hospitais, e bancos de sangue na identificação do tipo sanguíneo de amostras.

## Funcionalidades do Projeto

1. **Interface Gráfica com C#:**  
   A aplicação terá uma interface amigável desenvolvida em C#, utilizando **WinForms **. A interface permitirá ao usuário fazer **upload de uma imagem do teste de sangue ou capturá-la diretamente através de uma câmera** conectada ao sistema.

2. **Processamento de Imagem com OpenCvSharp:**  
   Utilizando a biblioteca **OpenCvSharp**, a imagem será pré-processada para melhorar a qualidade da detecção, aplicando técnicas como **ajuste de contraste, remoção de ruído, conversão para escala de cinza e binarização/Limiarização**.

3. **Detecção de Reagentes e Aglutinações:**  
   O sistema será treinado para reconhecer **padrões específicos de aglutinação** que indicam a presença de antígenos A, B e D (para o fator Rh). Técnicas como **análise de contornos, detecção de formas e segmentação de cores** serão utilizadas.

4. **Classificação de Tipo Sanguíneo:**  
   Após a detecção das áreas de aglutinação, a aplicação aplicará um algoritmo de classificação para determinar o tipo sanguíneo com base nas reações observadas. 

5. **Exibição de Resultados:**  
   Os resultados da análise, incluindo o tipo sanguíneo e o fator Rh, serão exibidos na interface gráfica. Também haverá a opção de **salvar um relatório detalhado em formato PDF** ou enviar os resultados por e-mail.

## Tecnologias Utilizadas

- **Linguagem de Programação:** C#
- **Biblioteca de Processamento de Imagens:** OpenCvSharp
- **Interface de Usuário:** WinForms 


