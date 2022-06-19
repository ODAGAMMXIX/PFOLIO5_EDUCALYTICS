## PORTFOLIO ACADÊMICO - PROJETOS INTEGRADORES:

[SEMESTRE-01-2019.2 - *Python-Sqlite3 Web Scrapper - Monitor de Segurança Pública*](https://github.com/ODAGAMMXIX/PFOLIO1_DANZO) 

[SEMESTRE-02-2020.1 - *Java-MySQL Stand Alone App - Gráfico de GANTT para Gestores*](https://github.com/ODAGAMMXIX/PFOLIO2_GANTT)

[SEMESTRE-03-2020.2 - *Java-Oracle - Cadastro Positivo e Desbancarizados*](https://github.com/ODAGAMMXIX/PFOLIO3_VALCODE)

[SEMESTRE-04-2021.1 - *Java-Oracle API - Recrutamento por Geolocalização et al.*](https://github.com/ODAGAMMXIX/PFOLIO4_JOBNATION)

## [SEMESTRE-05-2021.2 - *Java-Pentaho-My(SQL)Server-MongoDB - Engajamento Estudantil*](https://github.com/ODAGAMMXIX/PFOLIO5_EDUCALYTICS)

## [FRONTEND of *Java-Pentaho-My(SQL)Server-MongoDB - Engajamento Estudantil*](https://github.com/ODAGAMMXIX/PFOLIO5_EDUCALYTICS_FE)	

[SEMESTRE-06-2022.1 - *Python-MongoDB-LGPD Opt-in, Opt-out*](https://github.com/ODAGAMMXIX/PFOLIO6_OPTIN_OUT)

***
<h1 align="center">[Java-Pentaho-My(SQL)Server-MongoDB - Engajamento Estudantil.]</h1>

<h1 align="center">EDUCALYTICS</h1>
<h3 align="center">The Analytics of Education</h3>


# I - RESUMO DO PROJETO 

Plataforma com fulcro em Ciência de Dados, capaz de buscar e consumir de fontes externas *i.e.* aplicações legado (*in casu* "Skilllshare"), suprindo os tomadores de decisão de uma dada instituição de ensino com informações gerenciais.

Os dados são produzidos pelo uso regular de uma plataforma externa de e-learning. Assim, o histórico de uso, incluindo as iterações pelo *chat* e *logs* de sistema, tarefas, performance acadêmica dos alunos e satisfação dos usuários podem ser extraídos, compilados e apresentados aos nossos clientes.

Ao final, *Educalytics* deve ser capaz de demonstrar o comportamento dos usuários da aplicação legado e prover inteligência suficiente, suportando o processo de tomada de decisão.

Consequentemente, *Educalytics* apresenta uma interface gráfica, na forma de *dashboard* com os dados mais importantes sob o ponto de vista da instituição de ensino contratante.

A empresa Ionic Health figurou como cliente.

For DASHBOARD (FRONTEND), please acess: https://gitlab.com/rafaelEstevam/front-educalytics

<h3 align="center">Arquitetura da Aplicação</h3>

_____________---------------------------IMAGEM FINAL DO PROJETO-------------------------------___________________________

<details><summary> 1) THE ARCHITECTURE OF EDUCALYTICS</summary>
<p align="center">
<img src="https://user-images.githubusercontent.com/54047352/168504029-d49d6599-06c0-4d7a-85d3-4c29d906922e.png">
</p>
</details>

- [x]  2) FRONTEND;

<details><summary> 2.1) DASHBOARD (MVP);</summary>
<p align="center">
<img src="https://user-images.githubusercontent.com/54047352/168504109-64045972-2b34-4a19-8098-23b1017fd5d2.png">
</p>
</details>


<details><summary>2.2) LOGIN SCREEN (WITH CRIPTOGRAPHY "bcript");</summary>
<p align="center">
<img src="https://user-images.githubusercontent.com/54047352/168504140-08aff39b-4f2d-49c0-a49d-1c454a37ee0c.png">
</p>
</details>


<details><summary>2.3) REQUEST USING UNIQUE TOKEN;</summary>
<p align="center">
<img src="https://user-images.githubusercontent.com/54047352/168504168-bd12e7fb-992f-4036-8e62-f7797a2a6cff.gif">
</p>
</details>



