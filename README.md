# Security-EternalBlue-Bluekeep

# Relatório de Segurança da Informação em Ambiente Interno com Kali Linux

Este repositório contém o relatório completo do projeto acadêmico desenvolvido no curso de Sistemas de Informação do Centro Universitário UNIFACISA, cujo objetivo principal foi realizar uma análise detalhada da segurança em ambiente interno utilizando ferramentas avançadas de testes de penetração.

## Sobre o Projeto

O foco deste trabalho foi avaliar a segurança de máquinas virtuais configuradas para simular um ambiente vulnerável, explorando falhas críticas de segurança conhecidas, como as vulnerabilidades **EternalBlue (CVE-2017-0144)** e **BlueKeep (CVE-2019-0708)** em sistemas operacionais Windows 7.

Utilizamos o Kali Linux como plataforma principal para realizar:

- Varreduras de rede e detecção de vulnerabilidades (com Nmap).
- Exploração das vulnerabilidades usando o Metasploit Framework.
- Análise dos impactos e riscos de segurança decorrentes dessas falhas.
- Proposição de soluções e boas práticas para mitigar os riscos identificados.

## Metodologia

O ambiente de testes foi montado com duas máquinas virtuais:

- **Máquina Atacante:** Kali Linux, equipada com ferramentas como Metasploit e Nmap para realizar ataques simulados.
- **Máquina Alvo:** Windows 7 SP1, configurada com falhas conhecidas, incluindo o protocolo SMBv1 ativo e o serviço RDP habilitado, para simular ambientes vulneráveis.

Foram realizados testes práticos para explorar as vulnerabilidades EternalBlue e BlueKeep, com documentação detalhada das etapas, comandos utilizados e resultados obtidos.

## Principais Resultados

- Exploração bem-sucedida da vulnerabilidade EternalBlue, que permitiu acesso remoto e controle total do sistema alvo via protocolo SMB.
- Identificação da vulnerabilidade BlueKeep no serviço RDP, demonstrando riscos críticos, como falhas graves no sistema (BSOD).
- Demonstração da importância da aplicação constante de patches e atualizações de segurança para prevenção desses ataques.
- Elaboração de recomendações técnicas, incluindo desativação do SMBv1, implementação de autenticação multifatorial (MFA), uso de VPN para acesso remoto e monitoramento de rede.

## Recomendações e Boas Práticas

O relatório destaca a necessidade de uma postura proativa em segurança da informação, incluindo:

- Atualização contínua dos sistemas e softwares.
- Monitoramento e análise de tráfego suspeito na rede.
- Implementação de controles de acesso robustos, como MFA e VPN.
- Capacitação de equipes técnicas para prevenção e resposta a incidentes.

## Equipe

- Alisson Deivison Silva Pereira – Documentação Inicial  
- David Mickael Chaves de Moraes – Análise de Vulnerabilidades  
- Iago José Ramos Borges – Teste de Penetração e Exploits  
- José Lucas Bringel Leite – Coleta e Análise de Evidências  
- Gabriely Vitoria Rodrigues Couto – Coleta e Análise de Evidências  
- Yanna Aparecida dos Santos Ferreira – Relatório Final e Recomendações  

## Referência

Relatório desenvolvido para a disciplina de Segurança da Informação ministrada pelo docente Cleisson Christian Lima da Costa Ramos, UNIFACISA, Campina Grande, 2025.
