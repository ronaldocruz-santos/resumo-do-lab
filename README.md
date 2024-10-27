![github-header-image](https://github.com/user-attachments/assets/538768f1-6607-4e27-add0-6c824b6dbd64)
# resumo-do-lab
Este repositório tem como finalidade apresentar um breve resumo das lições aprendidas do Bootcamp Microsoft Azure Essentials.
___
Saudações! Estou iniciando minha jornada rumo a certificação Azure AZ-900 e estou dando meus primeiros passos aqui na [***DIO***](https://www.dio.me). Por isto te convido a conhecermos juntos essa fantástica plataforma que é o Microsoft Azure.

Primeiramente a melhor forma de conhecer o Microsoft Azure é acessando a plataforma certo? E aqui aprendi a efetuar meu cadastro em uma conta gratuita, no qual qualquer pessoa pode se cadastrar através deste [***link***](https://azure.microsoft.com/pt-br/pricing/purchase-options/azure-account#:~:text=A%20conta%20gratuita%20do%20Azure%20fornece%20acesso%20a%20todos%20os?msockid=028bcaa179b26d921a3cde7778d96cda)!

Mas criar uma conta e não saber o que fazer é complicado, mas aprendi que o conceito é bem simples, primeiro conhecemos os tipos e diferenças dos ambientes computacionais
|Tipo|Descrição|
|----|---------|
|On Premises| Modelo de computação padrão, ou seja computadores e servidores físicos alocados em instalações locais e administrados pela própria empresa.|
|Nuvem Pública| Modelo de computação onde computadores e servidores são virtuais e alocados em empresas como Microsoft, Amazon, entre outras, em infraestruturas distribuidas.|
|Híbrida| Modelo de computação no qual uma empresa pode possuir parte de seus servidores locais e outros servidores ou serviços alocados na nuvem.|
|Nuvem Privada| Modelo de computação no qual a própria empresa cria e gerencia seus recursos na nuvem.|

Certo, mas o que faz com que uma empresa use recursos computacionais em nuvem pela internet, sendo que ela pode manter sua infraestrutura local?

A resposta pode ser bem simples, alta disponibilidade, segurança, agilidade e por fim alocação de recursos comforme a demanda. Na nuvem podemos implantar um banco de dados em segundos, disponibilizar acesso a filiais remotas num piscar de olhos e contratar apenas o que iremos realmente usar.

Uma infrastrutura local depende de planejamento no qual a implantação é demorada, tem um custo inicial muito alto e por fim é sucetível a falhas de disponibilidade.

Com estas diferenças fica evidente que um modelo computacional em nuvem tem enormes vantagens, ainda mais se tratando em custos já que seu modelo é baseado em consumo. E falando no bolso aprendi dois termos que descrevem bem estas diferenças que são OpEx e CapEx

|||
|---|---|
|CapEx|Os recursos financeiros são usados na aquisição de equipamentos nos quais os custos são diluidos com o tempo|
|OpEx| Os recursos financeiros são usados no consumo de recursos contratados conforme a necessidade, sendo do ponto de vista financeiro mais eficiente|

Com estas informações agora ficou mais fácil compreender e tirar vantagem da computação em nuvem e iniciar o uso da plataforma Microsoft Azure de forma responsável e segura.

---
## Vantagens de uma Nuvem Pública

A principio a nuvem pública é a melhor escolha em vários cenários, pois suas vantagens são;

* Alta Disponibilidade
* Escalabilidade e Elasticidade
* Confiabilidade e Previsibilidade
* Gerenciamento
* Segurança e Governança

### *Alta Disponibilidade*

Trata-se de assegurar a máxima disponibilidade de tempo dos recursos disponíveis, e estes tempos são tratados como níveis de SLA para os recursos utilizados. No Microsoft Azure estes níveis correspondem em;

|SLA|Indisponibilidade mensal|
|--|--|
|99%|7,2 Horas|
|99.9%|43.2 minutos|
|99,95%|21.6 minutos|
|99,99%|4.32 minutos|
|99,999%|25.9 segundos|

### *Escalabilidade e Elasticidade*

Compreende em ajustar seus recursos escalando os mesmos, seja aumentando recursos de vCPU´s ou aumentando a quantidade de discos de armazenamento conforme a necessidade. 

No caso de elasticidade podemos expandir ou reduzir recursos de forma dinâmica. Um exemplo muito utilizado é o período de Black Friday, nos quais as lojas on-line possuem uma explosão de acessos de clientes e logo após uma redução brusca nos acessos.

### *Confiabilidade e Previsibilidade*

Confiabilidade na nuvem se demonstra na capacidade de manter seus recursos sempre disponíveis, isso é possivel pois fornecedores de nuvem possuem um modelo de infra distribuida, mesmo que uma infra se torne indisponível, os recurso estão replicados em outras infras em locais distintos, regiões distantes ou até mesmo em outros paises.

E por fim a previsibilidade fornece ao cliente a confiança em ajustar seus recursos de acordo com suas demandas, sejam em desempenho ou mesmo em custo dos recursos utilizados.

### *Gerenciamento*

O gerenciamento de nuvem permite que o administrador possa executar, manipular, ajustar seus recursos de várias formas, além do painel via WEB o administrador pode usar um CLI, programar um API, usar o Powershell para este fim. Em um exercício prático um administrador consegue subir várias VM´s, dimensionar bases de dados ou mesmo programar thresholds através de scripts, otimizando ao máximo o tempo de administração dos recursos.

### *Segurança e Governança*

A nuvem permite que as organizações ou as empresas que as adota, tenham ferramentas para manter seus recursos em nuvem aderentes as regras de governaça das mesmas. Permitindo que as organizações auditem seus recursos na nuvem da mesma forma que os fazem em seus recursos locais.

E na questão de segurança, a nuvem de acordo com seus recursos fornecidos, permite que as organizações gerenciem a segurança de seu ambiente de infra em nuvem exatamente como as fazem no ambiente on premises, ou se for adota soluções como SaaS esta segurança é gerenciada pela própria nuvem.

## Serviços IaaS, PaaS e SaaS no Microsoft Azure

Mas não só de maquinas virtuais se compõe os serviços de nuvem, na verdade são fornecidos pelos Cloud Provider como a Microsoft e Amazon, tipos distintos de serviços que compreendem em;

***IaaS*** - Infra estrutura como serviço, no qual o cliente tem maior controle dos recursos contratados como tambén a responsabiliade em gerenciá-los. Como caracteristicas temos disponíveis na nuvem os mesmos recursos de infra estrutura local, podemos configurar servidores, firewall, dispositivos de redes exatamente como faríamos em um ambiente On Premises.

***PaaS*** - Plataforma como serviço, nos permite contratar recursos como por exemplo bancos de dados, sem a necessidade de criar, instalar e administrar servidores e posteriormente instalar um DB. Nesta modalidade como clientes ainda temos responsabilidades no gerenciamento, acessos e segurança da plataforma usada ficando a cargo do Cloud Provider a responsabilidade de toda a infra que está abaixo da plataforma utilizada.

***SaaS*** - Software como serviço, é a camada mais superficial de recursos, basicamente serviços como Microsoft 365, Microsoft Outlook, Microsoft Teams, Google Docs são exemplos de SaaS, onde usamos as aplicações com o nível de responsabilidade mais baixo por parte do cliente.

## Regiões e Zonas do Microsoft Azure

Como toda Infra de redes necessita de um plano de contingência, isso não é diferente com os serviços de Cloud, isso permite que os administradores configurem de acordo com os serviços contratados, regiões de disponibilidade, basicamente os serviços ou ambientes são espelhados em outros servidores, datacenters ou mesmo ambientes alocados em outras regiões. Isto é necessário para manter a disponibilidade tanto da Infra em nuvem quanto aos serviços contratados.

***Zonas*** - São datacenter separados dentro da mesma região com o objetivo de manter a disponibilidade de recursos.

***Região*** - Possuem datacenters próximos que permitem disponibilidade dos recursos e infra contratados. Como por exemplo um conjunto de datacenter se torna indisponivel, porém existem outros que compõe a mesma região, mesmo estando distantes e são ativados permitindo a máxima disponibilidade dos recursos de nuvem. Também é possivel dependendo da assinatura, manter a disponibilidade dos recursos entre regiões, desta forma o acesso se mantém em operação mesmo que uma região seja severamente afetada.

***Região Soberana*** - São regiões que possuem datacenters dedicados a clientes governamentais, como por exemplo os Estados Unidos, sendo que fisicamente são isolados das demais regiões, como também os acessos físicos e tipo de assinatura de serviços são restritos.

## Recursos do Microsoft Azure ##

São denominados recursos do Azure máquinas virtuais, funções, banco de dados, redes virtuais, serviços de aplicativos e contas de armazenamento.

E estes recursos podem ser organizados e manipulados criando os "Grupos de Recursos". Nestes grupos podemos criar um grupo com recursos utilizados para um ambiente de VM, DB e uma aplicação ou um outro grupo que compõe apenas de recursos de banco de dados. Lembrando que os recursos podem ser movidos entre grupos, mas nunca utilizados por dois grupos distintos.

Quanto as aplicações estas podem utilizar recursos dentro degrupos distintos, um exemplo é um website que utiliza um DB do grupo de banco de dados e busca imagens de drive locados em discos virtuais em outro grupo de armazenamento.

## Assinaturas do Microsoft Azure ##

São utilizadas para acessar e utilizar os recursos contratados, as mesmas podem ser definidas de acordo com o uso dos recursos como por exemplo uma assinatura para uso e gerenciamento de um grupo de bando de dados, outra assinatura para a equipe de desenvolvimento que utiliza apenas os recursos designados a eles, etc.

O importante das assinaturas é que aumentam a segurança no gerenciamento e acesso dos recursos, e para os administradores, as mesmas podem ser incluidas no gerenciamento de grupos, herdando os parâmetros definidos neste gerenciamento.

## Serviços de Computação do Azure ##

O Microsoft Azure fornece os seguintes tipos de serviços de computação conforme a seguir;

* Máquinas Virtuais
* Área de trabalho virtual
* Aplicações / Serviços
* Serviço de Kubernetes (AKS)
* Instâncias de Contêiners (exemplo Docker)
* Serviços de Redes

***Máquinas Virtuais***

Modalidade IaaS que permite ao cliente criar VM´s com total controle dos recursos utilizados como vCPU, vRAM, vNET e etc. Permite criar conjuntos de dimensionamento onde pode-se escalar os recursos utilizados de forma elástica e automatizada. Também pode-se criar conjuntos de disponibilidade, onde se uma VM torna-se indisponível no rack físico, existem duas ou mais para substituir automáticamente e manter o acesso disponível. Este grupo de disponibilidade pode ser configurado de diversas formas através de domínios de falha e domínios de atualização, sendo o primeiro como exemplo mantendo em outros dois rack´s do datacenter uma cópia da VM principal, e o domínio de atualização são VM´s cópias da principal que vão atualizando os dados entre si evitando lentidão na utilização da principal, enquanto os dados são replicados para os domínios de falha.

***Área de trabalho virtual***

Nesta modalidade acessamos um ambiente de usuário através do acesso remoto, basicamente é o mesmo que em ambientes on-premises acessamos um servidor ou um computador já configurado. Neste ambiente não gerenciamos a máquina virtual ou o sistema em si, apenas nos logamos na sessão de usuário e utilizamos o ambiente como um computador físico.

***Aplicações / Serviços***

Nesta modalidade em PaaS podemos utilizar o Azure Functions que executa comandos através de eventos programados no qual não utiliza servidores, ou a plataforma de serviços para criação e implantação de aplicações WEB e API que são executados em .NET, JAVA, Node.js, Python, .NET Core e por fim em PHP.

***Serviços de Kubernetes (AKS)***

Este serviço permite a orquestração de contêiners mantendo a escalabidade e resiliênhcia do ambiente.

***Instâncias de Contêiners***

Nesta modalidade podemos implementar um contêiner para execução de uma aplicação, sem a necessidade de utilizar uma VM para esta execução. Isto traz benefícios do ponto de vista de uso de recursos, agilidade e compatibilidade de execução.

***Serviços de Redes***

Nesta modalidade temos disponíveis serviços de vNET, Gateway VPN, DNS e por fim o Express Route que interliga diretamente o ambiente em Nuvem com suas instalações físicas através de parceiros.

## Serviços de Armazenamento ##

O primeiro passo para o armazenamento virtual no Azure é através da criação de uma conta de armazenamento, ou mais conhecida como Storage Account. Em sua criação é necessário criar um nome exclusivo em todo o serviço de armazenamento do Azure com letras minúsculas e números de 3 a 24 caracteres. A partir de sua criação podemos utilizar os demais serviços;

* Blob - serviço de armazenamento de dados não estruturados como imagens, arquivos texto entre outros.
* Discos - serviço de criação de unidades de discos virtuais, as mesmas criadas quando criamos uma VM.
* Filas - serviço de armazenamento de mensagens, funciona como uma espécie de servidor Syslog.
* Arquivos - serviço de compartilhamento de arquivos exatamente como é feito em ambientes On-Premises, no qual criamos um apontamento `smb:\\caminho` ou mapeamento.
* Tabelas - serviço de armazenamento de dados estruturados, como tabelas.

Os serviços de armazenamento quando são criados possuem camadas de acesso que são listadas como;

* Frequente - Dados acessados com frequência.
* Esporádico.- Dados com acesso esporárico a armazenados por 30 dias.
* Frio - Dados com acesso esporárico a armazenados por 90 dias.
* Arquivo Morto - Dados com acesso esporárico a armazenados por 180 dias.

### Redundância de armazenamento ###

O Microsoft Azure configura a redundância dos armazenamentos permitindo quatro opções conforme a necesidade.

| Opção | Implantação | Durabilidade |
|-------|-------------|--------------|
|LRS - Redundância Local| Datacenter Individual | 11 noves |
|ZRS - Redundância de Zona | Utiliza três zonas de disponibilidade | 12 noves |
|GRS - Redundância Geográfica | Utiliza datacenter primário e região secundária | 16 noves |
| GZRS - Redundância com Zona Geográfica | Três zonas primárias e uma região secundária | 16 noves |

### Migrações ###

O Microsoft Azure disponibiliza recursos para migrações que atendem diversos cenários e estes são;

***Azure Data Box*** - serviço de migração de dados físicos, armazena até 80TB de dados. Permite mover backups de recuperação de desastre de locais remotos com conectividade limitada ou sem para o Azure fisicamente. Slide 21

***AzCopy*** - Utilitário de linha de comando que sincroniza de forma unilateral. Ele copia Blobs ou arquivos para sua conta de armazenamento(Storage Account).

***Gerenciamento de Armazenamento do Azure*** - Utiliza interface gráfica semelhante ao Windows Explorer, com compatibilidade com Windows, Linux e MacOS. Basicamente é o AzCopy em interface gráfica.

***Sincronização de Arquivos do Azure*** - Sincroniza os arquivos de forma bidirecional, e a camada de nuvem mantém os arquivos com frequência no local, liberando espaço local dos arquivos menos utilizados.

## Identidade, Acesso e Segurança ##

### Microsoft Entra ID ###

Serviço de diretório do Microsoft Azure, é uma nova nomenclatura para o antigo Microsoft Active Directory, onde podemos gerenciar as identidades dos usuários, seus acessos a recursos e dispositivos, entre outros.

***Microsoft Entra Domain Services***

Permite sincronizar usuários em redes locais (On-Premises) para domínio da Nuvem de forma que toda atualização de usuários locais são sincronizadas no ambiente de nuvem. Lembrando que não é possível a sincronização reversa, como por exemplo criar um novo usuário na nuvem ele não fica disponível na rede local.

### Autenticação e autorização ### 

Métodos de Autenticação

***SSO (Single Sign On)*** - permite o logon único do usuário em dispositivos, aplicações e serviços.

***MFA*** - utiliza dois ou mais elementos(algo que você é/sabe/possui) para autenticação de usuário.

***External ID (colaboração B2B)*** - utiliza identidades de usuários de fora da organização, como por exemplo o login usando um e-mail de terceiros ou uma conta de uma rede social.

***External ID (colaboração B2C)*** - utiliza identidades de usuários consumidores de seus aplicativos autenticando através de sua conta de e-mail particular ou  de uma rede social.

### Métodos de Autorização ###

***Acesso condicional*** - é através de localização, aplicativo utilizado, dispositivo, associação de usuário ou grupo e por fim através de detecção de risco. 

***RBAC - Controle de acesso baseado em função.*** - sua autorização é baseada em funções de credenciais, como por exemplo usuários que são integrantes do grupo "financeiro" após autenticados acessam recursos do departamento financeiro dentro do ambiente computacional.

### Modelos de proteção ###

***Zero-Trust (confiança zero)*** - modelo de segurança onde todos os acessos são criados com restrição máxima, no qual são liberados apenas recursos ou acessos no qual o usuário tem permissão.

***Proteção em Camadas*** - é um modelo de segurança onde a proteção da camada superior blinda as camadas inferiores. Um exemplo de como funciona esse modelo é no painel abaixo;

1. Segurança física
2. Identidade e acesso
3. Perímetro
4. Rede
5. Computação
6. Aplicativo
7. Dados

### Microsoft Defender for Cloud ###

É um serviço de proteção e monitoramento de ameaças do Microsoft Azure.
Analisa e identifica ataques, detecta e bloqueia malware e analisa seu ambiente e recomenda melhorias.

## Gerenciamento de custos no Microsoft Azure ##

No Microsoft Azure temos um recurso que permite calcular custos e preços e também faz o gerenciamento de custos.

Esta calculadora permite estimar os custos de migração ou implantação de recursos para nuvem, como também a calculadora de custo total de propriedade (TCO) usado para estimar custos ao migrar a infraestrutura para o Microsoft Azure comparando o ambiente atual para o ambiente em nuvem.

### Fatores de custos ###

1. Tipos de recursos - Custos agregados por recursos, como por exemplo uma VM para servidor de DB tem mais recursos e é mais custoso por ser IaaS do que apenas contratar um banco de dados na modalidade PaaS.

2. Consumo - alguns serviços ou recursos tem cobrança por uso, portanto mal dimensionado o uso do serviço ou recurso pode ter um alto custo. Nesta situação planejamento é fundamental para determinar como será o modelo que pode ser de consumo ou de reserva(no qual tem uma cobrança ajustada) que pode ser mais econômica.

3. Manutenção - ajuste de recursos para que seu consumo seja otimizado, neste caso o monitoramento do ambiente é importante para identificar recursos ociosos e ajustes no dimensionamento destes recursos, como por exemplo o uma VM que consome apenas 1GB de vRAM mas está configurada com 8GB, portanto estes  6 ou 7GB aumentam o valor da VM sem necessidade e a redução dessa memória faz o uso inteligente da VM, além de reduzir seu valor.

4. Área geográfica - ajuste do local dos recursos antes de implantá-los é essencial para uma economia, pois dependendo da região geográfica, um recurso fica mais caro que em outro Em alguns casos pode-se pagar mais caro pelo recursos mas se faz necessário para atender a uma legislação do pais ou politica da empresa.

5. Tráfego de rede - custo de tráfego de redes entre regiões ou comunicações

6. Assinatura - tipo e configuração de assinatura afetam os custos pois vários tipos de assinaturas possuem acessos a recursos distintos.

### Azure Market Place ###

Loja de aplicativos e serviços virtualizados de terceiros que podem ser adquiridos para uso em seu ambiente. Estes recursos não nativos(de terceiros) são de responsabilidade do cliente a sua manutenção e até mesmo suporte. A Microsoft não dá suporte ao produto, sempre acione o fabricante do recurso não nativo.

### Gerenciamento de Custos ###

O Microsoft Azure possui ferramentas de monitoramento de custos com relatórios de cobrança e gatilhos de alertas para um melhor controle do ambiente, como características então podemos afirmar que;

- O gerenciamento permite recomendar ajustes de custos.
- Permite alertar quando custos pré-definidos que estão no limiar, evitando surpresas na fatura.
- Orçamento define os orçamentos de gastos para os recursos.

### Tags(Marcas) do Microsoft Azure ###

A função das tags é identificar recursos dentro do ambiente em nuvem no qual são utilizadas para identificar corretamente estes recursos nas faturas ou relatórios do Microsoft Azure (Taxonomia).

As tags não são obrigatórias e não herdáveis, portanto apesar de estarem disponível na hora de criar um recurso, são utilizadas para organizar os recursos principalmente para reunir informações de cobrança. São normalmente criadas em um par de nome-valor como por exemplo "Departamento" = "Financeiro".

## Governança e conformidade ##

### Azure Policy ###

Ele permite que o administrador imponha padrões nos recursos de nuvem mantendo o uso destes recursos em conformidade com os padrões da empresa ou organização.

O Azure Policy permite avaliar e identificar os recursos que foram implantados anteriormente e que não atendam as políticas implantadas, como fornece definições de políticas em categorias dos tipos de recursos como rede, segurança, computação e monitoramento.

### Bloqueio de recursos ###

Através do portal do Azure podemos gerenciar os bloqueios aplicados na assinatura, nos grupos de recursos e por fim nos próprios recursos. Isso impede modificações ou exclusões acidentais ou de forma irresponsável. Lembrando que os bloqueios são herdáveis, portanto deve-se atentar a melhor estratégia de bloqueio.

|Tipos | Ler | Atualizar | Excluir |
|---|---|---|---|
|Excluir | SIM |SIM|NÃO|
|ReadOnly | SIM | NÃO | NÃO |

### Portal de Confiança do Serviço ###

Portal da Microsoft onde é apresentando as regras que a Microsoft aplica a todos os seus serviços, como leis, protocolos e regras. Este portal é de acesso aberto a consulta pública.

### Microsoft Purview ###

É uma aplicação de gerenciamento de governança, risco e conformidade. Avaliando regras de compliance das organizações que estão na nuvem. Reunindo insights dos dados locais, multinuvem e software como serviço.

* Descoberta de dados automatizados
* Classificação dos dados confidenciais
* Linhagem dos dados de ponta a ponta