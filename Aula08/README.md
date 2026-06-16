**PALESTRANTES E PARTICIPANTES**
* Leonardo Lemes Fagundes 
* William Bianchi Tavares 
* Guilherme de Moraes 
* Anderson Farias 
* Giuseppe Lamberto (Itália) 

---

CIBERSEGURANÇA E INFRAESTRUTURA CRÍTICA 

**Riscos, Ameaças e o Caminho para a Resiliência Nacional** *Leonardo Lemes Fagundes - Professor Universitário Especialista em Segurança Cibernética* 

INTRODUÇÃO 

Vivemos em uma sociedade radicalmente dependente de sistemas digitais interconectados. Energia, água, transporte, saúde, comunicação e o sistema financeiro funcionam sobre uma camada invisível de tecnologia que sustenta o cotidiano de milhões de pessoas. Quando essa camada é atacada, as consequências ultrapassam a tela do computador: tornam-se filas de gasolina, hospitais paralisados, panes financeiras e, em última instância, caos social. Este documento sintetiza os principais pontos abordados na palestra sobre cibersegurança em infraestruturas críticas: os riscos, os atores envolvidos, casos reais de impacto e os caminhos possíveis para construirmos resiliência no Brasil e no mundo. 

O QUE É INFRAESTRUTURA CRÍTICA 

Chamamos de infraestrutura crítica o conjunto de instalações e serviços essenciais para o funcionamento de um país sem os quais a sociedade não consegue operar normalmente. Estão nesse grupo os setores de energia, água, transporte, comunicação, saúde, financeiro, internet e espaço aéreo, entre outros. Os ataques do 11 de setembro de 2001 marcaram um divisor de águas na percepção global sobre a importância de proteger essas infraestruturas. A partir dali, governos passaram a tratar a questão como pauta de segurança nacional. Hoje, porém, as ameaças mais sofisticadas não vêm mais de aviões sequestrados vêm de teclados conectados a redes industriais. 

**O Efeito Dominó** A grande vulnerabilidade da infraestrutura crítica moderna está na sua interconexão. Um ataque bem-sucedido em um único setor pode desencadear uma reação em cadeia: Ataque Cibernético → Energia Cai → Comunicação Falha → Sistema Financeiro Para → Saúde e Outros Colapsam → Caos Social 

**Guerra Cibernética** O caso mais emblemático da atualidade é o conflito entre Rússia e Ucrânia, onde operações cibernéticas têm sido usadas como instrumento direto de guerra. Ficou demonstrado que é possível paralisar um país inteiro com um ataque cirúrgico sem disparar um único tiro. 

**CASO ÁFRICA DO SUL** Em 2019, um ataque de ransomware criptografou os bancos de dados, aplicativos e rede da City Power, distribuidora de energia de Joanesburgo, impedindo clientes de comprar eletricidade. Em 2022, a Eskom única grande fornecedora de energia do país - também foi vítima de ransomware, com dados sensíveis à venda na dark web. Por dominar o setor elétrico nacional, a Eskom representa um ponto único de falha: qualquer ataque bem-sucedido tem consequências para o país inteiro. 

OS ATORES POR TRÁS DOS ATAQUES 

Entender quem ataca é tão importante quanto entender como atacam. Quatro grandes grupos compõem o cenário de ameaças cibernéticas: 

* **Cibercriminosos - Motivação Financeira:** Atores com interesse, conhecimento e recursos para monetizar o crime digital. O modelo de Crime como Serviço (Crime-as-a-Service) tornou-se tão rentável que, em alguns casos, supera o tráfico de drogas. O crime organizado tradicional migrou para o ciberespaço, encontrando ali um modelo de negócio extremamente lucrativo e com risco operacional muito menor. 


* **Estados-Nação - Motivação Geopolítica:**  Governos utilizam capacidades cibernéticas para espionagem, sabotagem e guerra. Contam com recursos praticamente ilimitados e objetivos estratégicos de longo prazo, muitas vezes invisíveis às vítimas até o momento da exposição. 


* **Hacktivistas - Motivação Ideológica:** Movidos por causas políticas, sociais ou ideológicas atacam para protestar, expor ou desestabilizar instituições. A capacidade técnica é variável: de amadores a grupos com nível próximo de operações estatais. 


* *EXEMPLO REAL - OPERAÇÃO #OpIran:* Em 2022, após a morte de Mahsa Amini, o coletivo Anonymous lançou a #OpIran. Atacaram o Banco Central do Irã, bancos nacionais, uma planta petroquímica offshore e invadiram o banco de dados do parlamento iraniano, vazando dados pessoais de parlamentares. Também atingiram a presidência e a mídia estatal, principalmente via ataques DDoS. 




* **Ameaças Internas:** Funcionários mal-intencionados ou negligentes com acesso legítimo representam um dos vetores mais difíceis de detectar. A ameaça vem de dentro atravessa todas as camadas de defesa perimetral porque tecnicamente tem permissão para estar ali. 



