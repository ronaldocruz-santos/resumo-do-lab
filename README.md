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