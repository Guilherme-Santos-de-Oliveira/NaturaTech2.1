IFPR Campus Pinhais – Técnico em Informática
README e Apresentação do Projeto

Projeto: NaturaTech
Versão: 2.0
Data: 10/04/2025

Alunos participantes:
Guilherme Santos (Desenvolvedor de apoio, Designer, pesquisador,parte escrita do Tcc)
Giovani Ramos (Desenvolvedor principal, tester,aulixiar de escrita)

---

## 1. Identificação

**Nome do Projeto:** NaturaTech  
**Slogan:** “Se você quer plantar, a NaturaTech vai te ajudar”  
**Mascote:** Teco – sagui-da-serra-escuro (mascote decorativo)  
**Cores principais:** Verde, preto, azul e marrom

**Organização da Equipe:**
| Nome             | Papel                   | Responsabilidades principais                             |
|------------------|--------------------------|----------------------------------------------------------|
| Guilherme Santos |  Documentador e desiniger| escrita técnica e design visual      |
| Giovani Ramos    | Desenvolvedor principal   | desenvolver programação      |

**Redes Sociais:** *Não se aplica*  
**Data de criação:** 10/04/2025

---

## 2. Introdução

### a. Visão Geral do Projeto
O NaturaTech é um aplicativo de orientação ao cultivo  que ajuda pessoas leigas e pequenos produtores a cuidarem de plantas, flores, frutas e hortaliças. Ele oferece informações simples e acessíveis sobre o cultivo de cada planta, como tipo de solo, adubo, rega, época ideal de plantio, pragas e repelentes naturais.

### b. Público Alvo
- Pessoas com pouco ou nenhum conhecimento sobre agricultura
- Pequenos produtores rurais
- Usuários que desejam começar hortas caseiras

### c. Objetivo do Projeto
Criar um aplicativo leve, funcional e educativo que auxilie usuários no cultivo de plantas, fornecendo informações personalizadas e de fácil entendimento.

### d. Escopo do Produto

**Descrição do Produto (MVP):** Aplicativo móvel com cadastro de plantas e exibição de informações básicas organizadas em tabelas simples.

**Principais Entregas:**
- Cadastro de plantas com dados sobre solo, adubo e pragas
- Tela com explicações sobre tipos de adubo, solo e pragas
- Mascote visual decorativo
- Aplicativo funcional em Flutter

**Critérios de Aceite:**
- **Qualitativos:** Interface amigável com linguagem simples; informações organizadas e de fácil entendimento
- **Quantitativos:** Funciona offline; tempo de carregamento inferior a 2 segundos; tamanho inferior a 50 MB

### e. Matriz de Riscos

| Id  | Descrição do Risco                                   | Probabilidade | Impacto | Plano de Resposta                              | Status             |
|-----|--------------------------------------------------------|---------------|---------|------------------------------------------------|--------------------|
| R01 | Equipe pequena e com múltiplas tarefas               | Alta          | Médio   | Dividir funções e priorizar MVP                | Resolvido  |
| R02 | Dificuldade de adaptação ao FlutterFlow              | Média         | alto  | Usar tutoriais e exemplos prontos              | Em acompanhamento       |
| R03 | Perda de dados em modo offline                       | Baixa         | Alto    | Utilizar Firebase com armazenamento local      | Em teste           |
| R04 | Interface confusa para leigos                        | Baixa       | Alto    | Testar com usuários e simplificar textos       | Em acompanhamento  |
| R05 | Limitações técnicas do dispositivo do usuário        | Baixa         | Baixo   | App leve e compatível com versões antigas      | Resolvido          |

---

## 3. Design de Software

### a. UI Design (Guia de Estilo)

