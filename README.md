[README.md](https://github.com/user-attachments/files/33174700/README.md)[Uploading REA# Ficha de Herói — Warui

Projeto Prático — Parte 1  
Tecnologias: HTML5 + CSS3
## 1. Conceito

Este projeto transforma a história do personagem Warui em uma ficha de herói com estética de RPG/shinobi.

Warui é um jovem shinobi órfão e prodígio que cresceu em um orfanato. Ao longo da história, ele se envolve em um conflito que ameaça o País do Fogo e passa a investigar a estrutura de corrupção que sustenta a guerra.

A ficha apresenta quatro áreas principais exigidas pelo projeto:

- Sobre o Herói
- Atributos & Habilidades
- Inventário & Conquistas
- Contato com a Guilda

## 2. Estrutura

```text
ficha-heroi-parte1/
├── index.html
├── style.css
├── README.md
└── imagens/
    └── warui-avatar.svg
```

## 3. Decisões de UI/UX

### Hierarquia visual
O nome "Warui" recebe o maior destaque tipográfico da página. Depois, o fluxo leva o usuário para a biografia, atributos, habilidades, inventário e contato.

### Contraste e legibilidade
Foi utilizado fundo escuro com textos claros e cores de destaque em azul/ciano e dourado. A intenção é manter a leitura confortável e separar informações importantes do conteúdo secundário.

### Consistência
Cards, bordas, espaçamentos, barras de atributos e etiquetas usam padrões repetidos. Isso faz com que o usuário reconheça rapidamente quais elementos pertencem à mesma categoria.

### Affordance e feedback
Links e botões possuem estados de `hover` e `focus`, deixando evidente que são elementos interativos. Os cards também apresentam movimento sutil quando o cursor passa sobre eles.

### Lei de Fitts
Os botões de contato possuem uma área clicável confortável, especialmente importante em telas pequenas.

### Proximidade / Gestalt
Nome, ícone, valor e barra de cada atributo ficam agrupados no mesmo bloco. Inventário e conquistas também usam cards individuais para separar as informações.

### Fluxo de leitura
A estrutura segue uma sequência natural: apresentação do herói → capacidades → equipamentos/conquistas → contato com a guilda.

## 4. Requisitos técnicos atendidos

- HTML semântico com `header`, `nav`, `main`, `section` e `footer`.
- Hierarquia com `h1`, `h2`, `h3`.
- Imagem com `alt` descritivo.
- CSS externo.
- Variáveis CSS em `:root`.
- Flexbox na navegação.
- CSS Grid no inventário.
- Media queries para desktop, tablet e celular.
- Barras de atributos feitas somente com HTML/CSS.
- Transições em cards e botões.
- Pseudo-elemento `::before` em cards do inventário.
- Ícones temáticos usando Font Awesome.
- Biografia ilustrada.
- Item de destaque com raridade "Lendário".
- Links de contato/comunidade.
- Código separado e comentado por seção.

## 5. Protótipo visual

A composição prevista para a tela é:

1. **Topo:** identificação da ficha + menu.
2. **Hero:** avatar de Warui, nome, classe, biografia e resumo.
3. **Atributos:** barras de progresso + habilidades.
4. **Inventário:** cards de equipamentos e conquistas em Grid.
5. **Guilda:** mensagem e protocolo.
6. **Rodapé:** identificação do projeto.

No desktop, o conteúdo utiliza múltiplas colunas. No tablet, as áreas são reduzidas para duas colunas. No celular, a página passa para uma coluna, preservando a ordem de leitura.

## 6. Como executar

Basta abrir o arquivo `index.html` em um navegador.

Para usar os ícones e a fonte externa, é necessário acesso à internet. O restante da estrutura funciona localmente.

## 7. Observação sobre a Parte 2

A estrutura foi organizada para ser reutilizada posteriormente com JavaScript. IDs como `#sobre`, `#atributos`, `#inventario` e `#guilda` já facilitam a criação de interações futuras.
DME.md…]()
# -ficha-heroi-parte1.
