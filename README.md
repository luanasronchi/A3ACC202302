# Avaliação A3: Ambientes Computacionais e Conectividade 2023-2

## 20% Primeira Etapa: Topologia
○ Início: 17/11 | Entrega: 23/11
## 30% Segunda Etapa: Segmentação de Redes (15%) e Configuração de VLAN
(15%)
○ Início: 23/11 | Entrega: 30/11
## 30% Etapa Final: Configuração de Servidores HTTP (10%), DHCP (10%), DNS
(10%).
○ Início: 01/12 | Entrega: 07/12
Desenvolva uma infraestrutura de rede corporativa com a capacidade para até 512
endereços, dividida em duas sub-redes que representam duas filiais com diferentes
localizações em uma região metropolitana.
Rede (MAN):
## Capacidade total: 512 endereços.
Sub-rede: Filial A (LAN):
## Capacidade: Até 254 endereços.
Sub-redes:
1. Setor de Suporte ao Cliente:
Capacidade: Até 128 endereços.
Configuração de VLAN.
2. Setor de Desenvolvimento de Software:
Capacidade: Até 64 endereços.
Configuração de VLAN.
3. Setor Comercial:
Capacidade: Até 32 endereços.
Configuração de VLAN.
4. Central de Processamento de Dados (Datacenter):
Capacidade: Até 32 endereços.
Configuração de VLAN.
Servidores:
Servidor HTTP.
Servidor DNS.
Servidor DHCP.
Servidor SMTP.
Opcional: Configuração de NAT para
redirecionamento de portas para DNS, HTTP,
Email (DMZ).
## Sub-rede: Filial B (LAN):
Capacidade: Até 254 dispositivos.
## Sub-redes internas:
1. Setor Administrativo:
Capacidade: Até 128 dispositivos.
Configuração de VLAN.
2. Rede Sem Fio:
Capacidade: Até 128 dispositivos.
Configuração de VLAN.
## Conectividade:
Cada filial deve se conectar com 2 ISPs.
## Configuração ISP A:
Rotas internas anunciadas usando OSPF (intraAS).
Roteamento interAS: Configurar anúncio de rotas BGP.
## Configuração ISP B:
Rotas internas anunciadas usando OSPF (intraAS).
Roteamento interAS: Configurar anúncio de rotas BGP.