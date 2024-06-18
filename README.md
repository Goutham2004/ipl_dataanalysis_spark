# IPL Real-Time Analysis with Apache Spark


## Overview

The IPL Real-Time Analysis project leverages Apache Spark to provide comprehensive insights into Indian Premier League (IPL) cricket matches. This project processes large volumes of IPL match data to derive valuable insights and trends, focusing on real-time data analysis.
s
## Table of Contents

- [Overview](#overview)
- [Project Components](#project-components)
- [Data Schema](#data-schema)
- [Real-Time Analysis](#real-time-analysis)
- [Data Processing Steps](#data-processing-steps)
- [Visualization](#visualization)
- [Getting Started](#getting-started)
- [Contributors](#contributors)
- [License](#license)
## Images of project

  ![Alt Text](![image](https://github.com/Goutham2004/ipl_dataanalysis_spark/assets/102670790/d0728dfc-7a2c-45fb-a076-67880ed2e24f)
)


## Project Components

- **Data Source**: IPL match data from various sources, stored in an S3 bucket.
- **Apache Spark**: Used for distributed computing to process and analyze the IPL match datasets.
- **Databricks**: Utilized as the integrated environment for running Spark jobs and managing the data pipeline.

## Data Schema

The data is structured using various schemas to ensure proper loading and type consistency.

## Real-Time Analysis

The project performs various analyses on the IPL dataset, such as:

- Top-scoring batsmen per season
- Most economical bowlers in powerplay overs
- Impact of winning the toss on match outcomes
- Average runs in winning matches
- Team performance after winning the toss

## Data Processing Steps

The data processing involves several steps, including data loading, transformation, and analysis.

## Visualization

Insights and trends derived from the data are visualized using matplotlib and seaborn libraries.
q2
![Screenshot 2024-06-03 030421](https://github.com/Goutham2004/ipl_dataanalysis_spark/assets/102670790/2a24958b-2131-4f9c-94d6-7c9f8e24b9b2)

![Screenshot 2024-06-03 030412](https://github.com/Goutham2004/ipl_dataanalysis_spark/assets/102670790/ba54156d-beca-4195-939d-3a0aaa99314c)

![Screenshot 2024-06-03 030402](https://github.com/Goutham2004/ipl_dataanalysis_spark/assets/102670790/c9cd63c6-2e53-4265-905c-3767e92b7e94)

![Screenshot 2024-06-03 030352](https://github.com/Goutham2004/ipl_dataanalysis_spark/assets/102670790/6e2afb20-f40e-4b93-ab4c-f919297c7aff)


![Screenshot 2024-06-03 030336](https://github.com/Goutham2004/ipl_dataanalysis_spark/assets/102670790/2503f000-4d01-4eef-bf78-edff691f11f2)




## Getting Started

To get started with this project, follow these steps:

1. Clone the repository.
2. Set up the required environment with Apache Spark and Databricks.
3. Upload the IPL match datasets to the configured data storage (e.g., S3 bucket).
4. Execute the notebook files in Databricks to perform real-time analysis on the IPL data.

## Contributors

- kancherla goutham (@Goutham2004)



