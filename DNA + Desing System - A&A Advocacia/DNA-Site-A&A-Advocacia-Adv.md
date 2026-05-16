---
SITE DNA — A&A Advocacia
Nicho: Advocacia / Posicionamento: Especializada e Humanizada (Luxo Jurídico) / Data de criação: 2026

IDENTIDADE VISUAL
- Paleta: 
  - `#1a4a5a` e `#061a21`: Teal Deep/Dark (Primária e Backgrounds Escuros / Fundo Hero, Footer)
  - `#fafbfc` e `#f5f7f8`: Escalas de Gelo/Branco Quebrado (Fundos principais e Seções alternadas)
  - `#c9a962` e variações (`#e0c078`, `#a68a4a`): Dourado/Gold (Acentos textuais, ícones, CTAs, tags decorativas)
  - `#1a1a1a` e `#4a4a4a`: Dark gray (Textos Body e Textos Light para ambientes claros)
  - `#ffffff`: Branco (Textos e Base em ambientes escuros)
- Tipografia: 
  - `Playfair Display`, serif — weight 400/700 — h1: `clamp(2.8rem, 6vw, 5rem)`, h2: `clamp(1.8rem, 3.5vw, 2.8rem)` e display text.
  - `Inter`, sans-serif — weight 400/500/600 — body: `1rem` ao `1.15rem`, nav e legibilidade geral.
  - `Crimson Pro`, serif — weight 400 itálico — acento textual visual mesclado aos H1s e titles.
- Estilo geral: "Luxo Jurídico" combinando paletas escuras Neo-Clássicas e fontes serifadas imponentes com texturas de glassmorphism premium (vidros opacos) e brilhos dourados sutis para transmitir alta confiança.

LAYOUT — SEÇÃO POR SEÇÃO

1. Header Premium
2. Estrutura: Flexbox `space-between` numa barra fixa de 80px de altura. Nav oculta em mobile com Hamburger Menu.
3. Fundo: `rgba(255, 255, 255, 0.95)` usando `backdrop-filter: blur(8px)`.
4. Elementos: Logo da A&A à esquerda. Nav (`nav-desktop`) centralizada com margem direita, e botão CTA Dourado à direita (com ícone SVG check in).
5. Animação: Scroll Control JS escondendo via `transform: translateY(-100%)` em scroll-down e exibindo em scroll-up em 400ms.
6. Micro-interações: Hover progressivo na tag `a` com linha dourada bottom-border width animando para 100%. Logo ganha scale flexível. Hover nos botões aumenta expansivamente a box-shadow (brilho externo extra).
7. Elemento diferenciador: Menu mobile overlay com desfoque blur que entra pelo slider lateral de `right: -100%` a `0`.

---

1. Hero Premium
2. Estrutura: Grid em duas colunas (Desktop `1.2fr 1fr`), ou single column flex-align em mobile com texto se empilhando antes de foto inserida manualmente.
3. Fundo: `radial-gradient` mesclando com linear gradient dark e textura xadrez via linear-gradient (pontilhado linear cruzado 60px/60px). Padrão paper texture em overlay opacidade 0.012% para base.
4. Elementos: Badge left c/ ícone ping (pulsating gold), Texto H1 massivo esquerdo e Subtexto p com borda esquerda. Hero Image encaixada na direita (wrapper colando no viewport right end com mask image fade). CTA duplo base (Contato). Scroll marker abaixo.
5. Animação: Textos sofrendo 'cascata' reveal (subindo translateY e opacitying), ponto dourado via infinite pulse-gold keyframe (2s) de scale/opacity (0.7 a 1.2). JS scroll parallax translateY na foto Hero direita (sincronizada ao scroll).
6. Micro-interações: Shine effect via highlight atravessando botão CTA dourado. Efeito magnético dos botões de hero associado com mousemove via JavaScript (movendo elementos sutilmente X/Y axis).
7. Elemento diferenciador: Efeito parallax unificado junto da opacidade `mask-image: linear-gradient` preta da Hero Image (grayscale mesclada ao background sem arestas visíveis).

