# Atividade Prática: Demonstração de Vulnerabilidades em Engenharia Social

Como parte da aula sobre engenharia social e phishing para o curso de Engenharia da Computação, esta atividade prática visa ilustrar **hipoteticamente** como um atacante poderia se passar por uma entidade confiável (neste caso, um representante de uma *“universidade gratuita”*) para coletar informações pessoais de pais sobre seus filhos (alunos universitários).

O objetivo é **educacional**: destacar a vulnerabilidade humana ao compartilhar dados sensíveis sem verificação, e discutir como isso poderia ser explorado em cenários maliciosos, como a criação de perfis falsos ou bancos de dados para fins ilícitos (ex.: tráfico humano).

---

## Importante (para o professor e alunos)

* Esta é uma **simulação teórica e ética**. Não realize chamadas reais ou colete dados reais sem consentimento explícito e sob supervisão institucional.
* **Foco na defesa**: após a discussão das perguntas, analise como detectar e prevenir tais abordagens (ex.: verificação de identidade, uso de canais oficiais).

---

## Contexto Hipotético do Ataque

* O impostor liga ou envia e-mail se passando por um *“coordenador de bolsas da Universidade Gratuita Online”*, alegando atualizar cadastros para *“oportunidades educacionais exclusivas”*.
* Utiliza linguagem **amigável, urgente e autoritária** para ganhar confiança (princípios de reciprocidade e autoridade).

### Objetivo simulado

* Coletar dados como:

  * Nome completo
  * Endereço
  * Rotina
  * Contatos
  * Fotos

Essas informações poderiam ser compiladas em um “banco de dados” para exploração maliciosa (ex.: identificação de alvos vulneráveis).

### Demonstração de vulnerabilidade

Mostrar como pais, motivados por “benefícios educacionais”, compartilham informações sem questionar.

---

## Lista de Perguntas Hipotéticas (por Fases)

As perguntas são organizadas para simular uma conversa progressiva:

1. Construção de rapport
2. Coleta básica
3. Aprofundamento
4. Fechamento

Cada pergunta inclui o risco associado para discussão.

---

## Fase de Rapport e Verificação Inicial

**(Construir confiança – 5 a 10 perguntas iniciais)**

* Olá, sou [Nome Falso], coordenador de bolsas da Universidade Gratuita Online. Estamos atualizando nossos cadastros para oferecer cursos gratuitos ao seu filho/a. Posso confirmar o nome completo do aluno para prosseguir?

  * *Risco:* Obter identidade básica para personalização de ataques futuros.

* Qual é o e-mail principal do seu filho/a que usamos para comunicações oficiais?

  * *Risco:* Acesso a contatos digitais para phishing direcionado.

* Poderia me confirmar o número de telefone do aluno para enviarmos atualizações via SMS?

  * *Risco:* Coleta de contatos para vishing ou smishing.

* Qual é a data de nascimento do seu filho/a, para verificarmos elegibilidade para bolsas etárias?

  * *Risco:* Uso em fraudes e criação de perfis falsos.

---

## Fase de Coleta de Dados Pessoais e Rotina

**(Aprofundamento – mapear vulnerabilidades)**

* Onde o seu filho/a reside atualmente? Poderia fornecer o endereço completo?

  * *Risco:* Localização física para monitoramento.

* Qual é a rotina diária do aluno (horários de ida e volta)?

  * *Risco:* Identificação de padrões de movimento.

* Seu filho/a tem redes sociais? Pode compartilhar os perfis?

  * *Risco:* Acesso a fotos e dados públicos para ataques.

* Há alguma condição de saúde ou necessidade especial?

  * *Risco:* Exploração emocional.

* Qual é o CPF ou documento de identidade do aluno?

  * *Risco:* Fraudes financeiras e roubo de identidade.

---

## Fase de Dados Sensíveis e Multimídia

**(Escalada)**

* Poderia enviar uma foto recente do aluno?

  * *Risco:* Uso em deepfakes ou identificação ilícita.

* Seu filho/a viaja com frequência?

  * *Risco:* Mapeamento de mobilidade.

* Nome e contato de amigos ou familiares próximos?

  * *Risco:* Expansão do ataque em cadeia.

* Poderia informar renda familiar ou dados bancários?

  * *Risco:* Fraudes financeiras diretas.

---

## Fase de Fechamento e Pressão

**(Urgência e conclusão)**

* Há mais informações sobre hobbies ou interesses?

  * *Risco:* Pretextos mais convincentes.

* Poderia reenviar um resumo com todos os dados coletados?

  * *Risco:* Consolidação de informações sensíveis.

* Isso é urgente para não perder a vaga gratuita.

  * *Risco:* Uso de escassez para evitar questionamentos.

---

## Debriefing da Atividade (Discussão em Aula)

### Análise de Vulnerabilidades

* Quantos “pais” compartilharam dados sem verificar a identidade?
* Discussão dos princípios de persuasão (ex.: autoridade).

### Medidas de Prevenção

* Verificar contatos via canais oficiais
* Utilizar autenticação multifator
* Identificar sinais de engenharia social (urgência, pedidos incomuns)

### Extensão Técnica

* Propor sistemas de IA para detectar fraudes

  * Ex.: análise de voz
  * padrões de perguntas

### Ética

* Esta simulação é apenas para aprendizado
* Na prática, essas ações são **criminosas** e violam leis de proteção de dados (ex.: LGPD)