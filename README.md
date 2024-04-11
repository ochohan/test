# Google Cloud (gcloud) Commands

This Bamboo spec plan facilitates the execution of a bash script using the `gcloud` command.

## Usage

1. **Commit Input File**: Ensure that the input file containing the bash script is committed inside the `gcloud` directory of your repository.

2. **Run the Plan**: When running the plan, specify the filename as a variable and set its value equal to the filename.

### Example

Suppose the filename is `gcloud_commands.sh`, you would run the plan with the following command:

```bash
filename=gcloud_commands.sh
