# 🚴‍♂️ Via-Bike - Plataforma Colaborativa para Ciclistas Urbanos

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![OpenStreetMap](https://img.shields.io/badge/OpenStreetMap-7EBC6F?style=for-the-badge&logo=OpenStreetMap&logoColor=white)

> Projeto acadêmico desenvolvido para a disciplina Hands on Work - ADS UNIVALI

## 📋 Sobre o Projeto

O **Via-Bike** é uma plataforma web colaborativa que permite aos ciclistas urbanos reportar, visualizar e validar as condições das vias para bicicletas em tempo real. A plataforma utiliza mapas interativos e um sistema de validação comunitária para criar uma base de dados colaborativa que melhora a segurança e experiência do ciclismo urbano.

### 🎯 Objetivos

- ✅ **Reportar problemas** em vias para bicicletas (buracos, obstáculos, falta de sinalização)
- ✅ **Visualizar condições** em tempo real através de mapas interativos
- ✅ **Validar informações** através da comunidade
- ✅ **Criar uma base de dados** colaborativa para melhorias urbanas
- ✅ **Melhorar a segurança** dos ciclistas urbanos

## 🚀 Funcionalidades

### 🗺️ Mapa Interativo
- Visualização em tempo real dos problemas reportados
- Integração com OpenStreetMap
- Seleção de localização por clique no mapa
- Geolocalização do usuário

### 📝 Sistema de Reporte
- Categorização de problemas (buracos, obstáculos, sinalização, etc.)
- Descrição detalhada dos problemas
- Localização precisa no mapa
- Armazenamento local dos dados

### 👥 Validação Comunitária
- Sistema de confirmação de problemas
- Contador de confirmações por report
- Listagem de problemas recentes
- Interface responsiva para mobile

## 🛠️ Tecnologias Utilizadas

- **Frontend:** HTML5, CSS3, JavaScript (ES6+)
- **Mapas:** Leaflet.js + OpenStreetMap
- **Armazenamento:** LocalStorage do navegador
- **Hospedagem:** GitHub Pages
- **Metodologia:** Scrum

## 📦 Como Executar o Projeto

### Pré-requisitos
- Navegador web moderno (Chrome, Firefox, Safari, Edge)
- Conexão com internet (para carregar mapas)

### Execução Local
```bash
# 1. Clone o repositório
git clone https://github.com/seu-usuario/via-bike.git

# 2. Acesse o diretório
cd via-bike

# 3. Abra o arquivo index.html no navegador
# Ou use um servidor local:
python -m http.server 8000
# Acesse: http://localhost:8000
