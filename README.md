<h1 align='center'>
  :rocket: Welcome! Markdown Complete Guide 4 README.md
</h1>

<p align='center'>
  :octocat: Start improving your README's with this guide.
</p>

<p align='center'>
  ⭐If you liked this repository, please give it a star
</p>

<!-- |||||||||||||||||||| SPONSORS & STARS |||||||||||||||||||| -->
<p align='center'>
  <a href="https://github.com/sponsors/dev-ggomes"><img alt="Sponsor" src="https://img.shields.io/badge/sponsor-30363D?style=for-the-badge&logo=GitHub-Sponsors&logoColor=#white" /></a>
  &nbsp;
  <a href="#"><img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/dev-ggomes/Markdown-Complete-Guide4-README.md?style=for-the-badge" /></a>
</p>

<br>

## How this repository will be shown?

1. How to do it (with Markdown)
2. Preview

## Menu (not remissive yet)

- [Welcome](#menu)
- [How it will be shown](#how-it-would-be-shown)

- [Guide](#guide)
  - [🧱Fundamentals](#fundamentals)
  - [📐Structure and Layout](#structure-and-layout)
  - [🔍Advanced](#advanced)
  - [🧩Renderers and Compatibility](#renderers-and-compatibility)
  - [⛔Bad habits to avoid](#bad-habits-to-avoid)

- [How to Contribute](#how-to-contribute)

<h2 align='center'>🧱 1. Fundamentals</h2>

## 1.1 Titles (`#`)[🔝](#menu)

```Markdown
# Title 1
## Title 2
### Title 3
#### Title 4
##### Title 5
###### Title 6
```

# Title 1
## Title 2
### Title 3
#### Title 4
##### Title 5
###### Title 6

## 1.2 ✍️ Emphasis[🔝](#menu)

```Markdown
*italic* ou _italic_  
**bold** ou __bold__  
***bold + italic***  
~~erased~~
```

*italic* ou _italic_  
**bold** ou __bold__  
***bold + italic***  
~~erased~~

## 1.3 🗒️ Lists[🔝](#menu)
### Unordered
```Markdown
- Item
* Item
+ Item
```

- Item
* Item
+ Item

### Ordered
```Markdown
1. Item
2. Item 2
   1. Subitem
```

1. Item  
2. Item 2  
   1. Subitem
  
### Checkboxes
```Markdown
- [x] Done
- [ ] To do
```

- [x] Done
- [ ] To do

> [!NOTE]\
> The `x` must be put only in the tasks you've already done

## 1.4 🔗 Links[🔝](#menu)
```Markdown
[Google](https://google.com)
```

[Google](https://google.com)

## 1.5 🖼️ Images[🔝](#menu)
```Markdown
![Alt text](https://via.placeholder.com/100)
```

![Alt text](https://via.placeholder.com/100)

## 1.6 💻 Code[🔝](#menu)

### Inline
```Markdown
Use `npm install`
```

Use `npm install`

### Code block
<pre>
```
block of code here
```
</pre>

How it will be shown:
```
block of code here
```

### With language (Python for example)
<pre>
```Python
def hello():
    print("Hello World!")
```
</pre>

How it will be shown:
```Python
def hello():
    print("Hello World!")
```

### Before and after (changes made)
<pre>
```diff
  - def hello():
  + def hi():
      print("Hello World!")
```
</pre>

How it will be shown:
```diff
- def hello()
+ def hi():
  print("Hello World!")
```

<h2 align='center'>📐 2. Structure and Layout</h2>

## 2.1 📊 Tables[🔝](#menu)
```Markdown
| Name  | Age | Role     |
|-------|------:|-----------|
| Name 1  | 24    | Backend developer |
| Name 2 | 32    | Fullstack developer   |
```

| Name  | Age | Role     |
|-------|------:|-----------|
| Name 1  | 24    | Backend developer |
| Name 2 | 32    | Fullstack developer   |

> [!IMPORTANT]\
> `:---:` -> aligned to the center <br> `---:` -> aligned to the right <br> `:---` -> left aligned

## 2.2 ➖ Horizontal line[🔝](#menu)
> All 3 do the same thing
```Markdown
___
---
***
```

___
---
***

## 2.3 💬 Quotes[🔝](#menu)
```Markdown
> This is a quote.
>> Subquote
```

> This is a quote.
>> Subquote

## 2.4 💬 Different types of Quotes[🔝](#menu)
```Markdown
> [!IMPORTANT]\
> This is a important quote

> [!WARNING]\
> This is a quote that warns the person

> [!NOTE]\
> This is just a quote that expresses a note
```

> [!IMPORTANT]\
> This is a important quote

> [!WARNING]\
> This is a quote that warns the person

> [!NOTE]\
> This is just a quote that expresses a note

<h2 align='center'>🔍 3. Advanced</h2>

## 3.1 ❗ Character Escaping[🔝](#menu)
```Markdown
\*not italic\*
```

\*not italic\*

## 3.2 📁 Collapsible (GitHub only)[🔝](#menu)
```HTML
<details>
  <summary>Show</summary>
  Hidden text
</details>
```

<details>
  <summary>Show</summary>
  Hidden text
</details>

## 3.3 😄 Emojis[🔝](#menu)

```Markdown
:sparkles: :tada: :rocket:
```

✨ 🎉 🚀

> [!NOTE]\
> You can check all the emojis available at the present moment here: [Emoji-Cheat-Sheet repository by ikatyang](https://github.com/ikatyang/emoji-cheat-sheet)

## 3.4 🧭 TOC (Table of Contents)[🔝](#menu)

```Markdown
- [Fundaments](#1-fundaments)
- [Structure](#2-structure-and-layout)
```

- [Fundaments](#1-fundaments)
- [Structure](#2-structure-and-layout)

## 3.5 🕵️ Comments (not visible)[🔝](#menu)
```Markdown
<!-- this is a comment -->
```

## 3.6 ➗ Math formulas[🔝](#menu)

```Markdown
$E = mc^2$
```
<p align='center'>
  $E = mc^2$
</p>

```Markdown
$$
\frac{a}{b} = c
$$
```

$$
\frac{a}{b} = c
$$

<h2 align='center'>🧩 4. Renderers and Compatibility</h2>

<p align='center'>
  
  Plataform | Tables | Emojis | Math | Mermaid | HTML
  :---:|:---:|:---:|:---:|:---:|:---:
  Github | ✅ | ✅ | ❌ | ✅ | ✅
  Obsidian | ✅ | ✅ | ✅ | ✅ | ⚠️
  Typora | ✅ | ✅ | ✅ | ✅ | ✅
  VS Code | ✅ | ✅ | ✅ | ⚠️ | ✅  
  
</p>

<h2 align='center'>❌ 5. Bad habits to avoid</h2>

 - ❌ Titles with `**bold**`
 - ❌ Mix ordered with unordered lists
 - ❌ Using advanced HTML inside a Markdown document
 - ❌ Links without proper text

---

## ✏ How to contribute[🔝](#menu)

<p align='center'>
  
  If you want to contribute to this repository you can `fork it` or open an `issue`!
  > ⚠️**Forks** and **issues** should only be used to improve this repository for the community. Disrespectful forks and issues will be reported. 

</p>
