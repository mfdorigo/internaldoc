# Guia de Comentários e Padrões de Commit

## Tipos de Comentários

- **Correção de Bug**: 
  - `fix: Resolve typo in user registration`
  - `fix: Fix null pointer exception in payment processing`

- **Nova Funcionalidade**: 
  - `feat: Add user profile page`
  - `feat: Implement search feature for articles`
  - `feat: Introduce dark mode option`

- **Refatoração de Código**: 
  - `refactor: Update authentication logic`
  - `refactor: Simplify file upload handling`
  - `refactor: Extract common method for data processing`

- **Melhorias**: 
  - `perf: Enhance data fetching performance`
  - `perf: Optimize database query for faster response`
  - `perf: Improve caching strategy`

- **Documentação**: 
  - `docs: Update README instructions`
  - `docs: Add API usage examples`
  - `docs: Include troubleshooting guide`


## Padrões de Commit

- **Use o tempo presente imperativo**: 
  - Correto: `Add user login feature`
  - Errado: `Added user login feature`

- **Seja conciso e claro**: 
  - Correto: `Fix null pointer exception`
  - Errado: `Fixed a bug`

- **Inclua contexto quando necessário**:
  - `Update dependencies to latest versions`
  - `Refactor file handling: update search mode, add 30-minute delay, and remove start time`

## Exemplo de Boas Práticas

```plaintext
feat: Add user login feature
fix: Correct null pointer exception
refactor: Simplify file upload handling
docs: Update README instructions
perf: Enhance data fetching performance
style: Format code to comply with style guide
test: Add unit tests for user profile component
