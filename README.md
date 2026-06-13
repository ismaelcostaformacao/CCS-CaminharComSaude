# CCS - Caminha Com Saúde 🚶‍♂️💚

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Bootstrap 5](https://img.shields.io/badge/Bootstrap-5.3-purple)](https://getbootstrap.com/)
[![Google Apps Script](https://img.shields.io/badge/Google%20Apps%20Script-Enabled-green)](https://script.google.com/)

Uma aplicação web progressiva que calcula metas personalizadas de caminhada diária e contribui anonimamente para o desenvolvimento de algoritmos de Inteligência Artificial em saúde.

## 📋 Sobre o Projeto

O **CCS - Caminha Com Saúde** é uma ferramenta interativa que ajuda os utilizadores a descobrir quantos quilómetros devem caminhar por dia, com base no seu perfil físico, estilo de vida e condições de saúde. 

Além de fornecer recomendações personalizadas e seguras, o sistema recolhe dados anonimizados (com consentimento) para uma base de dados centralizada, permitindo o treino de modelos de Machine Learning que visam otimizar as recomendações de exercício físico para diferentes perfis populacionais.

### ✨ Funcionalidades Principais
- ✅ **Cálculo Inteligente**: Algoritmo que pondera peso, altura, idade, condicionamento, tipo de trabalho, exercício regular, alimentação e histórico de saúde.
- ✅ **Histórico Local**: Guarda automaticamente os cálculos no navegador do utilizador via `LocalStorage`.
- ✅ **Base de Dados Centralizada**: Envia dados anonimizados para o Google Sheets (via Google Apps Script) para treino de IA.
- ✅ **Exportação CSV**: Permite ao utilizador exportar o seu histórico pessoal em formato CSV compatível com Excel.
- ✅ **Design Responsivo**: Interface moderna e adaptável a telemóveis, tablets e computadores.
- ✅ **Recomendações Personalizadas**: Dicas de segurança e desempenho baseadas no IMC e perfil etário.
- ✅ **Avisos de Segurança**: Limitações automáticas de meta para pessoas com restrições de saúde ou idade avançada.

## 🚀 Tecnologias Utilizadas

### Frontend
- **HTML5** & **CSS3** (com variáveis CSS personalizadas)
- **Bootstrap 5.3** (Framework responsivo)
- **Bootstrap Icons** (Iconografia vetorial)
- **JavaScript (Vanilla)** (Lógica de cálculo, LocalStorage e Fetch API)

### Backend & Dados
- **Google Apps Script** (API backend serverless)
- **Google Sheets** (Base de dados estruturada para IA/ML)
- **LocalStorage** (Armazenamento persistente no lado do cliente)

## 📦 Instalação e Configuração

### 1. Clonar o Repositório
```bash
git clone https://github.com/SEU-USUARIO/ccs-caminha-com-saude.git
cd ccs-caminha-com-saude
