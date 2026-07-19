# Changelog

Formato baseado em [Keep a Changelog](https://keepachangelog.com/pt-BR/1.1.0/). O projeto ainda
não segue Versionamento Semântico formal — as entradas abaixo, anteriores a esta etapa, foram
**reconstruídas retroativamente** a partir do histórico de commits real de cada repositório, não
representam releases numeradas publicadas no momento em que aconteceram.

## [Não lançado]

### Adicionado
- Repositório público de comunidade (este) — roadmap, issues, discussions, canal privado de
  segurança.

## Retroativo — desenvolvimento até aqui

### Adicionado
- API pública para integradores: API Key com rotação/expiração, OAuth 2.1
  (`authorization_code` + PKCE), tempo real público via SignalR, compatibilidade oficial com
  Nightscout, política de depreciação de 90 dias, ambiente de sandbox (código pronto, banco não
  provisionado).
- Documentação completa do produto em português, inglês e espanhol.
- Alertas configuráveis (glicemia alta/baixa, sensor sem sincronizar) com entrega por push web e
  Pushover, e relatórios (CSV, JSON, AGP em PDF, link compartilhável).
- Dashboard do cuidador com múltiplos pacientes, vínculos com escopo de acesso e histórico de
  auditoria.
- Dashboard do paciente: visão geral em tempo real, histórico com anotações, estatísticas
  (tempo no alvo, CV, GMI, HbA1c estimada), gestão de sensores e integrações.
- Portal web (GluWebView): design system próprio, internacionalização completa.
- Autenticação segura: sessão via cookie HttpOnly com rotação de refresh token, passkeys/WebAuthn,
  MFA obrigatório para administração, modelo de vínculo paciente-cuidador por convite.
- Contrato de dados versionado (`/api/glusync/v1`), tempo real via SignalR, perfil internacional
  (fuso horário, unidade de glicemia, faixas de tempo no alvo).
- App Android (GluView): leitura direta de sensores CGM via Bluetooth (Sibionics, Freestyle Libre
  2 Plus), sincronização em nuvem opcional, visor personalizado para wearables, acompanhamento em
  tempo real entre paciente e cuidador.

### Segurança
- Varredura de segredo executada a cada etapa de desenvolvimento antes de qualquer publicação de
  conteúdo novo.
- Trilha de auditoria de segurança separada dos logs operacionais, visível ao próprio usuário.
