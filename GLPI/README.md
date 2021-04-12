# Template GLPI direto do banco

## Requisitos
Usuário 'zabbix' no banco com privilégios de SELECT no banco do GLPI.


## Como utilizar
Adicione o template ao host e coloque o nome do banco de dados do GLPI na macro {$BANCO}.
Coloque o userparameters_glpi.conf na pasta /etc/zabbix/zabbix_agentd.d do servidor do GLPI.
Os itens já estão criados no template.
