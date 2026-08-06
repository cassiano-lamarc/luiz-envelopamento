# Landing Page — Luiz Envelopamento

## Objetivo

Criar uma landing page profissional, moderna, elegante, responsiva e focada em conversão para a **Luiz Envelopamento**, empresa especializada em envelopamento e renovação de superfícies.

O site deve transmitir imediatamente:

- excelência e capricho na execução;
- qualidade de acabamento;
- cuidado com cada detalhe;
- possibilidade de renovar ambientes e objetos sem grandes reformas;
- proteção e aumento da vida útil dos bens envelopados;
- atendimento profissional para clientes residenciais, comerciais e hotelaria;
- atendimento em **Salvador, Região Metropolitana de Salvador e Linha Verde**.

O principal objetivo da página é fazer o visitante entrar em contato pelo **WhatsApp** para solicitar orçamento.

---

## Dados do negócio

- **Nome:** Luiz Envelopamento
- **WhatsApp / telefone:** +55 71 8207-7328
- **E-mail:** luizenvelopamento2014@gmail.com
- **Instagram:** https://www.instagram.com/luizenvelopamento_/
- **Área de atendimento:** Salvador, Região Metropolitana de Salvador e Linha Verde — BA

Criar os links corretamente:

- WhatsApp: `https://wa.me/557182077328`
- E-mail: `mailto:luizenvelopamento2014@gmail.com`
- Instagram: `https://www.instagram.com/luizenvelopamento_/`

Nos CTAs de WhatsApp, usar uma mensagem pré-preenchida semelhante a:

> Olá, Luiz! Vi seu trabalho pelo site e gostaria de solicitar um orçamento de envelopamento.

---

## Stack obrigatória

Construir a landing page utilizando apenas:

- HTML5;
- CSS3;
- JavaScript puro (Vanilla JS).

Não utilizar React, Angular, Vue ou outros frameworks.

Evitar dependências pesadas. O site deve carregar rapidamente inclusive em conexões móveis.

Organizar preferencialmente em:

```text
/
├── index.html
├── css/
│   └── style.css
├── js/
│   └── main.js
└── assets/
    ├── images/
    └── icons/
```

---

## Direção visual

Quero uma identidade visual **premium, limpa, sofisticada e contemporânea**, valorizando principalmente as fotografias dos serviços realizados.

Evitar aparência de template genérico.

O site precisa funcionar muito bem tanto no desktop quanto no celular.

### Tipografia

Usar a aparência tipográfica do iOS/San Francisco através da pilha nativa do sistema, sem depender do download da fonte proprietária:

```css
font-family: -apple-system, BlinkMacSystemFont, "SF Pro Display", "SF Pro Text", "Helvetica Neue", Arial, sans-serif;
```

Usar títulos fortes, boa hierarquia tipográfica, bastante respiro e textos curtos.

### Cores

Criar uma paleta elegante e profissional, preferencialmente com:

- preto/grafite;
- branco/off-white;
- cinzas neutros;
- uma cor de destaque sofisticada para CTAs e pequenos detalhes.

Não exagerar em gradientes, sombras ou animações.

### Ícones

Todos os botões ou elementos em que um ícone melhorar a leitura devem possuir ícones corretos e consistentes, especialmente:

- WhatsApp;
- Instagram;
- e-mail;
- telefone;
- solicitar orçamento;
- localização/área de atendimento;
- proteção;
- acabamento;
- rapidez/renovação;
- seta de navegação quando aplicável.

Pode utilizar uma biblioteca leve e confiável de ícones ou SVGs apropriados. Não utilizar emojis no lugar dos ícones da interface.

---

## Imagens

Pode utilizar imagens temporárias/placeholders coerentes com envelopamento de móveis, eletrodomésticos, portas, bancadas, ambientes comerciais e hotelaria.

Entretanto, prepare toda a página para que as imagens possam ser substituídas facilmente depois pelas fotografias reais fornecidas pelo Luiz.

