
# 📊 Análise de Desempenho de Agente de Customer Support

Esse README contém o prompt utilizado para análise de dados de um agente de suporte e a análise resultante realizada por uma inteligência artifical, atuando como um cientista de dados.

---

## 📝 O Prompt

> **#Persona**
> Você é um cientista de dados e foi contratado por uma empresa para analisar os dados de um agente que trabalhou como customer support.

> **#contexto**
> Sendo esta uma confirmação empírica, a maioria dos contatos era para solicitação de reembolso, suporte técnico ou renovação, respectivamente.
>
> O público que mais contatou o agente eram pessoas idosas - A ressalvar que se trata de mais uma análise empírica, sem dados concretos.
>
> É uma empresa do ramo de tecnologia com assinaturas com renovação automática.
>
> O agente trabalhou por um período de um ano e oito meses e no total recebeu 858 avaliações de clientes.

> **#Dados**
> * Resolution rate: 90%
> * First call resolution: 86%
> * NPS: 73.9%
> * Agent Net Sat: 88.8% (avaliação do cliente referente ao atendimento do agente)
> * NetSat: 82.1%

> **#conclusão**
> A análise precisará possuir diferentes perspectivas, pois gestor e ex agente analisarão o seu relatório.
>
> Analise as métricas de maneira isolada, de maneira comparada e de uma maneira geral.
>
> Considere como o contexto informado de maneira empírica pode influenciar as métricas e explique as possíveis falhas por não possuir um dado concreto.
>
> Portanto, verifique se é possível retirar insights sobre business outcomes a partir dos dados desse agente.
>
> Por fim, sugira ações práticas para que o agente melhore seu desempenho de maneira geral e especificamente em cada métrica.
>
> Crie cinco possíveis perguntas relevantes que o gestor poderia fazer no qual podem ser respondidas com as informações apresentadas e responda-as.
>
> Estruture seu texto em pequenos parágrafos de até 150 carácteres e garanta informação precisa antes de continuar para a próxima etapa.
>
> A cada parte, adicione uma nota, representada com # explicando a sua análise e raciocínio.

---

## 🧑‍🔬📊 A Análise do Cientista de Dados

**Para:** Gestor e Ex-Agente
**De:** Cientista de Dados
**Assunto:** Análise de performance (Agente X, Período Y)

### Introdução

Analisamos 858 avaliações de 20 meses de trabalho do agente. Os dados mostram alta performance, especialmente em satisfação e resolução de problemas.

Consideramos o contexto empírico (tipos de chamada, público idoso, auto-renovação). Sua natureza não confirmada por dados limita certas conclusões.

> **# Nota:** A introdução estabelece o escopo, a base de dados, uma visão geral do desempenho e as ressalvas sobre o contexto empírico.

### Análise Isolada das Métricas

* **Resolution Rate (90%):** Muito forte. Indica que o agente foi altamente eficaz em encontrar soluções para os problemas dos clientes.

* **First call resolution (FCR - 86%):** Excelente. Mostra eficiência, resolvendo a vasta maioria das questões já no primeiro contato.

* **NPS (73.9):** Excepcional. Este nível sugere um forte impacto positivo na lealdade, criando promotores da marca.

* **Agent Net Sat (88.8%):** Altíssimo. Demonstra que os clientes ficaram muito satisfeitos com a conduta e atendimento pessoal do agente.

* **NetSat (82.1%):** Bom resultado. Reflete a satisfação geral com a interação, incluindo processo e política, além do agente.

> **# Nota:** Analisamos cada métrica individualmente, interpretando seu valor absoluto como indicador de desempenho em diferentes facetas do atendimento.

### Análise Comparada das Métricas

A pequena diferença (4%) entre **Resolution Rate** e **FCR** sugere que poucos casos, talvez os mais complexos, precisaram de mais de um passo ou contato.

A diferença maior (6.7%) entre **Agent Net Sat** e **NetSat** é significativa. Sugere que fatores externos ao agente limitam a satisfação total.

Políticas da empresa, limitações do produto ou complexidade do processo podem ser esses fatores externos que reduzem o **NetSat**.

O alinhamento do alto **NPS** com o **Agent Net Sat** reforça que a performance *pessoal* do agente gera uma percepção muito positiva da marca.

> **# Nota:** Comparamos métricas relacionadas (Resolução vs FCR, Agent Sat vs NetSat) para extrair insights sobre eficiência e o impacto de fatores sistêmicos.

