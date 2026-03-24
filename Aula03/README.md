### Ciclo de Interação

No contexto da cibersegurança, estes elementos formam um ciclo contínuo:

1. Ameaças exploram ativamente as vulnerabilidades existentes.


2. Vulnerabilidades, quando exploradas, geram riscos significativos.


3. Riscos exigem monitoramento constante de novas ameaças.



### Exemplos e Mitigação

* **Vulnerabilidades comuns**: Softwares desatualizados, senhas fracas, configurações incorretas de firewall e falta de criptografia.


* **Tipos de Ameaças**: Externas (hackers, malware), Internas (erros de funcionários) e Físicas (desastres naturais).


* **Casos Reais**:
* **Ameaça**: Incêndio no datacenter da OVH (2021) e ataque WannaCry (2017).


* **Vulnerabilidade**: Log4j (2021) e roubo de servidores físicos.


* **Risco (Impacto)**: Ataque à Localiza (2023) custou R$ 50 milhões.





---

## 6. Ativos e Controles de Segurança

### Categorias de Ativos

Recursos valiosos que precisam de proteção:

* **Físicos**: Servidores, datacenters e dispositivos móveis.

* **Digitais**: Bancos de dados, sistemas e códigos-fonte.

* **Humanos**: Conhecimento técnico e propriedade intelectual.

* **Intangíveis**: Reputação da marca e segredos comerciais.

### Categorias de Controles

Os controles atuam em diferentes momentos do ciclo de proteção:

* **Preventivos**: Firewalls, autenticação de dois fatores e políticas de senha forte (impedem o ataque).


* **Detectivos**: IDS, monitoramento de logs e antivírus em tempo real (identificam o ataque em curso).


* **Corretivos**: Backups, planos de continuidade e restauração de sistemas (restauram após o ataque).


### Camadas de Proteção

<img width="384" height="232" alt="image" src="https://github.com/user-attachments/assets/2f29b4ac-3b0c-484f-8c78-de96983eac9e" />


1. **Prevenção**: Primeira linha de defesa.


2. **Detecção**: Monitoramento contínuo.


3. **Correção**: Resposta e recuperação.

# Camadas de Proteção

Os controles de segurança formam um sistema integrado de proteção para os ativos organizacionais, atuando em diferentes camadas de defesa.

* **Controles Preventivos:** Atuam como barreiras iniciais contra ameaças. Exemplos incluem firewalls, autenticação 2FA, antivírus e políticas de senha forte.


* **Controles Detectivos:** Monitoramento constante por atividades suspeitas através de IDS/IPS e vigilância.


* **Controles Corretivos:** Garantem a continuidade do negócio por meio de backups, planos de recuperação e procedimentos de restauração.


Esta estrutura em camadas garante uma proteção abrangente e resiliente.

---

# Análise de Risco em Cibersegurança

O processo de análise de risco envolve as seguintes etapas fundamentais:

1. **Identificação de Ativos:** Levantamento e classificação de dados, sistemas, hardware e recursos humanos.


2. **Análise de Vulnerabilidades:** Identificação de fraquezas nos sistemas e processos.


3. **Identificação de Ameaças:** Mapeamento de possíveis ameaças internas e externas.


4. **Avaliação de Impacto:** Determinação das consequências caso uma ameaça explore uma vulnerabilidade.


5. **Tratamento de Riscos:** Implementação de controles para mitigar, transferir, aceitar ou evitar os riscos.


---

# Gestão de Riscos de Segurança da Informação (ISO/IEC 27005)

O documento referencia a norma **ABNT NBR ISO/IEC 27005:2019**, que orienta a gestão de riscos. O processo inclui:

* Definição do contexto.


* Avaliação de riscos (identificação, análise e avaliação).


* Tratamento do risco, com opções de modificação, retenção, ação de evitar ou compartilhamento.


* Aceitação do risco e monitoramento contínuo.



---

# Framework, Guias e Modelos (gov.br)

<img width="652" height="399" alt="image" src="https://github.com/user-attachments/assets/a2323581-d989-4e56-b55a-3f583d9d089b" />


No âmbito do Programa de Privacidade e Segurança da Informação (PPSI) do governo brasileiro, órgãos devem adotar o **Framework de Privacidade e Segurança da Informação**.

* 
**Etapas de Implementação:** Autoavaliação, análise de lacunas e planejamento.


* **Principais Guias:**
* Gerenciamento de Vulnerabilidades.


* Resposta a Incidentes de Segurança.


* Privacidade desde a concepção (Privacy by Design).


* Inventário de Dados Pessoais e RIPD (Relatório de Impacto à Proteção de Dados).





---

# Malware: Tipos e Características

Diferentes tipos de softwares maliciosos e seus comportamentos:

* **Vírus:** Anexam-se a arquivos legítimos e requerem interação humana para propagação.


* **Worms:** Autônomos, propagam-se por redes explorando vulnerabilidades sem necessidade de interação humana.


* **Ransomware:** Criptografa dados e exige resgate, causando grande impacto organizacional.


* **Spyware:** Coleta informações (senhas, hábitos) sem o conhecimento do usuário.



### Ciclo de Propagação

1. **Infecção Inicial:** Via e-mails, downloads ou mídias removíveis.


2. **Estabelecimento:** Instalação e criação de persistência no sistema.


3. **Comunicação:** Conexão com servidores de comando e controle (C&C).


4. **Propagação:** Disseminação para outros sistemas na rede.



---

# Engenharia Social

Técnica de manipulação psicológica para obter dados ou acesso, explorando falhas humanas em vez de técnicas.

### Principais Tipos:

* **Phishing:** E-mails, SMS ou chamadas falsas para obter dados.


* **Pretexting:** Criação de um cenário falso (ex: falso técnico de suporte).


* **Baiting (Isca):** Uso de itens infectados, como pendrives deixados em locais públicos.


* **Tailgating:** Seguir fisicamente alguém autorizado para entrar em áreas restritas.


* **Quid pro quo:** Oferta de um serviço ou benefício em troca de informações ou acesso.



---

# Como se Proteger contra Phishing

O phishing utiliza "iscas" para atrair as vítimas e roubar dados, ocorrendo principalmente via e-mail.

### Dicas para Identificar E-mails Falsos:

1. **Verifique o remetente:** Analise se o endereço de e-mail é legítimo e se o nome corresponde ao endereço.


2. **Conteúdo suspeito:** Fique atento a erros de ortografia, tons de urgência/ameaça e saudações genéricas.


3. **Links e anexos:** Passe o mouse sobre links para ver a URL real antes de clicar e evite anexos inesperados.


4. **Ofertas:** Desconfie de promoções que parecem "boas demais para ser verdade".



---

# Infraestrutura e Defesa

* **Dispositivos Móveis e IoT:** Vulnerabilidades em apps, ataques a redes Wi-Fi (Man-in-the-middle) e exploração de firmware desatualizado.


* **Firewalls e IDS/IPS:** Uso de firewalls de próxima geração (inspeção profunda), sistemas de detecção (IDS) para alertas e de prevenção (IPS) para bloqueio automático.


* **Defesa em Profundidade:** Implementação de camadas física (acesso), rede (VPNs), aplicação (autenticação), dados (criptografia) e humana (treinamento).


### Políticas de Segurança:

Desenvolvimento de políticas de controle de acesso, uso aceitável, resposta a incidentes e backup. A conscientização dos usuários deve ser feita através de treinamentos regulares e simulações de phishing.
