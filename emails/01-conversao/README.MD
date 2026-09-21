# 📥 E-mail de Conversão — Download de E-book B2B

## 🎯 Objetivo da Peça
Conduzir leads cadastrados na base de nutrição a realizarem o download do material rico (E-book de Power BI), gerando novo engajamento e qualificando o lead com intenção de aprofundamento técnico.

---

## 🛠️ Boas Práticas Técnicas Implementadas
- **Estrutura Table-Based:** Construção integral em tabelas aninhadas (`<table>`, `<tr>`, `<td>`) para suporte a Outlook (Windows/Office 365) e clientes legados.
- **Preheader Invisível:** Texto de pré-visualização configurado via CSS com *zero height* e espaçadores invisíveis (`&zwnj;&nbsp;`) para evitar que textos de cabeçalho vazem na caixa de entrada.
- **CTA Bulletproof:** Botão desenhado em célula de tabela com fundo sólido, garantindo renderização e clique mesmo se imagens estiverem desativadas.
- **Rastreamento UTM:** Parâmetros `utm_source=email`, `utm_medium=conversao` e `utm_campaign=ebook_powerbi` integrados no link principal.
- **Compliance & Entregabilidade:** Rodapé em conformidade com as diretrizes da LGPD e CAN-SPAM (endereço físico institucional e link claro de descadastro/opt-out).