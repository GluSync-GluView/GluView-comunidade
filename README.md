# GluView — comunidade

Este repositório é o espaço público de comunidade do projeto **GluView/GluSync**: um app Android
de monitoramento de glicemia (Diabetes Mellitus Tipo 1) com sincronização em nuvem opcional e um
portal web (GluWebView) para pacientes e cuidadores.

**Este repositório não contém código-fonte.** Ele existe para hospedar issues, discussões,
roadmap e o canal privado de segurança do projeto. Os três produtos (GluView, GluSync,
GluWebView) têm repositórios de código próprios, hoje privados — veja [por quê](#sobre-os-repositórios-de-código) abaixo.

## Os três produtos

- **GluView** — app Android (Kotlin + Jetpack Compose): leitura direta de sensores CGM via
  Bluetooth, acompanhamento paciente ↔ cuidador em tempo real, visor personalizado para
  wearables, alertas configuráveis.
- **GluSync** — backend (ASP.NET Core + PostgreSQL): sincronização em nuvem opcional, API pública
  para integradores (API Key ou OAuth 2.1), compatibilidade com o protocolo Nightscout.
- **GluWebView** — portal web: dashboard de paciente e cuidador, relatórios, alertas, e a
  documentação pública completa do projeto.

## Documentação

A documentação completa (instalação, uso, API pública, segurança e privacidade) está publicada em
**https://glusync-gluview.github.io/GluView-comunidade/**, em português, inglês e espanhol.

## ⚠️ Aviso médico

O GluView **não é um dispositivo médico** e não substitui orientação profissional de saúde. Não
use este projeto, suas issues ou discussões como canal de emergência médica — procure atendimento
de saúde real. Veja o aviso médico completo na documentação publicada.

## Status do projeto

Em desenvolvimento ativo, mantido por uma única pessoa. Veja [`ROADMAP.md`](ROADMAP.md) para o
que já está pronto e o que vem a seguir, e [`GOVERNANCE.md`](GOVERNANCE.md) para como o projeto é
mantido.

## Como participar

- **Dúvida ou sugestão de uso**: abra uma [Discussion](../../discussions).
- **Bug ou pedido de funcionalidade**: abra uma [Issue](../../issues/new/choose).
- **Vulnerabilidade de segurança ou incidente de privacidade**: **nunca** abra uma issue pública —
  veja [`SECURITY.md`](SECURITY.md).
- **Quer contribuir de verdade** (código, tradução, documentação): veja
  [`CONTRIBUTING.md`](CONTRIBUTING.md) — a situação atual dos repositórios de código exige um
  fluxo um pouco diferente do PR direto de código aberto usual.

## Sobre os repositórios de código

Os repositórios de código-fonte (GluView, GluSync, GluWebView) continuam **privados** por
enquanto. Essa é uma decisão deliberada da fase atual do projeto — não uma omissão. Veja
[`CONTRIBUTING.md`](CONTRIBUTING.md) para o que isso significa na prática hoje.

## Licença

Nenhuma licença de código aberto foi definida ainda. **Todos os direitos reservados** — nenhuma
licença de uso, modificação ou redistribuição é concedida por enquanto. Essa decisão será
revisitada quando/se um repositório de código-fonte for aberto publicamente.
