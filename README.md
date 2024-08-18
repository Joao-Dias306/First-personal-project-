# First-personal-project-
**English version**

<div align="center">

# Hello there! 👋

## I am here to share my first personal project!!🥳🥳
</div>

Some information about the project: 

+ Where did I get the original dataset from?
    - I got it from [Kaggle](https://www.kaggle.com/datasets/uom190346a/e-commerce-customer-behavior-dataset).

+ Which programming language and vizualization software were used?
    - I used: <div align="center">![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Power Bi](https://img.shields.io/badge/power_bi-F2C811?style=for-the-badge&logo=powerbi&logoColor=black).</div>

+ Is the data exstracted from real business?
    - No, it is not. According with the author it was <cite>- "synthetically generated for illustrative purposes, and any resemblance to real individuals or scenarios is coincidental."</cite>

+ Where can I find the Paython analysis?
    - It will be provided in this repository, while the PowerBi DashBoards will be only given in images on this README file. 

+ Overview of the Dataset columns:
    - Customer ID:

    Type: Numeric
    
    Description: A unique identifier assigned to each customer, ensuring distinction across the dataset.
    
    - Gender:
    
    Type: Categorical (Male, Female)
    
    Description: Specifies the gender of the customer, allowing for gender-based analytics.

    - Age:

    Type: Numeric

    Description: Represents the age of the customer, enabling age-group-specific insights.

    - City:

    Type: Categorical (City names)

    Description: Indicates the city of residence for each customer, providing geographic insights.
    - Membership Type:

    Type: Categorical (Gold, Silver, Bronze)
    
    Description: Identifies the type of membership held by the customer, influencing perks and benefits.
    - Total Spend:

    Type: Numeric
    
    Description: Records the total monetary expenditure by the customer on the e-commerce platform.

    - Items Purchased:

    Type: Numeric

    Description: Quantifies the total number of items purchased by the customer.

    - Average Rating:

    Type: Numeric (0 to 5, with decimals)

    Description: Represents the average rating given by the customer for purchased items, gauging satisfaction.

    - Discount Applied:

    Type: Boolean (True, False)
    
    Description: Indicates whether a discount was applied to the customer's purchase, influencing buying behavior.

    - Days Since Last Purchase:

    Type: Numeric

    Description: Reflects the number of days elapsed since the customer's most recent purchase, aiding in retention analysis.

    - Satisfaction Level:

    Type: Categorical (Satisfied, Neutral, Unsatisfied)

    Description: Captures the overall satisfaction level of the customer, providing a subjective measure of their experience.

___ 


<div align="center">

### **Now that we know a little bit about this project lets show the Dashboards and the conclusions.**

</div>

<div align="center">

### DashBoard 1!! 

</div>

![Dashboard_1](https://github.com/user-attachments/assets/0476c820-6f33-4dce-bec0-d806792e9a0c)


Here we are trying to find our target audience. Because if we can find our target audience we can have a better return on investment (ROI) throughout our marketing campaigns. 

In order to find it we made this Dashboard comparing the quantity of sold items and sells with our clients in the dataset considering also their gender.

In the dataset, we only found two genders: female and male. We can see that the total spent by both is around 295.03 Mil and that men are accountable for more than half of it. This is shown on the top right graph. 

Also, we found through quantitative methods that our target audience age group should be 30 years old. They are the larger age group when it comes to spending and items purchased by our company. When looking into the standard deviation in "items purchased" we found a low number which correlates with a good consistency of the numbers in each age group, meaning that in all cities where the data was collected, we had a similar number of purchased items by age group.

In the tree map graph in the middle of the dashboard, we can also see that the greatest number of purchased items was made by the 30-year-old with more than double the size of the 31, 32, 27, and 28-year-old. Which they have good numbers of bought products but not like the 30 years old age group. Once more, we emphasize that our target audience should be 30 years old with an acceptable range of 2 years up and down. 

The bar graph at the bottom gives another perspective of what we have been talking about but in a different way. There we can see a strong correlation between the total sum spent by age with the sum of items purchased by age. This shows that the 30-year-old age group has the most effect on our company's revenue.

In conclusion, with the first Dashboard and the studies we made, the target audience to be considered in our market efforts should be men in the 30-year-old age group with an acceptable range of two years up or down. As we found that they affect a good quantity of our company revenue in our studies.

<div align="center">

### DashBoard 2!! 

</div>

![Dashboard_2](https://github.com/user-attachments/assets/fe304173-df2e-4d36-8c3b-2a675bac29e1)

Now we will find out how we could increase our revenue. We started with which city would be best to focus our marketing efforts on to increase the number of loyal customers. For this matter, it would be easier if we already have satisfied clients that could be used as references. It was not surprising to find that the cities with the most satisfied clients were also with the clients that spend the most in our company. Therefore, the best choices were San Francis and New York. We can see these metrics in this dashboard in the bar graph and the map graph. 

Then, we try to figure out how we could improve the level of satisfaction of our already clients. Because it gave us a risk of losing them. On this dashboard, we can see some interesting data to help us with that, such as the Average Rating given by our unsatisfied clients. It shows that our ratings are not low, it is important to remember that the ratings go from 0 to 5, and we had an average of 3.69. To complete the analysis we can see that the lowest number of days that an unsatisfied client bought with us was 32 days. These metrics combined tell us that something must have happened in the last month reducing our search for the problem.

It doesn't show on the dashboard, but we analyzed on Python that all the unsatisfied clients had previously purchased from us. This fact together with the idea that the average rating given by them was not small means that they were satisfied with the other purchased items and the problem occurred in the last item bought by them.

To further reduce our problem search we narrowed down to the cities where we only had unsatisfied clients. As shown at the bottom left of the DashBoard, the cities are Chicago and Miami.

In conclusion, until we discover what problem occurred and what caused it we can't get new loyal clients in these cities. Because to neglect the already unsatisfied ones means a great probability of losing them, and they represent a respectable piece of our revenue. Hence, we had the scope of the search reduced now it is necessary to make another dataset. 


**Versão PT-BR**

<div align="center">

# Olá! 👋

## Estou aqui para compartilhar meu primeiro projeto pessoal!!🥳🥳

</div>

Algumas informações sobre o projeto: 

+ De onde obtive o conjunto de dados original?
    - Eu peguei isso de 
+ Qual linguagem de programação e software de visualização foram utilizados?
    - Eu usei:  <div align="center">![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Power Bi](https://img.shields.io/badge/power_bi-F2C811?style=for-the-badge&logo=powerbi&logoColor=black).</div>

+ Os dados são extraídos de negócios reais?
    - Não, não é. Segundo o autor foi <cite>- "gerado sinteticamente para fins ilustrativos, e qualquer semelhança com indivíduos ou cenários reais é mera coincidência."</cite>

+ Onde posso encontrar a análise do Paython?
    - Será fornecido neste repositório, enquanto os PowerBi DashBoards serão fornecidos apenas em imagens neste arquivo README. 

+ Visão geral das colunas do conjunto de dados:
    - ID do cliente:

    Tipo: Numérico
    
    Descrição: Um identificador exclusivo atribuído a cada cliente, garantindo a distinção em todo o conjunto de dados.
    
    - Gênero:
    
    Tipo: Categórico (Masculino, Feminino)
    
    Descrição: especifica o sexo do cliente, permitindo análises baseadas em gênero.

    - Idade:

    Tipo: Numérico

    Descrição: representa a idade do cliente, permitindo insights específicos por faixa etária.

    - Cidade:

    Tipo: Categórico (nomes de cidades)

    Descrição: Indica a cidade de residência de cada cliente, fornecendo insights geográficos.
    - Tipo de associação:

    Tipo: Categórico (Ouro, Prata, Bronze)
    
    Descrição: Identifica o tipo de adesão do cliente, influenciando vantagens e benefícios.
    - Gasto total:

    Tipo: Numérico
    
    Descrição: Registra o gasto monetário total do cliente na plataforma de e-commerce.

    - Itens adquiridos:

    Tipo: Numérico

    Descrição: Quantifica o número total de itens adquiridos pelo cliente.

    - Avaliação Média:

    Tipo: Numérico (0 a 5, com decimais)

    Descrição: Representa a avaliação média dada pelo cliente aos itens adquiridos, aferindo a satisfação.

    - Desconto aplicado:

    Tipo: Booleano (Verdadeiro, Falso)
    
    Descrição: Indica se foi aplicado desconto na compra do cliente, influenciando no comportamento de compra.

    - Dias desde a última compra:

    Tipo: Numérico

    Descrição: Reflete o número de dias decorridos desde a compra mais recente do cliente, auxiliando na análise de retenção.

    - Nível de satisfação:

    Tipo: Categórico (Satisfeito, Neutro, Insatisfeito)

    Descrição: Captura o nível geral de satisfação do cliente, fornecendo uma medida subjetiva de sua experiência.

___ 


<div align="center">

### **Agora que sabemos um pouco sobre este projeto vamos mostrar os Dashboards e as conclusões.**

</div>

___

<div align="center">

### DashBoard 1!! 

</div>

![Dashboard_1](https://github.com/user-attachments/assets/0476c820-6f33-4dce-bec0-d806792e9a0c)

Estamos aqui focados em identificar nosso público-alvo, pois ao encontrá-lo, poderemos obter um melhor retorno sobre o investimento (ROI) em nossas campanhas de marketing.

Para isso, criamos este dashboard que compara a quantidade de itens vendidos com nossos clientes, considerando também o gênero.

Nos dados analisados, encontramos apenas dois gêneros: feminino e masculino. Constatamos que o total gasto por ambos gira em torno de 295,03 mil, sendo os homens responsáveis por mais da metade desse valor, como mostrado no gráfico superior direito.

Além disso, por meio de métodos quantitativos, identificamos que a faixa etária do nosso público-alvo deve ser de 30 anos. Essa é a maior faixa etária em termos de gastos e itens adquiridos em nossa empresa. Ao analisar o desvio padrão em "itens comprados", encontramos um número baixo, indicando uma boa consistência dos números em cada faixa etária. Ou seja, em todas as cidades onde os dados foram coletados, houve uma quantidade semelhante de itens comprados por faixa etária.

No gráfico de mapa de árvore, localizado no centro do dashboard, também podemos ver que o maior número de itens comprados foi feito por clientes com 30 anos, representando mais do que o dobro em comparação com clientes de 31, 32, 27 e 28 anos, que também compraram uma quantidade significativa de produtos, mas não tanto quanto os de 30 anos. Reforçamos, portanto, que nosso público-alvo deve ser composto por pessoas de 30 anos, com uma margem aceitável de dois anos para mais ou para menos.

O gráfico de barras na parte inferior oferece uma outra perspectiva, mostrando uma forte correlação entre o valor total gasto e a soma dos itens adquiridos por idade. Isso confirma que a faixa etária de 30 anos é a que mais impacta o faturamento da nossa empresa.

Em conclusão, com base no primeiro dashboard e nos estudos realizados, o público-alvo para nossas campanhas de marketing deve ser composto por homens na faixa etária de 30 anos, com uma margem aceitável de dois anos para mais ou para menos, uma vez que identificamos que eles são responsáveis por uma parte significativa da receita da empresa.

<div align="center">

### DashBoard 2!! 

</div>

![Dashboard_2](https://github.com/user-attachments/assets/fe304173-df2e-4d36-8c3b-2a675bac29e1)

Agora, vamos descobrir como podemos aumentar nossa receita. Iniciamos identificando em qual cidade seria mais estratégico concentrar nossos esforços de marketing para aumentar o número de clientes fiéis. Seria ideal se já tivéssemos clientes satisfeitos que pudessem servir como referência. Não foi surpresa perceber que as cidades com clientes mais satisfeitos também são aquelas onde os clientes mais gastam na nossa empresa. Portanto, as melhores escolhas foram São Francisco e Nova York. Podemos observar essas métricas no painel, tanto no gráfico de barras quanto no gráfico de mapa.

Em seguida, buscamos entender como poderíamos melhorar o nível de satisfação dos nossos clientes atuais, pois há um risco significativo de perdê-los. Neste dashboard, podemos visualizar alguns dados interessantes para nos auxiliar, como a Avaliação Média dada pelos nossos clientes insatisfeitos. Essas avaliações não são baixas — é importante lembrar que as notas variam de 0 a 5, e tivemos uma média de 3,69. Além disso, constatamos que o menor intervalo de tempo entre a última compra de um cliente insatisfeito e a análise foi de 32 dias. Esses indicadores sugerem que algo aconteceu no último mês, reduzindo nosso escopo de investigação.

Embora não esteja visível no painel, analisamos em Python e verificamos que todos os clientes insatisfeitos já haviam comprado conosco anteriormente. Isso, combinado com o fato de que a média das avaliações não foi baixa, sugere que os clientes estavam satisfeitos com as compras anteriores e que o problema ocorreu no último item adquirido.

Para restringir ainda mais nossa busca pelo problema, focamos nas cidades onde os clientes insatisfeitos estão concentrados. Como mostrado no canto inferior esquerdo do dashboard, as cidades em questão são Chicago e Miami.

Em conclusão, até identificarmos a causa do problema e resolvê-la, não conseguiremos fidelizar novos clientes nessas cidades. Ignorar os clientes já insatisfeitos significa correr um grande risco de perdê-los, e eles representam uma parte significativa da nossa receita. Assim, com o escopo da busca reduzido, é necessário criar outro conjunto de dados para uma análise mais detalhada.
