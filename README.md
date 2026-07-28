# Renomeador de Laudos

App web para renomear laudos de químico digitalizados (PDF).

## O que faz
- Lê os PDFs (ou uma pasta ZIP com eles dentro)
- Usa OCR para identificar fabricante, químico, lote e ano de fabricação
- Renomeia os arquivos no padrão `QUÍMICO_LOTE_ANO`
- Gera um ZIP com os arquivos renomeados e um CSV de resumo

## Como usar
Abra o arquivo `INDEX.html` no navegador e arraste os PDFs (ou o ZIP) para a área indicada.

Tudo roda localmente no navegador — nenhum arquivo é enviado para fora.
