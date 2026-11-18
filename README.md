# TCC — Inventário patrimonial com RFID

Trabalho de Conclusão de Curso em Ciência da Computação na UESC. O trabalho apresenta um protótipo web que registra leituras de etiquetas RFID, acompanha a localização de bens e apoia a identificação de divergências durante auditorias patrimoniais.

A validação funcional foi realizada com um leitor de proximidade em cenário controlado. A implementação está no [InventoryRFID](https://github.com/EzekLobo/inventory-rfid).

## Documento

- [PDF do trabalho](PRINCIPAL.pdf)
- [Arquivo principal em LaTeX](PRINCIPAL.tex)
- [Bibliografia](TCC.bib)

Para compilar a partir da raiz, use uma distribuição LaTeX com abnTeX2 e BibTeX.

```sh
pdflatex PRINCIPAL.tex
bibtex PRINCIPAL
pdflatex PRINCIPAL.tex
pdflatex PRINCIPAL.tex
```
