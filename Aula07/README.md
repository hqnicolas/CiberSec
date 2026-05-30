CyberSATC 2026 

Compilado de Palestras - Cibersegurança & Infraestrutura 

* **Realização:** SATC - Educação e Negócios 


* **Data e Local:** 26 e 27 de maio de 2026 | AM Master Hall | Criciúma, SC 


* **Apoio:** Ministério da Ciência, Tecnologia e Inovação | Governo do Brasil 


* **Documentado por:** Lucas Siqueira Sosa - Desenvolvedor de Software e Acadêmico de Engenharia da Computação 



---

CIBERSEGURANÇA E INFRAESTRUTURA CRÍTICA 

**Riscos, Ameaças e o Caminho para a Resiliência Nacional** *Leonardo Lemes Fagundes - Professor Universitário e Especialista em Segurança Cibernética* 

### Introdução

Vivemos em uma sociedade radicalmente dependente de sistemas digitais interconectados. Energia, água, transporte, saúde, comunicação e o sistema financeiro funcionam sobre uma camada invisível de tecnologia que sustenta o cotidiano de milhões de pessoas. Quando essa camada é atacada, as consequências ultrapassam a tela do computador: tornam-se filas de gasolina, hospitais paralisados, panes financeiras e, em última instância, caos social. Este documento sintetiza os principais pontos abordados na palestra sobre cibersegurança em infraestruturas críticas — os riscos, os atores envolvidos, casos reais de impacto e os caminhos possíveis para construirmos resiliência no Brasil e no mundo. 

### O Que é Infraestrutura Crítica

Chamamos de infraestrutura crítica o conjunto de instalações e serviços essenciais para o funcionamento de um país — sem os quais a sociedade não consegue operar normalmente. Estão nesse grupo os setores de energia, água, transporte, comunicação, saúde, financeiro, internet e espaço aéreo, entre outros. Os ataques do 11 de setembro de 2001 marcaram um divisor de águas na percepção global sobre a importância de proteger essas infraestruturas. A partir dali, governos passaram a tratar a questão como pauta de segurança nacional. Hoje, porém, as ameaças mais sofisticadas não vêm mais de aviões sequestrados — vêm de teclados conectados a redes industriais. 

#### O Efeito Dominó

A grande vulnerabilidade da infraestrutura crítica moderna está na sua interconexão. Um ataque bem-sucedido em um único setor pode desencadear uma reação em cadeia: 

* **Ataque Cibernético** → **Energia Cai** → **Comunicação Falha** → **Sistema Financeiro Para** → **Saúde e Outros Colapsam** → **Caos Social** 



#### Guerra Cibernética e o Caso África do Sul

O caso mais emblemático da atualidade é o conflito entre Rússia e Ucrânia, onde operações cibernéticas têm sido usadas como instrumento direto de guerra. Ficou demonstrado que é possível paralisar um país inteiro com um ataque cirúrgico, sem disparar um único tiro. 

Na África do Sul, em 2019, um ataque de ransomware criptografou os bancos de dados, aplicativos e rede da City Power, distribuidora de energia de Joanesburgo, impedindo clientes de comprar eletricidade. Em 2022, a Eskom — única grande fornecedora de energia do país - também foi vítima de ransomware, com dados sensíveis à venda na dark web. Por dominar o setor elétrico nacional, a Eskom representa um ponto único de falha: qualquer ataque bem-sucedido tem consequências para o país inteiro. 

### Os Atores Por Trás dos Ataques

Entender quem ataca é tão importante quanto entender como atacam. Quatro grandes grupos compõem o cenário de ameaças cibernéticas: 

* **Cibercriminosos (Motivação Financeira):** Atores com interesse, conhecimento e recursos para monetizar o crime digital. O modelo de Crime como Serviço (Crime-as-a-Service) tornou-se tão rentável que, em alguns casos, supera o tráfico de drogas. O crime organizado tradicional migrou para o ciberespaço, encontrando ali um modelo de negócio extremamente lucrativo e com risco operacional muito menor. 


* **Estados-Nação (Motivação Geopolítica):** Governos utilizam capacidades cibernéticas para espionagem, sabotagem e guerra. Contam com recursos praticamente ilimitados e objetivos estratégicos de longo prazo, muitas vezes invisíveis às vítimas até o momento da exposição. 


* **Hacktivistas (Motivação Ideológica):** Movidos por causas políticas, sociais ou ideológicas — atacam para protestar, expor ou desestabilizar instituições. A capacidade técnica é variável: de amadores a grupos com nível próximo de operações estatais. Em 2022, após a morte de Mahsa Amini, o coletivo Anonymous lançou a #OpIran. Atacaram o Banco Central do Irã, bancos nacionais, uma planta petroquímica offshore e invadiram o banco de dados do parlamento iraniano, vazando dados pessoais de parlamentares. Também atingiram a presidência e a mídia estatal, principalmente via ataques DDoS. 


