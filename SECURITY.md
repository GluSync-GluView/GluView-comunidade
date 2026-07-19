# Política de segurança

## ⚠️ Isto não é um canal de emergência

Se você está tendo uma emergência de saúde, **procure atendimento médico real imediatamente**.
Este repositório e seus canais (issues, discussions, relato de vulnerabilidade) não são
monitorados em tempo real e não substituem atendimento médico.

## Versões suportadas

O projeto ainda não tem um processo de release com número de versão público formal — o
desenvolvimento é contínuo. "Versão suportada", por enquanto, significa **a última versão
implantada em produção**. Isso será refinado quando um processo de release formal existir (ver
[`ROADMAP.md`](ROADMAP.md)).

## Como reportar uma vulnerabilidade ou incidente de privacidade

**Nunca abra uma issue pública** para reportar uma vulnerabilidade de segurança (falha de
autenticação, acesso indevido a dado de terceiro, injeção, exposição de segredo) ou um incidente
de privacidade (dado de saúde exposto indevidamente). Uma issue pública torna o problema visível
antes que haja tempo de corrigi-lo.

Use um destes canais privados:

1. **GitHub Private Vulnerability Reporting** — na aba "Security" deste repositório, "Report a
   vulnerability". Preferencial: fica registrado de forma estruturada e privada, mesmo que o
   código afetado esteja em outro repositório do projeto (GluView, GluSync ou GluWebView).
2. **E-mail**: `glusync.gluview@gmail.com` — alternativa ao PVR, mesmo compromisso de resposta.

Descreva o problema com o máximo de detalhe técnico possível **sem incluir** token, senha, cookie
de sessão válido, ou dado de saúde de qualquer pessoa real na mensagem — descreva o tipo de dado
exposto, não o valor.

## O que esperar depois de reportar

- **Confirmação de recebimento em até 5 dias úteis.**
- Não há prazo público prometido de correção — depende da gravidade e complexidade. Você será
  informado quando a correção estiver disponível.
- Não publicamos aviso de segurança detalhado (advisory) antes da correção estar implantada e
  coordenada com quem reportou, quando aplicável.

## Escopo

Vulnerabilidades nos três produtos do projeto (GluView, GluSync, GluWebView), incluindo a API
pública documentada. Problemas de configuração do seu próprio ambiente (ex.: sensor mal pareado)
não são vulnerabilidade de segurança — use as [Issues](../../issues/new/choose) normais para isso.
