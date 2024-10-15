# Projeto Final de Conclusão do Curso - EBAC

Este repositório contém o **Projeto Final** de conclusão do curso **Engenheiro de Qualidade de Software** da EBAC. Ele é composto por três projetos principais, relacionados às funcionalidades de um e-commerce, e um **Trabalho de Conclusão de Curso (TCC)** que aprofunda conceitos e práticas de Qualidade de Software.

## Projetos

### 1. **Adicionar Item ao Carrinho - US001**
- **Descrição**: Implementação e automação da funcionalidade que permite ao usuário adicionar um item ao carrinho de compras.
- **Objetivo**: Garantir que os itens selecionados pelo usuário sejam corretamente adicionados ao carrinho e que o processo de compra seja iniciado.
- **Cenários Testados**:
  - Adicionar item ao carrinho com sucesso.
  - Tentativa de adicionar item indisponível.
  - Verificação da atualização correta da quantidade no carrinho.

### 2. **Login na Plataforma - US002**
- **Descrição**: Automação do processo de login de usuários registrados na plataforma.
- **Objetivo**: Validar que o sistema permite o login de usuários com credenciais válidas, e que mensagens de erro apropriadas são exibidas em caso de falha.
- **Cenários Testados**:
  - Login com credenciais válidas.
  - Tentativa de login com senha incorreta.
  - Recuperação de senha via e-mail.

### 3. **API de Cupons - US003**
- **Descrição**: Criação e testes de uma API para gerenciamento de cupons de desconto no e-commerce.
- **Objetivo**: Garantir que a API de cupons funcione corretamente, permitindo a criação, consulta e aplicação de cupons de desconto em compras.
- **Cenários Testados**:
  - Criação de cupons válidos.
  - Validação de cupons expirados.
  - Aplicação de cupons com restrições de uso (valor mínimo de compra, número de usos).

## Trabalho de Conclusão de Curso (TCC)

O **TCC** aborda os principais conceitos e práticas de **Engenharia de Qualidade de Software**, focando em automação de testes, boas práticas de desenvolvimento de software, e a importância da entrega contínua (CI/CD). Entre os tópicos abordados estão:

- Introdução à Qualidade de Software.
- Planejamento estratégico de testes e cobertura.
- Automação de testes em sistemas frontend, backend e APIs.
- Ferramentas: Cypress, PactumJS, Postman.
- Integração de pipelines de CI/CD..

## Estrutura do Repositório

```bash
├── US001_Adicionar_Item_Carrinho/
├── US002_Login_Plataforma/
├── US003_API_Cupons/
└── TCC_Engenheiro_Qualidade_Software/

