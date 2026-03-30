# 📦 Sistema de Gestão de Disputas e Defesas - PRATIK

Este repositório centraliza a inteligência de pós-venda da **PRATIK Distribuidora**. O objetivo é padronizar, agilizar e aumentar a taxa de conversão em disputas de devoluções nos marketplaces (Shopee, Mercado Livre, SHEIN), garantindo a proteção do fluxo de caixa e da reputação da conta.

---

## 🚀 Objetivo Estratégico
Minimizar perdas financeiras através de respostas técnicas, baseadas em evidências logísticas (pesagem, conferência e imagens) e alinhadas aos algoritmos de mediação de cada plataforma.

## 📂 Estrutura do Repositório

| Pasta | Descrição |
| :--- | :--- |
| `📂 scripts/shopee` | Modelos de texto para as 10+ razões de disputa da Shopee. |
| `📂 scripts/mercadolivre` | Defesas focadas em "Compra Garantida" e mediações. |
| `📂 scripts/shein` | Respostas adaptadas ao algoritmo específico da SHEIN. |
| `📂 docs/pops` | Procedimentos Operacionais Padrão (SOP) via Notion. |
| `📂 assets/provas` | Modelos de fotos de pesagem e etiquetas de segurança. |

---

## 🛠️ Fluxo de Operação (SOP)

Para garantir a eficiência na disputa, siga estes passos:

1. **Identificação:** Identifique o motivo real da disputa no painel do marketplace.
2. **Conferência (Tiny ERP):** Acesse o histórico do pedido no Tiny para verificar o peso de expedição e o log de separação.
3. **Seleção do Script:** Escolha o arquivo correspondente na pasta `/scripts` deste repositório.
4. **Customização:** Substitua as variáveis entre colchetes (ex: `[ID_PEDIDO]`, `[PESO_REAL]`).
5. **Evidência Visual:** Anexe a foto da pesagem/etiqueta disponível no nosso banco de dados de expedição.
6. **Submissão:** Envie a defesa e monitore o status.

---

## 📝 Exemplo de Padrão de Defesa (Peso Divergente)

> "Prezada equipe de mediação, informamos que o pedido **[ID_PEDIDO]** foi conferido e bipado em nosso sistema logístico. O peso registrado na saída foi de **[PESO_SAIDA]g**, condizente com o produto **[NOME_PRODUTO]**. O peso relatado pelo cliente apresenta divergência técnica. Segue anexo o log de expedição e foto da pesagem."

---

## 🔗 Integrações
