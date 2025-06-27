# Skillium
TCC Curso Técnico em Informática - IFPR Campus Pinhais 2025

# Skillium

**Skillium** é uma plataforma web desenvolvida para ajudar estudantes a organizar e potencializar seus estudos. Através de ferramentas como **timers personalizados**, **calendário interativo**, **anotações rápidas** e **upload de conteúdos**, o sistema busca tornar a rotina de estudos mais eficiente, produtiva e intuitiva.

# Guia de Estilo - Projeto de Interface de Usuário

Este guia de estilo descreve os elementos visuais e componentes utilizados na construção da interface do projeto. Ele serve como base para manter a consistência visual em todo o sistema.

## 🎨 Identidade Visual

**Paleta de Cores – Aurora Boreal:**

| Cor           | Código Hex |
|---------------|------------|
| Roxo Neon     | `#8B32F4`  |
| Roxo Escuro   | `#5320A6`  |
| Branco Gelo   | `#F3F3F3`  |
| Preto Grafite | `#0E0D0D`  |

## 🔠 Tipografia

**Família Principal:** Arial  
**Família Secundária:** Verdana  

| Elemento        | Fonte                | Tamanho     | Estilo         |
|----------------|----------------------|-------------|----------------|
| `H1`           | Arial Bold           | 32px        | Negrito        |
| `H2/H3/etc.`   | Arial                | 20px        | Padrão         |
| Texto normal   | Verdana              | 16px        | Padrão         |
| Botões         | Arial Negrito        | 16px        | Negrito        |

---

## 🔘 Botões

- **Primário:** Roxo claro (`#8B32F4`)
- **Normal:** Roxo escuro (`#5320A6`)
- **Secundário:** Preto Grafite (`#0E0D0D`)
- **Ativo:** Braco

Todos os botões têm texto branco ou preto (dependendo da cor de fundo), cantos arredondados e espaçamento consistente.

---

## 📦 Elementos de Formulário

- Campos de texto com bordas retas, fundo branco e texto cinza claro como placeholder.
- Botões de ação: Salvar, Editar, Apagar, todos com cores de destaque (`#8B32F4`), estilo negrito.

---

## 🔣 Ícones

**Fonte Utilizada:** Font Awesome  
Ícones incluídos:
- Calendário
- Sino (Timer)
- Documento
- Livro
- Sair (log out)

Todos estilizados com a cor `#8B32F4`, mantendo o padrão visual.

---

## 🖼️ Imagens

Imagens decorativas ou de conteúdo seguem um estilo simples com borda cinza clara e fundo neutro.

---

## ✅ Objetivo

Este guia serve como uma referência visual para o desenvolvimento contínuo da interface do projeto, garantindo coesão e acessibilidade.

Acesse o protótipo navegável através do link abaixo:

👉 [Clique aqui para visualizar no Quant-UX](https://app.quant-ux.com/#/test.html?h=a2aa10aeNkthEyQjAYheWOkvKdzcOyZWngW2zJ9vjgBRAxiM27JSUYdHMV9G&ln=en)

## 👥 Equipe

- **Guilherme Borges** – Desenvolvedor full-stack e documentação  
- **Ighor Alexandre** – Desenvolvedor full-stack e documentação  

## 🎯 Visão Geral

Skillium é um site responsivo e funcional voltado para estudantes que buscam melhor organização do tempo e dos conteúdos de estudo. Com uma interface intuitiva, o sistema oferece:

- Criação de cronogramas de estudo
- Timer baseado no metodo pomodoro
- Sistema de anotações rápidas
- Upload e categorização de conteúdos
- Painel com estatísticas de uso e progresso
- Calendário integrado ao google

## 🧠 Público-alvo

Estudantes do Ensino Médio,Técnico, Superior e pessoas que buscam organizar o estudo no geral

## 🎯 Objetivo

Desenvolver uma plataforma online que centralize ferramentas de organização pessoal voltadas ao estudo, promovendo mais eficiência na preparação para provas, vestibulares, concursos ou rotina escolar/universitária.

## 📦 Escopo do Produto (MVP)

### Funcionalidades principais

- Autenticação de usuários (login/cadastro)
- Calendário interativo com notificações
- Temporizador de foco personalizável
- Editor de notas por categoria
- Upload de materiais didáticos
- Interface responsiva para mobile e desktop

### Critérios de Aceite

- Compatibilidade com os principais navegadores modernos
- Timer funcional com notificação ao término
- CRUD completo de eventos no calendário
- Salvamento automático de anotações
- Upload restrito a tipos de arquivos seguros (PDF, TXT, DOCX, etc)

## ⚠️ Matriz de Riscos

| Id Risco | Descrição do Risco                             | Probabilidade | Impacto | Plano de Resposta                                               | Status do Risco     |
|----------|------------------------------------------------|---------------|---------|------------------------------------------------------------------|----------------------|
| R1       | Atraso na entrega de funcionalidades           | Baixa         | Alto    | Divisão de tarefas com controle semanal                         | Em monitoramento     |
| R2       | Erros no timer ou calendário                   | Média         | Alto    | Testes unitários e verificação cruzada entre navegadores        | Em desenvolvimento   |
| R3       | Upload de arquivos inseguros                   | Média         | Alto    | Validação de tipo e antivírus automático na API                 | Em análise           |
| R4       | Layout com problemas em telas pequenas         | Baixa         | Médio   | Aplicação de design responsivo com media queries                | Controlado           |
| R5       | Baixa adesão por complexidade de uso           | Média         | Médio   | Interface intuitiva e testes com usuários                       | Em melhoria contínua |

[Clique aqui para abrir o Diagrama de Atividade](https://www.mermaidchart.com/raw/1d2757ea-143f-41b5-b738-9b84568e656c?theme=light&version=v0.1&format=svg)
[Clique aqui para abrir o Trello do nosso projeto](https://trello.com/invite/b/685dfed0478c0018a4e197da/ATTI9d93741efbb0da9fe79c29ee7e5a55d20C3A1ED9/organizacao)
---








