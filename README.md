# Desafio Back-End Prefeitura Virtual
Primeiramente, obrigado pelo seu interesse em trabalhar na melhor ferramenta de tecnologia para que o município possa atender melhor seus cidadãos!

Abaixo você encontrará todos as informações necessárias para iniciar o seu teste.

# Avisos antes de começar
  * Crie um repositório no seu GitHub sem citar nada relacionado ao Prefeitura Virtual.
  * Faça seus commits no seu repositório.
  * Você poderá consultar o Google, Stackoverflow ou algum projeto particular na sua máquina.
  * Fique à vontade para perguntar qualquer dúvida aos recrutadores.
  * Fique tranquilo, respire, assim como você, também já passamos por essa etapa. Boa sorte! :)
 
 # Setup do projeto
  * PHP : 8.1
  * Laravel : 9.x
  * PostgreSQL: 13

A utilização do Laravel na versões acima é obrigatória.

# Objetivo 

Temos 2 tipos de usuários, os comuns e lojistas, ambos têm carteira com dinheiro e realizam transferências entre eles. 

Requisitos:

 * Para ambos tipos de usuário, precisamos do Nome Completo, CPF, e-mail e Senha. CPF/CNPJ e e-mails devem ser únicos no sistema. Sendo assim, seu sistema deve permitir apenas um cadastro com o mesmo CPF ou endereço de e-mail.

 * Usuários comuns podem realizar depósitos.
 
 * Usuários podem enviar dinheiro (efetuar transferência) para lojistas e entre usuários.

 * Lojistas só recebem transferências, não enviam dinheiro para ninguém.

 * A operação de transferência deve ser uma transação (ou seja, revertida em qualquer caso de inconsistência) e o dinheiro deve voltar para a carteira do usuário que   envia.

 * Este serviço deve ser RESTFul.

# Orientações 

 * Faça commits regulares. Eles são melhores do que um commit gigantesco. Gostaríamos de ver commits organizados e padronizados, então capriche neles!
 * Documentação
 * Código limpo e organizado (nomenclatura, etc)
 * Conhecimento de padrões (PSRs, design patterns, SOLID)
 * Ser consistente e saber argumentar suas escolhas
 * Apresentar soluções que domina
 * Modelagem de Dados
 * Manutenibilidade do Código
 * Tratamento de erros
 * Cuidado com itens de segurança
 * Arquitetura (estruturar o pensamento antes de escrever)
 * Carinho em desacoplar componentes (outras camadas, service, repository)

De acordo com os critérios acima, iremos avaliar seu teste para avançarmos para a entrevista técnica. Caso não tenha atingido aceitavelmente o que estamos propondo acima, não iremos prosseguir com o processo.
 
# Materiais úteis
  * https://refactoring.guru/refactoring
  * http://br.phptherightway.com/
  * https://www.php-fig.org/psr/psr-12/
  * https://docs.guzzlephp.org/en/stable/request-options.html
  * https://laravel.com/docs/9.x
  * https://www.php.net/
