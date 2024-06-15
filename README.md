# Desafio Sistema Bancário

1. O código define uma função chamada **menu**, que exibe um menu para o usuário com opções como dpósitar, sacar, consultar extrato, criar nova conta, listar contas, criar novo usuário e criação de conta.
2. O código define um conjunto de funções para realziação de algumas operações bancarias
   - **depositar()**: Função utilizada para reazlair um depósito na conta do usuário, atualizando o saldo e o extrato;
   - **sacar()**: Função utilizada para efetuar um saque na conta do usuário, verificando se o saldo é suficiente e se o limite de saques não foi excedido;
   - **Exibir_extratos()**: Função utilizada parae exibir o extratoda conta do usuário, mostrando as transações realziadas e o saldo atual.
3. O código também inclui funcionalidades para criar novos usuários e contas bancárias:
   - **criar_usuario()**: A função criar usuário solicita informações como nome do usuário, CPF e endereço e cria um novo usuário no sistema.
   - **filtrar_usuário()**: A função filtrar usuário verifica se um usuário já está cadastrado com base no CPF fornecido.
   - **criar_conta()**: A função criar conta cria uma nova conta associando a um usuário existente no sistema.
4. O programa principal **main** executa um loop **while true** que continuará em execução idenfinidamente até que o usuário decida sair do sistema.
5. Dentro do loop, o programa solicita ao usuário que selecione uma das opções do menu e aguarda a entrada do usuário. 
   - **d**: Para realizar um deposito;
   - **s**: Para realizar um saque;
   - **e**: Para imprimir um extrato;
   - **q**: Para finaizar o programa e sair do loop.
    Após a seleção de uma  opção o programa irá executar o bloco de código associado.
6. Para a opção depósito (**d**), o programa solicita ao usuário que insira o valor a ser depósitado. Se o valor for válido (maior que zero), ele é adicionado ao saldo e uma mensagem de comprovante de depósito é exibida.
7. Para a opção de saque(**s**), o programa verifica se o valor do saque excede o saldo disponível, o limite de saque diário ou o limite total de saques. Se não houver divergência em relação a regra de negócio, o valor é subtraído do saldo e uma mensagem de comprovante de saque é exibida.
8. Para a opção de extrato (**e**), o programa exibe todas as transações realizadas pelo usuário e o saldo atual.
9. Se o usuário selecionar a opção (**q**), o programa sai do loop **while** e termina a execução.
