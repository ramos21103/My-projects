 Gerenciador de Lista de Compras

Um aplicativo de terminal interativo construído em Python para criar e gerenciar uma lista de compras. 

Este projeto foi desenvolvido como um marco inicial no aprendizado de Python, focado na aplicação direta de **Estruturas de Dados (Listas)** e controle de fluxo, antes da introdução à modularização por funções.

 Funcionalidades

O sistema roda em um loop contínuo e interativo, permitindo ao usuário:
- **Adicionar itens:** Insere novos produtos na lista usando o método `.append()`.
- **Remover o último item:** Utiliza o método `.pop()` para desfazer rapidamente a última adição do carrinho.
- **Remover um item específico:** Busca e deleta um item exato pelo nome usando o método `.remove()`.
- **Visualizar a lista:** Exibe o estado atual da lista de compras na tela.
- **Validação de entrada:** O sistema avisa o usuário caso uma opção fora do menu (1 a 5) seja digitada.
- **Sair do sistema:** Encerra o loop e finaliza o programa de forma limpa.

 🛠️ Tecnologias e Conceitos Utilizados

- **Python 3**
- Estruturas de Dados: `Listas`
- Estruturas de Repetição: `while True`
- Estruturas Condicionais: `if`
- Operadores Lógicos: `and`, `!=` (para validação do menu)
- Interação com usuário via Terminal (`input`, `print`)

 💻 Como executar o projeto

1. Certifique-se de ter o Python instalado no seu computador.
2. Baixe o arquivo principal do projeto (ex: `compras.py`).
3. Abra o terminal e navegue até a pasta onde o arquivo foi salvo.
4. Rode o comando:
   ```bash
   python compras.py
