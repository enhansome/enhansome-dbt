<!--lint disable awesome-heading-->

# Awesome dbt with stars

[<img src="dbt-logo.png" align="right" width="200">](https://www.getdbt.com/)

Welcome to the awesome curated list of dbt resources!

Any kind of contribution is greatly encouraged and appreciated. For making a contribution, **please check the [contribution guidelines](https://github.com/Hiflylabs/awesome-dbt/blob/main/contributing.md) ⭐ 1,721 | 🐛 2 | 📅 2026-08-24 first!** **Add new entries on the top of sections** (LIFO) to keep fresh items more visible! Also, **feel free to add new sections**.

Happy contributing!

## Contents

* [Get Started](#get-started)
* [How To](#how-to)
* [Integrations](#integrations)
* [User Stories](#user-stories)
* [Data Quality](#data-quality)
* [CI/CD](#cicd)
* [Orchestration](#orchestration)
* [Utilities](#utilities)
* [Packages](#packages)
* [Snippets](#snippets)
* [Community](#community)
* [Sample Projects](#sample-projects)
* [Contributors](#contributors)

## Get Started

Courses from where you can get started with Analytics Engineering.

* [Accelerating and Scaling dbt for the Enterprise](https://www.phdata.io/blog/accelerating-and-scaling-dbt-for-the-enterprise/) - Guide for large scale dbt projects. .
* [The Ultimate Guide to dbt](https://count.co/canvas/JpkaYdqr9oN) - A comprehensive canvas guide to dbt, from the basics to advanced topics.
* [dbt in a real world scenario, A Beginner dbt tutorial](https://tipseason.com/dbt-tutorial-real-world-scenario-guide/) - A beginner tutorial to understand dbt with a real world example.
* [Mastering dbt: Beginner to Pro](https://www.udemy.com/course/mastering-dbt-data-build-tool-bootcamp/?referralCode=FFF494163B7B9E5E846F) - Paid Udemy course that covers theory, building a dbt project from scratch, and deploying to dbt Cloud.
* [Zero to Hero dbt](https://www.udemy.com/course/complete-dbt-data-build-tool-bootcamp-zero-to-hero-learn-dbt/) - Complete course covering both theory & practice through real-world Airbnb use-case.
* [Data Engineering Zoomcamp](https://github.com/DataTalksClub/data-engineering-zoomcamp) ⭐ 44,883 | 🐛 4 | 🌐 Jupyter Notebook | 📅 2026-08-20 - Data engineering course on cutting edge tools including dbt.
* [Analytics Engineering with dbt](https://uplimit.com/course/analytics-engineering-with-dbt) - Paid course offered by Uplimit covering the basics of dbt.
* [Advanced dbt](https://uplimit.com/course/advanced-dbt) - Another paid course by Uplimit covering the advanced dbt topics.
* [dbt Fundamentals](https://learn.getdbt.com/catalog) - Official free course offered by dbt. Excellent for learning the basics of dbt Cloud.
* [Refactoring SQL for Modularity](https://learn.getdbt.com/courses/refactoring-sql-for-modularity) - Another dbt labs offered free course on dbt refactoring and CTE supercharging.
* [Learn DBT from Scratch](https://www.udemy.com/course/learn-dbt-from-scratch/) - Guides you through a setup paired with Snowflake (decorated with extras).

## How To

Helping hand on setting up integrations and implementing best practices.

* [Automatically generate ERD](https://github.com/dbt-labs/docs.getdbt.com/discussions/1541) ⭐ 210 | 🐛 210 | 🌐 JavaScript | 📅 2026-08-24 - Automatically generate ERDs and display in your docs site.
* [Business Intelligence Standards](https://github.com/flexanalytics/dbt-business-intelligence) ⭐ 160 | 🐛 5 | 🌐 Python | 📅 2026-04-30 - Best practices in Business Intelligence standards for integrating with dbt.
* [Jinja cheatsheet](https://github.com/zsombor-flds/dbt-jinja-cheatsheet) ⭐ 42 | 🐛 1 | 📅 2022-07-25 - Jinja cheatsheet for dbt development.
* [Best Practices for Leveraging Amazon Redshift and dbt](https://d1.awsstatic.com/products/Redshift/Amazon-Redshift-dBT-Best-Practices_paper.pdf) - An overivew of best practices on how to integrate dbt with Redshift, that includes information about performance tunning and dbt code optimizations.
* [dbt Jinja Functions Cheat Sheet - Datacoves](https://datacoves.com/post/dbt-jinja-functions-cheat-sheet) - Jinja Functions Cheat Sheet that covers the Jinja additions in dbt Core.
* [Discovery API use-cases](https://docs.getdbt.com/docs/dbt-cloud-apis/discovery-use-cases-and-examples) - Use-cases and examples for the dbt Cloud Discovery API.
* [dbt Docs as a Static Website](https://medium.com/hiflylabs/dbt-docs-as-a-static-website-c50a5b306514) - How to deploy dbt docs as a static website with App Engine and GitHub Actions.
* [dbt Monorepo Workflow](https://www.loom.com/share/3b4f2d1d209444f1bff75bf4aac2fe1c) - How to get started with the team dbt workflow.
* [BigQuery Ingestion-Time Partitioning and Partition Copy With dbt](https://medium.com/teads-engineering/bigquery-ingestion-time-partitioning-and-partition-copy-with-dbt-cc8a00f373e3) - Combining ingestion-time partitioning and partition copy is a great way to achieve better performance for your models.
* [Power up your data quality with grouped checks](https://docs.getdbt.com/blog/grouping-data-tests) - How to use grouped checkes in dbt-utils to keep our data "on track".
* [Dry running our data warehouse using BigQuery and dbt](https://engineering.autotrader.co.uk/2022/04/06/dry-running-our-data-warehouse-using-bigquery-and-dbt.html) - Use dbt & BigQuery dry run jobs to validate our 1000+ models in under 30 seconds.
* [Test SQL Pipelines against Production Clones using DBT and Snowflake](https://medium.com/airtribe/test-sql-pipelines-against-production-clones-using-dbt-and-snowflake-2f8293722dd4) - Leverage Snowflake Zero-copy-clones to run slim ci checks.
* [How we structure our dbt projects](https://discourse.getdbt.com/t/how-we-used-to-structure-our-dbt-projects/355) - How the dbt team structures its dbt projects.
* [dbt guide](https://about.gitlab.com/handbook/business-technology/data-team/platform/dbt-guide/) - Primer on how you should properly set up and configure your dbt workflow.
* [dbt for Data Transformation – Hands-on](https://www.kdnuggets.com/2021/07/dbt-data-transformation-tutorial.html) - Yet another tutorial for using dbt Cloud.
* [Start Modeling Data](https://dataschool.com/sql-optimization/start-modeling-data/) - Configuring Bigquery with your dbt project.
* [Accelerating Data Teams with dbt & Snowflake](https://quickstarts.snowflake.com/guide/data_teams_with_dbt_cloud/?index=..%2F..index) - A dbt & Snowflake workshop on financial data.
* [Creating a dev environment quickly on Snowflake](https://discourse.getdbt.com/t/creating-a-dev-environment-quickly-on-snowflake/1151) - Setting up teh integraton with Snowflake.
* [How to set up a dbt data-ops workflow, using dbt cloud and Snowflake](https://www.startdataengineering.com/post/cicd-dbt/) - Leverage GitHub Actions to set up CI/CD with dbt Core.
* [How to configure your dbt repository](https://discourse.getdbt.com/t/how-to-configure-your-dbt-repository-one-or-many/2121) - Mono-repo or not mono-repo?
* [Best Practices for Optimizing Your dbt and Snowflake Deployment](https://resources.snowflake.com/white-paper/best-practices-for-optimizing-your-dbt-and-snowflake-deployment) - Pocket guide on optimization best practices with Snowflake.
* [How to Deploy dbt to Production using GitHub Actions](https://towardsdatascience.com/how-to-deploy-dbt-to-production-using-github-action-778bf6a1dff6)
* [Doing More With Less: Using DBT to load data from AWS S3 to Snowflake via External Tables](https://medium.com/slateco-blog/doing-more-with-less-usingdbt-to-load-data-from-aws-s3-to-snowflake-via-external-tables-a699d290b93f) - An alternative guide to set up your dbt-external-tables workflow.
* [Best Practices for your dbt Style Guide](https://airbyte.com/content-hub/blog/best-practices-dbt-style-guide) - Standards for well organized base layer with Airbyte ingestion.
* [Tips and Tricks about working with dbt](https://discourse.getdbt.com/t/tips-and-tricks-about-working-with-dbt/287) - Tips from community members.
* [Best Practices for your dbt Style Guide](https://airbyte.com/blog/best-practices-dbt-style-guide?utm_content=bufferd2cd7\&utm_medium=social\&utm_source=linkedin.com\&utm_campaign=buffer) - Standards for well organized base layer with Airbyte ingestion.
* [Writing Unit Tests for dbt](https://www.equalexperts.com/blog/our-thinking/writing-unit-tests-for-dbt-with-tdd/) - An overview about the package dbt-unit-testing.
* [How to create Kimball dimensional models with dbt](https://docs.getdbt.com/blog/kimball-dimensional-model) - A step by step guide on how to build Kimball dimensional models with dbt.

## Integrations

Collection of known data integrations with dbt

* [Lightdash](https://github.com/lightdash/lightdash) ⭐ 6,075 | 🐛 1,199 | 🌐 TypeScript | 📅 2026-08-24 - Open source Looker alternative with deep dbt integration.
* [ingestr](https://github.com/bruin-data/ingestr) ⭐ 3,859 | 🐛 18 | 🌐 Go | 📅 2026-08-21 - CLI tool to copy data from any source to any destination with a single command. Load data into your warehouse before dbt transforms it. Supports 50+ sources including Postgres, MongoDB, Salesforce, Shopify.
* [fal](https://github.com/fal-ai/fal) ⭐ 947 | 🐛 68 | 🌐 Python | 📅 2026-08-24 - Add multi-language support (Python) to your dbt project.
* [dbt-agent-skills](https://github.com/dbt-labs/dbt-agent-skills/tree/main) ⭐ 685 | 🐛 39 | 🌐 Python | 📅 2026-08-21 - A curated collection of agent skills, built and maintained by dbt Labs, to help AI coding agents work more effectively with dbt.
* [dbt MCP Server](https://github.com/dbt-labs/dbt-mcp/tree/main) ⭐ 598 | 🐛 38 | 🌐 Python | 📅 2026-08-21 - MCP tools to interact with dbt.
* [prefect-dbt](https://github.com/PrefectHQ/prefect-dbt) ⚠️ Archived - Collection of Prefect integrations for working with dbt with your Prefect flows.
* [dbt-cli-mcp](https://github.com/MammothGrowth/dbt-cli-mcp) ⭐ 18 | 🐛 4 | 🌐 Python | 📅 2025-06-26 - MCP for dbt CLI.
* [modal-dbt](https://github.com/trouze/modal-dbt) ⭐ 11 | 🐛 0 | 🌐 Python | 📅 2023-09-07 - This repo gives some code to run dbt jobs/actions using modal which is a serverless application framework.
* [dbt-streamdeck](https://github.com/nicholasyager/dbt-streamdeck) ⭐ 6 | 🐛 1 | 🌐 JavaScript | 📅 2024-02-09 - Stream Deck plugin enables you to view the status of models and jobs as actions in your Stream Deck.
* [Raycast dbt Metadata](https://github.com/b-per/raycast-dbt-cloud-metadata) ⭐ 3 | 🐛 2 | 🌐 TypeScript | 📅 2022-10-26 - Queries the dbt Cloud API to return some useful information about your models (number of tests, time they took to run etc…).
* [Bonnard](https://bonnard.dev) - Governed, multi-tenant MCP access to customer data. Turn your dbt models into a secure, per-customer MCP for AI agents.
* [Auto Alert - diqu](https://diqu.iflambda.com/latest/) - Automate and streamline the alerting/ notification process for dbt test results using this versatile CLI companion tool. Receive detailed alerts & test metadata seamlessly on various platforms, promoting improved collaboration on dbt project issues 🐞🚀.
* [Tabula](https://docs.tabula.io/) - Tabula is an end-to-end automation platform for data management tasks.
* [Grai](https://docs.grai.io/integrations/etl/dbt) - Expose warehouse dbt tests in CI to upstream data consumers so production changes never break the warehouse.
* [Datafold](https://docs.datafold.com/data-diff/what-is-data-diff) - Gives a quick print out summary of changes so you can move fast and (not) break stuff!
* [Cube](https://cube.dev/blog/dbt-metrics-meet-cube?ref=awesome-dbt) - APIs, Caching, and Access Control on top of dbt Metrics.
* [FlexIt Analytics](https://learn.flexitanalytics.com/docs/dbt/) - Business Intelligence platform with deep dbt Cloud and CLI integration.
* [Raycast dbt Jobs](https://www.raycast.com/zsombor-flds/dbtcloud) - Raycast integration to monitor dbt Cloud Jobs.
* [Metaplane](https://www.metaplane.dev/) - Data Observaibility layer on top of your dbt + BI project.
* [Dbt + Machine Learning: What makes a great baton pass?](https://docs.getdbt.com/blog/maching-learning-dbt-baton-pass) - Landscape of ML utilities around dbt.
* [Soda](https://docs.soda.io/soda/integrate-dbt.html) - Integration of Soda's data observability platform and dbt.
* [Supported Adapters](https://docs.getdbt.com/docs/supported-data-platforms) - Offically supported database adapters.
* [Superset](https://superset.apache.org/) - Open source visualization layer for your Modern Data Stack.
* [Dagster and dbt: Better Together](https://dagster.io/blog/dagster-dbt) - Getting started with the dagster-dbt library.
* [Privacy Dynamics](https://www.privacydynamics.io) - Anonymize data in your dbt project.
* [Acryl DataHub](https://datahubproject.io/docs/generated/ingestion/sources/dbt/) - A unified data catalog, governance, and observability platform. Use it to view models, docs, test results, and column-level lineage across your dbt projects and downstream dashboards.

## User Stories

Use-cases and user stories implemented by the community members using components of the MDS with dbt.

* [Speeding up the dbt™ docs by 20x with React Server Components](https://dagster.io/blog/dbt-docs-on-react) - A rewrite of dbt docs using Next.js with React Server Components and SSG.
* [How HomeToGo connected dbt and Superset to make metadata more accessible and reduce analytical overhead](https://medium.com/m/global-identity-2?redirectUrl=https%3A%2F%2Fengineering.hometogo.com%2Fhow-hometogo-connected-dbt-and-superset-to-make-metadata-more-accessible-and-reduce-analytical-2223af539cc6) - A dbt<>Superset connector that leverages Superset's API capabilities and dbt's manifest.
* [Self-service Business Intelligence](https://medium.com/modern-business-intelligence/self-service-business-intelligence-powered-by-dbt-3b7e24a92e27) - Eliminate the need for a data modeling semantic layer in BI.
* ["Semantic-free" is the future of Business Intelligence](https://towardsdatascience.com/semantic-free-is-the-future-of-business-intelligence-27aae1d11563) - How to leverage dbt as a data catalog and semantic layer (joins, synonyms, etc.) that BI tools can just plug into.
* [Building an extension framework for dbt](https://medium.com/data-monzo/building-an-extension-framework-for-dbt-654ca99495da) - How Monzo built an extension framework for dbt.
* [Why I moved my dbt workloads to GitHub and saved over $65,000](https://medium.com/@datajuls/why-i-moved-my-dbt-workloads-to-github-and-saved-over-65-000-759b37486001) - Save by replacing dbt Cloud with GitHub Actions.
* [“Is This You?” Entity Matching in the Modern Data Stack with Large Language models](https://towardsdatascience.com/is-this-you-entity-matching-in-the-modern-data-stack-with-large-language-models-19a730373b26) - An experiment in productionizing LLMs.
* [How HomeToGo connected dbt and Superset to make metadata more accessible and reduce analytical overhead](https://engineering.hometogo.com/how-hometogo-connected-dbt-and-superset-to-make-metadata-more-accessible-and-reduce-analytical-2223af539cc6) - A dbt<>Superset connector that leverages Superset's API capabilities and dbt's manifest.
* [Self-service Business Intelligence](https://medium.com/p/3b7e24a92e27) - Eliminate the need for a data modeling semantic layer in BI.
* [Leveraging DBT as a Data Modeling tool](https://medium.com/analytics-and-data/leveraging-dbt-as-a-data-modeling-tool-b3caf78f4a3a) - Reflection on one-year usage of dbt.
* [dbt + Materialize: Streaming to a dbt project near you](https://www.getdbt.com/blog/dbt-materialize-streaming-to-a-dbt-project-near-you) - How to own your real-time transformation workflows like batch-based alternatives.
* [Who's really using dbt?](https://semistructured.substack.com/p/dbt-analytics-engineering-or-data-engineering) - Behind the community of analytics engineers.
* [dbt and the Analytics Engineer — what's the hype about](https://medium.com/validio/dbt-and-the-analytics-engineer-whats-the-hype-about-907eb86c4938) - Behind the upheaval of the analytics engineer profession.
* [Analyzing Fishtown's dbt project performance with artifacts](https://discourse.getdbt.com/t/analyzing-fishtowns-dbt-project-performance-with-artifacts/2214) - Using project artifacts to identify anomalies and room for refactoring.
* [Deploying and Running dbt on Azure Container Instances](https://medium.com/hashmapinc/deploying-and-running-dbt-on-azure-container-instances-f6136f8ea74c) - Demonstration of integration with Azure.
* [Beware of DBT Incremental Updates Against Snowflake External Tables](https://dm03514.medium.com/beware-of-dbt-incremental-updates-against-snowflake-external-tables-beeda513e748) - Things you should be aware of when using external tables with dbt.
* [dbt development at Vimeo](https://medium.com/vimeo-engineering-blog/dbt-development-at-vimeo-fe1ad9eb212) - Best practises from the Vimeo Data team.

## Data Quality

Best-practices and extensions of the testing framework.

* [Elementary](https://github.com/elementary-data/elementary) ⭐ 2,397 | 🐛 26 | 🌐 HTML | 📅 2026-08-24 - A dbt package that provides data anomaly detection as dbt tests.
* [dbt-expectations](https://github.com/calogica/dbt-expectations) ⭐ 1,233 | 🐛 37 | 🌐 Shell | 📅 2024-12-16 - Port between dbt and great\_expectations to extend out-of-the-box tests.
* [DataKitchen Open Source Data Observability](https://github.com/DataKitchen/data-observability-installer) ⭐ 141 | 🐛 6 | 🌐 Python | 📅 2026-07-23 - Data breaks. Servers break. dbt and other tools break. Observability and alerting across and down your data estate. Save time with simple, fast data quality test generation and execution.
* [Misata](https://github.com/rasinmuhammed/misata) ⭐ 68 | 🐛 0 | 🌐 Python | 📅 2026-08-24 - Generate known-answer seed and test data for dbt models: declare the expected aggregates (revenue curves, rates, rollups) and assert your models return them exactly.
* [dq-tools](https://github.com/infinitelambda/dq-tools) ⭐ 56 | 🐛 1 | 🌐 PLpgSQL | 📅 2026-08-21 - Make simple storing test results and visualisation of these in a BI dashboard leveraging 6 Data Quality KPIs.
* [Scherlok](https://github.com/rbmuller/scherlok) ⭐ 9 | 🐛 9 | 🌐 Python | 📅 2026-08-20 - Zero-config data quality CLI that complements `dbt test` with auto-detected anomalies (volume, schema drift, freshness, distribution, cardinality) on every materialized model after `dbt run`.
* [data-contract-validator](https://github.com/OGsiji/data-contract-validator) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2026-08-15 - Fails the pull request when a model stops producing what a downstream consumer expects. Reads columns from `catalog.json`/`manifest.json` (falling back to a sqlglot parse of the SQL) and compares them against reverse-ETL destinations such as HubSpot CRM and against FastAPI/Pydantic services, in CI or pre-commit.
* [Aegis DQ](https://github.com/aegis-dq/aegis-dq) ⭐ 4 | 🐛 10 | 🌐 Python | 📅 2026-05-27 - Agentic data quality framework that runs YAML rules against your warehouse (DuckDB, BigQuery, Snowflake, Databricks, Athena, Postgres), then uses LLMs to diagnose failures, trace root causes, and propose SQL fixes. Pairs naturally with dbt models as the validation layer after `dbt run`.
* [BigQuery Stale data detection](https://eponkratova.medium.com/stale-data-detection-with-dbt-and-bigquery-dataset-metadata-662196cf9370) - Stale data detection with dbt and BigQuery dataset metadata.
* [Environment-dependent Unit Testing in dbt](https://medium.com/hiflylabs/environment-dependent-unit-testing-in-dbt-c081a0a5ff1e) - Guide on how to run unit tests in dbt dynamically.
* [re\_data](https://www.getre.io/) - A dbt package for montioring metrics and detect anomalies.
* [How do you test your data](https://discourse.getdbt.com/t/how-do-you-test-your-data/149) - Suggestions on testing your data powered by the community.
* [How to unit test sql transforms in dbt](https://www.startdataengineering.com/post/how-to-test-sql-using-dbt/) - Unit test using source defer and generic custom tests.

## CI/CD

Make the best out of your product quality and seamless delivery.

* [dbt-ci-cd](https://github.com/bruno-szdl/dbt-ci-cd) ⭐ 188 | 🐛 3 | 📅 2025-08-24 - This setup is designed to demonstrate and implement best practices for testing and deploying dbt models.
* [dbt-beyond-the-basics](https://github.com/pgoslatara/dbt-beyond-the-basics) ⭐ 105 | 🐛 2 | 🌐 Python | 📅 2026-08-17 - Showcase of advanced options when running CI for dbt.
* [dbt-cloud-download-artifacts-action](https://github.com/pgoslatara/dbt-cloud-download-artifacts-action) ⭐ 2 | 🐛 3 | 🌐 Python | 📅 2025-12-12 - A GitHub action for downloading dbt artifacts from dbt Cloud CI jobs.
* [How to Create CI/CD Pipelines for dbt Core](https://paulfry999.medium.com/v0-4-pre-chatgpt-how-to-create-ci-cd-pipelines-for-dbt-core-88e68ab506dd) - This post dives into the use of CI/CD for dbt Core, providing insights on dbt Cloud's Slim CI CICD job pattern and how to implement this using dbt Core.
* [Slim CI/CD with Bitbucket Pipelines](https://docs.getdbt.com/blog/slim-ci-cd-with-bitbucket-pipelines) - How to setup slim CI on Bitbucket.
* [dbt-docs-to-notion](https://github.com/marketplace/actions/dbt-docs-to-notion) - A GitHub action for exporting dbt model docs to a Notion database.
* [How to review an analytics pull request](https://www.getdbt.com/blog/how-to-review-an-analytics-pull-request) - Checkpoints to consider when reviewing an analytics engineer PR.
* [Continuous Integration and Automated Build Testing with dbtCloud](https://blog.rittmananalytics.com/continuous-integration-and-automated-analytics-test-pipelines-using-dbt-and-dbtcloud-c4517f40b874) - Great and detailed blogpost on setting up Slim CI in dbt Cloud.
* [Performing a blue/green deploy of your dbt project on Snowflake](https://discourse.getdbt.com/t/performing-a-blue-green-deploy-of-your-dbt-project-on-snowflake/1349) - A very tidy and fail-safe way to run dbt in production by using two parallel production enviromnents.
* [How we speed up our CI runs by 10x using Slim CI](https://discourse.getdbt.com/t/how-we-sped-up-our-ci-runs-by-10x-using-slim-ci/2603) - Limit data in long-running CI checks to improve developing experience.
* [DBT CI/CD Demo with BigQuery and GitHub Actions](https://jaehyeon.me/blog/2024-09-05-dbt-cicd-demo/) - A demo CI/CD implementation using GitHub Actions, including [slim CI](https://docs.getdbt.com/reference/node-selection/defer) and [unit tests](https://docs.getdbt.com/docs/build/unit-tests).
* [Guide to Running DBT in Production](https://jaehyeon.me/blog/2024-09-13-dbt-guide/) - A guide to implementing a complete CI/CD process for a *dbt* project. The **defer** feature (for slim CI) and **unit tests** are used for continous integration (CI). For continuous delivery (CD), automatic deployment is advised in lower environments, and the [Write-Audit-Publish](https://lakefs.io/blog/data-engineering-patterns-write-audit-publish/) pattern using the **dbt clone** feature is introduced for higher environments.

## Orchestration

Resources to manage and maintain dependencies in modern data pipelines.

* [Bruin](https://github.com/bruin-data/bruin) ⭐ 1,674 | 🐛 33 | 🌐 Go | 📅 2026-08-24 - Run and schedule dbt-style SQL transformations without Airflow. Adds data ingestion (50+ sources) and built-in data quality to the transformation layer. Open-source CLI or managed [Bruin Cloud](https://getbruin.com) for teams who want dbt Cloud-like experience with ingestion included.
* [Orchestrate dbt Core jobs with Airflow and Cosmos](https://docs.astronomer.io/learn/airflow-dbt) - Run your dbt Core projects as Apache Airflow DAGs and Task Groups.
* [Building a Scalable Analytics Architecture with Airflow and dbt](https://www.astronomer.io/blog/airflow-dbt-1/) - Leveraging the dbt manifest in Airflow.
* [Auto-generating an Airflow DAG using the dbt manifest](https://engineering.autotrader.co.uk/2021/09/15/auto-generated-airflow-dag-for-dbt.html) - Yet another article on extracting value from the manifest file.
* [Building a robust data pipeline with the dAG stack: dbt, Airflow, Great Expectations](https://airflowsummit.org/sessions/2021/building-a-robust-data-pipeline-with-the-dag-stack/) - Demonstration of a data orchestration project with Airflow.
* [Run dbt in Azure Data Factory](https://medium.com/@guangx/run-dbt-in-azure-data-factory-a-clean-solution-for-azure-cloud-edddf0c85849) - Primer about dbt on Azure Data Stack.
* [ModelDock](https://modeldock.run) - Hosted dbt-core scheduler. Connect your repo, pick dbt-core and adapter version, set a cron, run dbt-core in isolated Docker containers. No Airflow to manage.
*

## Utilities

Useful tools and extensions to bump up your analytics engineer workflow.

* [SQLFluff](https://github.com/sqlfluff/sqlfluff) ⭐ 9,861 | 🐛 334 | 🌐 Python | 📅 2026-08-22 - SQL linter that supports dbt and Jinja templating.
* [Altimate Code](https://github.com/AltimateAI/altimate-code) ⭐ 795 | 🐛 241 | 🌐 TypeScript | 📅 2026-08-24 - Open-source data engineering harness with 100+ deterministic tools for building, validating, optimizing, and shipping data products — usable from any LLM, across your warehouses. Ranked #1 on ADE-Bench (78%).
* [Pre-commit hooks](https://github.com/dbt-checkpoint/dbt-checkpoint) ⭐ 762 | 🐛 65 | 🌐 Python | 📅 2026-08-17 - Pre-commit hooks for checking data integity before schema change commit.
* [dbt-osmosis](https://github.com/z3z1ma/dbt-osmosis) ⭐ 639 | 🐛 14 | 🌐 Python | 📅 2026-08-15 - Enhance the developer experience significantly with workbench, output diffs, and YAML management.
* [vscode-dbt-power-user](https://github.com/innoverio/vscode-dbt-power-user) ⭐ 583 | 🐛 158 | 🌐 JavaScript | 📅 2026-08-17 - VSCode extension to give more clarity on model dependencies.
* [sqlfmt](https://github.com/tconbeer/sqlfmt) ⭐ 546 | 🐛 38 | 🌐 Python | 📅 2026-08-24 - This tool formats your dbt SQL code so you don't have to.
* [dbt-tips](https://github.com/erika-e/dbt-tips) ⭐ 404 | 🐛 2 | 📅 2022-10-12 - Excellent companion to your dbt practice with rich collection of tips.
* [dbterd](https://github.com/datnguye/dbterd) ⭐ 345 | 🐛 2 | 🌐 Python | 📅 2026-08-24 - CLI to generate DBML file from dbt manifest.json.
* [dbt-score](https://github.com/PicnicSupermarket/dbt-score) ⭐ 246 | 🐛 16 | 🌐 Python | 📅 2026-08-05 - Linter for dbt metadata.
* [dbt-loom](https://github.com/nicholasyager/dbt-loom) ⭐ 221 | 🐛 25 | 🌐 Python | 📅 2026-06-25 - A dbt-core plugin to weave together multi-project dbt-core deployments.
* [dbt-column-lineage-extractor](https://github.com/canva-public/dbt-column-lineage-extractor) ⭐ 209 | 🐛 4 | 🌐 Python | 📅 2025-03-28 - Extract column level linage from dbt projects.
* [dbt-llm-tools](https://github.com/pragunbhutani/dbt-llm-tools) ⭐ 179 | 🐛 4 | 🌐 Python | 📅 2026-04-01 - RAG based LLM chatbot for dbt projects.
* [dbtpal](https://github.com/PedramNavid/dbtpal) ⭐ 138 | 🐛 10 | 🌐 Lua | 📅 2025-06-19 - A Neovim plugin for dbt model editing.
* [dbt-meshify](https://github.com/dbt-labs/dbt-meshify) ⚠️ Archived - A dbt-core plugin that automates the management and creation of dbt groups, contracts, access, and versions.
* [dbt-bouncer](https://github.com/godatadriven/dbt-bouncer) ⭐ 127 | 🐛 6 | 🌐 Python | 📅 2026-08-24 - Tool to configure and enforce conventions for your dbt project.
* [dbt-ui](https://github.com/data-diving/dbt-ui) ⭐ 124 | 🐛 2 | 🌐 TypeScript | 📅 2026-02-01 - A modern web-based user interface for dbt-core projects
* [dbt-artifacts-parser](https://github.com/yu-iskw/dbt-artifacts-parser) ⭐ 115 | 🐛 6 | 🌐 Python | 📅 2026-08-20 -  It enables us to deal with catalog.json, manifest.json, run-results.json and sources.json as python objects.
* [fzf-dbt](https://github.com/Infused-Insight/fzf-dbt) ⭐ 74 | 🐛 2 | 🌐 Shell | 📅 2023-07-26 - Search dbt models interactively from terminal.
* [dbt-Workbench](https://github.com/rezer-bleede/dbt-Workbench) ⭐ 71 | 🐛 0 | 🌐 Python | 📅 2026-05-30 - An open UI for dbt providing model browsing, lineage visualization, run orchestration, documentation, environment management — without vendor lock-in. Designed for local, on‑prem, and air‑gapped deployments.
* [dbt-exposures-crawler](https://github.com/voi-oss/dbt-exposures-crawler) ⭐ 64 | 🐛 3 | 🌐 Python | 📅 2024-01-25 - Automate the creation of dbt exposures from different sources.
* [pytest-dbt-core](https://github.com/godatadriven/pytest-dbt-core) ⭐ 63 | 🐛 8 | 🌐 Python | 📅 2026-07-06 - Pytest dbt core is a pytest plugin for testing your dbt projects.
* [dbt-sql-formatter](https://github.com/dbt-labs/dbt-sql-formatter) ⚠️ Archived - Makes your sql less bad.
* [dbt-container-skeleton](https://github.com/gnilrets/dbt-container-skeleton) ⭐ 58 | 🐛 1 | 🌐 Python | 📅 2022-06-02 - All the basics to get a nice containerized dbt development environment.
* [cookiecutter-dbt](https://github.com/datacoves/cookiecutter-dbt) ⭐ 50 | 🐛 3 | 🌐 Python | 📅 2023-08-08 - Cookiecutter template for dbt projects.
* [turbovault4dbt](https://github.com/ScalefreeCOM/turbovault4dbt) ⭐ 50 | 🐛 16 | 🌐 Python | 📅 2026-07-31 - TurboVault4dbt is an open source tool that automatically generates dbt models according to datavault4dbt-templates.
* [dbtective](https://github.com/feliblo/dbtective) ⭐ 43 | 🐛 2 | 🌐 Rust | 📅 2026-08-17 Rust-powered 'detective'/linter for dbt project/metadata best practices
* [datapilot](https://github.com/AltimateAI/datapilot) ⭐ 43 | 🐛 8 | 🌐 Python | 📅 2026-08-20 - AI teammate for engineers to ensure best practices in their SQL.
* [dbtc](https://github.com/dpguthrie/dbtc) ⭐ 41 | 🐛 4 | 🌐 Python | 📅 2025-05-08 - Unaffiliated python interface to various dbt Cloud API endpoints.
* [dbt-lineagex](https://github.com/sfu-db/dbt-lineagex) ⭐ 40 | 🐛 2 | 🌐 Python | 📅 2024-04-25 - A Column Level Lineage Graph for dbt.
* [oliver-twist](https://github.com/autotraderuk/oliver-twist) ⭐ 40 | 🐛 16 | 🌐 Python | 📅 2021-11-02 - DAG auditing tool that audits the DBT DAG and generates a summary report.
* [dbot](https://github.com/dbt-labs/dbot) ⚠️ Archived - An LLM-powered chatbot with the added context of the dbt knowledge base.
* [dbt-feature-flags](https://github.com/z3z1ma/dbt-feature-flags) ⭐ 35 | 🐛 0 | 🌐 Python | 📅 2026-07-05 - Feature Flags in dbt models.
* [fst: flow state tool](https://github.com/sungchun12/fst) ⭐ 34 | 🐛 15 | 🌐 Python | 📅 2023-06-13 - A tool to help you stay in flow state while developing dbt models.
* [dbt-toolkit](https://github.com/ramonvermeulen/dbt-toolkit) ⚠️ Archived - Jetbrains IDE plugin for dbt lineage and more.
* [tdb](https://github.com/gwenwindflower/tbd) ⚠️ Archived - A sweet and speedy code generator for dbt.
* [dbt-command-center](https://github.com/montara-io/dbt-command-center) ⭐ 31 | 🐛 9 | 🌐 TypeScript | 📅 2025-04-20 - A local web application that provides a user-friendly interface to monitor and manage dbt runs.
* [dbtenv](https://github.com/brooklyn-data/dbtenv) ⭐ 31 | 🐛 4 | 🌐 Python | 📅 2022-10-27 - A version manager for dbt.
* [metaplane cli](https://github.com/metaplane/cli) ⭐ 27 | 🐛 1 | 🌐 TypeScript | 📅 2025-02-14 - Various tools for working with data stacks.
* [Build Data Access Layer on dbt](https://github.com/coterahq/dal) ⭐ 27 | 🐛 0 | 🌐 Go | 📅 2022-04-11 - Package to build GraphQL API on top of your dbt project.
* [looker-gen](https://github.com/aaronbannin/looker-gen) ⭐ 23 | 🐛 0 | 🌐 Python | 📅 2022-10-19 - Generate lookml from dbt.
* [dbt-doctor](https://github.com/joachimhodana/dbt-doctor) ⭐ 22 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-14 - CLI health check and linter for dbt projects (SQL, YAML, Jinja): 190+ custom rules, optional SQLFluff, 0–100 score, GitHub Actions CI, and coding-agent skills.
* [dbtvault-generator](https://github.com/Oracen/dbtvault-generator) ⭐ 20 | 🐛 2 | 🌐 Python | 📅 2023-07-27 - Generate DBT Vault files from yml metadata (supporting `dbtvault` package).
* [GitHub Action: Cancel Running CI Job](https://github.com/Stevedow99/dbt-cloud-cancel-running-ci-job-action) ⭐ 15 | 🐛 1 | 🌐 Python | 📅 2024-09-23 -  This allows to always have the newest code commit running in the CI job without having to wait for the stale job runs to finish.
* [dlin](https://github.com/eitsupi/dlin) ⭐ 13 | 🐛 1 | 🌐 Rust | 📅 2026-08-24 - Gives coding agents instant dbt lineage: no dbt compile, no Python, no grep. Fast model-level lineage CLI parsing SQL files directly (or a `manifest.json`), with experimental column-level lineage too.
* [turboYAML](https://github.com/fredbrowne/turboYAML) ⭐ 12 | 🐛 1 | 🌐 Python | 📅 2024-03-25 - An AI-powered CLI tool for converting dbt SQL files to YAML using OpenAI.
* [dbt-cue](https://github.com/gilcrest/dbt-cue) ⭐ 11 | 🐛 0 | 🌐 CUE | 📅 2024-02-14 - Generate dbt yml files using the CUE language.
* [metadv](https://github.com/data-diving/metadv) ⭐ 6 | 🐛 2 | 🌐 Python | 📅 2026-01-24 - Python library for generating models from a declarative YAML configuration. It supports multiple data modeling approaches including Data Vault 2.0, Anchor Modeling, and Dimensional Modeling, with template packages for popular dbt libraries.
* [ERD Studio](https://github.com/liam-machine/erd-studio) ⭐ 5 | 🐛 0 | 🌐 TypeScript | 📅 2026-06-10 - VS Code extension that puts a visual ERD designer inside your dbt repo. Two-stage (logical/physical) canvas, drift detection against `manifest.json`, auto-generated `selectors.yml`, and AI-readable semantic models (YAML/JSON) with a built-in harness for Claude, Copilot, Gemini, and Codex.
* [docbt](https://github.com/aleenprd/docbt) ⭐ 4 | 🐛 6 | 🌐 Python | 📅 2025-12-13 - Documentation Build Tool - Generate YAML documentation for dbt models with optional AI assistance. Built with Streamlit for an intuitive and familiar web interface.
* [dbt\_tld](https://github.com/GJMcClintock/dbt_tld) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2026-02-15 - A self-updating dbt library that will maintain a list of current IANA/ICANN recognized top level domains.
* [sqllens](https://github.com/NiclasOlofsson/sqllens) ⭐ 2 | 🐛 10 | 🌐 TypeScript | 📅 2026-07-26 - TypeScript SQL parser and static analyzer: type inference, schema diagnostics, and column-level lineage. Reads Jinja-templated SQL (dbt models) natively, without rendering.
* [dbt-column-lineage](https://github.com/Oisix/dbt-column-lineage) ⭐ 1 | 🐛 1 | 🌐 TypeScript | 📅 2026-08-19 - Tool to visualize the column level lineage of dbt models.
* [dbt-colibri](\[https://github.com/godatadriven/dbt-bouncer]\(https://github.com/b-ned/dbt-colibri\)) - Self hostable column-level lineage for dbt core projects.
* [diff2docs](https://diff2docs.replit.app/) - Turn your diff into docs with the help of GPT-4o.
* [dlt(data load tool)](https://dlthub.com/) - The open-source Python library for data loading.
* [Turntable VSCode extension](https://www.turntable.so/extension) - A handy docs composer and column-level lineage.
* [Jinjat](https://jinjat.com/) - Low-code application framework that turns your dbt projects into web apps.
* [dbt-model-finder](https://dbt-model-finder.streamlit.app/) - A Streamlit web app to find currently running dbt models.
* [dbtc Explorer](https://dpguthrie-dbtc-streamlit-home-yy7c0b.streamlit.app/Admin_API) - A Streamlit web app to explore the dbt Cloud API.
* [drift](https://github.com/f4rkh4d/drift) - Multi-dialect SQL linter and formatter in Rust. Postgres, MySQL, SQLite, BigQuery, Snowflake. Single binary, \~448x faster than SQLFluff on plain SQL, with SARIF output for GitHub code scanning and a baseline mode for legacy adoption.
* [Run changed models based on Git status](https://discourse.getdbt.com/t/tips-and-tricks-about-working-with-dbt/287/2) - Handy bash function to run changed models since last commit.
* [How we set up our computers for working on dbt projects](https://discourse.getdbt.com/t/how-we-set-up-our-computers-for-working-on-dbt-projects/243) - Things I wish I would have known when started working with dbt. Tools and hacks to improve developing experience.
* [Your Essential dbt Project Checklist](https://discourse.getdbt.com/t/your-dbt-project-checklist/1377) - Checklist on items necessary for a successful dbt project.
* [dbt Style Guide](https://github.com/dbt-labs/corp/blob/main/dbt_style_guide.md) - Developing styleguide often referred in PR templates.
* [Clean your warehouse of old and deprecated models](https://discourse.getdbt.com/t/clean-your-warehouse-of-old-and-deprecated-models/1547) - Clean out warehouse models which are not existent in the project.
* [Understanding the scopes of dbt tags](https://yu-ishikawa.medium.com/understanding-the-scopes-of-dbt-tags-691d0286f3aa) - Understanding the scopes of dbt tags.
* [Lunapad](https://lunapad.dev/) - Open-source notebook for running, exploring, and debugging dbt projects with interactive data analysis.

## Packages

Community-developed packages to extend default macros and toolset.

* [data-diff](https://github.com/datafold/data-diff) ⚠️ Archived - A command-line tool and Python library to efficiently diff rows across two different databases.
* [dbt-codegen](https://github.com/dbt-labs/dbt-codegen) ⭐ 670 | 🐛 24 | 🌐 Makefile | 📅 2026-07-28 - Macros that generate dbt code, and log it to the command line.
* [dbt-metabase](https://github.com/gouline/dbt-metabase) ⭐ 610 | 🐛 1 | 🌐 Python | 📅 2026-08-06 - Model synchronization from dbt to Metabase.
* [dbt-project-evaluator](https://github.com/dbt-labs/dbt-project-evaluator) ⭐ 572 | 🐛 21 | 🌐 Shell | 📅 2026-08-24 - This package highlights areas of a dbt project that are misaligned with dbt Labs' best practices.
* [dbt-unit-testing](https://github.com/EqualExperts/dbt-unit-testing) ⭐ 448 | 🐛 25 | 🌐 Shell | 📅 2026-05-13 -  Package which contains macros to support unit testing.
* [dbt\_audit\_helper](https://github.com/dbt-labs/dbt-audit-helper/) ⭐ 422 | 🐛 11 | 📅 2026-05-19 - Macros for data audits that compare columns values and schemas between tables.
* [dbt-artifacts](https://github.com/brooklyn-data/dbt_artifacts) ⭐ 403 | 🐛 84 | 🌐 Shell | 📅 2026-08-10 - This package builds a mart of tables from dbt artifacts loaded into a table.
* [dbt-external-tables](https://github.com/dbt-labs/dbt-external-tables) ⭐ 381 | 🐛 63 | 🌐 Jupyter Notebook | 📅 2026-07-24 - Macros to stage your external sources.
* [dbt-snowflake-monitoring](https://github.com/get-select/dbt-snowflake-monitoring) ⭐ 260 | 🐛 33 | 📅 2026-03-18 - A dbt package to help you monitor Snowflake performance and costs.
* [dbt-coverage](https://github.com/slidoapp/dbt-coverage) ⭐ 240 | 🐛 17 | 🌐 Python | 📅 2026-04-29 - Checks dbt docs and tests coverage.
* [dbt\_metrics](https://github.com/dbt-labs/dbt_metrics) ⭐ 223 | 🐛 0 | 🌐 Python | 📅 2025-12-17 - Macros to support secondary calculations and generate business metrics.
* [datavault4dbt](https://github.com/ScalefreeCOM/datavault4dbt) ⭐ 202 | 🐛 16 | 🌐 PLSQL | 📅 2026-08-19 - Macros for staging and creation of all DataVault-Entities you need, to build your own DataVault2.0 solution.
* [dbt2looker](https://github.com/lightdash/dbt2looker) ⭐ 193 | 🐛 34 | 🌐 Python | 📅 2024-08-20 - Generate Looker views for dbt models.
* [dbt-ml-preprocessing](https://github.com/omnata-labs/dbt-ml-preprocessing) ⭐ 185 | 🐛 7 | 🌐 Python | 📅 2023-07-03 - A SQL port of python's scikit-learn preprocessing module, provided as cross-database dbt macros.
* [dbt\_constraints](https://github.com/Snowflake-Labs/dbt_constraints) ⭐ 177 | 🐛 12 | 🌐 SQL | 📅 2026-05-28 - Generate database constraints based on the tests in a dbt project.
* [dbt-superset-lineage](https://github.com/slidoapp/dbt-superset-lineage) ⭐ 156 | 🐛 3 | 🌐 Python | 📅 2026-02-12 - Push and pull metadata between dbt to Superset.
* [dbt-fabric](https://github.com/microsoft/dbt-fabric) ⭐ 146 | 🐛 32 | 🌐 Python | 📅 2026-08-24 - A dbt adapter for working with Microsoft Fabric Data Warehouses.
* [dbt-meta-testing](https://github.com/tnightengale/dbt-meta-testing) ⭐ 131 | 🐛 10 | 🌐 SQL | 📅 2026-04-16 - Yet another coverage testing.
* [Terraform-dbt Cloud Module](https://github.com/GtheSheep/terraform-provider-dbt-cloud) ⭐ 116 | 🐛 19 | 🌐 Go | 📅 2026-08-21 - IAC in dbt Cloud via Terraform.
* [dbt-excel](https://github.com/godatadriven/dbt-excel) ⭐ 97 | 🐛 10 | 🌐 Python | 📅 2026-03-12 - A dbt adapter for working with Excel.
* [dbt\_linreg](https://github.com/dwreeves/dbt_linreg) ⭐ 79 | 🐛 4 | 🌐 Python | 📅 2025-12-28 - Linear regression in SQL using dbt.
* [dbt\_ml](https://github.com/kristeligt-dagblad/dbt_ml) ⭐ 77 | 🐛 13 | 🌐 Makefile | 📅 2026-02-07 - Package for dbt that allows users to train, audit and use BigQuery ML models.
* [dbt-ibis](https://github.com/binste/dbt-ibis) ⭐ 74 | 🐛 7 | 🌐 Python | 📅 2025-03-18 - Write your dbt models using [Ibis](https://ibis-project.org/), the portable Python dataframe library.
* [dbt-assertions](https://github.com/AxelThevenot/dbt-assertions) ⭐ 73 | 🐛 2 | 📅 2025-11-25 - Package to assert rows in-line with dbt macros.
* [dbt-invoke](https://github.com/Dashlane/dbt-invoke) ⭐ 73 | 🐛 12 | 🌐 Python | 📅 2024-07-31 - CLI for creating, updating, and deleting dbt property files.
* [dbt-snow-mask](https://github.com/entechlog/dbt-snow-mask) ⭐ 70 | 🐛 30 | 📅 2026-03-15 - A dbt package for Snowflake Dynamic Data Masking.
* [ddbt](https://github.com/monzo/ddbt) ⚠️ Archived - This repo represents my attempt to build a fast version of DBT which gets very slow on large projects (3000+ data models). This project attempts to be a direct drop in replacement for DBT at the command line.
* [dbt-fabricspark](https://github.com/microsoft/dbt-fabricspark) ⭐ 64 | 🐛 4 | 🌐 Python | 📅 2026-08-24 - A code package from Microsoft for enabling dbt to work with Synapse Spark in Microsoft Fabric.
* [dbt-init](https://github.com/dbt-labs/dbt-init) ⚠️ Archived - Create a project and populate as much of the dbt project as possible.
* [dbt-snowflake-query-tags](https://github.com/get-select/dbt-snowflake-query-tags) ⚠️ Archived - Automatically tag dbt-issued queries with informative metadata.
* [dbt-privacy](https://github.com/pvcy/dbt-privacy) ⭐ 53 | 🐛 3 | 🌐 Makefile | 📅 2023-02-13 - Macros to make it easier to protect your customers' data.
* [dbt-erdiagram-generator](https://github.com/intellishore/dbt-erdiagram-generator) ⭐ 51 | 🐛 3 | 🌐 Python | 📅 2023-02-07 - This packages generate ERD diagrams from a dbt project.
* [dbt-timescaledb](https://github.com/sdebruyn/dbt-timescaledb) ⭐ 45 | 🐛 6 | 🌐 Python | 📅 2026-06-19 -  The TimescaleDB adapter plugin for dbt.
* [dbt-incremental-stream](https://github.com/arnoN7/dbt-incremental-stream) ⭐ 39 | 🐛 3 | 🌐 Python | 📅 2026-02-05 - A dbt package for Snowflake Streams.
* [dbt-testgen](https://github.com/kgmcquate/dbt-testgen) ⭐ 39 | 🐛 6 | 🌐 Shell | 📅 2024-02-28 - Generate dbt tests based on sample data.
* [dbt-feature-store](https://github.com/fal-ai/dbt_feature_store) ⭐ 39 | 🐛 1 | 🌐 Python | 📅 2022-12-16 - Macros to build a feature store right within your dbt project.
* [dbt-fake](https://github.com/leogodin217/dbt-fake) ⭐ 35 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2024-01-07 - Daily updated fake data for dbt learning and projects.
* [dbt-fivetran-utils](https://github.com/fivetran/dbt_fivetran_utils) ⭐ 33 | 🐛 21 | 🌐 Shell | 📅 2026-08-12 - General macros and helpers.
* [dbt-dag-monitoring](https://github.com/techindicium/dbt-dag-monitoring) ⭐ 30 | 🐛 12 | 🌐 Shell | 📅 2025-02-14 - A dbt package for monitoring airflow DAGs and tasks.
* [dbt-date](https://github.com/godatadriven/dbt-date) ⭐ 29 | 🐛 3 | 🌐 Python | 📅 2026-08-21 - Date logic and calendar functionality.
* [dbt-data-diff](https://github.com/infinitelambda/dbt-data-diff) ⭐ 26 | 🐛 1 | 🌐 PLpgSQL | 📅 2026-07-02 - Data-diff solution for dbt-ers with Snowflake.
* [dbt-tags](https://github.com/infinitelambda/dbt-tags) ⭐ 26 | 🐛 0 | 📅 2026-07-02 - Tag-based masking policies management in Snowflake.
* [DDO](https://github.com/marco-roy/DDO) ⭐ 16 | 🐛 1 | 📅 2021-05-11 - Perform DataOps & administrative CI/CD on your data warehouse.
* [dbt\_otel\_export](https://github.com/irvingpop/dbt_otel_export) ⭐ 11 | 🐛 0 | 🌐 PLpgSQL | 📅 2025-06-20 - Takes dbt runs and turns them into OpenTelemetry traces.
* [dbt-translate](https://github.com/datnguye/dbt-translate) ⭐ 10 | 🐛 0 | 🌐 TSQL | 📅 2023-10-21 - Translate numbers into words.
* [dbt-ml-inline-preprocessing](https://github.com/Matts52/dbt-ml-inline-preprocessing) ⭐ 8 | 🐛 2 | 📅 2026-08-07 - Feature Engineering in dbt.
* [snowflake-resource-monitoring](https://github.com/dbt-labs/snowflake-resource-monitoring) ⭐ 8 | 🐛 1 | 📅 2025-02-03 - Yet another package to monitor Snowflake usage.
* [usagedata](https://github.com/anjane-tech/usagedata) ⭐ 6 | 🐛 2 | 📅 2025-03-07 - Provides insights on the database/table level usage informations from Snowflake.
* [dbt\_diving](https://github.com/data-diving/dbt_diving) ⭐ 6 | 🐛 3 | 🌐 Shell | 📅 2026-01-15 - A free to use dbt package with helper macros
* [dbt\_cloud\_run\_cost](https://github.com/danthelion/dbt_cloud_run_cost) ⭐ 5 | 🐛 0 | 📅 2023-08-13 - Package to calculate dbt Cloud usage-based cost.
* [dq-vault](https://github.com/infinitelambda/dq-vault) ⭐ 5 | 🐛 0 | 🌐 Shell | 📅 2023-02-17 - Data Quality Observation of Data Vault layer.
* [dbt-reconfigured](https://github.com/TheGrowthEngineeringCompany/dbt-reconfigured) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2024-03-07 - A dbt package containing reconfigured macros.
* [dbt-unirate](https://github.com/UniRate-API/dbt-unirate) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-07-08 - Currency exchange rate macros and models for dbt, powered by the UniRate API.
* [dbt-census-utils](https://github.com/sutrolabs/dbt_census_utils) ⭐ 0 | 🐛 2 | 📅 2026-03-30 - A collection of dbt macros for working with Census data.
* [dbt\_semantic\_view/](https://hub.getdbt.com/Snowflake-Labs/dbt_semantic_view/) This package lets you materialize Semantic Views via dbt and reference them from downstream models.
* [dbt-fabricsparknb](https://insight-services-apac.github.io/APAC-Capability-DAI-DbtFabricSparkNb/) - Dbt Fabric Spark Notebook Generator by Insight based on/forked form dbt-fabricspark by Microsoft.
* [dbt-yaml-check](https://github.com/aranke-archive/dbt-yaml-check) - Checks that columns defined in YAML also exist in SQL.
* [dbt-coves](https://pypi.org/project/dbt-coves/) - CLI tool for generating a scaffold for your dbt project.
* [dbt-profiler](https://hub.getdbt.com/data-mie/dbt_profiler/latest) - Data profiling and doc block generator.
* [dbt\_utils](https://hub.getdbt.com/dbt-labs/dbt_utils/latest) - General macros library. A must have.
* [dbtvault](https://dbtvault.readthedocs.io/en/latest/) - Package for generating and executing ETL for Data Vault 2.0.

## Snippets

Useful code snippets and templates to speed up your dbt development.

* [trange\_join](https://gist.github.com/gnilrets/48886b4c8945dde1da13547c2373df73) - Macro to join dbt snapshots.
* [dbt\_to\_dbdiagram](https://gist.github.com/pcreux/b2e4a288b272fb17a36d319734fbb8ee) - Generate an ERD via dbdiagram.io from a dbt project.

## Community

Conferences, meetups, dicussions, newsletters, podcasts, etc. led by fellow analytics engineers and forums of contact.

* [Data Council Austin 2023](https://www.youtube.com/playlist?list=PLAesBe-zAQmF-GpvZ3ba5YpVzoVbgzl8M) - A conference for data teams.
* [State of Analytics Engineering 2023](https://www.getdbt.com/state-of-analytics-engineering-2023?mn=gWlJaysu_LpdqLTox0JXl6LHyaPHE5lKxcKh.yF0aSpyD38bsL9D9) - A survey of pains, gains, and areas of investment for global data teams.
* [dbt Labs Tiktok](https://www.tiktok.com/@dbtlabs) - Official TikTok channel of dbt Labs.
* [Locally Optimistic](https://locallyoptimistic.com/about/) - A Slack community of aspiring analytics leaders discussing and sharing lessons learned and challenges from their experiences in using data.
* [DataTalks.Club](https://datatalks.club/) - Global online community of data enthusiasts. Podcasts and blogs, etc. are distributed with high frequency.
* [Metadata Weekly](https://metadataweekly.substack.com) - Weekly substack about metadata, the metrics layer and MDS.
* [Data & Analytics Events in 2022](https://atlanhq.notion.site/atlanhq/Data-Analytics-Events-in-2022-7abf9f3daf8d42358234c6a00b43f1a6) - Great curated list of upcoming data analytics conferences.
* [Data Council Austin 2022](https://www.youtube.com/playlist?list=PLAesBe-zAQmEod2ARZjjAHmGFoGcjaXK6) - Worldwide community driven analytics conference with a handful of talks fitting to the dbt stack.
* [Discourse v2](https://github.com/dbt-labs/docs.getdbt.com/discussions) ⭐ 210 | 🐛 210 | 🌐 JavaScript | 📅 2026-08-24 - Revamped and ported hub of main discussions for the community.
* [Coalesce conference recordings](https://coalesce.getdbt.com/on-demand) - Recordings of Coalesce conferenfes from 2022 and after.
* [Coalesce 2021](https://www.youtube.com/playlist?list=PL0QYlrC86xQnNXXXL7WPRTULbMgh_Sry3) - Second iteration of the analytics engineer conference.
* [Coalesce 2020](https://www.youtube.com/playlist?list=PL0QYlrC86xQmPf9QUceFdOarYcv3ETSsz) - Annual dbt conference full of fascinating use-cases.
* [dbt meetups](https://www.meetup.com/en-AU/pro/dbt/) - List of community led dbt meetups.
* [Analytics Engineer Roundup](https://roundup.getdbt.com/) - Official dbt Labs newsletter on topics of the MDS.
* [Benn Stacil's Newsletter](https://benn.substack.com/) - Tought-provoking reads from founder of Mode.
* [Data Engineering Weekly](https://www.dataengineeringweekly.com/) - Weekly newsletter of recent trends in Data Engineering.
* [Data Engineering Podcast](https://www.dataengineeringpodcast.com/) - One of the most popular data engineering podcasts covering great concepts and new products.
* [Analyitics Engineer Podcast](https://podcasts.apple.com/us/podcast/the-analytics-engineering-podcast/id1574755368) - Official podcast of dbt Labs.
* [dbt Slack](https://www.getdbt.com/community) - Energy-filled hub of analytics engineers (Highly recommended).
* [r/dataengineering](https://www.reddit.com/r/dataengineering/) - Subreddit of data engineering topics.
* [Drill to Detail Podcast](https://www.rittmananalytics.com/drilltodetail) - Special guests discussing big data, business intelligence, modern data stack.
* [#dbtips](https://dbtips.substack.com) - Newsletter about dbt, with tips and tutorials on various topics.

## Sample Projects

Sample projects which work out-of-the box. Reflect use-cases publicly available.

* [Jaffle Shop](https://github.com/dbt-labs/jaffle_shop) ⚠️ Archived - A self-contained dbt project for testing purposes.
* [transfermarkt-datasets](https://github.com/dcaribou/transfermarkt-datasets) ⭐ 480 | 🐛 51 | 🌐 Python | 📅 2026-08-05 - E2E dbt project for scraping and transforming football data from Transfermarkt.
* [awesome-public-dbt-projects](https://github.com/InfuseAI/awesome-public-dbt-projects) ⭐ 213 | 🐛 2 | 📅 2023-12-28 - A curated list of awesome public dbt projects.
* [airflow-dbt-demo](https://github.com/astronomer/airflow-dbt-demo) ⭐ 186 | 🐛 8 | 🌐 Python | 📅 2023-08-23 - Demonstration of Airflow integration.
* [mdsfest-opensource-mds](https://github.com/dagster-io/mdsfest-opensource-mds) ⭐ 171 | 🐛 2 | 🌐 Python | 📅 2025-08-27 - Demo project for open source MDS.
* [dag-stack](https://github.com/spbail/dag-stack) ⭐ 167 | 🐛 2 | 🌐 HTML | 📅 2021-07-14 - Dbt-Airflow-GreatExpectations Stack.
* [Spotify User Analytics](https://github.com/ftupas/dbt-spotify-analytics) ⭐ 132 | 🐛 1 | 🌐 Python | 📅 2022-07-08 - Sample dbt project with Spotify user data.
* [mrr-playbook](https://github.com/dbt-labs/mrr-playbook) ⚠️ Archived - A worked example to demonstrate how to model subscription revenue.
* [Make Open Data](https://github.com/make-open-data/make-open-data/) ⭐ 78 | 🐛 30 | 🌐 Python | 📅 2026-02-07 -  A production grade ELT with tests, documentation and CI/CD (GHA) about french open data (housing, demography, geography, etc). Can be used to learn with voluminous and ambiguous data. Contributions are welcome.
* [dbt\_workspace](https://github.com/randypitcherii/dbt_workspace) ⭐ 62 | 🐛 1 | 🌐 PLpgSQL | 📅 2023-05-17 - A workspace template for dbt demos.
* [Use dbt inside Visual Studio Code development containers](https://github.com/davidgasquez/dbt-devcontainer) ⭐ 45 | 🐛 1 | 🌐 Dockerfile | 📅 2026-05-19 - Set up your dbt environment with pre-installed extensions.
* [Cloud Cost Monitoring](https://github.com/randypitcherii/cloud_cost_monitoring) ⭐ 38 | 🐛 1 | 🌐 PLSQL | 📅 2020-03-01 - A dbt project to monitor cloud costs.
* [attribution-playbook](https://github.com/dbt-labs/attribution-playbook) ⚠️ Archived - A worked example to demonstrate how to model customer attribution.
* [Data-aware orchestration](https://github.com/jonathanneo/data-aware-orchestration) ⭐ 31 | 🐛 0 | 🌐 Python | 📅 2023-01-20 - Dagster's ability to create a global dependency graph between different dbt projects.
* [mdsinabox](https://github.com/matsonj/mdsinabox) ⭐ 19 | 🐛 4 | 🌐 JavaScript | 📅 2023-06-28 - MDS in a box deployed anywhere.
* [dbt-github-workflow](https://github.com/slve/dbt-github-workflow) ⭐ 17 | 🐛 0 | 🌐 Makefile | 📅 2022-03-27 - Deploy BigQuery + Airflow.
* [dbt-snowflake-template](https://github.com/collinrlenon/dbt-snowflake-template) ⭐ 10 | 🐛 0 | 📅 2025-03-06 - Production-ready template deploying dbt project to Snowflake using GH Actions.
* [Analytics Engineer Survey 2023](https://github.com/dbt-labs/analytics-engineering-survey/tree/main) ⚠️ Archived - Repo containing data and dbt template of the survey.
* [datafold-dbt-ci-advanced](https://github.com/elliotgunn/datafold-dbt-ci-advanced) ⭐ 8 | 🐛 1 | 📅 2024-03-26 - Add 4 more integrations to your dbt CI pipeline: Slim CI, pre-commit hooks, Data Diffs, and Slack notifications.
* [NBA\_Data\_Modeling](https://github.com/jpooksy/paradime-dbt-nba-challenge) ⭐ 4 | 🐛 0 | 📅 2024-02-01 - Using the official NBA API, this repo explains how to ingest, store, transform, and serve insights.
* [dbt\_github\_archive\_bigquery](https://github.com/preset-io/dbt_github_archive_bigquery) ⭐ 3 | 🐛 1 | 🌐 Python | 📅 2023-06-28 - A dbt project for GitHub Archive data on BigQuery.
* [gee\_production\_gatekeepers](https://github.com/nszoni/gee_production_gatekeepers) ⭐ 2 | 🐛 0 | 📅 2024-01-15 - A demonstration of production gatekeepers in Snowflake and BigQuery.
* [f1-data-pipeline](https://github.com/InosRahul/f1-data-pipeline) - F1 Data Pipeline.
* [Tracking the Fake GitHub Star Black Market with Dagster, dbt and BigQuery](https://dagster.io/blog/fake-stars) - Explore the topic of fake GitHub stars.
* [GitLab Data Team](https://gitlab.com/gitlab-data/analytics/-/tree/master/transform/snowflake-dbt) - GitLab's open source dbt project.
* [aws athena x dbt](https://kiwamizamurai.github.io/posts/2022-08-25/) - How to build a small and modern data infrastructure.
* dbt on AWS ![image](https://user-images.githubusercontent.com/1023748/206618801-52fb35ab-bcb3-4ba5-9986-23498f03f70c.png) - Data Build Tool (dbt) for Effective Data Transformation on AWS
  * [Part 1 – Redshift](https://jaehyeon.me/blog/2022-09-28-dbt-on-aws-part-1-redshift/)
  * [Part 2 – Glue](https://jaehyeon.me/blog/2022-10-09-dbt-on-aws-part-2-glue/)
  * [Part 3 – EMR on EC2](https://jaehyeon.me/blog/2022-10-19-dbt-on-aws-part-3-emr-ec2/)
  * [Part 4 – EMR on EKS](https://jaehyeon.me/blog/2022-11-01-dbt-on-aws-part-4-emr-eks/)
  * [Part 5 – Athena](https://jaehyeon.me/blog/2022-12-06-dbt-on-aws-part-5-athena/)
* Data Build Tool (dbt) Pizza Shop Demo - A series of posts that illustrate data modeling and Airflow integration, targeting multiple data warehouses.
  * [Part 1 Modelling on PostgreSQL](https://jaehyeon.me/blog/2024-01-18-dbt-pizza-shop-1/)
  * [Part 2 ETL on PostgreSQL via Airflow](https://jaehyeon.me/blog/2024-01-25-dbt-pizza-shop-2/)
  * [Part 3 Modelling on BigQuery](https://jaehyeon.me/blog/2024-02-08-dbt-pizza-shop-3/)
  * [Part 4 ETL on BigQuery via Airflow](https://jaehyeon.me/blog/2024-02-22-dbt-pizza-shop-4/)
  * [Part 5 Modelling on Amazon Athena](https://jaehyeon.me/blog/2024-03-07-dbt-pizza-shop-5/)
  * [Part 6 ETL on Amazon Athena via Airflow](https://jaehyeon.me/blog/2024-03-14-dbt-pizza-shop-6/)

## Contributors

Thanks for all the great resources! Can't see your avatar? Check the contribution guide on how you can submit your resources to the community!

<a href="https://github.com/Hiflylabs/awesome-dbt/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=Hiflylabs/awesome-dbt" />
</a>

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-24._
