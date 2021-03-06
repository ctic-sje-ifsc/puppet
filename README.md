# Módulos do Puppet

Este repositório contém nossas implementações internas de [puppet](https://puppet.com/), as regras, configurações e módulos utilizados para as máquinas administrativas e de laboratório do Câmpus. Seguimos sempre que possível a [documentação oficial](https://docs.puppet.com).

O Puppet foi a ferramenta que nos permitiu automatizar uma série de tarefas e de __atuar de maneira muito mais rápida no gerenciamento do nosso parque de máquinas__, nos dando o poder de fazer __atualizações e configurações em minutos do parque inteiro__. A partir da consolidação do Puppet vislumbramos um caminho bem interessante a trilhar na __área de infraestrutura ágil e melhorando nossa atuação__.

"*__Automação de infraestrutura__ é o processo de criar scripts de ambientes — da instalação de um sistema operacional até a instalação e configuração de serviços em instâncias, a configuração de como as instâncias e softwares comunicam-se entre si, e muito mais. Criando scripts para ambientes, é possível aplicar a mesma configuração a um único nó ou a milhares.
A automação de infraestrutura também atende por outros nomes: gerenciamento de configuração, gerenciamento de TI, fornecimento, infraestruturas em script, gerenciamento de configuração do sistema e muitos outros termos que se sobrepõem. O sentido é o mesmo: sua infraestrutura e sua configuração estão sendo descritas como um ou um conjunto de scripts para que os ambientes possam ser replicados de maneira muito menos propensa a erros*". [Referência](https://www.ibm.com/developerworks/br/library/a-devops2/index.html)

![InfraAgil](http://papodesysadmin.org/wp-content/uploads/2016/08/infra_agil_eixos.png)

*"__Puppet__ é um utilitário para gerenciamento de configuração de código livre. Ele roda em muitos sistemas Unix-compativeis bem como em Microsoft Windows, e inclui sua própria linguagem declarativa para descrever a configuração do sistema.
O usuário descreve recursos do sistema e seu estado, usando a linguagem declarativa do Puppet ou uma (Linguagem_de_domínio_específico). Esta informação é armazenada em arquivos chamados "Puppet manifests". Puppet descobre a informação do sistema e compila os arquivos Manifests em um sistema específico com recursos e dependências catalogados, que são aplicados no sistema alvo. Quaisquer ações tomadas pelo Puppet são então relatadas."* [Referência](https://pt.wikipedia.org/wiki/Puppet)

![PuppetLogo](https://upload.wikimedia.org/wikipedia/en/0/09/Puppet%27s_company_logo.png)
