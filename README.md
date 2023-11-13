<div align="center" id="top"> 
  <img src="./.github/app.gif" alt="DataEngineer" />

  &#xa0;

  <!-- <a href="https://dataengineer.netlify.app">Demo</a> -->
</div>

<h1 align="center">DataEngineer Youtube Project</h1>

<p align="center">
  <img alt="Github top language" src="https://img.shields.io/github/languages/top/{{YOUR_GITHUB_USERNAME}}/dataengineer?color=56BEB8">

  <img alt="Github language count" src="https://img.shields.io/github/languages/count/{{YOUR_GITHUB_USERNAME}}/dataengineer?color=56BEB8">

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/{{YOUR_GITHUB_USERNAME}}/dataengineer?color=56BEB8">

  <img alt="License" src="https://img.shields.io/github/license/{{YOUR_GITHUB_USERNAME}}/dataengineer?color=56BEB8">

  <!-- <img alt="Github issues" src="https://img.shields.io/github/issues/{{YOUR_GITHUB_USERNAME}}/dataengineer?color=56BEB8" /> -->

  <!-- <img alt="Github forks" src="https://img.shields.io/github/forks/{{YOUR_GITHUB_USERNAME}}/dataengineer?color=56BEB8" /> -->

  <!-- <img alt="Github stars" src="https://img.shields.io/github/stars/{{YOUR_GITHUB_USERNAME}}/dataengineer?color=56BEB8" /> -->
</p>

<!-- Status -->

<!-- <h4 align="center"> 
	🚧  DataEngineer 🚀 Under construction...  🚧
</h4> 

<hr> -->

<p align="center">
  <a href="#dart-about">About</a> &#xa0; | &#xa0; 
  <a href="#sparkles-goals">Goals</a> &#xa0; | &#xa0;
  <a href="#sparkles-features">Features</a> &#xa0; | &#xa0;
  <a href="#rocket-technologies">Technologies</a> &#xa0; | &#xa0;
  <a href="#white_check_mark-requirements">Archaitecture</a> &#xa0; | &#xa0;
  <a href="#checkered_flag-starting">Starting</a> &#xa0; | &#xa0;
  <a href="#memo-license">License</a> &#xa0; | &#xa0;
  <a href="https://github.com/{{YOUR_GITHUB_USERNAME}}" target="_blank">Author</a>
</p>

<br>

## :dart: About ##

On this project we are going to use Proccess data that come from the YOUTUBE API. The data can be find on https://www.kaggle.com/datasets/datasnaek/youtube-new

## :sparkles: Goals ##
1. Data Ingestion — Build a mechanism to ingest data from different sources
2. ETL System — We are getting data in raw format, transforming this data into the proper format
3. Data lake — We will be getting data from multiple sources so we need centralized repo to store them
4. Scalability — As the size of our data increases, we need to make sure our system scales with it
5. Cloud — We can’t process vast amounts of data on our local computer so we need to use the cloud, in this case, we will use AWS
6. Reporting — Build a dashboard to get answers to the question we asked earlier


## :sparkles: Features ##

:heavy_check_mark: Amazon S3;\
:heavy_check_mark: AWS IAM;\
:heavy_check_mark: AWS GLUE;\
:heavy_check_mark: AWS LAMBDA;\
:heavy_check_mark: AWS Athena;\
:heavy_check_mark: QuickSight;


## :rocket: Technologies ##

The following tools were used in this project:

- [Athena](https://aws.amazon.com/athena)
- [AWS LAMBDA](https://aws.amazon.com/es/pm/lambda/?gclid=Cj0KCQiAr8eqBhD3ARIsAIe-buNyrpmuZMwaDYoyFRL8_JOAWqyalTWHd7XUB-oNRm8qg4XQEx_mS0YaAhY-EALw_wcB&trk=c8019b8a-d2f2-4ec8-ac50-7bdc0dbe1996&sc_channel=ps&ef_id=Cj0KCQiAr8eqBhD3ARIsAIe-buNyrpmuZMwaDYoyFRL8_JOAWqyalTWHd7XUB-oNRm8qg4XQEx_mS0YaAhY-EALw_wcB:G:s&s_kwcid=AL!4422!3!651612391322!e!!g!!aws%20lambda!19828205892!147081379877)
- [AWS GLUE](https://aws.amazon.com/glue/)
- [Python](https://www.python.org/)
- [Pandas](https://pandas.pydata.org/)

## :white_check_mark: Architecture ##

![Architecture](https://github.com/DuvanEZ/data-youtube-end-to-end/blob/master/architecture.jpeg)



## :checkered_flag: Starting ##

Useful links mentioned in the video - 
1. Create Your AWS Account - https://aws.amazon.com/premiumsupport...
2. Download AWS CLI - https://aws.amazon.com/cli/

 Instala AWS CLI
Configuración de AWS CLI: Una vez que AWS CLI está instalado, puedes configurarlo ejecutando el siguiente comando en tu terminal:

```bash
aws configure
```
Ingreso de credenciales: Se te pedirá que ingreses tus credenciales de AWS, que incluyen tu Access Key ID y Secret Access Key. Estas se pueden obtener desde la consola de administración de AWS en la sección de IAM. También se te pedirá que ingreses la región predeterminada (por ejemplo, us-west-2, us-east-1, etc.) y el formato de salida predeterminado (por ejemplo, json, text, etc.).

Validación.
```bash
aws s3 ls
```
Create an S3 bucket on your current region. Remember that name should be rame unique.
```bash
aws s3api create-bucket --bucket youtube-raw-data-json --region us-east-1 --create-bucket-configuration LocationConstraint=us-east-1
```




```bash
#

# Access
$ cd dataengineer

# Install dependencies
$ yarn

# Run the project
$ yarn start

# The server will initialize in the <http://localhost:3000>
```

## :memo: License ##

This project is under license from MIT. For more details, see the [LICENSE](LICENSE.md) file.


Made with :heart: by <a href="https://github.com/{{YOUR_GITHUB_USERNAME}}" target="_blank">{{YOUR_NAME}}</a>

&#xa0;

<a href="#top">Back to top</a>

