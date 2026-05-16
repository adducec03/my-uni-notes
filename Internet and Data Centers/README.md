# Internet and Data Centers
### Laurea Magistrale in Ingegneria Informatica | Università degli Studi Roma Tre

Questo spazio contiene il materiale didattico, gli appunti e le esercitazioni relative all'architettura di Internet, alle tecnologie di routing e ai data center.

---

## Indice del Corso

Il programma affronta l'infrastruttura di rete, dal routing intra-dominio e inter-dominio fino ai servizi distribuiti su larga scala:

### 1. Introduzione
* **Presentazione del corso**
* **Internet, Data Center e Cloud:** Introduzione alla struttura di Internet e al rapporto tra Internet, Data Center e Cloud
* **Infrastruttura nazionale:** Il Polo Strategico Nazionale e il Sistema Pubblico di Connettività

### 2. Metodologie e Tecnologie di Routing
* **Routing di livello tre:**
    * Generalità sugli algoritmi di instradamento per l'infrastruttura di rete fissa
    * Algoritmi Distance Vector
    * Algoritmi Link-State-Packet
    * Protocolli di instradamento
* **Routing di livello due:**
    * Calcolo dello spanning tree in reti con switch
    * VLAN: reti locali virtuali
    * Evoluzione dello spanning tree protocol
    * Software Defined Networks
    * Network Address Translation (NAT)

### 3. IPv6
* **Protocollo:** Indirizzamento e aspetti di base del protocollo IPv6
* **ICMPv6:** Meccanismi di controllo e diagnostica
* **Multihoming:** Source address selection e multihoming
* **Transizione:** Meccanismi di transizione IPv4-IPv6

### 4. Routing Interdominio
* **BGP:** Border Gateway Protocol, BGP pitfalls e scalabilità
* **Gerarchia di Internet:** La gerarchia di Internet e anomalie in Internet
* **Sicurezza del routing:** Introduzione ad RPKI (trasparenze del RIPE NCC)
* **MPLS:** Routing di un ISP basato su MPLS

### 5. TCP e Trasmissioni Efficienti
* **Servizi interattivi:** Efficienza di TCP nei servizi interattivi
* **Controllo di congestione:** TCP e controllo di congestione, self-clocking, prodotto banda-latenza, AIMD
* **BBR:** Tecniche moderne per la gestione della banda

### 6. Routing nei Data Center
* Routing nei data centers

### 7. Servizi Web e Content Delivery
* **Architetture e algoritmi:** Modelli e algoritmi per servizi basati sul Web
* **Distribuzione:** Distribuzione locale e distribuzione globale
* **CDN:** Content delivery networks

---

## Esercizi

### Routing Intra-dominio
* FFRouting Introduction
* RIP with FFRouting
* OSPF with FRRouting

### Routing Inter-dominio
* BGP Simple Peering FRR
* BGP Announcement FRR
* Prefix Filtering
* Stub AS
* Stub AS Static
* Multi-homed Stub AS
* Multi-homed Stub AS Large
* Multi-homed AS
* Web server
* Errori nelle configurazioni
* Transit

### Data Centers
* Architettura data centers
* Data Center Routing using FRR
* Data Center VXLAN

---

##  Struttura della Repository

* `/sections`: Appunti teorici divisi per capitoli.
* `/ex`: Esercitazioni pratiche con Katharà su routing e data center.

---

## ?? Risorse Utili

* **Ambiente di laboratorio:** [Katharà](https://www.kathara.org/) per la simulazione di reti e protocolli di routing.
* **Documentazione:** Materiale di riferimento del corso e slide ufficiali.
