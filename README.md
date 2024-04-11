# Google Cloud (gcloud) Commands

This Bamboo spec plan facilitates the execution of a bash script using the `gcloud` command.

## Usage

1. **Commit Input File**: Ensure that the input file containing the bash script is committed inside the `gcloud` directory of your repository.

2. **Run the Plan**: When running the plan, specify the filename as a variable and set its value equal to the filename.

### Example

Suppose the filename is `gcloud_commands.sh`, you would run the plan with the following variable:

```variable when running the plan
filename=gcloud_commands.sh
**|

## Important Note

Make sure that you have the necessary permissions and configurations set up for executing `gcloud` commands within your environment.

[Link to Bamboo Plan](https://example.com/bamboo-plan)


# Postman Collection Plan

This Bamboo spec plan facilitates the execution of a postman collection using newman.

## Usage

1. **Commit Input File**: Ensure that the input file containing the postman collection json is committed inside the `postman/collection` directory of your repository and variables.json to the `postman/variables` directory of your repository.

2. **Run the Plan**: When running the plan, specify the filename as a variable and set its value equal to the filename.

### Example

Suppose the filename is `collection1.json`, you would run the plan with the following variable:

```variable when running the plan
filename=collection1.json
**|

## Important Note

[Link to Bamboo Plan](https://example.com/bamboo-plan)
