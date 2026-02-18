# Paper LaTeX

Repositório para edição colaborativa do paper acadêmico.

## 📁 Estrutura

```
├── main.tex           # Arquivo principal
├── references.bib     # Referências bibliográficas
├── sections/          # Seções do paper
│   ├── intro.tex
│   ├── methods.tex
│   └── results.tex
├── figures/           # Imagens e figuras
└── README.md
```

## ✏️ Editar Online

### Overleaf (Recomendado)
1. Acesse https://www.overleaf.com
2. Clique em **New Project** → **Upload Project**
3. Envie todos os arquivos deste repositório
4. Edite e compile na nuvem

### Outras opções
- [Authorea](https://www.authorea.com)
- [CoCalc](https://cocalc.com)

## 🖥️ Compilar Localmente

### Pré-requisitos
- [TeX Live](https://www.tug.org/texlive/) (Linux/Windows)
- [MacTeX](https://tug.org/mactex/) (macOS)
- Ou [MiKTeX](https://miktex.org)

### Comandos
```bash
# Compilar
pdflatex main.tex
bibtex main
pdflatex main.tex
pdflatex main.tex

# Ou usar latexmk (automático)
latexmk -pdf main.tex
```

## 🤖 Editar com IA

Este repositório está otimizado para edição por assistentes de IA:
- Seções separadas em arquivos individuais
- Comentários claros em português
- Estrutura padrão fácil de navegar

### Dicas para IAs
1. Referencie sempre o label da seção: `\label{sec:intro}`
2. Use `\cite{chave}` para citações da `references.bib`
3. Figuras devem estar em `figures/` com formato PNG, PDF ou SVG

## 📄 Licença

Este trabalho está licenciado sob [escolha sua licença, ex: CC BY 4.0]
