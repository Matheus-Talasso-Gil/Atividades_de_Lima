# Atividade de Apropriação

## Exercício 1

Identifique qual método CSS está sendo utilizado:

### Exemplo A

```html
<p style="color: red;">Texto</p>
```

**Resposta:** CSS Inline. O estilo fica no atributo `style` do elemento.

### Exemplo B

```html
<style>
    p {
        color: red;
    }
</style>
```

**Resposta:** CSS Interno. O estilo fica na tag `style` dentro do HTML.

### Exemplo C

O código não foi fornecido no enunciado. Exemplo de CSS externo:

```html
<link rel="stylesheet" href="style.css">
```

**Resposta:** CSS Externo. O estilo fica em um arquivo separado.

## Atividade de Aplicação

### Exercício 2

Criar uma página contendo:

- Título.
- Subtítulo.
- Dois parágrafos.

Aplicar os estilos utilizando:

| Parte | Método | Resolução |
| --- | --- | --- |
| A | CSS Inline | [inline.html](inline.html) |
| B | CSS Interno | [interno.html](interno.html) |
| C | CSS Externo | [externo.html](externo.html) e [style.css](style.css) |

Os exemplos usam fundo cinza claro, texto preto, título principal azul e fonte Arial.

### Reflexão

**Qual solução foi mais fácil de manter?**

O CSS externo, porque basta alterar um arquivo para atualizar o estilo de todas as páginas que o utilizam.

## Desafio Profissional

Uma empresa possui quatro páginas web: Home, Produtos, Serviços e Contato.

Crie `css/style.css` e aplique um padrão visual único para todas as páginas.

### Requisitos

- Mesma fonte.
- Mesmas cores.
- Mesmo estilo para títulos.
- Organização profissional dos arquivos.

### Resolução

As páginas da empresa fictícia Lima Soluções Digitais utilizam o mesmo arquivo [css/style.css](css/style.css):

- [Home](index.html).
- [Produtos](produtos.html).
- [Serviços](servicos.html).
- [Contato](contato.html).

Todas usam fonte Arial, fundo cinza claro, texto preto e título principal azul. Os links no início permitem navegar entre as páginas.

### Como visualizar

Abra `index.html` no navegador para acessar o desafio. Abra `inline.html`, `interno.html` e `externo.html` para conferir os três métodos de CSS.

## Avaliação por Competências

| Capacidade | Critério |
| --- | --- |
| Identificar métodos CSS | Reconhece corretamente cada abordagem |
| Aplicar CSS | Utiliza os três métodos corretamente |
| Organizar arquivos | Cria estrutura adequada de pastas |
| Utilizar CSS Externo | Realiza o vínculo corretamente |
| Manter padrão visual | Reutiliza os estilos adequadamente |

## Instrumentos de Avaliação

- Observação prática.
- Checklist de atividades.
- Correção comentada.
- Autoavaliação.
- Avaliação por pares.

## Feedback Formativo

### Durante a Aula

O docente deverá observar:

- Organização dos arquivos.
- Correção dos caminhos utilizados.
- Aplicação dos estilos.
- Identificação dos erros de sintaxe.

### Após a Atividade

Promover discussão sobre:

- Vantagens da reutilização.
- Impactos da manutenção em projetos reais.
- Padrões utilizados pelo mercado de desenvolvimento web.