| Elemento         | Especificação                                   |
|------------------|-------------------------------------------------|
| Fonte            | Roboto (Flutter padrão)                         |
| Ícones           | Simples, grandes e intuitivos                   |
| Cores            | Verde (#3B7A57), preto, azul e marrom           |
| Estilo visual    | Minimalista, com foco em acessibilidade         |
| Teco             | Mascote decorativo, sagui-da-serra-escuro       |

### b. Prototipação
- Ferramenta: Canva (protótipos estáticos)
- Interfaces criadas:
  - Tela inicial com botões grandes
  - Tela de cadastro de planta
  - Tela de informações com tabelas

### c. Roteiro de Testes (com base nos critérios de aceite)

| Caso de Uso           | Ação esperada                          | Resultado esperado                           |
|------------------------|-----------------------------------------|----------------------------------------------|
| Buscar planta          | Digitar nome na busca                  | Planta aparece com dados corretos            |
| Visualizar informações | Clicar em planta           | aparece informações basicas|
| Visualizar informações | Clicar em leia mais            | ir para o site com as informações|
| Visualizar informações | Clicar em "como cultivar"            | ir para tela onde etão instruçoes de como cultivar a planta|
| adicionar planta | Clicar m adicionar            |  adiciona a planta em questão em "minhas plantas"|

---

## 4. Organização do Projeto

### a. Cronograma e Duração

| Etapa                  | Início       | Fim         | Responsável         |
|------------------------|--------------|-------------|----------------------|
| Planejamento           | 10/04/2025   |    ---      | Equipe               |
| Levantamento de dados  | 14/04/2025   |    ---      | Giovani              |
| Design e protótipos    | 20/04/2025   | 23/04/2025  | Guilherme            |
| Desenvolvimento        | 24/04/2025   | 10/05/2025  | Equipe               |
| Testes                 | 11/05/2025   | 14/07/2025  | Guilherme            |
| Finalização            | 15/05/2025   | 17/08/2025  | Equipe               |

### b. Quadro Kanban
- Ferramenta usada: Trello
- Listas: A Fazer, Em Progresso, Concluído

### c. Relatório de Desempenho
- Todas as tarefas principais concluídas até o momento conforme cronograma

### d. Relatório de Encerramento e Lições Aprendidas
- Importância de dividir bem as tarefas
- Manter o projeto simples ajuda a concluir tudo com qualidade

---

## 5. Metodologia de Desenvolvimento

### a. Processo / Metodologia
- **Metodologia ágil:** Kanban com quadro no Trello

### b. Recursos Utilizados
- **Tecnologias:** FlutterFlow, Firebase Firestore
- **Ferramentas:** Canva, Trello, Google Docs
- **Linguagem:** Dart (gerado pelo FlutterFlow)
- **Equipamentos:** Notebooks pessoais com conexão à internet

### c. Resultados Esperados
- Aplicativo funcional, leve, educativo e fácil de usar

### d. Métricas de Acompanhamento
- Tempo de carregamento inferior a 2 segundos
- Funcionalidades testadas com sucesso
- Feedback positivo dos testes com usuários

### e. Instruções para Download e Execução
- O app poderá ser disponibilizado em formato APK para Android via Google Drive
- Não requer internet após instalação (modo offline)

### f. Licença de Uso e Distribuição
- Licença livre para uso pessoal e pequena empresa

---

## 6. Anexos Técnicos

**a. Resultados da Entrevista com o Usuário:** *em anexo físico*

**b. Termo Livre de Consentimento:** *em anexo físico*

**c. Documento de Pré-Projeto:** *em anexo físico*

**d. Documento de Projeto:** *este README + Documento de Requisitos*

**e. Modelagem do Sistema:**
- Documento de Requisitos ✅
- Documento de Casos de Uso ❌ *(em desenvolvimento)*
- Diagrama de Atividades ❌ *(em desenvolvimento)*
- Diagrama de Sequência ❌ *(em desenvolvimento)*
- Diagrama de Classes ❌ *(em desenvolvimento)*
- Projeto de Banco de Dados (DER) ❌ *(em desenvolvimento no Workbench)*