Centralizar os caminhos das imagens na pasta `assets/images/` e utilizar nomes autoexplicativos, por exemplo:

```text
hero-envelopamento.jpg
cozinha-envelopada.jpg
geladeira-envelopada.jpg
armario-envelopado.jpg
porta-envelopada.jpg
hotelaria-envelopamento.jpg
antes-depois-01.jpg
```

Sempre definir `alt` descritivo nas imagens.

Aplicar `loading="lazy"` nas imagens fora da primeira dobra.

---

# Estrutura da landing page

## 1. Header

Criar header elegante e responsivo.

No desktop:

- logo/nome **Luiz Envelopamento**;
- Início;
- Vantagens;
- Serviços;
- Trabalhos;
- Hotelaria;
- Contato;
- botão destacado **Solicitar orçamento** com ícone do WhatsApp.

No mobile, utilizar menu compacto/hambúrguer acessível.

O header pode ficar fixo/sticky após a rolagem, desde que permaneça leve e não ocupe espaço demais.

---

## 2. Hero — primeira dobra

Esta área deve causar impacto visual e explicar o serviço em poucos segundos.

Usar uma foto ampla e bonita de um ambiente ou móvel envelopado. Garantir excelente legibilidade do texto no desktop e mobile.

### Sugestão de headline

> **Renove sem reformar. Transforme sem substituir.**

### Texto de apoio

> Envelopamento profissional para transformar móveis, eletrodomésticos e ambientes com acabamento de excelência, mais praticidade e muito menos intervenção que uma reforma tradicional.

Complemento curto:

> Atendimento em Salvador, Região Metropolitana e Linha Verde.

### CTAs

Botão principal:

> **Solicitar orçamento pelo WhatsApp**

Com ícone oficial/reconhecível do WhatsApp.

Botão secundário:

> **Ver trabalhos realizados**

Com ícone de galeria/imagem ou seta.

Adicionar pequena prova de valor próxima aos botões, como:

> Residencial • Comercial • Hotelaria

---

## 3. Seção de posicionamento

Criar uma seção visual que apresente o envelopamento como solução inteligente, não apenas estética.

### Título sugerido

> **Uma nova aparência para o que você já gosta.**

### Texto

> Nem sempre é preciso quebrar, reformar ou substituir para transformar um ambiente. Com o envelopamento, móveis, portas, eletrodomésticos e diversas superfícies podem ganhar uma aparência completamente nova, com menos sujeira, menos intervenção e um resultado capaz de mudar a percepção de todo o espaço.

> É a possibilidade de mudar cores, texturas e estilos sem precisar comprar tudo novamente só porque você gostaria de outra aparência.

Adicionar CTA discreto para orçamento.

---

## 4. Benefícios do envelopamento

Criar cards ou blocos premium com ícones.

### Renovação sem grandes reformas

> Transforme o visual do ambiente sem passar por uma obra longa. O envelopamento permite renovar superfícies de forma muito mais prática e com mínima intervenção no espaço.

### Mais proteção, mais vida útil

> Além de renovar a aparência, uma aplicação bem executada cria uma camada adicional de proteção sobre a superfície, ajudando a preservar o bem contra o desgaste cotidiano e prolongando sua vida útil, respeitando as características do material original.

Evitar prometer proteção absoluta, impermeabilização ou uma quantidade específica de anos sem comprovação.

### Um novo estilo sem trocar tudo

> Quer outra cor ou acabamento? Em muitos casos, você não precisa substituir um móvel ou eletrodoméstico em bom estado. O envelopamento dá uma nova identidade à peça e ao ambiente.

### Acabamento que valoriza os detalhes

> Cada recorte, encontro e acabamento importa. O resultado de qualidade está justamente nos detalhes — e é neles que o trabalho da Luiz Envelopamento deve transmitir excelência.

---

## 5. Serviços

Criar uma seção visual com categorias e fotografias.

Incluir possibilidades como:

