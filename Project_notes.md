# Padrão de Projeto VO (Value Object)
Em virtude das iterações entre bancos de dados e clients precisamos proteger a estrutura do banco de dados que foi definida na entidade, deste modo utilizamos uma arquitetura de mapping, que opera no middleware entre o client e a entidade, protegendo a estrutura e convertendo a estrutura dos dados recebidos e enviados pelas requests.
O modelo de Value object permite alterarmos as estruturas, mudando os atributos e manipulando os dados de modo que a informação pode ser adequada para as finalidades às quais se destina sem a necessidade de alterarmos os atributos da entidade, como, por exemplo, separando nome e sobrenome na entidade mas recebendo ambos em um campo único na requisição. Essa estratégia, além de agregar uma camada de segurança permite formatações de dados diferentes entre diversas API's, o que serve muitas vezes em cenários de migração ou comportamentos distintos entre uma e outra solução dentro da nossa aplicação.


