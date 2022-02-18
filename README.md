# Indigo Developer Template
This is a template for Indigo developers to create and own their web3 SQL models and license them to daily users on the Indigo marketplace.

Indigo uses the industry standard (DBT package)[https://docs.getdbt.com/docs/introduction] and SQL to make it faster and easier for Data Scientists and Analysts to create data models without the heavy lifting of running their own infrastructure. The public Indigo Data Nodes require dbt compliant file structure and config to  compile and buidl the thousands data models owned by the developer community. 

This template and the steps below are all you need to get your model on the marketplace and generate revenue.

### Pre-development: 
To gain access to the Indigo dev environment for testing, you need data warehouse credentials. Please reach out to ahessert@gmail.com or `@rooo#8135` on discord.

### Using this template
1. Fork and rename this repository.
2. *Edit* `dbt_project.yml`
  a. Replace <repository_name> with your new name.
  b. Replace <author_name> with your username used to access the Indigo developer node.
3. Write your model using SQL in `./models/sample_model.sql`, and rename the file (this will the name used on the Indigo marketplace)
4. *Edit* `./models/schema.yml`
  a. Replace <sample_model> with your model matching the name of your SQL file.
  

### Running your model
`dbt build <model_name>`

### Minting your model NFT
