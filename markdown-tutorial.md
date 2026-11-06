# Tutorial de Markdown

Fundamentos da Ciência de Dados Agroambientais (FADS) — Exercício 5

Este documento demonstra a sintaxe básica de Markdown, usando como exemplo
dados fictícios de uma pequena exploração agrícola.

## 1. Preparação do ambiente

Comandos usados no terminal (Git Bash) para criar este repositório:

```bash
mkdir fads-ex-05
cd fads-ex-05
git init
touch markdown-tutorial.md
ls -l
code markdown-tutorial.md
```

## 2. Títulos

# Título de primeiro nível

## Título de segundo nível

### Título de terceiro nível

## 3. Ênfase

As quatro palavras seguintes **estão em letra negrita**, mas as restantes não.

As quatro palavras seguintes *estão em letra itálica*, mas as restantes não.

Também é possível combinar ***negrito e itálico*** ao mesmo tempo.

> "O solo é a base de toda a produção agrícola."
>
> — citação ilustrativa

## 4. Listas

Lista ordenada — etapas de uma amostragem de solo:

1. Definir a parcela a amostrar
2. Recolher subamostras em ziguezague
3. Misturar e identificar a amostra composta

Lista não ordenada — culturas da exploração:

- Trigo
- Milho
- Vinha
  - Castas tintas
  - Castas brancas

## 5. Código

Esta frase tem `uma porção de código` no meio do texto.

Bloco de código em Python:

```python
def printMyName(name):
   a = name
   print(a)
```

## 6. Links e imagens

[Markdown Guide](https://www.markdownguide.org/)

![Logo do ISA](./images/LogoISA.png)

**Explicação do caminho da imagem:** o caminho `./images/LogoISA.png` é um
caminho *relativo*. O `.` representa a pasta onde está este ficheiro
(`markdown-tutorial.md`, ou seja, a raiz do repositório); `images/` é a
subpasta dentro dessa pasta; e `LogoISA.png` é o nome do ficheiro da imagem.
Como o caminho é relativo, a imagem continua a aparecer corretamente no GitHub
ou noutro computador, desde que a pasta `images` seja copiada juntamente com o
ficheiro Markdown.

## 7. Tabelas

|ID| Column 1| Column 2| Column 3|
|--|---------|---------|---------|
|1 | item 1  | item 2  | item 3  |
|2 | item 4  | item 5  | item 6  |

Exemplo com dados agroambientais (fictícios):

| Parcela | Cultura | Área (ha) | pH do solo |
|:--------|:-------:|----------:|-----------:|
| P1      | Trigo   | 2.5       | 6.4        |
| P2      | Milho   | 4.0       | 6.9        |
| P3      | Vinha   | 1.8       | 7.2        |

## 8. Outras opções (cheat sheet)

- [x] Títulos
- [x] Negrito e itálico
- [x] Listas, código, links, imagens e tabelas
- [ ] Explorar o resto da [cheat sheet](https://www.markdownguide.org/cheat-sheet/)

Texto ~~riscado~~ e uma linha horizontal:

---

## Resumo

Neste exercício aprendi:

- o que é Markdown e para que serve
- a sintaxe básica de Markdown, incluindo:
  - títulos
  - negrito e itálico
  - listas
  - links
  - imagens
  - tabelas

# Referências

[1] https://daringfireball.net/projects/markdown/syntax
