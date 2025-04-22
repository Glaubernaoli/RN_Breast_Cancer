# RN_Breast_Cancer

<div align="center">

<img loading="lazy" src="https://github.com/Glaubernaoli/PCD---GenomeIdentifier/assets/172425065/bcfc56a4-b124-4988-88b4-e860cb438f27" width=800>

</div>

<h1 align="center"> Classifier Neural Network made with pure python to predict Breast Cancer tumor </h1>

### Fera Formidável, Turma 2024
### Glauber Nascimento de Oliveira  
###  Redes Neurais e Algoritmos Genéticos -  Prof. Dr. Daniel Cassar

 <h4 align="center"> 
     Educational Purpouse
</h4>

<h2 align="left"> 💡 Descrição </h2>

<div align="justify">
Este projeto se baseia em um conjunto de modelos preditivos para encontrar o tempo de sobrevida de pacientes com câncer de pulmão de células não pequenas. Dessa forma, foi necessário o uso de um modelo classificador binário, que prevê se o paciente foi curado ou não, ou seja, se a previsão de sobrevida é maior que 60 meses ou não, e caso não tenha sido curado, um modelo regressor, que prevê o tempo, em meses, de sobrevida deste paciente. O objetivo desse trabalho é auxiliar na urgência/intensificação de tratamento em pacientes com menos tempo de sobrevida.
</div>

<h2 align="left"> 🏹 Target </h2>

<div align="justify">

Para o modelo classificador binário:
 
`Curado`: Se o paciente irá ser curado do cancer em menos de 5 meses.

Para o modelo regressor floresta aleatória:

`Sobrevida`: Tempo, em meses, que o paciente irá sobreviver.

</div>


<h2 align="left"> 📔 Notebooks e arquivos do projeto </h2>

<div align="justify">

`msk_met_2021_clinical_data (1).tsv`: Dataset usado no trabalho, retirado da referência 1
 
`Estudando o Target`: Neste notebook, estudamos as colunas do dataset com potencial de serem targets para a realização dos modelos. Ao ver que as colunas presentes no dataset eram organizadas de forma diferente do que os modelos buscam, novas colunas foram criadas.

`Escolhendo o modelo classificador`: Neste notebook, buscamos, por meio do Optuna, os melhores hiperparâmetos e atributos para o modelo classificador binário, onde ele prevê se o paciente foi curado, ou não.

`Escolha o modelo regressor`: Neste notebook, buscamos, por meio do Optuna, os melhores hiperparâmetos e atributos para o modelo regressor, onde ele prevê o tempo de sobrevida do paciente, em meses. <br> 

`Predição de sobrevida - A história`: Neste notebook, apresentamos, de forma resumida, o projeto final como um todo. Apresentando os melhores modelos treinados e teste de aplicação em um grupo pertencente no limiar de meses entre 55 e 60.


</div>

<h2 align="left"> 🤖 Modelos Usados </h2>

<div align="justify">

`Baseline`: Este modelo é usado como uma forma de comparação aos modelos mais complexos, sendo a média ou mediana, em casos numéricos e a moda em variáveis cateóricas.

`Classificador binário Floresta Aleatória`: Este modelo classifica os dados em Curados e Não-Curados. 

`Regressor Floresta Aleatória`: Este modelo retorna o target do tempo de sobrevida, em meses, do paciente. Este modelo possui diversas árvores de decisão, que organiza os dados através da semelhança em um atributo, e é aleatório pois a formação dessas árvores depende da amostragem dos atributos.

</div>

<h2 align="left"> 🧰 Ferramentas Usadas </h2>

<div align="justify">

`Acurácia`: métrica usada na classificação de problemass binários, que se baseia nos exemplos que foram corretamente identificados.

`Precisão`: métrica usada na classificação de problemass binários, que se baseia nos exemplos que foram classificados com rótulo positivo e foram corretamente identificados.

`Sensibilidade`: métrica usada na classificação de problemass binários, que se baseia nos exemplos que possuem um rótulo positivo e foram corretamente identificados.

</div>

<h2 align="left"> 📁 Acesso ao projeto </h2>

<div align="justify">

Você pode acessar o código pelo github ou, preferencialmente, baixá-lo.

</div>

<h2 align="left"> 🛠️ Abrir e rodar o projeto </h2>

<div align="justify">

Depois de baixar o projeto você deve abrí-lo no Jupyter Notebook/VS code

</div>

<h2 align="left"> 📓 Linguagens e programas usados </h2>

<div align="justify">

`Python`, `Jupyter Notebook`, `VS Code`, `Math`, `Scikit Learn`, `Numpy`, `Pandas` 

</div>

<h2 align="left"> 📖 Referências </h2>

<div align="justify">

1.  [Nguyen, B. et al. Genomic characterization of metastatic patterns from prospective clinical sequencing of 25,000 patients. Cell 185, 563-575.e11 (2022).](https://medium.com/ensina-ai/uma-explica%C3%A7%C3%A3o-visual-para-fun%C3%A7%C3%A3o-de-custo-binary-cross-entropy-ou-log-loss-eaee662c396c)
2.  Daniel Cassar, Material de Aula, disciplina: Redes Neurais e Algoritmos Genéticos. 2025


</div>

<h2 align="center"> :octocat:  Autores </h2>

<div align="center">
 
|  [<img loading="lazy" src="https://github.com/user-attachments/assets/421a946a-dd10-4477-8f3f-e1a277d997b0" width=115><br><sub>Glauber Nascimento de Oliveira</sub>](https://github.com/Glaubernaoli)<br> [<sub>Currículo Lattes</sub>](http://lattes.cnpq.br/0913262665776521)<br> [<sub>Linkedin</sub>](https://www.linkedin.com/in/glauber-naoli/) |
| :---: |

</div>

<h2 align="center"> 👓  Orientação </h2>

<div align="center">
 
| [<img loading="lazy" src="https://github.com/user-attachments/assets/463d4753-7fa4-4a42-aa54-409e4150bb51" width=115><br> <sub>Daniel R. Cassar </sub>](https://github.com/drcassar)<br> [<sub>Currículo Lattes</sub>](http://lattes.cnpq.br/1717397276752482) | 
| :---: | 

</div>

<h3 align="center"> 
 
`Contribuições` - Todos os autores construíram o código juntos e também atuaram como revisores do trabalho apresentado.
 
 </h3>

<div align="center">
 
<img loading="lazy" src="https://github.com/Glaubernaoli/PCD---GenomeIdentifier/assets/172425065/6c9216ea-0cdb-4dac-aac5-445d505b2804" width=800>

</div>