<details><summary>2.4) CONTINUOUS INTEGRATION;</summary>
<p align="center">
<img src="https://user-images.githubusercontent.com/54047352/168504269-088503b3-c056-46c7-9210-a8fe22022a3e.png">
<img src="https://user-images.githubusercontent.com/54047352/168504270-cd16dc20-67ce-4372-a1b2-edd8d15c74ba.png">
<img src="https://user-images.githubusercontent.com/54047352/168504272-14f01caf-6960-4705-a29a-daad2befa23c.png">
<img src="https://user-images.githubusercontent.com/54047352/168504274-5d31bb4d-7ef9-4238-9155-1a54b39e6165.png">
<img src="https://user-images.githubusercontent.com/54047352/168504276-f55f9000-10ee-4064-a13e-f51375cc618f.png">
<img src="https://user-images.githubusercontent.com/54047352/168504291-48b713ab-52a8-4a10-bacb-acd19b7a8400.png">
<img src="https://user-images.githubusercontent.com/54047352/168504292-d70c2f47-5312-4d7c-8303-3391df2cf738.png">
</p>
</details>



<details><summary> 2.5) STUDENT PARTICIPATION RESULTS BEING SHOWED VIA GRAPHICS ON DASHBOARD;</summary>
<p align="center">
<img src="https://user-images.githubusercontent.com/54047352/168504337-9977c291-ba71-43ae-acfe-7be1f69f815d.png">
<img src="https://user-images.githubusercontent.com/54047352/168504342-edd33729-b1dc-43b6-b194-3bd6c75c35be.png">
<img src="https://user-images.githubusercontent.com/54047352/168504344-a157ed44-30b6-4775-9677-f645f4f2b04e.png">
</p>
</details>


<details><summary> 2.6) RESULTS ON EACH CLASS;</summary>
<p align="center">
<img src="https://user-images.githubusercontent.com/54047352/168504345-cb3a578b-208b-487b-80ca-7769bdc276da.png">
</p>
</details>
   
- [x] 3) BACKEND - THE 8 LAYERS (MPConConRVSC).

Model, 
Payload, 
Config, 
Converter, 
Repository, 
Validator, 
Services, 
Controller.

<details><summary> Camadas:</summary>
<p align="center">
<img src="https://user-images.githubusercontent.com/54047352/168504378-89855926-2958-452a-9e9d-e07bb78eef77.png">
<img src="https://user-images.githubusercontent.com/54047352/168504379-0c5e1a0b-0404-4217-b9c8-76860088de30.png">
</p>
</details>


<details><summary> 3.1) BACKEND - VALIDATION (user and password).</summary>
<p align="center">
<img src="https://user-images.githubusercontent.com/54047352/168504410-032731d7-b71d-4d74-be41-de70e200f4b2.gif">
</p>
</details>


<details><summary> 3.2) BACKEND - DATABASE ACCESS (MVP for Sprint 01 = concluded).</summary>
<p align="center">
<img src="https://user-images.githubusercontent.com/54047352/168504448-0fefada2-66d8-49b0-8266-72aa7c3f3f32.gif">
</p>
</details>


<details><summary> 3.3) BACKEND - ETL.</summary>
<p align="center">
<img src="https://user-images.githubusercontent.com/54047352/168504748-ecc214a6-0acc-4520-96a6-fa220f601d74.gif">
<img src="https://user-images.githubusercontent.com/54047352/168504752-be99f11e-4a7b-4ba3-a684-7291c38fc165.gif">
<img src="https://user-images.githubusercontent.com/54047352/168504755-9fc67cf3-4cda-4359-a61e-c3cffb08a72f.gif">
<img src="https://user-images.githubusercontent.com/54047352/168504764-5af45d97-ee54-4545-87da-5442af80e93c.gif">
</p>
</details>

