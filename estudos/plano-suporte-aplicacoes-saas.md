# Plano de estudos: Suporte a Aplicações e Sucesso do Cliente em SaaS — 30 dias

## Meu objetivo

Em 30 dias, construir uma base prática para atuar em Suporte a Aplicações e Sucesso do Cliente em SaaS: reconhecer problemas comuns de hardware, Windows/Linux e conectividade; fazer triagem inicial de chamados; comunicar próximos passos sem jargões; proteger dados; e acompanhar o cliente até confirmar que conseguiu atingir o resultado esperado.

**Ritmo sugerido:** 45–60 min por dia (25–35 min de conteúdo, 15–20 min de prática e 5 min de anotações). Faça os exercícios em dispositivo/ambiente próprio, sem alterar sistemas de produção e sem registrar senhas, tokens ou dados pessoais de clientes.

## Cronograma semanal

### Semana 1 — Hardware e sistemas operacionais (dias 1–7)

- **Dia 1:** componentes do PC: CPU, placa-mãe, RAM, SSD/HDD; desenhe como se relacionam.
- **Dia 2:** sintomas de falha ou lentidão: distinguir memória, armazenamento, temperatura e aplicativo; pratique um checklist de observação segura.
- **Dia 3:** Windows: contas, atualizações, configurações, Gerenciador de Tarefas e Gerenciador de Dispositivos.
- **Dia 4:** Windows: investigar problemas simples de inicialização, espaço em disco e aplicativos; anote evidências antes de sugerir uma ação.
- **Dia 5:** Linux: arquivos e diretórios, terminal, usuários, permissões e processos.
- **Dia 6:** compare tarefas equivalentes no Windows e Linux; pratique explicar cada uma em linguagem simples.
- **Dia 7:** revisão leve: mapa dos componentes + glossário de 10 termos; registre o que ainda confunde.

**Materiais e referências**

