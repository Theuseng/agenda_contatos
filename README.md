# 📒 Agenda de Contatos

Este é um projeto simples de agenda de contatos em Python. O programa permite que você adicione, edite, exclua, busque e visualize contatos, além de importar e exportar contatos de/para um arquivo CSV.

## 🚀 Funcionalidades

- Mostrar todos os contatos da agenda
- Buscar um contato específico
- Incluir um novo contato
- Editar um contato existente
- Excluir um contato
- Exportar contatos para um arquivo CSV
- Importar contatos de um arquivo CSV

## 📋 Pré-requisitos

Certifique-se de ter o Python instalado em sua máquina. Este projeto foi desenvolvido e testado com a versão 3.x do Python.

## 💻 Como usar

1. **Clone o repositório:**
    ```sh
    git clone https://github.com/Theuseng/agenda_contatos.git
    cd agenda_contatos
    ```

2. **Execute o programa:**
    ```sh
    python agenda.py
    ```

## 📚 Menu de Opções

Ao executar o programa, você verá o seguinte menu:


### Exemplos de Uso

- **Mostrar todos os contatos:**
    - Escolha a opção `1` no menu.

- **Buscar um contato:**
    - Escolha a opção `2` e digite o nome do contato.

- **Incluir um contato:**
    - Escolha a opção `3`, digite o nome do contato e forneça os detalhes (telefone, email, endereço).

- **Editar um contato:**
    - Escolha a opção `4`, digite o nome do contato e atualize os detalhes.

- **Excluir um contato:**
    - Escolha a opção `5` e digite o nome do contato.

- **Exportar contatos para CSV:**
    - Escolha a opção `6` e forneça o nome do arquivo.

- **Importar contatos de CSV:**
    - Escolha a opção `7` e forneça o nome do arquivo.

## 📝 Estrutura do Código

- **mostrar_contatos():** Mostra todos os contatos na agenda.
- **buscar_contato(contato):** Busca e exibe detalhes de um contato específico.
- **ler_detalhes_contato():** Lê os detalhes de um contato (telefone, email, endereço).
- **incluir_editar_contato(contato, telefone, email, endereco):** Adiciona ou edita um contato na agenda.
- **excluir_contato(contato):** Exclui um contato da agenda.
- **exportar_contatos(nome_do_arquivo):** Exporta os contatos para um arquivo CSV.
- **importar_contatos(nome_do_arquivo):** Importa contatos de um arquivo CSV.
- **salvar():** Salva os contatos em um arquivo CSV.
- **carregar():** Carrega os contatos de um arquivo CSV.
- **imprimir_menu():** Imprime o menu de opções.

## 🛠️ Melhorias Futuras

- Implementação de uma interface gráfica.
- Adição de validação de dados de entrada.
- Opção de salvar e carregar contatos de um banco de dados.

---

Feito com ❤️ por [Theuseng](https://github.com/Theuseng)
