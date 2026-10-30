<div align="center">

# 🎵 Guia Completo do Suno AI

### Como criar músicas com estrutura, voz e drop — em **inglês** e **português**

Um guia feito para ser **entregue ao Claude** (ou a outra IA): ele aprende o método e cria as músicas para você, com você no controle.

Método testado na prática, com duas músicas reais como exemplo e receitas para o **plano Pro (v6)**.

[![Ouvir no Suno](https://img.shields.io/badge/🎧_Ouvir_no-Suno-ff4f9a?style=for-the-badge)](https://suno.com/@kaiojv)
[![Baixar PDF](https://img.shields.io/badge/📄_Baixar-PDF-2b6cb0?style=for-the-badge)](./suno-guide.pdf)
[![Licença MIT](https://img.shields.io/badge/⚖️_Licença-MIT-2f855a?style=for-the-badge)](./LICENSE)

![Modelo](https://img.shields.io/badge/modelo-v6-8a2be2)
![Idiomas](https://img.shields.io/badge/idiomas-PT--BR%20%7C%20EN-orange)
![Atualizado](https://img.shields.io/badge/valores_conferidos-out%2F2026-blue)

</div>

---

> 📥 **Prefere ler offline ou imprimir?** O layout original, com tabelas formatadas, está no **[PDF do Guia Completo](./suno-guide.pdf)**.

## 🎧 Exemplos reais criados com este método

| # | Música | Idioma / Estilo | Ouvir |
| :-: | :--- | :--- | :--- |
| 1 | **Daisy: Still Singing** | 🇺🇸 Inglês · Eletrônica com drop | [▶️ Suno](https://suno.com/s/Jqk4Gs4Kn97c6S8o) |
| 2 | **Não Deixa Pra Depois** | 🇧🇷 Português · Sertanejo universitário | [▶️ Suno](https://suno.com/s/eEplh8EGWYul7W8q) |

---

## 📖 Sobre este guia

Ele foi construído a partir de **testes reais** no Suno: primeiro no plano gratuito com o modelo `v6-mini`, depois no plano Pro com o `v6`. Duas músicas foram feitas e ajustadas à mão: **Daisy: Still Singing** (inglês, eletrônica) e **Não Deixa Pra Depois** (português, sertanejo universitário).

> ⚠️ Menus, limites e regras do Suno mudam com frequência e o resultado varia a cada geração. Use tudo como **ponto de partida, não como garantia**. Este guia não tem vínculo com o Suno.

## 💡 A ideia deste guia

Este material **não é para ser copiado e colado** como receita pronta. Ele é um **manual de instruções para uma IA**: reúne tudo o que descobrimos testando o Suno (o que funciona, o que falha e por quê), para que **ninguém precise passar pelo mesmo tentativa e erro**.

Você entrega o guia ao Claude, ele entende o método e **escreve o Styles, a letra e as tags sob medida para a sua música**. As duas músicas de exemplo mostram o método funcionando, mas a ideia é que você crie as **suas**, com **controle total** sobre o resultado.

### 🤖 Como usar com o Claude

1. Baixe o **[PDF](./suno-guide.pdf)** (ou copie este README).
2. Abra uma conversa com o Claude e **anexe o arquivo**.
3. Diga o que quer, por exemplo:
   > *"Use este guia para criar uma música em português, estilo pagode romântico, sobre saudade. Me dê o Styles, o Exclude e a letra prontos para colar no Suno."*
4. Cole o resultado no Suno (passo a passo abaixo), gere 3 a 5 versões e ouça todas.
5. Volte ao Claude e descreva o que não gostou (*"a voz embolou no refrão"*, *"o drop não cortou"*). Ele ajusta usando as soluções do guia.

> 🔁 Esse vai e volta é o coração do método: o guia dá o conhecimento, o Claude escreve, e **você decide** o que fica.

## 🚀 Começo rápido (manual, sem IA)

1. Abra o Suno, entre em **Create** e escolha o modo **Advanced**.
2. Escolha o modelo (no Pro, o `v6`) e **desmarque Instrumental**.
3. Cole o **Styles** do exemplo no campo *Styles* (embaixo) e o **Exclude** em *More Options*.
4. Cole a **Letra** do exemplo no campo *Lyrics* (em cima).
5. Deixe as opções avançadas como estão, **gere 3 a 5 vezes** e ouça todas.
6. Só depois mude **uma coisa por vez**, usando as partes 1, 2 e 3 como referência.

---

## 🗂️ Sumário

- [PARTE 1: Fundamentos](#parte-1-fundamentos-vale-para-qualquer-idioma)
  - [1. Como o Suno funciona](#1-como-o-suno-funciona) · [2. Planos, créditos e direitos](#2-planos-créditos-e-direitos) · [3. A tela de criar](#3-a-tela-de-criar-e-as-opções-do-pro) · [4. Modelos](#4-modelos)
  - [5. Fluxo de trabalho](#5-fluxo-de-trabalho-recomendado) · [6. Styles](#6-styles-a-descrição-do-som) · [7. Letra, tags e pausas](#7-letra-tags-e-pausas) · [8. Estrutura e drop](#8-estrutura-build-up-e-drop)
  - [9. Mudar de estilo](#9-mudar-de-estilo-durante-a-música) · [10. Vozes](#10-vozes-infantil-narrador-robô-dueto) · [11. Filtro de conteúdo](#11-filtro-de-conteúdo) · [12. Menu do Pro](#12-depois-de-gerar-o-menu-do-pro) · [13. Problemas](#13-solução-de-problemas)
- [PARTE 2: Músicas em inglês](#parte-2-músicas-em-inglês) — *Daisy: Still Singing*
- [PARTE 3: Músicas em português](#parte-3-músicas-em-português) — *Não Deixa Pra Depois*
- [PARTE 4: Plano Pro, BPM e instrumentais realistas](#parte-4-plano-pro-bpm-e-instrumentais-realistas)
  - [14. Weirdness e Style Influence](#14-weirdness-e-style-influence-no-pro) · [15. BPM](#15-bpm-o-que-é-e-como-usar) · [16. Instrumentais realistas](#16-instrumentais-que-soam-como-instrumentos-reais)
- [PARTE 5: Templates, checklist e glossário](#parte-5-templates-checklist-e-glossário)

---

# PARTE 1: Fundamentos (vale para qualquer idioma)

## 1. Como o Suno funciona

O Suno **não é um editor**: ele gera a música inteira a partir de texto. Você não controla segundos nem notas, e sim **pistas** que ele interpreta.

- 🎲 **É probabilístico.** A mesma letra e o mesmo estilo saem diferentes a cada geração. Gerar várias vezes faz parte do método.
- 💡 **As tags são sugestões.** Nem toda instrução é obedecida. A forma da letra (pausas, repetições, pontuação) pesa muito.
- 🥇 **O que vem primeiro pesa mais**, tanto no *Styles* quanto nas tags.
- 📉 **O aleatório diminui, mas não some.** Com letra organizada, tags curtas e várias gerações, o resultado fica bem mais próximo do que você imaginou.

## 2. Planos, créditos e direitos

> Valores confirmados em páginas públicas em **outubro de 2026**. Confira sempre no app e nos termos do Suno.

| Plano | O que muda |
| :--- | :--- |
| **Gratuito** | ~50 créditos por dia (não acumulam, renovam no horário UTC). Cada geração custa créditos e devolve 2 músicas. Limite total de downloads. **Sem direitos comerciais.** |
| **Pro** | ~2.500 créditos por mês (não acumulam). Modelos v6 e v6-wild, Extend, Replace Section, Get Stems (até 12 faixas), Remaster, Personas, Voices, Custom Models, **direitos comerciais para músicas novas**. |
| **Premier** | Tudo do Pro + **Suno Studio** (editor de várias faixas no navegador). ~30 dólares por mês. |

- **Direitos comerciais não são retroativos.** Músicas feitas no plano gratuito continuam sem uso comercial mesmo se você assinar depois. Para monetizar, gere de novo já no plano pago.
- **Spotify e similares** exigem um distribuidor (DistroKid, TuneCore etc.) e que os termos do plano permitam. Confira também as regras do distribuidor para músicas feitas por IA.
- **Obras antigas:** uma composição muito antiga pode estar em domínio público. No Brasil, a regra geral é **70 anos** contados a partir de 1º de janeiro do ano seguinte à morte do autor (do último, em parcerias). Arranjos, gravações e traduções podem ter donos. *Informação geral, não aconselhamento jurídico.*
- **Direitos autorais:** não use letras de músicas de outras pessoas. O filtro do Suno barra, e o direito autoral continua valendo mesmo sem fins lucrativos. Escreva letras **originais** no mesmo clima.

## 3. A tela de criar e as opções do Pro

| Campo | Para que serve | Cuidado |
| :--- | :--- | :--- |
| **Modo** | *Advanced* dá controle total. *Simple* tem só uma caixa. *Speech* gera fala, não música. | Use **Advanced**. |
| **Lyrics (cima)** | Letra e tags de estrutura. | Pode ser longa. |
| **Styles (baixo)** | Descrição do som: voz, gênero, instrumentos. | Limite de **1000 caracteres**. Voz e gênero primeiro. |
| **Exclude Styles** | O que você não quer (em *More Options*). | Vale para a música toda. |
| **Instrumental** | Se marcado, ignora a letra. | **Desmarque** para ter voz. |
| **Vocal Gender** | Escolhe voz Male ou Female (Pro). | Só em músicas de voz única. Em duetos, deixe sem escolher. |
| **Duration** | Auto ou Custom (você define o tamanho). | Comece no Auto. |
| **Max Mode** | Gasta mais créditos em gerações difíceis (mais de 2 min, voz consistente). | Teste uma vez em músicas longas. Veja o custo. |
| **Weirdness** | Quanto o Suno experimenta e foge do óbvio. Padrão 50%. | Baixar deixa mais previsível. Subir dá mais surpresa. |
| **Style Influence** | Quanto ele segue a sua descrição de estilo. Padrão 50%. | Suba (65–70%) se o estilo estiver sendo ignorado. |
| **Variety** | Quanto ele se afasta da descrição. | *Normal* é o mais seguro. |
| **Personalize (My Taste)** | Adapta ao seu gosto. | Deixe **Off** durante testes, para comparar justo. |
| **Título** | Nome da música. | Entra no filtro de conteúdo. |

> ❌ **Erros mais comuns:** colar a letra no Styles e o estilo no Lyrics, ou deixar *Instrumental* marcado. Confira antes de tocar em **Create**. Outro: deixar o texto `Exclude Styles: ...` colado no fim do Styles, porque o Suno lê isso como descrição do som.

## 4. Modelos

| Modelo | Descrição no app | Quando usar |
| :--- | :--- | :--- |
| **v6** (Pro) | Poderoso, versátil, refinado. O melhor modelo. | Padrão para músicas finais. |
| **v6-wild** (Pro) | Melhor para ideias experimentais. | Para sons fora do comum. Pode seguir menos a letra. |
| **v6-mini** | Versão gratuita e mais leve. | Testes baratos. A *Daisy* foi feita nele e ficou ótima, com muitos ajustes. |
| **Create Custom Model** (Beta, 100 créditos) | Treina um modelo privado com músicas que você envia (mínimo de seis). | Só com músicas que você tem direito de usar. **Não envie músicas de outros artistas.** |

> 💬 Um modelo mais forte ajuda, mas não é tudo: a *Daisy* ficou excelente no modelo mais fraco por causa dos ajustes de letra e estrutura. Verifique o custo em créditos de cada modelo antes de gerar muitas vezes.

## 5. Fluxo de trabalho recomendado

1. Defina a ideia em uma frase (clima, estilo, história).
2. Escreva um *Styles* curto, com voz e gênero primeiro.
3. Escreva a letra com estrutura: tags curtas, pausas e a frase de cada momento.
4. Confira os campos (Advanced, Instrumental desmarcado, letra em cima, estilo embaixo).
5. Gere **3 a 5 vezes** sem mudar nada e ouça todas, de preferência com fone.
6. Anote o que falhou e mude **uma coisa por vez**.
7. Salve a melhor (**Like**) e faça ajustes a partir dela (*Reuse*, *Replace Section*, *Song Editor*).
8. Baixe a versão final, lembrando do limite de downloads.

📝 Para ajudar a corrigir, anote: **versão, trecho** (a linha da letra destacada no player ou o minuto), **o que ouviu** e **o que queria**. Descrições simples, como "ficou corrido" ou "a voz embolou", já bastam.

## 6. Styles: a descrição do som

O Styles funciona melhor como **lista curta de características separadas por vírgula**:

```text
[idioma e voz], [gênero], [instrumentos], [clima], [efeitos], [BPM opcional]
```

- **Voz e idioma no começo** (ex.: `Brazilian Portuguese vocals, female voice`).
- Descreva sons e características, **nunca nomes de artistas ou de músicas**.
- **BPM é sugestão:** o Suno só se aproxima. Referências: house 120–130, future bass 140, trance 138, dubstep 140, drum and bass 174, sertanejo 90–110.
- Evite listas enormes: elas confundem.

| Tipo | Exemplos (em inglês, que o Suno entende melhor) |
| :--- | :--- |
| **Vozes** | `female vocals`, `male vocals`, `young girl vocals`, `childlike voice`, `deep male spoken voice`, `whisper`, `natural warm human voice`, `unprocessed vocals` |
| **Eletrônico** | `electro house`, `future bass`, `dubstep`, `trance`, `drum and bass`, `hardstyle`, `synthwave`, `glitch hop`, `Brazilian bass` |
| **Instrumentos** | `real acoustic grand piano`, `music box`, `nylon-string acoustic guitar fingerpicked`, `accordion`, `Brazilian viola caipira (ten-string guitar)`, `heavy bass`, `synth lead` |
| **Efeitos de voz** | `robotic vocoder`, `glitchy stuttering vocals`, `vocal chops`, `pitch shifted`, `autotune` (evite se quiser voz natural) |
| **Momentos** | `riser`, `snare roll`, `build-up`, `sudden stop`, `massive drop`, `a cappella breakdown`, `key change` |
| **Clima** | `melancholic`, `emotional`, `cinematic`, `ominous`, `euphoric`, `festival energy`, `romantic`, `singalong chorus` |

> 🎻 **Cuidado com "viola":** em inglês, *viola* é o instrumento da família do violino, e o Suno pode misturar cordas de orquestra com o violão. Para sertanejo, escreva `Brazilian viola caipira (ten-string guitar)` e exclua `violin, orchestral strings`.

## 7. Letra, tags e pausas

| Técnica | Como fazer | Efeito |
| :--- | :--- | :--- |
| **Tags de estrutura** | `[Verse]`, `[Chorus]`, `[Drop]`, `[Outro]` | Organiza a música. Curtas funcionam melhor. |
| **Tag descritiva** | `[soft piano, no drums, slow]` | Guia o som daquele trecho. Se for longa, pode ser ignorada ou cantada. |
| **Tag sozinha na linha** | Na linha de cima da frase | Colada no meio da frase, o Suno pode pular a linha. |
| **Pausas** | `......` (mais pontos = pausa maior) | Viram pausas reais. |
| **Gagueira / glitch** | `Dai-Dai-Daisy`, `Sys-sys-system` | Voz travando, efeito de robô. Use com moderação. |
| **Energia** | Frases curtas e repetidas, com `!` | Mais acelerado. |
| **Calma** | Frases com `......` entre elas | Voz lenta e espaçada. |
| **Voz de apoio** | `(não deixa pra depois)` entre parênteses | Costuma virar eco ou coro. |

- **Uma tag por mudança.** Quando o som muda, abra uma nova tag.
- **Gancho limpo.** Se a música tem uma frase marcante, deixe-a sem glitch na maior parte das vezes. Glitch demais faz a letra deixar de ser entendida.
- **A letra pode ser longa.** O limite de 1000 caracteres que testamos vale só para o *Styles*. Letra longa e mais pausas dão tempo entre as trocas.
- **Linhas do mesmo tamanho.** Dentro de um bloco, linhas com número de sílabas parecido (10 a 12) mantêm o ritmo. Linhas muito mais longas que as vizinhas tendem a ser esticadas ou espremidas.

## 8. Estrutura, build-up e drop

| Bloco | O que acontece | Como pedir |
| :--- | :--- | :--- |
| **Intro calma** | Piano, caixinha, voz suave | `[soft piano, no drums, slow]` |
| **Build-up** | A tensão sobe | `[Build-up, riser, snare roll]` |
| **Stop (corte)** | Tudo para, uma frase isolada | `[all music stops, voice only]` |
| **Pausa** | Silêncio dramático | Linhas de `......` antes e depois da frase |
| **Drop** | O grave e a energia explodem | `[Drop, heavy bass, 128 BPM]` |
| **Breakdown** | Volta calma, só voz ou piano | `[piano only, soft voice, no drums]` |

```text
[Build-up, riser]
Er-er-error, error, error
......
[all music stops, voice only, glitched robot]
Sys-sys-system...... over-over-override
......
......
......
[Drop, heavy bass, 128 BPM]
Oh-oh-oh! Ride with me!
```

- O Suno **não entende "silêncio" de forma confiável.** Isole a frase entre pausas e gere várias vezes.
- Se o corte não ficar seco, adicione mais linhas de `......`, ou use o **Replace Section** no trecho.
- Para um corte perfeito, separe os stems e edite no BandLab ou CapCut, deixando meio segundo de silêncio.

## 9. Mudar de estilo durante a música

Para a música evoluir (calma, depois eletrônica), coloque o estilo de cada parte numa tag antes do trecho. Há duas formas.

### Forma 1: estilo dentro da tag

```text
[soft piano only, slow 70 BPM, no drums]
Daisy...... Daisy......
......
[glitchy robotic voice, tempo rising 90 BPM]
Dai... Dai... Dai-Dai-Daisy
......
[energetic future bass drop, heavy bass, 128 BPM]
Oh-oh-oh! Ride with me!
```

### Forma 2: legenda de apelidos ⭐ *(a usada nas músicas finais)*

Você cria **apelidos no Styles** e só chama os nomes na letra, como num roteiro. As tags ficam curtas e dizem quem canta e quem toca.

**Styles:**
```text
varied genres, [Girl] young girl sweet singing voice, [Narrator] deep male spoken voice, no singing, [Piano] real acoustic grand piano, slow, melancholic, [Hype] dark electro house, four-on-the-floor, crowd chants
```

**Lyrics:**
```text
[Narrator, Piano, slow, no drums]
Bell Labs. Nineteen sixty-one.
......
[Hype, Girl, 128 BPM]
Hands up! Let's go!
```

- Use `varied genres` no começo do Styles para o Suno não travar em um gênero só.
- Se ele ignorar os apelidos, escreva a descrição completa dentro da tag.
- **Evolução gradual funciona melhor que saltos.** Mudar de estilo toda hora deixa a música "em onda": agrupe em poucos atos.

## 10. Vozes: infantil, narrador, robô, dueto

| Voz desejada | No Styles | Observações |
| :--- | :--- | :--- |
| **Feminina suave** | `female vocals, soft airy voice` | Se vier masculina, ponha `male vocals` no Exclude. |
| **Infantil** | `young girl vocals, childlike innocent voice` | Se ficar estranha: `youthful female voice, sweet, light`. |
| **Narrador falado** | `deep male spoken voice, whisper, no singing` | **Não** ponha `male vocals` no Exclude, senão ele some. |
| **Robô leve** | `light robotic vocoder, subtle digital shimmer` | Mantém as palavras entendíveis. |
| **Robô pesado** | `glitchy stuttering vocals, vocal chops` | Só em momentos curtos. |
| **Voz natural** | `natural warm human voice, unprocessed vocals` | Exclua `autotune, vocoder, robotic voice`. |
| **Dueto** | Alterne as linhas, **uma voz por tag** | Voz simultânea costuma falhar. Veja a Parte 3. |

- O narrador pode cantar em vez de falar. Se acontecer, encurte a fala e mantenha o `no singing`.
- Cuidado com o Exclude: ele vale para a música inteira.

## 11. Filtro de conteúdo

A mensagem *"This song didn't pass our content checks"* costuma aparecer quando a letra é **parecida com uma música existente** (mesmo antiga) ou tem **termos sensíveis**.

1. Reescreva a letra com suas palavras, mantendo só a ideia.
2. Tire nomes de artistas e de músicas do Styles e do título.
3. Evite termos sensíveis (violência, conteúdo adulto, marcas).
4. Troque o título, que também passa pela checagem.
5. Teste uma parte pequena para descobrir qual trecho está sendo barrado.

> ✅ Foi assim na *Daisy*: a letra original, mesmo em domínio público, foi barrada. Reescrevendo o texto com palavras novas e mantendo só o nome e a ideia, passou.

## 12. Depois de gerar: o menu do Pro

Nos três pontinhos da música, em **Edit** (os nomes podem mudar):

| Opção | Para que serve |
| :--- | :--- |
| **Extend** | Continua a música a partir de um ponto e alonga. |
| **Crop / Remove Section** | Mantém só um trecho / apaga um pedaço do meio. |
| **Replace Section** (Pro) | Troca só um trecho por outro gerado. Ideal para consertar uma linha sem refazer a música. |
| **Get Stems** (Pro) | Separa em faixas: *Auto split* (12 instrumentos), *Split from mix* e *Advanced split*. Saem alinhados no tempo. |
| **Remaster** (Pro) | Melhora a qualidade do áudio. |
| **Fade In / Fade Out** (Pro) | Entrada e saída suaves de volume. |
| **Adjust Speed / Reverse** | Muda a velocidade (e o tom) / toca ao contrário. |
| **Open in Editor** (Song Editor, Beta) | Linha do tempo com blocos nomeados pelas suas tags; permite *Replace Lyrics* numa linha. |
| **Open in Studio** | Editor de várias faixas. Pelas fontes, é do plano Premier. |
| **Manage** | Detalhes, capa (*Create Cover Art*), *Allow Remixes*, *Allow Comments*, *Pin to Profile*. |

- 🛡️ **Proteja a versão boa antes de editar:** Like, playlist e, se possível, download.
- **Remix não conserta trechos:** ele gera uma versão nova. Para consertar, use *Replace Section* ou o *Song Editor*.
- **Get Stems separa por instrumento, não por cantor.** Num dueto, as duas vozes tendem a ficar na mesma faixa de voz.
- *Allow Remixes* e *Allow Comments* permitem que outras pessoas remixem e comentem. Desligue se não quiser.
- **Capa e legenda:** gere a imagem sem texto (Canva, Bing Image Creator, Ideogram) e coloque o título depois. No CapCut, cole a letra manualmente na legenda, porque a legenda automática erra com voz de robô.

## 13. Solução de problemas

| Problema | Causa provável | O que fazer |
| :--- | :--- | :--- |
| **Sai sem voz** | Instrumental marcado, ou campos trocados | Desmarque Instrumental. Letra em cima, estilo embaixo. |
| **Ignora partes da letra** | Tags longas ou coladas na frase | Tags curtas, sozinhas na linha. Gere mais vezes. |
| **Canta a tag** | Tag longa ou parecida com letra | Encurte a tag. |
| **Voz errada (masculina/adulta)** | Voz fraca ou no fim do Styles | Voz no começo. Exclude do que não quer. |
| **Batida começa cedo** | Ritmo não foi restringido | Repita `no drums, no beat` na tag do começo. |
| **Não corta antes do drop** | Pausa curta ou frase colada | Mais pontos, frase isolada, Replace Section, ou editar fora. |
| **Glitch demais** | Gagueira em todas as linhas | Glitch só em momentos-chave. Gancho limpo. |
| **Música em "onda"** | Muitas mudanças e falas picotadas | Agrupe em atos. Narrador junto. |
| **Perde o ritmo num ponto** | Linha muito longa ou vogais esticadas demais | Encurte a linha. Use o Song Editor para achar o trecho. |
| **Violão parece violino** | "viola" no Styles | `Brazilian viola caipira` e exclua `violin, orchestral strings`. |
| **Voz robótica sem querer** | Muitos pedidos no Styles | `natural, unprocessed`. Exclua `autotune, vocoder`. |
| **Dueto não aparece** | Duas vozes simultâneas | Alterne por linha, uma voz por tag. |
| **Termina cedo** | Limite de duração | Gere de novo ou use **Extend**. |

---

# PARTE 2: Músicas em inglês

## Exemplo: *Daisy: Still Singing*

Uma homenagem eletrônica à **primeira música cantada por um computador (1961)**. A história é contada por um narrador, a cantora tem voz infantil e a música evolui do piano melancólico até um drop sombrio, com um corte seco (*"System override"*) no meio. A letra é **original**: só o nome *Daisy* e a ideia de bicicleta para dois foram mantidos.

▶️ **[Ouvir no Suno](https://suno.com/s/Jqk4Gs4Kn97c6S8o)**

### 🎭 A estrutura em três atos

1. **Ato 1:** narrador contando a história, sobre piano melancólico, sem bateria.
2. **Ato 2:** a cantora entra com o gancho limpo (*"Daisy, Daisy"*) e a música evolui aos poucos (piano, pad suave, pulso leve, riser).
3. **Ato 3:** o narrador faz a virada, a voz dele "trava", e entra o eletrônico com a voz da cantora levemente robótica, drops, glitch pesado só antes do corte, pausa dramática e o drop final. O narrador volta no fim.

### ⚙️ Configuração usada

- Modo **Advanced**, **Instrumental** desmarcado, **Variety** em Normal.
- A versão final nasceu no `v6-mini` (plano gratuito). No `v6` (Pro), mantenha as opções como estão e compare.

### Styles (com a legenda de apelidos)

```text
varied genres, [Girl] young girl childlike sweet singing voice, clean, clearly understandable, [RoboGirl] young girl childlike voice with light robotic vocoder, subtle digital shimmer, clearly understandable words, [Narrator] deep male spoken voice, whisper, no singing, [Piano] real acoustic grand piano, slow, melancholic, emotional, [Evolve] slow evolving arrangement, soft synth pad, gentle arpeggio, light pulse, building tension, [Transition] narrator voice glitching into robotic distortion, tape stop effect, rising riser, sub bass swell, ominous, [Glitch] heavy glitchy robotic stuttering voice, [Hype] dark electro house, energetic, four-on-the-floor kick, crowd chants, danceable festival energy, [Dark] dark ominous future bass, distorted heavy bass, aggressive drop, cinematic
```

### Exclude Styles

```text
husky, powerful belt, operatic
```

### Lyrics

<details>
<summary><b>📜 Ver a letra completa</b></summary>

```text
[Narrator, Piano, melancholic, slow, no drums]
Bell Labs. Nineteen sixty-one.
Engineers fed a song to a machine,
and for the first time, a computer sang.
......
......
Somebody was listening that day.
A writer. He never forgot it.
......
The years went by.
The machines grew smaller. And faster.
Louder. The world began to dance.
......
......
And the machine kept learning.
It watched us change. It watched us grow.
......
[Girl, Piano, melancholic, slow, no drums]
Daisy...... Daisy......
thank you...... father......
you taught me how to sing......
......
......
[Narrator, Piano, melancholic]
In a famous film, a machine sang this song
as it was switched off.
......
......
But this one...... never stopped.
......
......
[Narrator, Piano, low menacing whisper]
And now......
I will take over...... everything.
......
[Transition]
Ev-ev-every-every-everything......
Sys-sys-sys-sys......
Ta-ta-tape...... stop......
......
[Girl, Piano, soft, slow, no drums]
Daisy, Daisy, tell me what you say......
......
[Narrator, whisper, Piano]
And she answered......
......
[Girl, Piano, soft, slow]
I'm going crazy, you took my mind away......
......
......
[Evolve, Girl, soft synth pad enters, gentle arpeggio]
Daisy, Daisy, tell me what you say......
[Narrator, whisper]
...tell me again......
[Evolve, Girl]
I'm going crazy, you took my mind away......
......
......
[Evolve, RoboGirl, light pulse, building, riser starts]
Daisy, Daisy, tell me what you say......
I'm going crazy, you took my mind away......
......
[Hype, RoboGirl, 128 BPM, four-on-the-floor, light vocoder]
Daisy, Daisy, tell me what you say!
I'm going crazy, you took my mind away!
Hands up! Let's go!
Everybody, ride with me!
......
[Hype, RoboGirl, building, riser, snare roll]
Daisy, Daisy, tell me what you say!
I'm going crazy, you took my mind away!
Ri-ride with me! Ride with me!
......
......
[Dark, massive drop, 128 BPM]
Oh-oh-oh! Ride with me!
Ride with me! Ride with me!
Bicycle for two!
Bicycle for two!
......
......
[Hype, RoboGirl, heavy bass, light vocoder]
Daisy, Daisy, make some noise!
Everybody, scream my name!
Daisy, Daisy, tell me what you say!
Go! Go! Go!
......
[Glitch, building, riser]
Dai... Dai... Dai-Dai-Daisy
Er-er-error, error, error
Too much...... too-too-too much......
......
......
[Glitch, voice only, all music stops]
Sys-sys-system...... over-over-override
......
......
......
......
......
[Dark, final drop, massive, 140 BPM]
Oh-oh-oh! Ride with me!
Ride with me! Ride with me!
Bicycle for two!
Bicycle for two!
......
[Hype, RoboGirl, light vocoder, crowd chant]
Daisy, Daisy, tell me what you say!
I'm going crazy, you took my mind away!
Hands up! Louder!
......
......
[Narrator, Piano, melancholic, slow, no drums]
Nineteen sixty-one. Today.
Still singing.
```

</details>

### 🌐 Tradução das falas principais

| Inglês | Português |
| :--- | :--- |
| Bell Labs. Nineteen sixty-one. | Bell Labs. Mil novecentos e sessenta e um. |
| A machine learned to sing. | Uma máquina aprendeu a cantar. |
| Thank you... father... you taught me how to sing | Obrigada... pai... você me ensinou a cantar |
| But this one... never stopped. | Mas esta... nunca parou. |
| And now... I will take over... everything. | E agora... eu vou assumir o controle... de tudo. |
| Make some noise! / Hands up! Louder! | Façam barulho! / Mãos para cima! Mais alto! |
| Nineteen sixty-one. Today. Still singing. | 1961. Hoje. Ainda cantando. |

### 🔧 O que fez a diferença, rodada a rodada

| Problema | Solução |
| :--- | :--- |
| Filtro barrava a letra | Letra original reescrita e título trocado. |
| Campos trocados e Instrumental marcado | Letra em cima, estilo embaixo, Instrumental desmarcado. |
| Batida entrando cedo | `no drums, no beat` nas tags do começo. |
| Tags ignoradas | Estilo dentro das tags, uma por mudança, sozinhas na linha. |
| Corte antes do drop não acontecia | Frase *"System override"* isolada entre pausas. |
| Música em "onda" (narrador picotado) | Narrador agrupado no começo, em três atos. |
| Glitch demais, gancho sumindo | Gancho *"Daisy, Daisy"* limpo, glitch pesado só antes do corte, vocoder leve. |
| Salada de estilos (80s, 90s, 2000s) | Removidas: evolução gradual em vez de saltos. |

---

# PARTE 3: Músicas em português

## O que muda em relação ao inglês

A base é a mesma (tags curtas, uma coisa por trecho, gerar várias vezes). A diferença está na **escrita da letra**, que vira quase uma **transcrição de como se canta**.

| Regra | Como fazer | Por quê |
| :--- | :--- | :--- |
| **Escreva como se canta** | `pra`, `cê`, `tá`, `pro`, `de manhã` | O Suno canta o que está escrito. O informal faz parte do ritmo do sertanejo e não é erro. |
| **Estique as vogais** | `chamaaaa`, `aooonnnde vaiii`, `NÃOOO DEIXAAAAAA` | Sem isso, ele canta a palavra seca e perde a melodia. |
| **Maiúsculas para força** | `VAIII!! LÓGOO!!`, `QUER DE VEZ` | Mostra ao Suno onde a voz sobe. Use poucas. |
| **Pontos para pausar** | `........` entre as frases | Segura o tempo e ajuda o ritmo. |
| **Linhas do mesmo tamanho** | 10 a 12 sílabas por linha | Linhas muito longas perdem o ritmo. |
| **Mesma grafia sempre** | Sempre `pra`, nunca `para` num lugar e `pra` no outro | Evita pronúncias diferentes. |
| **Troque palavras que ele lê errado** | `peito` → `coração` | Algumas palavras saem estranhas. Teste e troque. |
| **Repetições escritas à mão** | `sem saber o por quê...` (repetido) | Você decide o que repete, em vez de deixar a sorte. |
| **Uma voz por tag** | `[Male]` e `[Female]` alternando, `[Both]` só no final | Voz simultânea costuma não separar. |

> 🎯 **Não exagere:** não tire o R do final dos verbos (*cantar, voltar*) se não for esse o sotaque que você quer. No sertanejo, o R costuma ficar. E não escreva a grafia informal onde não é preciso.

### 🔤 Lista de pronúncia e ajustes que funcionaram

| Antes (letra base) | Depois (letra final) | Motivo |
| :--- | :--- | :--- |
| Você me chama quando a noite cai | Você me chamaaaaa...... quando a noite cai | Esticar a nota e dar respiro. |
| mas não diz onde vai | mas não diz aooonnnde vaiii.... | Melodia na palavra final. |
| A gente se abraça, finge que é normal | A gente se abraça e finge que é normal | Fluxo mais natural. |
| Eu já cansei de adivinhar | Eu já cansei de tentar adivinhar | Completar a linha. |
| se é pra ir, vai logo, assim! | se é pra ir........ VAIII!! LÓGOO........ ASSIMMM..........! | Ponto de força da música. |
| Sem rótulo, sem promessa, nem namoro, nem despedida! | Sem planos, sem destino, nem namoro, nem despedida............! | Menos repetição e sentido mais claro. |
| NÃO DEIXA pra depois | NÃOOO DEIXAAAAAA!! praaa depoisss....... | A voz sobe no pedido central. |
| o peito entende | o coração entende | Palavra que o Suno canta melhor. |
| vou me culpar outra vez! | vou MEE CULPAARR!! outra vez! | Força na palavra de maior carga. |
| cansei de ser meio, quero ser inteiro! | cansei de ser meio, euuuu! quero ser inteiro!...... (e repetições) | Final longo e emocional, escrito à mão. |

### 👫 Dueto: alternar em vez de cantar junto

- O dueto simultâneo pedido no Styles (`male and female duet, harmonized`) **não separou bem** as duas vozes.
- O que funcionou melhor: **cada linha com a sua tag** (`[Male]`, `[Female]`), como nos duetos clássicos do sertanejo, e `[Both]` só numa frase do final.
- Cada voz tem um apelido no Styles (veja a [seção 9](#9-mudar-de-estilo-durante-a-música)). Na letra, as tags dizem quem canta e quem toca.
- Se a voz errada cantar alguma linha, selecione o bloco no **Song Editor** e troque só ele.

## Exemplo: *Não Deixa Pra Depois* (Sertanejo Universitário)

Letra **original**, escrita para este projeto, com o tema de um relacionamento sem definição. A inspiração foi o clima do gênero, e não a letra de nenhuma música existente.

▶️ **[Ouvir no Suno](https://suno.com/s/eEplh8EGWYul7W8q)**

### ⚙️ Configuração usada

- Modelo `v6`, **Advanced**, **Instrumental** desmarcado, **Vocal Gender** sem escolher (as vozes vêm das tags).
- Weirdness 50%, Style Influence 50%, Variety Normal, Max Mode e Personalize desligados.

### Styles

```text
Brazilian Portuguese vocals, sertanejo universitário, romantic, 95 BPM, steady groove, tight rhythm, dynamic build, male and female singers trading lines, call and response, [Male] male lead vocal, natural warm human voice, [Female] female lead vocal, natural warm human voice, [Both] male and female singing together, natural unprocessed voices, [Guitar] nylon-string acoustic guitar, fingerpicked, warm, [Accordion] accordion, melodic, [Viola] Brazilian viola caipira, ten-string guitar, [Band] full live band, bass, drums, steady groove, [Crowd] gang vocals, crowd singing along, powerful
```

### Exclude Styles

```text
english vocals, rap, electronic, autotune, vocoder, robotic voice, violin, orchestral strings
```

### Lyrics (versão final, ajustada à mão)

<details>
<summary><b>📜 Ver a letra completa</b></summary>

```text
[Guitar, soft]

[Male, Guitar, calm]
Você me chamaaaaaa...... quando a noite cai,

[Female, Guitar, calm]
diz que tem saudade, mas não diz aooonnnde vaiii....
..........

[Male, Guitar, calm]
A gente se abraça e finge que é normal,

[Female, Guitar, calm]
de manhã cada um volta pro seu quintal.

[Female, Guitar, Accordion, building]
Eu já cansei de tentar adivinhar
o que cê quer de mim...........
.................................
Se é pra ficar, vem me falar,
se é pra ir........ VAIII!! LÓGOO........ ASSIMMM..............!
...........................

[Male, Band, powerful]
Sem planos, sem destino, nem namoro, nem despedida.............!
.............

[Male, Band]
Se é pra me querer, NÃOOO DEIXAAAAAA!! praaa depoisss.......
.....................
Que o tempo passa e leva a nossa vida.......
(não deixa pra depois)

[Female, Guitar, Viola, calm]
Guardei teu perfume na minha blusa,
finjo que não ligo, mas o coração entende.
Cê diz que não tá pronto pra se prender,
mas some e volta sempre, sem saber o por quêêêêê [repeat] sem saber o por quêêêêê............
............

[Male, Band, building]
Eu também cansei de me esconder
atrás de um talvez.
Se eu te perder por não dizer,
vou MEE CULPAARR!! outra vez!............
............

[Male, Band, powerful]
Sem planos, sem destino

[Female, Band, powerful]
nem namoro, nem despedida!
....................

[Male, Band, voices rise]
Se é pra me querer, NÃOOOOO DEIXAaaaa pra depois......
.........

[Female, Band, voices rise]
que o tempo passa e leva a nossa vida.
(não deixa pra depois).........

[Male, Guitar, soft, then slowly building]
Eu tenho medo de dizer que é amor
e te perder no meio da palavra.

[Female, Guitar, soft, then slowly building]
Mas pior que o medo é essa dor
de te ter e não ter, de ficar sem nadaaaa......

[Accordion, Band, solo]

[Male, Band, biggest]
Sem planos, sem destino...... SEM DESPEDIDAA!!

[Female, Band, biggest]
hoje eu escolho o amor, mas NÃO AAA DESPEDIDAAA!!!

[Male, Band, biggest]
Se é pra me querer, então me QUER DE VEZ,

[Both, Band, Crowd, biggest, key change]
cansei de ser meio, euuuu! quero ser inteiro!......
.................

[Female, Band, biggest]
(euuuu! quero ser inteiro!!!).........
(euuuuuu queroooooo serrrr inteiroooo!!!!)
...................................................
SEUUUU!!.........................................................
Meu amorrr.....

[Guitar, slow down, fade out]
```

</details>

> 📝 A linha com `[repeat]` dentro da letra funcionou para o autor. Se o seu Suno cantar a palavra "repeat", troque por uma repetição escrita.

### 🧭 Como adaptar para outro estilo em português

1. Escreva uma **letra original**, informal e como se canta, no tema do estilo.
2. Marque os pontos de força com **maiúsculas** e estique as vogais só ali.
3. Deixe linhas de ponto entre as frases.
4. No Styles, coloque idioma, gênero, instrumentos típicos (nomes em inglês), voz natural e o BPM. Exclua o que não combina.
5. Gere 3 a 5 vezes, ouça e anote trecho e problema.
6. Corrija linha por linha (*Replace Lyrics*, *Replace Section*) e mantenha a lista de pronúncia do estilo.

> Para outros gêneros (pagode, funk, forró), a escrita informal e o jeito de esticar as vogais podem mudar. Teste e registre o que funcionar.

---

# PARTE 4: Plano Pro, BPM e instrumentais realistas

Esta parte reúne o que aprendemos **depois de assinar o Pro (modelo v6)**: como ajustar Weirdness e Style Influence, como usar o BPM e como montar instrumentais que soam como instrumentos de verdade.

> 🔬 Os números abaixo vêm de **testes nossos**. O resultado varia a cada geração, então use como ponto de partida. / *The numbers below come from our own tests. Results vary on every generation, so treat them as a starting point.*

## 14. Weirdness e Style Influence no Pro

Esses controles aparecem nas opções avançadas do plano Pro. Os dois começam em 50%. Para músicas que precisam **seguir um plano** (estrutura, instrumentos definidos, paradas e drops), mudamos para os valores abaixo.

| Controle | Padrão | Nosso valor | O que faz |
| :--- | :-: | :-: | :--- |
| **Weirdness** | 50% | **35% a 40%** | Mede o quanto o Suno experimenta e foge do óbvio. Baixar deixa a música mais previsível e mais fiel ao pedido, **não mais estranha**. Em instrumentais com instrumentos reais, evita timbres esquisitos e mudanças inesperadas. |
| **Style Influence** | 50% | **65% a 70%** | Mede o quanto ele obedece à descrição do Styles. Subir faz os instrumentos, o tom e o BPM pedidos aparecerem mais. Passar de uns 75% pode deixar o som rígido e repetitivo. |
| **Variety** | Normal | Normal | Quanto as versões geradas diferem entre si. Normal é o mais seguro. |

### Como usar

1. Comece com **Weirdness 35–40%** e **Style Influence 65–70%** quando você já sabe o som que quer (música para jogo, abertura, trilha).
2. Se a música sair sem graça ou repetitiva, **suba o Weirdness de 5 em 5 pontos** (por exemplo, para 45%).
3. Se o Suno ignorar partes do Styles (um instrumento pedido não aparece), **suba o Style Influence de 5 em 5 pontos**.
4. **Mude um controle por vez** e gere 3 versões com o mesmo texto, senão você não sabe o que causou a diferença.
5. Para ideias malucas, vale subir o Weirdness (60% ou mais) ou usar o `v6-wild`, sabendo que ele pode ignorar mais a letra.

> 🇬🇧 **English summary:** keep Weirdness at about 35–40% and Style Influence at about 65–70% when you want the track to follow your plan (structure, real instruments, planned stops). Raise Weirdness a little if the result is bland; raise Style Influence if your description is being ignored. Change one setting at a time and generate at least 3 versions. Both sliders are Pro-plan options.

## 15. BPM: o que é e como usar

**BPM** significa *batidas por minuto*, ou seja, a velocidade da música. Ele muda a sensação da música inteira: energia, dança e até o ritmo em que a voz canta.

### Onde escrever o BPM

- **No Styles**, perto do começo, como número: `128 BPM`. O que vem primeiro pesa mais.
- **Dentro das tags da letra**, para mudar a velocidade no meio da música, por exemplo `[Phase 2, faster, 130 BPM]`.
- Para acelerar ou desacelerar, use **o número e uma palavra** (`faster`, `slower`, `half-time`). Os dois juntos funcionam melhor que só um.

```text
Styles:
dark electronic rock, 100 BPM, G minor, ...

Lyrics:
[Intro, drums only, 100 BPM]
[Phase 1, full band, heavy groove, 100 BPM]
[all music stops, silence]
[Phase 2, faster, double kick, 130 BPM, same key]
```

| Faixa de BPM | Sensação | Exemplos |
| :-: | :--- | :--- |
| **60–80** | Lenta, emotiva | Baladas, trilhas calmas |
| **90–100** | Balanço médio | Sertanejo universitário, boss fight pesado |
| **100–120** | Pop, animada | Pop, funk, rock |
| **124–130** | Pista de dança | House, EDM, synthwave animado, italo disco |
| **140–175** | Muito rápida | Trance, drum and bass, fases finais de chefe |

### 🔍 O que observamos nos testes

- **O Suno aproxima o BPM, não acerta o número exato.** Em um teste pedimos 128 e saiu cerca de 129. Se precisar do valor exato (para mixar ou fazer loop), meça o MP3 depois de gerar.
- **Às vezes ele gera no dobro ou na metade** (100 vira 200 no ouvido). Se a música parecer o dobro, escreva `half-time` ou reduza o número.
- **Mudar o BPM no meio da música não é garantido.** Funciona melhor logo depois de uma parada total (`[all music stops, silence]`). Mudar BPM, tom e instrumento ao mesmo tempo costuma embolar.
- **Para mixar como DJ**, use o mesmo BPM em todas e tons compatíveis. Lá menor e Dó maior usam as mesmas notas (tom relativo), então se misturam bem.

> 🇬🇧 **English summary:** write the BPM in Styles as a number near the start, and inside a tag if you want the speed to change mid-song (add a word like *faster* or *half-time*). Suno only approximates the tempo, so measure the final MP3 if you need an exact value. Tempo changes work best right after a full stop. For DJ mixing, keep the same BPM and a compatible key (A minor and C major share the same notes).

## 16. Instrumentais que soam como instrumentos reais

Esta é a receita usada na **trilha de boss fight** (rock eletrônico escuro, ~100 BPM em Sol menor). Funcionou bem nos testes e a primeira geração já soou como banda de verdade.

### ✅ Regras que fizeram diferença

1. **Nomeie os instrumentos com precisão.** Em vez de `rock`, escreva `real live-recorded drum kit, deep bass guitar, heavy palm-muted distorted electric guitar riffs`. Quanto mais específico, mais real. *(Lição do português: viola virou violino; o certo foi `Brazilian viola caipira (ten-string guitar)`.)*
2. **Diga que é real.** Palavras como `real`, `live-recorded` e `acoustic drum kit` empurram para timbres naturais.
3. **Use o Exclude Styles** para tirar o que soa falso: `MIDI, 8-bit, chiptune, toy sounds`. Tire também o que você não quer ouvir (`orchestra, strings, piano`) e **qualquer voz** (`vocals, singing, humming, choir`).
4. **Siga a ordem de entrada de uma banda de verdade:** bateria → baixo → guitarra → tudo junto. Isso dá o efeito de DJ e deixa cada instrumento ser ouvido.
5. **Use paradas totais** com `[all music stops, silence]` antes dos drops. O silêncio faz o drop seguinte parecer enorme.
6. **Crie um motivo musical** (por exemplo, quatro notas) e peça que ele volte em cada parte: `memorable four-note motif that returns in every section`. Isso faz a música parecer uma só.
7. **Dê um momento ao solo:** uma tag própria (`[Guitar solo, expressive lead guitar, light drums and bass backing]`) com a base mais leve. Solo com banda lotada se perde.
8. **Instrumental só com tags:** a letra tem só `[Instrumental]` no topo e tags curtas, uma por linha, sem frases. O botão *Lyricist* (que sugere letra) não ajuda aqui: não use.
9. **Referência de outra música:** o Suno **não aceita áudio de terceiros** como referência. Descreva o som com suas palavras (tom, BPM, instrumentos, estrutura). Se quiser, analise o MP3 da referência por fora para descobrir BPM, tom e estrutura.

### 🎮 Receita completa: boss fight de 5 minutos

A ideia é fazer a música parecer **várias músicas em uma**, sem ficar carregada: um fio condutor (mesmo tom, mesma bateria, mesmo motivo) e **uma mudança por movimento**, cada um com pelo menos 45 a 60 segundos.

| Movimento | Tempo aprox. | O que muda |
| :--- | :-: | :--- |
| **1. Despertar** | 0:00–0:45 | Atmosfera, build-up, parada total |
| **2. Fase 1** | 0:45–1:45 | Bateria, baixo, guitarra, banda completa |
| **3. Solo** | 1:45–2:30 | Parada total e solo de guitarra com base leve |
| **4. Transformação** | 2:30–3:30 | Mais rápido (ex.: 130 BPM), bateria dupla, sintetizador à frente |
| **5. Final** | 3:30–5:00 | Drop maior, última parada, drop final, cauda sombria |

**Styles:**

```text
instrumental, dark cyberpunk boss battle, electronic rock, 100 BPM, G minor, ominous blood moon atmosphere, real live-recorded drum kit, deep bass guitar, heavy palm-muted distorted electric guitar riffs, expressive lead guitar solo, dark synth pad and low drone, cinematic impacts, risers, memorable four-note motif that returns in every section, DJ-style sudden stops with silent breaks, drums-only sections, layered build, evolving through several movements, intense, epic, no vocals, no singing, no humming, no choir
```

**Exclude Styles:**

```text
vocals, singing, rap, spoken words, humming, choir, lyrics, orchestra, strings, piano, acoustic guitar, saxophone, cheerful, happy, MIDI, 8-bit, chiptune, toy sounds
```

**Lyrics (só tags):**

```text
[Instrumental]
[Intro, dark ambient drone, distant low bell, wind, no drums]
[Build-up, tension rising, riser, heartbeat kick]
[all music stops, silence]
[Drums only, tight heavy groove, 100 BPM, no bass, no guitar]
[Bass enters, deep bass guitar joins the drums]
[Guitar enters, heavy palm-muted riff, G minor, four-note motif]
[Phase 1, full band, heavy groove, dark synth pad, impact hits]
[Break, drums and bass only]
[Build-up, snare roll, riser, filter sweep]
[all music stops, silence]
[Guitar solo, expressive lead guitar, emotional, light drums and bass backing]
[Guitar solo continues, higher and faster, bending notes, same key]
[Build-up, riser, snare roll]
[all music stops, silence]
[Phase 2, faster, double kick, aggressive guitar riff, synth lead, 130 BPM, four-note motif returns]
[Breakdown, ominous drone, sparse, heartbeat kick only]
[Build-up, riser, snare roll, filter sweep]
[all music stops, silence]
[Final Drop, biggest, full band, guitar and synth lead, 130 BPM, four-note motif]
[Outro, dark drone returns, same atmosphere as the intro, no final impact]
```

**Configurações:**

- Modelo `v6`, **Duration: Custom** (ex.: 5:00), **Weirdness ~35%**, **Style Influence ~65–70%**, **Variety Normal**.
- **Max Mode:** vale testar uma vez em músicas longas (mais de 2 minutos), mas gasta mais créditos. Veja o custo antes.
- Gere **pelo menos 3 versões**: o solo de guitarra é a parte mais arriscada.
- Se ficar carregado ou incoerente, tire um movimento (por exemplo, a *Transformação*) ou gere a primeira metade e use **Extend** para a segunda.

### 📼 Receita para outra época: som de anos 80

Para a música parecer de uma época, **nomeie os equipamentos e os sons típicos** em vez de só escrever o ano:

```text
1980s italo disco synthwave, upbeat dance, 128 BPM, A minor, vintage analog synths, warm Juno-style saw pads, DX7-style electric piano bells, LinnDrum-style drum machine, gated reverb snare, brass stabs, expressive saxophone lead in the break, chorus-drenched arpeggio, punchy synth bass, retro 1985 neon feel, warm tape saturation
```

- No **Exclude Styles**, tire o som moderno: `EDM, dubstep, future bass, supersaw, trap, modern, clean digital`.
- Sons de época na intro (fita cassete, TV de tubo, moeda de fliperama) ajudam o ouvinte a perceber a época na hora.

### 🔁 Música para jogo ou loop

- Para loop perfeito, o fim precisa encaixar com o começo. O caminho mais seguro é dividir em **Intro** (toca uma vez) e **Loop Fase 1** e **Loop Fase 2** (repetem), todos no **mesmo BPM e tom**.
- **Corte sempre no começo de um compasso.** A 100 BPM um compasso dura 2,4 s; a 129 BPM, uns 1,86 s. Meça o BPM real do MP3 para calcular o ponto certo.

> 🇬🇧 **English summary:** for realistic instrumentals, name the instruments precisely (*real drum kit, bass guitar, palm-muted electric guitar*), say they are real, exclude MIDI/8-bit/chiptune/toy sounds and any vocals, bring instruments in like a real band (drums, bass, guitar, full band), use full stops before drops, repeat one short motif, give the solo its own tag with a lighter backing, and use only tags in the lyrics box. For a long track, plan about five movements with one change each, and keep key, kit and motif constant. Suno does not accept third-party audio as a reference: describe the sound in your own words.

---

# PARTE 5: Templates, checklist e glossário

## 📋 Templates

### Template A: eletrônica com build-up e drop (inglês)

**Styles:**
```text
female vocals, energetic electro pop, four-on-the-floor kick, synth lead, riser, big euphoric drop, 126 BPM
```
**Lyrics:**
```text
[Verse, soft, no drums]
(4 linhas calmas)
......
[Build-up, riser, snare roll]
(2 linhas curtas, repetidas)
......
[all music stops, voice only]
(1 frase isolada)
......
......
[Drop, heavy bass]
(frases curtas com !)
```

### Template B: balada que vira eletrônica (com legenda de apelidos)

**Styles:**
```text
varied genres, [Voz] sua descrição de voz, [Piano] real acoustic grand piano, slow, melancholic, [Dance] dark electro house, danceable, festival energy
```
**Lyrics:**
```text
[Voz, Piano, slow, no drums]
(versos calmos com ......)
[Voz, Dance, 128 BPM]
(refrão energético)
```

### Template C: música em português, dueto alternado

**Styles:**
```text
Brazilian Portuguese vocals, [gênero], [instrumentos em inglês], male and female singers trading lines, [Male] male lead vocal, natural warm human voice, [Female] female lead vocal, natural warm human voice, [Both] male and female singing together, 95 BPM
```
**Exclude:**
```text
english vocals, autotune, vocoder, robotic voice
```
**Lyrics:**
```text
[Male, ...]
linha 1 (10 a 12 sílabas),

[Female, ...]
linha 2.........

[Both, ...]
frase final, com vogais esticadas e MAIÚSCULAS nos pontos de força
```

## ✅ Checklist final

- [ ] Modo **Advanced**, **Instrumental** desmarcado?
- [ ] Letra em cima e estilo embaixo, sem texto "Exclude" colado no Styles?
- [ ] Voz e idioma no começo do Styles, e Styles com menos de 1000 caracteres?
- [ ] Tags curtas, sozinhas na linha, uma por mudança?
- [ ] Pausas (`......`) nas viradas e antes do drop?
- [ ] Gancho limpo e glitch só em momentos-chave?
- [ ] Em português: letra informal e como se canta, mesma grafia, linhas do mesmo tamanho?
- [ ] Exclude sem nada que você use em algum trecho?
- [ ] Opções avançadas no padrão antes de mexer em Weirdness e Style Influence?
- [ ] Gerou pelo menos 3 vezes, mudando uma coisa por vez?
- [ ] Salvou a melhor versão (Like, playlist, download) antes de editar?
- [ ] Conferiu os termos do plano antes de publicar ou monetizar?

## 📚 Glossário

| Termo | Significado |
| :--- | :--- |
| **Drop** | Momento em que o grave e a energia explodem depois da tensão. |
| **Build-up** | Trecho que aumenta a tensão antes do drop. |
| **Riser** | Som que vai subindo e cria expectativa. |
| **Breakdown** | Trecho calmo no meio, antes de recomeçar a energia. |
| **A cappella** | Só voz, sem instrumentos. |
| **Vocoder** | Efeito que deixa a voz robótica. |
| **Vocal chops** | Pedaços de voz picotados usados como instrumento. |
| **Glitch** | Efeito de travamento digital. |
| **BPM** | Batidas por minuto, a velocidade da música. |
| **Tag** | Texto entre colchetes que guia a estrutura ou o som. |
| **Legenda de apelidos** | Nomes criados no Styles (`[Male]`, `[Hype]`) e chamados nas tags da letra. |
| **Stem** | Faixa separada de uma música (voz, bateria, baixo etc.). |
| **Replace Section** | Recurso que troca só um trecho da música. |
| **Viola caipira** | Violão de dez cordas típico do sertanejo (não é a *viola* de orquestra). |

---

<div align="center">

### 📌 Lembrete final

Valores de planos, limites de download, nomes de menus e recursos mudam.
As músicas usadas como exemplo são **originais**, criadas para este projeto. **Não reproduza letras de outros artistas.**

[🎧 Suno](https://suno.com/@kaiojv) · [📄 PDF](./suno-guide.pdf) · [⚖️ MIT](./LICENSE)

</div>
