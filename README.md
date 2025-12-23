# 💸 App de Organização de Finanças Pessoais "Mentor Financeiro" by Ricardo Freitas

1. PRD REVISADO (COM DESIGN UNIVERSAL)

```txt
1.1 Visão Geral do Produto

Criar um assistente financeiro pessoal conversacional e inclusivo, no qual o usuário registra gastos, acompanha metas e recebe orientações financeiras. A interação principal ocorre via chat em linguagem natural com um assistente inteligente chamado "Mentor Financeiro".

O objetivo é desmistificar e automatizar o controle financeiro, tornando-o uma tarefa simples, rápida e acessível, eliminando a necessidade de formulários complexos ou planilhas.

A solução será construída sob uma rigorosa abordagem de Design Universal desde a sua concepção, garantindo uma experiência de uso excepcional para o maior número possível de usuários, independentemente de idade, nível de escolaridade, letramento digital, condições cognitivas, sensoriais ou motoras.

1.2 Problema a Ser Resolvido

O controle financeiro pessoal, embora essencial, é frequentemente percebido como uma tarefa complexa e desmotivadora. Muitos usuários abandonam aplicativos de controle financeiro porque:

Fadiga: Processos manuais e repetitivos de registro de despesas.
Interfaces complexas: Telas poluídas, com múltiplas abas, gráficos difíceis de interpretar e jargões técnicos.
Linguagem excludente: Uso de termos financeiros que não são do dia a dia, tornando o usuário se sentir incapaz.
Experiência impessoal e punitiva: Aplicativos que apenas apontam o ultrapassagem de metas sem oferecer caminhos ou educação.
Falta de personalização: Soluções genéricas que não se adaptam ao perfil e à realidade de cada usuário.
Barreiras de acessibilidade: Baixa ou nenhuma adaptação para usuários com deficiências visuais, motoras ou cognitivas.

Esses fatores afetam de forma desproporcional usuários iniciantes, pessoas com menor letramento digital e indivíduos com necessidades específicas de acessibilidade.

1.3 Objetivo do Produto

A solução proposta é redefinir a experiência de controle financeiro, transformando-a de uma obrigação burocrática para um hábito simples e empoderador, por meio de uma experiência conversacional, com recomendações automáticas e educativas que incentivem o usuário a manter o hábito de organização financeira. 

Objetivo Principal: Reduzir a barreira de entrada para o controle financeiro, tornando-o um hábito acessível, educativo e contínuo para um público amplo e diverso.

Objetivos Específicos:

Oferecer uma experiência intuitiva e centrada no diálogo, que minimize a necessidade de navegação por menus e telas.
Promover a educação financeira através de interações contextuais e personalizadas, com um tom de apoio e não de julgamento.
Garantir inclusão e acessibilidade total, permitindo que pessoas com diferentes habilidades e contextos de uso possam utilizar o produto com autonomia.
Aumentar a retenção de usuários ao demonstrar valor real e imediato, simplificando o que é complexo.

1.4 Público-Alvo

Pessoas que desejam iniciar ou retomar a organização de suas finanças pessoais de forma prática e sem complicação, incluindo:

Usuários iniciantes em controle financeiro: Jovens e adultos que nunca tiveram disciplina ou ferramenta adequada para começar.
Pessoas que buscam simplicidade: Profissionais ocupados, pais, estudantes que preferem uma experiência mais natural e amigável a planilhas e formulários.
Pessoas com "aversão a números": Usuários que se sentem intimidados por interfaces técnicas e linguagem financeira.
Público diverso: Usuários com diferentes níveis de letramento, idade, habilidades digitais e necessidades de acessibilidade.

Arquétipos de Usuários (Personas):

Ana, 24, Jovem Profissional: Iniciando a vida financeira, quer controlar os gastos, mas acha apps de finanças "chatos" e complicados. Valoriza a praticidade do chat.

Carlos, 45, Pai de Família: Ocupado com o trabalho e os filhos, precisa de uma forma rápida de anotar gastos e saber se está no caminho certo para as metas da família. Não tem tempo para categorizar tudo manualmente.

Marta, 65, Aposentada: Tem pouca familiaridade com tecnologia e alguma dificuldade visual. Precisa de uma interface com fontes grandes, alto contraste e uma interação de conversa muito clara e direta.

1.5 Princípios de Design (MVP)

O produto deverá ser orientado pelos seguintes princípios:

Design Universal (Inclusive Design): A interface deve ser projetada desde o início para ser utilizável pelo maior espectro de pessoas possível, sem necessidade de adaptações específicas.

Linguagem Simples e Empática: Comunicação em português claro, direto e amigável, evitando jargões. O tom do "Mentor Financeiro" deve ser sempre de apoio.

Interação Multimodal (Futura): Prioritariamente texto no MVP, mas a arquitetura deve ser preparada para adicionar interação por voz em versões futuras.

Baixa Carga Cognitiva: Apresentar informações de forma progressiva e resumida. Respostas curtas, claras e focadas na ação ou informação solicitada.

Tolerância a Erros: O sistema deve ser robusto para entender variações na linguagem do usuário e permitir correções fáceis e naturais via conversa (ex: "Ops, errei, aquele gasto foi de 35, não 30").

Feedback Constante e Claro: O sistema deve sempre confirmar as ações do usuário (ex: "Entendido! Gasto de R$30 em transporte registrado.") e explicar o que está fazendo, criando confiança e transparência.

1.6 Funcionalidades-Chave (MVP)

Registro de Gastos via Chat em Linguagem Natural:
- O usuário inicia o registro com frases como: "Gastei 30 reais com transporte ontem", "Paguei 50 de almoço", "Comprei um livro por 80".
- O sistema deve identificar de forma automática o valor, a categoria (se mencionada) e a data da transação.

Classificação Inteligente das Transações:
- Identificação automática de valor, categoria (ex: alimentação, transporte, lazer, contas) e período com base no texto do usuário.
- O usuário pode facilmente corrigir uma classificação incorreta (ex: "Isso na verdade foi lazer, não alimentação"), e o IA deve aprender com a correção.

Definição e Acompanhamento de Metas Financeiras:
- O usuário define metas de forma conversacional: "Quero economizar R$ 500 até o Natal".
- O Agente deve perguntar o prazo e sugerir um valor mensal/semanal, facilitando o planejamento.
- Acompanhamento claro do progresso através de frases simples (ex: "Você já economizou R$ 150 da sua meta de R$ 500. Falta R$ 350!"). Evitar gráficos complexos no MVP.

Agente Financeiro ("Mentor Financeiro") com Abordagem Educativa:
- Tom de voz: Amigável, encorajador, nunca julgador.
- Exemplo de interação: Em vez de "Você ultrapassou seu orçamento", dizer "Vi que seus gastos com lazer estão um pouco acima do planejado este mês. Que tal a gente dar uma olhada juntos em algumas opções para equilibrar?".
- Oferecer dicas de economia e boas práticas financeiras de forma proativa e adaptadas ao comportamento do usuário, mas sem ser invasivo.

Relatórios Simples e Acessíveis:
- Formato: Texto claro e, opcionalmente, gráficos de barras simples com alto contraste e legendas claras.
- Deve ser gerado tanto por solicitação do usuário ("Me mostre um resumo do mês") quanto de forma proativa (ex: no fim do mês, enviar um resumo positivo: "Parabéns! Você conseguiu economizar R$ 200 este mês!").

1.7 Requisitos Não Funcionais (MVP)

Acessibilidade: Conformidade com as diretrizes WCAG (Web Content Accessibility Guidelines) 2.1 Nível AA, no mínimo. Isso inclui alto contraste, compatibilidade total com leitores de tela (como VoiceOver e TalkBack), navegação por teclado e tamanhos de fonte ajustáveis.

Privacidade e Segurança: Todas as transações e dados do usuário devem ser criptografados (tanto em trânsito quanto em repouso). A política de privacidade deve ser transparente, de fácil entendimento e prontamente acessível.

Performance: O tempo de resposta do agente conversacional deve ser inferior a 2 segundos para interações simples. A aplicação deve ser leve e funcionar bem em conexões de internet mais lentas.

Linguagem e Tom: Experiência consistente em diferentes dispositivos (mobile-first, mas acessível via web). O tom educacional e inclusivo deve ser mantido em todas as interações.

1.8 Entregável da IA

Processamento de Linguagem Natural (PLN): Capacidade de entender variações da linguagem natural, gírias e diferentes formas de expressar uma mesma despesa.

Modelo de Classificação: Algoritmo de machine learning para categorizar despesas que possa ser treinado e melhorado com as correções dos usuários.

Motor de Aprendizagem: O sistema deve aprender com as correções do usuário para refinar as classificações e as sugestões futuras, personalizando a experiência.

Integração de APIs (Futura): Arquitetura preparada para futura integração com APIs de bancos (usando Open Banking) para automação de lançamentos, mas isso não está no escopo do MVP.

A IA deverá:
Propor um plano de MVP considerando princípios de Design Universal;
Descrever fluxos conversacionais acessíveis;
Principais telas (chat, dashboard de metas, relatórios)
Sugerir estratégias de validação com usuários diversos;
Esboço de validação inicial (testes com usuários iniciantes e diversos perfis, feedback rápido sobre usabilidade e acessibilidade)
Utilizar linguagem acessível, educativa e em português, evitando jargões técnicos.
```

