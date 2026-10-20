# API de produtos

## Requisitos

- PHP 8.3 ou superior
- Composer

## Instalar dependências

Na raiz do projeto, execute:

```bash
composer install
```

## Executar os testes

Para executar todos os testes:

```bash
./vendor/bin/phpunit tests
```

Para executar somente os testes de produtos:

```bash
./vendor/bin/phpunit tests/ProdutoTest.php
```

Para executar um teste específico:

```bash
./vendor/bin/phpunit --filter testDeleteProdutoPorId tests/ProdutoTest.php
```

Os testes usam o Slim diretamente e não precisam que o servidor web esteja iniciado.
