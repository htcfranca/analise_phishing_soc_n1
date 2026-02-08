Análise de Incidente de Phishing — SOC N1

Visão Geral

Este projeto simula a atuação de um Analista de SOC Nível 1 (N1) em um cenário realista de incidente de phishing. O foco está na triagem inicial, análise de evidências, identificação de indicadores de comprometimento (IOC), classificação do incidente e documentação técnica, seguindo boas práticas operacionais de um SOC.
________________________________________
Objetivo do Projeto

Demonstrar as responsabilidades de um SOC N1, incluindo: 
- Análise de e-mail suspeito reportado por usuário
- Identificação de indicadores de comprometimento (IOC)
- Classificação do incidente por tipo, severidade e impacto
- Registro técnico claro e rastreável do incidente
________________________________________
Contexto do Papel no SOC

Nível do SOC: N1 (Tier 1)

Como Analista SOC N1, este projeto demonstra: 
- Detecção inicial e triagem de eventos de segurança
- Identificação de padrões suspeitos e IOC
- Classificação adequada do incidente
- Recomendações de encaminhamento e mitigação
Ações avançadas de resposta e remediação estão fora do escopo do N1 e, portanto, não são abordadas.
________________________________________
Resumo do Incidente
- Tipo de Incidente: Phishing
- Origem: E-mail reportado por usuário
- Usuários Afetados: 1
- Severidade: Média
- Impacto: Potencial (não houve interação com o link malicioso)
- Status: Incidente confirmado
________________________________________
Evidências Coletadas
Detalhes do E-mail: 
- Remetente: suporte@empresa-atualizacao.com
- Assunto: Ação necessária: Atualização de segurança
- Conteúdo da Mensagem: > Detectamos atividade incomum em sua conta. Para evitar bloqueio, atualize sua senha imediatamente.
- Link presente na mensagem: http://empresa-segura-login[.]com
Nenhum link foi acessado durante a análise.
________________________________________
Análise Realizada
O e-mail foi analisado com base nos seguintes critérios: 
- Legitimidade do domínio do remetente
- Uso de linguagem de urgência e engenharia social
- Solicitação de informações sensíveis
- Estrutura genérica da mensagem

Resultados da Análise
•	Domínio do remetente não oficial
•	Linguagem de alta pressão para induzir ação imediata
•	Tentativa de coleta de credenciais por meio de URL externa
Essas características são consistentes com uma tentativa de phishing.
________________________________________
Indicadores de Comprometimento (IOC)
Tipo	Descrição
URL	empresa-segura-login[.]com
Domínio	empresa-atualizacao.com
Técnica	Engenharia social
Padrão de linguagem	Urgência / ameaça de bloqueio
________________________________________
Classificação do Incidente
•	Categoria: Phishing
•	Severidade: Média
•	Nível de Impacto: Potencial
•	Classificação: Incidente confirmado
________________________________________
Ações Realizadas (SOC N1)
•	Análise do conteúdo do e-mail
•	Identificação dos IOC
•	Classificação do incidente
•	Registro técnico do incidente
________________________________________
Ações Recomendadas
•	Bloqueio do domínio e da URL identificados
•	Orientação ao usuário afetado
•	Comunicação preventiva aos demais usuários
•	Monitoramento de novos incidentes semelhantes
________________________________________
Conclusão
O e-mail analisado apresenta características típicas de phishing, utilizando técnicas de engenharia social e direcionamento para URL maliciosa. Não foram identificadas evidências de comprometimento do usuário no momento da análise.
Este projeto demonstra a atuação prática e o raciocínio esperado de um Analista SOC N1 durante o tratamento inicial de incidentes de segurança.
________________________________________
Competências Demonstradas
•	Triagem de eventos de segurança
•	Detecção de phishing
•	Identificação de IOC
•	Classificação de incidentes
•	Documentação técnica
•	Fluxo operacional de SOC
________________________________________
👩‍💻 Autora

Hortência França de Souza

Analista de Cibersegurança | Analista SOC Júnior
