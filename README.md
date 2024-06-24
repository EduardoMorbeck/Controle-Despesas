<h1>WebApp para Controle Financeiro</h1>

<p>Este repositório contém um WebApp desenvolvido em JavaScript para gerenciar transações financeiras. O aplicativo permite ao usuário adicionar, remover e visualizar transações, exibindo os valores totais de receitas, despesas e saldo atual. As transações são armazenadas no localStorage do navegador, permitindo que os dados persistam entre sessões.</p>

<h2>Funcionalidades</h2>
Adicionar Transações: O usuário pode adicionar uma nova transação fornecendo um nome e um valor. Transações de valor positivo são consideradas receitas, enquanto valores negativos são despesas.
Remover Transações: Cada transação listada possui um botão de exclusão que permite ao usuário remover a transação correspondente.
Visualizar Saldo: O aplicativo exibe o saldo atual, total de receitas e despesas de todas as transações cadastradas.
Persistência de Dados: As transações são armazenadas no localStorage do navegador, permitindo que os dados sejam mantidos mesmo após o fechamento e reabertura do aplicativo.
Estrutura do Código
Seleção de Elementos do DOM: Os elementos do DOM são selecionados e armazenados em variáveis para facilitar a manipulação posterior.
Carregamento de Transações do localStorage: As transações são carregadas do localStorage ao iniciar o aplicativo.
Funções Principais:
removeTransaction(ID): Remove uma transação com base no ID.
addTransactionIntoDOM(transaction): Adiciona uma transação ao DOM.
updateBalanceValues(): Atualiza os valores de saldo, receita e despesa exibidos no DOM.
init(): Inicializa o aplicativo, carregando transações do DOM e atualizando os valores de saldo.
updateLocalStorage(): Atualiza as transações armazenadas no localStorage.
generateID(): Gera um ID aleatório para novas transações.
addToTransactionsArray(transactionName, transactionAmount): Adiciona uma nova transação ao array de transações.
cleanInputs(): Limpa os campos de entrada após o envio do formulário.
handleFormSubmit(event): Manipula o envio do formulário, adicionando uma nova transação e atualizando o DOM e o localStorage.
 