- envelopamento de móveis;
- armários e planejados;
- cozinhas;
- geladeiras e eletrodomésticos compatíveis;
- portas;
- bancadas e superfícies compatíveis;
- painéis e elementos decorativos;
- ambientes comerciais;
- soluções para hotelaria.

Não afirmar que todo tipo de superfície pode ser envelopado. O texto pode explicar que a viabilidade depende do estado e do material da superfície e pode ser avaliada no orçamento.

### Texto da seção

> De uma peça que você quer renovar a um ambiente inteiro que precisa ganhar uma nova identidade. Cada projeto é avaliado individualmente para encontrar a solução e o acabamento mais adequados.

---

## 6. Galeria — trabalhos realizados

Esta deve ser uma das áreas de maior destaque do site.

### Título

> **Transformações que falam pelo acabamento.**

Criar galeria responsiva e visualmente sofisticada para fotos reais dos serviços realizados.

Sugestões:

- grid/masonry leve no desktop;
- organização adaptada para mobile;
- imagens com proporções variadas sem quebrar layout;
- ao clicar, abrir uma lightbox leve;
- possibilidade de indicar categorias como Cozinha, Móveis, Eletrodomésticos, Comercial e Hotelaria.

Caso seja possível criar sem complicar o código, prever alguns conjuntos de **antes e depois**, deixando os arquivos fáceis de substituir.

Não adicionar dezenas de imagens placeholder. Usar quantidade suficiente para demonstrar a composição da página.

---

## 7. Antes e depois

Criar uma seção curta que demonstre de forma muito visual o poder da transformação.

### Título sugerido

> **Às vezes, você não precisa de algo novo. Precisa enxergar o que já tem de um jeito novo.**

Utilizar 2 ou 3 comparações placeholder de antes/depois, preparadas para substituição pelas imagens reais.

Pode ser um slider comparativo se a implementação for leve, acessível e boa no touch. Caso isso comprometa desempenho ou UX, usar pares de fotos lado a lado.

---

## 8. Envelopamento como presente

Criar uma pequena seção mais emocional.

### Headline

> **Que tal presentear alguém com uma transformação?**

### Texto sugerido

> Presentear também pode ser renovar algo que faz parte da rotina de quem você ama. Uma cozinha com outra aparência, aquele móvel especial revitalizado ou um eletrodoméstico com uma nova identidade podem se transformar em um presente diferente, útil e cheio de significado.

CTA:

> **Quero conversar sobre uma ideia**

Com ícone do WhatsApp.

---

## 9. Hotelaria e negócios

Dar destaque real a esse público, sem deixá-lo escondido em uma lista de serviços.

### Headline

> **Renove ambientes de hotelaria com menos intervenção na operação.**

### Texto sugerido

> Hotéis, pousadas e outros negócios precisam manter seus ambientes bem apresentados sem transformar cada atualização visual em uma grande reforma. O envelopamento pode ser uma alternativa inteligente para renovar elementos existentes, atualizar acabamentos e manter uma identidade visual mais atual, conforme a viabilidade de cada superfície.

> A Luiz Envelopamento atende projetos de hotelaria e empresas em Salvador, Região Metropolitana e Linha Verde, com avaliação de cada necessidade e atenção especial à qualidade do acabamento.

CTA:

> **Solicitar avaliação para hotel ou empresa**

---

## 10. Excelência e qualidade

Criar uma seção que dê segurança para contratar.

### Título

> **O acabamento muda tudo.**

### Copy sugerida

> Um bom envelopamento não é apenas escolher uma cor bonita. Preparação, aplicação, recortes e acabamento determinam como a transformação será percebida. Por isso, cada projeto deve ser tratado com atenção aos detalhes e compromisso com um resultado à altura do ambiente.

Usar três pilares visuais:

- **Cuidado nos detalhes** — atenção do preparo ao acabamento final.
- **Materiais de qualidade** — escolha adequada ao projeto e à superfície.
- **Excelência na execução** — resultado limpo, preciso e visualmente valorizado.

Não inventar certificações, marcas de materiais, quantidade de anos de experiência, número de clientes ou garantias que não tenham sido fornecidos.

