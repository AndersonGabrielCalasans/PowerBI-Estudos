# Modelo de de Organização dos Dados

Created: October 11, 2022 5:27 PM

É um estudo que visa, como o próprio nome já diz, organizar como será feita o trabalho com os dados e com ele é importante atender as perguntas:

- Posso levar os dados para o Power BI da forma que estão?
- Quais são os requerimentos de organização dos dados?
- Como mantenho os dados em um formato de atualização sob demanda?
- Como visualizar os dados por diferentes visões e ângulos?

É dever do analista de dados desenvolver um solução que resolva e responda a todas essas perguntas e para isso é necessário carregar os dados de uma forma que facilite a extração de relatórios e a entrega dos resultados aos tomadores de decisão!

Para atender a essa demanda precisamos de um modelo que facilite a visualização dos dados por diferentes ângulos e sob demanda, aí que entra o Modelo de de Organização dos Dados.

O modelo acompanha a seguinte resolução:

![Untitled](Modelo%20de%20de%20Organizac%CC%A7a%CC%83o%20dos%20Dados%201d89b86b92b34785a1dbdf2614e4f13e/Untitled.png)

Existem 2 modelos principais de organização dos dados: ***Star Schema*** e ***SnowFlake***. Em ambos, o objetivo é criar uma estrutura de organização, que facilite a compreensão dos dados.

Normalmente o modelo de dados é criado em um *Data Warehouse* (DW), um banco de dados que serve de fonte para processos de BI. As empresas extraem dados de sistemas transacionais, como CRM ou ERP, consolidam os dados e carregam no DW seguindo o modelo adotado. As ferramentas de BI podem conectar no DW e extrair os dados para análise.

Para o *PowerBI*, vamos implementar o modelo ***Star Schema.***

![Untitled](Modelo%20de%20de%20Organizac%CC%A7a%CC%83o%20dos%20Dados%201d89b86b92b34785a1dbdf2614e4f13e/Untitled%201.png)