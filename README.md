# 📘 Project Symbiosis: Neo-Kanto 2077

> **Classificação:** USO RESTRITO // OPERATIVOS AUTORIZADOS
> **Sistema Base:** Savage Worlds (Edição Aventura - SWADE)

![Status](https://img.shields.io/badge/Status-In_Development-cyan)
![System](https://img.shields.io/badge/System-Savage_Worlds-red)
![Setting](https://img.shields.io/badge/Setting-Cyberpunk_Solarpunk-green)

## 🌐 Visão Geral

**Project Symbiosis** é uma reimaginação tática, adulta e futurista do universo de captura de monstros. Ambientado em **Neo-Kanto no ano de 2077**, o jogo abandona a fantasia infantil de "temos que pegar" para focar em ética, tática militar e sobrevivência econômica.

[cite_start]Neste mundo, a tecnologia de **Pokébolas foi banida** por ser considerada tortura digital[cite: 96, 204]. Os jogadores assumem o papel de **Operativos** que utilizam o sistema **S.Y.N.C.** (Synchronized Neural Connection) para formar parcerias biológicas com criaturas, agora chamadas de **Bio-Ativos**.

### A Filosofia
* [cite_start]**Conexão acima de Coleção:** Ter um Pokémon é uma responsabilidade logística e financeira imensa[cite: 102].
* **Autopreservação:** A IA dos Bio-Ativos é realista. [cite_start]Se ordenados a cometer suicídio tático, o Link Neural se rompe e eles fogem[cite: 104].
* [cite_start]**O Inimigo Real:** O Cartel Rocket utiliza "Slave-Balls" ilegais que fritam os inibidores de dor das criaturas, criando máquinas de matar sem consciência [cite: 208-209].

---

## ⚙️ Mecânicas Principais (Adaptação SWADE)

O sistema utiliza o motor **Savage Worlds Adventure Edition** com modificações pesadas para simular a letalidade e a tática do cenário.

### 1. Conversão de Dados (Data-to-Dice)
[cite_start]Utilizamos os stats base da espécie (0-255) para definir os dados de RPG[cite: 111].

| Valor do Stat | Dado (SWADE) | Classificação |
| :--- | :--- | :--- |
| **00 - 45** | `d4` | Civil / Frágil |
| **46 - 80** | `d6` | Padrão / Competente |
| **81 - 110** | `d8` | Atlético / Forte |
| **111 - 140** | `d10` | Elite / Brutal |
| **141 - 170** | `d12` | Ápice Biológico |
| **171+** | `d12 + X` | Anomalia / Lendário |

* [cite_start]**Defesa (Defense):** Convertida em Armadura Natural (`+0` a `+6`) somada à Resistência [cite: 120-121].

### 2. Ciclo de Evolução (Bio-Data)
Não existe XP tradicional. [cite_start]A evolução é baseada na coleta de **Bio-Data (BD)** [cite: 10-11].
* [cite_start]**Avanço:** A cada **5 BD**, o Bio-Ativo ganha um upgrade (Perícia, Vantagem ou Atributo)[cite: 13].
* [cite_start]**Patamares:** De **Novato** (Nvl 1-20) a **Lendário** (Nvl 81+), desbloqueando capacidades físicas e ultimates [cite: 122-124].

### 3. Sistema de Gênese
[cite_start]Na criação, o jogador recebe um orçamento de **3 Pontos de Gênese** para customizar seu Bio-Ativo inicial[cite: 237].
* [cite_start]**Anomalias (Custo 3):** Shiny (Vantagem Social/Sorte), Alpha (Tanque/Tamanho), Delta (Mudança de Tipo) [cite: 242-246].
* [cite_start]**Combate (Custo 2):** Pele de Adamantium, Instinto Predatório, Mira Computadorizada [cite: 251-255].
* [cite_start]**Utilitários (Custo 1):** Visão Térmica, Escalador, Carapaça Reativa [cite: 257-260].

---

## 🗺️ O Mundo de Neo-Kanto

* **Setor Central (Saffron):** Onde a elite vive sob proteção da **Silph Co.** e seus drones de segurança.
* [cite_start]**Zona Industrial (Lavender):** Cemitérios de lixo eletrônico e fábricas, lar de tipos Elétricos e Fantasmas [cite: 79-80].
* [cite_start]**Orla Tóxica (Vermilion):** Porto controlado por contrabandistas onde chegam as cargas de Slave-Balls [cite: 80-81].

### Facções
1.  **Operativos Livres (Jogadores):** Focados em libertação e sobrevivência.
2.  [cite_start]**Cartel Rocket:** Traficantes paramilitares que usam escravidão tecnológica[cite: 207].
3.  [cite_start]**Silph Co.:** Monopólio corporativo de biogenética e tecnologia S.Y.N.C.[cite: 83].

---

## 💻 Tech Stack (SymbioDex App)

> *Planejamento para o Companion App do Jogador.*

* **Front-end:** Next.js (App Router), React, TailwindCSS.
* **UI/UX:** Glassmorphism, Dark Mode, Data-Heavy Interface (inspirado em Datadex).
* **Features:**
    * Gerenciamento de Ficha de Bio-Ativo.
    * Monitoramento de Estresse e Bio-Energia em tempo real.
    * Banco de Dados de Espécies com conversor automático para SWADE.

---

## 🛠️ Instalação & Uso (RPG de Mesa)

1.  **Requisitos:** Livro básico *Savage Worlds Edição Aventura*.
2.  **Criação:**
    * [cite_start]Defina seu arquétipo de Operativo (Handler, Tech-Op, Vanguard) [cite: 108-110].
    * Escolha uma espécie base e aplique os **Pontos de Gênese**.
3.  **Logística:**
    * [cite_start]Calcule o custo diário de manutenção do seu time (20 NC$ - 200 NC$)[cite: 60].
    * [cite_start]Equipe seus Bio-Ativos com Implantes (ex: *Bio-Gel Injector*)[cite: 67].

---

## 📄 Licença

Este projeto é uma obra de fã baseada em mecânicas de *Savage Worlds* e na propriedade intelectual *Pokémon*. Criado para fins de entretenimento e design de jogo não-comercial.

---

*"O mito do Mestre Pokémon morreu. Bem-vindo à Era da Simbiose."*