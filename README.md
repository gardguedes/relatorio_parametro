# Relatório de Vendas com Parâmetros – Power BI

Projeto desenvolvido como parte do **bootcamp da DIO: Klabin - Excel e Power BI Dashboards**.

## 📌 Desafio do Projeto
**Desafio de Projeto – Criar visuais utilizando parâmetros no Power BI**

Este projeto foi desenvolvido como parte do Desafio de Projeto da DIO, cujo objetivo era criar pelo menos dois visuais utilizando parâmetros no Power BI, de forma a tornar a análise mais dinâmica, exploratória e personalizada para o usuário final.

O arquivo do projeto está disponível em: **[Sales Report 07-12-2025.pbix](https://github.com/gardguedes/relatorio_parametro)**.

---

## 🎯 Objetivo
Criar visuais configuráveis a partir de parâmetros, permitindo ao usuário escolher quais variáveis quer analisar — seja por categoria ou por valores — promovendo uma experiência analítica mais rica, personalizada e flexível.

---

## 🛠️ Ferramentas Utilizadas
- **Power BI Desktop**
- Parâmetros (Field Parameters)
- Gráficos de barras
- Medidas DAX

---

## 📄 Estrutura das Novas Páginas Criadas
Foram adicionadas duas páginas ao relatório:

---

## 🟦 1. Primeira Visão – Parâmetros Baseados em Categorias
Esta página utiliza **Field Parameters** para permitir que o usuário selecione qual categoria deseja analisar. Os parâmetros disponíveis são apresentados como **botões clicáveis**:

- País
- Ano
- Produto
- Segmento
- Segmentos Agrupados

### 🔎 Como os parâmetros ajudam nesta visão
Os parâmetros permitem alternar rapidamente entre diferentes dimensões da análise. Isso ajuda a responder perguntas como:

- *Quais países tiveram maior volume de vendas neste período?*
- *Quais produtos se destacaram em determinado ano?*
- *Existe um segmento que impulsiona mais vendas do que os outros?*

O usuário define **qual aspecto das vendas deseja investigar**, tornando a análise mais direcionada e relevante.

---

## 🟩 2. Segunda Visão – Parâmetros Baseados em Valores
Nesta página, os parâmetros foram criados para orientar a análise do **lucro**. Eles são exibidos como **listas selecionáveis**, oferecendo flexibilidade para escolher diferentes combinações analíticas:

- País
- Mês
- Semestres
- Segmento
- Produto

### 🔎 Como os parâmetros ajudam nesta visão
Esses parâmetros permitem explorar o lucro sob várias perspectivas, respondendo perguntas como:

- *Quais países trouxeram maior retorno financeiro?*
- *Há sazonalidade no lucro por mês ou semestre?*
- *Quais segmentos têm maior margem?*
- *Quais produtos geram mais ou menos lucro?*

Com isso, o usuário pode **comparar rapidamente diferentes níveis de detalhamento**, ajustando a análise de lucro conforme necessário.

---

## 📊 Visuais Criados
Em ambas as páginas foram utilizados **gráficos de barras**, pois:

- São versáteis e funcionam bem com qualquer tipo de parâmetro.
- Possuem alta legibilidade.
- Permitem comparação direta entre categorias e valores.
- Reagem de forma clara à troca de campos via parâmetros.

---

## 🎛️ Importância dos Parâmetros em Relatórios Power BI
Os parâmetros ampliam a capacidade de exploração do relatório, permitindo que o usuário:
- Personalize sua visão sem modificar o relatório original;
- Simule cenários diferentes rapidamente;
- Compare resultados por categorias ou valores de forma interativa;
- Transforme um relatório estático em uma ferramenta dinâmica de análise.

Eles são especialmente importantes em dashboards corporativos, pois empoderam o usuário final e reduzem a dependência de analistas para gerar novas visualizações.

---

## ▶️ Como Explorar o Relatório
1. Abra o arquivo **Sales Report 07-12-2025.pbix**.
2. Acesse a página **Primeira Visão** e clique nos botões para alternar entre os parâmetros de categoria.
3. Explore a página **Segunda Visão** selecionando os parâmetros da lista focada em lucro.
4. Observe como os gráficos de barras se reorganizam conforme a seleção.
5. Compare diferentes combinações de filtros e parâmetros para obter insights mais profundos.

---

## 🧾 Conclusão
Este projeto demonstra como o uso de parâmetros no Power BI amplia significativamente a capacidade analítica de um relatório. Ao permitir que o usuário escolha o foco da visualização, cria-se uma experiência dinâmica, acessível e completamente personalizada.

Os parâmetros tornam o relatório mais enxuto, interativo e eficiente — alinhando boas práticas de design com flexibilidade analítica.
