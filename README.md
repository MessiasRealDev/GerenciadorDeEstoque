# Gerenciamento de Produtos

**Trabalho Acadêmico**

Este projeto consiste em um sistema simples de gerenciamento de produtos utilizando Java. O sistema permite cadastrar, atualizar, remover produtos, calcular vendas com ou sem desconto, verificar estoque e checar a validade dos produtos armazenados.

## Requisitos
- Java 8 ou superior
- Um arquivo `produtos.txt` para armazenamento dos produtos

## Como Usar

### Compilar o código
Para compilar o código, utilize o seguinte comando no terminal:
```sh
javac Principal.java
```

### Executar o programa
Após compilar, execute o programa com o comando:
```sh
java Principal
```

## Funcionalidades

O programa apresenta um menu interativo com as seguintes opções:

1. **Cadastrar produto**: Permite adicionar um novo produto ao sistema.
2. **Atualizar produto**: Modifica os dados de um produto existente.
3. **Remover produto**: Exclui um produto do banco de dados.
4. **Calcular venda com desconto**: Calcula o preço final de uma venda aplicando um desconto.
5. **Calcular venda sem desconto**: Calcula o preço final sem descontos.
6. **Verificar estoque**: Lista os produtos disponíveis no estoque.
7. **Verificar validade de um produto**: Exibe a validade de um produto específico.
0. **Sair**: Encerra o programa.

## Estrutura do Código

O sistema é composto pelas seguintes classes:

- `Principal`: Contém o menu principal e gerencia a interação do usuário.
- `BancoDeDadosProduto`: Responsável pelo armazenamento e recuperação de produtos.
- `GerenciadorProduto`: Manipula o cadastro, atualização e remoção de produtos.
- `CalculadoraVenda` e `CalculadoraVendaImpl`: Realizam o cálculo de preços de venda.
- `GerenciadorEstoque`: Monitora a disponibilidade e validade dos produtos.
- `Produto`: Representa um produto com atributos como ID, nome, preço, quantidade e validade.

## Tratamento de Erros
O sistema possui tratamento de erros para entradas inválidas, como números inválidos ou produtos inexistentes, garantindo uma experiência de uso mais segura.

## Melhorias Futuras
- Implementação de interface gráfica.
- Suporte a banco de dados SQL para persistência dos produtos.
- Relatórios de vendas e estoque.

## Autor
Desenvolvido por **Diego Messias**.