<details><summary> 3.3.1) BACKEND - ETL TIME DIMENSION.</summary>
<p align="center">
<img src="https://user-images.githubusercontent.com/54047352/168504855-8765cf2a-f846-469c-addc-ffcd8f4f3c46.png">
<img src="https://user-images.githubusercontent.com/54047352/168504857-1fd56213-e9da-4976-bf31-410c9eaafd70.png">
</p>
</details>


<details><summary> 3.3.2) BACKEND - ETL COURSE DIMENSION ON THE LEGACY APPLICATION.</summary>
<p align="center">
<img src="https://user-images.githubusercontent.com/54047352/168505076-e4ffb3b1-4ffb-49b6-a1a0-f7bd87fe37c1.png">
<img src="https://user-images.githubusercontent.com/54047352/168505078-6ab613d8-0f63-4ba3-b72d-70405387e7d2.png">
<img src="https://user-images.githubusercontent.com/54047352/168505083-8f647cd3-de1e-4d3b-96e1-e072d42a33c9.png">
<img src="https://user-images.githubusercontent.com/54047352/168505120-bd3daed2-a668-4884-a103-a59f7f63066f.png">
<img src="https://user-images.githubusercontent.com/54047352/168505129-bffd498c-fa94-447b-8ddb-9a2660b9b014.png">
</p>
</details>


<details><summary> 3.3.3) BACKEND - ETL COURSE TO DATAMART ON THE PROGRAMME DIMENSION OF THE LEGACY APPLICATION.</summary>
<p align="center">
<img src="https://user-images.githubusercontent.com/54047352/168505213-bcd2dc2f-23f3-4993-9573-3db337397f4a.png">
<img src="https://user-images.githubusercontent.com/54047352/168505216-e3219e54-d9a3-4b18-9ae1-ee9fe7788390.png">
<img src="https://user-images.githubusercontent.com/54047352/168505217-99eb2d1e-2e8a-42fb-8c67-f1cb8cc38702.png">
<img src="https://user-images.githubusercontent.com/54047352/168505220-9fdce18d-368a-4cca-86f8-97acacabccfe.png">
<img src="https://user-images.githubusercontent.com/54047352/168505221-8a8881e0-f2f2-43df-8068-76a8ee0b5387.png">
<img src="https://user-images.githubusercontent.com/54047352/168505222-6080ccf5-9882-4c55-b3b7-18b9337c838e.png">
</p>
</details>

- [x] 4) EDUCALYTICS's DATABASE (RELATIONAL)


<details><summary> 4.1) LOGICAL MODEL</summary>
<p align="center">
<img src="https://user-images.githubusercontent.com/54047352/168505254-7cd2f65c-09a6-4670-bde2-c8db5038dc7b.png">
</p>
</details>



<details><summary> 4.2) ENTITY-RELATIONSHIP MODEL</summary>
<p align="center">
<img src="https://user-images.githubusercontent.com/54047352/168505257-9a438ab4-b4b1-40ca-aa47-8b4e1be06b2e.png">
</p>
</details>


<details><summary> 4.5) SKILLSHARE DATABASE MODEL</summary>
<p align="center">
<img src="https://user-images.githubusercontent.com/54047352/168505323-c5dfcd4c-419a-45ec-b42d-c7669732155f.png">
</p>
</details>


<details><summary> 4.6) DATAMART PERFORMANCE DATABASE MODEL</summary>
<p align="center">
<img src="https://user-images.githubusercontent.com/54047352/168505344-f64615c7-635d-4c7a-9af7-a3275cd22862.png">
<img src="https://user-images.githubusercontent.com/54047352/168505347-43a5d48f-388c-402a-8e94-db69049898e7.png">
</p>
</details>


