<table align="center"><tr><td align="center" width="9999">
<img src="https://github.com/SartMorgs/data-engineer-roadmap/blob/master/img/dataeng.jpg" align="center" width="400" alt="Project icon">

# Roadmap de Engenharia de Dados

Este repositório foi desenvolvido como um compilado de todas as skills e conteúdos que julguei interessantes de serem consumidas para aprimorar meu conhecimento em engenharia de dados. Todo conteúdo que está aqui foi formado de acordo com minha vivência nessa área, pode ser acrescentado da visão de outras pessoas que queiram colaborar. Com esse conteúdo viso me organizar, me desafiar e ajudar outras pessoas também.

Sugestões são muito bem vindas!
</td></tr></table>

## Tabela de Conteúdo
* [Skills](#skills)
* [Links-Úteis](#links-e-dicas-úteis)
* [Artigos para ler](#artigos-para-ler)
* [Livros para ler](#livros-para-ler)
* [Cursos para fazer](#cursos-para-fazer)
* [Contribuição](#contribuição)
* [Meu Resultado](#meu-resultado)

***
## Links e Dicas Úteis

Primeiro de tudo é importante se entender o que um engenheiro de dados faz, onde ele se encaixa no mercado e quais necessidades ele supre. Portanto eu recomendo os seguintes conteúdos antes de qualquer interação com o restante:

[O que é um engenheiro de dados](https://youtu.be/5ksmT5mphV4)


- [Outline - Para ler artigos premium](https://outline.com/)
- [Start Data Engineering - Muitos posts úteis](https://www.startdataengineering.com/)

Pode-se usar a guia anônima para ler os artigos que pedem premium no medium (quando o link acima não funcionar).
Infelizmente não existem tantos conteúdos em português sobre isso ainda, portanto é possível utilizar o chrome e a ferramente de tradução do google para ler os artigos caso você não entenda inglês. Para os vídeos pode-se usar a ferramenta de legendas geradas.

É importante tentar criar projetinhos para aplicar o que você está estudando, pois acredite: existe um abismo entre a teoria e a prática, principalmente se tratando de dados :)
Aproveite para exercitar sua capacidade de lidar com vários cenários de erro e criar ações para contorná-los.

***
## Skills

O básico para uso geral:

| Skill | Links | 
|:------|:------|
| Git (versionamento) | https://towardsdatascience.com/introduction-to-git-for-data-science-ca5ffd1cebbe <br> https://youtu.be/DqTITcMq68k <br> https://youtu.be/UBAX-13g8OM |
| Shell script/bash | https://www.sqlservercentral.com/articles/bash-for-etl-pre-processing <br> https://www.youtube.com/playlist?list=PLUJBQEDDLNcmHrKy_1sjd98Md-bfmtQOL |
| SSH | https://medium.com/free-code-camp/a-top-down-introduction-to-ssh-965f4fadd32e <br> https://youtu.be/HOQlfJScWH4 |
| HTTP/HTTPS | https://medium.com/swlh/how-http-and-https-work-4c689e1ea369 <br> https://medium.com/@sahelasumi/http-status-codes-31644d99fb1 |
| API | https://towardsdatascience.com/what-is-an-api-and-how-does-it-work-1dccd7a8219e |
| SQL e NoSQL | https://youtu.be/aure5d3B88g |
| Docker | https://medium.com/data-hackers/docker-do-zero-a-marinheiro-adf4d9087f76 <br> https://youtu.be/RE31GWJGkwA |
| Kubernetes | https://medium.com/the-programmer/kubernetes-fundamentals-for-absolute-beginners-architecture-components-1f7cda8ea536 <br> https://youtu.be/pV0nkr61XP8 |
| IaC/IaaS | https://medium.com/@kehinde_/infrastructure-as-code-what-is-it-all-about-c8ae2b8deddf <br> https://medium.com/tech-business-talk/the-easiest-explanation-of-iaas-paas-saas-the-3-cloud-service-models-432ac36ba6e1 <br> https://youtu.be/Yp-7Hn_O--g?t=753 |

Habilidades mais específicas:

| Grupo | Skills | Links |
|:------|:-------|:------|
| Conceitos | OLTP e OLAP <br> Business Inteligence <br> Data Modeling <br> Data Warehouse <br> Data Lake <br> Data Mesh <br> ETL e ELT | [OLTP e OLAP](https://www.linkedin.com/pulse/explain-example-oltp-vs-olap-michelle-xie/) <br> [Business Inteligence](https://youtu.be/PoCLfN6sF_8) <br> [Data Modeling](https://medium.com/sagar-explains-azure-and-analytics-data-engineerin/introduction-to-data-modelling-c0c44432ec0b) <br> [Data Warehouse](https://www.analytics8.com/blog/data-warehouse-creation-basics/) <br> [Data Lake](https://faun.pub/an-overview-of-data-lake-concepts-and-architectures-on-aws-and-azure-f485ed5110e2) <br> [Data Mesh](https://medium.com/data-hackers/data-mesh-indo-al%C3%A9m-do-data-lake-e-data-warehouse-465d57539d89) <br> [ETL e ELT](https://www.guru99.com/etl-vs-elt.html) |
| Linguagens de Programação | Python <br> R <br> Scala | [Python](https://www.youtube.com/watch?v=S9uPNppGsGo&list=PLvE-ZAFRgX8hnECDn1v9HNTI71veL3oW0) <br> [R](https://www.youtube.com/playlist?list=PLjgj6kdf_snYBkIsWQYcYtUZiDpam7ygg) <br> [Scala](https://www.youtube.com/playlist?list=PLmtsMNDRU0BxryRX4wiwrTZ661xcp6VPM) |
| Banco de Dados | RDBMS <br> NoSQL Databases | [RDBMS](https://medium.com/@asterasoftware1/all-you-need-to-know-about-relational-database-management-systems-rdbmss-4b86dd804bac) <br> [RDBMS - Postgres](https://www.youtube.com/playlist?list=PLucm8g_ezqNoAkYKXN_zWupyH6hQCAwxY) <br> [RDBMS - MySQL](https://www.youtube.com/watch?v=Ofktsne-utM&list=PLHz_AreHm4dkBs-795Dsgvau_ekxg8g1r) <br> [NoSQL Databases](https://medium.com/@mark.rethana/introduction-to-nosql-databases-c5b43f3ca1cc) <br> [NoSQL Datbases - MongoDB](https://youtu.be/x9tC0eK0GtA) <br> [NoSQL Databases - Hadoop](https://www.youtube.com/playlist?list=PLeFetwYAi-F_l-NP-TUE2MqKeu_haMP79) |
| Pipelines/ELT/ETL | Orquestradores <br> Processamento de dados <br> | [Orquestrador - Airflow](https://youtu.be/f_lnDBR3rFU?t=468) <br> [Orquestrador - Prefect](https://youtu.be/FETN0iivZps) <br> [Processamento: Batch vs Stream](https://gowthamy.medium.com/big-data-battle-batch-processing-vs-stream-processing-5d94600d8103) <br> [Processamento Bacth - Exemplo](https://www.startdataengineering.com/post/update-mysql-in-batch/) <br> [Processamento Stream - Exemplo](https://www.startdataengineering.com/post/data-engineering-project-for-beginners-stream-edition/) |
| Cloud | AWS <br> Azure <br> GCP | [AWS - Fundamentos](https://medium.com/age-of-awareness/aws-fundamentals-beginners-guide-ffea402596fb) <br> [AWS - S3](https://medium.com/analytics-vidhya/amazon-s3-for-dummies-infinite-storage-on-the-cloud-cdc43da0c013) <br> [AWS - RDS](https://medium.com/edureka/rds-aws-tutorial-for-aws-solution-architects-eec7217774dd) <br> [AWS - Athena](https://medium.com/edureka/amazon-athena-tutorial-c7583053495f) <br> [AWS - ECR/ECS](https://blog.clairvoyantsoft.com/deploy-and-run-docker-images-on-aws-ecs-85a17a073281) <br> [AWS - Lambda](https://medium.com/swlh/everything-you-need-to-know-about-aws-lambda-e0b214224b0f) <br> [AWS - StepFunction](https://medium.com/b2w-engineering/step-functions-orquestrando-aws-lambdas-1d23cdaca633) <br> [AWS - IAM](https://medium.com/kernel-space/perfect-way-to-get-started-on-aws-iam-e1d66f63acd7) <br> [AWS - EC2](https://medium.com/edureka/aws-ec2-tutorial-16583cc7798e) <br> [AWS - EMR](https://medium.com/nerd-for-tech/aws-elastic-map-reduce-intro-55206fd47c85) |

***
## Artigos
- :fire: [A Beginner’s Guide to Data Engineering — Part I](https://medium.com/@rchang/a-beginners-guide-to-data-engineering-part-i-4227c5c457d7)
- :fire: [Data Engineering 101: From Batch Processing to Streaming](https://medium.com/better-programming/data-engineering-101-from-batch-processing-to-streaming-54f8c0da66fb)
- :fire: [Implementing a Data Lake or Data Warehouse Architecture for Business Intelligence?](https://towardsdatascience.com/implementing-a-data-lake-architecture-for-business-intelligence-f2c99551db1a)
- :fire: [DataOps is NOT Just DevOps for Data](https://medium.com/data-ops/dataops-is-not-just-devops-for-data-6e03083157b7)
- :fire: [Data Warehousing: Basics of Relational Vs Star Schema Data Modeling](https://medium.com/@daryl.ung/data-warehousing-basics-of-relational-vs-star-schema-data-modeling-75a68eeaf0e3)
- :fire: [Spark 101: Introdução ao framework de processamento de dados distribuídos](https://medium.com/gabriel-luz/spark-101-introdu%C3%A7%C3%A3o-ao-framework-de-processamento-de-dados-distribu%C3%ADdos-1f959e596024)

***
## Livros para ler
- [The Data Warehouse Toolkit: The Definitive Guide to Dimensional Modeling](https://www.amazon.com.br/Data-Warehouse-Toolkit-Definitive-Dimensional/dp/1118530802/ref=asc_df_1118530802/?tag=googleshopp00-20&linkCode=df0&hvadid=379726160779&hvpos=&hvnetw=g&hvrand=10840528030872557247&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=1031754&hvtargid=pla-396828635481&psc=1)
- [Como Mentir com Estatística](https://www.amazon.com.br/Como-Mentir-Estat%C3%ADstica-Darrell-Huff/dp/858057952X/ref=sr_1_1?adgrpid=83840412449&dchild=1&gclid=CjwKCAiAqJn9BRB0EiwAJ1SztUFa3-B1ZfPfV-q9rjyzDoNLwoPF17GvS6hqgNrW9nnuLtLne7vJhBoCeDoQAvD_BwE&hvadid=425954614302&hvdev=c&hvlocphy=1031754&hvnetw=g&hvqmt=e&hvrand=11105997254867108473&hvtargid=kwd-362161445721&hydadcr=5658_11235231&keywords=como+mentir+com+estat%C3%ADstica&qid=1604763557&sr=8-1&tag=hydrbrgk-20)
- [Data Architecture: A Primer for the Data Scientist: Big Data, Data Warehouse and Data Vault](https://www.amazon.com/Data-Architecture-Primer-Scientist-Warehouse/dp/012802044X/ref=as_li_ss_tl?s=books&ie=UTF8&qid=1528996327&sr=1-102&keywords=big+data&linkCode=sl1&tag=solutionsre04-20&linkId=52b933f8ec9b490c88e937aff44c7732)


***
## Cursos para fazer
Alguns dos cursos que avaliei como benéficos para gastar meu $$$

- [Formação Engenheiro de Dados: Domine Big Data!](https://www.udemy.com/course/engenheiro-de-dados/)
- [Big Data - Processamento de dados com Spark e PySpark](https://www.udemy.com/course/big-data-com-apache-spark-e-pyspark/)
- [GCP: Complete Google Data Engineer and Cloud Architect Guide](https://www.udemy.com/course/gcp-data-engineer-and-cloud-architect/)
- [HashiCorp Certified: Terraform Associate 2020](https://www.udemy.com/course/terraform-beginner-to-advanced/)

***
## Contribuição
- Pull Request
- Discussões em Issues
- Divulgação
- Demais [![Twitter URL](https://img.shields.io/twitter/url/https/twitter.com/kamranahmedse.svg?style=social&label=%20%40sartor_morgana)](https://twitter.com/sartor_morgana)

***
## Meu Resultado
Eventualmente, conforme eu for aprendendo e aplicando tudo que reuni aqui pretendo listar todos os repositórios e conteúdo que eu gerar a partir disso.