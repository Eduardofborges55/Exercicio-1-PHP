# Exercicio-1-PHP

# Exercicio de sintaxe de PHP e rotas

1 -# Criar um array de eventos

- Cada evento vai ser um array associativo com no minimo os seguintes dados:
    - Identificador
    - Nome
    - Data de inicio (aaaa-mm-dd)
    - Data de término (aaaa-mm-dd)
    - Array associativo de ingresso (um ingresso inteiro e um meia entrada)
    - Os ingressos devem ter os dados
    - Valor
    - Tipo -> meio ou inteiro
    - Quantidade Disponível
    - Quantidade Vendida
  - Criar pelo menos 3 eventos

# 2. Rota para buscar as informações do event:o
  - Informar o identificador do evento
  - Buscar no array de eventos qual possui o indificador informado
  - Retornar as informações desse evento em formato JSON

# 3. Rota para comprar um ingresso:
  -  Informar o evento que deseja comprar;
  -  Informar o tipo de ingresso que deseja comprar;
  -  Informar a quantidade de ingressos que deseja comprar;
  -  A rota deve reronar os dados do evento atualizados com a quantidade informada

# OBS: Não precisa salvar nada, sempre utilizar o array de eventos original como base.
