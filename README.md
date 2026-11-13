🚀 JobMatch AI — Análise de Vagas e Geração de Currículos ATS
📌 Sobre o projeto

O JobMatch AI é uma aplicação desenvolvida com o auxílio do Lovable, com o objetivo de facilitar a busca por oportunidades profissionais e a personalização de currículos utilizando inteligência artificial.

A plataforma permite que o usuário cadastre suas informações profissionais, analise descrições de vagas e gere currículos personalizados de acordo com os requisitos de cada oportunidade.

A proposta é tornar o processo de candidatura mais estratégico, ajudando os candidatos a identificar suas compatibilidades com as vagas e apresentar suas qualificações de maneira mais adequada aos sistemas ATS (Applicant Tracking Systems).

🎯 Qual problema a aplicação resolve?

Um dos principais desafios enfrentados por candidatos durante processos seletivos é adaptar o currículo para diferentes oportunidades de emprego.

Muitas vezes, o profissional possui as qualificações necessárias para uma vaga, mas não consegue apresentar suas experiências e habilidades de maneira alinhada aos requisitos descritos pela empresa.

Além disso, muitas organizações utilizam sistemas ATS para realizar uma triagem automática de currículos, buscando palavras-chave, competências e experiências específicas.

O JobMatch AI busca solucionar esse problema oferecendo ferramentas que auxiliam o candidato em três etapas:

Organização profissional: permite cadastrar informações pessoais, experiências, formação e habilidades em um perfil centralizado.
Análise de vagas: permite inserir uma descrição de vaga para identificar seus requisitos e compreender melhor o perfil profissional procurado.
Geração de currículos personalizados: utiliza os dados cadastrados pelo usuário para gerar um currículo direcionado à oportunidade desejada, considerando boas práticas de formatação e compatibilidade com sistemas ATS.

Dessa maneira, a aplicação busca economizar tempo, facilitar a personalização dos currículos e melhorar a apresentação das qualificações profissionais dos candidatos.

⚙️ Como a análise funciona: da vaga colada até o currículo ajustado?

O funcionamento da aplicação está organizado em três áreas principais:

1. Meu Perfil

Na seção Meu Perfil, o usuário cadastra suas informações pessoais e profissionais.

Esses dados funcionam como uma base de informações que será utilizada nas demais funcionalidades da plataforma.

O perfil permite organizar informações como:

Nome e dados de contato;
Experiências profissionais;
Formação acadêmica;
Habilidades e competências;
Outras informações relevantes para a trajetória profissional.
2. Analisador de Vagas

Na seção Analisador de Vagas, o usuário pode copiar e colar a descrição de uma vaga de emprego que deseja concorrer.

A aplicação utiliza o conteúdo informado para realizar uma análise da oportunidade, ajudando o candidato a compreender os requisitos e as competências solicitadas pela empresa.

Essa etapa permite que o usuário tenha uma visão mais clara sobre o que precisa destacar em seu currículo.

3. Gerador ATS

O Gerador ATS permite que o usuário cole a descrição de uma vaga e gere um currículo personalizado utilizando as informações previamente cadastradas em seu perfil.

A aplicação utiliza os dados profissionais do candidato como referência para construir um currículo direcionado à oportunidade.

O objetivo é apresentar as experiências, habilidades e qualificações de maneira alinhada aos requisitos da vaga, utilizando uma estrutura adequada para facilitar a leitura por sistemas ATS.

Fluxo de funcionamento:

Meu Perfil → Cadastro das informações profissionais → Analisador de Vagas → Identificação dos requisitos → Gerador ATS → Currículo personalizado.

🤖 Desenvolvimento com Lovable: Mega Prompt utilizado

O desenvolvimento da aplicação foi orientado por um mega prompt enviado ao Lovable, ferramenta de desenvolvimento de aplicações com inteligência artificial.

O objetivo inicial era criar uma plataforma SaaS chamada JobMatch AI, voltada para o matchmaking entre candidatos e vagas de emprego, além da geração automática de currículos compatíveis com sistemas ATS.

O prompt especificava a estrutura da aplicação, tecnologias, identidade visual, funcionalidades, armazenamento de dados e experiência do usuário.

Mega Prompt original

Abaixo está o prompt utilizado como ponto de partida para o desenvolvimento:

text
# Prompt para Lovable - JobMatch AI (ATS Resume Builder + Matchmaking de Vagas)

Crie uma aplicação SaaS moderna chamada JobMatch AI, focada em matchmaking inteligente entre candidatos e vagas de emprego, além de geração automática de currículos ATS Friendly otimizados para cada vaga.

## Objetivo

A plataforma deve permitir que usuários:

1. Cadastrem seu perfil profissional.
2. Importem currículo existente (PDF ou DOCX).
3. Colem o link ou descrição de uma vaga.
4. Recebam um score de compatibilidade entre perfil e vaga.
5. Gere um currículo ATS Friendly personalizado para a vaga.
6. Recebam sugestões de melhorias para aumentar o match.
7. Baixem o currículo em PDF.
8. Acompanhem histórico de vagas analisadas.

## IMPORTANTE

A aplicação NÃO deve possuir:

- Login
- Cadastro
- Autenticação
- Recuperação de senha
- Controle de usuários
- Multiusuário

O usuário acessa diretamente a plataforma e utiliza todas as funcionalidades.

Todos os dados devem ser armazenados localmente utilizando:

- LocalStorage
- IndexedDB

ou banco de dados opcional sem necessidade de autenticação.

