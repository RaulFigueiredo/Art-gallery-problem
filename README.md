## Trabalho Final - Matemática Discreta

Este é o trabalho final da disciplina **Matemática Discreta** da FGV EMAp, realizado pelos alunos **Gustavo Sanches**, **Raul Lomonte** e **Vanessa Berwanger**.

### Sobre o Projeto

O trabalho aborda o clássico **Problema da Galeria de Arte**, que consiste em determinar o menor número de guardas necessários para vigiar completamente uma galeria de arte representada por um polígono. Para isso, desenvolvemos uma aplicação em Python que utiliza:

- **Triangulação do polígono** (algoritmo de corte de orelhas);
- **Representação planar** em forma de grafo;
- **3-coloração de grafos planares**, fundamentada no **Teorema de Chvátal**.

### Estrutura do Projeto

- `art_gallery_problem.ipynb`: Notebook principal que implementa e demonstra o algoritmo.
- `data/coordinates_10nodes.csv`: Arquivo CSV com as coordenadas de um polígono com 10 vértices.
- `data/coordinates_32nodes.csv`: Arquivo CSV com as coordenadas de um polígono com 32 vértices.

### Resultado

O notebook apresenta visualizações gráficas para:
- A triangulação do polígono;
- A coloração do grafo resultante;
- Os locais ideais para posicionamento dos guardas.

---

**FGV EMAp - 2024**