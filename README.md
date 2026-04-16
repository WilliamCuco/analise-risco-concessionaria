Este projeto consiste em uma ferramenta interativa desenvolvida em Python para prever o risco de inadimplência de clientes em uma concessionária.
O sistema utiliza algoritmos de Machine Learning para classificar o risco entre "Alto" e "Baixo", baseando-se em dados históricos e perfil financeiro.

Funcionalidades:
-Limpeza Automática de Dados: Tratamento de strings heterogêneas e conversão de formatos monetários (R$) para numéricos.
-Modelagem Preditiva: Comparação entre dois modelos de classificação:
-Árvore de Decisão: Permite a visualização clara da lógica de decisão.
-SVM (Support Vector Machine): Utiliza normalização de dados para maior robustez.
-Interface Interativa: Menu no terminal para realizar novas classificações, ver acurácia e visualizar gráficos sem precisar mexer no código.
-Validação de Entradas: Tratamento de erros para garantir que o usuário insira dados válidos (números, valores binários, etc).

Tecnologias Utilizadas:
-Python 3
-Pandas: Manipulação e limpeza de dados.
-Scikit-Learn: Criação de modelos de ML, divisão de treino/teste e pipelines de escala.
-Matplotlib: Visualização da árvore de decisão.

Estrutura do Projeto:
-Pré-processamento: Limpeza de dados "sujos" e padronização de categorias.
-Treinamento: Divisão da base de dados (70% treino / 30% teste).
-Pipelines: Uso de StandardScaler para normalizar dados antes de alimentar o SVM.
-Interface: Sistema de menus interativos para o usuário final.
