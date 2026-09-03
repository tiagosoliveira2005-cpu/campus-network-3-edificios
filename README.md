# 🏢 Campus Network — Empresa com 3 Edifícios

Projeto de rede empresarial simulado no **Cisco Packet Tracer**, desenvolvido para estudo de redes de campus (Campus Network Design) e para portefólio.

## 📌 Descrição

Simulação de uma infraestrutura de rede corporativa distribuída por **3 edifícios**, seguindo o modelo hierárquico de rede em **três camadas**:

- **Core Layer** — backbone de alta velocidade, interligando os edifícios
- **Distribution Layer** — agregação de tráfego, roteamento entre VLANs, redundância
- **Access Layer** — ligação dos dispositivos finais (portas de acesso)

## ⚙️ Tecnologias e Protocolos Implementados

| Categoria | Tecnologia |
|---|---|
| Segmentação de rede | VLANs |
| Redundância de camada 2 | STP (Spanning Tree Protocol) |
| Routing | OSPF (Open Shortest Path First) |
| Redundância de gateway | FHRP em SVIs (ex: HSRP/VRRP) |
| Agregação de links | EtherChannel |
| Ligação entre switches | Trunk Ports |
| Ligação a dispositivos finais | Access Ports |
| Atribuição de IP | DHCP |

## 🗂️ Estrutura da Rede

- 3 edifícios interligados via camada Core
- Cada edifício com a sua própria segmentação por VLANs
- Redundância de links entre switches (STP) e entre gateways (FHRP)
- Ligações agregadas (EtherChannel) para maior largura de banda e tolerância a falhas
- Atribuição dinâmica de endereços IP via DHCP

## 🎯 Objetivo do Projeto

Este projeto foi desenvolvido como exercício prático de estudo de **arquitetura de redes empresariais (Campus Network Design)**, aplicando conceitos fundamentais de redes hierárquicas, redundância e segmentação — conteúdos alinhados com certificações como o **CCNA**.

## 🛠️ Como abrir o projeto

1. Instalar o [Cisco Packet Tracer](https://www.netacad.com/courses/packet-tracer) (gratuito, requer conta NetAcad)
2. Abrir o ficheiro `.pkt` incluído neste repositório

## 📁 Ficheiros

- `Projeto_1_-_Empresa_com_3_edificios_Campus_Network.pkt` — ficheiro do projeto Packet Tracer

---

*Projeto desenvolvido para fins de estudo e portefólio profissional.*
