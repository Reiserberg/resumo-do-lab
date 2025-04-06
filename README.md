# resumo-do-lab
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO.
Resumo – Laboratório: Benefícios da Nuvem
O laboratório teve como foco demonstrar, na prática, os principais benefícios da computação em nuvem utilizando o Azure, com destaque para a demonstração da criação de máquinas virtuais e os impactos relacionados à disponibilidade e replicação de dados.
Durante a simulação da criação de uma máquina virtual, foi apresentado onde localizar a documentação oficial do Azure (Docs), reforçando a importância de entender bem cada etapa da configuração. Foi evidenciado que as opções escolhidas durante a criação influenciam diretamente no SLA (Acordo de Nível de Serviço), ou seja, no tempo máximo permitido de indisponibilidade da solução.
O laboratório abordou os diferentes modelos de SLA, destacando quais oferecem menor tempo de inatividade. Quanto maior o nível do SLA, menor é o risco de interrupções — o que está atrelado a escolhas como tipo de armazenamento, região e estratégias de replicação.
Sobre a replicação, foi explicado como funcionam as diferentes opções oferecidas pelo Azure:
• Redundância Local (LRS): dados replicados dentro de um único datacenter.
• Redundância de Zona (ZRS): dados replicados entre zonas diferentes dentro da mesma região.
• Redundância Geográfica (GRS): dados replicados entre regiões geograficamente distintas.
A lógica é simples: quanto mais replicado o dado, menor a chance de perda ou indisponibilidade, pois ele estará salvo em múltiplos locais ao mesmo tempo. Isso é fundamental em casos de falhas, desastres naturais ou necessidades de acesso a partir de diferentes pontos.
Por fim, foi reforçado o propósito real da criação de máquinas virtuais: elas resolvem problemas específicos e agregam valor quando bem aplicadas. No entanto, é importante lembrar que cada decisão impacta diretamente nos custos, sendo essencial criar com consciência e alinhamento ao objetivo do negócio.