TTPs - TÁTICAS, TÉCNICAS E PROCEDIMENTOS 

Independentemente de quem ataca, a maioria das operações ofensivas segue um padrão dividido em cinco fases: 

| Fase | Descrição |
| --- | --- |
| Reconhecimento | Mapeamento do alvo via OSINT, varredura de portas e identificação de sistemas expostos (SCADA/ICS). A ferramenta Shodan permite localizar sistemas industriais na internet com poucos cliques. |
| Acesso Inicial | Spear-phishing, credenciais comprometidas e exploração de vulnerabilidades em VPNs. Com IA generativa e deepfakes, essa etapa está cada vez mais automatizada e personalizada. |
| Persistência | Backdoors, webshells e contas privilegiadas criadas silenciosamente. O atacante pode permanecer meses na rede sem ser detectado, observando e aguardando o momento certo. |
| Movimento Lateral | Pivô entre redes IT e OT. Escalada de privilégios para alcançar sistemas de controle industrial. Ambientes IT/OT deveriam ser segregados mas raramente estão. |
| Impacto | Ransomware, wipers, sabotagem de PLCs e SCADA. Do dado criptografado ao equipamento fisico danificado - passando por interrupções massivas de serviço. |

As Principais Ameaças em Operação 

| Ameaça | Descrição |
| --- | --- |
| Ransomware | Alto impacto. Criptografa dados e sistemas, exigindo resgate. Pode paralisar operações inteiras por dias ou semanas.  |
| DDoS | Escala massiva. Sobrecarregam serviços até derrubá-los. Usados por hacktivistas e como cortina de fumaça para ataques paralelos mais sofisticados. |
| Roubo de Dados | Espionagem. Extração silenciosa de informações sensíveis, segredos de Estado e propriedade intelectual. O dano pode levar anos para se manifestar. |
| Sabotagem OT/ICS | A ameaça mais crítica. Ataca PLCs e SCADA com potencial de causar danos físicos reais: explosões, apagões e falhas em usinas. |

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

**A LIÇÃO DO CASO COLONIAL** O ataque não causou dano físico direto - foi o próprio operador quem desligou o sistema por precaução. Uma única credencial VPN sem MFA paralisou a cadeia energética de uma região inteira. A ameaça cibernética não precisa quebrar nada para gerar caos: basta forçar o desligamento. 

**Outros Casos Emblemáticos** 

| Caso | Categoria | Impacto |
| --- | --- | --- |
| Stuxnet | Arma cibernética | Primeiro malware a causar dano físico real sabotou centrífugas nucleares iranianas.  |
| Rede Elétrica Ucraniana | Sabotagem OT | Apagão deliberado por ataque coordenado marco da guerra cibernética Rússia x Ucrânia.  |
| Oldsmar, EUA | Saúde Pública | Invasor tentou aumentar drasticamente o nível de soda cáustica na água potável de uma cidade.  |

BRASIL E AMÉRICA LATINA NO RADAR 

O Brasil não é apenas observador desse cenário é um dos principais alvos: 

* 356 bilhões de tentativas de ataques cibernéticos contra o Brasil em 2024 (FortiGuard Labs). 
* 38,73% de todas as atividades maliciosas da América Latina têm o Brasil como alvo o maior da região. 
* +95% de aumento nos ciberataques contra organizações brasileiras no 3º trimestre de 2024 (Check Point). 
* Indústrias brasileiras em alerta crescente para ataques a sistemas OT, com risco direto a operações físicas. 

**Cabos Submarinos - Vulnerabilidade Estratégica** Entre 16 e 17 cabos submarinos chegam à costa brasileira, sustentando praticamente toda a conectividade internacional do país e, portanto, grande parte da nossa economia digital. O tema é tão extenso e crítico que, sozinho, renderia uma palestra inteira. 

**Política Nacional de Segurança de Infraestruturas Críticas** O Brasil já possui um arcabouço legal estruturado sobre o tema: 

* Decreto 9.573/2018 institui a Política Nacional de Segurança de Infraestruturas Críticas. 
* Decreto 10.569/2020 regulamenta a estrutura e os mecanismos de proteção. 
* Decreto 11.200/2022 aprova o Plano Nacional de Segurança de Infraestruturas Críticas (Plansic). 

**O DIAGNÓSTICO** 
As políticas públicas brasileiras já são bem formalizadas. O que falta é investimento real e prática para colocá-las em execução.  Existe lei falta operação. Existe diretriz falta orçamento. Existe consciência no papel falta consciência nos boards. 

O CAMINHO PARA A RESILIÊNCIA 

Não existe defesa absoluta no ciberespaço, mas existe um caminho concreto rumo à resiliência. Cinco pilares sustentam essa jornada: 

