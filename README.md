# SASS - Guia Rápido

## Introdução

SASS (_Syntactically Awesome Stylesheets_) é um pré-processador de CSS que adiciona funcionalidades como variáveis, aninhamento, mixins, herança, entre outros. Ele facilita a manutenção de estilos e melhora a organização do código CSS.

## Instalação

### Via npm

Para instalar o SASS usando npm, utilize o seguinte comando:

```sh
npm install -g sass
```

### Compilação Manual

Você pode compilar arquivos SASS para CSS usando o seguinte comando:

```sh
sass input.scss output.css
```

Ou para recompilar automaticamente sempre que houver alteração:

```sh
sass --watch input.scss:output.css
```

## Principais Extensões

Se você trabalha com editores como VS Code, algumas extensões podem ajudar:

- **Live Sass Compiler** (compila SCSS automaticamente para CSS)
- **Sass** (suporte a sintaxe no editor)
- **Prettier** (formatação do código SCSS)

## O que é um Pré-processador?

Um pré-processador CSS é uma ferramenta que expande as funcionalidades do CSS, permitindo um código mais modular e reutilizável. Ele adiciona recursos como:

- **Variáveis**
- **Aninhamento**
- **Mixins**
- **Funções**
- **Herança**

## Diferenças entre CSS, SCSS e SASS

O SASS possui duas sintaxes principais:

### CSS (Convencional)

```css
.button {
  background-color: blue;
  color: white;
}
```

### SCSS (SASS moderno, compatível com CSS)

```scss
$primary-color: blue;

.button {
  background-color: $primary-color;
  color: white;
}
```

### SASS (Sintaxe mais concisa, sem chaves e ponto e vírgula)

```sass
$primary-color: blue

.button
  background-color: $primary-color
  color: white
```

## Conclusão

O SASS melhora a produtividade ao trabalhar com estilos, oferecendo recursos que simplificam a escrita e manutenção do CSS. Seu uso é altamente recomendado para projetos de qualquer tamanho!
