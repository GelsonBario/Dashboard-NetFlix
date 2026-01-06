# 📺 Dashboard de Assinaturas Netflix (Projeto Estratégico)

## 📌 Visão Geral
Este repositório contém um dashboard interativo desenvolvido em Excel/Google Sheets para a gestão e análise de dados de assinantes da Netflix. O projeto transforma dados brutos de faturamento e comportamento em indicadores visuais (KPIs) para suporte à tomada de decisão.

---

## 📊 Indicadores de Performance (KPIs)
O dashboard foi estruturado para monitorar quatro métricas vitais:

1. **Faturamento Bruto:** Valor total arrecadado, somando assinaturas base e taxas de perfis extras, subtraindo os cupons.
2. **Taxa de Churn:** Percentual de cancelamento da base (usuários inativos), permitindo medir a fidelidade do cliente.
3. **Total de Assinantes:** Volume total de usuários cadastrados na base de dados.
4. **ARPU (Average Revenue Per User):** Receita média gerada por cada usuário, essencial para medir o sucesso de planos mais caros.

---

## 🛠️ Tecnologias e Referências Técnicas
* **Ferramenta:** Microsoft Excel / Google Sheets.
* **Referência Visual:** Identidade visual oficial da Netflix.
    * **Fundo:** Dark Mode (#141414).
    * **Destaques:** Vermelho Netflix (#E50914).
    * **Tipografia:** Cores contrastantes (Branco e Cinza Claro) para garantir a legibilidade em telas escuras.
* **Lógica de Fórmulas:** Utilização de funções avançadas como `SOMASE`, `CONT.SE`, `MÉDIA` e conexões dinâmicas entre caixas de texto e células da aba de cálculos.

---

## 🧩 Estrutura da Planilha
Para manter a organização profissional, o arquivo foi dividido em três camadas:
* **`Bases`**: A "Single Source of Truth" (Fonte Única da Verdade), onde estão os 60 registros de usuários, datas e valores.
* **`Cálculos`**: A camada de inteligência de dados, onde as fórmulas processam os números brutos.
* **`Dashboard`**: A camada visual, livre de linhas de grade, focada na experiência do usuário (UX).

---

## 📈 Visualizações Inclusas
* **Cards Dinâmicos:** Indicadores macro no topo do painel.
* **Gráfico de Rosca:** Distribuição percentual entre os planos (Premium, Padrão e Com Anúncios).
* **Gráfico de Barras Horizontais:** Análise de dispositivos (Smart TV, Mobile, Console, etc.), facilitando a identificação de onde o público mais consome conteúdo.

---

## 💡 Diferenciais do Projeto
Este projeto não apenas conta assinaturas, mas simula o modelo de negócio atual da Netflix, incluindo a variável de **"Perfil Extra"** (taxa de compartilhamento de senha) e a análise de impacto de **cupons de desconto** no faturamento final.

---
**Desenvolvido por:** [Seu Nome Aqui]
**Data:** 2024