---

## 11. Área de atendimento

Criar uma seção com ícone de localização e destaque para:

> **Salvador, Região Metropolitana e Linha Verde**

Copy:

> Onde estiver o seu projeto, converse com a Luiz Envelopamento. Atendemos residências, empresas, hotéis e pousadas em Salvador, municípios da Região Metropolitana e localidades da Linha Verde.

Adicionar CTA de WhatsApp:

> **Consultar atendimento na minha região**

---

## 12. Instagram

Criar seção:

> **Acompanhe as transformações no Instagram**

Exibir o perfil `@luizenvelopamento_`.

Pode ser utilizado iframe/embed oficial do Instagram quando tecnicamente permitido ou um bloco visual simulando o feed com fotos locais/placeholders e link para o perfil.

Importante: não depender exclusivamente de um iframe que possa ser bloqueado pelo navegador ou pelo próprio Instagram. Se o embed não carregar, a seção ainda deve ficar bonita e possuir um CTA funcional:

> **Seguir no Instagram**

Com ícone do Instagram.

Todos os links externos devem abrir com segurança (`target="_blank"` e `rel="noopener noreferrer"`, quando aplicável).

---

## 13. CTA final

Criar uma seção visual forte antes do footer.

### Headline

> **Antes de trocar, veja o que uma boa transformação pode fazer.**

### Texto

> Conte o que você gostaria de renovar, envie algumas fotos e converse com a Luiz Envelopamento sobre as possibilidades para o seu projeto.

Botão grande:

> **Pedir orçamento pelo WhatsApp**

Com ícone do WhatsApp.

Adicionar abaixo:

> Salvador • Região Metropolitana • Linha Verde

---

## 14. Footer

Incluir:

- Luiz Envelopamento;
- WhatsApp +55 71 8207-7328;
- luizenvelopamento2014@gmail.com;
- Instagram `@luizenvelopamento_`;
- área de atendimento;
- links internos para as principais seções;
- ano atual automaticamente via JavaScript;
- ícones corretos para telefone, e-mail e Instagram.

---

# WhatsApp flutuante

Adicionar botão flutuante de WhatsApp no canto inferior da tela, especialmente útil no mobile.

Requisitos:

- não cobrir conteúdo ou botões importantes;
- possuir `aria-label`;
- ícone reconhecível do WhatsApp;
- abrir conversa com mensagem predefinida;
- animação mínima e elegante, sem ficar pulsando de forma exagerada.

---

# Responsividade

O site deve ser desenvolvido **mobile-first**.

Testar visualmente pelo menos nos seguintes intervalos:

- 320–375 px;
- 390–430 px;
- tablets;
- notebooks;
- desktop 1440 px ou maior.

Garantir:

- nenhum scroll horizontal;
- textos sem cortes;
- botões confortáveis para touch;
- imagens responsivas;
- hero bem composto no mobile;
- menu mobile funcional;
- grids convertidos corretamente para uma coluna;
- espaçamento proporcional;
- CTAs principais facilmente acessíveis.

---

# Interações e animações

Usar animações apenas quando ajudarem a percepção de qualidade:

- entrada suave de elementos durante scroll;
- hover discreto em botões e cards;
- header com comportamento suave;
- lightbox da galeria;
- slider antes/depois somente se continuar leve.

Utilizar `IntersectionObserver` quando necessário, evitando listeners de scroll pesados.

Respeitar `prefers-reduced-motion`.

---

# SEO e descoberta local

Preparar SEO básico para buscas relacionadas a envelopamento na região.

Sugestão de `<title>`:

> Luiz Envelopamento | Envelopamento em Salvador, RMS e Linha Verde

Sugestão de description:

> Envelopamento profissional de móveis, ambientes e superfícies em Salvador, Região Metropolitana e Linha Verde. Renove sem grandes reformas. Solicite seu orçamento.

Incluir:

- title e meta description;
- Open Graph básico;
- favicon placeholder fácil de substituir;
- headings semânticos (`h1`, `h2`, `h3`);
- HTML semântico;
- textos alternativos nas imagens;
- dados estruturados apropriados ao negócio local apenas com informações realmente conhecidas;
- não inventar endereço físico, horário de funcionamento ou avaliações.

---

# Acessibilidade

Garantir:

- contraste adequado;
- navegação por teclado;
- foco visível;
- `aria-label` em botões que sejam apenas ícones;
- `alt` nas imagens;
- menu mobile acessível;
- áreas clicáveis adequadas ao touch;
- links e botões semanticamente corretos.

---

# Performance

A landing page deve ser rápida e leve.

Aplicar:

- JavaScript mínimo;
- imagens otimizadas e responsivas;
- lazy loading abaixo da dobra;
- evitar bibliotecas pesadas;
- evitar vídeos em autoplay;
- evitar parallax pesado;
- evitar filtros/efeitos que consumam processamento desnecessário;
- evitar carregar recursos que não estejam sendo utilizados.

---

# Regras de conteúdo

- Escrever todos os textos em **português do Brasil**.
- Não usar Lorem Ipsum.
- Não inventar depoimentos ou avaliações de clientes.
- Não inventar números de projetos realizados.
- Não inventar anos de mercado apenas a partir do nome/e-mail/Instagram.
- Não prometer durabilidade específica sem informação fornecida pelo proprietário.
- Não afirmar que o envelopamento substitui reforma em qualquer situação.
- Valorizar qualidade, transformação, praticidade e conservação sem promessas técnicas falsas.
- Evitar textos genéricos como “somos os melhores”. Demonstrar qualidade através da linguagem e da apresentação dos trabalhos.

---

# Critérios finais de aceite

Antes de considerar a implementação concluída, verificar:

- [ ] Site funciona apenas com HTML, CSS e JavaScript puro.
- [ ] Layout está excelente em desktop e mobile.
- [ ] Número do WhatsApp está correto em todos os links: +55 71 8207-7328.
- [ ] E-mail está correto: luizenvelopamento2014@gmail.com.
- [ ] Instagram aponta para `https://www.instagram.com/luizenvelopamento_/`.
- [ ] Área de atendimento menciona Salvador, Região Metropolitana e Linha Verde.
- [ ] Botões relevantes possuem ícones.
- [ ] CTA principal leva ao WhatsApp com mensagem predefinida.
- [ ] Existe botão flutuante de WhatsApp.
- [ ] Existe seção de serviços.
- [ ] Existe galeria de trabalhos realizados.
- [ ] Existe seção de antes e depois.
- [ ] Existe seção sobre aumento de proteção/conservação e vida útil, sem promessas absolutas.
- [ ] Existe seção mostrando a possibilidade de renovar sem uma grande reforma ou troca de bens em bom estado.
- [ ] Existe seção sobre presentear alguém com uma transformação.
- [ ] Existe seção específica para hotelaria e empresas.
- [ ] Existe integração ou apresentação visual do Instagram com fallback.
- [ ] Imagens são fáceis de substituir depois.
- [ ] Página possui SEO básico e HTML semântico.
- [ ] Não existem depoimentos, estatísticas, endereços, garantias ou certificações inventadas.
- [ ] Não existe Lorem Ipsum ou conteúdo provisório aparecendo para o visitante.
- [ ] Console do navegador está sem erros.
- [ ] Navegação funciona por teclado e em touch.
- [ ] Animações respeitam `prefers-reduced-motion`.

## Resultado esperado

Entregar uma landing page com aparência profissional e premium, capaz de valorizar visualmente o trabalho da **Luiz Envelopamento** e converter visitantes em pedidos de orçamento.

O visitante deve terminar a navegação com três percepções muito claras:

1. **envelopar pode ser uma forma inteligente de transformar sem substituir ou fazer uma grande reforma;**
2. **qualidade de aplicação e acabamento fazem diferença no resultado;**
3. **é muito fácil falar diretamente com Luiz pelo WhatsApp e avaliar o projeto.**