* **Ameaças Internas:** Funcionários mal-intencionados ou negligentes com acesso legítimo representam um dos vetores mais difíceis de detectar. A ameaça vem de dentro — atravessa todas as camadas de defesa perimetral porque tecnicamente tem permissão para estar ali. 



### TTPs - Táticas, Técnicas e Procedimentos

Independentemente de quem ataca, a maioria das operações ofensivas segue um padrão dividido em cinco fases: 

| Fase | Descrição |
| --- | --- |
| **Reconhecimento** | Mapeamento do alvo via OSINT, varredura de portas e identificação de sistemas expostos (SCADA/ICS). A ferramenta Shodan permite localizar sistemas industriais na internet com poucos cliques. |
| **Acesso Inicial** | Spear-phishing, credenciais comprometidas e exploração de vulnerabilidades em VPNs. Com IA generativa e deepfakes, essa etapa está cada vez mais automatizada e personalizada. |
| **Persistência** | Backdoors, webshells e contas privilegiadas criadas silenciosamente. O atacante pode permanecer meses na rede sem ser detectado, observando e aguardando o momento certo. |
| **Movimento Lateral** | Pivô entre redes IT e OT. Escalada de privilégios para alcançar sistemas de controle industrial. Ambientes IT/OT deveriam ser segregados mas raramente estão. |
| **Impacto** | Ransomware, wipers, sabotagem de PLCs e SCADA. Do dado criptografado ao equipamento fisico danificado - passando por interrupções massivas de serviço. |

#### As Principais Ameaças em Operação

| Ameaça | Descrição |
| --- | --- |
| **Ransomware** | Alto impacto. Criptografa dados e sistemas, exigindo resgate. Pode paralisar operações inteiras por dias ou semanas. |
| **DDoS** | Escala massiva. Sobrecarregam serviços até derrubá-los. Usados por hacktivistas e como cortina de fumaça para ataques paralelos mais sofisticados. |
| **Roubo de Dados** | Espionagem. Extração silenciosa de informações sensíveis, segredos de Estado e propriedade intelectual. O dano pode levar anos para se manifestar. |
| **Sabotagem OT/ICS** | A ameaça mais crítica. Ataca PLCs e SCADA com potencial de causar danos físicos reais: explosões, apagões e falhas em usinas. |

### Impactos Reais

Quando um ataque cibernético atinge infraestrutura crítica, o impacto se desdobra em duas dimensões que se reforçam mutuamente: 

| Impacto Social | Impacto Econômico |
| --- | --- |
| Rotinas de milhões paralisadas instantaneamente. | Bilhões em perdas diretas e indiretas. |
| Hospitais sem sistemas - vidas em risco. | Cadeias de suprimento quebradas. |
| Perda de confiança em tecnologia e em governo. | Preços sobem por escassez de bens e serviços. |
| Pânico, ansiedade e trauma coletivo. | Multas regulatórias e custos elevados de recuperação. |

Casos Reais que Marcaram a História 

**Colonial Pipeline (EUA, 2021):** Em maio de 2021, o grupo DarkSide invadiu a maior operadora de dutos de combustível refinado dos EUA explorando uma única credencial VPN sem autenticação multifator (MFA). Em duas horas, exfiltraram ~100 GB de dados e instalaram ransomware nos sistemas críticos. 

* Escassez de combustível em toda a Costa Leste dos EUA. 


* Estado de emergência declarado em 5 estados americanos. 


* Filas quilométricas e pânico nos postos de combustível. 


* Resgate de US$ 4,4 milhões pago em bitcoin (75 BTC). 


* **A Lição:** O ataque não causou dano físico direto - foi o próprio operador quem desligou o sistema por precaução. Uma única credencial VPN sem MFA paralisou a cadeia energética de uma região inteira. A ameaça cibernética não precisa quebrar nada para gerar caos: basta forçar o desligamento. 



**Outros Casos Emblemáticos** 

| Caso | Categoria | Impacto |
| --- | --- | --- |
| **Stuxnet** | Arma cibernética | Primeiro malware a causar dano físico real — sabotou centrífugas nucleares iranianas. |
| **Rede Elétrica Ucraniana** | Sabotagem OT | Apagão deliberado por ataque coordenado — marco da guerra cibernética Rússia x Ucrânia. |
| **Oldsmar, EUA** | Saúde Pública | Invasor tentou aumentar drasticamente o nível de soda cáustica na água potável de uma cidade. |

### Brasil e América Latina no Radar

O Brasil não é apenas observador desse cenário — é um dos principais alvos: 

* 356 bilhões de tentativas de ataques cibernéticos contra o Brasil em 2024 (FortiGuard Labs). 


* 38,73% de todas as atividades maliciosas da América Latina têm o Brasil como alvo — o maior da região. 


* +95% de aumento nos ciberataques contra organizações brasileiras no 3º trimestre de 2024 (Check Point). 


* Indústrias brasileiras em alerta crescente para ataques a sistemas OT, com risco direto a operações físicas. 



**Cabos Submarinos - Vulnerabilidade Estratégica:** Entre 16 e 17 cabos submarinos chegam à costa brasileira, sustentando praticamente toda a conectividade internacional do país e, portanto, grande parte da nossa economia digital. O tema é tão extenso e crítico que, sozinho, renderia uma palestra inteira. 

