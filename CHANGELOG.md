# CHANGELOG

## 2025-06-28

### Melhorias e Correções

- **Correção de Renderização de Páginas:**
  - Adicionado `baseurl` ao `_config.yml` para corrigir problemas de estilo no GitHub Pages.
  - Adicionado o front matter YAML ao `guia_mcp.md` para garantir a renderização correta como página HTML.
  - Corrigido o link em `index.md` para apontar para `guia_mcp.html`, resolvendo o erro 404.

- **Melhorias Visuais e Tema:**
  - Criada uma Issue no GitHub para rastrear a tarefa de melhoria visual e implementação de tema escuro.
  - Alterado o tema Jekyll de 'just-the-docs' para 'Justice' no `_config.yml`.
  - Removido o diretório `_sass` e seu conteúdo, que eram específicos do tema anterior.

- **Gerenciamento de Dependências:**
  - Atualizada a versão do Jekyll para `4.3.4` no `Gemfile` para resolver a incompatibilidade de versão que causava falha no build do GitHub Actions.
  - Removida a dependência do tema 'just-the-docs' do `Gemfile`.

### Outros

- Adicionada uma seção de 'Novidades Recentes' ao `README.md`.
- Criado este `CHANGELOG.md` para um registro detalhado das alterações.