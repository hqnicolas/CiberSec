# Tipos de Ataques de Cibersegurança
Uma exploração técnica e detalhada dos mecanismos, vetores e contramedidas dos ataques cibernéticos mais sofisticados da atualidade.

---

## 1. Introdução aos Ataques Cibernéticos
Um ataque cibernético consiste na exploração sistemática de vulnerabilidades para comprometer a tríade **CIA**: **Confidencialidade**, **Integridade** e **Disponibilidade**.

* **Impacto Económico**: Prevê-se que o custo global atinja **US$ 10,5 triliões** anualmente até 2025.
* **Abordagem Proativa**: Engenheiros devem compreender os mecanismos internos para projetar sistemas seguros desde a conceção.

---

## 2. Ransomware: Sequestro Digital
O ransomware utiliza algoritmos de criptografia robustos (como AES-256 e RSA-2048/4096) para tornar os dados inacessíveis, exigindo resgate em criptomoedas.

* **Dupla Extorsão**: Além de encriptar, os atacantes exfiltram os dados e ameaçam publicá-los.
* **Exemplos**:
    * **WannaCry (2017)**: Explorou a vulnerabilidade *EternalBlue*, infetando 200.000 computadores.
    * **Colonial Pipeline (2021)**: Paralisou o abastecimento de combustível nos EUA; resgate de US$ 4,4 milhões.
* **Prevenção**: Backups offline (regra 3-2-1), microsegmentação *Zero-Trust* e detecção comportamental por IA.

---

## 3. Malware: Variedades e Atuação
O malware engloba diversas categorias de software malicioso:

| Tipo | Descrição | Exemplo |
| :--- | :--- | :--- |
| **Trojans** | Disfarçam-se de software legítimo. | Emotet |
| **Worms** | Auto-replicam-se em redes sem interação humana. | NotPetya |
| **Spyware** | Coleta dados furtivamente (mensagens, câmeras). | Pegasus |
| **Cryptominers** | Sequestram recursos (CPU/GPU) para minerar cripto. | Coinhive |
| **Backdoors** | Pontos de entrada ocultos para acesso remoto. | - |
| **Keyloggers** | Registram todas as teclas digitadas pelo usuário. | - |

---

## 4. Ataques de Rede e Aplicações Web

### Negação de Serviço (DoS e DDoS)
Visa tornar recursos indisponíveis por saturação. O **DDoS** utiliza botnets (milhares de dispositivos infetados).
* **Exemplo**: Ataque recorde de 2,3 Tbps contra a AWS em 2020.

### Man-in-the-Middle (MitM)
O atacante interceta a comunicação entre duas partes.
* **Técnicas**: ARP Spoofing, DNS Spoofing e Rogue Access Points.

### Injeção de SQL (SQLi)
Explora a falta de validação em campos de entrada para manipular consultas à base de dados.
* **Prevenção**: Uso de *Prepared Statements* e consultas parametrizadas.

### Cross-Site Scripting (XSS)
Injeção de scripts maliciosos em páginas web para execução no navegador da vítima.
* **Tipos**: Refletido, Armazenado e Baseado em DOM.

---

## 5. Sofisticação e Novas Fronteiras

* **Explorações de Dia Zero (Zero-Day)**: Ataques que exploram falhas desconhecidas pelos fabricantes.
* **Ataques à Cadeia de Suprimentos**: Comprometimento de software/hardware durante a produção ou distribuição (Ex: Caso **SolarWinds**).
* **Vulnerabilidades em IoT**: Dispositivos com firmware desatualizado ou credenciais padrão (Ex: Botnet **Mirai**).
* **Ameaças Internas (*Insiders*)**: Riscos causados por funcionários maliciosos ou negligentes (Ex: Casos na **Tesla** e **Capital One**).

---

## 6. Anatomia Técnica de um Ataque (Cyber Kill Chain)
1. **Reconhecimento**: Coleta de informações (OSINT, Nmap).
2. **Armamento**: Criação de payloads e exploits.
3. **Entrega**: Envio via phishing, USB ou web.
4. **Exploração**: Execução do código malicioso.
5. **Instalação**: Estabelecimento de persistência (Rootkits, DLL hijacking).
6. **Comando e Controle (C2)**: Comunicação externa com o atacante.
7. **Movimentação Lateral**: Expansão do acesso dentro da rede.
8. **Ações nos Objetivos**: Exfiltração, sabotagem ou criptografia.
