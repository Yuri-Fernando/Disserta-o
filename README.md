Código da Dissertação

Observações:

    IA2: Primeiro teste em Python para um banco de dados.
    O Código (2): Aplicação de rede neural e geração de um gráfico 3D em função de camada/neurônio.
    Testes: Contém todos os testes realizados para alcançar o resultado desejado, incluindo todas as falhas durante o processo.
    Yuri (1): Base do código inicial.
    Final: Código final onde a regressão foi usada nos dados de 2022 para validação, sem a criação de rede neural, utilizando apenas a regressão para permitir uma árvore de decisões.

Os códigos fornecem a regressão não linear por mínimos quadrados da função de emissão de CO₂ das usinas termelétricas do Brasil.

Mecanismo de Funcionamento do Código:

    Coleta de dados de geração elétrica da ONS e IEMA.
    Concatenação dos dados, separando apenas as usinas termelétricas, dos anos de 2020 a 2023.
    Geração da regressão não linear por mínimos quadrados da função de emissão de CO₂.
    Obtenção dos coeficientes da função de emissão de CO₂ das usinas termelétricas.
    Realização das métricas MSE, MSRE, MAPE para estimar os erros relativos.
    Geração de gráficos da geração e emissão de CO₂, com base nos resultados dos coeficientes.
    Criação e treinamento de uma rede neural.
    Cálculo dos erros e geração de um gráfico 3D em função da rede neural.
    Validação da regressão com os dados de 2020 e 2021, utilizada para calcular a emissão nos dados de 2022, comparando o resultado calculado com o real e o erro relativo.
