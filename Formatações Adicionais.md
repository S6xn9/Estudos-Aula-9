
# 📘 Anotações de Estudo: Formatações Adicionais em HTML

📅 Criado em: **20 de julho de 2025**  
📚 Matéria:**Programação Web (HTML5 e CSS3)**  
✍️ Autor: **Marco**

## 1. Introdução: Além do Básico

Além dos títulos, parágrafos, negrito e itálico, o HTML oferece várias tags que ajudam a dar mais **significado** ao conteúdo e a exibir informações de formas específicas. Vamos conhecer algumas dessas formatações.

---

## 2. Tags de Formatação Comuns (com Semântica)

### 🔹 `<small>` — Texto Pequeno

- **Propósito:** Letras miúdas, comentários secundários, direitos autorais etc.
- **Semântica:** Conteúdo menos importante hierarquicamente.

```html
<p>Conteúdo principal.</p>
<p><small>Copyright 2025. Todos os direitos reservados.</small></p>
```

---

### 🔹 `<del>` — Texto Deletado

- **Propósito:** Indica remoção de texto.
- **Semântica:** Mostra revisões, histórico de edição.

```html
<p>Preço antigo: <del>R$ 100,00</del> Preço novo: R$ 80,00</p>
```

---

### 🔹 `<ins>` — Texto Inserido

- **Propósito:** Indica adição de conteúdo novo.
- **Semântica:** Complementa o `<del>`.

```html
<p>Preço antigo: <del>R$ 100,00</del> Preço novo: <ins>R$ 80,00</ins></p>
```

---

### 🔹 `<mark>` — Texto Marcado

- **Propósito:** Destacar algo relevante no contexto.
- **Semântica:** Relevância contextual (ex: resultados de busca).

```html
<p>Veja o capítulo <mark>3</mark>.</p>
<p>Sua busca por "banana" encontrou <mark>banana</mark> nanica e <mark>banana</mark> prata.</p>
```

---

### 🔹 `<sub>` — Subscrito

- **Propósito:** Texto abaixo da linha (índices, fórmulas).
- **Semântica:** Matemática, química etc.

```html
<p>A fórmula da água é H<sub>2</sub>O.</p>
```

---

### 🔹 `<sup>` — Sobrescrito

- **Propósito:** Texto acima da linha (expoentes, notas).
- **Semântica:** Notas, ordinais, matemática.

```html
<p>Energia: E = mc<sup>2</sup>.</p>
<p>Este é o 1<sup>o</sup> parágrafo.</p>
```

---

### 🔹 `<abbr>` — Abreviações

- **Propósito:** Define uma sigla ou abreviação.
- **Semântica:** Recomendado usar `title` para acessibilidade.

```html
<p>O <abbr title="HyperText Markup Language">HTML</abbr> é a linguagem base da web.</p>
```

---

### 🔹 `<bdo>` — Substituição Bidirecional

- **Propósito:** Muda a direção de leitura do texto.
- **Semântica:** Útil em idiomas com escrita RTL (ex: árabe).

```html
<p>Texto normal. <bdo dir="rtl">texto invertido</bdo></p>
```

---

### 🔹 `<pre>` — Texto Pré-formatado

- **Propósito:** Mantém espaços, quebras e tabulações.
- **Semântica:** Ideal para código, poesia, formatação rígida.

```html
<pre>
function greet(name) {
    console.log("Hello, " + name + "!");
}
greet("World");
</pre>
```

---

## 3. Pontos Chave para Lembrar

- ✅ **Priorize a semântica:** Escolha a tag que melhor representa o significado do conteúdo.
- ✅ **Acessibilidade:** Tags como `<abbr>`, `<ins>`, `<del>` ajudam tecnologias assistivas.
- ✅ **Código limpo:** Usar a tag certa evita confusão e deixa o HTML mais legível.
- ✅ **CSS é para estilo:** Para efeitos visuais sem significado, use CSS, não HTML semântico.

---

## Conclusão

As "formatações adicionais" do HTML5 vão muito além da aparência. Elas fornecem **significado**, **acessibilidade** e **clareza** — tanto para humanos quanto para máquinas.

