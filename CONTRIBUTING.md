# Guia de Contribuição para o ERPNinja

Obrigado pelo interesse em contribuir com o ERPNinja! Este documento fornece diretrizes para contribuir com o projeto.

## Código de Conduta

Ao participar deste projeto, você concorda em seguir nosso [Código de Conduta](CODE_OF_CONDUCT.md).

## Como Contribuir

### Reportando Bugs

1. Verifique se o bug já não foi reportado na seção de Issues.
2. Use o template de bug report para criar uma nova issue.
3. Descreva claramente o problema, incluindo passos para reproduzi-lo.
4. Inclua screenshots ou logs se possível.

### Sugerindo Melhorias

1. Verifique se a melhoria já não foi sugerida na seção de Issues.
2. Use o template de feature request para criar uma nova issue.
3. Descreva claramente a melhoria e como ela beneficiaria o projeto.

### Pull Requests

1. Faça um fork do repositório.
2. Crie uma branch a partir da `main`:
   ```bash
   git checkout -b feature/sua-feature
   ```
3. Faça suas alterações seguindo as convenções de código.
4. Adicione testes para suas alterações quando aplicável.
5. Execute os testes para garantir que tudo está funcionando:
   ```bash
   composer test
   npm run test
   ```
6. Commit suas alterações seguindo as [convenções de commit](#convenções-de-commit).
7. Push para sua branch:
   ```bash
   git push origin feature/sua-feature
   ```
8. Abra um Pull Request para a branch `main` do repositório original.

## Convenções de Código

- Siga o PSR-12 para código PHP.
- Use camelCase para métodos e variáveis.
- Use PascalCase para classes.
- Documente todas as classes e métodos públicos.
- Escreva testes para novas funcionalidades.

## Convenções de Commit

Usamos [Conventional Commits](https://www.conventionalcommits.org/) para padronizar nossas mensagens de commit:

- `feat`: Nova funcionalidade
- `fix`: Correção de bug
- `docs`: Alterações na documentação
- `style`: Alterações que não afetam o código (formatação, etc)
- `refactor`: Refatoração de código
- `perf`: Melhorias de performance
- `test`: Adição ou correção de testes
- `chore`: Alterações no processo de build ou ferramentas auxiliares

Exemplo:
```
feat(módulo-financeiro): adiciona relatório de fluxo de caixa
```

## Processo de Revisão

- Todos os Pull Requests serão revisados por pelo menos um mantenedor.
- Feedback será dado o mais rápido possível.
- Após aprovação, um mantenedor fará o merge do PR.

## Recursos Adicionais

- [Documentação do Laravel](https://laravel.com/docs)
- [Documentação do Vue.js](https://vuejs.org/guide/introduction.html)
- [Documentação do Tailwind CSS](https://tailwindcss.com/docs)

Obrigado por contribuir com o ERPNinja!