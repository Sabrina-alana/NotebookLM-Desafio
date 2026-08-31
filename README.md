# 📘 Manual de Preparação para a Certificação Microsoft Certified: Azure Fundamentals (AZ-900)

Este repositório foi criado para servir como um guia completo, prático e estruturado para quem deseja obter a certificação **Microsoft Azure Fundamentals (AZ-900)**. Aqui você encontrará os objetivos oficiais do exame, um cronograma de estudos de 7 dias, fontes gratuitas recomendadas e testes de prompts para otimizar seus estudos utilizando Inteligência Artificial.

---

## 🎯 1. Objetivos do Exame (Habilidades Medidas)

O exame **AZ-900** é voltado para profissionais de tecnologia que desejam demonstrar conhecimento básico sobre os conceitos de nuvem em geral e do Microsoft Azure em particular [164]. É a porta de entrada ideal para quem está iniciando sua jornada na nuvem da Microsoft [62, 164].

As habilidades medidas na prova estão divididas em três domínios principais [165]:

### A. Descrever Conceitos de Nuvem (25% a 30%) [165]
*   **Computação em Nuvem:** Definição prática e o modelo de responsabilidade compartilhada entre o provedor e o cliente [113, 166].
*   **Modelos de Nuvem:** Diferenças e casos de uso de nuvem pública, privada e híbrida [166].
*   **Modelo Baseado em Consumo:** Entendimento de modelos de preços e comparação entre Capex (despesas de capital únicas) e Opex (despesas operacionais recorrentes) [108, 109, 166].
*   **Benefícios da Nuvem:** Definição de Alta Disponibilidade, Escalabilidade (vertical e horizontal), Elasticidade (capacidade de contrair e expandir sob demanda), Confiabilidade, Previsibilidade, Segurança e Governança [144, 166, 167].
*   **Tipos de Serviço:** Diferenças cruciais e casos de uso de **IaaS** (Infraestrutura como Serviço), **PaaS** (Plataforma como Serviço) e **SaaS** (Software como Serviço) [167].

### B. Descrever a Arquitetura e os Serviços do Azure (35% a 40%) [165]
*   **Componentes Arquitetônicos:** Datacenters, Regiões do Azure, pares de regiões, regiões soberanas e Zonas de Disponibilidade (datacenters isolados para resiliência física) [168].
*   **Estrutura de Gerenciamento:** Recursos, Grupos de Recursos, Assinaturas (Subscriptions) e Grupos de Gerenciamento (hierarquia completa de controle) [168].
*   **Serviços de Computação e Rede:**
    *   Máquinas Virtuais (VMs), Conjuntos de Dimensionamento (Scale Sets) e Área de Trabalho Virtual (Azure Virtual Desktop) [169].
    *   Hospedagem de contêineres: instâncias de contêiner (ACI) e o Serviço de Kubernetes do Azure (AKS) [21, 168, 169].
    *   Computação Serverless (sem servidor), como Azure Functions [19, 166, 168].
    *   Estrutura de Redes: Redes Virtuais (VNet), sub-redes, emparelhamento (peering), Gateway de VPN, ExpressRoute (conexão privada dedicada) e endpoints públicos/privados [18, 169].
*   **Serviços de Armazenamento:**
    *   Contas de armazenamento, Azure Blob Storage (armazenamento de dados não estruturados) e seus níveis de acesso (quente/hot, frio/cool, arquivo/archive) [9, 106, 170].
    *   Ferramentas de migração e movimentação: AzCopy, Gerenciador de Armazenamento (Storage Explorer) e Sincronização de Arquivos do Azure [13, 39, 170].
    *   Migrações em grande escala: Azure Migrate e Azure Data Box [13, 24, 170].
*   **Serviços de Identidade e Segurança:**
    *   Serviços de diretório: Microsoft Entra ID (antigo Azure AD) e Microsoft Entra Domain Services [36, 170].
    *   Segurança de acesso: Logon Único (SSO), Autenticação Multifator (MFA) e Acesso Condicional [171].
    *   Modelos conceituais: Confiança Zero (Zero Trust) e o modelo de defesa em profundidade [171].
    *   Central de Segurança: Microsoft Defender para Nuvem [35, 171].

