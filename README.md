# 1. Sobre A Xtreme Groovy Bikes Sales 

A Xtreme Groovy Bikes Sales é uma empresa de revenda de motocicletas. Seu modelo de nogócio é revender motocicletas usadas. Com a crescente do valor dos veículos usados, a XGB Sales, como é conhecida, deseja expandir os seus negócios. Você foi contratado como cientista de dados pela empresa XGB Sales para ajudá-los a encotrar as melhores motocicletas para revenda. 

# 2. Premissas assumidas para a análise
Para isso, o CEO da empresa fez um estudo de mercado uma base de dados, obtida através desse estudo, para que consiga auxiliar a encontrar as melhores motocicletas para revenda, aumentando assim o lucro da empresa.
O conjunto de dados que representam o contexto está disponível na plataforma do Kaggle. O link para acesso aos dados: [Motorcycle Dataset](https://www.kaggle.com/datasets/nehalbirla/motorcycle-dataset).
Além disso, eles podem ser encontrados dentro do diretóirio `data` deste projeto.

# 3. Estratégia da solução
Além disso, o CEO fez algumas perguntas a cerca da base de dados que a empresa possui.
Lembrando que o contexto, pessoas e perguntas são completamente fictícios.

## Primeira Rodada de Perguntas
    1. Quantas motos temos dentro do Dataset?
    2. Qual é o ano da moto mais antiga da base de dados?
    3. Qual é o ano da moto mais nova da base de dados?
    4. Qual é o valor da moto mais cara da base de dados?
    5. Qual é o valor do hodômotro da moto com a maior quilometragem?
    6. Qual é o valor do hodômotro da moto com a menor quiilometragem?
    7. Das motocicletas que estão sendo expostas dentro de um Show Room, qual é o maior valor registrado na base de dados?
    8. Das motocicletas que estão sendo expostas dentro de um Show Room, qual é o menor valor registrado na base de dados?
    9. Quantas motocicletas estão sendo vendidades pelos seus donos e quantas estão sendo vendidas por outros revendedores?
    10. Qual é a média de valores das motos na base de dados?
    11. Qual é a média de ano das motos cadastradas dentro da base de dados?
    12. Qual é a média de quilometragem das motos cadastradas dentro da base de dados?
    13. Existem quantas motos dentro da base de dados que são motos de um único dono?
    14. As motos com menor quilometragem são as motos mais baratas do Dataset?

## Segunda Rodada de Perguntas
    1. As motos que possuiram somente 1 dono são as motos mais caras na média que as motos que tiveram mais donos?
    2. As motos que possuiram mais donos são as motos que possuem quilometragem média maior que as motos que possuiram menos donos?
    3. As motos que possuiram mais donos são as motos mais velhas na média?
    4. As motos que são vendidas por revendedores são as motos mais caras na média do que as motos vendidas pelos seus donos?
    5. O CEO lhe entregou um novo dataset chamado companies.csv, onde estão todas as fabricantes de motocicletas. Adicione uma coluna no DataFrame com o nome de company. Essa coluna deve possuir o nome do fabricante de cada moto do DataFrame.
    6. Crie um novo dataset chamado bikes_completed.csv a partir do DataFrame com a coluna company preenchida.
    7. Quais são so fabricantes que mais possuem motos cadastradas na base de dados completa?

## Terceira Rodada de Perguntas
    1. Ajustar a coluna `name` para que ela fique somente com o nome da moto.
    2. Qual das fabricantes possui o maior preço médio de suas motos?
    3. Qual o fabricante que possui a moto com o maior quilometragem?
    4. Qual o fabricante que possui a moto mais velha?
    5. O fabricante que possui a moto mais cara do Dataset é também o fabricante que possui menos motos cadastradas?
    6. Qual o fabricante que possui a menor variação de valor de venda?
    7. Quais motos eu devo comprar? 
    - Leve em conta que eu desejo motos com no máximo 3 anos de uso; no máximo 40 mil quilometros rodados; que sejam de um único dono; que estejam sendo vendidas por possoas físicas e que tenham o valor pretendido de venda menor que o valor do showroom. Envie um relatório contendo o modelo, preço de venda, quilometro rodado e ano, ordenado por valor de venda de forma decrescente para o meu e-mail.

# 4. Principais insights
    1. Tem uma quantidade expressiva de vendas por pessoas do que por distribuidoras.
    2. Quantidade de vendas de um único proprietário e maior, tendo com isso um maior valor.
    3. Com uma lista de onde comprar e quais as melhores para comprar.

# 5. O produto final do projeto:
Um dashboard iterativo hospedado em cloud que está disponível para acesso de qualquer dispositivo com conexão à internet. Para acessá-los basta clicar no link a seguir:(https://git-project.streamlit.app/)

# 6. Conclusão
Este projeto teve como objetivo a criação de um dashboard iterativo para auxiliar o CEO da empresa na tomada de decisões, de maneira simples e rápida.  Territoriamente, existem muitas expansões possíveis para se fazerem, o novo CEO terá uma maior gama de informações e métricas relevantes sobre o negócio para elaborar uma reestruturação do planejamento de negócio que poderá levar a um outro patamar, tornando a Xtreme Groovy Bikes Sales uma das melhores empresa de motocicletas no segmento de revenda.

# 7. Próximo passos
1 Verificar outros dados da empresa, como, quantidade total de usuários, idade média dos usuários, % de homens e mulheres, preferência por homens e mulheres, qual a idade média de quem prefere delivery.

2 Adicionar novas tabelas com as novas informações relevantes, adicionando novos filtros.

3 Adicionar novas visões do negócio, com essas novas conclusões, novas ações de marketing direcionado podem ser feitas.


