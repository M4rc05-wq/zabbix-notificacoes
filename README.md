# zabbix-notificacoes

*Este repositório é dedicado para conteúdo de notificações **ZABBIX**.*

## Formtação para telegram

**Subject**
```markdown
{HOST.NAME}-{TRIGGER.STATUS}: {EVENT.NAME}
```
**Message**
```markdonw
**Service HMRP-{EVENT.SEVERITY}-{TRIGGER.STATUS} {EVENT.NAME}**
**Hostname:** {HOST.NAME} **IP:** {HOST.IP}
**Data:** {EVENT.DATE} **Horário:** {EVENT.TIME}
**Item de Monitoramento:** {EVENT.NAME}**
**Descrição do Incidente:** {TRIGGER.DESCRIPTION}
**Descrição do servidor:** {HOST.DESCRIPTION}
**Consumo / Status:** {ITEM.NAME1}-{ITEM.VALUE1}
**Severidade:** {EVENT.SEVERITY}
**Link para manual:** {TRIGGER.URL}
**Original event ID:** {EVENT.ID}
[Zabbix](http://Monitoramento.acsc.org.br:12011)
```