**Política Nacional e o Diagnóstico:** O Brasil já possui um arcabouço legal estruturado sobre o tema, incluindo o Decreto 9.573/2018 (institui a Política), o Decreto 10.569/2020 (regulamenta a estrutura) e o Decreto 11.200/2022 (aprova o Plano Nacional).  As políticas públicas brasileiras já são bem formalizadas. O que falta é investimento real e prática para colocá-las em execução.  Existe lei — falta operação. Existe diretriz — falta orçamento. Existe consciência no papel — falta consciência nos boards. 

### O Caminho para a Resiliência

Não existe defesa absoluta no ciberespaço, mas existe um caminho concreto rumo à resiliência. Cinco pilares sustentam essa jornada: 

1. **Responsabilidade:** cada ator (público, privado e cidadão) deve assumir seu papel na proteção do ecossistema digital. 


2. **Gestão de Risco:** identificar, avaliar e mitigar ameaças de forma contínua, com base em dados e inteligência. 


3. **Educação e Conscientização:** o fator humano é, simultaneamente, o elo mais fraco e a primeira linha de defesa. 


4. **Cooperação Internacional:** ameaças globais exigem respostas coordenadas entre países, agências e empresas. 


5. **Resposta Inteligente:** capacidade de detecção, reação e recuperação rápida, baseada em planos testados e automação. 



**O Gap de Talentos:** Estima-se um déficit de cerca de 400 mil profissionais de cibersegurança apenas no Brasil. Sem gente capacitada, não há política que se sustente, não há tecnologia que se opere e não há defesa que se mantenha. 

> "A cibersegurança deixou de ser um assunto técnico restrito ao departamento de TI. Tornou-se uma questão de Estado, de soberania, de saúde pública e de continuidade da vida em sociedade. Quando um hospital perde acesso aos prontuários, uma família perde acesso a remédios. Quando um banco trava, milhões perdem acesso ao próprio dinheiro. Quando um duto para, uma região inteira entra em pânico. Não se trata de prever todos os ataques — isso é impossível. Trata-se de construir uma sociedade capaz de absorver impactos, responder rápido e voltar a operar. Resiliência não é a ausência de crise; é a capacidade de atravessá-la sem colapsar." 
> "Proteger infraestrutura crítica é proteger a vida cotidiana, a nossa sociedade e a soberania nacional." — Leonardo Lemes Fagundes 
> 
> 

---

CONTINUIDADE DE NEGÓCIOS - MUITO ALÉM DA TECNOLOGIA 

**Como organizações sobrevivem a desastres cibernéticos e naturais** *William Bianchi Tavares - CTO, NGXit* 

### Introdução

A palestra de William Bianchi Tavares, CTO da NGXit, trouxe uma perspectiva fundamental: a continuidade de negócios vai muito além da tecnologia. Usando como estudo de caso real as enchentes do Rio Grande do Sul, o palestrante mostrou como um desastre — seja natural ou cibernético — pode colapsar simultaneamente todos os pilares que sustentam uma organização. A mensagem central é clara: não basta ter um plano de TI. É preciso pensar em pessoas, processos, finanças, clientes e cadeia de suprimentos — tudo ao mesmo tempo, antes que o desastre aconteça. 

### O Que É Continuidade de Negócios?

"Capacidade da organização de continuar a entrega de produtos ou serviços em um nível aceitável, previamente definido, após incidentes de interrupção." Três palavras-chave nessa definição merecem atenção especial: 

* **Continuar:** não se trata de evitar o incidente, mas de manter a operação mesmo durante e após ele. 


* **Nível aceitável:** o objetivo não é operar a 100%, mas a um patamar mínimo que preserve clientes, receita e reputação. 


* **Previamente definido:** o plano precisa existir antes do desastre. Improvisar no meio do caos é tarde demais. 



### Cibernético ou Natural - O Impacto é o Mesmo

As enchentes do Rio Grande do Sul mostraram que um desastre natural pode causar exatamente os mesmos colapsos que um ataque cibernético sofisticado: sistemas offline, equipes impossibilitadas de trabalhar, fornecedores inacessíveis, clientes sem atendimento e fluxo de caixa comprometido. A origem do incidente muda — as consequências organizacionais são as mesmas. 

### Os 7 Pilares da Continuidade de Negócios

O slide apresentado na palestra organizou a continuidade de negócios em sete pilares interdependentes. A grande lição é que proteger apenas um deles — como a tecnologia de TI — não garante a sobrevivência da organização se os demais colapsarem: 

