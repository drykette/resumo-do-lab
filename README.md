# Resumo dos Estudos
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO.

<h1>Primeiro Captulo</h1>

<h2>Descobrindo a Nuvem</h2>

Até aqui vimos como criar uma conta no Portal Azure, algumas configurações possiveis como idioma, aparencia. Além de ter visto assuntos como o que é um Serviço de Nuvem, quais os prós e contras. 
Atém dos tipos: Publico, privado e hibrido. 

* Publico: São serviços onde todos podem usar e armazenar suas informações, totalmente em nuvem. 

* Privado: Onde tudo fica armazenado em datacenter local, só na empresa mesmo, sem contato com o mundo exterior. 

* Hibrido: Quando o servidor fica parte da nuvem e parte localmente, dando mais segurança e flexibilidade pra empresa. 

<h2>Beneficios da Nuvem Azure</h2>

Até aqui vimos os beneficios de uma Nuvem Azure e os conceitos basicos. Beneficios de Alta Diponibilidade, Escabilidade, Confiança, Previsibilidade, Confiança, Governança, Capacidade e Gerenciamento. 

<h2>Conceitos de Nuvem</h2>

Até aqui vimos os tipos de serviços de Nuvem: IaaS, PaaS, SaaS.

IaaS - Infraestrutura como serviços: O serviço de nuvem mais flexível, Você configura e gerencia o hardware para seu aplicativo.
* Serviços e armazenamentos;
* Firewalls/Segurança de rede;
* Planta fisíca/Edificio do datacenter.
  
PaaS - Plataforma como serviços: Focado no desenvolvimento de aplicações, O gerenciamneto da plataforma é realizado pelo provedor de nuvem.
* IaaS +
* Sistema Operacionais;
* Ferramentas para desenvolvedores análise de negócios de gerenciamneto da database. 

SaaS - Software como serviço: Modelo de preço de pagamento conforme o uso (licença), Os usuários pagam pelo software que utilizam em um modelo de assinatura. 
* IaaS +
* PaaS +
* Aplicações/ apps hospedados. 
* Os usuários se conectam e usam aplicativos com base em nuvem pela internet, por exemplo: Microsoft office, email e calendarios. 

<h2>Computação e Rede</h2>

* Até aqui vemos os tipos de computação, instâncias de conteiners, maquinas virtuais e funções.
* Opções de hospedagem de aplicativos, aplicativos web, conteiners e maquinas virtuais.
* Redes virtuais, sub-redes, emparelhamento, DNS do gateway de VPN e do ExpressRoute.
* 
<h1>Segundo Captulo</h1>
  
<h2>Armazenamento</h2>

* Até aqui vemos os tipos de armazenamento do Azure.
* Contas de armazenamento, onde deve se ter um nome globalmente exclusivo. 
* Redundância de armazanamento:
*       LRS (Armazenamento com redundancia LOCAL) --- DURABILIDADE --- 11 NOVES
*       ZRS (Armazenamento com redundancia de ZONA) --- DURABILIDADE --- 12 NOVES
*       GRS (Armazenamento com redundancia GEOGRAFICA) --- DURABILIDADE --- 16 NOVES
*       GZRS (Armazenamento com redundancia de ZONA GEOGRAFICA) --- DURABILIDADE --- 16 NOVES
*  BLOB do Azure: Armazenamento de quantidade massiva não estruturado, texto ou dados binarios.
*  DISCO do Azure: Fornece disco para VM's, aplicativos e outros.
*  FILA do Azure: Armazenamento de mensagens, em grande quantidades.
*  ARQUIVOS do Azure: Configura um compartilhamento de arquivos de rede altamente disponivel, que pode ser usado usando o protocolo de bloco de mensagens. 
*  TABELA do Azure: Fornece uma opção de chave/atributo para armazenamento ESTRUTURADO não relacionais. 
*  Camadas de acesso de armazanamento do Azure:  Frequente(Acessados com frequencia), Esporádico(Acessados em pelo menos 30 dias), Frio(Acessados em pelo menos 90 dias) e Arquivo morto(Acessados em pelo menos 180 dias). 
*  Migração para o Azure:
*        Azure DATA BOX até 80Terabytes - Caixa Física - DATA BOX DISK(PEQUENO ATÉ 32TB) - DATA BOX(UM GABINETE COM MAIS CAPACIDADE) - DATA BOX HEAVY(UM CARRINHO COM MUITO MAIS CAPACIDADE ATÉ 80TB) 
*        AzCopy - Utiliza linha de comando - Copia BLOBS ou ARQUIVOS de ou para sua conta de armazenamento - Sincronização em uam direção. 
*        Gerenciador de Armazenamento - Interface gráfica do usuário(semelhante ao windows explore) - Compativel com windows, linux e mac.
*        Sincronização de Arquivos do Azure - Sincroniza de forma bidimencional - Mantém arquivos acessads com frequencia no local enquanto libera espaço.

