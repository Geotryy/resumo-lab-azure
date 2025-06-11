# Resumo do Lab – Microsoft 50 Anos: Computação em Nuvem com Azure

Este repositório contém o resumo das lições aprendidas durante o laboratório prático realizado no bootcamp "Microsoft 50 Anos - Computação em Nuvem com Azure", oferecido pela DIO em parceria com a Microsoft.

---

## O que eu aprendi

Durante este lab, explorei diversos conceitos fundamentais sobre computação em nuvem com foco na plataforma Microsoft Azure. Aqui estão os principais tópicos que aprendi:

### SSH (Secure Shell)
- É um protocolo que permite acesso remoto seguro a máquinas Linux.
- O acesso é feito via linha de comando, utilizando a porta 22.
- Permite gerenciar servidores mesmo à distância, com criptografia.

### RDP (Remote Desktop Protocol)
- Usado para acessar máquinas Windows com interface gráfica.
- A conexão é feita pela porta 3389.
- Permite visualizar a área de trabalho da VM remotamente, como se fosse um PC normal.

### NSG (Network Security Group)
- Atua como um firewall básico de rede no Azure.
- Permite criar regras de entrada e saída baseadas em IP e porta.
- É usado para controlar quem pode acessar uma máquina virtual.

### Azure Bastion
- Serviço gerenciado que permite acesso seguro às VMs via navegador, sem expor IPs públicos.
- Elimina a necessidade de abrir portas como 22 ou 3389 na internet.
- Mais seguro e prático do que usar um Jump Server.

### Jump Server
- É uma VM intermediária usada para acessar outras máquinas privadas.
- Requer configuração manual e tem exposição pública.
- Azure Bastion é uma evolução mais segura desse conceito.

---

## Conclusão

Esse lab foi essencial para entender os primeiros passos na gestão de máquinas virtuais e segurança de rede na nuvem. Aprender a usar ferramentas como SSH, RDP, NSG e Azure Bastion me deu uma base prática sobre como proteger e acessar recursos no Azure com mais eficiência.

Este repositório foi criado como parte da conclusão do desafio da DIO.

---

## Autora

Feito por Geovanna Dias  
Bootcamp: Microsoft 50 Anos - Computação em Nuvem com Azure  
LinkedIn: linkedin.com/in/geosdias