| Pilar | Foco | Perguntas-chave |
| --- | --- | --- |
| **1. Produtos** | Linhas de negócio e produtos ofertados. | Quais produtos podem continuar sendo entregues durante o incidente? Quais precisam ser suspensos? Há alternativas ou versões degradadas aceitáveis? |
| **2. Clientes e Receita** | Continuidade dos clientes atuais, prospecção e linhas de receita. | Como manter o relacionamento com clientes existentes? A receita será impactada? Por quanto tempo a organização aguenta sem faturar? |
| **3. Pessoas** | Colaboradores e cultura organizacional. | Os colaboradores estão seguros? Conseguem trabalhar remotamente? A cultura de crise existe? Há planos de comunicação interna? |
| **4. Cadeia de Suprimentos** | Insumos, fornecedores e logística. | Os fornecedores críticos também foram afetados? Há fornecedores alternativos? Os insumos essenciais têm estoque de segurança? |
| **5. Estrutura e Facilities** | Ambiente para colaboradores, clientes e fornecedores. | O escritório/fábrica está operacional? Há sites alternativos? O acesso físico ao local é possível? |
| **6. Processos e Tecnologia** | Processos de negócio + tecnologias de TI e segurança. | Quais sistemas são críticos? Há backups testados? Os processos manuais de contingência existem e são conhecidos pela equipe? |
| **7. Financeiro e Orçamento** | Fluxo de caixa, custos e nova visão orçamentária. | Qual é o custo diário do incidente? A empresa tem reservas para sustentá-lo? Há seguro cibernético ou de desastre? |

**A Interdependência:** Nenhum dos sete pilares funciona de forma isolada. O colapso de um inevitavelmente pressiona os demais — criando um efeito cascata que pode transformar um incidente gerenciável em uma crise existencial: 

* **Pessoas indisponíveis** → Processos param, clientes ficam sem atendimento, produtos deixam de ser entregues. 


* **Tecnologia offline** → Processos precisam de alternativas manuais, cadeia de suprimentos perde visibilidade, receita cai. 


* **Cadeia de suprimentos quebrada** → Produtos não podem ser entregues, receita cai, clientes migram para concorrentes. 


* **Caixa comprometido** → Fornecedores param de entregar, pessoas podem ser demitidas, estrutura é reduzida. 


* **Estrutura inacessível** → Pessoas não conseguem trabalhar, processos físicos param, clientes não são atendidos. 



**A Lição das Enchentes do RS:** As empresas afetadas perderam funcionários impossibilitados de chegar ao trabalho, fornecedores, estruturas físicas inundadas, acesso a insumos cortado e fluxo de caixa comprometido. Quem sobreviveu melhor foi quem tinha planos — e não apenas planos de TI. 

### O Plano de Continuidade de Negócios (PCN/BCP)

Um Plano de Continuidade de Negócios eficaz não é um documento guardado na gaveta — é um processo vivo, testado regularmente e conhecido por toda a organização. Seus componentes essenciais são: 

1. **Análise de Impacto nos Negócios (BIA):** identificar processos críticos, impacto financeiro/operacional de cada interrupção e tempo máximo tolerável (RTO/RPO). 


2. **Análise de Riscos:** mapear as ameaças mais prováveis (desastres naturais, ciberataques, falhas, crises reputacionais, etc.). 


3. **Estratégias de Continuidade:** definir alternativas (sites de backup, fornecedores alternativos, processos manuais). 


4. **Planos de Resposta:** documentar quem faz o quê, quando e como. Comunicação interna e externa incluídas. 


5. **Testes e Simulações:** exercitar o plano. Um plano não testado é apenas um documento — não uma capacidade real. 


6. **Revisão e Melhoria Contínua:** atualizar o plano após cada teste ou incidente. 



**RTO e RPO - Conceitos Fundamentais:** 

* **RTO (Recovery Time Objective):** quanto tempo a organização pode ficar sem um processo crítico antes que o impacto seja inaceitável. 


* **RPO (Recovery Point Objective):** quanto de dado/histórico a organização pode perder — até quando os backups precisam remontar. 


* *Esses dois números precisam ser definidos antes do incidente, não durante.* 



### Tecnologia é Meio, Não Fim

A tecnologia é fundamental — mas é apenas um dos sete pilares. 

| Visão Limitada (só TI) | Visão Completa (PCN real) |
| --- | --- |
| Backup dos servidores | Backup dos servidores + processos manuais de contingência |
| Plano de recuperação de dados | Plano para pessoas, processos, fornecedores e comunicação |
| Sistemas em nuvem | Sistemas + pessoas capacitadas + acordos com fornecedores alternativos |
| Teste de restore de backup | Simulação completa de crise com todas as áreas envolvidas |
| Responsabilidade do TI | Responsabilidade da liderança executiva — com apoio do TI |

**Conexão com a Cibersegurança:** A continuidade de negócios e a cibersegurança são faces do mesmo desafio. Um ataque cibernético bem-sucedido é, em última instância, um incidente de continuidade de negócios.  Times de segurança e de continuidade precisam trabalhar juntos. O plano de resposta a incidentes deve estar integrado ao PCN. 

