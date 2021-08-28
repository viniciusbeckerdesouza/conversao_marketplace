# Análise de conversão em um marketplace

Neste trabalho realizo a análise de conversões e outras métricas em um marketplace.

## Etapas

1. Carregamento e transformação dos dados.
2. Análise explorratório dos dados.
3. VIsualização de indicadores relevantes.
4. Utilização da base de dados para treinar um modelo de Regressão Logística.

## Conclusões

No período observado, o marketplace contou com **621** lojas ativas.

O dia com mais vendas foi **15 de Abril**, quando foram realizadas 217 negociações.

A **taxa de conversão mensal** foi de:
* 24,7% em Janeiro
* 25,8% em Fevereiro
* 23,5% em Março
* 20,2% em Abril
* 19,9% em Maio

![image](https://user-images.githubusercontent.com/72235256/131224132-22a84713-68af-437b-a86b-ea0e95f677d6.png)

O **GMV** - *volume bruto de mercadoria* - foi maior em **Março** e **Abril**:

![image](https://user-images.githubusercontent.com/72235256/131224173-54ce0d2e-6b0a-41fe-a1e2-26a3a45e49f0.png)

Houve um **período promocional** entre 20 e 31 de Março, com um pico de vendas em 28 de Março.

Encontramos uma **correlação** entre número de vendas, número de acessos e GMV:

![image](https://user-images.githubusercontent.com/72235256/131224263-396bb376-b9d9-4a4d-bdff-1bc19252021c.png)

Nosso modelo de Regressão Linear obteve um score de 0.77.

Nosso modelo de Árvore de Decisão obteve um score de 0.98.


