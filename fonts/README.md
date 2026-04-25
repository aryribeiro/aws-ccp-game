# Fontes de Backup para Certificados

## Por que esta pasta existe?

O Streamlit Cloud pode não ter todas as fontes do sistema disponíveis. Esta pasta serve como backup para garantir que os certificados sejam gerados corretamente com fontes adequadas.

## Como adicionar fontes de backup

### Opção 1: Usar fontes do Google Fonts (Recomendado)

1. Acesse: https://fonts.google.com/
2. Escolha uma fonte (ex: Roboto, Open Sans, Montserrat)
3. Baixe a fonte
4. Coloque os arquivos `.ttf` nesta pasta:
   - `fonts/NomeDaFonte-Bold.ttf`
   - `fonts/NomeDaFonte-Regular.ttf`

### Opção 2: Usar DejaVu Sans (Livre e com acentos)

1. Baixe de: https://dejavu-fonts.github.io/Download.html
2. Extraia e copie para esta pasta:
   - `fonts/DejaVuSans-Bold.ttf`
   - `fonts/DejaVuSans.ttf`

### Opção 3: Usar Liberation Sans (Alternativa livre)

1. Baixe de: https://github.com/liberationfonts/liberation-fonts
2. Copie para esta pasta:
   - `fonts/LiberationSans-Bold.ttf`
   - `fonts/LiberationSans-Regular.ttf`

## Fontes recomendadas (com suporte a acentos)

✅ **DejaVu Sans** - Excelente suporte Unicode
✅ **Liberation Sans** - Compatível com Arial
✅ **Roboto** - Moderna e limpa
✅ **Open Sans** - Muito legível
✅ **Montserrat** - Elegante

## IMPORTANTE

- As fontes devem ter suporte a **Unicode** para renderizar acentos corretamente
- Use fontes com licença livre (OFL, GPL, Apache)
- Não inclua fontes proprietárias (Arial, Calibri, etc.) no repositório

## Licenças

Certifique-se de que as fontes adicionadas têm licença compatível com seu projeto:
- ✅ OFL (Open Font License)
- ✅ Apache License 2.0
- ✅ GPL
- ❌ Fontes proprietárias da Microsoft/Apple