1. **Responsabilidade**: cada ator (público, privado e cidadão) deve assumir seu papel na proteção do ecossistema digital. 
2. **Gestão de Risco**: identificar, avaliar e mitigar ameaças de forma contínua, com base em dados e inteligência. 
3. **Educação e Conscientização**: o fator humano é, simultaneamente, o elo mais fraco e a primeira linha de defesa. 
4. **Cooperação Internacional**: ameaças globais exigem respostas coordenadas entre países, agências e empresas. 
5. **Resposta Inteligente**: capacidade de detecção, reação e recuperação rápida, baseada em planos testados e automação. 

O GAP DE TALENTOS 

Estima-se um déficit de cerca de 400 mil profissionais de cibersegurança apenas no Brasil. Sem gente capacitada, não há política que se sustente, não há tecnologia que se opere e não há defesa que se mantenha. 

CONSIDERAÇÕES FINAIS 

A cibersegurança deixou de ser um assunto técnico restrito ao departamento de TI. Tornou-se uma questão de Estado, de soberania, de saúde pública e de continuidade da vida em sociedade. Quando um hospital perde acesso aos prontuários, uma família perde acesso a remédios.  Quando um banco trava, milhões perdem acesso ao próprio dinheiro. Quando um duto para, uma região inteira entra em pânico. Não se trata de prever todos os ataques isso é impossível. Trata-se de construir uma sociedade capaz de absorver impactos, responder rápido e voltar a operar.  Resiliência não é a ausência de crise; é a capacidade de atravessá-la sem colapsar. 

> "Proteger infraestrutura crítica é proteger a vida cotidiana, a nossa sociedade e a soberania nacional." 
> 
> 

---

CONTINUIDADE DE NEGÓCIOS 

**MUITO ALÉM DA TECNOLOGIA** Como organizações sobrevivem a desastres cibernéticos e naturais *William Bianchi Tavares - CTO - NGXit* 

INTRODUÇÃO 

A palestra de William Bianchi Tavares, CTO da NGXit, trouxe uma perspectiva fundamental: a continuidade de negócios vai muito além da tecnologia. Usando como estudo de caso real as enchentes do Rio Grande do Sul, o palestrante mostrou como um desastre seja natural ou cibernético pode colapsar simultaneamente todos os pilares que sustentam uma organização. A mensagem central é clara: não basta ter um plano de TI. É preciso pensar em pessoas, processos, finanças, clientes e cadeia de suprimentos tudo ao mesmo tempo, antes que o desastre aconteça. 

O QUE É CONTINUIDADE DE NEGÓCIOS? 

> "Capacidade da organização de continuar a entrega de produtos ou serviços em um nível aceitável, previamente definido, após incidentes de interrupção." - Definição de Continuidade de Negócios 
> 
> 

Três palavras-chave nessa definição merecem atenção especial: 

* **Continuar**: não se trata de evitar o incidente, mas de manter a operação mesmo durante e após ele. 
* **Nível aceitável**: o objetivo não é operar a 100%, mas a um patamar mínimo que preserve clientes, receita e reputação. 
* **Previamente definido**: o plano precisa existir antes do desastre. Improvisar no meio do caos é tarde demais. 

**CIBERNÉTICO OU NATURAL - O IMPACTO É O MESMO** As enchentes do Rio Grande do Sul mostraram que um desastre natural pode causar exatamente os mesmos colapsos que um ataque cibernético sofisticado: sistemas offline, equipes impossibilitadas de trabalhar, fornecedores inacessíveis, clientes sem atendimento e fluxo de caixa comprometido. A origem do incidente muda as consequências organizacionais são as mesmas. 

OS 7 PILARES DA CONTINUIDADE DE NEGÓCIOS 

O slide apresentado na palestra organizou a continuidade de negócios em sete pilares interdependentes. A grande lição é que proteger apenas um deles como a tecnologia de TI não garante a sobrevivência da organização se os demais colapsarem: 

| Pilar | Foco | Perguntas-chave |
| --- | --- | --- |
| 1. Produtos | Linhas de negócio e produtos ofertados. | Quais produtos podem continuar sendo entregues durante o incidente? Quais precisam ser suspensos? Há alternativas ou versões degradadas aceitáveis? |
| 2. Clientes e Receita | Continuidade dos clientes atuais, prospecção e linhas de receita. | Como manter o relacionamento com clientes existentes? A receita será impactada? Por quanto tempo a organização aguenta sem faturar?  |
| 3. Pessoas | Colaboradores e cultura organizacional. | Os colaboradores estão seguros? Conseguem trabalhar remotamente? A cultura de crise existe? Há planos de comunicação interna?  |
| 4. Cadeia de Suprimentos | Insumos, fornecedores e logística. | Os fornecedores críticos também foram afetados? Há fornecedores alternativos? Os insumos essenciais têm estoque de segurança? |
| 5. Estrutura e Facilities | Ambiente para colaboradores, clientes e fornecedores. | O escritório/fábrica está operacional? Há sites alternativos? O acesso físico ao local é possível?  |
| 6. Processos e Tecnologia | Processos de negócio + tecnologias de TI e segurança. | Quais sistemas são críticos? Há backups testados? Os processos manuais de contingência existem e são conhecidos pela equipe? |
| 7. Financeiro e Orçamento | Fluxo de caixa, novos custos e visão orçamentária. | Qual é o custo diário do incidente? A empresa tem reservas para sustentá-lo? Há seguro cibernético ou de desastre?  |

