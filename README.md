[README.md](https://github.com/user-attachments/files/31110337/README.md)
# Sistema-Vendas-Livraria
Sistema em Python, via terminal, para gerenciar o estoque e as vendas de uma livraria: consulta de livros disponíveis, cálculo de pagamento com troco, cadastro de novos títulos e remoção de itens do estoque.
# 📚 Sistema de Vendas para Livraria

Sistema em Python, via terminal, para gerenciar o estoque e as vendas de uma livraria: consulta de livros disponíveis, cálculo de pagamento com troco, cadastro de novos títulos e remoção de itens do estoque.

## Funcionalidades

- **Realizar venda**: exibe o catálogo, calcula o valor do livro escolhido e conduz o fluxo de pagamento (Dinheiro, Débito ou Crédito), incluindo cálculo de troco ou verificação de valor insuficiente.
- **Cadastrar livro**: adiciona um novo título ao estoque com nome e preço, evitando duplicidade.
- **Remover livro**: exclui um título do estoque a partir do nome.
- **Menu interativo**: navegação simples via terminal com opções numeradas.

## Tecnologias

- Python 3 (sem bibliotecas externas)
- Armazenamento em memória, usando dicionário (`dict`)

## Como executar

```bash
python trabalho.py
```

Basta ter o Python 3 instalado — não há dependências adicionais.

## Exemplo de uso

```
========================================
          LIVRARIA - MENU PRINCIPAL
========================================
  1 - Realizar venda
  2 - Cadastrar livro
  3 - Remover livro
  0 - Sair
========================================
Escolha uma opção: 1
```


- Validação de entrada mais robusta (ex.: tratamento de erros ao digitar texto em campos numéricos)

## Autor

Matheus Sayegh — Estudante de Engenharia de Software (PUCPR)
[LinkedIn](https://www.linkedin.com/in/matheus-sayegh-5772b93b3) · [GitHub](https://github.com/matheusayegh)
