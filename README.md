Micromobilidade lisboa 

                                          Contexto

Este conjunto de dados é referente ao estudo da micromobilidade desenvolvido no âmbito do
projeto Urban Co-Creation Data Lab na Cidade de Lisboa. Os dados que foram analisados são
provenientes de um conjunto de dados retirado do site Lisboa Aberta (lisboaaberta.cm-lisboa.pt)
que é uma plataforma digital disponibilizada pela Câmara Municipal de Lisboa, sendo totalmente
credível e fiável tendo em conta que foram cedidos por um organismo oficial publico. Estes dados
podem ser analisados no reportório (AnaliseJupyterMicroMobilidadeAT.ipy)

A informação disponibilizada pela plataforma de Lisboa Aberta, relativamente ao projeto Urban Co-
Creation Data Lab (UCD Lab), cujo objetivo principal é apoiar o planeamento e a tomada de decisão,
ao nível municipal, a fim de fornecer aos cidadãos serviços de alta qualidade nas áreas de
micromobilidade em Lisboa, pois a esta refere-se aos meios de transportes que servem para
percorrer distâncias curtas, mais especificamente sobre as bicicletas “Gira” (Sobre a gira - GIRA -
Bicicletas de lisboa), pela nossa análise existe pouca informação divulgada com pouca especificação
e detalhe o que dificultou as tarefas de análise, modelação e visualização por parte da comunidade.

O compromisso deste repositório é justamente que todos os meses se façam atualizações
relativamente ao uso do ‘Gira’, no ficheiro micromobilityoutput.csv onde será atualizada com a
informação mais recente disponibilizada pela plataforma Lisboa Aberta. Esta informação será
extraída das fontes de dados da desta plataforma assim que disponibilizada.

A estrutura base deste ficheiro, desenhada para fácil manipulação em Excel/Python
podendo a comunidade analítica adicionar pu alterar os dados, mediante as atualizações
dadas pela plataforma, onde poderão ser adicionadas novas colunas. Fontes adicionais de
dados também poderão ser adicionados.



Bibliografia

https://lisboaaberta.cm-lisboa.pt/index.php/pt/dados/conjuntos-de-dados
https://www.gira-bicicletasdelisboa.pt/
https://docs.jupyter.org/en/latest/

Dicionário dos dados

| Nome da coluna        | Significado           | Possíveis valores  |
| ------------- |:-------------:| -----:|
| `data` | Data a que se referem os dados | DD-MM-YYYY |
| `doses` | Número total de doses de vacinas administradas em Portugal continental | Inteiro >= 0 ou _vazio_ |
| `doses_novas` | Número diário de doses de vacinas administradas em Portugal continental | Inteiro >= 0 ou _vazio_ |
| `doses1` | Número total de primeiras doses de vacinas administradas em Portugal continental. Nota: inclui unidoses | Inteiro >= 0 ou _vazio_ |
| `doses1_novas` | Número diário de primeiras doses de vacinas administradas em Portugal continental. Nota: inclui unidoses | Inteiro >= 0 ou _vazio_ |
| `doses2` | Número total de segundas doses de vacinas administradas em Portugal continental. Nota: exclui unidoses | Inteiro >= 0 ou _vazio_ |
| `doses2_novas` | Número diário de segundas doses de vacinas administradas em Portugal continental. Nota: exclui unidoses | Inteiro >= 0 ou _vazio_ |