**A INTERDEPENDÊNCIA DOS PILARES** 
Nenhum dos sete pilares funciona de forma isolada. O colapso de um inevitavelmente pressiona os demais criando um efeito cascata que pode transformar um incidente gerenciável em uma crise existencial para a organização: 

| Se isso falha.... | ...isso è afetado |
| --- | --- |
| Pessoas indisponíveis | Processos param, clientes ficam sem atendimento, produtos deixam de ser entregues. |
| Tecnologia offline | Processos precisam de alternativas manuais, cadeia de suprimentos perde visibilidade, receita cai.  |
| Cadeia de suprimentos quebrada | Produtos não podem ser entregues, receita cai, clientes migram para concorrentes.  |
| Caixa comprometido | Fornecedores param de entregar, pessoas podem ser demitidas, estrutura é reduzida.  |
| Estrutura inacessível | Pessoas não conseguem trabalhar, processos físicos param, clientes não são atendidos.  |

**A LIÇÃO DAS ENCHENTES DO RS** As empresas afetadas pelas enchentes do Rio Grande do Sul não perderam apenas os servidores. Perderam funcionários impossibilitados de chegar ao trabalho, fornecedores que também foram atingidos, estruturas físicas inundadas, acesso a insumos cortado e fluxo de caixa comprometido pela queda abrupta de receita. Quem sobreviveu melhor foi quem tinha planos e não apenas planos de TI. 

TIPOS DE INCIDENTES QUE EXIGEM CONTINUIDADE 

O plano de continuidade de negócios deve ser pensado para uma ampla gama de cenários não apenas ataques cibernéticos: 

| Tipo de Incidente | Caracteristicas |
| --- | --- |
| Desastres Naturais | Enchentes, terremotos, furacões, incêndios. Impactam simultaneamente pessoas, estrutura, fornecedores e tecnologia.  |
| Ataques Cibernéticos | Ransomware, DDoS, sabotagem de sistemas. Podem derrubar operações inteiras sem qualquer dano físico.  |
| Falhas de Infraestrutura | Quedas de energia prolongadas, falhas de telecomunicações, interrupção de fornecedores críticos.  |
| Crises de Saúde | Pandemias ou surtos que impossibilitam a presença física de colaboradores e clientes.  |
| Falhas Humanas | Erros operacionais, sabotagem interna, perda de colaboradores-chave sem sucessores treinados.  |
| Crises Reputacionais | Vazamentos de dados, escândalos públicos ou falhas de produto que geram perda massiva de clientes. |

O PLANO DE CONTINUIDADE DE NEGÓCIOS (PCN/BCP) 

Um Plano de Continuidade de Negócios eficaz não é um documento guardado na gaveta é um processo vivo, testado regularmente e conhecido por toda a organização. Seus componentes essenciais são: 

1. **Análise de Impacto nos Negócios (BIA):** identificar quais processos são críticos, qual o impacto financeiro e operacional de cada interrupção e qual é o tempo máximo tolerável de inatividade (RTO/RPO). 

2. **Análise de Riscos:** mapear as ameaças mais prováveis para o contexto da organização (localização geográfica, setor, tamanho, dependências). 

3. **Estratégias de Continuidade:** definir alternativas para cada cenário: sites de backup, fornecedores alternativos, processos manuais de contingência. 

4. **Planos de Resposta:** documentar quem faz o quê, quando e como em cada tipo de incidente. Comunicação interna e externa incluídas. 

5. **Testes e Simulações:** exercitar o plano regularmente. Um plano não testado é apenas um documento não uma capacidade real. 

6. **Revisão e Melhoria Contínua:** atualizar o plano após cada teste, após cada incidente e quando o negócio mudar significativamente. 



**RTO e RPO - CONCEITOS FUNDAMENTAIS** 

* **RTO (Recovery Time Objective):** quanto tempo a organização pode ficar sem um processo crítico antes que o impacto seja inaceitável. 
* **RPO (Recovery Point Objective):** quanto de dado/histórico a organização pode perder ou seja, até quando os backups precisam remontar. 

Esses dois números precisam ser definidos antes do incidente, não durante. 

TECNOLOGIA É MEIO, NÃO FIM 

Um dos pontos centrais da palestra foi desmistificar a ideia de que continuidade de negócios é sinônimo de backup e recuperação de TI. A tecnologia é fundamental mas é apenas um dos sete pilares. 

| Visão Limitada (só TI) | Visão Completa (PCN real) |
| --- | --- |
| Backup dos servidores | Backup dos servidores + processos manuais de contingência |
| Plano de recuperação de dados | Plano para pessoas, processos, fornecedores e comunicação  |
| Sistemas em nuvem | Sistemas + pessoas capacitadas + acordos com fornecedores alternativos  |
| Teste de restore de backup | Simulação completa de crise com todas as áreas envolvidas  |
| Responsabilidade do TI | Responsabilidade da liderança executiva com apoio do TI  |