Interações com o lovable
> Crie um App de Finanças com base no seguinte PRD (Product Requirements Document) {PRD}

Resultado final no lovable: https://money-mindful-chat.lovable.app/

<img width="1003" height="557" alt="image" src="https://github.com/user-attachments/assets/41ad0472-d84b-4850-91e8-2fb57829a891" />

<img width="1355" height="605" alt="image" src="https://github.com/user-attachments/assets/e9bbd187-0beb-4cdc-a105-50282e5524a0" />

<img width="1345" height="593" alt="image" src="https://github.com/user-attachments/assets/b2764b2a-133a-40ad-a90e-a01f3f3fc038" />

<img width="1345" height="587" alt="image" src="https://github.com/user-attachments/assets/fb27168c-50c0-45e8-8619-bff6eb86ba02" />

# Assistente Financeiro Conversacional

> Controle suas finanças com a simplicidade de uma conversa.

## Sobre o Projeto

Este é um aplicativo de organização financeira pessoal que utiliza uma interface conversacional para tornar o controle de gastos simples, acessível e educativo. O objetivo é eliminar a complexidade dos aplicativos financeiros tradicionais, que exigem preenchimento manual de formulários e possuem interfaces carregadas.

Através de um assistente inteligente, os usuários podem registrar despesas, criar metas e receber dicas financeiras personalizadas usando linguagem natural, como se estivessem conversando com um amigo.