<details><summary> 4.7) DATAMART PARTICIPATION ETL INTEGRATION</summary>
<p align="center">
<img src="https://user-images.githubusercontent.com/54047352/168505504-0083765d-d887-4f07-93af-9b98b7eb5ee1.png">
</p>
</details>


<details><summary> 4.8) DATAMART PARTICIPATION - EXTRACTING DATA FROM MONGO DB</summary>
<p align="center">
<img src="https://user-images.githubusercontent.com/54047352/168506159-7f8f8acc-5e9c-42a4-8da3-775602a89743.png">
</p>
</details>


<details><summary> 4.9) DATAMART PARTICIPATION - EXTRACTING FROM DIMENSION TO FACT</summary>
<p align="center">
<img src="https://user-images.githubusercontent.com/54047352/168506384-65dc2173-3af2-41a7-83da-e21f1d6d534b.png">
</p>
</details>


<details><summary> 5) DUPLO ETL (MONGODB + APPLICAÇÃO LEGADO)</summary>
<p align="center">
<img src="https://user-images.githubusercontent.com/54047352/168506605-078d9b67-53fd-4e17-974f-bcd6d99c9148.png">
</p>
</details>


<details><summary> 5.1) ESTRUTURA DA APLICAÇÃO LEGADO</summary>
<p align="center">
<img src="https://user-images.githubusercontent.com/54047352/168506764-7bcd1279-68ca-48af-bae7-7e007e9ab655.png">
</p>
</details>


<details><summary> 5.2) DATAMART "ENGAJAMENTO" - ETL DE BD NÃO-RELACIONAL</summary>
<p align="center">
<img src="https://user-images.githubusercontent.com/54047352/168506962-ed873842-0ac2-4f14-8d8f-0c6419741a2a.png">
</p>
</details>



<details><summary> 5.3)  ESTRUTURA DO MONGODB CLOUD (COLLECTIONS) - CHAT+LOGS DOS ALUNOS.</summary>
<p align="center">
<img src="https://user-images.githubusercontent.com/54047352/168507538-d7f3ba49-b2a4-4093-a94b-8c23e24154ce.png">
</p>
</details>


<details><summary> 5.3.1)  MONGODB "CONNECTIONS" COLLECTION PARA DATAMART "ENGAJAMENTO"</summary>
<p align="center">
<img src="https://user-images.githubusercontent.com/54047352/168507269-5f95f35a-220f-48ea-81c9-1e5d892b885e.png">
</p>
</details>


<details><summary> 5.4.2) MONGODB "MESSAGES" COLLECTION PARA DATAMART "ENGAJAMENTO"</summary>
<p align="center">
<img src="https://user-images.githubusercontent.com/54047352/168507273-69592d50-dd7c-4c1b-9665-0c21f1429383.png">
</p>
</details>


<details><summary> 5.2) NON-RELATIONAL DATABASE ETL</summary>
<p align="center">
<img src="https://i.ibb.co/wMrLpBB/ETL-BDNR.png">
</p>
</details>


<details><summary> 5.3) CASOS DE USO</summary>
<p align="center">
<img src="https://user-images.githubusercontent.com/54047352/168507568-1a68ff7b-7d01-4a11-abc7-9235c7c826e5.png">
</p>
</details>
   
# II - TECNOLOGIAS ADOTADAS NA SOLUÇÃO 

:wrench: **Banco de Dados 01** 

:wrench: **Banco de Dados 02**

:wrench: **Banco de Dados 03**

:wrench:  linguagem: ![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=java&logoColor=white)