**CONEXÃO COM A CIBERSEGURANÇA** A continuidade de negócios e a cibersegurança não são disciplinas separadas são faces do mesmo desafio. Um ataque cibernético bem-sucedido é, em última instância, um incidente de continuidade de negócios. 

| Incidente Cibernético | Pilares de Continuidade Afetados |
| --- | --- |
| Ransomware | Sistemas offline por dias ou semanas o pilar Tecnologia colapsa primeiro, arrastando Processos, Produtos e Receita.  |
| Ataque à cadeia de suprimentos | Fornecedor crítico é comprometido o pilar Cadeia de Suprimentos colapsa, impactando Produtos e Clientes.  |
| Vazamento de dados | Clientes perdem confiança o pilar Clientes e Receita é diretamente atingido, com impacto financeiro imediato.  |
| DDoS prolongado | Serviços inacessíveis por horas Clientes migram para concorrentes, Receita cai, Reputação é afetada.  |

**A INTEGRAÇÃO NECESSÁRIA** Times de cibersegurança e times de continuidade de negócios precisam trabalhar juntos não em silos separados. O plano de resposta a incidentes de segurança deve estar integrado ao PCN, com responsabilidades claras, comunicação definida e critérios objetivos para acionar cada protocolo. 

CONSIDERAÇÕES FINAIS 

As enchentes do Rio Grande do Sul e os grandes ataques cibernéticos da última década ensinam a mesma lição: a questão não é se um incidente vai acontecer, mas quando e se a organização estará pronta para atravessá-lo.  Continuidade de negócios não é um projeto de TI. É uma decisão estratégica de liderança. Exige que o board entenda os riscos, que os processos sejam documentados, que as pessoas sejam treinadas e que os planos sejam testados antes que a crise chegue. Organizações que tratam continuidade como burocracia ou como responsabilidade exclusiva da área de tecnologia descobrem, no pior momento possível, que um plano incompleto não é melhor que nenhum plano - é apenas uma falsa sensação de segurança. 

> "Continuidade de negócios é a capacidade de continuar entregando valor mesmo quando tudo ao redor está falhando. É a diferença entre sobreviver e desaparecer." 
> 
> 

---

MERCADO, DESAFIOS E CARREIRA EM SEGURANÇA DA INFORMAÇÃO 

**Panorama, ameaças e o caminho para profissionais de InfoSec** *Guilherme de Moraes - Senior Manager - Fortinet* 

A FORTINET NO BRASIL 

A palestra principal foi conduzida por Guilherme de Moraes, gerente da Fortinet, que abriu apresentando a posição da empresa no mercado nacional: 

| Indicador | Detalhe |
| --- | --- |
| #1 em presença geográfica no Brasil | Presença em todas as regiões do país.  |
| +70% de market share | Maior participação de mercado entre fabricantes de segurança no Brasil.  |
| 300+ funcionários | Operação local com sede em São Paulo e TAC em Uberlândia.  |
| 3.000+ canais parceiros | Maior capilaridade do setor em território nacional.  |
| 13+ parceiros acadêmicos | Investimento em formação de novos profissionais.  |
| Great Place to Work | Reconhecimento pelo 9º ano consecutivo.  |

O QUE É SEGURANÇA DA INFORMAÇÃO? 

> "A segurança da informação, ou InfoSec, inclui as ferramentas e processos para prevenir, detectar e corrigir ataques e ameaças a informações confidenciais, tanto digitais quanto não digitais." - Definição apresentada pela Fortinet 
> 
> 

Ponto-chave: InfoSec não se limita ao mundo digital. Abrange qualquer forma de informação confidencial incluindo documentos físicos, controle de acesso físico e processos organizacionais. A defesa começa muito antes do firewall. 

A IMPORTÂNCIA DA SEGURANÇA CIBERNÉTICA 

Segundo o WEF Global Risks Report 2026, a cyber insegurança aparece entre os 10 maiores riscos globais tanto no curto quanto no longo prazo ao lado de crises climáticas, geopolíticas e sociais. 

| # | Curto Prazo (2 anos) | Longo Prazo (10 anos) |
| --- | --- | --- |
| 1 | Confrontação geoeconômica  | Eventos climáticos extremos |
| 2 | Desinformação e fake news  | Perda de biodiversidade  |
| 3 | Polarização social  | Mudanças críticas nos sistemas terrestres |
| 4 | Eventos climáticos extremos  | Desinformação e fake news  |
| 5 | Conflitos armados entre Estados  | Consequências adversas da IA  |
| 6 | Cyber insegurança  | Escassez de recursos naturais  |
| 7 | Desigualdade  | Desigualdade  |
| 8 | Erosão de direitos humanos  | Cyber insegurança  |
| 9 | Poluição  | Polarização social  |
| 10 | Migração involuntária  | Poluição  |

