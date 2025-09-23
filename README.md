Desafio_Modulo_2-Consultoria_Kensey
Projeto de Rede Corporativa - Fictício S/A
Este repositório contém a documentação e os arquivos de simulação para o projeto de modernização e reestruturação da rede corporativa da empresa Fictício S/A, uma companhia do setor de serviços financeiros com múltiplas localidades[cite: 2, 3, 4].

📜 Sobre o Projeto
O projeto visa solucionar a necessidade da Fictício S/A por uma rede mais segura, segmentada, escalável e, acima de tudo, resiliente[cite: 9]. [cite_start]A arquitetura proposta foi desenhada para garantir a continuidade das operações, proteger os dados sensíveis e otimizar a performance de aplicações críticas, alinhando a infraestrutura de TI com os objetivos estratégicos de negócio da empresa[cite: 10, 23].

A solução completa foi simulada no Cisco Packet Tracer para validar o design, as configurações e as políticas de segurança.

📂 Estrutura do Repositório
.
├── 📄 Proposta_Tecnica_FicticioSA.docx
├── 📁 Simulacao_Packet_Tracer/
│   ├── 📍 Matriz_SP.pkt
│   ├── 📍 Filial_RJ.pkt
│   └── 📍 Filial_MG.pkt
├── 📁 Diagramas/
│   ├── Logico_Alto_Nivel.png
│   ├── Fisico_Matriz_SP.png
│   ├── Fisico_Filial_RJ.png
│   └── Fisico_Filial_MG.png
└──  README.md

Proposta_Tecnica_FicticioSA.docx: Documento detalhado com o escopo, objetivos, justificativas e o plano de implementação do projeto[cite: 1].
Simulacao_Packet_Tracer/: Pasta com os arquivos .pkt para simulação no Cisco Packet Tracer.
Diagramas/: Imagens dos diagramas lógicos e físicos da solução implementada[cite: 24, 25].
✨ Principais Características da Solução
A arquitetura de rede proposta implementa as melhores práticas de mercado para garantir um ambiente robusto e seguro:

Alta Disponibilidade (HA): Implementação de Firewalls em cluster e redundância no core da rede para eliminar pontos únicos de falha e garantir a continuidade do negócio.
Segurança Avançada: Uso de Firewall com IDS/IPS, segmentação de rede com VLANs, criação de uma zona desmilitarizada (DMZ) para servidores e isolamento completo da rede Wi-Fi de visitantes.
Conectividade Segura Interunidades: Configuração de VPNs site-to-site (Matriz ↔ Filiais) para garantir a criptografia e a integridade dos dados em trânsito.
Otimização de Tráfego: Políticas de Qualidade de Serviço (QoS) para priorizar aplicações críticas (ERP, CRM, VoIP) e garantir a performance.
Segmentação Lógica: Separação de redes por departamento (Administrativo, Financeiro, TI, Atendimento) para reduzir a superfície de ataque e limitar a propagação de incidentes
Monitoramento Proativo: Estrutura preparada para ferramentas de monitoramento que permitem à equipe de TI agir antes que falhas impactem os usuários.
🌐 Diagrama Lógico da Solução
O diagrama abaixo representa a visão lógica da conectividade entre as unidades e os serviços, centralizados por um perímetro de segurança robusto.

(Diagramas/Logico_Alto_Nivel.png)

🛠️ Como Utilizar
Para explorar os arquivos de simulação, siga os passos abaixo:

Clone este repositório:
git clone [URL_DO_SEU_REPOSITORIO]
Software Necessário:
Cisco Packet Tracer (versão 8.0 ou superior).
Um leitor de arquivos .pdf.
Execução:
Navegue até a pasta Simulacao_Packet_Tracer/.
Abra os arquivos .pkt com o Cisco Packet Tracer para visualizar a topologia, os equipamentos e suas configurações.
Consulte o documento Proposta_Tecnica_FicticioSA.docx para entender todas as justificativas e o racional por trás do projeto.
👤 Autor
Nome: Fernando Andrade
LinkedIn: www.linkedin.com/in/fernando-silva-andrade

*******************************************************************************************************************
<<<<<<< HEAD
=======

>>>>>>> 0f5ea8e (Projeto Final Modulo 2 Kensey Cibersec)
