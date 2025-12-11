# 📘 Project Symbiosis: Neo-Kanto 2077

> **Classificação:** USO RESTRITO // OPERATIVOS AUTORIZADOS
> **Sistema Base:** Savage Worlds (Edição Aventura - SWADE)

![Status](https://img.shields.io/badge/Status-In_Development-cyan)
![System](https://img.shields.io/badge/System-Savage_Worlds-red)
![Setting](https://img.shields.io/badge/Setting-Cyberpunk_Solarpunk-green)

## 🌐 Visão Geral

**Project Symbiosis** é uma reimaginação tática, adulta e futurista do universo de captura de monstros. Ambientado em **Neo-Kanto no ano de 2077**, o jogo abandona a fantasia infantil para focar em ética, tática militar e sobrevivência econômica.

Neste mundo, a tecnologia de **Pokébolas foi banida** por ser considerada tortura digital. Os jogadores assumem o papel de **Operativos** que utilizam o sistema **S.Y.N.C.** (Synchronized Neural Connection) para formar parcerias biológicas com criaturas, agora chamadas de **Bio-Ativos**.

### A Filosofia
* **Conexão acima de Coleção:** Ter um Bio-Ativo é uma responsabilidade logística e financeira. Manter um Pokémon custa créditos e sanidade.
* **Autopreservação:** A IA dos Bio-Ativos é realista. Se ordenados a cometer suicídio tático, o Link Neural se rompe e eles fogem.
* **O Inimigo Real:** O Cartel Rocket utiliza "Slave-Balls" ilegais que fritam os inibidores de dor das criaturas, criando máquinas de matar sem consciência.

---

## ⚙️ Mecânicas Principais (Adaptação SWADE)

O sistema utiliza o motor **Savage Worlds Adventure Edition** com modificações para simular a letalidade e a tática do cenário.

### 1. Conversão de Dados (Data-to-Dice)
Utilizamos os stats base da espécie (0-255) para definir os dados de RPG.

| Valor do Stat | Dado (SWADE) | Classificação |
| :--- | :--- | :--- |
| **00 - 45** | `d4` | Civil / Frágil |
| **46 - 80** | `d6` | Padrão / Competente |
| **81 - 110** | `d8` | Atlético / Forte |
| **111 - 140** | `d10` | Elite / Brutal |
| **141 - 170** | `d12` | Ápice Biológico |
| **171 - 200** | `d12 + 1` | Anomalia Genética |
| **201+** | `d12 + 2/3` | Escala Divina / Kaiju |

* **Defesa (Defense):** Convertida em Armadura Natural (`+0` a `+8`) somada à Resistência.

### 2. Ciclo de Evolução (Bio-Data)
Não existe XP tradicional. A evolução é baseada na coleta de **Bio-Data (BD)**.
* **Avanço:** A cada **5 BD**, o Bio-Ativo ganha um upgrade (Perícia, Vantagem ou Atributo).
* **Patamares:** De **Novato** (Nvl 1-20) a **Lendário** (Nvl 81+), desbloqueando capacidades físicas e ultimates.

### 3. Sistema de Gênese
Na criação, o jogador recebe um orçamento de **3 Pontos de Gênese** para customizar seu Bio-Ativo inicial.
* **Anomalias (Custo 3):** Shiny (Vantagem Social/Sorte), Alpha (Tanque/Tamanho), Delta (Mudança de Tipo).
* **Combate (Custo 2):** Pele de Adamantium, Instinto Predatório, Mira Computadorizada.
* **Utilitários (Custo 1):** Visão Térmica, Escalador, Carapaça Reativa.

### 4. Protocolos Modulares (TMs & HMs)
Movimentos e habilidades de campo são softwares comprados com pontos de evolução.
* **TMs (1 Ponto):** Táticas de combate (Protect, Toxic, U-Turn).
* **HMs (2 Pontos):** Habilidades de elite (Fly, Surf, Strength).

---

## 🗺️ O Mundo de Neo-Kanto

* **Setor Central (Saffron):** Onde a elite vive sob proteção da **Silph Co.** e seus drones de segurança.
* **Zona Industrial (Lavender):** Cemitérios de lixo eletrônico e fábricas, lar de tipos Elétricos e Fantasmas.
* **Orla Tóxica (Vermilion):** Porto controlado por contrabandistas onde chegam as cargas de Slave-Balls.

### Facções
1.  **Operativos Livres (Jogadores):** Focados em libertação e sobrevivência.
2.  **Cartel Rocket:** Traficantes paramilitares que usam escravidão tecnológica e armaduras pesadas.
3.  **Silph Co.:** Monopólio corporativo de biogenética e tecnologia S.Y.N.C.

---

## 💻 Tech Stack (SymbioDex App)

> *Planejamento para o Companion App do Jogador.*

* **Front-end:** Next.js (App Router), React, TailwindCSS.
* **UI/UX:** Tech-Noir Aesthetic (Dark Mode, Red/Cyan Accents), Glassmorphism.
* **Features:**
    * Gerenciamento de Ficha de Bio-Ativo.
    * Monitoramento de Estresse e Bio-Energia em tempo real.
    * Banco de Dados de Espécies com conversor automático para SWADE.

---

## 🛠️ Instalação & Uso (RPG de Mesa)

1.  **Requisitos:** Livro básico *Savage Worlds Edição Aventura*.
2.  **Criação:**
    * Defina seu arquétipo de Operativo (Handler, Tech-Op, Vanguard).
    * Escolha uma espécie base e aplique os **Pontos de Gênese**.
3.  **Logística:**
    * Calcule o custo diário de manutenção do seu time (20 NC$ - 200 NC$).
    * Equipe seus Bio-Ativos com Implantes (ex: *Bio-Gel Injector*).

---

## 📄 Licença

Este projeto é uma obra de fã baseada em mecânicas de *Savage Worlds* e na propriedade intelectual *Pokémon*. Criado para fins de entretenimento e design de jogo não-comercial.

---

*"O mito do Mestre Pokémon morreu. Bem-vindo à Era da Simbiose."*