---

1. Áreas de Atuação Jurídica
2. Estrutura: Grid flexível (1fr mobile à 3 colunas desktop com gap largo).
3. Fundo: Background seccional quebrado / neutro cinza claro `#f5f7f8`.
4. Elementos: Content tag com decorador de tracejado em 45 graus, Section Title sublinhado pontual pequeno centralizado. Cards brancos de borda fina. Ícone box gradient e h3 com parágrafo simplificado. Anchor fina com setas no limite inferior do box.
5. Animação: Intersection observer com escalonamento cascata JS (`mod index % 6 * 100ms`). 
6. Micro-interações: Hover no bloco aciona Top Border Line ScaleX expansível. Hover 3D Tilt nos cards manipulando eixo perspective no mousemove, adicionando profundidade com sombra subindo (e translateY). Ancora ganha margem progressiva no gap da setinha.
7. Elemento diferenciador: União refinada entre o expansor the linha Edge Gold Hover c/ o JS Mouse Hover 3d (perspective).

---

1. Como Funciona a Contratação
2. Estrutura: List order structure (Flex column) colado a centro visual com tracking line.
3. Fundo: Branco `#ffffff`.
4. Elementos: Título, Tag. Em sequência vertical temos elementos flex-row dot point left/texto block right. Number blocks customizados grandes em background sólido/brilho dourado. Texto do Step title + texto Body.
5. Animação: Reveal cascate via Scroll trigger.
6. Micro-interações: Zero hard interações, estático pela arquitetura purista.
7. Elemento diferenciador: Tracking line contínua da esquerda que passa por "dentro" dos number boxes com CSS absolute.

---

1. Sobre / Compromisso com Excelência Jurídica
2. Estrutura: Grid de 1.2 x 1, foto a esquerda (tablet down) contraída com max dimension fixa, textão a direita.
3. Fundo: Branco `#ffffff`.
4. Elementos: Imagem esquerda em moldura paralela assimétrica solta do top. Título display alinhado a esquerda com bottom edge decorativo. Textos em colunas seguidas de CTA outline button e um subgrid bottom de 2x2 para listagem rápida (Badges rectangulares flex com stroke icon).
5. Animação: Imagem vindo do "left" (`transform: translateX(-60px) -> 0`); Texto subindo de bottom.
6. Micro-interações: Interações Hover no bloco individual das check informations puxando eixo X levemente ao dar scroll.
7. Elemento diferenciador: Frame offset frame design. (Borda outline em gold deslocada 20px no topo/left) quebrado pelo box offset da própria imagem realçando efeito depth.

---

1. Diferenciais A&A Advocacia
2. Estrutura: Grelha paralela restrita (max width 1000px). Desktop de duas colunas, gap grande.
3. Fundo: Quebrado neutro cinza claro `#f5f7f8`.
4. Elementos: Section Headers. Caixa flexbox-row contendo icon container a esquerda de fixadas proporçoes e content container a direita. Clean layout box.
5. Animação: Cascading scroll reveals.
6. Micro-interações: Leve elevação nos y axis (`-4px`) somados a sombra interna e borda glow highlight de rgba dourado suave em interações de ponteiro.
7. Elemento diferenciador: Legibilidade cirúrgica, background de ícone mescla com stroke dourado criando arremate de ícone flutuante sobre glass background nativo.

---

1. Perguntas Frequentes (FAQ)
2. Estrutura: Accordion list empilhada bloco após bloco. Limite máximo centrado central 850px.
3. Fundo: Branco Puro `#ffffff`.
4. Elementos: Heading groups centrados, Botões expanders (`.faq-question`) para click list item, texto container max-height para `.faq-answer`. Chevron icon dourado de stroke a direita das linhas.
5. Animação: Calc maxHeight por JS ativando transition natural e Arrow SVG com rotation.
6. Micro-interações: Dropdown animation, Click toggle open class (Accordion fechamento de terceiros ao abrir target). Hover de bloco com alteração do opacity do background highlight.
7. Elemento diferenciador: Elemento minimalista funcional quebra o ritmo impositivo para respiro da landing page.