### Análise Geral e Contexto Empírico

O desempenho geral é consistentemente alto, considerando o volume e período. O agente possui habilidades interpessoais e de resolução notáveis.

O contexto empírico (idosos, tecnologia, auto-renovação, tipos de chamada) pode influenciar as métricas, especialmente **FCR** e **NetSat**.

Idosos podem precisar de mais suporte técnico. Políticas de reembolso/renovação podem gerar atrito, afetando o **NetSat** apesar do bom agente.

> **# Nota:** Sintetizamos a performance geral e levantamos hipóteses sobre como o contexto empírico (não confirmado) poderia explicar algumas nuances nos dados.

### Falhas por Falta de Dados Concretos ⚠️

Sem dados demográficos confirmados ou segmentação por tipo de chamada, não podemos *provar* o impacto do público idoso ou dos tipos de contato.

A análise é uma "fotografia" média do período. Não temos dados para ver tendências, sazonalidade ou evolução do agente ao longo dos 20 meses.

> **# Nota:** Explicitamos as limitações da análise devido à natureza empírica do contexto e à falta de granularidade temporal ou por tipo de contato nos dados.

### Insights sobre Business Outcomes (Inferencial) 💡

O **NPS** altíssimo sugere forte contribuição para a reputação da marca e retenção de clientes atendidos por este agente (marketing boca-a-boca).

Altas taxas de resolução (90%) e **FCR** (86%) impactam positivamente a retenção e reduzem custos operacionais (menos contatos repetidos).

A diferença **Agent Sat**/**NetSat** indica oportunidade de melhoria em processos/políticas para elevar a satisfação *geral*, alavancando o bom desempenho dos agentes.

> **# Nota:** Inferimos possíveis impactos no negócio (lealdade, retenção, custo, reputação) com base nas métricas de desempenho do agente, apesar da falta de dados financeiros diretos.

### Sugestões de Ações de Melhoria (Ex-Agente) ✨

* **Geral:** Manter a excelência interpessoal. Documentar e compartilhar abordagens que funcionam bem, especialmente em casos difíceis.

* **FCR:** Analisar os tipos de caso que exigiram mais de um contato. Buscar aprofundar conhecimento técnico ou sobre processos para agilizar esses casos.

* **NetSat:** Focar em gerenciar expectativas e explicar claramente políticas ou limitações, mesmo mantendo a empatia, para reduzir frustrações.

* **NPS/Agent Sat:** Continuar aplicando as habilidades que geram essas notas altas, como escuta ativa, personalização e resolução eficaz.

> **# Nota:** Propusemos ações práticas e direcionadas para o agente, focadas em manter pontos fortes e otimizar áreas com pequena margem de melhoria (FCR, NetSat gap).

### Perguntas e Respostas para o Gestor ❓

1.  *Qual o impacto deste agente na lealdade do cliente, com base no NPS?*
    **R:** O impacto é excepcional (**NPS 73.9**). Ele transforma a maioria dos clientes atendidos em promotores da marca, fortalecendo a lealdade.

2.  *O que a diferença entre a satisfação com o agente e a satisfação geral sugere sobre nossos processos ou políticas?*
    **R:** Sugere que nossos processos, políticas ou talvez limitações do produto/serviço podem estar limitando a satisfação geral, apesar do ótimo agente.

3.  *Devemos nos preocupar com a diferença entre a Taxa de Resolução e o FCR deste agente?*
    **R:** Não é alarmante (apenas 4% de diferença), mas indica uma pequena oportunidade para melhorar a eficiência na resolução de casos mais complexos no 1º contato.

4.  *Quão consistente parece ter sido o alto desempenho deste agente, considerando o volume e período?*
    **R:** As médias altas sobre 858 avaliações em 20 meses sugerem um desempenho consistentemente elevado, não um resultado pontual.

5.  *Quais qualidades deste agente, indicadas pelas métricas, deveríamos valorizar ou buscar em outros membros da equipe?*
    **R:** Habilidade de resolução (90%), eficiência (**FCR** 86%), forte capacidade interpessoal (**Agent Sat** 88.8%) e impacto na lealdade (**NPS** 73.9).

> **# Nota:** Respondemos às perguntas relevantes do gestor usando estritamente os dados e inferências da análise, fornecendo uma avaliação concisa da performance e seus indicativos.