**INSIGHT** A cibersegurança não é mais um problema de TI é um problema civilizatório, ao lado de mudanças climáticas e conflitos armados. Isso muda completamente a forma como empresas e governos precisam tratar o tema. 

O ECOSSISTEMA DO CRIME CIBERNÉTICO 

O cibercrime funciona hoje como uma indústria estruturada, com papéis bem definidos em três grandes camadas: fornecedores, operadores e facilitadores. 

* **Camada 1: Produtores** 
Quem fabrica as armas digitais. Especialistas em exploits, packers, plataformas e ataques mobile. Desenvolvedores sênior criam o código-fonte original; desenvolvedores júnior copiam, adaptam e distribuem. 


* **Camada 2: Cibercrime Composto** 
Quem opera e distribui em escala. Organizações criminosas centralizam as operações, vendem, licenciam e dão manutenção às ferramentas. Trabalham com afiliados em um modelo similar a franquias operam ransomware e botnets em larga escala, dividindo o lucro com os fornecedores. 


* **Camada 3: Facilitadores de Serviços** A infraestrutura de suporte que viabiliza tudo: 



| Serviço | O que oferece |
| --- | --- |
| Garantia de qualidade | Crypters, scanners e packers para evitar detecção de antivírus.  |
| Hospedagem | Infecções, drop zones e gestão de infraestrutura criminosa.  |
| Aluguel de botnets | Instalações, spam, SEO malicioso e ataques DDoS sob demanda.  |
| Laranjas financeiros | Lavagem de dinheiro e contas a receber.  |
| Consultoria | Suporte especializado para criminosos sem conhecimento técnico.  |

**O QUE ISSO SIGNIFICA** O cibercrime não é mais obra de hackers solitários no porão de casa. É uma cadeia produtiva profissional, com fornecedores, distribuidores, afiliados e até suporte ao cliente. Quem ataca sua empresa hoje pode ser apenas um operador final de uma indústria multinacional do crime. 

O GAP DE PROFISSIONAIS NO BRASIL 

Enquanto o cibercrime se profissionaliza, o lado da defesa enfrenta um déficit gigantesco: 

* 750 mil profissionais são necessários para preencher o gap em Segurança da Informação no Brasil (Fortinet Skills Gap Report 2024 - e crescendo). 

* Quase 90% das empresas brasileiras sofreram uma violação no último ano, atribuída parcialmente à falta de habilidades cibernéticas. 

* 70% das empresas atribuem o aumento dos riscos cibernéticos diretamente à lacuna de competências no mercado. 



**A TENDÊNCIA** Os dados são de 2024 e a tendência só cresce. A superfície de ataque se expande mais rápido do que a formação de profissionais - quanto menos talento qualificado, mais ataques bem-sucedidos. É um ciclo que se retroalimenta. 

INVESTIMENTOS - DE CUSTO A INVESTIMENTO 

Segundo estudo da Brasscom, o Brasil deve investir R$ 104,6 bilhões em cibersegurança até 2028. O país segue como principal alvo de ataques cibernéticos no mundo, apesar do reconhecimento internacional em segurança digital. 

**MUDANÇA DE MENTALIDADE** 
Segurança sempre foi vista como custo. Precisa ser vista como investimento. Empresas que tratam segurança como custo cortam o budget exatamente nas crises quando mais precisam de proteção. Empresas que tratam como investimento constroem resiliência antes do incidente, não depois. 

Três pilares desse investimento, segundo o palestrante: 

* **Treinamento**: capacitar continuamente os profissionais existentes. 

* **Contratação**: atrair talentos num mercado com déficit de 750 mil vagas. 

* **Retenção**: manter os bons profissionais, que são extremamente disputados. 


CASOS REAIS - APRENDENDO COM O PASSADO 

**WannaCry - Maio de 2017** 
Um dos maiores ataques de ransomware da história. Afetou centenas de milhares de computadores em mais de 150 países, paralisando hospitais, bancos, telecomunicações e indústrias. 

**O DETALHE QUE MARCOU A HISTÓRIA** O patch de segurança que corrigia a vulnerabilidade explorada pelo WannaCry já existia 2 meses antes do ataque.  As vítimas simplesmente não tinham aplicado a atualização. Faltou higienização cibernética básica. 

*Por que não atualizam?* O exemplo clássico é o de equipamentos médicos: uma máquina de ultrassom, por exemplo, é projetada e homologada para rodar em um sistema operacional específico. Atualizar o SO pode invalidar a certificação, quebrar a compatibilidade ou exigir um processo regulatório longo e caro então simplesmente não atualizam. Isso cria um universo de dispositivos críticos rodando sistemas desatualizados e vulneráveis não por negligência simples, mas por restrições técnicas, regulatórias e financeiras reais. 