<h2>Armazenamento</h2>

* Até aqui vemos os meios de Identidade, Acesso e Segurança.
* Serviços de Diretorio incluem o Microsoft Entra ID e o Microsoft Entra Domain Services.
* Metodos de autenticação Azure: SSO(logon Unico), MFA(Autenticação multifator) e sem senha.
* Identidades externas e o acesso de convidados no Azure.
* Acesso condicional do Entra.
* Controle de acesso baseado em função(RBAC).
* Confiança Zero.
  
<h1>Terceiro Captulo</h1>
<h2>Gerenciamento e Governança</h2>

* Fatores que afetam dos custos:
*        1) Tipo de Recurso
*        2) Consumo
*        3) Manutenção
*        4) Area Geografica
*        5) Trafego de Rede
*        6) Assinatura

* Azure Marketplace: Quando recursos que não são do microsoft no Azure marketplace dão problema é preciso contatar o fabricante do mesmo, não do microsoft.
* Calculadora de Preços: Estima o custo dos produtos Azure. 
* Calculadora de custos total de priodidade(TCO): Uma ferramenta para estimar a economia de custos possivel ao migrar para o Azure.
* Gerenciamento de custos do Azure: Relatorios.
* Marcas/Tags: Fornecem metadados aos recursos, organizam os mesmo em uma taxonomia de maneira logica, consistencia em um par nome-valor, muito uteis para reunir informações de cobrança.
*       Marcas não são obrigatorias e não são herdadas. 
* Azure Policy: Ajuda a IMPOR padrões organizacionais e a avaliação a conformidade em escala. Ele fornece GOVERNANÇA e CONSISTENCIA de recursos com a conformidade regulatória, segurança, custo, e gerenciamento.
* Bloqueio de Recurso: Gerencia bloqueios na assinaura, grupos de recursos, ou niveis de recursos individuais dentro do portal do azure.
*       Bloqueios são herdaveis.
*   Microsoft Purview: Da familia de soluções de gonervança, risco, e conformidade. Dados locais, multinuvem e de software como serviço.
*       Descoberta de dados automatizada.
*       Classificação de dados confidenciais.
*       Linhagem de dados de ponta a ponta.
*Ferramenta de implantação de recursos: Portal, poweshell, CL1 (tipo cmd).
*Azure ARC e Azure Resource Menager. 
*Azure ARC: Administra o que está fora do AZURE, e não existe nada equivalente a ele no mercado. 
*ARM(Azure Resource Menager: O ARM fornece uma camada de gerenciamente que permite criar, atualizar e excluir recursos na assinatura AZURE. 
*      Modelos ARM: Os modelos ARM são arquivos em JSON que podem ser usados para criar, implantar a insfraestrutura do AZURE sem a necessidade de escrever comandos de programaçao. 
*      Sintaxe Declarativa, Resultados repetiveis, Orquestração, Arquivos modulares, Validação integrada, Codigo exportavel. 
*Insfraentrutura de codigo: Garanta constancia na impnatação em todo o ecossistema de nuvem, gerencia a configuração em escala, provisione rapidamente.
*Bicep: Linguagem especifica de DSL que usa sintaxe declarativa para implantar recursos apenas dentro do azure. 













