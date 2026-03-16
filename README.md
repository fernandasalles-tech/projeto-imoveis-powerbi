# 📊 Dashboard de Inteligência Imobiliária - São Paulo

## 📝 Sobre o Projeto
Este projeto foi desenvolvido para análise estratégica do mercado imobiliário na cidade de São Paulo. O objetivo é permitir que investidores e locatários identifiquem oportunidades de mercado através de uma análise visual, geográfica e técnica.

## 🚀 Funcionalidades Principais (ACs)
- **AC 1 - Geolocalização Dinâmica: Mapeamento interativo de ofertas com integração Bing Maps e inteligência de filtragem cruzada (Cross-filtering), permitindo que a seleção de pontos geográficos atualize instantaneamente os indicadores de todo o dashboard.

​📂 Base de Dados Tratada (Dataset)
​Para esta entrega, foi disponibilizado o arquivo dataset_imoveis_sp_limpo.csv (ou o nome que você deu), que é o resultado do processo de ETL (Extração, Transformação e Limpeza).
​Principais tratamentos realizados:
​Padronização Geográfica: Ajuste de logradouros para garantir a plotagem correta no Bing Maps (evitando conflitos de nomes de ruas fora de São Paulo).
​Limpeza de Tipos: Conversão e correção de formatos de moeda, áreas e quantidades de quartos para garantir cálculos precisos no Power BI.
​Sufixo Geográfico: Criação de colunas auxiliares para restringir a análise à Região Metropolitana de São Paulo.
​Portabilidade: Exportação em formato CSV (UTF-8) com cabeçalhos na primeira linha, permitindo a utilização dos dados em outras ferramentas como Python ou SQL.

​📍 Nota sobre a Visualização de Mapa (Bing Maps)
​Caso o visual de mapa não carregue corretamente durante a correção, informo que:

​Lógica de Geolocalização: Todos os dados foram devidamente tratados e categorizados (Endereço, Bairro e Cidade) para garantir a plotagem.

​Limitação de Conta: Em algumas contas institucionais, o Power BI pode bloquear o acesso ao Bing Maps por políticas de segurança de locatário (tenant).

​Validação: No vídeo de demonstração da AC1, é possível visualizar o mapa funcionando perfeitamente em ambiente de desenvolvimento, confirmando que a estrutura de dados está correta.

- **AC 2 - Inteligência de Negócio e DAX: Criação de camadas de cálculos avançados utilizando Linguagem DAX (Medidas de Média de Preço, Valor por M² e KPIs de Performance). Inclui o uso de Tooltips (Dicas de Ferramenta) personalizadas para detalhamento de dados ao passar o rato.
- **AC 3 - Navegação e UX: Estruturação de um Dashboard App com menu lateral de filtros alinhado e botões de navegação entre páginas ("Panorama Geral" e "Inteligência de Mercado"). Inclui botão de Reset de Filtros para otimizar a experiência do utilizador.
- **AC 4 - Navegação Drill-through:** Sistema de navegação profunda que permite sair da visão macro e analisar a dispersão (Preço x M²) de bairros específicos.

## 🛠️ Tecnologias Utilizadas
* **Power BI:** Construção dos dashboards e visuais.
* **Power Query (ETL):** Limpeza, normalização e tratamento de dados brutos.
* **DAX:** Criação de métricas de inteligência de negócio.
* **Trello:** Gestão ágil do projeto e documentação de etapas.

* ## 🔗 Acesso ao Projeto

* **[Clique aqui para baixar o arquivo do Power BI (.pbix)](https://github.com/fernandasalles-tech/projeto-imoveis-powerbi/blob/main/Dashboard_Mercado_imobiliario_SP.pbix)**
* **[Clique aqui para visualizar o quadro de gestão no Trello](https://trello.com/b/BnpttytH/projeto-intgrador-bi-imobiliario)**
* **[Fonte dos Dados Originais](https://www.kaggle.com/datasets/renatosn/sao-paulo-housing-prices)**

> **Nota:** O mapa interativo utiliza o motor Bing Maps, por isso recomenda-se a visualização através do Power BI Desktop para garantir a total funcionalidade dos recursos de geolocalização.
---
### 🔄 Atualização de Projeto (AC1)
* **Interatividade Avançada:** Implementada a funcionalidade de **Filtro Cruzado (Cross-filtering)**. Agora, ao interagir diretamente com os pontos de geolocalização no mapa, todos os indicadores e gráficos do dashboard são filtrados automaticamente para exibir os dados específicos da região selecionada.

---
*Projeto desenvolvido para fins acadêmicos e demonstração de competências em análise de dados.*

<img width="1427" height="792" alt="Image" src="https://github.com/user-attachments/assets/acbdba5f-3682-4b15-b480-84cb875a2388" />


---
Visão Geral: Dashboard consolidado em métricas de preços e distribuição de imóveis em SP.