### C. Descrever o Gerenciamento e a Governança do Azure (30% a 35%) [165]
*   **Gerenciamento de Custos:** Fatores de precificação, Calculadora de Preços e o uso estratégico de etiquetas (Tags) para organização de despesas corporativas [171, 172].
*   **Governança e Conformidade:** Funcionalidades do Microsoft Purview para controle de dados, Azure Policy para aplicar regras de negócios e bloqueios de recursos (locks) para evitar exclusões acidentais [37, 172].
*   **Gerenciamento e Implantação:** Portal do Azure, Azure Cloud Shell, CLI do Azure, Azure PowerShell, Azure Arc e modelos de Infraestrutura como Código (modelos ARM) [10, 53, 172].
*   **Ferramentas de Monitoramento:** Diagnóstico rápido com Azure Advisor (recomendações personalizadas), Azure Service Health (avisos sobre interrupções de serviço) e o ecossistema Azure Monitor (Log Analytics, alertas e Application Insights) [7, 24, 27, 173].

---

## 📚 2. Fontes e Materiais Gratuitos de Estudo

Para conquistar a sua aprovação sem a necessidade de investir em treinamentos pagos [177, 180], utilize as seguintes fontes oficiais e comunitárias de alta qualidade:

1.  **Microsoft Learn (Oficial):**
    *   [Roteiro de Aprendizagem Oficial da AZ-900](https://learn.microsoft.com/pt-br/credentials/certifications/exams/az-900#two-ways-to-prepare) [174]: Módulos interativos e laboratórios práticos e gratuitos que cobrem 100% da matéria da prova [177].
    *   [Simulado Simulador Oficial Gratuito (Practice Assessment)](https://learn.microsoft.com/pt-br/credentials/certifications/exams/az-900/practice/assessment?assessment-type=practice&assessmentId=23) [162]: Teste oficial da Microsoft para validar o seu nível antes de agendar o exame [162].
2.  **Canais Recomendados no YouTube:**
    *   **Raphael Andrade (Guia para Iniciantes):** Conteúdo com mais de 12 horas teóricas e práticas focadas em hands-on de VMs, Redes Virtuais e Storage [178, 179, 180].
    *   **Gabriel, O Programador:** Vídeos com roteiro acelerado de estudos e dicas do ambiente real do exame [62, 70].
    *   **Canal dotNET (Masterclasses de Cloud):** Lives dinâmicas explicando os conceitos essenciais aplicados a cenários do cotidiano corporativo [74].
3.  **Bancos de Questões e Revisão:**
    *   **Exam Topics:** Plataforma comunitária com questões reais do exame AZ-900 para praticar simulados [67]. (Dica: utilize a ferramenta de tradução do navegador se preferir estudar em português [69]).
    *   **Anki Flashcards:** Baralhos prontos para memorização espaçada dos conceitos fundamentais [67, 69].

---

## 📅 3. Miniguia de Estudos: Desafio dos 7 Dias

Com disciplina de **30 a 60 minutos diários** [71], você consegue se preparar e ser aprovado no exame [72]. Siga este cronograma estratégico passo a passo [62]:

```
┌────────────────────────────────────────────────────────┐
│                   CRONOGRAMA AZ-900                    │
├───────┬────────────────────────────────────────────────┤
│ Dia 0 │ Agendamento da Prova e Organização de Materiais│
│ Dia 1 │ Módulos do Microsoft Learn: Conceitos de Nuvem │
│ Dia 2 │ Módulos do Learn: Arquitetura e Computação     │
│ Dia 3 │ Módulos do Learn: Segurança e Identidade       │
│ Dia 4 │ Módulos do Learn: Governança e Custos          │
│ Dia 5 │ Simulados no Exam Topics e Flashcards          │
│ Dia 6 │ Revisão de Erros nos Simulados e Fixação       │
│ Dia 7 │ Dia da Prova: Revisão Rápida e Aprovação!      │
└───────┴────────────────────────────────────────────────┘
```

### Detalhamento do Plano de Ação:

*   **Dia 0: Preparação e Agendamento**
    *   Acesse o portal do Microsoft Learn e agende sua prova via Pearson VUE [64, 94].
    *   **Super Dica de Desconto:** Inscreva-se nos eventos oficiais gratuitos chamados *Microsoft Virtual Training Days*. Ao assistir ao treinamento completo, você garante **50% de desconto** na taxa de agendamento do exame [90].
    *   Organize e baixe o aplicativo ANKI ou selecione a sua playlist de revisão no YouTube [69, 70].
*   **Dia 1: Dominando os Conceitos de Nuvem (25% a 30% da prova)**
    *   Estude as diferenças de Capex vs. Opex [108, 109], modelos (Pública, Privada e Híbrida) [166] e serviços (IaaS, PaaS, SaaS) [167].
    *   Pratique 10 flashcards rápidos sobre esses conceitos [71].
*   **Dia 2: Entendendo a Arquitetura e Computação no Azure**
    *   Aprenda sobre Regiões, Zonas de Disponibilidade [168], VMs [169], Redes Virtuais (VNets) e Sub-redes [169].
    *   Assista a uma videoaula hands-on para fixar como criar uma Máquina Virtual no Portal do Azure [179].
*   **Dia 3: Identidade, Segurança e Confiança Zero**
    *   Foque no funcionamento do Microsoft Entra ID [170], MFA, Acesso Condicional [171] e no modelo de Defesa em Profundidade [171].
*   **Dia 4: Governança, Monitoramento e Gerenciamento de Custos**
    *   Estude ferramentas cruciais como Calculadora de Preços, Tags [172], Azure Policy [172], Azure Monitor e Azure Advisor [173].
*   **Dia 5: O Poder dos Simulados**
    *   Faça o primeiro bloco de questões simuladas no *Exam Topics* ou no *Practice Assessment* oficial da Microsoft [67, 162].
    *   Anote os conceitos que você errou para revisar no dia seguinte [67].
*   **Dia 6: Ajuste de Pontos Fracos**
    *   Refaça as questões erradas e use os flashcards no ANKI para memorizar siglas difíceis [67, 69].
*   **Dia 7: O Grande Dia!**
    *   Faça uma revisão super leve e rápida pela manhã [71].
    *   **Dica sobre o local de exame:** Se puder, escolha realizar a prova em um **centro de testes presencial** credenciado pela Pearson VUE [63, 94]. No formato online em casa, qualquer queda de internet ou interrupção por barulho externo de terceiros pode causar o cancelamento automático e imediato da sua prova, perdendo a taxa de inscrição [63, 95].
    *   O exame possui tipicamente entre **30 a 50 questões** com tempo máximo de até **45 minutos** [64, 71]. Para ser aprovado, você precisa de uma pontuação igual ou superior a **700 de 1000 pontos** [64, 162].

---

## 🤖 4. Testes de Prompts para Estudo com IA

Copie e cole estes prompts em sua ferramenta de Inteligência Artificial para acelerar sua memorização e esclarecer dúvidas complexas:

### Prompt 1: O Método das Analogias do Cotidiano
> *"Aja como um arquiteto especialista em Microsoft Azure e instrutor da certificação AZ-900. Explique a diferença teórica e prática entre os modelos **IaaS, PaaS e SaaS** utilizando uma única analogia do mundo real (como fazer ou comprar uma pizza). Seja didático e destaque qual deles dá mais controle ao usuário e qual exige menos gerenciamento de infraestrutura."*

### Prompt 2: O Criador de Simulados Customizados
> *"Aja como um examinador oficial da prova de certificação AZ-900 da Microsoft. Crie um simulado contendo 5 questões inéditas de múltipla escolha focadas estritamente no domínio **'Identidade, Acesso e Segurança'** (cobrindo Microsoft Entra ID, MFA, Acesso Condicional, Confiança Zero e RBAC). Não dê as respostas imediatamente. Aguarde minha resposta para cada uma e forneça a correção detalhada com a explicação de por que as alternativas erradas estão incorretas."*

### Prompt 3: O Desmistificador de Conceitos Abstratos
> *"Tenho dificuldades em diferenciar **Alta Disponibilidade, Tolerância a Falhas, Escalabilidade e Elasticidade** na nuvem. Crie uma tabela comparativa simples explicando a definição de cada termo técnico e um exemplo prático de cenário do mundo real para cada um dentro do ecossistema do Microsoft Azure."*

### Prompt 4: Detalhamento de Serviços do Azure
> *"Explique o que é o serviço **Azure Blob Storage** e diferencie seus três níveis de acesso primários: **Quente (Hot), Frio (Cool) e Arquivo (Archive)**. Em qual cenário real de negócios cada um desses níveis deve ser escolhido para otimizar os custos de armazenamento da empresa?"*

---

## 🏆 5. Dicas de Ouro para a Aprovação

*   **Tradução Flexível:** O exame AZ-900 está totalmente disponível em português [63]. Contudo, se alguma tradução de tela parecer confusa ou incoerente durante o teste (por exemplo, termos técnicos traduzidos incorretamente), o sistema da prova permite que você alterne a exibição da questão para o inglês original a qualquer momento com apenas um clique [63].
*   **Foco no Básico:** Lembre-se de que a prova AZ-900 avalia conceitos básicos e de fundamentos de nuvem [62]. Não serão cobradas linhas de código complexas ou configurações avançadas de infraestrutura.
*   **Elimine as Absurdas:** Em questões de múltipla escolha ou verdadeiro/falso com mais de uma resposta válida, utilize o método de eliminação [108]. Provedores de nuvem nunca oferecem soluções sem custo recorrente ou que exijam exclusividade total sem justificativa regulatória técnica [153, 154, 155].

*Boa sorte nos estudos e rumo à sua certificação Azure!* 🚀
