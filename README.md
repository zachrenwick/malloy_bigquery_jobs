# BigQuery Jobs Analysis
Model for information_schema.jobs in bigquery.  To run this model, Modify the [jobs_table.malloy](jobs_table.malloy) to point to your data.  Note, that this model won't yet run on Google Cloud Shell as it doesn't yet support Notebooks.

## Notebooks
* [Overall Statistics](overall.malloynb)
* [User Statistics](by_user.malloynb)
* [Most Expensive Queries](most_expensive.malloynb)


## Steps to get started
- create a fork
- open the repo from GitHub codespaces
- install gcloud cli into codespace:
curl -O https://dl.google.com/dl/cloudsdk/channels/rapid/downloads/google-cloud-cli-394.0.0-linux-x86_64.tar.gz
tar -xf google-cloud-cli-394.0.0-linux-x86_64.tar.gz
./google-cloud-sdk/install.sh
