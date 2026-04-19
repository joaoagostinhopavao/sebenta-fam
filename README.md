# Sebenta FAM — Ferramentas e Aplicações Multimédia

Projecto Quarto para a sebenta da UC de Ferramentas e Aplicações Multimédia,
Licenciatura em Comunicação e Multimédia, UTAD.

## Estrutura

```
Sebenta-FAM/
├── _quarto.yml          # Configuração do projecto
├── index.qmd            # Prefácio
├── capitulos/
│   ├── cap02.qmd        # Sistemas Numéricos e Codificação
│   ├── cap03.qmd        # Digitalização e Compressão
│   └── ...              # Capítulos seguintes
├── assets/
│   ├── css/custom.css   # Estilos personalizados
│   ├── images/          # Imagens e figuras
│   └── js/              # Scripts auxiliares
└── referencias.bib      # Bibliografia
```

## Renderização

```bash
# HTML interactivo
quarto render --to html

# PDF via LuaLaTeX
quarto render --to pdf

# Preview com hot reload
quarto preview
```

## Autores

João Pavão · Sérgio Madeira — UTAD, 2026