- Prioridade DIO: abra a busca indicada e pesquise por “hardware”, “Windows” e “Linux”; o endereço enviado usa o termo `sass`, então troque para `SaaS` quando buscar conteúdo da área. [[1]](https://web.dio.me/play?search=sass)
- DIO — curso Linux Fundamentals, para reforçar o sistema usado em servidores e aplicações. [[2]](https://www.dio.me/en/curso-linux)
- Complemento gratuito — curso de Manutenção de Computadores do IFSul, com conceitos e montagem/configuração de componentes. [[3]](https://mundi.ifsul.edu.br/portal/manutencao-de-computadores.php)

### Semana 2 — Redes e segurança da informação (dias 8–14)

- **Dia 8:** IP, rede local, gateway e DHCP; faça um desenho simples da rede de casa.
- **Dia 9:** DNS: entenda como nomes viram endereços; observe resultados de `ipconfig` e `nslookup` no seu próprio dispositivo.
- **Dia 10:** Wi‑Fi, roteador, cabo e sinal; liste causas prováveis para “sem internet” versus “um aplicativo não abre”.
- **Dia 11:** fluxo de diagnóstico: validar conexão, comparar outros sites/dispositivos e registrar horário; use `ping`/`tracert` apenas na própria rede.
- **Dia 12:** segurança: senhas únicas, gerenciador de senhas, MFA, phishing e princípio do menor privilégio.
- **Dia 13:** atualizações, antivírus, backup e cuidado com dados; escreva o que nunca pediria ao cliente (por exemplo, senha ou código MFA).
- **Dia 14:** simulação: internet funciona, mas o SaaS não abre. Registre hipótese, teste seguro, resultado e quando escalar.

**Materiais e referências**

- Prioridade DIO — curso Fundamentos de Redes de Computadores, cobrindo conceitos de redes e atividade de revisão. [[4]](https://www.dio.me/courses/fundamentos-de-redes-de-computadores)
- DIO — leitura de segurança da informação para discutir atualização e proteção de dispositivos; trate como leitura introdutória e valide procedimentos com a política da empresa. [[5]](https://www.dio.me/articles/seguranca-da-informacao)
- Microsoft Learn — visão geral da Segurança do Windows e seus recursos. [[6]](https://learn.microsoft.com/pt-br/windows/security/operating-system-security/system-security/windows-defender-security-center/windows-defender-security-center)

### Semana 3 — Help desk, atendimento e Customer Success (dias 15–21)

- **Dia 15:** diferencie incidente, solicitação e problema; pratique priorizar por impacto e urgência, respeitando o SLA definido pela equipe.
- **Dia 16:** monte um modelo de chamado: resumo, impacto, início do problema, ambiente, passos para reproduzir, tentativas e resultado — sem dados sensíveis.
- **Dia 17:** escreva uma resposta empática e objetiva: reconhecer o impacto, explicar o próximo passo e combinar quando haverá atualização.
- **Dia 18:** triagem e escalonamento: o que investigar no N1, o que registrar e como entregar contexto útil ao próximo time.
- **Dia 19:** suporte SaaS: investigue navegador/sessão, acesso e permissões; confirme se afeta uma pessoa ou várias antes de atribuir causa.
- **Dia 20:** Customer Success: conecte onboarding, adoção e suporte ao resultado desejado pelo cliente; conheça indicadores como CSAT, resolução no primeiro contato e adoção.
- **Dia 21:** pratique dois casos: escreva um ticket interno e uma atualização para o cliente em português claro.

**Materiais e referências**

- Prioridade DIO — use a busca enviada com os termos “SaaS”, “Customer Success”, “atendimento ao cliente” e “service desk”; selecione aulas que se encaixem no seu nível. [[1]](https://web.dio.me/play?search=sass)
- DIO — artigo sobre Service Desk e atendimento técnico; use como leitura complementar para discutir fluxo de chamados. [[7]](https://www.dio.me/articles/como-a-inteligencia-artificial-esta-transformando-o-suporte-tecnico-e-o-service-desk-6cce88c50986)
- Salesforce — visão de Customer Success em SaaS e foco no resultado do cliente. [[8]](https://www.salesforce.com/br/blog/customer-success-saas)

### Semana 4 — Integração e prática de suporte SaaS (dias 22–30)

- **Dia 22:** simule falha de login: diferencie credencial, MFA, permissão e indisponibilidade; nunca peça senha ou código.
- **Dia 23:** simule lentidão: compare navegador/dispositivo/rede e impacto em outros usuários; documente horário e passos para reproduzir.
- **Dia 24:** simule falha de conectividade: aplique o checklist de rede e prepare uma atualização curta para o cliente.
- **Dia 25:** simule suspeita de phishing ou exposição de dados: interrompa ações arriscadas, preserve evidências permitidas e escale conforme procedimento.
- **Dia 26:** faça revisão prática: escolha uma atividade de Linux, uma de Windows e uma de redes e explique o que cada evidência indica.
- **Dia 27:** escreva um artigo curto de base de conhecimento: problema, público afetado, passos seguros, resultado esperado e quando abrir chamado.
- **Dia 28:** priorize três chamados fictícios por impacto/urgência; justifique a ordem e escreva o primeiro retorno para cada cliente.
- **Dia 29:** capstone: resolva um caso fictício de cliente sem acesso ao SaaS, do primeiro contato ao escalonamento/solução e confirmação de sucesso.
- **Dia 30:** autoavaliação: revise suas notas, liste três pontos fortes e três lacunas; defina o próximo tema de aprofundamento.

**Materiais e referências**

- Prioridade DIO — retome a busca da plataforma com “SaaS”, “service desk”, “redes”, “Linux” e “segurança da informação”; aplique as aulas escolhidas aos casos simulados. [[1]](https://web.dio.me/play?search=sass)
- DIO — leitura sobre suporte a usuários em contexto corporativo, útil para praticar orientação sem jargão. [[9]](https://www.dio.me/articles/o-analfabetismo-digital-no-corporativo-o-desafio-do-suporte-de-ti-com-novos-colaboradores-7ea5f03a4ea9)
- Consulte novamente o curso de redes e o conteúdo de Segurança do Windows da semana 2 para fundamentar seus checklists. [[4]](https://www.dio.me/courses/fundamentos-de-redes-de-computadores) [[6]](https://learn.microsoft.com/pt-br/windows/security/operating-system-security/system-security/windows-defender-security-center/windows-defender-security-center)

## Entrega final

Guarde três artefatos sem dados reais: (1) checklist de triagem de conectividade, (2) modelo de ticket com atualização ao cliente e (3) artigo de base de conhecimento para um problema SaaS fictício. Esses exemplos podem compor um portfólio de aprendizagem.

> **Privacidade e personalização:** e-mails e Google Drive não foram consultados nesta versão porque essas integrações não estavam conectadas. O plano usa apenas os tópicos fornecidos e referências públicas; nenhum dado pessoal foi incluído.
>