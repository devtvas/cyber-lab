# SOC Interview — Questions & Answers

This is the running interview notebook for the target SOC Analyst role.

## 1. O que é um SIEM?

**Resposta curta:** uma plataforma que centraliza, normaliza, pesquisa e correlaciona eventos de diferentes fontes para apoiar monitoramento, detecção e investigação de segurança.

**Na prática:** o analista recebe eventos e alertas, valida o contexto, investiga evidências e decide a tratativa ou escalonamento.

## 2. Qual a diferença entre evento e alerta?

**Evento** é um registro de uma atividade observada por um sistema.

**Alerta** é uma sinalização gerada quando uma regra, correlação ou mecanismo de detecção identifica uma condição potencialmente relevante.

## 3. O que é triagem de alerta?

É o processo de avaliar rapidamente um alerta para determinar sua relevância, prioridade, contexto, possível impacto e próximos passos.

## 4. O que é um falso positivo?

É um alerta que parece indicar uma ameaça, mas após análise não representa um incidente real.

## 5. O que é um IOC?

IOC significa **Indicator of Compromise**. São evidências observáveis associadas a possível comprometimento, como IPs, domínios, hashes, URLs, arquivos ou artefatos específicos.

## 6. O que é EDR?

EDR significa **Endpoint Detection and Response**. É uma tecnologia voltada à coleta de telemetria dos endpoints, detecção de comportamentos suspeitos e apoio à investigação e resposta.

## 7. O que é SOAR?

SOAR significa **Security Orchestration, Automation and Response**. É utilizado para integrar ferramentas e automatizar etapas de investigação e resposta por meio de workflows/playbooks.

## 8. O que é MITRE ATT&CK?

É uma base de conhecimento que organiza comportamentos e técnicas utilizadas por adversários, permitindo estruturar análise, detecção e investigação.

## 9. Como você investigaria um alerta suspeito?

1. Validaria o alerta e sua origem.
2. Identificaria ativo, usuário, horário e contexto.
3. Consultaria eventos relacionados.
4. Procuraria IOCs e comportamento anômalo.
5. Avaliaria impacto e severidade.
6. Faria o mapeamento técnico quando aplicável.
7. Registraria evidências e conclusão.
8. Executaria ou recomendaria a resposta adequada.
9. Escalonaria quando necessário.

## 10. Qual é o objetivo deste laboratório?

Demonstrar, de forma prática e reproduzível, a capacidade de estudar e executar processos de monitoramento, triagem, investigação, documentação e resposta em um ambiente controlado.

---

## Próximas perguntas

Este documento será atualizado conforme cada novo laboratório for concluído.

- Como diferenciar incidente de evento?
- Como definir severidade?
- Como investigar múltiplas tentativas de login?
- O que procurar em logs Windows?
- O que procurar em logs Linux?
- Como funciona uma regra de correlação?
- Como reduzir falsos positivos?
- Como funciona um firewall?
- O que é NGFW?
- Qual a diferença entre IDS e IPS?
- O que é WAF?
- Qual a diferença entre EDR e XDR?
- Como funciona uma vulnerabilidade e seu ciclo de remediation?
- Como documentar um incidente para escalonamento?
