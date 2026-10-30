# Guia Completo do Suno
Como criar músicas com estrutura, voz e drop: método para inglês e para português, com duas músicas reais como exemplo[cite: 5].

> **Sobre este guia:** Construído a partir de testes reais no Suno (primeiro no plano gratuito com o modelo v6-mini, depois no plano Pro com o v6). Duas músicas foram feitas e ajustadas à mão: *Daisy: Still Singing* (inglês, eletrônica) e *Não Deixa Pra Depois* (português, sertanejo universitário)[cite: 5].

---

## Sumário
- [Parte 1: Fundamentos](#parte-1-fundamentos)
- [Parte 2: Músicas em Inglês (Daisy: Still Singing)](#parte-2-músicas-em-inglês)
- [Parte 3: Músicas em Português (Não Deixa Pra Depois)](#parte-3-músicas-em-português)
- [Parte 4: Templates, Checklist e Glossário](#parte-4-templates-checklist-e-glossário)

---

## Parte 1: Fundamentos

### 1. Como o Suno Funciona
- O Suno não é um editor tradicional: gera a música inteira a partir de texto[cite: 6].
- É probabilístico: a mesma letra e estilo geram resultados diferentes a cada tentativa[cite: 6].
- O que é colocado primeiro no texto tem mais peso[cite: 6].

### 2. Planos, Créditos e Direitos
- **Gratuito:** ~50 créditos/dia (não acumulam), sem direitos comerciais[cite: 6].
- **Pro:** ~2.500 créditos/mês, acesso aos modelos v6/v6-wild, Extend, Get Stems, Remaster, e direitos comerciais para novas músicas[cite: 6].
- **Premier:** Inclui o Suno Studio (editor multi-pistas)[cite: 6].

### 3. A Tela de Criar e Opções do Pro
- **Modo:** Utilize sempre o *Advanced*[cite: 7].
- **Styles:** Descrição do som (limite de 1000 caracteres). Coloque voz e gênero primeiro[cite: 7].
- **Exclude Styles:** O que pretende evitar na música inteira[cite: 7].

### 4. Modelos
- **v6 (Pro):** Poderoso, versátil e o melhor para versões finais[cite: 7].
- **v6-wild:** Ideal para testes experimentais[cite: 7].
- **v6-mini:** Versão gratuita mais leve, excelente para testes económicos[cite: 7].

### 5. Fluxo de Trabalho Recomendado
1. Definir a ideia principal numa frase[cite: 8].
2. Escrever um *Styles* curto, com voz e género no início[cite: 8].
3. Escrever a letra com tags de estrutura e pausas[cite: 8].
4. Conferir os campos e gerar 3 a 5 vezes sem alterar parâmetros[cite: 8].

### 6. Styles: A Descrição do Som
Formato recomendado: `[idioma e voz], [gênero], [instrumentos], [clima], [BPM opcional]`[cite: 8].
> **Atenção:** Para instrumentos tradicionais como a viola no sertanejo, utilize `Brazilian viola caipira (ten-string guitar)` e exclua `violin` para evitar confusão com cordas clássicas de orquestra[cite: 8].

### 7. Letra, Tags e Pausas
- Utilize tags curtas e isoladas por linha (`[Verse]`, `[Chorus]`, `[Drop]`)[cite: 9].
- Utilize pontos (`......`) para criar pausas dramáticas e naturais no ritmo da voz[cite: 9].

### 8. Estrutura, Build-up e Drop
- Controlo de tensão através de tags como `[Build-up, riser]`, cortes secos com `[all music stops, voice only]` e a explosão de energia no `[Drop, heavy bass]`[cite: 9, 10].

### 9. Mudar de Estilo Durante a Música
- Utilize legendas de apelidos no *Styles* (ex: `[Girl]`, `[Narrator]`) e invoque-as diretamente na letra como um guiões de teatro[cite: 10].

### 10. Vozes
- Definições específicas no *Styles* para vozes femininas suaves, infantis, narradores falados, efeitos robóticos subtis e duetos alternados[cite: 11].

### 11. Filtro de Conteúdo
- Se uma letra for barrada por direitos ou termos sensíveis, reescreva-a com palavras próprias, remova nomes de artistas do *Styles* e altere o título[cite: 11].

### 12. Depois de Gerar (Menu Pro)
- Acesso a ferramentas avançadas como *Extend*, *Replace Section*, *Get Stems* (separação de pistas), *Remaster* e *Open in Editor*[cite: 11, 12].

### 13. Solução de Problemas
- Guia rápido de diagnóstico para corrigir problemas comuns (voz ausente, tags ignoradas, batida prematura ou excesso de *glitch*)[cite: 12].

---

## Parte 2: Músicas em Inglês
### Exemplo: Daisy: Still Singing
Uma homenagem eletrónica à primeira música sintetizada por um computador em 1961.

- **Styles utilizado:**
  ```text
  varied genres, [Girl] young girl childlike sweet singing voice, clean, clearly understandable, [Narrator] deep male spoken voice, whisper, no singing, [Piano] real acoustic grand piano, slow, melancholic, emotional, [Hype] dark electro house, energetic, four-on-the-floor kick, crowd chants[cite: 13]
