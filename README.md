# Conteúdo relacionado ao curso Arquitetura de Redes

- Professor Gabriel Torres - plataforma Udemy

## Cabeamento de Rede

### Cabo coaxial

Formado por dois condutores
    - condutor central, fio rígido de cobre que fica ao centro do cabo.
    - camada protetora de plástico.
    - malha eletromagnética, contra interferências eletromagnéticas.

Caractéristica técnica

- Impedância

`Impedância elétrica ou simplesmente impedância, é a oposição que um circuito elétrico faz à passagem de corrente quando é submetido a uma tensão.`

Não são compatíveis

- Tv a cabo utilizam desse tipo de cabo.
   - em uso
   - 75 ohms

---

- Ethernet - redes locais (lan)
   - obsoleto
   - 50 ohms
   - Conector BNC

- Tipo de transmissão (banda base)

Cabo fino - Thinnet - 10BASE2

Cabo grosso - Thicknet - 10 BASE5

Largura de banda, em Mbit/s

Comprimento máximo do cabo 

2 = 165 metros

5 = 500 metros

---

### Par trançado

- Formado por um par de fios trançados, totalizando quatro pares de fio.

- Menos proteção contra intereferência eletromagnética.

- Transmissão diferencial

   - D + | D - (espelhamento)

UTP (Unshielded Twisted Pair) - sem blindagem

STP (Shielded Twisted Pair) - com blindagem

Blindagem geral ou individual, com alumínio ou malha

- Conector 8P8C ("RJ-45")

- Categoria mais comum - 5e - 2,5 Gbit/s

- Comprimento máximo 90 - 100 metros 

- 10BASE-T (Largura de banda, em Mbit/s ou Gbit/s)

- Tipo de transmissão (banda base)

- Tipo do cabo (T = Twisted pair, par trançado)

### Fibra Óptica

- Mais rápido e mais avançado que existe.

Óptica - visão
Ótica - ouvido

- Utiliza de sinais luminosos invés de sinais elétricos

- Vidro ou plástico

- laser (light amplification by stimulated emission - amplificação de luz através de emissão estimulada de radiação)

Núcleo

- Monomodo (SMF) 
   - linha reta no meio da fibra 
   - 9/125 (diâmetro / revestimento)
   - mais cara 
   - distância longa
   - maior largura de banda
   - comprimento de onda maior

- Multimodo (MMF) 
   - dispersão modal 
   - recochetiar 
   - índice degrau (dispersão maior) 
   - índice gradual (dispersão menor) - 50/125 | 62,5/125 
   - mais barata 
   - distância curta
   - menor largura de banda
   - comprimento de onda menor

- comprimento de onda (infravermelho - invisível ao olho humano).

- Conector 

   - MT-RJ - multimodo

   - SC | ST | LC

- 1000BASE-LX largura de banda, tipo de transmissão, tipo de fibra (Long) = monomodo | F ou S (short) = multimodo

### Cabeamento estruturado 

1 - entrada do prédio (conexão com o mundo externo)

2 - sala de equipamento (armazena os equipamentos - servidores)

3 - Cabeamento vertical = Backbone

4 - Sala de telecomunicação

5 - Cabeamento horizontal

6 - Área de trabalho

---

#### Questões

`1 - d | 2 - e | 3 - e | 4 - c | 5 - e`

`1 - V | 2 - a | 3 - c | 4 - c | 5 - c | 6 -`

`1 - d | 2 - a | 3 - b | 4 - e` 

---

## Equipamentos de rede

### Interface de rede (NIC) 

- porta de rede
- placa de rede
- NIC (Network Interface Card ou Controller)

- Permite a conexão entre o equipamento e a rede.

- A Interface de rede pode receber um endereço físico (endereço MAC)
- Nem toda porta de rede tem endereço físico

- Placa de expansão (placa de rede) 

- Switches e hubs não recebem um endereço físico (MAC)

Referência

https://www.cisco.com/c/en/us/about/brand-center/network-topology-icons.html

---

### Hubs e repetidores

- hubs
   - equipamentos concentradores - topologia física em estrela
   - camada 1 modelo ISO/OSI - física
   - não tem controle de tráfego
   - obsoleto
   - não seguro

- repetidores
   - expande o comprimento da rede (cabo coaxial)

---

### Switches e pontes

- equipamentos concentradores - topologia em estrela no nível físico e lógico
- camada 2 modelo ISO - link de dados
- analisa o tráfegos na rede
- fase de aprendizados (inundação - flooding)

- pontes
   - cabo coaxial
   - expande o comprimento da rede
   - isola os quadros, consegue ler os endereços 

---

## Roteadores e switches camada três

- roteadores

   - camada 3 - modelo OSI - rede - endereçamento lógico IP
   - wan (externa) / lan (interna)

-switches

   - lan (rede interna)
   - conexão com duas redes internas
   - não tem conexão com rede externa