## Funcionalidades Principais

- **🗣️ Registro de Gastos via Chat:** Adicione despesas simplesmente digitando frases como "Gastei R$ 30 com transporte ontem".
- **🤖 Classificação Inteligente:** O sistema identifica e categoriza automaticamente suas transações (alimentação, lazer, contas, etc.).
- **🎯 Acompanhamento de Metas:** Defina metas de economia de forma conversacional e acompanhe seu progresso com feedback claro e motivador.
- **📚 Assistente Financeiro:** Receba orientações e dicas de economia de um agente educacional, com uma abordagem amigável e sem jargões técnicos.
- **📊 Relatórios Simples:** Visualize resumos do seu financeiro de forma clara e acessível, com foco na informação mais importante.

## O Diferencial: Design Universal e IA

O projeto é construído com um forte compromisso com o **Design Universal**, garantindo que a experiência seja inclusiva e acessível para o maior número de pessoas possível, independentemente de sua idade, habilidade digital ou necessidades específicas.

- **Linguagem Clara:** Comunicação simples e direta, evitando termos financeiros complexos.
- **Interface Acessível:** Alto contraste, navegação intuitiva e compatibilidade com leitores de tela.
- **Baixa Carga Cognitiva:** Interações curtas e progressivas que não sobrecarregam o usuário.
- **Tom Empático:** O assistente financeiro foi projetado para ser um apoiador, e não um fiscal.

## Estado Atual do Aplicativo

O aplicativo está em sua fase inicial de desenvolvimento. As telas atuais, como as de "Histórico" e "Resumo Financeiro", apresentam um estado limpo, convidando o usuário a começar a interagir.

**Tela de Histórico:**
*   Exibe "0 transações" e a mensagem "Nenhuma transação encontrada".
*   Contém uma chamada para ação: "Comece a registrar seus gastos no chat!".

**Tela de Resumo:**
*   Mostra um resumo financeiro com valores zerados ("Gastos hoje: R$ 0,00").
*   Indica a ausência de metas e gastos recentes, incentivando o usuário a criar seu primeiro objetivo.

Essas telas refletem o foco do aplicativo em guiar o usuário a começar sua jornada financeira pelo chat.

## Tecnologias Utilizadas (Conceitual)

- **Processamento de Linguagem Natural (PLN):** Para entender e interpretar as mensagens do usuário.
- **Machine Learning:** Para a classificação automática e inteligente das transações.
- **Princípios de Design Universal e Acessibilidade (WCAG):** Para guiar o desenvolvimento da interface do usuário (UI).

## Próximos Passos

- [ ] Refinar o modelo de IA para maior precisão na classificação de gastos.
- [ ] Implementar interação por voz (comando de áudio).
- [ ] Desenvolver novas funcionalidades de relatórios e insights personalizados.
- [ ] Explorar integrações com APIs bancárias (Open Banking) para automação futura.

## 🧠 Reflexão

### O que funcionou bem?
O refinamento do PRD previamente feito no Copilot ajudou muito, pois os créditos do Lovable acabaram em apenas 3 interações.

### O que não funcionou como o esperado?
Esperava poder interagir mais vezes gratuitamente com o Lovable, mas as interações feitas já foram de grande valia para aprender mais sobre Vibe Coding.

### O que aprendi sobre conversar com IAs?
Aprendi que é basicamente igual a conversar com uma pessoa: quanto mais detalhes e clareza você dá, melhor é a interação.
