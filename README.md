# ⚔️ GURPS ALBION SYSTEM

![Version](https://img.shields.io/badge/version-1.0.0-blue)
![License](https://img.shields.io/badge/license-Fan%20Project-green)
![GURPS](https://img.shields.io/badge/system-GURPS-red)
![Albion](https://img.shields.io/badge/based%20on-Albion%20Online-yellow)

> **Um sistema completo de RPG de mesa que adapta o MMORPG Albion Online para o sistema GURPS.**

---

## 📖 SOBRE O PROJETO

**GURPS Albion** é uma adaptação fiel do universo de **Albion Online** para o sistema de RPG de mesa **GURPS (Generic Universal RolePlaying System)**. Este projeto captura a essência do jogo original: morte com consequências reais, economia dinâmica, PvP sem restrições e progressão permanente de habilidades.

### 🎯 Características Principais

✅ **Sistema de Morte Real:** Fora das cidades = Full Loot (perde tudo ao morrer)  
✅ **Progressão Permanente:** Você perde equipamentos, nunca perde perícias  
✅ **Economia Dinâmica:** Preços baseados no mercado real via [Albion 2D](https://www.albiononline2d.com/en/market)  
✅ **Habilidades por Equipamento:** Suas habilidades (Q, W, E) mudam com o item equipado  
✅ **Crafting Profundo:** Sistema completo de coleta, refinamento e fabricação  
✅ **Combate Tático:** Cada turno = 1 segundo. Defesas ativas, localização de dano, modificadores  
✅ **Reputação e Conquistas:** Títulos permanentes baseados em feitos  
✅ **Sistema de Dívidas:** Guilda de Agiotas persegue devedores  

---

## 📂 ESTRUTURA DO REPOSITÓRIO

GURPS-ALBION-SYSTEM/
├── README.md                 # Este arquivo
├── GUIA_DO_JOGADOR.md         # Manual completo para jogadores
├── GUIA_DO_MESTRE.md          # Manual completo para mestres
├── FICHA_DE_PERSONAGEM.md     # Modelo de ficha de personagem
├── exemplos/
│   ├── PERSONAGEM_EXEMPLO_GUERREIRO.md
│   ├── PERSONAGEM_EXEMPLO_MAGO.md
│   ├── PERSONAGEM_EXEMPLO_ARQUEIRO.md
│   ├── INIMIGO_EXEMPLO_T1.md
│   ├── INIMIGO_EXEMPLO_T4_BOSS.md
│   └── SESSAO_EXEMPLO_COMPLETA.md
├── tabelas/
│   ├── TABELA_DANO_POR_ST.md
│   ├── TABELA_TIER_E_BONUS.md
│   ├── TABELA_LOOT.md
│   ├── TABELA_MONTARIAS.md
│   └── TABELA_EVENTOS_ALEATORIOS.md
├── habilidades/
│   ├── ARMAS_CORPO_A_CORPO.md
│   ├── ARMAS_DE_LONGA_DISTANCIA.md
│   ├── CAJADOS_MAGICOS.md
│   └── ARMADURAS.md
├── recursos/
│   ├── LINKS_UTEIS.md
├── FAQ.md
└── CHANGELOG.md

---

## 🚀 COMEÇANDO

### Para Jogadores

1. **Leia o [GUIA_DO_JOGADOR.md](GUIA_DO_JOGADOR.md)**
2. **Copie a [FICHA_DE_PERSONAGEM.md](FICHA_DE_PERSONAGEM.md)**
3. **Crie seu personagem com 125 pontos**
4. **Escolha seu equipamento inicial** (consulte [Albion 2D](https://www.albiononline2d.com/en/market))
5. **Explore os exemplos em `/exemplos/`** para inspiração

### Para Mestres

1. **Leia o [GUIA_DO_MESTRE.md](GUIA_DO_MESTRE.md)**
2. **Consulte as tabelas em `/tabelas/`** para preparar sessões
3. **Use os exemplos em `/exemplos/`** como base para criar conteúdo
4. **Prepare 3 ganchos de aventura** para a primeira sessão
5. **Consulte [Albion 2D](https://www.albiononline2d.com/en/market)** para preços atualizados

---

## 🎲 MECÂNICAS PRINCIPAIS

### Sistema de Combate (3d6)

- Role **3d6** e compare com sua perícia
- Se o resultado for **≤ perícia**, você acertou
- O oponente pode usar **Defesa Ativa** (Esquiva/Aparar/Bloqueio)
- **Cada turno = 1 segundo** (combate rápido e letal)

### Morte e Respawn

| Local | Consequência |
|-------|--------------|
| **Dentro da Cidade** | Nocaute (sem perda de itens) |
| **Fora da Cidade** | **MORTE** → Full Loot → Respawn na última cidade |

**O que você PERDE ao morrer:**
- ❌ Todo equipamento
- ❌ Toda prata no bolso
- ❌ Todos recursos coletados

**O que você MANTÉM:**
- ✅ Perícias (Fame)
- ✅ Conquistas e Títulos
- ✅ Prata no banco
- ✅ Itens no armazém

### Sistema de Tier

| Tier | Arma (Dano) | Placa (RD) | Couro (RD) | Pano (RD) | Perícia Mín. |
|------|-------------|------------|------------|-----------|--------------|
| T1   | +0          | 1          | 0          | 0         | 10           |
| T3   | +2          | 3          | 2          | 1         | 12           |
| T5   | +4          | 5          | 4          | 3         | 14           |
| T8   | +7          | 8          | 7          | 6         | 17           |

### Habilidades de Itens (Q, W, E)

Cada equipamento tem **3 habilidades ativas**:

- **[Q] Básica:** Custo baixo (1-2 FP), uso frequente
- **[W] Utilitária:** Custo médio (2-4 FP), mobilidade/controle
- **[E] Suprema:** Custo alto (5-8 FP), grande impacto

**Exemplo: Espada Larga T4**
- **[Q] Golpe Heróico (2 FP):** +2 dano
- **[W] Interromper (3 FP):** Alvo perde próxima ação
- **[E] Impacto Sísmico (5 FP):** Dano em área, derruba inimigos

---

## 📊 TABELAS DE REFERÊNCIA RÁPIDA

### Dano por Força (ST)

| ST | Estocada | Balanço |
|----|----------|---------|
| 10 | 1d-2     | 1d      |
| 12 | 1d-1     | 1d+2    |
| 14 | 1d       | 2d      |
| 16 | 1d+1     | 2d+2    |

### Defesas Ativas

- **Esquiva** = Velocidade Básica + 3
- **Aparar** = (Perícia Arma ÷ 2) + 3
- **Bloqueio** = (Perícia Escudo ÷ 2) + 3

### Modificadores de Situação

| Situação | Modificador |
|----------|-------------|
| Atacar pelas costas | +4 |
| Alvo caído | +4 |
| Ataque na cabeça | -5 |
| Escuridão total | -10 |

---

## 🛠️ FERRAMENTAS RECOMENDADAS

### Sites Essenciais

- **[Albion 2D](https://www.albiononline2d.com/en/market)** - Preços de mercado em tempo real
- **[Albion Wiki](https://wiki.albiononline.com/)** - Informações sobre itens e criaturas
- **[GURPS Oficial](https://www.sjgames.com/gurps/)** - Site oficial do sistema

### Materiais de Mesa

- **3d6** por jogador + 3d6 para o mestre
- Fichas de personagem (impressas ou digitais)
- Marcadores de status (Atordoado, Envenenado, Caído)

---

## 📚 EXEMPLOS PRONTOS

### Personagens

- [⚔️ Thorin, o Guardião de Ferro](exemplos/PERSONAGEM_EXEMPLO_GUERREIRO.md) - Tank T3
- [🔥 Lyria, a Chama Dançante](exemplos/PERSONAGEM_EXEMPLO_MAGO.md) - Mago DPS T4
- [🏹 Personagem Arqueiro](exemplos/PERSONAGEM_EXEMPLO_ARQUEIRO.md) *(a criar)*

### Inimigos

- [Herege Recruta (T1)](exemplos/INIMIGO_EXEMPLO_T1.md) *(a criar)*
- [👹 Guardião das Ruínas (T4 Boss)](exemplos/INIMIGO_EXEMPLO_T4_BOSS.md)

### Sessões

- [🎲 A Primeira Expedição](exemplos/SESSAO_EXEMPLO_COMPLETA.md) - Sessão completa de 3-4 horas

---

## 🤝 CONTRIBUINDO

Este sistema está em evolução! Contribuições são bem-vindas:

### Como Contribuir

1. **Fork** este repositório
2. Crie uma **branch** para sua feature (`git checkout -b feature/NovaHabilidade`)
3. **Commit** suas mudanças (`git commit -m 'Adiciona habilidade de Martelo T5'`)
4. **Push** para a branch (`git push origin feature/NovaHabilidade`)
5. Abra um **Pull Request**

### O que precisamos

- [ ] Habilidades de armas faltantes (Martelos, Lanças, Bestas)
- [ ] Mais exemplos de personagens (Arqueiro, Tanque de Couro, Healer)
- [ ] Criaturas e bosses de T5-T8
- [ ] Mapas de masmorras
- [ ] Ganchos de aventura
- [ ] Traduções para outros idiomas

### Reportar Bugs

Abra uma [Issue](../../issues) descrevendo:
- **O que aconteceu**
- **O que deveria acontecer**
- **Passos para reproduzir**

---

## ❓ FAQ (PERGUNTAS FREQUENTES)

### Este sistema é oficial?

**Não.** Este é um projeto de fã, não oficial e sem fins lucrativos.

### Preciso do livro do GURPS para jogar?

**Recomendado, mas não obrigatório.** O [GUIA_DO_JOGADOR.md](GUIA_DO_JOGADOR.md) contém todas as regras essenciais. Para regras avançadas, consulte o **GURPS Basic Set**.

### Preciso jogar Albion Online para entender?

**Não.** O sistema é auto-contido. Conhecer o jogo ajuda, mas não é necessário.

### Como equilibrar combates?

Use a regra: **Inimigo Tier X é desafiador para 3 jogadores Tier X-1**.

Exemplo: Boss T4 vs. 3 jogadores T3.

### E se meu grupo não gosta de Full Loot?

Ajuste as regras! Sugestões:
- Morte dropa apenas 50% dos itens
- Itens T5+ são Soulbound (não caem)
- Zonas "Safe" onde não há full loot

### Onde encontro os preços dos itens?

Consulte o **[Albion 2D](https://www.albiononline2d.com/en/market)** para preços de mercado atualizados em tempo real.

---

## 📜 LICENÇA E CRÉDITOS

### Licença

Este é um **projeto de fã não oficial** fornecido gratuitamente para uso pessoal e não comercial.

- **GURPS** é propriedade de **[Steve Jackson Games](https://www.sjgames.com/)**.
- **Albion Online** é propriedade de **[Sandbox Interactive](https://albiononline.com/)**.

Este material não é endossado, aprovado ou afiliado a Steve Jackson Games ou Sandbox Interactive.

### Créditos

**Criado por:** [Seu Nome/Username]

**Agradecimentos:**
- **Steve Jackson Games** pelo sistema GURPS
- **Sandbox Interactive** por Albion Online
- **Comunidade Albion 2D** pelos dados de mercado
- Todos os jogadores e mestres que testaram este sistema

---

## 📞 CONTATO

### Suporte e Dúvidas

- **GitHub Issues:** [Abra uma issue](../../issues)
- **Discussions:** [Participe das discussões](../../discussions)
- **Email:** [seu-email@example.com] *(opcional)*

### Comunidades

- **r/GURPS:** https://www.reddit.com/r/gurps/
- **r/AlbionOnline:** https://www.reddit.com/r/albiononline/
- **Discord GURPS Brasil:** [Link se houver]

---

## 🗺️ ROADMAP

### Versão 1.0 (Atual) ✅
- [x] Sistema de combate completo
- [x] Sistema de morte e economia
- [x] Crafting e coleta
- [x] Tabelas de referência
- [x] Exemplos de personagens
- [x] Guias de Jogador e Mestre

### Versão 1.1 (Próxima)
- [ ] Habilidades de todas as armas (Martelo, Lança, Besta, etc)
- [ ] Sistema de Guildas (guerras, territórios)
- [ ] Bestiário completo (T1-T8)
- [ ] Mapas de masmorras prontos

### Versão 2.0 (Futuro)
- [ ] Sistema de Facções (Caerleon, Martlock, etc)
- [ ] Sistema de Avalon Roads (dimensões paralelas)
- [ ] Sistema de Conquista de Territórios
- [ ] Campaanha completa (10+ sessões)

---

## 📈 ESTATÍSTICAS

![GitHub Stars](https://img.shields.io/github/stars/SEU_USUARIO/GURPS-ALBION-SYSTEM?style=social)
![GitHub Forks](https://img.shields.io/github/forks/SEU_USUARIO/GURPS-ALBION-SYSTEM?style=social)
![GitHub Issues](https://img.shields.io/github/issues/SEU_USUARIO/GURPS-ALBION-SYSTEM)
![GitHub Contributors](https://img.shields.io/github/contributors/SEU_USUARIO/GURPS-ALBION-SYSTEM)

---

## 🎉 APOIE O PROJETO

Se este projeto te ajudou, considere:

- ⭐ **Dar uma estrela** neste repositório
- 🍴 **Fazer um fork** e contribuir
- 📢 **Compartilhar** com sua mesa de RPG
- 💬 **Deixar feedback** nas discussões

---

## 📅 CHANGELOG

### v1.0.0 (2025-01-29)

**Lançamento Inicial:**
- Sistema completo de combate GURPS adaptado
- Morte com full loot
- Economia dinâmica (Albion 2D)
- Sistema de crafting e coleta
- Tabelas de referência (Dano, Tier, Loot, Montarias, Eventos)
- Guias completos (Jogador e Mestre)
- Exemplos prontos (Guerreiro, Mago, Boss T4, Sessão completa)

---

<div align="center">

## ⚔️ BEM-VINDO A ALBION

**"Fora das muralhas, não há lei. Apenas o aço, a magia... e a morte."**

[📖 Começar a Jogar](GUIA_DO_JOGADOR.md) • [🎲 Mestrar](GUIA_DO_MESTRE.md) • [📊 Tabelas](tabelas/) • [💬 Discussões](../../discussions)

---

**Versão 1.0.0** • **Última Atualização: 2025-01-29**

</div>