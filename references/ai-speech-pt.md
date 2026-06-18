# AI speech em português — referência completa

Adapted for Portuguese from Wikipedia's "Signs of AI writing" (WikiProject AI Cleanup), the basis of the `humanizer` skill. The SKILL.md body groups these into seven clusters; this is the fuller catalog with more examples. Read it for a thorough de-AI edit or when you want to be exhaustive.

Two framing notes:
- These tells are **language-agnostic** — they show up in English and Portuguese alike. The examples here are PT-specific because the *fix* has to land in natural Portuguese.
- The rule throughout: **rewrite, don't delete.** Cover everything the original covered. If a paragraph makes three points, the rewrite makes three points — just without the slop.

---

## Content patterns

**Significance inflation.** Puffing up arbitrary facts with importance/legacy/broader-trends.
> *A fundação do instituto em 1989 marcou um momento decisivo na evolução das estatísticas regionais, parte de um movimento mais amplo de descentralização.*
> → *O instituto foi criado em 1989 para coletar e publicar estatísticas da região.*

**Promotional / advertisement tone.** Especially on "cultural heritage" topics.
> *Aninhada no coração de uma região deslumbrante, a cidade se destaca por seu vibrante patrimônio cultural e sua natureza de tirar o fôlego.*
> → *A cidade fica na região X e é conhecida pela feira semanal e pela igreja do século XVIII.*

**Fake-depth gerund tails (-ing → -ndo).** Participle phrases tacked on to sound deep.
> *O templo usa azul, verde e dourado, simbolizando a paisagem local e refletindo a conexão da comunidade com a terra.*
> → *O templo usa azul, verde e dourado. O arquiteto disse que escolheu essas cores em referência à paisagem local.*

**Vague attributions / weasel words.** Opinions pinned on nobody in particular.
> *Especialistas acreditam que o rio tem papel crucial no ecossistema.*
> → *O rio abriga várias espécies endêmicas de peixe, segundo levantamento de 2019.*

**Formulaic "desafios e perspectivas futuras" sections.**
> *Apesar de sua prosperidade, a cidade enfrenta desafios típicos de áreas urbanas. Apesar desses desafios, continua a prosperar.*
> → *O trânsito piorou depois de 2015, com a abertura de três novos parques industriais. A prefeitura iniciou obras de drenagem em 2022.*

## Language and vocabulary

**AI vocabulary.** High-frequency post-2023 words that cluster: *crucial, fundamental, essencial, robusto, abrangente, aprimorar, ressaltar, destacar, panorama, cenário, intrincado, mergulhar, desvendar, alavancar, fomentar, elevar, navegar (figurative), tapeçaria/mosaico (figurative), além disso (as default glue).* Prefer the plain word.

**Avoiding "ser".** Elaborate constructions where the copula would do: *serve como, configura-se como, constitui, representa, apresenta-se como, destaca-se como, conta com, dispõe de.*
> *A galeria serve como espaço expositivo e conta com quatro salas.*
> → *A galeria é o espaço expositivo e tem quatro salas.*

**Negative parallelisms / tailing negations.** *Não apenas... mas..., não se trata só de... é..., mais do que X, é Y.*
> *Não é só o ritmo sob os vocais; faz parte da agressividade. Não é apenas uma música, é uma declaração.*
> → *O ritmo pesado reforça o tom agressivo.*

**Rule of three.** Forcing triplets to look comprehensive.
> *O evento traz palestras, painéis e networking. Espere inovação, inspiração e ideias.*
> → *O evento tem palestras e painéis, com tempo pra conversar entre uma sessão e outra.*

**Elegant variation (synonym cycling).** Portuguese *does* avoid word repetition more than English, so calibrate — but mechanical cycling across consecutive sentences is still a tell.
> *O protagonista enfrenta desafios. O personagem principal supera obstáculos. A figura central triunfa. O herói volta pra casa.*
> → *O protagonista enfrenta vários obstáculos, mas no fim triunfa e volta pra casa.*

**False ranges.** *de X a Y* where X and Y aren't on a real scale.
> *Da singularidade do Big Bang à teia cósmica, do nascimento das estrelas à dança da matéria escura.*
> → *O livro cobre o Big Bang, a formação das estrelas e as teorias atuais sobre matéria escura.*

**Passive / subjectless fragments.** *Nenhuma configuração necessária. Os resultados são preservados automaticamente.* → *Você não precisa configurar nada. O sistema guarda os resultados sozinho.*

## Style and formatting

**Em/en dash (travessão).** Drop it. The travessão is rare enough in everyday Portuguese that it reads as an AI tell; replace each one with a comma, period, colon, or parentheses, or restructure. The one exception is dialogue in fiction, where it's the correct convention (*— Vamos? — perguntou ela.*). (Note: mainstream outlets do use the travessão for asides, but for an anti-AI-tell skill, dropping it in normal prose is the safe call.)