> "Continuidade de negócios não é um projeto de TI. É uma decisão estratégica de liderança. Exige que o board entenda os riscos, que os processos sejam documentados, que as pessoas sejam treinadas e que os planos sejam testados — antes que a crise chegue. Organizações que tratam continuidade como burocracia ou como responsabilidade exclusiva da área de tecnologia descobrem, no pior momento possível, que um plano incompleto não é melhor que nenhum plano — é apenas uma falsa sensação de segurança. Continuidade de negócios é a capacidade de continuar entregando valor mesmo quando tudo ao redor está falhando. É a diferença entre sobreviver e desaparecer." 
> 
> 

---

MERCADO, DESAFIOS E CARREIRA EM SEGURANÇA DA INFORMAÇÃO 

**Panorama, ameaças e o caminho para profissionais de InfoSec** *Guilherme de Moraes - Senior Manager, Fortinet* 

### A Fortinet no Brasil

A palestra abriu apresentando a posição da Fortinet no mercado nacional: 

* **#1 em presença geográfica no Brasil** (Presença em todas as regiões). 


* **+70% de market share** (Maior participação no Brasil). 


* **300+ funcionários** (Sede em SP e TAC em Uberlândia). 


* **3.000+ canais parceiros** e **13+ parceiros acadêmicos**. 


* **Great Place to Work** (9º ano consecutivo). 



### O Que É Segurança da Informação?

"A segurança da informação, ou InfoSec, inclui as ferramentas e processos para prevenir, detectar e corrigir ataques e ameaças a informações confidenciais, tanto digitais quanto não digitais." InfoSec não se limita ao mundo digital.  Abrange documentos físicos, controle de acesso e processos. A defesa começa muito antes do firewall. 

Segundo o WEF Global Risks Report 2026, a cyber insegurança aparece entre os 10 maiores riscos globais — ao lado de crises climáticas, geopolíticas e sociais.  A cibersegurança não é mais um problema de TI — é um problema civilizatório. Isso muda completamente a forma como empresas e governos precisam tratar o tema. 

### O Ecossistema do Crime Cibernético

O cibercrime funciona hoje como uma indústria estruturada em três grandes camadas: 

1. **Produtores:** Quem fabrica as armas digitais (exploits, packers). Desenvolvedores sênior criam o código original; desenvolvedores júnior copiam e adaptam. 


2. **Cibercrime Composto:** Quem opera e distribui em escala. Organizações criminosas centralizam as operações; trabalham com afiliados em modelo de franquias. 


3. 
**Facilitadores de Serviços:** A infraestrutura de suporte (hospedagem, garantia de qualidade, aluguel de botnets, lavagem de dinheiro, consultoria). 



O cibercrime não é mais obra de hackers solitários no porão de casa. É uma cadeia produtiva profissional. Quem ataca sua empresa hoje pode ser apenas um operador final de uma indústria multinacional do crime. 

### O Gap de Profissionais e a Mudança de Mentalidade

Enquanto o cibercrime se profissionaliza, o lado da defesa enfrenta um déficit gigantesco: 

* **750 mil profissionais** são necessários para preencher o gap de SI no Brasil (Fortinet Skills Gap Report 2024 — e crescendo). 


* **Quase 90%** das empresas brasileiras sofreram uma violação no último ano. 


* **70%** atribuem o aumento dos riscos à lacuna de competências. A superfície de ataque se expande mais rápido do que a formação de profissionais — um ciclo que se retroalimenta. 



O Brasil deve investir R$ 104,6 bilhões em cibersegurança até 2028 (estudo Brasscom).  Segurança sempre foi vista como custo. Precisa ser vista como investimento. Três pilares desse investimento são: **Treinamento**, **Contratação** e **Retenção**. 

### Casos Reais: Aprendendo com o Passado

* **WannaCry (2017):** O patch que corrigia a vulnerabilidade já existia 2 meses antes do ataque. Faltou higienização cibernética básica. Muitas vezes as empresas não atualizam devido a incompatibilidades ou invalidação de certificações de equipamentos (ex: máquinas médicas), rodando sistemas vulneráveis por restrições técnicas. 


* **Lurie Children's Hospital:** Hospital pediátrico americano atacado pelo grupo Rhysida (RaaS). Levou quase 4 meses para recuperação total. Dados médicos foram ofertados por US$ 3,4 milhões. 



**O Mercado de RaaS em 2026:** Só em 2026 foram identificados 13 novos sites/blogs de grupos de ransomware (ex: RansomHub, HellCat) e 13 novos RaaS na Darknet (ex: PlayBoy, Medusa). Qualquer criminoso pode contratar um ataque de ransomware como serviço. 

### Evolução dos Vetores de Ataque (Verizon DBIR 2026)

A intrusão direta dominou o cenário: 

| Vetor | 2024 | 2025 | 2026 |
| --- | --- | --- | --- |
| **System Intrusion** | 36% | 53% | <br>**61%** |
| **Social Engineering** | 22% | 17% | <br>**17%** |
| **Basic Web App Attacks** | 9% | 18% | <br>**10%** |
| **Miscellaneous Errors** | 25% | 12% | <br>**8%** |
| **Privilege Misuse** | 8% | 7% | <br>**3%** |