:wrench:  ![Insomnia](https://img.shields.io/badge/Insomnia-black?style=for-the-badge&logo=insomnia&logoColor=5849BE)

:wrench: SQL DEVELOPER.

:wrench:  IDE: ![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white).

:wrench:  Metodologia *Scrum* e Ágil;

:wrench: OBS Studio / Kdenlive

# III - CONTRIBUIÇÕES INDIVIDUAS/PESSOAIS

:axe: Atuei como *Product Owner* e *Scrum Master*

:axe: Como P.O., compreendi imediatamente a necessidade e realizei comunicação veloz com a equipe para criar uma plataforma de visão gerencial, provendo inteligência do negócio e habilitado o pensamento analítico, com dashboards, histórico de chat e armazenamento desses dados históricos e escalabilidade.

:axe: Através da plataforma, tornou-se possível encontrar os alunos com melhores e piores:
   i. frequência nas aulas;
   ii. interação (chat, para sanar dúvidas e avaliação das aulas dadas).
   iii. plataforma funcional com capacidade analítica
   * Ativação: Quantos usuários ativos (aluno/colaboradores) na plataforma legado;
* Engajamento: Conhecer o número de usuários, tipos, seu comportamento (matrícula, curso, disciplina, participação);
* Desempenho: qual o aproveitamento do aluno(nota atingida) e do professor (andamento da turma);
* Participação x taxas de conclusão x desempenho dos alunos/colaboradores;
* Avaliação de reação: quanto ao conteúdo apresentado, experiência do aluno/colaborador durante o curso;
* Registro do tempo de participação no curso;
* Guardar logs e histórico das conversas do chat;


# IV - APRENDIZADOS EFETIVOS

:heavy_check_mark:

No FRONTEND - criptografia e token.
No BACKEND - arquitetura em oito camadas, com múltiplos BACKENDs, tanto para acessar o DATAWAREHOUSE e apresetar dados no DASHBOARD ou acessar o MONGODB pra acessar os dados de CHAT e LOGs;
No BANCO DE DADOS 01 (RELACIONAL) - Primeira versão com todos os dados necessários (será decomposto);
No BANCO DE DADOS 02 (NÃO-RELACIONAL) - Receberá tabelas do BD01, segundo critérios de performance;
CI (*Continuous Integration*): testes do BACKEND da aplicação;
Distribuição dos BD - Se necessária a clusterização / fragmentação;
No DATA WAREHOUSE - Um *Datamart* para cada a indicador métrico apresentado no *DASHBOARD*;
*DASHBOARD*: Emulação do PDI-PENTAHO, para a apresentação dos dados aos usuários de alta gerência;
Estudo profundo do PENTAHO, realizando ETL (Extraction, Transformation, Loading) de duas fontes: um banco de dados SQLServer da aplicação legado (contendo os dados de trabalho cotidiano dos alunos à platarforma de e-learning ) e do MongoDB (contendo dados de interação similiar á uma rede social, como chat e seus logs).


## Running it up
Deployment
No seu dispositivo
Vide Pasta "DEPLOYMENT-FIND-STEPS-HERE" acima)

## Ferramentas Tecnologicas
💻

![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=java&logoColor=white)
![IntelliJ IDEA](https://img.shields.io/badge/IntelliJIDEA-000000.svg?style=for-the-badge&logo=intellij-idea&logoColor=white)
![VS CODE](https://img.shields.io/badge/IntelliJIDEA-000000.svg?style=for-the-badge&logo=intellij-idea&logoColor=white)
![Eclipse](https://img.shields.io/badge/Eclipse-FE7A16.svg?style=for-the-badge&logo=Eclipse&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![MicrosoftSQLServer](https://img.shields.io/badge/Microsoft%20SQL%20Sever-CC2927?style=for-the-badge&logo=microsoft%20sql%20server&logoColor=white)
![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![Insomnia](https://img.shields.io/badge/Insomnia-black?style=for-the-badge&logo=insomnia&logoColor=5849BE)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![GitLab](https://img.shields.io/badge/gitlab-%23181717.svg?style=for-the-badge&logo=gitlab&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)
- Git Flow
- OBS Studio / Kdenlive

The End.
:arrow_up: 
[`Go Back Up`](#java-oracle-api---recrutamento-por-geolocaliza%C3%A7%C3%A3o-e-outros-crit%C3%A9rios).