**Boldface overuse.** Mechanical bolding of phrases mid-prose. Drop it; let the sentence carry emphasis.

**Inline-header bullet lists.** *- **Desempenho:** o desempenho melhorou...* → fold into prose, or use plain bullets without the bold-header-plus-colon.

**Title case in headings.** Portuguese uses sentence case: *Negociações Estratégicas e Parcerias Globais* → *Negociações estratégicas e parcerias globais.*

**Emojis** decorating headings or bullets → remove (unless the channel and voice genuinely call for them).

**Curly vs. straight quotes** is a weak tell in PT and typography varies (" ", « », " "). Don't over-index on it; only consider it alongside other tells.

## Communication residue

**Collaborative artifacts.** Assistant chatter pasted as content: *Ótima pergunta!, Claro!, Com certeza!, Espero que ajude!, Aqui está um resumo…, Quer que eu detalhe algum ponto?, Posso continuar?* → cut entirely; just write the content.

**Cutoff disclaimers / speculative gap-filling.** *Até a minha última atualização…, com base nas informações disponíveis…, embora os detalhes sejam escassos…* and the stock filler for private people: *mantém um perfil discreto, prefere manter a vida pessoal reservada, provavelmente cresceu…* → say what isn't known, or cut the sentence. Don't dress a guess as fact.

**Sycophancy.** *Ótima pergunta!, Excelente ponto!, Você tem toda razão!* → drop the praise; engage with the substance.

## Filler and hedging

**Filler phrases.**
- *com o objetivo de alcançar isso* → *para isso*
- *devido ao fato de que estava chovendo* → *porque estava chovendo*
- *neste momento / no presente momento* (as filler) → *agora*
- *tem a capacidade de processar* → *consegue processar*
- *é importante destacar que os dados mostram* → *os dados mostram*
- *no que diz respeito a* → *sobre / quanto a*

**Excessive hedging.** *Poderia possivelmente talvez ser argumentado que...* → *É possível que...*

**Generic positive conclusions.** *O futuro é promissor. Tempos empolgantes estão por vir. Um passo na direção certa.* → end on a concrete fact, or just stop.

## Rhetoric

**Persuasive authority tropes.** *A verdadeira questão é, no fundo, na realidade, o que realmente importa, fundamentalmente, o cerne da questão* — ceremony before an ordinary point. Cut the frame; keep the point.

**Signposting / announcements.** *Vamos mergulhar, vamos explorar, vamos destrinchar, aqui está o que você precisa saber, sem mais delongas.* Don't announce what you're about to do — do it.

**Fragmented headers.** A heading followed by a one-line restatement before the real content. Delete the warm-up line.

**Diff-anchored writing.** Docs/comments that narrate a change instead of describing the thing as it is. Unless it's a changelog or migration guide, it should read coherently without knowing the last commit. *Esta função foi adicionada para substituir a abordagem anterior...* → *Esta função usa um hash map para busca O(1).*

**Manufactured punchlines / staccato drama.** A run of short fragments to force drama. One short sentence for emphasis is fine; a stack is engineered.

**Aphorism formulas.** *X é a linguagem de Y, X vira uma armadilha, X não é uma ferramenta, é um espelho, a arquitetura de, a moeda de.* Replace the formula with the concrete claim it gestures at.

**Conversational fake-candid openers.** *Olha,, Sinceramente?, Vou ser honesto:, A real é que, Cá entre nós* — as standalone hooks before a routine point. A person being honest usually just says the thing.

---

## What NOT to flag (false positives)

A clean human writer hits several of these without any AI involvement. Before rewriting, make sure you're not gutting good prose:
- **Polish ≠ AI.** Plenty of people write clean, edited Portuguese.
- **Mixed casual + formal register** often signals a real person in a technical field, not a chatbot.
- **One connector** (*um No entanto*), **one formal word**, **one short emphatic sentence**, a **salutation or sign-off** — none of these is a tell on its own.
- Look for **clusters**, not isolated hits. A single *No entanto* means nothing; *No entanto* + rule-of-three + *tapeçaria vibrante* + a "Conclusão" section is a confession.

## Signs of human writing (preserve these)
- Specific, hard-to-fabricate detail (a real address, a weird quote, an oddly exact number).
- Mixed feelings and unresolved tension ("acho que no geral é bom, mas tem algo que me incomoda e não sei dizer o quê").
- Dated, era-bound references (slang, memes tied to a specific year/subculture).
- Choices the writer could defend if asked.
- Real variety in sentence length.
- Genuine asides, parentheticals, self-corrections.

When these are present, lean toward leaving the prose alone. Over-editing destroys exactly what makes it sound human.
