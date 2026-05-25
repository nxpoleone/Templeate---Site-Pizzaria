# Template — Site para Pizzaria

Site responsivo e pronto para uso, desenvolvido com HTML e CSS puro. Sem dependências externas, fácil de personalizar e publicar.

## Preview

> Abra o arquivo `index.html` no navegador para visualizar o template.

---

##  Como usar

1. Faça o download ou clone este repositório
2. Abra o arquivo `index.html` em qualquer editor de código (ex: VS Code)
3. Siga o checklist abaixo para personalizar

---

##  Checklist de personalização

### Textos
- [ ] Nome da pizzaria na `<nav>` (linha com `Nome da Pizzaria`)
- [ ] Slogan no hero (`A pizza mais gostosa da cidade`)
- [ ] Descrição do hero (`Ingredientes frescos...`)
- [ ] Tempo de entrega, avaliação e política de frete na `.info-bar`
- [ ] Nome, descrição e preço de cada pizza nos `.pizza-card`
- [ ] Endereço, telefone e horários no `.footer`

### Imagens
- Cada card tem uma `div.pizza-img` com `background-image: url('')`
- Coloque o caminho da sua imagem dentro das aspas:
  ```html
  <div class="pizza-img" style="background-image: url('imagens/margherita.jpg');"></div>
  ```
- Recomendado: imagens em `600x400px`, formato `.jpg` ou `.webp`

### Cores
- A cor principal (vermelho) é `#c0392b` — busque e substitua para mudar o tema
- O fundo escuro do hero e rodapé é `#1a0a00`

---

##  Estrutura sugerida do projeto

```
pizzaria/
├── index.html
├── README.md
└── imagens/
    ├── margherita.jpg
    ├── carne-seca.jpg
    ├── frango.jpg
    └── chocolate.jpg
```

---

##  Tecnologias

- HTML5
- CSS3
- Google Fonts (Playfair Display + Inter)

---

##  Licença

Livre para uso pessoal e comercial. Atribuição não obrigatória, mas apreciada.