**Infostealers e o SSO:** 1,7 bilhão de registros de stealer logs já foram compartilhados. O tipo de credencial mais roubada é o SSO (Single Sign-On - 56%), seguido por Webmail (10%) e GitHub (9%). Uma única credencial SSO dá acesso a dezenas de sistemas — é a chave-mestra. Isso explica o crescimento de "System Intrusion": não é preciso invadir, basta comprar o acesso pronto. 

### Desafios em 2026 - A Nova Normalidade e a IA

"86% das organizações registraram ao menos um incidente de segurança nos últimos 12 meses." (Fortinet Report 2026). Não é mais questão de *se* a empresa será atacada — é questão de *quando* e *como* vai responder. 

As maiores preocupações com IA são "Vazamento de dados" (45%) e "Ataques cibernéticos com IA" (44%). A mesma tecnologia que defende também ataca. 

### O Profissional do Futuro: Soft Skills e Viés Cognitivo

Além do lado técnico, quatro soft skills são essenciais: 

1. **Solução de problemas:** Raciocínio lógico e criatividade para apagar incêndios. 


2. **Perfil analítico:** Interpretar logs e identificar ameaças em meio ao ruído. 


3. **Comunicação:** Traduzir riscos técnicos para a linguagem de negócios. 


4. **Trabalho em equipe:** Segurança é colaborativa. *O mercado já tem tecnologia — o que falta é o profissional que saiba usá-las, interpretar resultados e comunicar.* 



**Viés Cognitivo:** "O viés cognitivo é um atalho mental que leva a desvios de racionalidade. Ele ocorre porque criamos padrões, baseados nas nossas experiências, que distorcem o nosso julgamento." O analista de segurança lida com o viés de confirmação ("esse alerta sempre é falso positivo") ou de status quo ("o sistema está funcionando, logo está seguro").  Saber que você tem viés já é metade da defesa. A outra metade é construir processos que questionem decisões. 

### Painel de Discussão: Visão Internacional e Considerações Finais

O evento encerrou com um painel mediado por Anderson Farias (Coordenador SATC), com Guilherme Morais (Fortinet) e Giuseppe Lamberto (Executivo de TI da Itália), que trouxe uma visão internacional, evidenciando que desafios e maturidade em cibersegurança são questões universais. 

> O mercado de segurança vive uma equação desbalanceada: crime profissionalizado (86% de organizações atacadas) versus déficit de 750 mil profissionais no Brasil. Para o profissional, a oportunidade é enorme, mas exige mais do que certificações: exige perfil analítico, comunicação e consciência dos próprios vieses. 
> "Segurança sempre foi vista como custo. Precisa ser vista como investimento." — Guilherme de Moraes. 

Riscos, Ameaças e o Caminho para a Resiliência Nacional 

**Leonardo Lemes Fagundes** *Documento de Apoio à Palestra* 

---

CIBERSEGURANÇA E INFRAESTRUTURA CRÍTICA 

**INTRODUÇÃO** Vivemos em uma sociedade radicalmente dependente de sistemas digitais interconectados. Energia, água, transporte, saúde, comunicação e o sistema financeiro funcionam sobre uma camada invisível de tecnologia que sustenta o cotidiano de milhões de pessoas. Quando essa camada é atacada, as consequências ultrapassam a tela do computador: tornam-se filas de gasolina, hospitais paralisados, panes financeiras e, em última instância, caos social. Este documento sintetiza os principais pontos abordados na palestra sobre cibersegurança em infraestruturas críticas os riscos, os atores envolvidos, casos reais de impacto e os caminhos possíveis para construirmos resiliência no Brasil e no mundo.

O QUE É INFRAESTRUTURA CRÍTICA 

Chamamos de infraestrutura crítica o conjunto de instalações e serviços essenciais para o funcionamento de um país sem os quais a sociedade não consegue operar normalmente. Estão nesse grupo os setores de energia, água, transporte, comunicação, saúde, financeiro, internet e espaço aéreo, entre outros.

Os ataques do 11 de setembro de 2001 marcaram um divisor de águas na percepção global sobre a importância de proteger essas infraestruturas. A partir dali, governos passaram a tratar a questão como pauta de segurança nacional. Hoje, porém, as ameaças mais sofisticadas não vêm mais de aviões sequestrados vêm de teclados conectados a redes industriais.

O Efeito Dominó 

A grande vulnerabilidade da infraestrutura crítica moderna está na sua interconexão. Um ataque bem-sucedido em um único setor pode desencadear uma reação em cadeia:

Ataque Cibernético → Energia Cai → Comunicação Falha → Sistema Financeiro Para / Saúde e Outros Colapsam → Caos Social.

Guerra Cibernética 

O caso mais emblemático da atualidade é o conflito entre Rússia e Ucrânia, onde operações cibernéticas têm sido usadas como instrumento direto de guerra. Ficou demonstrado que é possível paralisar um país inteiro com um ataque cirúrgico sem disparar um único tiro.

