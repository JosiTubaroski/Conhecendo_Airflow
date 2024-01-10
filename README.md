# Conhecendo Airflow

### Conehecendo a UI / Interface gráfica do Airflow

<img src="https://github.com/JosiTubaroski/Conhecendo_Airflow/blob/main/img/Tela_Airflow.png">

### Pricipais componentes das visualizações.

O componente principal do Airflow é uma dag, e cada linha visualizada na interface gráfica é uma dag.
Essas dags são de demonstração, elas já foram instaladas quando instalamos o docker do airflow.
Cada uma dessas dags foi escrita em código python, inclusive o airflow é feito em python.
Essas dags de demonstração podem ser desabilitadas, para uma melhor visualização das dags que realmente estão em uso.

### Ligando ou desligando uma dag

<img src="https://github.com/JosiTubaroski/Conhecendo_Airflow/blob/main/img/Ligando_Desligando_Dag.png">

### Visualizando uma dag

<img src="https://github.com/JosiTubaroski/Conhecendo_Airflow/blob/main/img/Selecionar%20Dag.png">

### Grid, Graph e Calendar

Vamos utilizar para análise a dag: example_branch_Operator

<img src="https://github.com/JosiTubaroski/Conhecendo_Airflow/blob/main/img/Exemplo_branch_Oper.png">

Para isso vamos habilitar a dag e aguardar por alguns segundos o retorno da execução.

Perceba que a dag possui 5 tasks e 1 execução.

<img src="https://github.com/JosiTubaroski/Conhecendo_Airflow/blob/main/img/Tasks.png">

Visualizando as tasks da Dag

<img src="https://github.com/JosiTubaroski/Conhecendo_Airflow/blob/main/img/Tasks_Da_Dag.png">

Visualizando as tasks em modo grafico.

<img src="https://github.com/JosiTubaroski/Conhecendo_Airflow/blob/main/img/Tasks_Modo_Grafico.png">

Calendar

<img src="https://github.com/JosiTubaroski/Conhecendo_Airflow/blob/main/img/Calendar.png">






