# resumo-do-lab
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO
Computação em Nuvem é um fornecimento de serviços através de internet, sendo realizado por empresas como Microsoft, Oracle, etc.
Suas principais características são:
- criação de recursos de maneira rápida
- Baseado em computação, rede e armazenamento.
- Pode ser lido como um tipo de "Self-Service"
- Modelo baseado em consumo, ou seja, os usuários pagam pelo que consumiram.

Existem 3 tipos de nuvem, sendo elas: 
- Nuvem privada: ambiente em nuvem em seu próprio datacenter, não dividindo com ninguém. A organização tem total controle sobre os rescursos de segurança, seno também resposáveis pelas atualizações de hardware.
- Nuvem pública: entrega de recursos a uma série de clientes por meio de um único provider, acessada via conexão de rede segura. O pagamento é realizado posteriormente, sendo importante comentar que a empresa só paga pelo o que ela utiliza.
- Nuvem híbrida: comunicação entre nuvem privada e nuvem pública. Organização também controla segurança, a localização dos apps, porém nesse tipo de nuvem existe uma flexibilidade em maior que as demais.

Tipos de depesas (CapEx & OpEx):
- Despesas de capital(Capex): gasto inicial é realizado com a estrutura física nas empresas(servidores, computadores, etc), tendo seu valor reduzido com o tempo
- Despesas operacionais(Opex): gasto realizado com produtos e serviços operacionais caso necessário, sendo cobrado imediatamente.

Benefícios da nuvem:
-
- Alta disponibilidade: possui o SLA, uma porcentagem de tempo definida para ficar fora do ar, dependendo do pacote. Esse tempo é um período curto de horas e caso passe do tempo demilitado, a Microsoft recompensa o usuário através de um voucher.
  
- Escalabilidade: escalabilidade é a capacidade de ajustar recursos para atender a demanda. Com isso em mente, se a demanda cair, você poderá reduzir seus custos, pagando apenas pelo o que usa. Também é considerado uma escala vertical.
    
- Elasticidade: Em um cenário na qual você experimentasse um salto repentino acentuado na demanda, seus recursos implantados poderiam ser expandidos, dimensionando o ambiente com base em requisições. Sendo possível por exemplo, adicionar máquinas virtuais ou contêineres por meio de expansão.

- Confiabilidade: Sendo descentralizado, pode possuir recursos implantados em diversas regiões do mundo. Mesmo que ocorra algo em uma região, as outras ainda estarão em funcionamento, demonstrando suporte a uma infraestrutura confiável e resiliente.

- Previsibilidade: Avança com confiança, sejam em desempenho ou custo.

- Segurança: Possui diversas ferramentas de segurança, muitas vezes auxiliando clientes que realizam suas próprias implementações de acordo com suas necessidades.

- Governança: Sinaliza qualquer recurso que esteja fora do normal, de acordo com os modelos de regra específicas de cada empresa, gerando uma nuvem atualizada, protegida e bem gerenciada.

- Gerenciabilidade: Ofere a oportunidade do cliente gerenciar seus recursos em nuvem, criando modelos pré-configurados, por exemplo: escalar automaticamente a implantação de recursos de acordo com a necessidade, seja m portal da web, uma interface de linha de comando, etc.

Tipos de serviço em nuvem: IaaS, PaaS, SaaS.
-
-  IaaS(Infraestrutura como serviço): Sendo o mais utilizado, os clientes possuem o maior acesso comparado aos outros dois tipos de serviço(configuração, monitoramento, backup, etc). Os serviços são: Servidores e Armazenamento, Firewall e Segurança de rede, Planta física e Edifício do datacenter. Possui mais acesso ao recurso final, além de que o cliente tem sempre que validar e monitorar o que está acontecendo, dando consequência em uma maior liberdade para o mesmo.
-  PaaS(plataforma como serviço): Abrangendo todo o campo do serviço anterior, também inclui novos como sistemas operacionais, ferramentas de desenvolvedores e análise de negócios de gerenciamento de database. Se preocupa principalmente com a aplicação, fornecendo um ambiente de criação para testes, no intuito de implantar as aplicações de software sem se preocupar com o gerenciamento.
-  SaaS(Software como serviço): Abrangendo os outros dois, agora também inclui aplicativos e apps hospedados, como por exemplo, o Micrososft Teams. Nesse caso a aplicação já está pronta e o que determina o tamaho de recursos que o cliente pode utilizar da aplicação é o licenciamento.

Modelo de responsabilidade compartilhada:
-
  - No local: tudo é reponsabilidade do cliente.
  - Em hosts físicos, Rede física e Datacenter físico: Tudo é responsabilidade dos provedores de nuvem(Microsoft) nos três tipos de serviço.
  - Em infraestrutura e identidade de diretório, Aplicativos e Controles de rede: A responsabilidade varia conforme o tipo, indo de clientes para IaaS até em sua maioria provedores de nuvem na SaaS.
  - Informações de dados, Dispositivos(móveis e PC) e contas e identidades: Sempre responsabilidade do cliente.
  