> 
> **CASO ÁFRICA DO SUL** Em 2019, um ataque de ransomware criptografou os bancos de dados, aplicativos e rede da City Power, distribuidora de energia de Joanesburgo, impedindo clientes de comprar eletricidade. Em 2022, a Eskom única grande fornecedora de energia do país - também foi vítima de ransomware, com dados sensíveis à venda na dark web. Por dominar o setor elétrico nacional, a Eskom representa um ponto único de falha: qualquer ataque bem-sucedido tem consequências para o país inteiro.
> 
> 

---

OS ATORES POR TRÁS DOS ATAQUES 

Entender quem ataca é tão importante quanto entender como atacam. Quatro grandes grupos compõem o cenário de ameaças cibernéticas:

* **Cibercriminosos - Motivação Financeira:** Atores com interesse, conhecimento e recursos para monetizar o crime digital. O modelo de Crime como Serviço (Crime-as-a-Service) tornou-se tão rentável que, em alguns casos, supera o tráfico de drogas. O crime organizado tradicional migrou para o ciberespaço, encontrando ali um modelo de negócio extremamente lucrativo e com risco operacional muito menor.


* **Estados-Nação - Motivação Geopolítica:** Governos utilizam capacidades cibernéticas para espionagem, sabotagem e guerra. Contam com recursos praticamente ilimitados e objetivos estratégicos de longo prazo, muitas vezes invisíveis às vítimas até o momento da exposição.


* **Hacktivistas - Motivação Ideológica:** Movidos por causas políticas, sociais ou ideológicas atacam para protestar, expor ou desestabilizar instituições. A capacidade técnica é variável: de amadores a grupos com nível próximo de operações estatais.


* *EXEMPLO REAL - OPERAÇÃO #OpIran:* Em 2022, após a morte de Mahsa Amini, o coletivo Anonymous lançou a #OpIran. Atacaram o Banco Central do Irã, bancos nacionais, uma planta petroquímica offshore e invadiram o banco de dados do parlamento iraniano, vazando dados pessoais de parlamentares. Também atingiram a presidência e a mídia estatal, principalmente via ataques DDoS.


* **Ameaças Internas:** Funcionários mal-intencionados ou negligentes com acesso legítimo representam um dos vetores mais difíceis de detectar. A ameaça vem de dentro atravessa todas as camadas de defesa perimetral porque tecnicamente tem permissão para estar ali.



---

TTPs - TÁTICAS, TÉCNICAS E PROCEDIMENTOS 

Independentemente de quem ataca, a maioria das operações ofensivas segue um padrão dividido em cinco fases:

| Fase | Descrição  |
| --- | --- |
| <br>**Reconhecimento** | Mapeamento do alvo via OSINT, varredura de portas e identificação de sistemas expostos (SCADA/ICS). A ferramenta Shodan permite localizar sistemas industriais na internet com poucos cliques. |
| <br>**Acesso Inicial** | Spear-phishing, credenciais comprometidas e exploração de vulnerabilidades em VPNs. Com IA generativa e deepfakes, essa etapa está cada vez mais automatizada e personalizada. |
| <br>**Persistência** | Backdoors, webshells e contas privilegiadas criadas silenciosamente. O atacante pode permanecer meses na rede sem ser detectado, observando e aguardando o momento certo. |
| <br>**Movimento Lateral** | Pivô entre redes IT e OT. Escalada de privilégios para alcançar sistemas de controle industrial. Ambientes IT/OT deveriam ser segregados mas raramente estão. |
| <br>**Impacto** | Ransomware, wipers, sabotagem de PLCs e SCADA. Do dado criptografado ao equipamento fisico danificado - passando por interrupções massivas de serviço. |

As Principais Ameaças em Operação 

| Ameaça | Descrição |
| --- | --- |
| <br>**Ransomware** | Alto impacto. Criptografa dados e sistemas, exigindo resgate. Pode paralisar operações inteiras por dias ou semanas. |
| <br>**DDoS** 

 | Escala massiva. Sobrecarregam serviços até derrubá-los. Usados por hacktivistas e como cortina de fumaça para ataques paralelos mais sofisticados. |
| <br>**Roubo de Dados** | Espionagem. Extração silenciosa de informações sensíveis, segredos de Estado e propriedade intelectual. O dano pode levar anos para se manifestar. |
| <br>**Sabotagem OT/ICS** | A ameaça mais crítica. Ataca PLCs e SCADA com potencial de causar danos físicos reais: explosões, apagões e falhas em usinas. |

---

IMPACTOS REAIS 

Quando um ataque cibernético atinge infraestrutura crítica, o impacto se desdobra em duas dimensões que se reforçam mutuamente:

| Impacto Social | Impacto Econômico |
| --- | --- |
| Rotinas de milhões paralisadas instantaneamente. | Bilhões em perdas diretas e indiretas. |
| Hospitais sem sistemas - vidas em risco. | Cadeias de suprimento quebradas. |
| Perda de confiança em tecnologia e em governo. | Preços sobem por escassez de bens e serviços. |
| Pânico, ansiedade e trauma coletivo. | Multas regulatórias e custos elevados de recuperação. |

Casos Reais que Marcaram a História 

