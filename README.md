# Curso de Geoprocessamento com Python (GeoPython)

Este repositório contém os notebooks, dados e materiais de apoio para o curso de Geoprocessamento com Python, focado em ensinar os conceitos e práticas essenciais de análise de dados geoespaciais usando Python. O curso está dividido em seis aulas que cobrem desde conceitos básicos até operações avançadas de álgebra de mapas, explorando as bibliotecas GeoPandas, Matplotlib e Rasterio.

## Ementa

### Aula 01: Conceitos Básicos de Geoprocessamento
- Introdução aos conceitos de geoprocessamento e sua aplicação em ciências ambientais e áreas afins.
- Tipos de dados geoespaciais:
  - **Dados Vetoriais:** pontos, linhas e polígonos.
  - **Dados Raster:** grades e imagens de satélite.
- Geometrias básicas: estrutura e manipulação de pontos, linhas e polígonos em Python.
- Sistemas de coordenadas e projeções geográficas: fundamentos, importância, e práticas para o trabalho com diferentes sistemas de referência espacial.

### Aula 02: Leitura e Escrita de Dados Geoespaciais
- Operações de leitura e escrita com dados geoespaciais usando GeoPandas.
- União de tabelas (joins espaciais e não espaciais): introdução a operações de união de dados para análises integradas.

### Aula 03: Manipulação Avançada de Dados Vetoriais
- Operações de seleção e manipulação de dados geoespaciais.
- Técnicas para filtragem, agrupamento e resumo de dados vetoriais.

### Aula 04: Visualização e Criação de Mapas
- Plotagem de dados geoespaciais com as bibliotecas Matplotlib e GeoPandas.
- Criação de mapas temáticos para análise visual.
- Estilização e personalização de mapas: cores, legendas, escala e orientações para produzir mapas profissionais.

### Aula 05: Introdução ao Formato Raster
- Conceitos e introdução ao formato raster para análise espacial.
- Leitura e manipulação de dados raster utilizando a biblioteca Rasterio.
- Processamento de imagens de satélite e operações básicas com dados raster.

### Aula 06: Operações de Álgebra de Mapas
- Introdução a operações de álgebra de mapas para análise espacial avançada.
- Aplicação de operações raster para extração de informações e análises ambientais.

## Requisitos
- **Python 3.8+**
- **Bibliotecas:** GeoPandas, Rasterio, Matplotlib, NumPy, Pandas
- Recomenda-se o uso do Google Colab ou Jupyter Notebook para execução dos notebooks de maneira prática.

## Estrutura do Repositório
- **notebooks/**: Contém os notebooks organizados por aula.
- **docs/**: Documentação adicional e materiais de apoio.

## Acesso aos Dados
Os dados utilizados neste curso estão disponíveis no Google Drive. Você pode acessá-los através dos seguintes links:
[Aula 01](https://drive.google.com/drive/folders/1YOntYAEm1gnr_b8fm-0gSSN6tmP_Okjl?usp=drive_link)
[Aula 02](https://drive.google.com/drive/folders/109MvSRZ3FLQ2wl1ujqQ4yoeYnD8MhQXi?usp=drive_link)
[Aula 03](https://drive.google.com/drive/folders/19lQZAoFz8RNcVszk1pAkQYYnTohz3XB7?usp=drive_link)
[Aula 04](https://drive.google.com/drive/folders/1V3XhIBVGy0WjPtwSM_-AjJIizH8thEzD?usp=drive_link)
[Aula 05](https://drive.google.com/drive/folders/1taPIPFybzm8DpcDVJBUY4aMJcjyTygQY?usp=drive_link)
[Aula 06](https://drive.google.com/drive/folders/1lOcHWf7uxygS3StgCf5EaVcMtWTkmLbJ?usp=drive_link)

## Como Usar Este Repositório
1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/gepython-curso.git
2. Navegue até o diretório do~repositório:
   ```bash
   cd gepython-curso

3. Instale os requisitos:
    ```bash
    pip install -r requirements.txt
    cd gepython-curso

5. Abra os notebooks em seu ambiente de preferência (Jupyter Notebook ou Google Colab) e siga as instruções de cada aula.

## Licença
Este material é disponibilizado sob a Licença Pública Geral GNU (GPL). Você é livre para usar, modificar e redistribuir este material, desde que as modificações também sejam disponibilizadas sob a mesma licença. Isso garante que todos tenham acesso ao código-fonte e às melhorias feitas, preservando as liberdades de uso, estudo e compartilhamento.
