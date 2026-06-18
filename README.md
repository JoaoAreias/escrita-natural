# escrita-natural

*Uma skill para o Claude escrever em português do jeito que um brasileiro escreveria, sem cara de tradução e sem cara de IA.*

Texto gerado por IA em português costuma soar artificial de dois jeitos. Ou parece traduzido do inglês, com a estrutura da língua estrangeira aparecendo por baixo, ou parece escrito por um chatbot, cheio de frase inflada e entusiasmo genérico. Essa skill ataca os dois.

## Os dois problemas

### Cara de tradução

O sotaque que o texto ganha quando alguém (ou um modelo) traduz palavra por palavra em vez de reescrever a partir do sentido. Aparece em falso cognato (*realizar* no lugar de *perceber*), voz passiva demais, pronome e possessivo sobrando (*ele levantou a sua mão*), conector calcado e vocabulário sem graça. Quase nunca está "errado", só soa estrangeiro.

### Cara de IA

O registro de chatbot. Inflar a importância de tudo, encher de gerúndio pra fingir profundidade, abrir com "Ótima pergunta!", fechar com "o futuro é promissor", dizer tudo em trio. Pode estar em português perfeito e mesmo assim entregar que nenhuma pessoa escreveu aquilo.

## Como funciona

A ideia central vem da teoria interpretativa da tradução: em vez de verter o inglês direto, você descarta a forma e fica só com o sentido, e aí reescreve do zero, como um brasileiro escreveria pra aquele público. O alvo é a mesma reação no leitor, não as mesmas palavras.

Na prática, a skill separa o trabalho em duas frentes, uma pra cara de tradução e outra pra cara de IA, e fecha com uma revisão. Antes de publicar, você se pergunta "um brasileiro escreveria isso espontaneamente?" e "isso soa como pessoa ou como chatbot?", e corrige o que sobrou.

## O que tem dentro

- `SKILL.md`: o método, os cinco sinais de texto traduzido, os sete grupos de cara de IA, a calibragem de tom e a revisão final.
- `references/translationese-pt.md`: as tabelas completas com exemplos (inglês → tradução literal → natural) e um dicionário de falsos cognatos.
- `references/ai-speech-pt.md`: o catálogo completo dos padrões de cara de IA adaptado pro português.

## Quando usar

Vale pra quase qualquer texto em português que uma pessoa vai ler: post, artigo, email, mensagem, relatório, copy, trabalho acadêmico. Serve também pra adaptar conteúdo do inglês sem deixar com jeito de tradução.

Não vale pra código, dado bruto ou texto técnico em que a fidelidade literal pesa mais que a fluência. Nesses casos, traduzir mais perto do original é a escolha certa.

## Como instalar

Baixe o arquivo `escrita-natural.skill` e suba nas configurações de skills do Claude. Depois é só pedir um texto em português que ela entra em ação, mesmo sem você citar "deixa mais natural" ou "tira a cara de tradução".

## Exemplo

Antes (traduzido e com cara de IA):

> Nós estamos extremamente empolgados em anunciar que a nossa nova funcionalidade de colaboração está disponível. Projetada para revolucionar o trabalho em equipe, representa um marco em nossa jornada rumo à excelência.

Depois:

> Chegou o novo recurso de colaboração. Agora dá pra trabalhar junto no mesmo lugar, sem trocar arquivo por email. Testa lá.

Mesma mensagem, sem a estrutura do inglês e sem o entusiasmo de release corporativo.

## Créditos

A parte de cara de IA é adaptada do guia "Signs of AI writing" da Wikipédia (projeto WikiProject AI Cleanup) e da skill humanizer. A parte de cara de tradução se apoia na pesquisa sobre translationese e nos universais da tradução: explicitação, simplificação, normalização, interferência e nivelamento.

## Licença

Sem licença definida ainda. Se for abrir pro público, vale escolher uma (a MIT é comum pra projetos assim).