---

1. Orientação Jurídica (CTA Final e Form)
2. Estrutura: Layout flex centrado para headings seguido de form grid duas colunas (mobile 1fr). Width form de 700px.
3. Fundo: `var(--gradient-dark)` overlay radial top centro gradiente sutil. Elementos absolutos esféricos ofuscados por blur(100/120px) decorando os corners invisíveis da grade form.
4. Elementos: Headding complexo com texto H2 Gold color. Forms UI (Input, Select textareas em glass border solid transparente). Submit full block gold theme "Enviar Solicitação".
5. Animação: Enfeites redondos decor background flutuam (Keyframe float Yaxis ease-in-out infinite). Inputs interativos JS de loading state com svg circle spinner inserido in line submentendo visual wait-time and success redirect to whatsApp form.
6. Micro-interações: Inputs em Focus formam ring dorado c/ border light strong gold line e alteração de color base (solid dark input overlay). Submit com loading timeout JS UX control com spin delay lock button action -> success change text -> redirect delay trigger.
7. Elemento diferenciador: Glass UI inputs + Form state design (loading spin feedback real antes de chamar event API window location default e validação Realtime onBlur e onKey validation outline color error trigger).

---

1. Footer
2. Estrutura: Grid 4 blocos complexo responsivo (1.5 / 0.8 / 1.7 / 1.7 col proportion sizes CSS vars). Bottom thin copy bar.
3. Fundo: Escuro sólido (`#061a21`).
4. Elementos: Logo vertical text stack left e description company brand info; links tree sec; Contact details com icons left; Horários e iFrame Mapa embed para Maps widget location end block. Footer bar bottom.
5. Animação: N/A, UI clean final static.
6. Micro-interações: Hover links padding left addition progress com mudana pra cor dourada solid + opacity changes links utilidade legais and footer links bottom right flex.
7. Elemento diferenciador: Injeção flexível de IFrame maps no último segmento bottom-right, equilibrando informações em massa.

---

COMPONENTES REUTILIZÁVEIS
- Botões: O ".btn-primary" é um Linear Gradient de quatro extremidades Gold, Shadowed. Hover trigger executa `translateY(-3px)`, box shadow escala com maior amplitude local e `::before` pseudo element cross-cut de linear shine animation transleta-se do lado oposto. Efeito secundário "magnetic effect" reativa e-x/y translate com pointer movement via JS target bounding rect relative positioning.
- Cards: Estrutura Solid White Background Area Card Box, Light shadow hoverable e ScaleX 0 a 1 em before line edge top. JS Hover Tilt rotacionando caixa 3d Perspective para seguir mouse local axis em Y/-Y relative center de massa local viewport area element.
- Navbar: Sticky fixed transparente ao top scroll down state (transmutável via hide transform on Y array via delta listener down). Fundo glass, Hover Links geram pseudo expand bars from center width expansion color solid primary line track hover bottom.

---

ANTI-PADRÕES REGISTRADOS
- Evitado o uso de grids simétricos engessados e designs modulares matemáticos para as seções de informações de marcações; Quebrou grid c/ frames offset e colunas em proporções .2 a 1fr para mais aspecto orgânico de revista/cartaz luxuoso.
- Evitado forms chapados base browser styles. Adotou Glassmorphic Input Text boxes flutuando sobre Dark Blue Gradients sob soft orbs glow blur highlights para "luxo digital".
- Recusado text-center genéricos nos parágrafos principais da página, focados sempre a Left Align read layouts.
- Evitou Botões estáticos "WhatsApp". Usa floating gradient verde hover transform complexo nativo e Loading button validation steps dentro de Formulário em vez de click straight no WA.

---
