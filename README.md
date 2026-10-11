# SolucaoLAYER5
# 🚀 LAYER5 — Extensão Inteligente Help Desk SJP (GLPI)

> **Solução desenvolvida para o 1º Hackathon SJP — Gestão Pública**  
> *Prefeitura Municipal de São José dos Pinhais | Secretaria Municipal de Inovação, Modernização e Transformação Digital (SIMOT)*

---

## 👥 Equipe LAYER5

- **Bernardo Novaski Vidal de Almeida** — *Desenvolvedor & Empreendedor*
- **Affonso Kopmann** — *Desenvolvedor & Empreendedor* (Lead Developer)
- **Silvio Ricardo Batista** — *Desenvolvedor & Empreendedor*

---

## 📌 Sobre o Projeto

O **LAYER5 Help Desk** é uma solução GovTech desenvolvida para eliminar o **"ponto cego"** da execução de chamados em campo na Administração Pública de São José dos Pinhais.

Em vez de impor um novo sistema e exigir migrações custosas, a plataforma atua como uma **extensão nativa (plugin)** do **GLPI** — o sistema de chamados já utilizado pela prefeitura.

A solução moderniza o fluxo com **rastreabilidade em tempo real**, **5 dashboards estratégicos de controle**, **validação obrigatória pelo usuário** e um **motor de gamificação regulado pelo gestor**.

---

## ✨ Principais Diferenciais e Funcionalidades

### 1. 🔌 Extensão Nativa ao GLPI

- **Curva de aprendizado zero:** não exige troca de sistema nem retreinamento das equipes.
- **Integração bidirecional via API:** mantém o ID original do chamado e sincroniza o status automaticamente na base municipal.

### 2. 🛡️ Fim do "Ponto Cego" e Validação Obrigatória — Regra de Ouro

- **Check-in e geolocalização:** rastreamento da chegada do técnico à unidade, como escolas, CMEIs e unidades de saúde.
- **Tratamento de impedimentos:** botão de reporte em tempo real para falta de materiais ou peças, com notificação instantânea ao gestor.
- **Validação com nota de 1 a 5 estrelas:** o chamado só é considerado finalizado e o XP do técnico é liberado após a confirmação e avaliação direta do servidor solicitante, evitando encerramentos indevidos.

### 3. 🎮 Gamificação Regulada pelo Gestor

- **Triagem meritocrática:** ao atribuir o chamado, o gestor define a **prioridade** e a **complexidade técnica** da tarefa.
- **Cálculo transparente de XP:** a pontuação do técnico considera a complexidade do chamado, o cumprimento do SLA, o tempo de resolução, a eficiência e a avaliação do usuário.

### 4. 📊 Control Tower — 5 Dashboards em Tempo Real

1. **Status dos Chamados:** visão Kanban ágil com os estados Aberto, Em Atendimento, Impedimento, Aguardando Validação e Concluído.
2. **Estado dos Chamados:** mapeamento por setor de atendimento, incluindo Redes, Impressoras, Hardware, Telefonia e Sistemas.
3. **Operadores em Campo:** acompanhamento geográfico das equipes remotas e presenciais.
4. **Performance & SLA:** métricas focadas na meta de **reduzir em 20% o tempo de resolução**.
5. **Gamificação & Ranking:** painel de engajamento, medalhas e conquistas da equipe técnica.

### 5. 🏛️ Conformidade com a Lei de Soberania Digital

- **Referência legal:** Lei Municipal nº 4.715/2025.
- **100% on-premise:** projetado para operar no datacenter próprio do município, sob gestão da SIMOT.
- **Zero custo de nuvem terceirizada:** arquitetura projetada sem dependência de serviços externos pagos.
- **Código-fonte aberto e auditável:** transparência tecnológica e possibilidade de auditoria pela Prefeitura.

---

## 🛠️ Tecnologias Utilizadas

A aplicação foi projetada com foco em **desempenho, leveza, fácil manutenção e compatibilidade web**.

- **Frontend / Web App:** HTML5, CSS3 (Flexbox e CSS Grid) e JavaScript (ES6+ Vanilla).
- **Visualização de Dados:** bibliotecas JavaScript para renderização dos gráficos dos cinco dashboards e dos quadros Kanban.
- **Integração / Backend:** arquitetura orientada a APIs REST e Webhooks para comunicação bidirecional com o GLPI.

---

## 🔄 Fluxo de Funcionamento (Workflow)

```text
[1. Chamado no GLPI]
          |
          v
[2. Triagem e Atribuição de XP pelo Gestor]
          |
          v
[3. Check-in e Execução em Campo]
          |
          v
[4. Registro de Evidências Fotográficas]
          |
          v
[5. Avaliação do Solicitante (1 a 5 estrelas)]
          |
          v
[6. Encerramento e Sincronização com o GLPI]
```

---

## 🎯 Objetivo Estratégico

Modernizar a gestão de chamados de TI da Administração Pública por meio de **rastreabilidade, transparência, eficiência operacional e valorização dos servidores**, mantendo a integração com os sistemas existentes e respeitando a soberania tecnológica municipal.

> **LAYER5 — Mais transparência, mais eficiência e melhores serviços públicos.**

---