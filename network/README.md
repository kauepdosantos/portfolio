📡 Packet Tracer Project - VLANs + Routing + Network Services

This project simulates a corporate network using Cisco Packet Tracer, featuring VLAN segmentation, inter-VLAN routing (router-on-a-stick), and implementation of essential network services.

🧠 Objective

Demonstrate practical knowledge in:

VLANs
Inter-VLAN routing
Network services
Access control (ACL)
Remote access via SSH

🏗️ Topology

The network is segmented into 3 VLANs:

VLAN 10 → Administration
VLAN 20 → Finance
VLAN 30 → Guests

A router is used to enable communication between VLANs using the Router-on-a-Stick method.

🔀 Routing

Inter-VLAN routing is configured using subinterfaces on the router:

G0/0.10 → VLAN 10
G0/0.20 → VLAN 20
G0/0.30 → VLAN 30

Each subinterface uses 802.1Q encapsulation.

🌐 Network Services

A central server is configured with the following services:

DHCP → Automatic IP address assignment for VLANs
HTTP → Web hosting
DNS → Name resolution
FTP → File transfer
TFTP → Backup and configuration transfer

🔐 Security

ACL (Access Control List)

A security rule was implemented to restrict access:

❌ VLAN 30 cannot access VLAN 20

This simulates a scenario where guest users are restricted from accessing sensitive internal resources.

🔑 Remote Access

The router is configured for secure remote access using:

SSH (Secure Shell)

Allowing secure remote administration.

🛠️ Technologies Used
Cisco Packet Tracer
VLAN (802.1Q)
Router-on-a-Stick
DHCP, DNS, HTTP, FTP, TFTP
ACL
SSH

🚀 Notes

This project was developed for learning and practice purposes, and is suitable for demonstrating basic networking and infrastructure skills in a simulated environment.

---


📡 Projeto Packet Tracer - VLANs + Roteamento + Serviços de Rede

Este projeto simula uma rede corporativa utilizando o Cisco Packet Tracer, com segmentação por VLANs, roteamento inter-VLAN (router-on-a-stick) e implementação de serviços essenciais de rede.

🧠 Objetivo

Demonstrar conhecimentos práticos em:

VLANs
Roteamento inter-VLAN
Serviços de rede
Controle de acesso (ACL)
Acesso remoto via SSH

🏗️ Topologia

A rede foi segmentada em 3 VLANs:

VLAN 10 → Administração
VLAN 20 → Financeiro
VLAN 30 → Visitantes

Um roteador foi utilizado para permitir a comunicação entre VLANs utilizando o método Router-on-a-Stick (Roteamento Palito).

🔀 Roteamento

Foi configurado roteamento inter-VLAN com subinterfaces no roteador:

G0/0.10 → VLAN 10
G0/0.20 → VLAN 20
G0/0.30 → VLAN 30

Cada subinterface possui encapsulamento 802.1Q.

🌐 Serviços de Rede

Um servidor central foi configurado com os seguintes serviços:

DHCP → Distribuição automática de IPs para as VLANs
HTTP → Hospedagem de página web
DNS → Resolução de nomes
FTP → Transferência de arquivos
TFTP → Backup e transferência de configurações

🔐 Segurança

ACL (Access Control List)

Foi criada uma regra de segurança para restringir acessos:

❌ VLAN 30 não pode acessar a VLAN 20

Isso simula um cenário onde visitantes não têm acesso à rede interna sensível.

🔑 Acesso Remoto

O roteador foi configurado para acesso remoto seguro via SSH, permitindo administração remota com autenticação segura.

🛠️ Tecnologias Utilizadas
Cisco Packet Tracer
VLAN (802.1Q)
Router-on-a-Stick
DHCP, DNS, HTTP, FTP, TFTP
ACL
SSH

🚀 Observações

Este projeto foi desenvolvido com fins de aprendizado e prática em redes, sendo ideal para demonstrar habilidades básicas de infraestrutura em ambientes simulados.