**Colonial Pipeline (EUA, 2021)** Em maio de 2021, o grupo DarkSide invadiu a maior operadora de dutos de combustível refinado dos EUA explorando uma única credencial VPN sem autenticação multifator (MFA). Em duas horas, exfiltraram 100 GB de dados e instalaram ransomware nos sistemas críticos.

* Escassez de combustível em toda a Costa Leste dos EUA. 


* Estado de emergência declarado em 5 estados americanos. 


* Filas quilométricas e pânico nos postos de combustível. 


* Resgate de US$ 4,4 milhões pago em bitcoin (75 BTC). 



> 
> **A LIÇÃO DO CASO COLONIAL** O ataque não causou dano físico direto - foi o próprio operador quem desligou o sistema por precaução. Uma única credencial VPN sem MFA paralisou a cadeia energética de uma região inteira. A ameaça cibernética não precisa quebrar nada para gerar caos: basta forçar o desligamento.
> 
> 

**Outros Casos Emblemáticos** 

| Caso | Categoria | Impacto |
| --- | --- | --- |
| <br>**Stuxnet** | Arma cibernética  | Primeiro malware a causar dano físico real sabotou centrífugas nucleares iranianas. |
| <br>**Rede Elétrica Ucraniana** | Sabotagem OT  | Apagão deliberado por ataque coordenado marco da guerra cibernética Rússia x Ucrânia. |
| <br>**Oldsmar, EUA**  | Saúde Pública  | Invasor tentou aumentar drasticamente o nível de soda cáustica na água potável de uma cidade.  |

---

BRASIL E AMÉRICA LATINA NO RADAR 

O Brasil não é apenas observador desse cenário é um dos principais alvos:

* 356 bilhões de tentativas de ataques cibernéticos contra o Brasil em 2024 (FortiGuard Labs). 


* 38,73% de todas as atividades maliciosas da América Latina têm o Brasil como alvo o maior da região. 


* +95% de aumento nos ciberataques contra organizações brasileiras no 3º trimestre de 2024 (Check Point). 


* Indústrias brasileiras em alerta crescente para ataques a sistemas OT, com risco direto a operações físicas. 



**Cabos Submarinos - Vulnerabilidade Estratégica** Entre 16 e 17 cabos submarinos chegam à costa brasileira, sustentando praticamente toda a conectividade internacional do país e, portanto, grande parte da nossa economia digital. O tema é tão extenso e crítico que, sozinho, renderia uma palestra inteira.

**Política Nacional de Segurança de Infraestruturas Críticas** O Brasil já possui um arcabouço legal estruturado sobre o tema:

* **Decreto 9.573/2018:** institui a Política Nacional de Segurança de Infraestruturas Críticas. 


* **Decreto 10.569/2020:** regulamenta a estrutura e os mecanismos de proteção. 


* **Decreto 11.200:** avanços complementares na política nacional. 



**O DIAGNÓSTICO** 
As políticas públicas brasileiras já são bem formalizadas. O que falta é investimento real e prática para colocá-las em execução. Existe lei falta operação. Existe diretriz falta orçamento. Existe consciência no papel falta consciência nos boards.

---

O CAMINHO PARA A RESILIÊNCIA 

Não existe defesa absoluta no ciberespaço, mas existe um caminho concreto rumo à resiliência. Cinco pilares sustentam essa jornada:

1. **Responsabilidade:** cada ator (público, privado e cidadão) deve assumir seu papel na proteção do ecossistema digital. 


2. **Gestão de Risco:** identificar, avaliar e mitigar ameaças de forma contínua, com base em dados e inteligência. 


3. **Educação e Conscientização:** o fator humano é, simultaneamente, o elo mais fraco e a primeira linha de defesa. 


4. **Cooperação Internacional:** ameaças globais exigem respostas coordenadas entre países, agências e empresas. 


5. **Resposta Inteligente:** capacidade de detecção, reação e recuperação rápida, baseada em planos testados e automação. 



---

O GAP DE TALENTOS 

Estima-se um déficit de cerca de 400 mil profissionais de cibersegurança apenas no Brasil. Sem gente capacitada, não há política que se sustente, não há tecnologia que se opere e não há defesa que se mantenha.

CONSIDERAÇÕES FINAIS 

A cibersegurança deixou de ser um assunto técnico restrito ao departamento de TI. Tornou-se uma questão de Estado, de soberania, de saúde pública e de continuidade da vida em sociedade. Quando um hospital perde acesso aos prontuários, uma família perde acesso a remédios. Quando um banco trava, milhões perdem acesso ao próprio dinheiro. Quando um duto para, uma região inteira entra em pânico.

Não se trata de prever todos os ataques isso é impossível. Trata-se de construir uma sociedade capaz de absorver impactos, responder rápido e voltar a operar. Resiliência não é a ausência de crise; é a capacidade de atravessá-la sem colapsar.

> 
> *"Proteger infraestrutura crítica é proteger a vida cotidiana, a nossa sociedade e a soberania nacional."* — **Leonardo Lemes Fagundes** 