## Stack

- React
- TypeScript
- Vite
- OpenAI API
- Tailwind CSS
- ShadCN UI
- React Hook Form
- Zod
- TanStack Query
- Lucide React
- Recharts

## Design System

Utilize obrigatoriamente ShadCN UI.

Estética moderna inspirada em:

- Linear
- Stripe
- Vercel
- Notion

Paleta de cores:

- Primary: #2563EB
- Secondary: #1E40AF
- Background: #0A0A0A e #111827
- Surface: #171717 e #1F2937
- Text: #FFFFFF, #D1D5DB e #9CA3AF
- Success: #22C55E
- Warning: #F59E0B
- Danger: #EF4444

## Layout Geral

Criar interface dark premium.

- Sidebar fixa à esquerda.
- Header superior com pesquisa e perfil local do usuário.
- Área principal responsiva.
- Desktop First com adaptação mobile.

## Estrutura de Páginas

1. Landing Page
2. Dashboard
3. Meu Perfil
4. Analisador de Vagas
5. Gerador de Currículo ATS
6. Histórico
7. Configurações

## Inteligência Artificial

Implementar funcionalidades de:

- Matchmaking de vagas.
- Geração de currículos ATS Friendly.
- Gap Analysis.

A IA deve identificar palavras-chave, competências, requisitos e oportunidades de melhoria, mantendo as informações verdadeiras do usuário e nunca inventando experiências.

## Armazenamento de Dados

Utilizar armazenamento local para informações do perfil, experiências, formação, habilidades, vagas analisadas e currículos gerados.

## Componentes ShadCN

Utilizar componentes como:

- Button
- Card
- Badge
- Input
- Textarea
- Dialog
- Tabs
- Dropdown Menu
- Avatar
- Sheet
- Scroll Area
- Select
- Skeleton
- Progress
- Table
- Tooltip
- Sonner Toast

## Microinterações

- Hover suave.
- Fade animations.
- Loading skeletons.
- Progress bars animadas.
- Toasts para feedback.
- Dashboard com métricas animadas.

## Responsividade

Criar versões Mobile, Tablet e Desktop, com sidebar adaptável.

## Experiência Premium

Adicionar:

- Visual corporativo moderno.
- Alto contraste.
- Aparência SaaS enterprise.
- Componentes refinados.
- Excelente UX.
- Fluxo intuitivo.
- Performance otimizada.

## Funcionalidades Extras Premium

- ATS Score Breakdown.
- Keyword Optimizer.
- Resume Comparison.
- Smart Recommendations.

## Estrutura de Pastas

Organizar o projeto em componentes, páginas, hooks, serviços, tipos, utilitários, armazenamento e estilos.

## Entregáveis Esperados

1. Aplicação completa em React + TypeScript.
2. Estrutura de pastas escalável.
3. Componentes reutilizáveis.
4. Integração OpenAI.
5. Dashboard funcional.
6. Matchmaking de vagas.
7. Gerador ATS Friendly.
8. Exportação PDF e DOCX.
9. Tema dark azul/preto utilizando ShadCN UI.
10. Persistência local dos dados.
11. Histórico de análises.
12. Código limpo seguindo boas práticas SOLID e Clean Architecture.
13. UX moderna nível produto SaaS premium.
14. Sem sistema de login ou cadastro.
15. Utilização imediata ao acessar o aplicativo.

O que mudou do mega prompt inicial até a versão final?

O mega prompt inicial apresentava uma proposta bastante ampla, planejando uma plataforma completa de recrutamento e preparação profissional.

Durante a construção, o escopo foi direcionado para as funcionalidades centrais da experiência, priorizando a utilização prática da aplicação.

As principais diferenças entre a proposta inicial e o produto apresentado são:

Proposta inicial	Direcionamento da aplicação
Plataforma completa de matchmaking	Foco na análise de vagas e preparação do candidato
Importação de currículos PDF e DOCX	Perfil profissional como base das informações
Dashboard com diversas métricas	Priorização das funcionalidades principais
Histórico completo de candidaturas	Ênfase no fluxo de análise e geração
Configurações avançadas	Interface direcionada à utilização das ferramentas
Gerador ATS	Geração de currículo a partir do perfil e da vaga

A principal mudança foi concentrar a proposta nas três funcionalidades fundamentais: Meu Perfil, Analisador de Vagas e Gerador ATS.

Isso permitiu direcionar o produto para uma experiência mais objetiva, na qual o usuário cadastra suas informações, identifica os requisitos de uma oportunidade e utiliza esses dados para gerar um currículo personalizado.

Observação: a tabela descreve o direcionamento do produto em relação ao escopo planejado. Nem todos os itens podem ser considerados funcionalidades removidas ou alterações efetivamente realizadas sem uma comparação entre as versões do projeto.

🛠️ Tecnologias e ferramentas previstas no planejamento

O mega prompt especificou as seguintes tecnologias e ferramentas como base para o desenvolvimento:

React;
TypeScript;
Vite;
OpenAI API;
Tailwind CSS;
ShadCN UI;
React Hook Form;
Zod;
TanStack Query;
Lucide React;
Recharts.

O Lovable foi utilizado como ferramenta de desenvolvimento assistido por inteligência artificial.

🌐 Aplicação publicada

A aplicação pode ser acessada pelo seguinte endereço:

Link: [https://pixel-perfect-replay-62380.lovable.app/
](https://pixel-perfect-replay-62380.lovable.app/)

