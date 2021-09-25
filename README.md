# phpUnit

Projeto com exemplos de testes unitários.
O projeto foi implementado utilizando PHP 7.2

## Comandos úteis
- Para executar os testes: `vendor\bin\phpunit --colors tests`
- Para instalação do phpUnit no projeto: `composer require --dev phpunit/phpunit ^8.1`
- Uma classe nova deve finalizar com a palavra Test. Como por exemplo AvaliadorTest.php
- O método para ser executado no teste deve começar com testNomeMetodo.
- Exemplo Para executar um teste específico: `vendor/bin/phpunit --colors --filter AvaliadorTest` ou `vendor/bin/phpunit --colors --filter AvaliadorTest::testAvaliadorDeveEncontrarOMaiorValorDeLances`
