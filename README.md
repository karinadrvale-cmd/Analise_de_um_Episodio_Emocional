# 🌿 Episódio Emocional

**Um espaço seguro para explorar o que você sente, compreender seus padrões e encontrar novas perspectivas sobre o que aconteceu.**

![Demonstração do Episódio Emocional](https://via.placeholder.com/800x400?text=Prévia+da+Aplicação)  
*(Adicione aqui um print ou GIF da sua aplicação)*

## 📖 Sobre o Projeto

**Episódio Emocional** é uma ferramenta web interativa de auto-reflexão guiada. Ela convida o usuário a revisitar um episódio emocional específico, mapeando cada camada da experiência: desde o contexto inicial, gatilhos, padrões automáticos, até as sensações físicas, reações e, finalmente, um novo olhar sobre o ocorrido.

O projeto foi criado por [Karina Drvale](https://github.com/karinadrvale-cmd) com o objetivo de oferecer um espaço livre de julgamentos para que qualquer pessoa possa **nomear, compreender e ressignificar** suas emoções.

## ✨ Funcionalidades

- **Jornada em 6 etapas**: cada etapa foca em um aspecto do episódio emocional (situação, padrão, emoções, ações, reestruturação e insight).
- **Seleção de emoções primárias e secundárias**: escolha entre Alegria, Medo, Tristeza, Raiva, Nojo, Surpresa e refine com nuances.
- **Slider de intensidade emocional**: visualize e registre a força do sentimento (0 a 10).
- **Padrões automáticos**: sugestões de comportamentos recorrentes e campo para padrão personalizado.
- **Classificação de ações**: diferencie reações construtivas de destrutivas.
- **Resumo final**: cartões clicáveis com todos os campos preenchidos – ao clicar, abre um modal com o texto completo.
- **Mapa mental interativo (SVG)**: representação visual das conexões entre gatilho, padrão emocional e comportamento. Clique em qualquer nó para ver o conteúdo detalhado.
- **Design responsivo e acolhedor**: cores suaves, tipografia legível e animações que transmitem calma e segurança.
- **Privacidade total**: nenhum dado é enviado para servidores – tudo permanece apenas no seu navegador.

## 🚀 Como usar

1. Acesse o projeto online (ou abra o arquivo `index.html` no seu navegador).
2. Na tela inicial, clique em **“Começar minha jornada”**.
3. Preencha cada etapa com honestidade e sem pressa. Você pode avançar e voltar sempre que quiser.
4. Ao concluir as 6 etapas, visualize:
   - Todos os seus registros em cartões de resumo.
   - Um mapa mental dinâmico que conecta os principais pontos da sua narrativa.
5. Clique em qualquer cartão ou nó do mapa para ler o texto completo (caso tenha sido cortado).
6. Finalize ou inicie uma nova jornada usando o botão no rodapé.

## 🛠️ Tecnologias utilizadas

- **HTML5** – estrutura semântica
- **CSS3** – estilos customizados, variáveis CSS, animações, layout responsivo
- **JavaScript (ES6)** – lógica de navegação, manipulação do DOM, geração do mapa mental SVG e modais
- **SVG** – mapa mental interativo desenhado programaticamente
- **Google Fonts** – famílias `Fraunces` (serifada) e `DM Sans` (sem serifa)

## 📂 Estrutura do projeto

> O projeto é autocontido em um único arquivo HTML – ideal para protótipos, portfólios ou ferramentas pessoais.

## 📸 Prévia

| Etapa de emoções | Resumo e Mapa Mental |
|----------------|----------------------|
| <img src="https://via.placeholder.com/300x200?text=Etapa+3" alt="Etapa 3"> | <img src="https://via.placeholder.com/300x200?text=Mapa+Mental" alt="Mapa Mental"> |

*(Substitua os placeholders por imagens reais do seu projeto)*

## 🔧 Personalização

Você pode adaptar o código livremente:

- **Cores**: as variáveis CSS estão na `:root` – altere `--cream`, `--rose`, `--purple`, etc.
- **Emoções secundárias**: edite o objeto `BRANCHES` no JavaScript.
- **Padrões automáticos**: modifique os textos das `.pattern-chip` dentro do HTML.
- **Mapa mental**: ajuste coordenadas, tamanhos e estilos na função `buildMindMap()`.

## 📄 Licença

Este projeto está sob a licença **MIT**. Sinta-se à vontade para usar, modificar e distribuir, mantendo os devidos créditos à autora original.

## 👩‍💻 Autora

Desenvolvido por **Karina Drvale**  
🔗 [GitHub](https://github.com/karinadrvale-cmd)

---

> 🌻 *Parar, observar e nomear suas emoções é um ato de coragem e autocuidado.*
