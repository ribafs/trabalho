# Recomendações diversas para um melhor código

- Tenha em mente uma atitude voltada para a produtividade nas várias áreas que trabalha e estuda

- Usar uma boa IDE (Eclipse PDT ou Netbeans) ou editor de código (VSCode)

- Usar bons templates para a criação de sites

- Usar snippets de código testados e prontos para uso

- Guardar bons exemplos testados e funcionando

- Ter uma boa biblioteca de funções e classes úteis testadas e prontas para uso

- Manter uma boa referência de todas as dependências de terceiros com que trabalha. Tanto seus sites quanto documentação de instalação, configuração e uso

- Mantenha um favoritos organizado por pastas em seu navegadotr

- Confie em sua memória, em sua inteligência e em sua criatividade para que assim possa reforçar estes fatores e melhor-alos, visto que são execlentes auxiliares

- Em ambiente de desenvolvimento no desktop sempre habilite ao máximo a exibição de erros no php.ini

- Estudar sobre os vários recursos para tratamento de erros

- Ao trabalhar com bancos de dados use uma abstração como PDO ou Doctrine, que facilitam a migração para outros SGBD

- Mantenha os includes do javascript sempre ao final da página (acima da tag </body>)

- Ative sempre que puder recursos de cache

- Não use tag de fechamento (?>) em scripts contendo somente PHP

- Nunca execute consultas dentro de laços

- Não use * em consultas SQL, ao contrário especifique cada campo: SELECT * FROM clientes; Melhor: SELECT name,email,ssn FROM clientes;

- Nunca confie em entradas de usuários: filtre todas as entradas, todos os campos, por nome, tipos, tamanho, etc. As fuções filter_*, filter_var() são ótimas.
https://www.php.net/manual/pt_BR/book.filter.php

- Não exagere em seus cuidados com o código: Você pode conseguir economizar 0,01 segundo extra de cada carregamento de página encurtando tudo para variáveis de uma letra, usando lógica ternária de vários níveis e outra inteligência, mas isso realmente não é nada em comparação com as dores de cabeça que você estará causando a si mesmo e a todos ao redor vocês.

- Existe muita coisa já pronta, muitos componentes e respostas para praticamente qualquer dúvida, portanto não perca muito tempo tentando resolver um problema que talvez resolva rápido com uma pesquisa

- Idealmente para trabalhar com PHP precisamos conhecer Composer, Git, IDE/Editor, HTML, CSS, JavaScript, Bootstrap, MySQL, SQLite, PostgreSQL, algum bom CMS e um bom framework para saber o que usar ou os que usar em cada projeto. Também é importante conhecer os recursos de PHP e suas limitações para quando for o caso poder procurar outra linguagem.

- A orientação a objetos é boa para abstrair problemas e encapsular soluções em classes de objetos, mas a maneira como certos ORMs funcionam adiciona sobrecarga desnecessária.

