# Como contribuir

Obrigado pelo interesse em ajudar o GluView/GluSync. A situação atual do projeto muda um pouco o
fluxo usual de contribuição de código aberto — leia esta página antes de abrir uma issue ou
discussão para saber o que esperar.

## O que é possível hoje

- **Reportar um bug** — [abra uma issue](../../issues/new/choose) usando o formulário de bug.
  Descreva com passos reproduzíveis e, se possível, **dados sintéticos** (nunca sua própria
  glicemia real, nome, e-mail ou token — veja o aviso de privacidade em cada formulário).
- **Sugerir uma funcionalidade** — [abra uma issue](../../issues/new/choose) usando o formulário
  de feature request, ou inicie uma [Discussion](../../discussions) se quiser conversar antes de
  formalizar o pedido.
- **Reportar erro de tradução ou de documentação** (português, inglês, espanhol) — formulário
  dedicado nas issues.
- **Reportar incompatibilidade de sensor/integração** — formulário dedicado, com campos
  específicos de modelo de sensor e versão de app.
- **Discutir uso, configuração ou dúvida geral** — [Discussions](../../discussions).

## O que é diferente aqui

Os repositórios de código-fonte (GluView, GluSync, GluWebView) **continuam privados** por
enquanto (veja o porquê no [`README.md`](README.md)). Isso significa que, hoje, **não é possível
abrir um pull request diretamente contra o código** como em um projeto open source tradicional.

Na prática, se você quiser contribuir além de reportar um problema:

1. Abra uma issue ou discussion descrevendo o que gostaria de mudar/adicionar.
2. O mantenedor avalia e decide se aceita a contribuição.
3. Se aceita, a mudança é implementada internamente (pelo mantenedor, ou por você mediante convite
   individual ao repositório privado correspondente — não é um convite automático).

Isso é uma limitação real do estágio atual do projeto, não uma formalidade — sendo honesto sobre
isso agora para não prometer um fluxo de PR aberto que ainda não existe.

## Antes de reportar

- Busque nas issues e discussions existentes para evitar duplicata — cada formulário pede
  confirmação de que essa busca foi feita.
- Nunca inclua, em issue ou discussion: token, senha, cookie de sessão, log completo do
  aplicativo, ou qualquer dado de saúde (sua glicemia real, nome de paciente, e-mail cadastrado).
  Use dados sintéticos e óbvios (ex.: `glicemia = 120`, `usuário teste`) ao descrever um problema.
- Se o que você encontrou é uma **vulnerabilidade de segurança ou incidente de privacidade**
  (dado exposto, acesso indevido, falha de autenticação), **não abra uma issue pública** — veja
  [`SECURITY.md`](SECURITY.md).

## Testes e dados sintéticos

Se e quando um repositório de código se tornar público, contribuições de código deverão seguir a
mesma disciplina já usada internamente: nunca usar dado real de paciente em teste, seed,
screenshot ou log; testes automatizados cobrindo a mudança proporcionalmente ao seu tamanho.
