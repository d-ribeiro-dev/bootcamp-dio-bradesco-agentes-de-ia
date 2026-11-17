# Recursos e Materiais de Apoio

Materiais de estudo, documentações, ferramentas recomendadas e referências organizadas por semana para apoiar sua jornada de 30 dias.

---

## 💻 Semana 1 — Hardware e Sistemas Operacionais

### 📚 Cursos e Referências Recomendadas
- **Cursos e Trilhas da DIO (Digital Innovation One):**
  - Módulos fundamentais de Hardware, Introdução a Sistemas Operacionais e Linux.
- **Curso de Manutenção de Computadores — IFSul:**
  - Material introdutório e gratuito sobre arquitetura de computadores, periféricos e diagnóstico básico.
- **Linux Fundamentals:**
  - Tutoriais e guias de comandos básicos (`cd`, `ls`, `cat`, `grep`, `chmod`, `chown`, `ps`, `top`).
  - [Ubuntu Tutorials / Documentação Oficial do Linux](https://ubuntu.com/tutorials)

### 🛠️ Ferramentas & Comandos Práticos
- **Windows:**
  - Atalhos de diagnóstico: `Win + R` > `taskmgr` (Gerenciador de Tarefas), `devmgmt.msc` (Dispositivos), `eventvwr` (Visualizador de Eventos).
  - Utilitários de integridade: `sfc /scannow` e `chkdsk`.
- **Linux / WSL:**
  - Diagnóstico de processos: `top`, `htop`, `ps aux`, `kill -9`.
  - Espaço em disco e uso de memória: `df -h`, `du -sh`, `free -m`.

---

## 🌐 Semana 2 — Redes e Segurança da Informação

### 📚 Cursos e Referências Recomendadas
- **Microsoft Learn — Segurança do Windows:**
  - Conceitos de proteção de identidade, antivírus nativo (Microsoft Defender) e controle de contas de usuário (UAC).
- **Conteúdos de Redes da DIO:**
  - Fundamentos do modelo TCP/IP, endereçamento IPv4/IPv6, portas e serviços essenciais.
- **Cartilha de Segurança para a Internet (CERT.br):**
  - Guias essenciais sobre golpes, engenharia social, phishing, criação de senhas seguras e uso de MFA (Autenticação em Duas Etapas).

### 🛠️ Ferramentas & Comandos Práticos
- **Diagnóstico de Conectividade:**
  - `ipconfig /all` (Windows) ou `ip a` / `ifconfig` (Linux): verificar IP, máscara e gateway padrão.
  - `nslookup dominiodosaas.com`: testar se a resolução DNS está respondendo corretamente.
  - `ping -n 4 <endereço>`: checar latência e perda de pacotes para a rede local ou roteador.
  - `tracert <endereço>` (Windows) ou `traceroute` (Linux): rastrear a rota dos pacotes até o destino.

> [!WARNING]
> Execute comandos de diagnóstico de rede (`ping`, `tracert`) apenas em redes locais autorizadas ou em destinos públicos seguros, respeitando as boas práticas.

---

## 🎧 Semana 3 — Help Desk, Atendimento e Customer Success

### 📚 Cursos e Referências Recomendadas
- **Conceitos ITIL 4 (Fundamentos):**
  - Diferença estrutural entre **Incidente** (interrupção do serviço), **Requisição de Serviço** (pedido padrão) e **Problema** (causa raiz de incidentes recorrentes).
  - Conceito de **SLA** (Acordo de Nível de Serviço) e **SLO/SLA de Atendimento e Resolução**.
- **Customer Success & Suporte Técnico:**
  - Métricas essenciais: **CSAT** (Customer Satisfaction Score), **FCR** (First Contact Resolution), **NPS** (Net Promoter Score) e **CES** (Customer Effort Score).
- **Comunicação Empática e Escrita Técnica:**
  - Técnicas de escuta ativa, linguagem positiva, alinhamento de expectativas e como explicar causas técnicas sem 'tecniquês'.

### 🛠️ Ferramentas & Ambientes de Simulação
- **Depuração no Navegador para SaaS:**
  - Ferramentas de Desenvolvedor (`F12` ou `Ctrl + Shift + I`):
    - Aba **Network (Rede):** identificar requisições com status `4xx` (cliente/permissão) ou `5xx` (falha de servidor).
    - Aba **Application / Storage:** limpar Cookies, LocalStorage e Cache de sessão.
- **Simuladores de Help Desk:**
  - Estudo de interfaces como Zendesk, Jira Service Management, Freshdesk ou HubSpot (artigos e vídeos de demonstração pública).

---

## 🚀 Semana 4 — Integração, Troubleshooting SaaS e Entregas

### 📚 Cursos e Referências Recomendadas
- **Boas Práticas para Base de Conhecimento (Knowledge Base):**
  - Estrutura recomendada de artigos: *Título orientado ao problema*, *Contexto*, *Pré-requisitos*, *Passo a passo com telas/exemplos* e *O que fazer se o erro persistir*.
- **Matriz de Priorização (Impacto x Urgência):**
  - Como classificar criticidade de chamados (P1/Crítico, P2/Alto, P3/Médio, P4/Baixo).

### 📋 Modelos para as Entregas Finais
1. **Checklist de Triagem de Conectividade:**
   - 1. Verificar conexão física/Wi-Fi > 2. Testar acesso a outros sites > 3. Testar navegação anônima sem extensões > 4. Limpar cache/DNS > 5. Verificar status da aplicação SaaS (ex: status page pública).
2. **Modelo de Ticket de Suporte:**
   - ID do chamado, solicitante, impacto/urgência, ambiente/navegador/SO, descrição passo a passo para reproduzir o erro, evidências (prints simulados) e comunicação de retorno ao cliente.
3. **Artigo de Base de Conhecimento:**
   - Exemplo de tema sugerido: *"Como redefinir sua senha e reconfigurar o MFA no aplicativo SaaS X"*.

---

## 🔒 Lembrete de Privacidade & Dados
- Nunca utilize informações confidenciais, números de documentos, credenciais reais ou dados de terceiros.
- Todos os chamados e evidências criados devem ser 100% fictícios.
