**Extraindo Dados Históricos do Ethereum do CoinMarketCap**

---

Neste documento, descrevemos o processo de extração de dados históricos do Ethereum (ETH) do site CoinMarketCap. Inicialmente, tentamos extrair dados de preços de produtos do Mercado Livre, mas encontramos dificuldades ao obter apenas os dados do mesmo dia. Em seguida, realizamos com sucesso a extração dos dados históricos do Ethereum do CoinMarketCap, usando uma combinação de scraping da web e análise de HTML.

### Tentativa de Extração de Dados do Mercado Livre:

- **Objetivo:** Inicialmente, nosso objetivo era extrair dados de preços de produtos, como iPhones, do site Mercado Livre. 
- **Desafios Encontrados:** No entanto, enfrentamos dificuldades ao tentar obter apenas os dados do mesmo dia, sem sucesso na obtenção de dados históricos.
- **Resultados:** Concluímos que a estrutura do site do Mercado Livre dificultava a extração de dados históricos, pois os dados disponíveis estavam limitados ao dia atual.

### Extração Bem-Sucedida dos Dados do CoinMarketCap:

- **Objetivo Revisitado:** Diante das dificuldades encontradas com o Mercado Livre, decidimos mudar nossa abordagem e extrair dados de preços de criptomoedas.
- **Fonte Selecionada:** Optamos por usar o CoinMarketCap devido à disponibilidade de dados históricos detalhados para várias criptomoedas, incluindo o Ethereum (ETH).
- **Método de Extração:** Utilizamos técnicas de scraping da web e análise de HTML para extrair os dados diretamente da página do CoinMarketCap.
- **Resultados:** Conseguimos com sucesso extrair os dados históricos do Ethereum, incluindo preços de fechamento diários, volumes de negociação porem so utilizamos o preço inicial para demonstrar um pouco do que é possivel.

### Conclusão:

- Embora tenhamos enfrentado desafios ao tentar extrair dados do Mercado Livre, nossa mudança para o CoinMarketCap foi bem-sucedida. 
- Este caso destaca a importância da escolha da fonte de dados adequada e da flexibilidade ao lidar com a estrutura variada dos sites da web ao realizar atividades de scraping e extração de dados.

---
