Este repositório contém o projeto de Data Science que eu desenvolvi com o objetivo de analisar e visualizar um conjunto de dados e criar um modelo preditivo.

Conjunto de dados
O conjunto de dados que eu escolhi para este projeto é o Titanic dataset do Kaggle. Este conjunto de dados contém informações sobre os passageiros do Titanic e é frequentemente usado em projetos de Data Science para prever a sobrevivência dos passageiros com base em seus atributos.

Arquivos do repositório
titanic_data.csv : O conjunto de dados original
titanic_analysis.ipynb : Jupyter Notebook contendo todo o código Python utilizado na análise e visualização de dados.
titanic_model.ipynb : Jupyter Notebook contendo o código Python utilizado para treinar e avaliar o modelo preditivo.
titanic_model.pkl : O modelo preditivo treinado e salvo em um arquivo .pkl.
README.md : O arquivo que você está lendo agora.
Análise e visualização de dados
O arquivo titanic_analysis.ipynb contém todo o código utilizado na análise e visualização de dados. Neste notebook, eu explorei o conjunto de dados, verificando a qualidade dos dados, eliminando dados duplicados e tratando dados ausentes. Além disso, criei gráficos e tabelas para visualizar a distribuição de dados em diferentes atributos e analisei a correlação entre os atributos.

Modelo preditivo
O arquivo titanic_model.ipynb contém o código utilizado para treinar e avaliar o modelo preditivo. Neste notebook, eu utilizei o algoritmo de regressão logística para prever a sobrevivência dos passageiros com base em seus atributos. Eu avaliei a precisão do modelo utilizando a validação cruzada e criei uma matriz de confusão para visualizar a performance do modelo.

O modelo treinado foi salvo em um arquivo titanic_model.pkl para uso futuro.

Como executar o código
Para executar o código em sua máquina local, você precisa ter o Python e os pacotes necessários instalados. Para instalar os pacotes, você pode usar o seguinte comando no terminal:

Copy code
pip install -r requirements.txt
Após instalar os pacotes, você pode executar os notebooks Jupyter através do comando:

Copy code
jupyter notebook
Isso abrirá uma janela do navegador contendo todos os notebooks do repositório. Você pode abrir e executar os notebooks na ordem em que estão listados acima.
