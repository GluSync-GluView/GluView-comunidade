# Roadmap

Formato `Now / Next / Later` — sem datas ou números de versão prometidos, decisão deliberada
registrada internamente no projeto. O projeto é mantido por uma única pessoa, em infraestrutura
de plano gratuito: prometer prazo aqui seria dar uma garantia que não posso sustentar de forma
confiável.

## Feito recentemente

- Fundação de segurança e auditoria do backend.
- Contratos de dados, migrações e tempo real (SignalR).
- Autenticação, autorização e contas (sessão segura, passkeys/WebAuthn, MFA para admin).
- Portal web: design system, internacionalização (pt-BR/en/es).
- Dashboard do paciente (histórico, estatísticas, AGP, relatórios).
- Dashboard do cuidador (múltiplos pacientes, vínculos com escopo).
- Alertas configuráveis e relatórios.
- Documentação completa em três idiomas.
- **API pública** para integradores externos — API Key e OAuth 2.1 (`authorization_code` +
  PKCE), tempo real público, compatibilidade oficial com Nightscout, política de depreciação de
  90 dias.

## Now

- **Roadmap público, issues e processo de comunidade** (este repositório) — em andamento.

## Next

- **Infraestrutura, CI/CD e hospedagem definitiva** — automatizar o pipeline que hoje é manual
  (build e publicação do site de documentação, deploy do backend), avaliar se os planos gratuitos
  atuais continuam adequados.
- **QA, segurança e período de beta** — testes mais amplos antes de qualquer uso além do circulo
  atual de uso pessoal/testado.

## Later

- **Release e operação contínua** — processo de release formal com versionamento semântico,
  changelog estruturado por versão (não mais retroativo).
- Ambiente de sandbox da API pública provisionado de fato (código já pronto, banco ainda não
  criado — decisão de infraestrutura separada).
- Expansão de compatibilidade de sensor/wearable conforme demanda da comunidade.

## Dependente de avaliação (não é um compromisso)

- Qualquer recurso que envolva orientação clínica, dosagem ou decisão de tratamento — este
  projeto é estritamente informativo, não um dispositivo médico, e qualquer mudança nessa
  direção exigiria avaliação regulatória que está fora do escopo atual.
- Abrir o código-fonte de algum repositório publicamente — depende de auditoria completa de
  segurança/licenciamento (ver processo interno) e de uma decisão de licença ainda não tomada.

## Como isso é atualizado

O mantenedor atualiza este arquivo manualmente ao concluir cada etapa de desenvolvimento — não há
sincronização automática com o planejamento interno do projeto.
