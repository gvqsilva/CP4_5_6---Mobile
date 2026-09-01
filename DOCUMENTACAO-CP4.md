# PitZone — Documentação CP4 (Idealização do App)

Este documento cobre os itens exigidos no Checkpoint 4: escopo do projeto, desenvolvimento de marca e ideia de venda (pitch).

---

## 1. Escopo do projeto

### 1.1 Problema

A Fórmula 1 vive atualmente um pico de popularidade global (impulsionado por fatores como documentários, cobertura de mídia e o calendário no Brasil), o que trouxe um grande volume de novos fãs à categoria. Esse público novo enfrenta duas dificuldades:

1. **Barreira de entrada** — não conhece pilotos, equipes, regras e histórico, e não encontra em um único lugar um conteúdo introdutório organizado.
2. **Fragmentação de experiência** — mesmo o fã experiente precisa alternar entre vários apps: um para notícias, outro para o Fantasy oficial, grupos de WhatsApp/Discord para competir com amigos e sites separados para comprar produtos oficiais.

Não existe hoje um app único que combine acompanhamento da categoria, competição (Fantasy), comunidade (ligas com amigos) e comércio em uma mesma experiência, com uma identidade visual que transmita a emoção da F1.

### 1.2 Público-alvo

- **Fãs novos/casuais**: pessoas que passaram a acompanhar F1 recentemente e querem entender pilotos, equipes e calendário de forma acessível.
- **Fãs engajados**: usuários que já acompanham a categoria e querem uma camada competitiva e social (Fantasy, ligas, ranking) além da informação.
- **Consumidores de produtos oficiais**: fãs que compram merchandising de equipes/pilotos e hoje precisam recorrer a lojas oficiais externas ao app.

### 1.3 Proposta de valor

> PitZone é a plataforma mobile que reúne informação, Fantasy, competição social, gamificação e loja em uma única experiência para fãs de Fórmula 1 — do iniciante ao apaixonado.

O diferencial não é apenas mostrar notícias da F1, e sim conectar toda a jornada do fã: saber quando é a próxima corrida → consultar um piloto → gerenciar o Fantasy → comparar posição no ranking → competir em liga com amigos → desbloquear conquistas → comprar na loja — tudo dentro do mesmo app.

---

## 2. Desenvolvimento de marca

### 2.1 Nome

**PitZone** — junção de *pit* (o "pit stop", coração técnico e estratégico de uma corrida) com *zone* (zona, território). O nome comunica a ideia de estar dentro da ação, no espaço reservado para quem realmente vive a Fórmula 1 — a "zona" do fã.

### 2.2 Paleta de cores

Com base nas telas do protótipo, a identidade segue uma paleta escura e de alto contraste, típica de aplicações esportivas premium:

| Uso | Cor | Referência aproximada |
|---|---|---|
| Fundo principal | Preto/azul muito escuro | `#0B0E14` – `#0D1117` |
| Superfície / cards | Cinza-azulado escuro | `#151A24` – `#1A1F2B` |
| Cor primária / destaque | Vermelho F1 | `#E10600` – `#FF1E1E` |
| Texto principal | Branco | `#FFFFFF` |
| Texto secundário | Cinza claro | `#9AA3B2` |
| Bordas | Cinza sutil | `#262C38` |

> Os tons exatos podem ser extraídos com o color picker do Figma a partir das telas já desenhadas; os valores acima servem como ponto de partida documentado.

### 2.3 Tipografia

Fonte sans-serif geométrica e condensada para títulos e números de destaque (pontuação, países, tempos), transmitindo velocidade e tecnologia; fonte sans-serif neutra e legível para corpo de texto e listas. Sugestão de referência: família como *Titillium Web* ou *Inter* para manter a leitura confortável em telas densas de dados (calendário, estatísticas de pilotos, carrinho de compras).

### 2.4 Logo

Wordmark "PitZone" combinado a um ícone que remete à bandeira quadriculada/checkered flag (visível no topo das telas de Introdução, Cadastro e Login), reforçando a associação imediata com corrida sem depender de marcas oficiais da F1.

### 2.5 Elementos visuais recorrentes

- Cards escuros com bordas discretas e leve efeito de brilho (glow) em elementos de destaque (ex: countdown da próxima corrida, badges de posição).
- Imagens grandes de carros e pilotos como elemento de impacto (telas de Introdução, Home, Detalhes do Piloto).
- Ícones minimalistas na tab bar inferior (Home, F1, Fantasy, Loja, Perfil).
- Uso do vermelho como cor de ação (botões "Faça parte", "Gerenciar Equipe", "Finalizar Compra") contra o fundo escuro neutro.

### 2.6 Telas conceituais (evidência)

Protótipos já desenhados cobrindo o fluxo completo do app:

- **Onboarding e conta**: Introdução (3 telas), Cadastro, Login.
- **Home**: hub com próxima corrida, countdown, minha equipe, notícias e destaques.
- **F1**: Calendário, Detalhes da sessão/circuito, Pilotos, Detalhes do piloto, Equipes, Notícias.
- **Fantasy**: Minha equipe, Pontuação, fluxo de criação de equipe em 5 passos (piloto 1, piloto 2, construtor, chefe, revisão).
- **Loja**: Categorias, Produtos, Produto, Carrinho, Checkout (entrega → pagamento → confirmação).
- **Perfil e social**: Perfil, Ligas, detalhes de liga (ranking/equipes), Histórico de pontos.

