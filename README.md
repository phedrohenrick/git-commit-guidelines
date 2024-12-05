# Git Commit Guidelines

Essa referência foi baseada em dois documentos importantes:

- [Karma Runner](http://karma-runner.github.io/6.4/dev/git-commit-msg.html)  
- [Conventional Commits](https://www.conventionalcommits.org/)

Simplifiquei o conteúdo para refletir o que é mais usado no dia a dia das empresas e boas práticas que funcionaram bem na minha experiência.

## Formato (Format)
Os commits devem seguir o formato abaixo, onde **`type`** é obrigatório. Ele indica o propósito do commit, e **`description`** detalha a ação realizada:

- **Formato (Português):**  
  `tipo: Descrição;`  

- **Format (English):**  
  `<type>: <description>;`

---

## Tipos de Commits (Commit Types)

### Português
Aqui estão os tipos mais comuns para o **`type`**:

| Tipo        | Descrição             | Quando Usar                                                                |
|-------------|-----------------------|----------------------------------------------------------------------------|
| **feat**    | Funcionalidades       | Adicionar uma nova funcionalidade.                                        |
| **fix**     | Correção de Bugs      | Corrigir um erro existente.                                               |
| **docs**    | Documentação          | Alterações exclusivamente na documentação.                                |
| **style**   | Estilização           | Mudanças que não afetam o comportamento do código (ex.: formatação, espaços). |
| **refactor**| Refatoração           | Reestruturar o código sem mudar sua funcionalidade ou corrigir bugs.      |
| **perf**    | Otimização            | Alterações que melhoram o desempenho.                                     |
| **test**    | Testes                | Adicionar ou corrigir testes.                                             |
| **build**   | Configuração de Build | Mudanças em scripts ou ferramentas de build (ex.: gulp, npm).             |
| **ci**      | Integração Contínua   | Alterações em arquivos/configurações de CI (ex.: Travis, CircleCI).       |
| **chore**   | Tarefas Gerais        | Mudanças que não afetam código-fonte ou testes.                           |
| **revert**  | Reversão              | Desfazer um commit anterior.                                              |

---

### English
Here are the most common types for **`type`**:

| Type        | Description           | When to Use                                                                 |
|-------------|-----------------------|-----------------------------------------------------------------------------|
| **feat**    | Features              | Add a new feature.                                                         |
| **fix**     | Bug Fixes             | Fix an existing bug.                                                       |
| **docs**    | Documentation         | Changes exclusively in the documentation.                                  |
| **style**   | Styling               | Changes that do not affect the behavior of the code (e.g., formatting, spaces). |
| **refactor**| Refactoring           | Restructure code without changing functionality or fixing bugs.            |
| **perf**    | Optimization          | Changes that improve performance.                                          |
| **test**    | Tests                 | Add or correct tests.                                                      |
| **build**   | Build Configurations  | Changes in build scripts or tools (e.g., gulp, npm).                       |
| **ci**      | Continuous Integration| Changes in CI files/configurations (e.g., Travis, CircleCI).               |
| **chore**   | General Tasks         | Changes that do not affect source or test files.                           |
| **revert**  | Reverting             | Undo a previous commit.                                                    |

---

## Autor (Author) ✒️  
**Phedro Henrick**
