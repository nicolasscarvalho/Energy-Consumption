# Índice

- [Do que se trata](#do-que-se-trata)
- [Features](#features)
- [Tecnologias e ferramentas utilizadas](#tecnologias-e-ferramentas-utilizadas)
- [A base de dados](#a-base-de-dados)
- [Insights esperados](#insights-esperados)
- [Cálculos utilizados](#cálculos-utilizados)
- [Como executar](#como-executar)
- [Estudos](#estudos)




# Do que se trata

Projeto voltado para auxiliar um cidadão comum fictício ter a gerenciar gastos elétricos em sua casa por equipamentos de refrigeração. 




# Features:

Principais:
- [ ] Criar uma base de medição dos aparelhos
- [ ] Tratar os dados coletados
- [ ] Fornecer uma visualização dos dados através de gráficos
- [ ] Gerar uma análise informativa para o usuário




# Tecnologias e ferramentas utilizadas:

Linguagem | Bibliotecas/frameworks      | Uso 
--------- | --------------------------- | -----------
`Python`  | SQLite, Pandas, Matplotlib  | Armazenamento, limpeza e análise de dados e plotagem de gráficos




# A base de dados

Atributo                                             | Unidade
---------------------------------------------------- | --------
Área do cômodo                                       | Metro quadrado (float)
Altura                                               | Metro (float)
Quantidade frequente de pessoas                      | Inteiro (int)
Alta incidência de luz solar                         | Boolean (bool)
Potência do ar-condicionado existente                | BTU (float)
EER ou COP do ar-condicionado presente               | Watt (float)
Energia térmica dissipada por equipamentos elétricos | Watt (array de floats)
Tarifa de energia                                    | R$/kWh (float)




# Insights esperados

- [ ] Calcular o BTU de um ar-condicionado personalizado ao ambiente
- [ ] Comparativo de gastos antes/depois em uma escala mensal e anual em gráficos de barra
- [ ] Exibir o quanto houve de economia ou gastos, para um melhor funcionamento, em uma escala mensal e anual




# Cálculos utilizados

Em desenvolvimento...




# Como executar:

Clone o repositório e execute o arquivo `main.py`

ou...

Baixe o .zip do repositório em `Code` > `Download as ZIP`, extraia o conteúdo e abra o arquivo `main.py` através do interpretador python

**Observação**: Certifique-se de ter os interpretadores e/ou compiladores e as bibliotecas e/ou frameworks das linguagens e instalados 




# Estudos:

Caso queira as fontes de estudo utilizadas para construir o projeto, basta acessar a pasta `resources`