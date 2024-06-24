<h1>WebApp para Controle Financeiro</h1>

<p>WebApp desenvolvido em JavaScript para gerenciar transações financeiras. O aplicativo permite ao usuário adicionar, remover e visualizar transações, exibindo os valores totais de receitas, despesas e saldo atual. As transações são armazenadas no localStorage do navegador, permitindo que os dados persistam entre sessões.</p>

<h2>Funcionalidades</h2>
<ul>
<li>Adicionar Transações: O usuário pode adicionar uma nova transação fornecendo um nome e um valor. Transações de valor positivo são consideradas receitas, enquanto valores negativos são despesas.</li>
</li>Remover Transações: Cada transação listada possui um botão de exclusão que permite ao usuário remover a transação correspondente.</li>
<li>Visualizar Saldo: O aplicativo exibe o saldo atual, total de receitas e despesas de todas as transações cadastradas.</li>
<li>Persistência de Dados: As transações são armazenadas no localStorage do navegador, permitindo que os dados sejam mantidos mesmo após o fechamento e reabertura do aplicativo.</li>
<h2>Estrutura do Código</h2>
<li>Seleção de Elementos do DOM: Os elementos do DOM são selecionados e armazenados em variáveis para facilitar a manipulação posterior.</li>
<li>Carregamento de Transações do localStorage: As transações são carregadas do localStorage ao iniciar o aplicativo.</li>
</ul>
<h2>Funções Principais:</h2>
<ul>
<li>removeTransaction(ID): Remove uma transação com base no ID.</li>
<li>addTransactionIntoDOM(transaction): Adiciona uma transação ao DOM.</li>
<li>updateBalanceValues(): Atualiza os valores de saldo, receita e despesa exibidos no DOM.</li>
<li>init(): Inicializa o aplicativo, carregando transações do DOM e atualizando os valores de saldo.</li>
<li>updateLocalStorage(): Atualiza as transações armazenadas no localStorage.</li>
<li>generateID(): Gera um ID aleatório para novas transações.</li>
<li>addToTransactionsArray(transactionName, transactionAmount): Adiciona uma nova transação ao array de transações.</li>
<li>cleanInputs(): Limpa os campos de entrada após o envio do formulário.</li>
<li>handleFormSubmit(event): Manipula o envio do formulário, adicionando uma nova transação e atualizando o DOM e o localStorage.</li>
</ul>
 