---

## 3. Ideia de venda (pitch)

### 3.1 Modelo de negócio

**Freemium com múltiplas frentes de monetização:**

1. **Núcleo gratuito** — calendário, notícias, pilotos/equipes, Fantasy básico e uma liga por usuário, para maximizar adoção, especialmente entre novos fãs.
2. **Assinatura PitZone+** — estatísticas avançadas, análises exclusivas de corrida, número ilimitado de ligas, personalização de perfil e remoção de anúncios.
3. **Comércio (loja)** — receita via comissão sobre vendas de produtos oficiais e colecionáveis, com potencial de parcerias diretas com equipes/varejistas licenciados.
4. **Publicidade nativa** — banners e conteúdo patrocinado no feed de notícias e na Home para usuários do plano gratuito.
5. **Ligas e conquistas patrocinadas** — parcerias de marca para ligas temáticas ou conquistas especiais durante a temporada.

### 3.2 Diferencial competitivo

| Concorrente típico | Limitação | Como o PitZone se diferencia |
|---|---|---|
| App oficial da F1 | Foco em informação e replays, sem camada social/competitiva robusta | Uni informação + Fantasy + liga social no mesmo fluxo |
| Fantasy F1 oficial / sites de Fantasy | Ficam isolados de notícias e comunidade dentro do app | Fantasy conectado à Home, notícias e ranking do usuário |
| Grupos de WhatsApp/Discord entre amigos | Sem estrutura, sem ranking automático, sem histórico | Ligas nativas com ranking, código de convite e histórico de pontuação |
| Lojas oficiais de equipes | Compra desconectada do restante da experiência de fã | Loja integrada ao mesmo app usado para acompanhar a temporada |

O maior diferencial é a **jornada conectada**: o usuário não precisa sair do app para nenhuma etapa da experiência de fã — informação, competição, comunidade e consumo estão no mesmo lugar, com uma identidade visual pensada especificamente para transmitir velocidade, tecnologia e exclusividade.

---

## 4. Organização do projeto (setup técnico inicial)

- **Stack proposta**: React Native + Expo (mobile), com estrutura de pastas por domínio (`screens/f1`, `screens/fantasy`, `screens/loja` etc. — ver `README.md`).
- **Repositório**: GitHub com README, este documento de escopo/marca/pitch em `docs/`, e protótipos de tela versionados ou linkados via Figma.
- **Fonte de dados de F1**: ver comparação de APIs no item 4.1 abaixo.
- **Próximos passos técnicos**: modelagem do backend do Fantasy (cálculo de pontuação, orçamento de equipe) e integração de pagamento para a loja.

### 4.1 Comparação de APIs de dados de F1

O app depende de uma fonte de dados de corridas, pilotos, equipes e resultados. A API oficial da F1 não é pública para desenvolvedores externos, então as opções realistas são:

| Fonte | O que oferece | Prós | Contras | Uso recomendado no PitZone |
|---|---|---|---|---|
| **Jolpica-F1** (`api.jolpi.ca/ergast/f1/`) | Dados históricos estruturados desde 1950: corridas, resultados, classificações, pilotos, equipes, circuitos | Sucessora direta e compatível do antigo Ergast (padrão usado pela maioria dos apps de F1 open source); gratuita, sem chave de API, resposta em JSON bem documentada | Mantida por poucos voluntários, sem SLA; limite de ~200 requisições/hora sem autenticação; depende de doações para se manter no ar | **Fonte principal**: calendário, resultados, histórico de pilotos/equipes, telas de estatísticas |
| **OpenF1** | Dados recentes (2023+) quase em tempo real: telemetria, posições, gaps, pit stops, clima, status da sessão | Atualização a cada ~3–4s durante a corrida; gratuita para uso histórico e básico ao vivo; sem autenticação obrigatória | Só cobre a partir da temporada 2023 (não serve como fonte histórica completa); uso intenso em tempo real tem limite de 3 req/s | Fonte complementar, para uma futura tela "ao vivo" (posições/gap durante a corrida) — não essencial no MVP do CP4 |
| **F1DB** | Dump completo do banco de dados de F1 em JSON/CSV/SQL | Não depende de um servidor externo no ar; ótimo para popular o app com dados históricos completos desde o início | É um snapshot estático — precisa ser atualizado manualmente a cada corrida/temporada | Seed inicial de banco local / fallback caso a API externa fique indisponível |

**Recomendação para o MVP do CP4**: usar a **Jolpica-F1** como fonte principal (calendário, pilotos, equipes, resultados e classificações), com a possibilidade de usar o **F1DB** como seed local de dados históricos caso a disponibilidade da API seja um risco durante a demonstração. A **OpenF1** fica como evolução futura, fora do escopo deste checkpoint, para uma eventual tela de acompanhamento ao vivo.
