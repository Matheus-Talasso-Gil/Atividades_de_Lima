# Atividade de Apropriação

## Exercício 1

Analise o código:

```css
.card {
    border: 1px solid #ccc;
}
```

### Respostas

- **Qual seletor está sendo utilizado?** `.card`.
- **Este seletor é de classe ou ID?** Classe, indicada pelo ponto (`.`).

## Atividade de Aplicação

### Exercício 2

Criar uma página contendo:

- Um título principal com `#titulo-principal`.
- Três parágrafos com `.texto`.
- Dois subtítulos com `.titulo-secao`.

### Resolução do exercício 2

O arquivo [index.html](index.html) contém um `h1` com `id="titulo-principal"`,
três parágrafos com `class="texto"` e dois subtítulos com `class="titulo-secao"`.
Os seletores são utilizados no arquivo [style.css](style.css).

## Desafio Profissional

Uma escola deseja criar seu portal institucional com:

- Cabeçalho.
- Banner.
- Cursos.
- Contato.
- Rodapé.

### Requisitos

- Utilizar pelo menos um ID.
- Utilizar no mínimo três classes.
- Padronizar títulos e textos.
- Utilizar CSS externo.

### Resolução do desafio profissional

A mesma página resolve o exercício 2 e o desafio profissional.
Ela apresenta uma escola fictícia com as cinco partes solicitadas.

- **ID:** `titulo-principal`.
- **Classes:** `titulo-secao`, `texto` e `banner`.
- **Estilos:** fonte Arial, títulos azuis, parágrafos pretos e banner cinza
  claro.
- **CSS externo:** `style.css`, vinculado pela tag `link`.

### Como visualizar

Abra `index.html` no navegador.

## Avaliação por Competências

| Capacidade | Critério |
| --- | --- |
| Identificar seletores | Reconhece elemento, classe e ID |
| Aplicar CSS | Utiliza a sintaxe corretamente |
| Organizar código | Mantém nomenclaturas adequadas |
| Reutilizar estilos | Utiliza classes corretamente |
| Estruturar páginas | Relaciona HTML e CSS adequadamente |

## Instrumentos de Avaliação

- Observação prática.
- Checklist de atividades.
- Correção comentada.
- Autoavaliação.
- Avaliação por pares.

## Feedback Formativo

Durante a atividade, o docente deve observar:

- Uso correto de classes.
- Uso correto de IDs.
- Organização do código.
- Aplicação dos estilos.

### Perguntas para reflexão

**Quando devo utilizar uma classe?**

Quando quero reutilizar o mesmo estilo em vários elementos.

**Quando devo utilizar um ID?**

Quando quero identificar um elemento único na página.
O mesmo ID não deve ser repetido.

**Qual abordagem facilita a manutenção do projeto?**

Reutilizar classes e manter os estilos em um arquivo CSS externo.
