
Target Enumeration and Vulnerability Scanner

Este script em Python automatiza a coleta de subdomínios e a análise de segurança de um domínio específico, utilizando as ferramentas Amass, Nmap e Nuclei.

Funcionalidades:

Amass: Enumera subdomínios do domínio de destino e salva os resultados em um arquivo de texto.

Nmap: Realiza uma varredura de portas abertas em todo o domínio e seus subdomínios.

Nuclei: Executa uma análise de vulnerabilidades em cada domínio/subdomínio usando templates específicos.

Fluxo de Trabalho:

O usuário insere o domínio alvo.
O script executa Amass para coletar subdomínios, seguido por Nmap para escanear portas abertas e Nuclei para análise de vulnerabilidades.
O usuário pode optar por usar os resultados do Amass para novas execuções de Nmap e Nuclei nos subdomínios descobertos.

Arquivos de Saída:

Cada etapa salva seus resultados em arquivos específicos para facilitar a análise posterior.

Este script é ideal para testes de segurança iniciais, simplificando o processo de enumeração de subdomínios e identificação de vulnerabilidades em um alvo.
