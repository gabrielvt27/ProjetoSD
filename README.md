# Projeto Sistemas Distribuídos

## My Party

### Descrição

A aplicação tem a finalidade de facilitar a criação e o controle de eventos/festas, sendo possível também realizar a venda de ingressos para tais eventos e participar de eventos de outros usuários. 

### Funcionamento

Na aplicação, qualquer usuário cadastrado poderá criar um evento e ter a seu dispor todas as informações para o gerenciamento e controle do evento, como por exemplo: lista de interessados, lista de inscritos, lista de presença, pagamentos de inscrições, entre outros. Também será possível que os usuários se inscrevam em eventos de outros usuários, efetuem pagamento de suas inscrições e obtenham seu ingresso do evento.

### Componentes

1. **Devices**
   * Cliente Web (Browser)
   * Smartphone (Browser mobile)
2. **Server**
   * Servidor de aplicação (Tomcat)
3. **Store**
   * Banco de Dados
   
**Testes**

* **Demostração de funcionalidade:** mostrar que o CRUD (Create, Read, Update e Delete) de usuários e eventos foram implementadas, demostrar o funcionamento da venda de ingressos e a inscrição de um usuário em um evento.
* **Teste de recuperação de falhas:** mostrar que se a aplicação falhar, não haverá nenhum estado inesperado, como perca de informações das listas de interessados, inscritos e presença, perca de pagamentos de inscrições em um evento.
* **Teste de concorrência:** mostrar que diversos usuários consigam utilizar a aplicação simultaneamente sem problemas, ou seja, deve ser possível que vários usuários consigam se cadastrar, se inscrever em um evento, gerenciar seus eventos, pagar inscrições, entre outras funções ao mesmo tempo sem ocorrer erros.
* **Teste de carga:** verificar o volume de transações, acessos simultâneos ou usuários a aplicação suporta sem que haja perda de performace.
