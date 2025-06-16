# Fundamentos-Azure-Maquinas-Virtuais
Projeto sobre Máquinas Virtuais no Azure - DIO
Durante as aulas e a análise para este desafio, os seguintes conceitos fundamentais da computação em nuvem e do Azure foram estudados:
Benefícios da Nuvem:
Alta Disponibilidade: Garante que os serviços estejam sempre acessíveis.
Escalabilidade: Capacidade de adicionar recursos para lidar com o aumento da demanda de consumo para atender uma necessidade específica.
Elasticidade: Capacidade de adaptar sistemas para atender requisições externas com agilidade e rapidez.
Confiabilidade: Consistência no desempenho e na funcionalidade dos serviços.
Previsibilidade: Capacidade de estimar custos e desempenho.
Segurança: Proteção contra ameaças e conformidade regulatória.
Governança: Gerenciamento e controle de políticas e recursos.
Gerenciabilidade: Facilidade na administração e operação dos serviços.
Modelos de Nuvem:
Nuvem Privada: Ambiente de nuvem criado em datacenter próprio da organização, que é responsável por operar os serviços e não fornece acesso a usuários externos.
Nuvem Pública: Pertence a provedores de nuvem ou hosting, fornece recursos e serviços a múltiplas organizações e usuários, e é acessada via conexão de rede segura (geralmente pela Internet).
Nuvem Híbrida: Combina nuvens públicas e privadas, permitindo que os aplicativos sejam executados no local mais adequado e fornecendo a maior flexibilidade.
Comparação CapEx e OpEx:
Despesas de Capital (CapEx): Gasto inicial em infraestrutura física, com valor que se reduz com o tempo.
Despesas Operacionais (OpEx): Gastos com produtos e serviços conforme necessário, com pagamento conforme o uso e cobrança imediata.
Tipos de Serviço de Nuvem:
IaaS (Infraestrutura como Serviço): Permite criar uma infraestrutura de TI de pagamento conforme o uso, alugando servidores, máquinas virtuais, armazenamento, redes e sistemas operacionais de um provedor de nuvem.
PaaS (Plataforma como Serviço): Fornece um ambiente para criação, teste e implantação de aplicativos de software, sem focar no gerenciamento da infraestrutura subjacente.
SaaS (Software como Serviço): Usuários se conectam e utilizam aplicativos baseados em nuvem pela Internet (ex: Microsoft Office 365, e-mail e calendários.
Componentes de Arquitetura do Azure:
Regiões: O Azure oferece mais de 60 regiões globais (mais de 140 países), compostas por um ou mais datacenters próximos. Elas fornecem flexibilidade e escala para reduzir a latência do cliente e preservam a residência dos dados com uma oferta abrangente de conformidade.
Zonas de Disponibilidade: Oferecem proteção contra tempo de inatividade devido a falha do datacenter, separando fisicamente datacenters dentro da mesma região. Cada datacenter é equipado com alimentação, resfriamento e rede independentes, conectados por redes privadas de fibra óptica.
Pares de Regiões: Apresentam no mínimo 300 milhas de separação, com replicação automática para alguns serviços, recuperação de região priorizada em caso de interrupção e atualizações distribuídas sequencialmente para minimizar o tempo de inatividade.
Regiões Soberanas do Azure (Governamentais e China):
Azure Governamental: Instância separada do Azure, fisicamente isolada de implantações não governamentais dos EUA, acessível apenas a pessoal verificado e autorizado. Atende às necessidades de segurança e conformidade de agências federais, governos estaduais e locais dos EUA.
Azure China: Instância fisicamente separada dos serviços de nuvem do Azure, operada pela 21Vianet, com todos os dados permanecendo dentro da China para garantir a conformidade.
Recursos do Azure: Componentes como armazenamento, máquinas virtuais e redes disponíveis para criar soluções de nuvem. Exemplos incluem Máquinas virtuais, Contas de armazenamento, Redes virtuais, Serviços de aplicativos, Bancos de dados SQL e Funções.
Grupos de Recursos: Contêineres utilizados para gerenciar e agregar recursos em uma única unidade. Recursos podem existir em apenas um grupo de recursos, em diferentes regiões, podem ser movidos para diferentes grupos de recursos, e os aplicativos podem utilizar vários grupos de recursos.
Assinaturas do Azure: Fornecem acesso autenticado e autorizado às contas do Azure, servindo como limite de cobrança (gerando relatórios e faturas separados) e limite do controle de acesso (gerenciando o acesso aos recursos que os usuários podem provisionar).
Grupos de Gerenciamento: Podem incluir múltiplas assinaturas do Azure, que herdam as condições aplicadas ao grupo de gerenciamento. É possível oferecer suporte a 10.000 grupos de gerenciamento em um único diretório, e uma árvore pode suportar até seis níveis de profundidade.
Serviços de Computação do Azure:
  Máquinas Virtuais do Azure (VMs): Emulações de software de computadores físicos, incluindo processador virtual, memória, armazenamento e rede. São uma oferta de IaaS que oferece personalização e controle total.
Serviços de Contêineres do Azure: Fornecem um ambiente leve e virtualizado que não exige o gerenciamento do sistema operacional e pode responder a alterações sob demanda. Incluem Instâncias de Contêiner do Azure (PaaS que executa contêiner ou pod) Aplicativos de Contêiner do Azure (PaaS que pode balancear a carga e escalar) e Serviço de Kubernetes do Azure (serviço de orquestração para contêineres com arquiteturas distribuídas e grandes volumes).
Azure Functions: Oferta de PaaS que dá suporte a operações de computação sem servidor.O código baseado em eventos é executado quando chamado, sem exigir uma infraestrutura de servidor durante períodos inativos.
Serviços de Aplicativo do Azure:** Plataforma totalmente gerenciada para criar, implantar e dimensionar rapidamente aplicativos Web e APIs. Compatível com .NET, Node.js, Java, Python ou PHP, é uma oferta de PaaS com requisitos de nível corporativo de desempenho, segurança e conformidade.
Serviços de Rede do Azure:
Rede Virtual do Azure (VNet): Permite que os recursos do Azure se comuniquem uns com os outros, com a Internet e com as redes locais. Oferece pontos de extremidade públicos (acessíveis de qualquer lugar na Internet) e privados (acessíveis somente de dentro da sua rede). Sub-redes virtuais segmentam a rede, e o emparelhamento de rede conecta redes privadas diretamente.
DNS do Azure: Oferece confiabilidade e desempenho aproveitando uma rede global de servidores de nome DNS usando a rede Anycast. A segurança do DNS do Azure baseia-se no gerenciador de recursos do Azure, habilitando o controle de acesso baseado em função e o monitoramento e o registro em log. Oferece facilidade de uso para gerenciar recursos externos e do Azure com um único serviço DNS, redes virtuais personalizáveis para nomes de domínio privados, e registros de alias que dão suporte a conjuntos de registros de alias para apontar diretamente para um recurso do Azure
Serviços de Armazenamento do Azure:
Contas de Armazenamento: Devem ter um nome globalmente exclusivo, fornecem acesso à Internet em todo o mundo, e determinam os serviços de armazenamento e as opções de redundância.
Redundância de Armazenamento: Define a configuração de redundância, implantação e durabilidade.
LRS (armazenamento com redundância local): Datacenter individual na região primária, 11 noves de durabilidade.
ZRS (armazenamento com redundância de zona): Três zonas de disponibilidade na região primária, 12 noves de durabilidade.
GRS (armazenamento com redundância geográfica): Datacenter único no primário e região secundária, 16 noves de durabilidade.
GZRS (armazenamento com redundância de zona geográfica): Três zonas de disponibilidade na região primária e um único datacenter na região secundária, 16 noves de durabilidade.
Tipos de Armazenamento:
Blob do Azure: Otimizado para o armazenamento de quantidades massivas de dados não estruturados (texto ou dados binários).
Disco do Azure: Fornece discos para máquinas virtuais, aplicativos e outros serviços acessarem e utilizarem.
Fila do Azure: Serviço de armazenamento de mensagens que fornece armazenamento e recuperação para grandes quantidades de mensagens, cada uma com até 64 KB.
Arquivos do Azure: Configura um compartilhamento de arquivos de rede altamente disponível que pode ser utilizado usando o protocolo Bloco de Mensagens do Servidor.
Tabelas do Azure: Fornece uma opção de chave/atributo para o armazenamento de dados estruturados não relacionais com um design sem esquema.
Camadas de Acesso de Armazenamento do Azure:
Frequente: Otimizada para armazenamento de dados acessados com frequência.
Esporádico: Otimizada para armazenamento de dados acessados com pouca frequência e armazenados por pelo menos 30 dias.
Frio: Otimizado para o armazenamento de dados acessados com pouca frequência e armazenados por pelo menos 90 dias.
Arquivo Morto: Otimizada para armazenamento de dados acessados raramente e armazenados por pelo menos 180 dias com requisitos de latência flexíveis.
Azure Data Box: Permite armazenar até 80 terabytes de dados e mover backups de recuperação de desastre para o Azure.Protege os dados em uma caixa robusta durante o trânsito e migra dados para o Azure de locais remotos com conectividade limitada ou sem conectividade.
