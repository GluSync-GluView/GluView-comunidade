# Governança

## Mantenedores

Hoje, **Felipe é o único mantenedor** do projeto — única pessoa com poder de aprovar releases e
avisos de segurança. Isso reflete o estado real do projeto, não uma estrutura permanente; será
atualizado se um segundo mantenedor for adicionado.

## Processo de decisão

Decisões técnicas e de produto relevantes (mudança de finalidade, contrato público, retenção de
dado, publicação externa, comportamento de alerta) são registradas como **ADR** (Architecture
Decision Record) no repositório interno do projeto. Este repositório de comunidade reflete o
resultado dessas decisões (roadmap, changelog), não o processo interno de decisão em si.

## Revisão

Como há um único mantenedor hoje, não existe revisão por terceiros antes de merge — o mantenedor
autorevisa. Isso é uma limitação reconhecida, não um objetivo; será revisado se um segundo
mantenedor entrar no projeto.

## Conflito de interesse

Não aplicável enquanto houver um único mantenedor. Será documentado quando deixar de ser o caso.

## Ciclo de vida de issues

1. **Nova issue** → label `needs-triage`.
2. Mantenedor avalia: pode virar `accepted` (será trabalhada), `needs-info` (falta detalhe do
   autor), `blocked` (depende de algo externo), ou ser fechada como `wontfix`/`duplicate`.
3. `needs-info` sem resposta do autor por **60 dias** → fechada automaticamente com nota
   explicando o motivo e como reabrir.
4. `wontfix` sempre vem com uma explicação do porquê, nunca fechada sem comentário.

## Cadência de triagem

**Best-effort, sem SLA prometido** — exceto para relatos de vulnerabilidade/privacidade via
canal privado (`SECURITY.md`), que têm confirmação garantida em até 5 dias úteis. Issues e
discussions comuns não têm prazo de resposta prometido, dado que o projeto é mantido por uma
única pessoa.

## Rótulos (labels)

**Tipo**: `bug`, `feature`, `docs`, `security-private` (uso interno do mantenedor, nunca aplicado
a uma issue pública que discuta uma vulnerabilidade em aberto), `accessibility`.

**Área**: `web`, `android`, `backend`, `api`, `alerts`, `caregiver`, `i18n`, `infra`.

**Status**: `needs-triage`, `needs-info`, `accepted`, `blocked`.

**Prioridade** (critério objetivo, não subjetivo):
- `priority: high` — perda de dado ou acesso indevido a dado de terceiro.
- `priority: medium` — funcionalidade quebrada, sem perda ou exposição de dado.
- `priority: low` — melhoria, cosmético, ou pedido de funcionalidade nova.

**Idioma**: `lang: pt-BR`, `lang: en`, `lang: es` — usado em issues de tradução/documentação.

## Dado sensível publicado por engano

Se alguém publicar dado de saúde real, token, senha ou outro dado sensível em uma issue ou
discussion pública: o mantenedor edita ou oculta o conteúdo imediatamente (sem aviso prévio, para
conter a exposição), comenta pedindo desculpas pela experiência e orienta a pessoa a nunca
reenviar esse tipo de dado, mesmo em canal privado de suporte.

## Releases

Cobertos em [`CHANGELOG.md`](CHANGELOG.md) e no template de release notes de cada repositório de
código. Só o mantenedor único pode publicar uma release ou aviso de segurança.
