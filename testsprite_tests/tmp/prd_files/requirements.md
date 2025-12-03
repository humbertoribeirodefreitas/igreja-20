# Requisitos do CMS Painel

## Autenticação
- Proteger rotas do painel com `ProtectedRoute` e chave `localStorage.isAuthenticated`.

## Edição de Conteúdo
- Editar Home em `HomeEditor` e salvar via `saveHomeData`.
- Editar Rodapé em `FooterEditor` e salvar via `saveFooterData`.
- Editar Ministérios em `MinistryEditor` e salvar via `saveMinistry`.

## Gerenciar Páginas Dinâmicas
- Listar páginas via `getPages`.
- Adicionar página com `addPage`.
- Atualizar status com `updatePage`.
- Deletar página com `deletePage`.
- Exibir rotas dinâmicas quando `type=dynamic` e `status=online`.

## Persistência Supabase
- Usar tabela `app_content` com `key` e `value` JSON.
- `DatabaseService.fetchItem` e `saveItem` devem funcionar.

## UI e Navegação
- Painel em `/painel/*` com layout e navegação.
- Visualizar alterações refletidas nas páginas públicas.
