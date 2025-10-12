# Callouts (ou Admonitions)

Os _callouts_ são perfeitos para destacar blocos de texto e dar a eles um contexto visual específico, como uma nota, um alerta, uma dica ou uma informação importante.
## A Sintaxe Básica do Callout

A sintaxe é uma variação do bloco de citação (`>`). Você começa a linha com `>` , seguido por `[!TIPO]`.

A estrutura é:

```
> [!tipo]
> Conteúdo do seu callout aqui.
> Pode ter múltiplas linhas.
```

- `>`: O símbolo de bloco de citação do Markdown.
- `[!tipo]`: O identificador do _callout_. A palavra dentro dos colchetes (`note`, `info`, `warning`, etc.) define o tipo, a cor e o ícone do bloco.    

---
### Tipos de Callouts Mais Comuns

Aqui estão os tipos mais comuns que você pode usar, com exemplos de como eles normalmente aparecem.
#### Nota (Note)
Para informações secundárias ou observações.

```
> [!note]
> Lembre-se de que a prática constante é a chave para a fluência.
```

> [!note] Lembre-se de que a prática constante é a chave para a fluência.

#### Informação (Info)
Para informações gerais e neutras.

```
> [!info]
> O verbo "to be" é o único verbo irregular com três formas no presente simples (am, is, are).
```

> [!info] O verbo "to be" é o único verbo irregular com três formas no presente simples (am, is, are).

#### Dica (Tip / Hint)
Para sugestões e dicas úteis.

```
> [!tip]
> Use contrações como "isn't" e "aren't" para soar mais natural na fala.
```

> [!tip] Use contrações como "isn't" e "aren't" para soar mais natural na fala.

#### Alerta (Warning / Caution)
Para avisos importantes que exigem atenção.

```
> [!warning]
> Não confunda "your" (seu/sua) com "you're" (você é/está). Este é um erro muito comum.
```

> [!warning] Não confunda "your" (seu/sua) com "you're" (você é/está). Este é um erro muito comum.

#### Perigo / Erro (Danger / Error)
Para alertas críticos ou informações sobre erros que devem ser evitados.

```
> [!danger]
> Usar a gramática de forma incorreta em um documento formal pode causar uma má impressão.
```

> [!danger] Usar a gramática de forma incorreta em um documento formal pode causar uma má impressão.

#### Sucesso (Success / Check / Done)
Para indicar a conclusão de uma tarefa ou um ponto positivo.

```
> [!success]
> Você completou o módulo de estudo do Verbo "to be"!
```

> [!success] Você completou o módulo de estudo do Verbo "to be"!

#### Pergunta (Question / Help / FAQ)
Para formatar perguntas ou seções de ajuda.

```
> [!question]
> Qual a diferença entre "Simple Past" e "Present Perfect"?
```

> [!question] Qual a diferença entre "Simple Past" e "Present Perfect"?

## Personalizando os Callouts (Recurso Avançado do Obsidian)

No Obsidian, você pode ir além:
**1. Mudar o Título:** Você pode adicionar seu próprio título logo após o tipo.

```
> [!info] Um Título Personalizado
> O conteúdo aparece aqui, sob o novo título.
```

**2. Torná-los Recolhíveis (Foldable):** Use um `+` para o _callout_ começar aberto e `-` para começar fechado.

```
> [!tip]+ Clique para ver a dica
> Esta é uma dica que começa visível.

> [!warning]- Cuidado: Erro Comum
> Este é um alerta que começa escondido. Você precisa clicar para expandir.
```
## Resumo em Tabela

| Uso Comum              | Tipo (Sintaxe)               |
| ---------------------- | ---------------------------- |
| Nota geral             | `[!note]`                    |
| Informação neutra      | `[!info]`                    |
| Dica ou sugestão       | `[!tip]`                     |
| Sucesso ou conclusão   | `[!success]`                 |
| Pergunta ou ajuda      | `[!question]`                |
| Alerta, requer atenção | `[!warning]` ou `[!caution]` |
| Perigo ou erro crítico | `[!danger]` ou `[!error]`    |
| Citação de texto       | `[!quote]`                   |
| Exemplo de código/uso  | `[!example]`                 |
