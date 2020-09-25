# Desafio Front-End #

Nesse desafio, a tarefa é implementar um CRUD de Tickets, sendo listados e gerenciados em um quadro Kanban.

Um Ticket consiste de uma ocorrência de algum problema, com os seguintes campos:

* Descrição: Texto - uma descrição do problema
* Tipo: Select com opções "Bem", "Procedimento" e "Predial"
* Responsável: Select com nomes de usuários
* Campo para imagem será um diferencial

O kanban deverá conter 4 colunas, que representarão os status do ticket: Aberto, Executado, Vistoriado e Arquivado.
* Cada ticket deverá aparecer como card no kanban.
* Todo novo ticket deve ter o status aberto e ser incluído na coluna "Aberto".
* O card deverá conter um botão de opções, com as opções de editar e excluir o ticket.
* O card poderá ser movido para outra coluna, porém seguindo o seguinte fluxo: Aberto > Executado > Vistoriado > Arquivado;
* Ao mover o card para outra coluna, deverá exibir um modal de alerta para o usuário confirmar se deseja realizar a operação.

Os registros deverão ser armazenados na memória do navegador, de forma que os dados não se percam ao atualizar a página.

O projeto deverá ser implementando em Javascript, utilizando React JS com Redux para gerência de estado.

Para dar início ao desafio, o candidato deve dar um fork no repositório e, ao fim do desenvolvimento, dar acesso ao usuário **_joel@trilogo.com.br_** ao seu repositório para análise do trabalho.


**Extras**

* Utilização de React Hooks
* Implementação de testes unitários
* CSS Modules
* Utilização do Ant Design (biblioteca React UI)

Os itens extras (opcionais) contarão positivamente na análise do seu desafio.

Arquivos de layout:

