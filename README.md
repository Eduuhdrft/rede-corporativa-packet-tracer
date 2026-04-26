# Rede Corporativa — Cisco Packet Tracer

Topologia de rede completa simulando uma instituição de ensino.

## Topologia
- SW L3 Core com roteamento inter-VLAN
- 3 VLANs (Desktops, WiFi, Servers)
- 6 switches de acesso por setor
- 6 roteadores WiFi com DHCP
- Servidor DHCP/DNS
- Servidor RADIUS/AAA
- Conexão WAN

## Endereçamento IP
| Rede | Endereço |
|------|----------|
| VLAN 1 Desktops | 192.13.1.0/24 |
| VLAN 2 WiFi | 192.13.2.0/24 |
| VLAN 3 Servers | 192.13.3.0/24 |
| WAN | 200.13.0.0/30 |

## Como abrir
1. Instale o Cisco Packet Tracer
2. Abra o arquivo .pkt
