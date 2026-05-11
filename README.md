
# 👋 Hi, I'm Waiz Imran

<div align="center">

### Senior Data Engineer &nbsp;|&nbsp; Cloud Architect &nbsp;|&nbsp; Technical Leader

</div>

<br/>

---

## 🚀 About Me

<img align="right" alt="Data Engineering GIF" src="https://media.giphy.com/media/qgQUggAC3Pfv687qPC/giphy.gif" width="320"/>

I'm a **Cloud Data Engineer** from Karachi, Pakistan 🇵🇰, passionate about building
pipelines that move and transform data at scale — reliably, fast, and cleanly.

- 🔭 &nbsp; Currently building **real-time streaming pipelines** with Kafka & Spark
- ☁️ &nbsp; Working with **AWS, Snowflake**, and cloud-native data tools
- 🧪 &nbsp; Strong focus on **data quality, validation, and ETL automation**
- 💬 &nbsp; Ask me about **Python, PySpark, AWS data stack, or pipeline design**
- 🌱 &nbsp; Learning **Databricks, dbt, and Terraform**
- 🤝 &nbsp; Open to **internships, freelance projects & collaborations**
- ⚡ &nbsp; Fun fact: My pipelines run 24/7 — unlike me 😄

<br clear="right"/>

---

## 🛠️ Tech Stack

<div align="center">

### 💻 Languages & Frameworks
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)

### ☁️ Cloud & Big Data
![AWS](https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![Apache Spark](https://img.shields.io/badge/Apache%20Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=for-the-badge&logo=snowflake&logoColor=white)
![Apache Airflow](https://img.shields.io/badge/Apache%20Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white)
![Apache NiFi](https://img.shields.io/badge/Apache%20NiFi-728E9B?style=for-the-badge&logo=apache&logoColor=white)

### 🗄️ AWS Services
![Amazon S3](https://img.shields.io/badge/Amazon%20S3-569A31?style=for-the-badge&logo=amazons3&logoColor=white)
![AWS Glue](https://img.shields.io/badge/AWS%20Glue-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Amazon Redshift](https://img.shields.io/badge/Amazon%20Redshift-8C4FFF?style=for-the-badge&logo=amazon-redshift&logoColor=white)
![Amazon Athena](https://img.shields.io/badge/Amazon%20Athena-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![AWS MSK](https://img.shields.io/badge/AWS%20MSK-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white)

### 🔧 Tools & DevOps
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white)
![Looker](https://img.shields.io/badge/Looker%20Studio-4285F4?style=for-the-badge&logo=looker&logoColor=white)

</div>

---

## 🔥 Featured Projects

### Smart City Real-Time Data Pipeline
> `Python` &nbsp;`Apache Kafka` &nbsp;`Apache Spark` &nbsp;`AWS` &nbsp;`Docker`

```
5 Urban Data Sources
       │
       ▼
 Apache Kafka  ──────────────────────────────────────────┐
 (ZooKeeper)                                             │
       │                                                 │
       ▼                                                 ▼
Apache Spark                                        AWS IAM
(Distributed Processing)                          (Security)
       │
       ▼
   AWS S3 (Raw Layer)
       │
       ▼
  AWS Glue (ETL + Crawlers + Data Catalog)
       │
       ├──► Amazon Redshift (Warehouse)
       │           │
       │           ▼
       │    Amazon Athena (Serverless Query)
       │           │
       └──────────►▼
             Power BI / Tableau / Looker Studio
```

- Designed pipeline with clear ingestion → processing → storage → analytics layers for 5 simultaneous urban data streams
- Kafka topics per source; Spark master-worker cluster handles parallel distributed processing
- Glue Crawlers auto-detect schema; clean data lands in Redshift for BI dashboards
- Entire stack containerized with Docker and secured via AWS IAM

<br/>

### Real-Time Streaming — AWS MSK to Snowflake
> `AWS MSK` &nbsp;`Snowflake` &nbsp;`FastAPI` &nbsp;`EC2` &nbsp;`Python`

```
Event Producers
       │
       ▼
  Custom VPC (Multi-AZ)
  ┌─────────────────────────────────┐
  │  Public Subnet  │  Private Subnet  │
  │  EC2 (Bastion)  │  EC2 (Workers)   │
  └─────────────────────────────────┘
       │
       ▼
   AWS MSK (Managed Kafka)
       │
       ▼
  MSK Connect  ──►  Python Validation Scripts
  (Auto Connector)    (Schema + Field Checks)
       │
       ▼
  Snowflake Data Warehouse
```

- Built custom multi-AZ VPC with isolated public/private subnets for production-grade network security
- MSK Connect handles zero-touch automated data flow from Kafka to Snowflake
- Python validation scripts enforce schema + field quality checks before ingestion
- Fully documented — from infrastructure config to validation rule spec

---

## 🏆 Certifications

| Badge | Name | Issuer |
|:---:|:---|:---|
| ❄️ | Snowflake Certificate of Completion | Snowflake Inc. |
| 🎯 | AWS Cloud Practitioner *(target)* | Amazon Web Services |

---

## 📊 GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=waizimran&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true" height="165"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=waizimran&layout=compact&theme=tokyonight&hide_border=true" height="165"/>

<br/>

[![GitHub Streak](https://streak-stats.demolab.com?user=waizimran&theme=tokyonight&hide_border=true)](https://git.io/streak-stats)

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=120&section=footer&animation=twinkling" width="100%"/>

![Visitor Badge](https://visitor-badge.laobi.icu/badge?page_id=waizimran.waizimran)

</div>
