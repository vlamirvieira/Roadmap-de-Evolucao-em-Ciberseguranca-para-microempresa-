# Roadmap-de-Evolucao-em-Ciberseguranca-para-microempresa-
Este projeto para o GitHub foi estruturado como um guia evolutivo, transformando a visão básica de segurança de um microempreendedor em uma postura de defesa corporativa resiliente. O foco é a Maturidade Cibernética, partindo de ferramentas nativas até sistemas avançados de monitoramento.
Objetivo
Orientar o crescimento da infraestrutura de segurança de forma escalável, permitindo que o empreendedor compreenda não apenas as ferramentas, mas o comportamento dos ataques e como interrompê-los.
🚀 Fases do Projeto
Fase 1: O Usuário Comum (Proteção de Endpoint)
Nesta etapa, o foco é a defesa automática para quem utiliza apenas um computador pessoal.
•	Ferramentas: Microsoft Defender Antivirus e Microsoft Defender Offline.
•	Alcance: Proteção contra ameaças conhecidas (malwares, ransomwares e cavalos de troia).
•	Ação Crítica: Utilizar o modo Offline para verificar o disco antes do Windows ser carregado, sendo essencial para detectar e remover malwares persistentes como rootkits e bootkits que tentam se esconder durante a execução do sistema.
Fase 2: A Investigação Ativa (Visão EDR)
A evolução ocorre quando a ferramenta deixa de ser apenas um antivírus reativo e passa a agir como uma "caixa-preta" gravadora.
•	Ferramenta: Microsoft Defender for Endpoint (MDE).
•	Capacidades: Permite investigar a árvore de processos (qual programa iniciou o malware), alterações em chaves de registro e conexões de rede.
•	Defesa Avançada: Detecção de ataques de Zero-Day (ameaças desconhecidas pelo fabricante) através da identificação de comportamentos suspeitos, como a desativação de recursos de segurança ou criação inesperada de scripts.
Fase 3: A Instalação Corporativa (SIEM e Monitoramento)
Nível máximo de maturidade, onde os dados são centralizados para uma visão holística de toda a empresa.
•	Wireshark (A Lente de Aumento): Ferramenta cirúrgica para analisar o tráfego de rede no nível mais profundo (DNA da conexão) através da captura de pacotes brutos.
•	Splunk (A Torre de Controle): Atua como um satélite que ingere logs do Wireshark, Firewalls e do Defender, usando inteligência artificial para cruzar bilhões de dados e alertar sobre cenários macro de ameaças.
________________________________________
🧠 Estruturas de Gestão e Defesa
Para sustentar essa evolução, o projeto deve adotar frameworks de mercado:
1.	CIS Controls (Os 18 Controles): Responde à pergunta: "Quais medidas devo implementar para me proteger?" (ex: inventário de ativos e controle de acesso).
2.	Cyber Kill Chain: Modelo que descreve as 7 etapas de um ataque, permitindo que o analista identifique em qual fase interrompê-lo.
3.	MITRE ATT&CK: Matriz que categoriza as táticas e técnicas dos adversários, ajudando a priorizar esforços e aprimorar a detecção de padrões suspeitos.
________________________________________
📖 O Tradutor de Cibersegurança (Glossário Prático)
Seção dedicada a facilitar a comunicação para o microempreendedor através de analogias:
•	Domínio: O nome de uma pessoa ("Maria").
•	IP: O endereço da casa da Maria.
•	Hash: A impressão digital de um documento; se um único bit mudar, a digital muda, provando que o arquivo foi alterado.
•	O Usuário Sentinela: O papel do usuário comum que, ao notar comportamentos estranhos, avisa a TI e fecha a "janela de oportunidade" do invasor.
________________________________________
⚖️ Gestão de Riscos
O projeto orienta o empreendedor a classificar seus dados (Públicos, Privados, Confidenciais e Restritos) e decidir como lidar com os riscos encontrados: Evitar, Mitigar, Transferir ou Aceitar.
Como o Modelo Diamante ajuda a explicar ataques para leigos?
Como usar a Pirâmide da Dor para priorizar minhas defesas?
Quais são as limitações atuais do modelo Cyber Kill Chain?

