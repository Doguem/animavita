# 🐾 Pet Data Checker

Este projeto é um pequeno utilitário desenvolvido em **JavaScript puro**, executado com **Node.js**, para verificar dados de pets cadastrados em sistemas como o [Animavita](https://github.com/animavita/animavita). Ele identifica possíveis problemas em registros de animais, como informações ausentes ou genéricas.

## 📌 Objetivo

Ajudar a manter a qualidade dos dados de pets cadastrados para adoção, alertando sobre campos vazios ou mal preenchidos, como:

- Nome ausente ou genérico ("sem nome")
- Descrição curta ou vazia
- Falta de foto
- Falta de telefone do responsável

## 📁 Estrutura do Projeto

- `mock_pets.json`: arquivo de exemplo contendo os dados simulados de pets
- `checkPets.js`: script que analisa os dados e exibe alertas no terminal
- `README.md`: este arquivo com instruções de uso

## 🚀 Como Executar

### Pré-requisitos

- Ter o [Node.js](https://nodejs.org/) instalado em sua máquina

### Passos

1. Clone ou baixe este repositório
2. No terminal, navegue até a pasta do projeto
3. Execute o script com o comando:

```bash
node checkPets.js

//EXEMPLO DE SAIDA

🐾 Pet 1 - Problemas encontrados:
  ⚠️ Sem foto
🐾 Pet 2 - Problemas encontrados:
  ⚠️ Nome ausente ou genérico
  ⚠️ Descrição ausente ou muito curta
  ⚠️ Sem telefone do responsável
