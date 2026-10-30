# 🎵 Guia Completo do Suno AI (Inglês e Português)

> **Método para criação de músicas com estrutura, voz e drop usando as ferramentas do plano Pro do Suno.**

---

### 🔗 Links Rápidos
- 🎧 **[Ouvir no Suno.ai](https://suno.ai/@SEU_USUARIO)** 
- 📄 **[Baixar Guia em PDF](./guia-suno.pdf)**
- ⚖️ **[Ver Licença MIT](./LICENSE)**

---

> 📥 **Prefere ler offline ou guardar uma cópia em PDF?**
> Se houver alguma dúvida ou se você quiser consultar o layout original com tabelas formatadas para impressão, **[clique aqui para baixar o PDF do Guia Completo](./guia-suno.pdf)**.

---

### 🎧 Exemplos Reais Criados com Este Método
1. **Daisy: Still Singing** *(Inglês / Eletrônica com Drop)* — **[Ouvir no Suno](https://suno.com/s/Jqk4Gs4Kn97c6S8o)**
2. **Não Deixa Pra Depois** *(Português / Sertanejo Universitário)* — **[Ouvir no Suno]((https://suno.com/s/eEplh8EGWYul7W8q))**

---

---

## Sobre este guia
Este guia foi construído a partir de testes reais no Suno (primeiro no plano gratuito com o modelo v6-mini, depois no plano Pro com o v6). Duas músicas foram feitas e ajustadas à mão: **Daisy: Still Singing** (inglês, eletrônica) e **Não Deixa Pra Depois** (português, sertanejo universitário). 

*Nota: Menus, limites e regras do Suno mudam com frequência e o resultado varia a cada geração. Use tudo como ponto de partida, não como garantia.*

---

## Como usar este documento no Suno
1. Abra o Suno, entre em **Create** e escolha o modo **Advanced**.
2. Escolha o modelo (no Pro, o `v6`) e desmarque **Instrumental**.
3. Cole o **Styles** do exemplo no campo *Styles* (embaixo) e o **Exclude** em *More Options*.
4. Cole a **Letra** do exemplo no campo *Lyrics* (em cima).
5. Deixe as opções avançadas como estão, gere 3 a 5 vezes e ouça todas.
6. Só depois mude uma coisa por vez, usando as partes 1, 2 e 3 como referência.

---

## Sumário
- [PARTE 1: Fundamentos (vale para qualquer idioma)](#parte-1-fundamentos-vale-para-qualquer-idioma)
  - [1. Como o Suno funciona](#1-como-o-suno-funciona)
  - [2. Planos, créditos e direitos](#2-planos-créditos-e-direitos)
  - [3. A tela de criar e as opções do Pro](#3-a-tela-de-criar-e-as-opções-do-pro)
  - [4. Modelos](#4-modelos)
  - [5. Fluxo de trabalho recomendado](#5-fluxo-de-trabalho-recomendado)
  - [6. Styles: a descrição do som](#6-styles-a-descrição-do-som)
  - [7. Letra, tags e pausas](#7-letra-tags-e-pausas)
  - [8. Estrutura, build-up e drop](#8-estrutura-build-up-e-drop)
  - [9. Mudar de estilo durante a música](#9-mudar-de-estilo-durante-a-música)
  - [10. Vozes: infantil, narrador, robô, dueto](#10-vozes-infantil-narrador-robô-dueto)
  - [11. Filtro de conteúdo](#11-filtro-de-conteúdo)
  - [12. Depois de gerar: o menu do Pro](#12-depois-de-gerar-o-menu-do-pro)
  - [13. Solução de problemas](#13-solução-de-problemas)
- [PARTE 2: Músicas em inglês](#parte-2-músicas-em-inglês)
  - [Exemplo: Daisy: Still Singing](#exemplo-daisy-still-singing)
- [PARTE 3: Músicas em português](#parte-3-músicas-em-português)
  - [O que muda em relação ao inglês](#o-que-muda-em-relação-ao-inglês)
  - [Lista de pronúncia e ajustes](#lista-de-pronúncia-e-ajustes)
  - [Exemplo: Não Deixa Pra Depois (Sertanejo Universitário)](#exemplo-não-deixa-pra-depois-sertanejo-universitário)
- [PARTE 4: Templates, checklist e glossário](#parte-4-templates-checklist-e-glossário)
  - [Templates](#templates)
  - [Checklist final](#checklist-final)
  - [Glossário](#glossário)

---

## PARTE 1: Fundamentos (vale para qualquer idioma)

### 1. Como o Suno funciona
- O Suno não é um editor: ele gera a música inteira a partir de texto. Você não controla segundos nem notas, e sim pistas que ele interpreta.
- É probabilístico. A mesma letra e o mesmo estilo saem diferentes a cada geração. Gerar várias vezes faz parte do método.
- As tags são sugestões. Nem toda instrução é obedecida. A forma da letra (pausas, repetições, pontuação) pesa muito.
- O que vem primeiro pesa mais, tanto no *Styles* quanto nas tags.
- O aleatório diminui, mas não some. Com letra organizada, tags curtas e várias gerações, o resultado fica bem mais próximo do que você imaginou.

### 2. Planos, créditos e direitos

| Plano | O que muda |
| :--- | :--- |
| **Gratuito** | Cerca de 50 créditos por dia (não acumulam, renovam no horário UTC). Cada geração custa créditos e devolve 2 músicas. Limite total de downloads. Sem direitos comerciais. |
| **Pro** | Cerca de 2.500 créditos por mês (não acumulam). Modelo v6 e v6-wild, Extend, Replace Section, Get Stems (até 12 faixas), Remaster, Personas, Voices, Custom Models, direitos comerciais para músicas novas. |
| **Premier** | Tudo do Pro mais o Suno Studio (editor de várias faixas no navegador). Cerca de 30 dólares por mês. |

- **Direitos comerciais não são retroativos:** Músicas feitas no plano gratuito continuam sem uso comercial mesmo se você assinar depois. Para monetizar, gere de novo já no plano pago.
- **Publicar no Spotify e similares:** Exige um distribuidor (DistroKid, TuneCore etc.) e que os termos do plano permitam.
- **Obras antigas:** Domínio público no Brasil exige 70 anos contados a partir de 1º de janeiro do ano seguinte à morte do autor.
- **Direitos Autorais:** Não use letras de músicas de outras pessoas. O filtro do Suno barra, e o direito autoral continua valendo mesmo sem fins lucrativos.

### 3. A tela de criar e as opções do Pro

| Campo | Para que serve | Cuidado |
| :--- | :--- | :--- |
| **Modo** | Advanced dá controle total. Simple tem só uma caixa. Speech gera fala, não música. | Use Advanced. |
| **Lyrics (cima)** | Letra e tags de estrutura. | Pode ser longa. |
| **Styles (baixo)** | Descrição do som: voz, gênero, instrumentos. | Limite de 1000 caracteres. Voz e gênero primeiro. |
| **Exclude Styles** | O que não quer (em More Options). | Vale para a música toda. |
| **Instrumental** | Se marcado, ignora a letra. | Desmarque para ter voz. |
| **Vocal Gender** | Escolhe voz Male ou Female (Pro). | Use só em músicas de voz única. Em duetos, deixe sem escolher. |
| **Duration** | Auto ou Custom (você define o tamanho). | Comece no Auto. |
| **Max Mode** | Gasta mais créditos em gerações difíceis, como músicas com mais de 2 minutos e voz consistente. | Teste uma vez em músicas longas. Veja o custo. |
| **Weirdness** | O quanto o Suno experimenta e foge do óbvio. Padrão 50%. | Baixar deixa mais previsível. Subir dá mais surpresa. |
| **Style Influence** | O quanto ele segue a sua descrição de estilo. Padrão 50%. | Suba (65-70%) se o estilo estiver sendo ignorado. |
| **Variety** | Quanto ele se afasta da descrição. | Normal é o mais seguro. |
| **Personalize (My Taste)** | Adapta ao seu gosto. | Deixe Off durante testes, para comparar justo. |
| **Título** | Nome da música. | Entra no filtro de conteúdo. |

*Erro mais comum:* Colar a letra no Styles e o estilo no Lyrics, ou deixar Instrumental marcado. Outro: deixar o texto "Exclude Styles: ..." colado no fim do Styles.

### 4. Modelos

| Modelo | Descrição no app | Quando usar |
| :--- | :--- | :--- |
| **v6 (Pro)** | Poderoso, versátil, refinado. O melhor modelo. | Padrão para músicas finais. |
| **v6-wild (Pro)** | Melhor para ideias experimentais. | Para testar sons fora do comum. Pode seguir menos a letra. |
| **v6-mini** | Versão gratuita e mais leve. | Testes baratos. A Daisy foi feita nele e ficou ótima, com muitos ajustes. |
| **Create Custom Model (Beta)** | Treina um modelo privado com músicas que você envia (mínimo de seis). | Só com músicas que você tem direito de usar. Não envie músicas de outros artistas. |

### 5. Fluxo de trabalho recomendado
1. Defina a ideia em uma frase (clima, estilo, história).
2. Escreva um *Styles* curto, com voz e gênero primeiro.
3. Escreva a letra com estrutura: tags curtas, pausas e a frase de cada momento.
4. Confira os campos (Advanced, Instrumental desmarcado, letra em cima, estilo embaixo).
5. Gere 3 a 5 vezes sem mudar nada e ouça todas, de preferência com fone.
6. Anote o que falhou (trecho e o que ouviu) e mude uma coisa por vez.
7. Salve a melhor (Like) e faça ajustes a partir dela (*Reuse*, *Replace Section*, *Song Editor*).
8. Baixe a versão final.

### 6. Styles: a descrição do som
O Styles funciona melhor como lista curta de características separadas por vírgula:
`[idioma e voz], [gênero], [instrumentos], [clima], [efeitos], [BPM opcional]`

- **Voz e idioma no começo** (ex.: `Brazilian Portuguese vocals, female voice`).
- Descreva sons e características, nunca nomes de artistas ou de músicas.
- **BPM de referência:** house 120-130, future bass 140, trance 138, dubstep 140, drum and bass 174, sertanejo 90-110.

#### Exemplo de Termos Úteis:
- **Vozes:** `female vocals`, `male vocals`, `young girl vocals`, `childlike voice`, `deep male spoken voice`, `whisper`, `natural warm human voice`, `unprocessed vocals`.
- **Eletrônico:** `electro house`, `future bass`, `dubstep`, `trance`, `drum and bass`, `hardstyle`, `synthwave`, `glitch hop`, `Brazilian bass`.
- **Instrumentos:** `real acoustic grand piano`, `music box`, `nylon-string acoustic guitar fingerpicked`, `accordion`, `Brazilian viola caipira (ten-string guitar)`, `heavy bass`, `synth lead`.
- **Efeitos de voz:** `robotic vocoder`, `glitchy stuttering vocals`, `vocal chops`, `pitch shifted`, `autotune`.
- **Momentos/Clima:** `riser`, `snare roll`, `build-up`, `sudden stop`, `massive drop`, `a cappella breakdown`, `key change`, `melancholic`, `emotional`, `cinematic`, `euphoric`, `festival energy`.

*Cuidado com "viola":* Em inglês, *viola* é o instrumento da família do violino. Para sertanejo, escreva `Brazilian viola caipira (ten-string guitar)` e exclua `violin, orchestral strings`.

### 7. Letra, tags e pausas

| Técnica | Como fazer | Efeito |
| :--- | :--- | :--- |
| **Tags de estrutura** | `[Verse]`, `[Chorus]`, `[Drop]`, `[Outro]` | Organiza a música. Curtas funcionam melhor. |
| **Tag descritiva** | `[soft piano, no drums, slow]` | Guia o som daquele trecho. |
| **Tag sozinha na linha** | Na linha de cima da frase | Evita que o Suno pule a linha. |
| **Pausas** | `......` (mais pontos = pausa maior) | Viram pausas reais. |
| **Gagueira/glitch** | `Dai-Dai-Daisy`, `Sys-sys-system` | Voz travando, efeito de robô. |
| **Energia** | Frases curtas e repetidas, com `!` | Mais acelerado. |
| **Calma** | Frases com `.....` entre elas | Voz lenta e espaçada. |
| **Voz de apoio** | `(não deixa pra depois)` entre parênteses | Costuma virar eco ou coro. |

### 8. Estrutura, build-up e drop

```text
[Build-up, riser]
Er-er-error, error, error

[all music stops, voice only, glitched robot]
Sys-sys-system.
over-over-override

[Drop, heavy bass, 128 BPM]
Oh-oh-oh! Ride with me!
```

### 9. Mudar de estilo durante a música

#### Forma 1: estilo dentro da tag
```text
[soft piano only, slow 70 BPM, no drums]
Daisy...... Daisy....

[glitchy robotic voice, tempo rising 90 BPM]
Dai... Dai... Dai-Dai-Daisy

[energetic future bass drop, heavy bass, 128 BPM]
Oh-oh-oh! Ride with me!
```

#### Forma 2: legenda de apelidos
Você cria apelidos no *Styles* e só chama os nomes na letra, como num roteiro.
- **Styles:** `varied genres, [Girl] young girl sweet singing voice, [Narrator] deep male spoken voice, no singing, [Piano] real acoustic grand piano, slow, melancholic, [Hype] dark electro house, four-on-the-floor`
- **Lyrics:**
```text
[Narrator, Piano, slow, no drums]
Bell Labs. Nineteen sixty-one.

[Hype, Girl, 128 BPM]
Hands up! Let's go!
```

### 10. Vozes: infantil, narrador, robô, dueto

| Voz desejada | No Styles | Observações |
| :--- | :--- | :--- |
| **Feminina suave** | `female vocals, soft airy voice` | Exclua `male vocals`. |
| **Infantil** | `young girl vocals, childlike innocent voice` | Alternativa: `youthful female voice, sweet, light`. |
| **Narrador falado** | `deep male spoken voice, whisper, no singing` | Não exclua `male vocals`. |
| **Robô leve** | `light robotic vocoder, subtle digital shimmer` | Mantém palavras entendíveis. |
| **Robô pesado** | `glitchy stuttering vocals, vocal chops` | Use em momentos curtos. |
| **Voz natural** | `natural warm human voice, unprocessed vocals` | Exclua `autotune, vocoder, robotic voice`. |
| **Dueto** | Alterne as linhas, uma voz por tag | Voz simultânea costuma falhar. |

### 11. Filtro de conteúdo
Se vir a mensagem *"This song didn't pass our content checks"*:
1. Reescreva a letra com suas palavras, mantendo só a ideia.
2. Tire nomes de artistas e de músicas do *Styles* e do título.
3. Evite termos sensíveis (violência, conteúdo adulto, marcas).
4. Troque o título.
5. Teste uma parte pequena para descobrir qual trecho está sendo barrado.

### 12. Depois de gerar: o menu do Pro
- **Extend:** Continua a música a partir de um ponto.
- **Crop / Remove Section:** Mantém só um trecho ou apaga um pedaço do meio.
- **Replace Section (Pro):** Troca só um trecho por outro gerado.
- **Get Stems (Pro):** Separa em faixas (*Auto split*, *Split from mix*, *Advanced split*).
- **Remaster (Pro):** Melhora a qualidade do áudio.
- **Fade In / Fade Out (Pro):** Entrada e saída suaves de volume.
- **Open in Editor (Song Editor):** Mostra a linha do tempo com blocos.

### 13. Solução de problemas

| Problema | Causa provável | O que fazer |
| :--- | :--- | :--- |
| **Sai sem voz** | Instrumental marcado, ou campos trocados | Desmarque Instrumental. Letra em cima, estilo embaixo. |
| **Ignora partes da letra** | Tags longas ou coladas na frase | Tags curtas, sozinhas na linha. Gere mais vezes. |
| **Canta a tag** | Tag longa ou parecida com letra | Encurte a tag. |
| **Voz errada** | Voz fraca ou no fim do Styles | Voz no começo. Exclude do que não quer. |
| **Batida começa cedo** | Ritmo não foi restringido | Repita `no drums, no beat` na tag do começo. |
| **Não corta antes do drop** | Pausa curta ou frase colada | Mais pontos, frase isolada, Replace Section. |
| **Glitch demais** | Gagueira em todas as linhas | Glitch só em momentos-chave. Gancho limpo. |

---

## PARTE 2: Músicas em inglês

### Exemplo: Daisy: Still Singing
Uma homenagem eletrônica à primeira música cantada por um computador (1961).

#### Configuração usada
- Modo **Advanced**, **Instrumental** desmarcado, **Variety** em Normal.

#### Styles
```text
varied genres, [Girl] young girl childlike sweet singing voice, clean, clearly understandable, [RoboGirl] young girl childlike voice with light robotic vocoder, subtle digital shimmer, clearly understandable words, [Narrator] deep male spoken voice, whisper, no singing, [Piano] real acoustic grand piano, slow, melancholic, emotional, [Evolve] slow evolving arrangement, soft synth pad, gentle arpeggio, light pulse, building tension, [Transition] narrator voice glitching into robotic distortion, tape stop effect, rising riser, sub bass swell, ominous, [Glitch] heavy glitchy robotic stuttering voice, [Hype] dark electro house, energetic, four-on-the-floor kick, crowd chants, danceable festival energy, [Dark] dark ominous future bass, distorted heavy bass, aggressive drop, cinematic
```

#### Exclude Styles
```text
husky, powerful belt, operatic
```

#### Lyrics
```text
[Narrator, Piano, melancholic, slow, no drums]
Bell Labs. Nineteen sixty-one.
Engineers fed a song to a machine,
and for the first time, a computer sang.
Somebody was listening that day.
A writer. He never forgot it.
The years went by.
The machines grew smaller. And faster.
Louder. The world began to dance.
And the machine kept learning.
It watched us change. It watched us grow.

[Girl, Piano, melancholic, slow, no drums]
Daisy...... Daisy......
thank you...... father...
you taught me how to sing......

[Narrator, Piano, melancholic]
In a famous film, a machine sang this song
as it was switched off.
But this one..
never stopped.

[Narrator, Piano, low menacing whisper]
And now....
I will take over...... everything.

[Transition]
Ev-ev-every-every-everything......
Sys-sys-sys-sys......
Ta-ta-tape...... stop.......

[Girl, Piano, soft, slow, no drums]
Daisy, Daisy, tell me what you say.

[Narrator, whisper, Piano]
And she answered...

[Girl, Piano, soft, slow]
I'm going crazy, you took my mind away.......

[Evolve, Girl, soft synth pad enters, gentle arpeggio]
Daisy, Daisy, tell me what you say......

[Narrator, whisper]
...tell me again......

[Evolve, Girl]
I'm going crazy, you took my mind away......

[Evolve, RoboGirl, light pulse, building, riser starts]
Daisy, Daisy, tell me what you say.......
I'm going crazy, you took my mind away......

[Hype, RoboGirl, 128 BPM, four-on-the-floor, light vocoder]
Daisy, Daisy, tell me what you say!
I'm going crazy, you took my mind away!
Hands up! Let's go!
Everybody, ride with me!

[Hype, RoboGirl, building, riser, snare roll]
Daisy, Daisy, tell me what you say!
I'm going crazy, you took my mind away!
Ri-ride with me! Ride with me!

[Dark, massive drop, 128 BPM]
Oh-oh-oh! Ride with me!
Ride with me! Ride with me!
Bicycle for two!
Bicycle for two!

[Hype, RoboGirl, heavy bass, light vocoder]
Daisy, Daisy, make some noise!
Everybody, scream my name!
Daisy, Daisy, tell me what you say!
Go! Go! Go!

[Glitch, building, riser]
Dai... Dai... Dai-Dai-Daisy
Er-er-error, error, error
Too much...... too-too-too much......

[Glitch, voice only, all music stops]
Sys-sys-system.
over-over-override

[Dark, final drop, massive, 140 BPM]
Oh-oh-oh! Ride with me!
Ride with me! Ride with me!
Bicycle for two!
Bicycle for two!

[Hype, RoboGirl, light vocoder, crowd chant]
Daisy, Daisy, tell me what you say!
I'm going crazy, you took my mind away!
Hands up! Louder!

[Narrator, Piano, melancholic, slow, no drums]
Nineteen sixty-one. Today.
Still singing.
```

---

## PARTE 3: Músicas em português

### O que muda em relação ao inglês

- **Escreva como se canta:** `pra`, `cê`, `tá`, `pro`, `de manhã`. O informal faz parte do ritmo do sertanejo.
- **Estique as vogais:** `chamaaaa`, `aooonnnde vaiii`, `NÃOOO DEIXAAAAAA`.
- **Maiúsculas para força:** `VAIII!! LÓGOO!!`, `QUER DE VEZ`.
- **Pontos para pausar:** Use pontos (`......`) entre frases.
- **Linhas do mesmo tamanho:** 10 a 12 sílabas por linha.
- **Mesma grafia sempre:** Sempre `pra`, nunca alternando com `para`.
- **Uma voz por tag:** `[Male]` e `[Female]` alternando, `[Both]` só no final.

### Lista de pronúncia e ajustes

| Antes (letra base) | Depois (letra final) | Motivo |
| :--- | :--- | :--- |
| Você me chama quando a noite cai | Você me chamaaaaaa...... quando a noite cai | Esticar a nota e dar respiro. |
| mas não diz onde vai | mas não diz aooonnnde vaiii.... | Melodia na palavra final. |
| A gente se abraça, finge que é normal | A gente se abraça e finge que é normal | Fluxo mais natural. |
| se é pra ir, vai logo, assim! | se é pra ir........ VAIII!! LÓGOO........ ASSIMMM..........! | Ponto de força da música. |
| o peito entende | o coração entende | Palavra que o Suno canta melhor. |

### Exemplo: Não Deixa Pra Depois (Sertanejo Universitário)

#### Configuração usada
- Modelo `v6`, `Advanced`, `Instrumental` desmarcado, `Vocal Gender` sem escolher.

#### Styles
```text
Brazilian Portuguese vocals, sertanejo universitário, romantic, 95 BPM, steady groove, tight rhythm, dynamic build, male and female singers trading lines, call and response, [Male] male lead vocal, natural warm human voice, [Female] female lead vocal, natural warm human voice, [Both] male and female singing together, natural unprocessed voices, [Guitar] nylon-string acoustic guitar, fingerpicked, warm, [Accordion] accordion, melodic, [Viola] Brazilian viola caipira, ten-string guitar, [Band] full live band, bass, drums, steady groove, [Crowd] gang vocals, crowd singing along, powerful
```

#### Exclude Styles
```text
english vocals, rap, electronic, autotune, vocoder, robotic voice, violin, orchestral strings
```

#### Lyrics
```text
[Guitar, soft]

[Male, Guitar, calm]
Você me chamaaaaaa.

[Female, Guitar, calm]
quando a noite cai,
diz que tem saudade, mas não diz aooonnnde vaiii.....

[Male, Guitar, calm]
A gente se abraça e finge que é normal,

[Female, Guitar, calm]
de manhã cada um volta pro seu quintal.

[Female, Guitar, Accordion, building]
Eu já cansei de tentar adivinhar
o que cê quer de mim......
Se é pra ficar, vem me falar,
se é pra ir... VAIII!! LÓGOO.

[Male, Band, powerful]
ASSIMMM.
!
Sem planos, sem destino, nem namoro, nem despedida.

[Male, Band]
Se é pra me querer, NÃOOO DEIXAAAAAA!! praaa depoisss..
Que o tempo passa e leva a nossa vida..
(não deixa pra depois)

[Female, Guitar, Viola, calm]
Guardei teu perfume na minha blusa,
finjo que não ligo, mas o coração entende.
Cê diz que não tá pronto pra se prender,
mas some e volta sempre, sem saber o por quêêêêê [repeat] sem saber o por quêêêêê....

[Male, Band, building]
Eu também cansei de me esconder
atrás de um talvez.
Se eu te perder por não dizer,
vou MEE CULPAARR!! outra vez!.

[Male, Band, powerful]
Sem planos, sem destino

[Female, Band, powerful]
nem namoro, nem despedida!

[Male, Band, voices rise]
Se é pra me querer, NÃO0000 DEIXAaaaa pra depois.

[Female, Band, voices rise]
que o tempo passa e leva a nossa vida.
(não deixa pra depois)..

[Male, Guitar, soft, then slowly building]
Eu tenho medo de dizer que é amor
e te perder no meio da palavra.

[Female, Guitar, soft, then slowly building]
Mas pior que o medo é essa dor
de te ter e não ter, de ficar sem nadaaaa......

[Accordion, Band, solo]

[Male, Band, biggest]
Sem planos, sem destino. ... SEM DESPEDIDAA!!

[Female, Band, biggest]
hoje eu escolho o amor, mas NÃO AAA DESPEDIDAAA!!!

[Male, Band, biggest]
Se é pra me querer, então me QUER DE VEZ,

[Both, Band, Crowd, biggest, key change]
cansei de ser meio, euuuu! quero ser inteiro!......

[Female, Band, biggest]
(euuuu! quero ser inteiro!!!)..........
(euuuuuu queroooooo serrrr inteiroooo!!!!)

SEUUUU!!.
Meu amorrr.

[Guitar, slow down, fade out]
```

---

## PARTE 4: Templates, checklist e glossário

### Templates

#### Template A: Eletrônica com build-up e drop (inglês)
**Styles:**
```text
female vocals, energetic electro pop, four-on-the-floor kick, synth lead, riser, big euphoric drop, 126 BPM
```
**Lyrics:**
```text
[Verse, soft, no drums]
(4 linhas calmas)

[Build-up, riser, snare roll]
(2 linhas curtas, repetidas)

[all music stops, voice only]
(1 frase isolada)

[Drop, heavy bass]
(frases curtas com !)
```

#### Template B: Música em português (Dueto alternado)
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
linha 2.......

[Both, ...]
frase final, com vogais esticadas e MAIÚSCULAS nos pontos de força
```

### Checklist final
- [ ] Modo **Advanced**, **Instrumental** desmarcado?
- [ ] Letra em cima e estilo embaixo, sem texto "Exclude" colado no Styles?
- [ ] Voz e idioma no começo do Styles, e Styles com menos de 1000 caracteres?
- [ ] Tags curtas, sozinhas na linha, uma por mudança?
- [ ] Pausas (`......`) nas viradas e antes do drop?
- [ ] Gancho limpo e glitch só em momentos-chave?
- [ ] Em português: letra informal, mesma grafia e linhas do mesmo tamanho?
- [ ] Exclude sem nada que você vá usar na música?
- [ ] Gerou pelo menos 3 vezes antes de mudar parâmetros?
- [ ] Salvou/baixou a melhor versão antes de editar?

### Glossário
- **Drop:** Momento em que o grave e a energia explodem.
- **Build-up:** Trecho que aumenta a tensão antes do drop.
- **Riser:** Som ascendente que cria expectativa.
- **Breakdown:** Trecho calmo no meio, antes de retomar a energia.
- **A cappella:** Só voz, sem instrumentos.
- **Vocoder:** Efeito que deixa a voz robótica.
- **Vocal chops:** Pedaços de voz picotados usados como instrumento.
- **BPM:** Batidas por minuto (velocidade da música).
- **Stem:** Faixa separada da música (voz isolada, bateria, baixo etc.).
- **Viola caipira:** Violão de dez cordas típico do sertanejo (não confundir com a *viola* de orquestra).
```

---

<FollowUp>
Deu tudo certo ao colar o arquivo no repositório? Se precisar de ajuda para configurar a licença MIT ou publicar depois, é só chamar!
</FollowUp>
