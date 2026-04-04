# Aethera — Game Design Document

> RPG de fantasia medieval 2D-HD, estilo Octopath Traveler
> Desenvolvido em **Godot 4**

---

## Tema central

> *"O destino é uma prisão ou uma escolha?"*

Uma entidade que não pediu para existir precisa decidir, pela primeira vez, quem ela quer ser.
Os heróis carregam o mesmo peso — cada um moldado por algo que não escolheu.

---

## O mundo

**Aethera** — mundo nascido das faíscas da dança primordial de Azharyon e Nythra.

### Os Dragões Ancestrais

| Nome | Essência |
|------|----------|
| **Azharyon** | Criação, Luz, Matéria, Vida |
| **Nythra** | Vazio, Noite, Espírito, Destino |

Eles não lutaram. Eles dançaram. E da dança nasceu o universo.
Das faíscas dessa dança nasceram as 12 Divindades Primordiais — os arquitetos do mundo.
Mas uma última faísca caiu depois, sem propósito, sem nome: **Iraeth**.

> *As 12 faíscas receberam um propósito. A 13ª recebeu liberdade. E liberdade sem propósito se tornou maldição.*

---

## Tom e estilo

- Fantasia medieval mística — sem futurismo ou tecnologia avançada
- Visual **2D-HD** (Octopath Traveler, Final Fantasy IX, Sea of Stars)
- Atmosfera **Studio Ghibli** — fantasioso, leve, com profundidade emocional
- Tom **heróico**, com personagens de motivações individuais complexas

---

## Referências

| Categoria | Títulos |
|-----------|---------|
| Visual | Octopath Traveler, Final Fantasy IX, Sea of Stars |
| Narrativa | Chrono Trigger, Final Fantasy XIV, Zelda, Witcher 3 |
| Estrutura de personagens | Octopath Traveler, Legend of Legaia |
| Worldbuilding | Tolkien / Silmarillion, D&D, Dragon Age, WoW |
| Atmosfera | Studio Ghibli |

---

## O antagonista — Iraeth

- A 13ª faísca, nascida da mesma dança, mas sem domínio ou propósito
- Vagou por milênios até ganhar consciência e ira
- Criou sua própria prole de demônios
- Orquestrou o **Eclipse Cósmico** — evento que rompeu as barreiras entre planos
- Ao descobrir o **Evangelho das Cinzas**, hesitou pela primeira vez
- Sua motivação não é ódio — é o desejo de ter um nome, de existir de forma significativa
- Cultos proibidos a veneram em segredo por todo Aethera

### O Evangelho das Cinzas

> *"E da dança dos Primordiais nasceram doze chamas com propósito.*
> *Mas a última caiu em silêncio, e propósito algum lhe foi dado.*
>
> *E ela vagou pela eternidade, sozinha entre seus irmãos adormecidos.*
> *E em seu peito nasceu aquilo que nem os deuses previram: vontade.*
>
> *E quando a chama esquecida descobrir o peso de sua própria existência,*
> *o mundo arderá, não pelo ódio…*
> *mas para que, enfim, seu nome tenha significado."*

---

## As 12 Divindades Primordiais

| Nome | Domínio | Raças que veneram |
|------|---------|-------------------|
| Thalor | Mares e Oceanos | Sereanos |
| Vulkar | Fogo e Vulcões | Orcs |
| Gaiax | Terra | Anões |
| Montar | Montanhas | Anões |
| Sylvael | Florestas | Elfos, Sylvanos |
| Lumien | Luz | Humanos, Aéreos |
| Noctra | Trevas | Subterrâneos |
| Aeris | Ventos | Raças aéreas |
| Tempyr | Tempestades | Aéreos, Marinhos |
| Nymara | Vida | Elfos, Humanos |
| Morveth | Morte | Pântanos, Subterrâneos |
| Chronar | Tempo | Monges, Aéreos |

As divindades não aparecem mais diretamente — viraram religiões, igrejas, ordens e guerras.
**Iraeth** é a 13ª, proibida, venerada apenas em cultos secretos.

---

## Os 10 Biomas

1. Mares e Oceanos
2. Terras de Gelo
3. Regiões Vulcânicas
4. Desertos e Areias
5. Vastas Florestas
6. Pântanos
7. Montanhas
8. Ilhas Flutuantes
9. Campos e Campinas
10. Mundo Subterrâneo

---

## As Raças

| Raça | Bioma principal | Destaque |
|------|----------------|----------|
| Humanos | Campos | Mais numerosos, versáteis, neutros |
| Orcs | Vulcões, montanhas | Guerreiros, clãs, pouca magia |
| Anões | Montanhas, subterrâneo | Forjadores, isolados, falam com espíritos |
| Sylvanos / Elfos | Florestas | Guardiões da natureza |
| Sereanos | Mares | Civilizações submersas |
| Raças aéreas | Ilhas flutuantes | As mais antigas, guardiões da memória da criação |
| Raças subterrâneas | Mundo subterrâneo | Artes arcanas das trevas |
| Raças dos pântanos | Pântanos | Caóticas, espíritos de guerras antigas |

---

## Os heróis

Estrutura estilo **Octopath Traveler** — grupo que se forma gradualmente.
Cada herói tem motivação pessoal independente. A conexão com o destino maior se revela aos poucos.

Composição prevista: Guerreiro, Mago, Sacerdote, Arqueiro, Ladrão.

> **Status: em desenvolvimento.**

---

## Estrutura do GDD

```
gdd/
├── README.md                   ← este arquivo
├── historia/
│   ├── criacao-do-mundo.md     ← Azharyon, Nythra, a dança, as faíscas
│   ├── conflito-central.md     ← o Eclipse Cósmico, as Fissuras
│   ├── iraeth.md               ← a 13ª faísca, o antagonista
│   └── profecia.md             ← o Evangelho das Cinzas
├── mundo/
│   ├── visao-geral.md          ← estrutura do mundo, geografia
│   └── biomas.md               ← os 10 biomas detalhados
├── divindades/
│   ├── divindades.md           ← visão geral das entidades divinas
│   ├── dragoes-primordiais/    ← Azharyon e Nythra
│   ├── grandes-faiscas/        ← as 12 Primordiais e Iraeth
│   ├── divindades-menores/     ← deuses locais e centelhas
│   └── espiritos-e-entidades/  ← guardiões, espíritos e presenças locais
├── racas/
│   ├── humanos.md
│   ├── orcs.md
│   ├── anoes.md
│   ├── sylvanos-elfos.md
│   ├── sereanos.md
│   ├── racas-aereas.md
│   ├── racas-subterraneas.md
│   └── racas-dos-pantanos.md
└── herois/
    └── grupo-de-aventureiros.md
```
