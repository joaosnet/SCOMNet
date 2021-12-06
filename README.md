<h1 align="center"> SCOMNet </h1>
<h3 align="center"> APRENDIZADO FEDERADO E BIOMETRIA COMPORTAMENTAL </h3>

<!-- ABOUT THE PROJECT -->
<h2 id="about-the-project"> :pencil: About The Project</h2>

<p align="justify"> 
  Esse projeto tem como objetivo identificar características avançadas em um contexto de autenticação contínua, utilizando dados do acelerômetro e giroscópio para extrair características representativas com alta discriminabilidade relacionadas ao comportamento dos usuários.
</p>

<!-- PREREQUISITES -->
<h2 id="prerequisites"> :fork_and_knife: Prerequisites</h2>

[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/) <br>
[![Made withJupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=Jupyter)](https://jupyter.org/try) <br>

<!--This project is written in Python programming language. <br>-->
The following open source packages are used in this project:
* Numpy
* Pandas
* Matplotlib
* PySyft
* PyTorch
* Scikit-Learn

<!-- DATASET -->
<h2 id="dataset"> :floppy_disk: Dataset</h2>
<p> 
  BrainRun dataset. Pode ser encontrado aqui:  https://zenodo.org/record/2598135#.X4H0qXgzbeo
  
 <!-- PREPROCESSING -->
<h2 id="preprocessing"> :hammer: Preprocessing</h2>

Os dados recebidos dos sensores de movimento estão no formato: x, y, z, tela. Onde x, y, z é a posição do dispositivo móvel de acordo com os 3 eixos e a tela é o jogo que foi gravado, por exemplo, SpeedyGame.
O conjunto de dados para cada usuário consiste em arquivos JSON. Cada arquivo JSON também é um registro de data / hora, durante o qual os dados foram coletados.

Desse modo os dados coletados pelos sensores estão relacionados a uma dimensão temporal, assim uma se utiliza uma técnica de janelamento para segmentar a série temporal bruta e extrair recursos de cada segmento.

<!-- PRE-PROCESSED DATA -->
<h2 id="preprocessed-data"> :diamond_shape_with_a_dot_inside: Pre-processed data</h2>



<!-- RESULTS AND DISCUSSION -->
<h2 id="results-and-discussion"> :mag: Results and Discussion</h2>
