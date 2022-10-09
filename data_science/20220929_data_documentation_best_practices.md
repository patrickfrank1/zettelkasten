# Data documentation best practices

url: <https://towardsdatascience.com/data-documentation-best-practices-3e1a97cfeda6> \
tags: data documentation, data versioning, data consistency, data science landscape

- need to document all of your data sources (and data models) in one place from the begining of development

Why data documentation is important:

1. saves time
    - memory and details are fresh while you are at it
    - documentation to read up later on
2. increased transparency
    - everyone in the company has a window into the data
    - fewer questions by stakeholders
    - users don't have to hunt down owners of datasets every time they use them
3. ensures high quality
    - makes sure the data is always used in the right way
    - KPIs will be consistent
    - code changes can be tracked
    - keep track of freshness of datasets, potential errors, dependencies between models

Best practices:

- create a dbt-style guide for data models
  - naming conventions
  - SQL best practices
  - documentation standards
  - data types
- document column definitions while building a model
  - make sure definitions are consistent and accurate
  - recommended to use dbt
- use version control with your data models and data pipeline
  - dbt
  - git
  - dvc
  - prefect
  - ...
