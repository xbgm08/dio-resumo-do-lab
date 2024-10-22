# Resumo das aulas
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento dos labs na DIO.

## Microsoft Azure - Localizando Serviços por Categoria
Durante esta aula, aprofundei meu conhecimento sobre a personalização e organização do Portal do Azure, aprendendo a:

* Adaptar o Portal à nossa preferência: Alterando o idioma e o tema visual para uma experiência mais personalizada.
* Organizar recursos por categoria: Facilitando a localização e gerenciamento de serviços.
* Compreender a rede Azure: Explorando a funcionalidade de Bastions como Jump Servers e a importância de Firewalls para a segurança.
* Explorar opções de armazenamento: Aprendendo sobre migração de dados e as considerações sobre recursos em Versão Prévia.
* Visualizar a localização dos serviços: Através de um laboratório prático, obtivemos uma visão geral da distribuição geográfica dos serviços Azure.

* Observações:
  * Versão Prévia: Recursos em Versão Prévia estão em desenvolvimento e podem não ser adequados para ambientes de produção.
  * Bastions: Funcionam como Jump Servers, proporcionando acesso seguro aos recursos da nuvem.

## Microsoft Azure - Criando máquinas Virtuais na Azure
Durante esta aula, aprofundei meu conhecimento os diferentes níveis de Service Level Agreement (SLA) e seu impacto no tempo de inatividade de um serviço. Os dados apresentados demonstram a relação entre o nível de SLA contratado e a disponibilidade do serviço.

| Nível de SLA | Tempo de Inatividade por Semana | Tempo de Inatividade por Mês | Tempo de Inatividade por Ano |
|---|---|---|---|
| 99% | 1,68 horas (2h 8min) | 7,2 horas | 3,65 dias |
| 99,9% | 10,1 minutos | 43,2 minutos | 8,76 horas |
| 99,95% | 5 minutos | 21,6 minutos | 4,38 horas |
| 99,99% | 1,01 minuto | 4,32 minutos | 52,56 minutos |
| 99,999% | 6 segundos | 25,9 segundos | 5,26 minutos |

### Análise

* **SLA e Disponibilidade:** Quanto maior o número de "9s" no SLA, menor o tempo esperado de inatividade.
* **Impacto no Custo:** SLAs mais altos geralmente estão associados a custos mais elevados.
* **Considerações para a Escolha do SLA:** Ao escolher um SLA, é fundamental avaliar a tolerância a falhas da sua aplicação e o impacto financeiro que a indisponibilidade pode causar.
