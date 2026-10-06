# 🏥 Estudo de Caso: Ataque de Ransomware à Change Healthcare

<div align="center">
  <a href="https://youtu.be/VylJB4Z8xgo" target="_blank">
    <img src="https://img.youtube.com/vi/VylJB4Z8xgo/maxresdefault.jpg" alt="Assistir ao vídeo: Estudo de Caso - Change Healthcare" width="650px">
  </a>
  <br>
  <sub>▶️ <i>Clique na imagem acima para assistir à apresentação completa no YouTube</i></sub>
</div>

<br>

*▶️ Clique na imagem acima para assistir à apresentação completa no YouTube*

> Trabalho acadêmico desenvolvido para o curso de Cibersegurança — Mulher Digital (Junior Achievement Brasil).
>
> **Apresentação:** Vanessa Carvalho de Oliveira
> **Tema:** Ataque cibernético à Change Healthcare — 2024

🎥 **Vídeo completo da apresentação:** [YouTube](https://youtu.be/VylJB4Z8xgo)

---

## 📌 Introdução

Em **21 de fevereiro de 2024**, a Change Healthcare sofreu um dos ataques de ransomware mais impactantes já registrados no setor de saúde dos Estados Unidos.

O ataque foi associado ao grupo **ALPHV/BlackCat** e provocou uma interrupção significativa nos sistemas utilizados por hospitais, farmácias, consultórios e outros prestadores de serviços de saúde.

Por atuar em uma infraestrutura essencial para o processamento de transações e pagamentos na área da saúde, a indisponibilidade dos sistemas da Change Healthcare acabou provocando impactos muito além da própria organização.

---

## 🏥 Sobre a Change Healthcare

A **Change Healthcare**, pertencente ao grupo **UnitedHealth Group**, atua na área de tecnologia e serviços para o setor de saúde dos Estados Unidos.

A empresa possui um papel importante no processamento de informações relacionadas a:

* 💳 Pagamentos e transações de saúde
* 🧾 Processamento de reivindicações médicas
* 💊 Prescrições e serviços farmacêuticos
* 🏥 Operações de hospitais e prestadores de saúde
* 🔄 Troca de informações entre diferentes participantes do sistema de saúde

Segundo a IBM, a Change Healthcare processava aproximadamente **15 bilhões de transações de saúde por ano**, o que ajuda a dimensionar o impacto provocado pela interrupção de seus serviços.

---

## ⚠️ O Ataque

O incidente envolveu o grupo de ransomware **ALPHV/BlackCat**.

O ataque teve uma característica especialmente preocupante: os invasores conseguiram obter acesso à rede antes da implantação do ransomware.

Segundo informações apresentadas posteriormente pelo CEO da UnitedHealth Group, **Andrew Witty**, os invasores utilizaram credenciais comprometidas para acessar um portal Citrix da Change Healthcare em **12 de fevereiro de 2024**.

Esse portal não utilizava autenticação multifator (**MFA**).

Após obterem acesso, os invasores permaneceram dentro do ambiente antes da implantação do ransomware em **21 de fevereiro de 2024**.

---

## 🔓 Como os invasores conseguiram acesso?

Uma das principais lições desse caso está relacionada ao controle de acesso.

### 🔑 Credenciais comprometidas

Os invasores utilizaram credenciais válidas para acessar remotamente um portal Citrix.

### ⚠️ Ausência de MFA

O portal utilizado para o acesso não possuía autenticação multifator.

Isso significa que a proteção dependia essencialmente das credenciais utilizadas para autenticação.

### 🕵️ Acesso antes da implantação do ransomware

O acesso inicial não resultou imediatamente na criptografia dos sistemas.

Os invasores tiveram tempo para realizar atividades dentro do ambiente antes da implantação do ransomware.

Esse período demonstra a importância de identificar e responder rapidamente a acessos suspeitos.

---

## 🦠 Ransomware ALPHV/BlackCat

O **ALPHV**, também conhecido como **BlackCat**, é uma família/grupo de ransomware conhecido por operações de extorsão e pelo modelo de **Ransomware-as-a-Service (RaaS)**.

O grupo e seus afiliados utilizam diferentes técnicas para obter acesso às redes, realizar movimentação dentro do ambiente, obter dados e posteriormente utilizar ransomware ou extorsão.

De acordo com a CISA, FBI e HHS, afiliados do ALPHV/BlackCat podem realizar atividades como:

* 🔑 Roubo de credenciais
* 🖥️ Acesso remoto
* ↔️ Movimentação lateral
* 📂 Exfiltração de dados
* 🔐 Criptografia de sistemas
* 💰 Extorsão

O alerta conjunto também descreve técnicas e ferramentas associadas às operações do BlackCat.

---

## ⏱️ Linha do Tempo

| Data                   | Evento                                                                                                                         |
| ---------------------- | ------------------------------------------------------------------------------------------------------------------------------ |
| **12/02/2024**         | Credenciais comprometidas são utilizadas para acessar um portal Citrix sem MFA.                                                |
| **21/02/2024**         | O ransomware é implantado nos ambientes da Change Healthcare.                                                                  |
| **21/02/2024**         | A organização isola seus sistemas para tentar conter o incidente.                                                              |
| **Final de fevereiro** | O grupo ALPHV/BlackCat reivindica responsabilidade pelo ataque.                                                                |
| **01/03/2024**         | Uma transação de aproximadamente US$ 22 milhões em Bitcoin é associada ao pagamento do resgate.                                |
| **Março/2024**         | A interrupção dos serviços continua afetando o setor de saúde.                                                                 |
| **22/04/2024**         | A UnitedHealth informa que os dados potencialmente afetados poderiam atingir uma proporção substancial da população americana. |
| **01/05/2024**         | Andrew Witty presta depoimento ao Congresso americano e confirma o pagamento do resgate.                                       |

A IBM relata que o ransomware foi implantado em 21 de fevereiro e que o portal Citrix utilizado no acesso inicial não possuía MFA.

---

## 💰 O Pagamento do Resgate

O ataque também ficou conhecido pelo pagamento de aproximadamente **US$ 22 milhões em Bitcoin**.

Posteriormente, Andrew Witty confirmou perante o Congresso que a organização havia efetuado o pagamento do resgate.

Mesmo após o pagamento, o incidente não foi simplesmente encerrado. Dados relacionados ao ataque continuaram sendo uma preocupação, demonstrando que **pagar o resgate não garante que todos os dados serão recuperados ou que novas tentativas de extorsão não ocorrerão**.

---

## 📊 Impactos do Ataque

O impacto ultrapassou os limites da própria Change Healthcare.

### 🏥 Impacto no setor de saúde

A interrupção afetou:

* Hospitais
* Farmácias
* Consultórios
* Prestadores de serviços de saúde
* Processamento de pagamentos
* Processamento de reivindicações
* Autorizações de procedimentos
* Processamento de prescrições

Uma pesquisa da American Hospital Association mostrou que **74% dos hospitais pesquisados relataram impacto direto no atendimento aos pacientes**, enquanto **94% relataram impacto financeiro**.

### 💵 Impacto financeiro

A UnitedHealth Group informou custos bilionários relacionados ao incidente e disponibilizou bilhões de dólares em apoio financeiro a prestadores afetados.

### 🔐 Exposição de dados

A UnitedHealth informou que sua investigação encontrou arquivos contendo **informações protegidas de saúde (PHI)** e **informações de identificação pessoal (PII)**, com possibilidade de atingir uma proporção substancial da população americana.

---

## 🔐 O que podemos aprender com esse caso?

O ataque à Change Healthcare demonstra que a segurança de uma organização não depende apenas de possuir antivírus ou ferramentas de proteção.

Algumas medidas importantes incluem:

### 🔑 Autenticação multifator

O uso de **MFA** pode adicionar uma camada adicional de proteção mesmo quando uma senha é comprometida.

### 👀 Monitoramento de acessos

É importante monitorar autenticações, principalmente acessos remotos e comportamentos fora do padrão.

### 🗂️ Proteção e recuperação de backups

Backups adequados e processos de recuperação podem reduzir o impacto de ataques de ransomware.

### 🌐 Segmentação de rede

A segmentação pode limitar a capacidade de um invasor se movimentar pelo ambiente.

### 🚨 Resposta a incidentes

Quanto mais rapidamente uma organização identifica e isola uma ameaça, menor pode ser o impacto causado.

---

## 🧠 Principais conceitos envolvidos

```text
Credenciais comprometidas
          ↓
Acesso remoto
          ↓
Ausência de MFA
          ↓
Acesso à rede
          ↓
Movimentação dentro do ambiente
          ↓
Exfiltração de dados
          ↓
Implantação do ransomware
          ↓
Criptografia / interrupção
          ↓
Extorsão
          ↓
Impacto no setor de saúde
```

---

## 📚 Referências

### 🔎 Fontes técnicas e notícias

* [CISA/FBI/HHS — #StopRansomware: ALPHV Blackcat](https://www.cisa.gov/news-events/cybersecurity-advisories/aa23-352a)
* [SC World — ALPHV/BlackCat e o setor de saúde](https://www.scworld.com/news/alphv-blackcat-hits-healthcare-after-retaliation-threat-fbi-says)
* [BleepingComputer — BlackCat e ataques a organizações](https://www.bleepingcomputer.com/news/security/fbi-blackcat-ransomware-breached-at-least-60-entities-worldwide/)
* [TechCrunch — Ataque à Change Healthcare](https://techcrunch.com/2024/02/29/unitedhealth-change-healthcare-ransomware-alphv-blackcat-pharmacy-outages/)
* [UnitedHealth Group — Atualização sobre o ataque](https://www.unitedhealthgroup.com/newsroom/2024/2024-04-22-uhg-updates-on-change-healthcare-cyberattack.html)
* [Optum — Status dos serviços da Change Healthcare](https://solution-status.optum.com/incidents/hqpjz25fn3n7)
* [IBM — Pagamento de US$ 22 milhões](https://www.ibm.com/br-pt/think/news/change-healthcare-22-million-ransomware-payment)
* [IBM — Impactos financeiros do ataque](https://www.ibm.com/think/news/change-healthcare-cyberattack-exceeds-1-billion-costs)
* [HIPAA Journal — Estatísticas de violações de dados na área da saúde](https://www.hipaajournal.com/healthcare-data-breach-statistics/)
* [Hyperproof — Análise do incidente](https://hyperproof.io/resource/understanding-the-change-healthcare-breach/)

### 🎥 Vídeos utilizados na pesquisa/apresentação

* [Apresentação do trabalho — YouTube](https://youtu.be/VylJB4Z8xgo)
* [Vídeo de referência — YouTube](https://www.youtube.com/watch?v=brpTl7gdCqA)
* [Vídeo de referência — YouTube](https://www.youtube.com/watch?v=vjQAcWy1_dQ)

---

## 💡 Conclusão

O caso da Change Healthcare demonstra como um único ponto de acesso comprometido pode gerar consequências em grande escala quando a organização está conectada a uma infraestrutura crítica.

Além do impacto tecnológico, o incidente afetou operações financeiras, prestadores de saúde, farmácias e pacientes.

Para quem está começando na área de Cibersegurança, esse caso mostra a importância de compreender não apenas o funcionamento de um malware, mas também conceitos como **autenticação, controle de acesso, monitoramento, resposta a incidentes, proteção de dados e continuidade de negócios**.

> 🛡️ Segurança da informação não é apenas impedir um ataque. É também estar preparado para detectar, responder e recuperar-se quando ele acontece.

---

*Projeto educacional desenvolvido para fins de estudo e conscientização em Cibersegurança.*