**Lurie Children's Hospital - Caso Recente** Hospital pediátrico americano atacado pelo grupo Rhysida, operando no modelo RaaS (Ransomware as a Service). Primeira vítima do grupo registrada em maio de 2023. Vetores de ataque mais comuns: phishing e credenciais de VPN expostas. 

Linha do tempo do impacto: 

| Data | O que aconteceu |
| --- | --- |
| 31 Jan | Incidente sistemas offline  |
| 15 Fev | Recuperação gradativa - registros médicos ainda indisponíveis  |
| 27 Fev | Relato de 16 hospitais atacados dados ofertados por US$ 3,4 milhões  |
| 15 Mar | Restauração do serviço MyChart (prontuários dos pacientes)  |
| 21 Mai | Sistema disponível 100%  |

**O PESO DO ATAQUE** 
Quase 4 meses para recuperação total. Um hospital infantil ficou sem acesso a registros médicos por semanas, com impacto direto no atendimento de crianças em situação crítica. Dados médicos pediátricos foram ofertados por US$ 3,4 milhões no mercado criminoso. 

RANSOMWARE-AS-A-SERVICE EM 2026 

O mercado de RaaS continua se expandindo rapidamente. Só em 2026 já foram identificados: 

* 13 novos sites/blogs de grupos de ransomware, incluindo: Ransom Hub, HellCat, Argonauts Ransomware, InterLock, Bashe (APT73/Eraleig), Termite, Sarcoma, Nitrogen, Lynx, Ransomcortex e Valencia. 


* 13 novos RaaS notáveis anunciados na Darknet, incluindo: PlayBoy, Rape, Medusa, Wing, BEAST e Cicada 3301. 



**O DESEQUILÍBRIO CRESCENTE** Enquanto o lado do crime se profissionaliza e escala em velocidade industrial com dezenas de novos fornecedores por ano, o lado da defesa enfrenta um déficit de 750 mil profissionais no Brasil. Qualquer criminoso, mesmo sem conhecimento técnico, pode hoje contratar um ataque de ransomware como serviço. 

EVOLUÇÃO DOS VETORES DE ATAQUE 

O Verizon Data Breach Investigations Report (DBIR) 2026 mostra como os ataques têm evoluído nos últimos três anos: 

| Vetor | 2024 | 2025 | 2026 |
| --- | --- | --- | --- |
| System Intrusion | 36%  | 53%  | 61%  |
| Social Engineering | 22%  | 17%  | 17%  |
| Basic Web App Attacks | 9%  | 18%  | 10%  |
| Miscellaneous Errors | 25%  | 12%  | 8%  |
| Privilege Misuse | 8%  | 7% | 3%  |

Tendências que se destacam: 

* **System Intrusion** explodiu de 36% para 61% em dois anos. Invasões diretas e sofisticadas estão dominando o cenário. 

* **Erros operacionais** caíram de 25% para 8%. As empresas estão errando menos no básico, mas ainda sendo invadidas. 

* **Social Engineering** segue estável (~17-22%) phishing e engenharia social continuam vetores persistentes. 

* **Privilege Misuse** caiu mas ameaças internas ainda existem. 

INFOSTEALERS - O MERCADO DE CREDENCIAIS 

1,7 bilhão de registros de stealer logs já foram compartilhados na Darknet. 

**Principais infostealers responsáveis:** 

| Malware | Participação |
| --- | --- |
| Redline | 60%  |
| Vidar | 27%  |
| Racoon | 12%  |

**Tipos de credenciais mais roubadas:** 

| Tipo | % do total |
| --- | --- |
| SSO (Single Sign-On) | 56%  |
| Webmail | 10% |
| GitHub | 9%  |

Juntas, essas três categorias representam 75% de todas as credenciais disponíveis em infecções por stealers. 

**POR QUE SSO É TÃO CRÍTICO** Uma única credencial SSO dá acesso a dezenas de sistemas ao mesmo tempo é a chave-mestra. Roubar um SSO é como roubar o crachá master de uma empresa inteira. Isso explica diretamente o crescimento de System Intrusion no DBIR: não é mais preciso 'invadir' - basta comprar o acesso pronto na darknet. 

RELATÓRIO 2026 - A NOVA NORMALIDADE 

> "86% das organizações registraram ao menos um incidente de segurança nos últimos 12 meses." - Fortinet Cybersecurity Skills Gap Report 2026 
> 
> 

Tradução prática: não é mais questão de se sua empresa será atacada é questão de quando e como você vai responder. Com 86% das organizações atingidas em apenas 12 meses, estar no grupo dos 14% restantes é cada vez mais improvável. 

DESAFIOS EM 2026 - O FATOR IA 

As maiores preocupações das organizações em relação à IA, segundo o relatório da Fortinet 2026: 

| Preocupação | % |
| --- | --- |
| Vazamento de dados e informações confidenciais | 45%  |
| Defesa contra ataques cibernéticos com IA | 44%  |
| Visibilidade de aplicações e workloads de IA | 34%  |
| Vigilância e violações de privacidade | 33%  |
| IA superinteligente e controle | 32%  |
| Regulação e governança | 29%  |
| Questões de copyright e legais | 23%  |

