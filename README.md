# webapp-landuse-mapbiomas
Projeto de web app com GEE para análise de uso do solo utilizando dados do MapBiomas, desenvolvido como parte de um treinamento da ambgeo.

# Web App de Análise de Uso do Solo com MapBiomas

Este é um projeto de web app desenvolvido para a visualização e análise de dados de uso do solo no Brasil utilizando o MapBiomas e Google Earth Engine. O aplicativo permite que os usuários visualizem mapas temáticos de diferentes biomas, além de realizar consultas interativas sobre mudanças no uso do solo ao longo do tempo. E ainda está sendo desenvolvido novas funcionalidades para este WebApp.

## Objetivo

O objetivo deste projeto é demonstrar a utilização de dados geoespaciais para fins de monitoramento ambiental e análise de mudanças no uso do solo. O web app foi construído como parte de um treinamento oferecido pela AmbGeo, onde foram utilizados dados da plataforma MapBiomas e processados com a API do Google Earth Engine.

## Funcionalidades

- Visualização de mapas temáticos de uso do solo com base nos dados do MapBiomas (Coleção 9).
- Consulta interativa por diferentes biomas e classes de uso do solo.
- Possibilidade de selecionar intervalos temporais e comparar mudanças ao longo do tempo.
- Interface simples e interativa construída com o framework Streamlit.

## Tecnologias Utilizadas

- **Python**: Linguagem principal para o desenvolvimento do projeto.
- **Streamlit**: Framework utilizado para criar a interface do web app.
- **Google Earth Engine (GEE)**: Utilizado para processar e extrair os dados geoespaciais.
- **Geemap**: Biblioteca para integração entre Google Earth Engine e Python.
- **MapBiomas**: Fonte de dados de cobertura e uso do solo no Brasil.

## Instalação

### Pré-requisitos

Antes de rodar o projeto localmente, é necessário ter as seguintes ferramentas instaladas ou configuradas:

- [Python 3.8+](https://www.python.org/downloads/)
- [Google Earth Engine](https://earthengine.google.com/)
- [Streamlit](https://streamlit.io/)
- [Geemap](https://geemap.org/)

### Passos para Instalação

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/webapp-landuse-mapbiomas.git
   cd webapp-landuse-mapbiomas

2. Crie e ative um ambiente virtual:
   ```bash
   python -m venv venv
   source venv/bin/activate  # No Windows: venv\Scripts\activate
   
3. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   
4. Configure o Google Earth Engine
5. Execute o aplicativo:
   ```bash
   streamlit run Mapgee.py
   
## Créditos
Este projeto foi desenvolvido como parte de um treinamento oferecido pela AmbGeo, com o objetivo de aplicar geotecnologias para análise ambiental. O código aqui apresentado foi adaptado e desenvolvido por mim, com base nos conhecimentos adquiridos durante o curso.

## Licença
Este projeto está licenciado sob a MIT License.

## Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e enviar pull requests.
