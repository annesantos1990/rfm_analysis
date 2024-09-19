<h1 align="center"> </a> RFM Analysis   </h1>

**Segmentação de clientes de uma loja usando a análise RFM**

![RFMAnalysisวิเคราะห์และแบ่งกลุ่มลูกค้าสู่ผลลัพธ์อันน่าทึ่ง](https://github.com/user-attachments/assets/8524d1c5-55b1-4ec6-ae79-0c5d22cd396b)


##

<p align="center">
 
[Caso](#caso)  •  [Objetivo](#objetivo)  •  [Ferramentas](#ferramentas)   •  [Resultados e Discussão](#resultados-e-discussão)  •  [Conclusões](#conclusões)  •  [Recomendações](#recomendações)  •  [LinkedIn](#linkedin)

</p>


## Caso
A loja “El Mercado” está num ambiente altamente competitivo e está experimentando mudanças significativas nas preferências dos consumidores. A fidelização do cliente tornou-se um desafio e a loja em questão está a procura de manter e aumentar o seu rendimento através de uma melhor compreensão de sua base de clientes e personalização de suas estratégias de marketing e retenção.

 <h2>Objetivo</h2> 

O objetivo desse projeto é fazer a análise é aprofundar a compreensão sobre os clientes da empresa *El Mercado*, permitindo que as empresas personalizem suas estratégias de marketing e vendas para entender às necessidades específicas de cada grupo de clientes de forma eficaz, além de identificar padrões de diferenças comuns e significativas entre clientes.


## Ferramentas
- Gerenciamento dos dados: BigQuery (SQL)
- Visualização de dados: Looker Studio
- Implementação do Modelo: Google Colab (Python)
- Ficha técnica: Notion, GitHub


## Biblioteca e Tratamento do Dados

A limpeza, tratamento dos dados e parte das análises dos dados foi feita pelo *Big Query*.
Para mais detalhes da biblioteca e do tratamento do dados, basta clicar nesse link: [Clique aqui](https://github.com/annesantos1990/data-cleansing_RFM/)

## Métodos e Técnicas
Para visualizar como feita a classificação dos clientes com base na análise RFM (Recência, Frequência e Valor Monetário), [clique aqui](https://github.com/annesantos1990/methods_techniques_rfm/)

### Visualização dos dados - Looker Studio
Os gráficos que estão apresentados na seção de resultados foi feito no Looker. Para acessar o dashboard feito nessa ferramenta, clique no Link abaixo:
[Clique aqui](https://lookerstudio.google.com/reporting/b583cbb9-833b-46a2-a6da-4a1eec0413ec)

Para visualizar os resultados e obter uma explicação detalhada sobre as páginas do relatório no Looker, [clique aqui](https://giddy-shamrock-550.notion.site/Resultados-e-Conclus-es-396b8a5dbe0f489ab1945b1d43e4971e?pvs=4)

<img width="282" height="250" alt="dashboard" src="https://github.com/user-attachments/assets/654971bf-e39d-4eda-b363-2e48cbf21d24">
<img width="282" height="250" alt="dashboard2" src="https://github.com/user-attachments/assets/0acbbfc5-8498-426a-af5a-627769b8a42a">
<img width="282" height="250" alt="dashboard3" src="https://github.com/user-attachments/assets/15f9638e-c4fe-4769-8e57-8c3ffb06236b">
<img width="282" height="250" alt="dashboard4" src="https://github.com/user-attachments/assets/d26845e1-8290-4591-8204-bc911b514dfc">


## Apresentação do projeto
Para ver os slides com a apresentação do projeto [clique aqui.]()
 
## Resultados e Discussão
A análise detalhada desse projeto, explicando o relatório desenvolvido no Looker studio e dos principais resultados obtidos, acesse minha página pública do Notion: [Clique aqui](https://giddy-shamrock-550.notion.site/Resultados-e-Conclus-es-396b8a5dbe0f489ab1945b1d43e4971e?pvs=4)

**Período de Coleta:** 30/07/2020 - 29/06/2022

As análises realizadas no Looker Studio proporcionaram uma visão abrangente do comportamento dos clientes e suas segmentações. A seguir, estão as principais conclusões divididas por área de foco:

### 1. Perfil dos Clientes:

- **Total de Clientes:** 2047
- **Média Salarial:** R$ 52.303,70
- **Idade Média:** 53,24 anos
- **Resposta à Campanha:** Apenas 15,29% dos clientes responderam à campanha de marketing.

**Principais Grupos:**

- **Faixa Etária predominante:** Geração X (45-63 anos) representa 47% dos clientes e 43% do valor monetário gerado.
- **Classe Social:** Embora a Classe D tenha mais clientes (52%), a Classe C gerou o maior valor monetário (57%), indicando o poder de compra superior da Classe C.
- **Estado Civil:** Clientes casados predominam, tanto em quantidade (38%) quanto em valor monetário gerado (37%).
- **Nível Educacional:** 50% dos clientes têm nível superior, representando 51% do valor monetário total.

**Comportamento de Compra:**

- **Local de Compra:** A maioria dos clientes (98%) compra em ambos os canais, loja física e site.

### 2. Análise de Produtos:

O **vinho** foi identificado como o produto mais adquirido em todas as categorias demográficas analisadas, destacando-se como o item de maior valor monetário.

- **Geração X** e **Classe C** lideram em termos de consumo e geração de receita.

### 3. Segmentação RFM:

A segmentação RFM destacou dois grupos principais que merecem atenção:

- **Clientes Fiéis:** 22,57% do total de clientes, sendo um segmento de alto valor com potencial para upselling e fidelização.
- **Hibernando:** 20,76% dos clientes, que precisam de campanhas de reengajamento para evitar a perda.

**Ações Sugeridas por Segmento:**

- **Clientes Fiéis:** Incentivar o upselling e aumentar o engajamento com recompensas e programas de fidelidade.
- **Hibernando:** Focar em reativação com ofertas e descontos exclusivos para reconquistar o interesse desses clientes.
- **Campeões:** Continuar a recompensá-los e mantê-los engajados, pois eles são os embaixadores da marca.

## Conclusões
O projeto revelou que a maioria dos clientes são da Geração X, Classe D e casados, com uma alta frequência de compra de vinho. A análise RFM mostrou que os segmentos predominantes são Clientes Fiéis e Hibernando, sugerindo foco em estratégias de retenção e engajamento. A segmentação permite direcionar campanhas personalizadas para diferentes perfis, maximizando o impacto das ações de marketing. As limitações incluem a dependência de dados gerais e a necessidade de filtragem adicional para insights mais específicos.

## Recomendações
### **Focar no Segmento de Clientes Fiéis**

- **Estratégia de Upselling**: Como os "Clientes Fiéis" representam 22,57% do total, seria interessante oferecer a eles produtos de maior valor ou combos exclusivos. Eles já têm um histórico de compra, então incentivá-los a gastar mais pode aumentar as receitas.
- **Criação de Programas de Fidelidade**: Oferecer programas de pontos, descontos ou brindes para manter esses clientes engajados e recompensá-los pela lealdade.

### **Reativar os Clientes Hibernando**

- **Campanhas de Reativação**: Clientes "Hibernando" (20,76%) precisam de ofertas atrativas e personalizadas. Envie promoções específicas, como descontos ou frete grátis, para trazê-los de volta à loja.
- **Reconstrução de Valor de Marca**: Mostre a esses clientes o valor que eles perderam desde a última compra, como novos produtos, melhorias no serviço ou inovações.

### **Promoções Personalizadas para Segmentos**

- **Campeões**: Recompense os "Campeões" com acesso antecipado a novos produtos ou descontos VIP. Isso reforça o vínculo e os transforma em embaixadores da marca.
- **Clientes em Risco**: Para os clientes "Em Risco", ofereça promoções urgentes, como descontos limitados ou recomendações personalizadas, para incentivá-los a retornar antes que eles deixem a marca.
- **Segmento "Não Posso Perdê-los"**: Foco em marketing direto com esses clientes, garantindo que eles saibam de novos produtos e tenham incentivos claros para continuar comprando.

### **Campanhas Direcionadas com Base no Perfil Demográfico**

- **Geração X e Classe C**: Focar em campanhas de marketing específicas para esses dois grupos, que têm maior poder de compra. Oferecer produtos premium, como vinhos ou itens gourmet, pode maximizar o valor monetário.

**Personalização por Local de Compra**: Como a maioria dos clientes compra tanto na loja física quanto no site, crie campanhas integradas para oferecer uma experiência de compra fluida entre os dois canais, com promoções que incentivem o uso de ambos.

### **Aumentar a Resposta às Campanhas**

- **Campanhas mais Engajadoras**: Com apenas 15,29% de resposta às campanhas, é crucial revisar as estratégias de marketing. Para isso, as informações da segmentação para personalizar e criar mensagens mais direcionadas, com benefícios claros para cada grupo.
- **Testes A/B de Campanhas**: Realizar experimentos com diferentes tipos de e-mails, mensagens e layouts de campanhas para entender quais formatos geram maior engajamento.

### **Promoção do Produto Mais Popular – Vinho**

- Dado que o vinho é o produto mais comprado em todas as categorias, é interessante considerar campanhas específicas focadas nesse item. Ofereça pacotes, combos e eventos especiais, como degustações ou descontos em compras de maior volume.

### **Explorar Potencial dos Novos Clientes**

- Criar uma boa experiência de boas-vindas para os novos clientes, educando-os sobre os produtos e serviços da loja, e oferecendo descontos para compras futuras, de modo a converter novos clientes em fiéis rapidamente.

Com essas estratégias, a loja pode otimizar o relacionamento com seus clientes, aumentar o valor médio de compra e melhorar a retenção.


## Links de Interesse:

- Repositório com a limpeza dos dados: https://github.com/annesantos1990/data-cleansing_RFM/
- Dashboard do Looker Studio: [Looker Studio](https://lookerstudio.google.com/reporting/b583cbb9-833b-46a2-a6da-4a1eec0413ec)   
- Detalhes sobre o dashboard do Looker e resultados e discussões: [Notion](https://giddy-shamrock-550.notion.site/Resultados-e-Conclus-es-396b8a5dbe0f489ab1945b1d43e4971e?pvs=4)

## LinkedIn

https://www.linkedin.com/in/eslaine-santos-e-santos-46159a28/

Obrigada por sua atenção!