**A FACA DE DOIS GUMES** As duas maiores preocupações estão diretamente conectadas: vazamento de dados (45%) e ataques usando IA (44%). A mesma tecnologia que defende também ataca e as organizações já sabem disso. O desafio de regulação e governança (29%) ainda está subestimado considerando a velocidade de adoção da IA. 

HABILIDADES NECESSÁRIAS PARA O PROFISSIONAL DE INFOSEC 

Além do conhecimento técnico, o palestrante destacou quatro habilidades essenciais todas soft skills: 

| Habilidade | Por que importa |
| --- | --- |
| Solução de problemas | O profissional de SI vive apagando incêndios e resolvendo situações inéditas. Raciocínio lógico e criatividade são indispensáveis.  |
| Perfil analítico | Capacidade de interpretar dados, logs, comportamentos e padrões para identificar ameaças em meio ao ruído.  |
| Comunicação | Traduzir riscos técnicos para a linguagem do negócio e do board. Um dos maiores gaps do setor.  |
| Trabalho em equipe | Segurança não é responsabilidade de uma pessoa ou de um time isolado é colaborativa por natureza.  |

**O QUE O MERCADO QUER** O mercado já tem ferramentas e tecnologia o que falta é o profissional que saiba usá-las, interpretar seus resultados e comunicar isso para quem decide.  Conhecimento técnico se aprende em curso. Soft skills se desenvolvem com tempo, prática e autoconsciência. 

VIÉS COGNITIVO O INIMIGO INVISÍVEL DO ANALISTA 

> "O viés cognitivo é um atalho mental que leva a desvios de racionalidade e lógica. Ele ocorre porque criamos padrões, baseados nas nossas experiências e percepções prévias, que distorcem o nosso julgamento." - Definição apresentada 
> 
> 

Por que isso importa em cibersegurança? O analista de segurança toma decisões críticas sob pressão, com dados incompletos e em alta velocidade. O viés cognitivo é um dos principais motivos pelos quais ataques passam despercebidos: 

* "Esse alerta é falso positivo, sempre é" - viés de confirmação 

* "Nunca fomos atacados por esse vetor" - viés de disponibilidade 

* "Esse fornecedor é confiável, não precisa verificar" - viés de autoridade 

* "O sistema está funcionando, logo está seguro" - viés do status quo 



**A CONEXÃO COM AS SOFT SKILLS** Perfil analítico e solução de problemas só funcionam se o profissional for capaz de reconhecer e questionar seus próprios vieses. Saber que você tem viés já é metade da defesa. A outra metade é construir processos e times que questionem as decisões individuais. 

PAINEL DE DISCUSSÃO - MERCADO E CARREIRA EM SEGURANÇA DA INFORMAÇÃO 

Encerrando o evento, um painel reuniu profissionais do setor para debater o cenário atual e as perspectivas de carreira em segurança da informação, trazendo inclusive uma visão internacional sobre o tema. 

| Painelista | Perfil |
| --- | --- |
| Anderson Farias | Coordenador de Cibersegurança da SATC. Mediador do painel e articulador do CyberSATC 2026.  |
| Guilherme Morais | Senior Manager, Systems Engineering Fortinet. Trouxe a perspectiva do mercado nacional e das tendências globais em segurança da informação. |
| Giuseppe Lamberto (Itália) | Senior IT Executive | CIO | CTO | Strategic Leader with Global Experience. Painelista internacional, Giuseppe contribuiu com sua experiência global em liderança estratégica de TI, oferecendo uma perspectiva europeia sobre os desafios e oportunidades na área de cibersegurança.  |

**VISÃO INTERNACIONAL** A presença de Giuseppe Lamberto, vindo da Itália, enriqueceu o debate com uma perspectiva global mostrando que os desafios de mercado, formação de talentos e maturidade em segurança da informação são questões universais, com nuances regionais importantes. A troca entre o cenário brasileiro e a experiência europeia evidenciou tanto as lacunas a superar quanto os avanços já conquistados pelo Brasil. 

CONSIDERAÇÕES FINAIS 

O mercado de segurança da informação vive uma equação desbalanceada: de um lado, um cibercrime profissionalizado, com estrutura industrial, fornecedores, afiliados e suporte ao cliente gerando 86% de organizações atacadas em 12 meses. Do outro lado, um déficit de 750 mil profissionais no Brasil, empresas tratando segurança como custo e sistemas críticos rodando sem patches básicos. Para o profissional, há uma oportunidade real: um mercado que precisa de gente mas que exige mais do que certificações. Exige perfil analítico, capacidade de comunicação, trabalho em equipe e, sobretudo, consciência dos próprios vieses cognitivos. 

> "Segurança sempre foi vista como custo. Precisa ser vista como investimento." - Guilherme de Moraes - Fortinet 
> 
>
