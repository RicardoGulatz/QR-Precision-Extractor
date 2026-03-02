# 🌌 QR Precision Extractor

Ferramenta web de alta performance projetada para extrair links de QR Codes em documentos PDF, otimizada para notas fiscais (NFSe) e fluxos de automação financeira.

## 🛠️ Diferenciais Técnicos

* **Deep Scan:** Renderiza páginas em múltiplas escalas (2.0x, 3.0x e 4.0x) para capturar códigos pequenos ou com ruído.
* **Binarização Agressiva:** Algoritmo de pré-processamento que restaura o contraste de QR Codes "apagados" ou granulados.
* **Processamento em Lote:** Suporte a múltiplos arquivos simultâneos com varredura completa de todas as páginas.
* **Dashboard de Resultados:** Interface moderna com estatísticas em tempo real e sistema de notificações (toasts).

## 📊 Exportação e Utilidade

* **Excel Ready:** Gera relatórios `.xlsx` estruturados com um link por linha via SheetJS.
* **Quick Copy:** Botão dedicado para copiar todos os links encontrados de uma vez para a área de transferência.
* **Interface Premium:** Design responsivo utilizando Tailwind CSS com efeitos de *glassmorphism* e modo escuro.

## 🧰 Tecnologias Utilizadas

* **pdf.js**: Renderização robusta de arquivos PDF diretamente no navegador.
* **jsQR**: Motor de decodificação de QR Codes em alta velocidade.
* **SheetJS (XLSX)**: Geração de planilhas Excel sem necessidade de backend.
* **Tailwind CSS**: Estilização moderna e interface intuitiva.

## 📄 Licença

Este projeto está sob a licença MIT. Consulte o arquivo `LICENSE` para mais detalhes.
