<h1 align="center">Hi 👋, I'm Abdelnaem Alaref</h1>
<h3 align="center"> Business Intelligence Engineer </h3>

<br/>

![](https://github.com/halfrost/halfrost/blob/master/icons/header_.png)

- 🌱 I’m currently learning **SQL**

- 👨‍💻 All of my projects are available at [https://github.com/Abdelnaem2002](https://github.com/Abdelnaem2002)

- 💬 Ask me about **Data**

- 📫 How to reach me **mhmwdalarf97@gmail.com**

- ⚡ Fun fact: Marathon runner

- So I  checkout a branch and start writing SQL using
<br><br/>

<img src="https://www.ancoris.com/hubfs/Partner%20logos/dbt%20transparent%20logo7.png" alt="dbt Logo" width="250" height="100">
<br><br/>

After I grab my morning coffee , I start my work with the goal of building something like this :
<br><br/>
So I  checkout a branch and start writing SQL using
<br><br/>


that usually looks like :
```
{{
  config(
    alias='cool_data_mart_name',
    materialized: table
  )
}}

WITH fact_table AS (
  SELECT * FROM {{ref('fact_table_name')}} WHERE [condition]
  ),

dimention_table_1 AS (
  SELECT
    {{ dbt_utils.star(
        from=ref('dimention_table_1_name'),
        except=[UNWANTED_COLUMN_NAMES],
        , relation_alias='d1'
        )}},
   FROM
      {{ref('dimention_table_1_name')}} AS d1
   WHERE
      [condition]
  ),

dimention_table_2 AS (
  SELECT * FROM {{ref('dimention_table_2_name')}} WHERE [condition]
  ),

final AS (
  SELECT
    f.col1,
    d1.*,
    COALESCE(d2.col123, 'default_value') AS col123,
    ROW_NUMBER() OVER( PARTITION BY id ORDER BY event_at DESC) AS deduplicate
  FROM
    fact_table AS f
  INNER JOIN
    dimention_table_1 AS d1
  ON
    f.foreign_1 = d1.primary
  LEFT JOIN
    dimention_table_2 AS d2
  ON
    f.foreign_2 = d2.primary
  WHERE
    [insert mart conditions]
  QUALIFY
   deduplicate = 1
)
SELECT * FROM final
  ```




Speaking of Data Warehouses I previously used

<img src="https://th.bing.com/th/id/R.28dbe7572811cb1cc6f38136cebda27c?rik=N7jRVMj%2bRX9K%2bw&pid=ImgRaw&r=0" alt="Redshift Logo" width="300" height="200">
<br><br/>


so I am experienced with that as well :)


No, I am not done yet!

The rest of my role is building charts and dashboards To help Business

<img src="https://th.bing.com/th/id/R.0dcdd373243bd1c01e7b1efb17351ad1?rik=H7d3jF4pNlA9WA&pid=ImgRaw&r=0" alt="Tableau Logo" width="300" height="200">
<br><br/>

<img src="https://linksinternational.com/wp-content/uploads/2020/09/PowerBI-Logo.png" alt="Power Bi" width="350" height="250">
<br>
<br><br/>
<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://www.linkedin.com/in/abdelnaem-alaref-404002190/" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="abdelnaem-alaref" height="30" width="40" /></a>
<a href="https://kaggle.com/abdelnaemalaref" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/kaggle.svg" alt="abdelnaemalaref" height="30" width="40" /></a>
<a href="https://fb.com/abdelnaemalaref" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/facebook.svg" alt="abdelnaemalaref" height="30" width="40" /></a>
</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> 
<a href="" target="_blank" rel="noreferrer"> <img src="https://icon-library.com/images/relational-database-icon/relational-database-icon-21.jpg" alt="Database" width="50" height="40"/> </a>
<a href="" target="_blank" rel="noreferrer"> <img src="https://www.nuget.org/profiles/powerbi/avatar?imageSize=512" alt="Powerbi" width="40" height="40"/> </a> 
<a href="" target="_blank" rel="noreferrer"> <img src="https://i.pinimg.com/originals/13/88/5f/13885f590c6070c7f106b0f19a17ab9b.png" alt="Excel" width="40" height="40"/> </a>
<p align="left"> <a href="https://www.figma.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/figma/figma-icon.svg" alt="figma" width="40" height="40"/> </a> <a href="https://git-scm.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> </a> <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/> </a> <a href="https://www.mysql.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/> </a> <a href="https://pandas.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/pandas/pandas-original.svg" alt="pandas" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> <a href="https://seaborn.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://seaborn.pydata.org/_images/logo-mark-lightbg.svg" alt="seaborn" width="40" height="40"/> </a> </p> 
<img height="32" width="32" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/visual-studio-code/visual-studio-code.png" />

<p><img align="left" src="https://github-readme-stats.vercel.app/api/top-langs?username=abdelnaem2002&show_icons=true&locale=en&layout=compact" alt="abdelnaem2002" /></p>

<p>&nbsp;<img align="center" src="https://github-readme-stats.vercel.app/api?username=abdelnaem2002&show_icons=true&locale=en" alt="abdelnaem2002" /></p>

<p><img align="center" src="https://github-readme-streak-stats.herokuapp.com/?user=abdelnaem2002&" alt="abdelnaem2002" /></p>
