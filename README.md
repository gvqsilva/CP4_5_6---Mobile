# 🏎️ PitZone

**A plataforma completa para fãs de Fórmula 1.**

PitZone é um aplicativo mobile que reúne informação, estatísticas, Fantasy, competição social, gamificação e comércio em uma única experiência para quem já é apaixonado por F1 — e para quem está começando a se interessar pela categoria agora.

## 📖 Sobre o projeto

A Fórmula 1 vive um momento de forte crescimento de audiência, atraindo um público novo que muitas vezes não sabe por onde começar a acompanhar a categoria. Ao mesmo tempo, o fã histórico usa hoje um conjunto fragmentado de apps e sites: um para notícias, outro para o Fantasy oficial, grupos separados no WhatsApp/Discord para competir com amigos, e mais um site para comprar produtos.

O PitZone nasce para resolver essa fragmentação, unindo em um só app:

- **Viva a Fórmula 1** — pilotos, equipes, corridas, notícias, circuitos e classificações.
- **Monte sua equipe. Supere seus rivais.** — Fantasy game completo, com ligas entre amigos.
- **Leve a paixão para as pistas** — loja integrada com produtos oficiais e colecionáveis.

## 👥 Integrantes

- _Augusto Mendonça - RM: 558371_
- _Gabriel Vasquez - RM: 557056_
- _Gustavo Oliveira - RM: 559163_

## 📱 Funcionalidades principais

| Área | Descrição |
|---|---|
| **Home** | Hub central: próxima corrida, countdown, minha equipe Fantasy, ranking, notícias em destaque |
| **F1** | Calendário, detalhes de corrida/circuito, pilotos, equipes, notícias, resultados e classificações |
| **Fantasy** | Criação de equipe (2 pilotos + construtor + chefe de equipe) dentro de um orçamento, pontuação por corrida |
| **Ligas** | Criar/entrar em ligas via código, ranking entre amigos |
| **Ranking** | Global, Brasil, amigos, ligas, por corrida e por temporada |
| **Conquistas** | Gamificação com badges (ex: Primeira Vitória, Campeão da Liga) |
| **Perfil** | Estatísticas, histórico, ligas, equipes, conquistas e configurações |
| **Loja** | Categorias, produtos, carrinho e checkout de itens oficiais de F1 |

## 🎨 Identidade visual

Fundo preto/azul muito escuro, vermelho como cor de destaque, cards escuros com bordas discretas e elementos luminosos — inspirado em interfaces esportivas premium. Detalhes completos na documentação.

## 🛠️ Tecnologias

- React Native + Expo
- _(completar conforme definição do time: backend, banco de dados, API de dados de F1, etc.)_

## 🚀 Como rodar o projeto

```bash
git clone https://github.com/<usuario>/pitzone.git
cd pitzone
npm install
npx expo start
```

## 📁 Estrutura de pastas (proposta inicial)

```
pitzone/
├── src/
│   ├── screens/
│   │   ├── onboarding/
│   │   ├── auth/
│   │   ├── home/
│   │   ├── f1/
│   │   ├── fantasy/
│   │   ├── ligas/
│   │   ├── ranking/
│   │   ├── perfil/
│   │   └── loja/
│   ├── components/
│   ├── navigation/
│   ├── services/
│   ├── store/
│   ├── theme/
│   └── assets/
├── docs/
│   └── DOCUMENTACAO-CP4.md
├── App.tsx
├── app.json
└── package.json
```

## 📄 Licença

Projeto acadêmico desenvolvido para a disciplina de Mobile Development & IOT — FIAP.
