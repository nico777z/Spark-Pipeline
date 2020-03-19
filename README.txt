This pipeline was adapted to run in a Cluster of Databricks.
You can either create/use a Community Databrick's account, or change the output directory to one of your local machine.

Local Machine:

Replace lines 1 and 2 with your preferred paths:
input_dir = '/FileStore/tables/'
outdir = '/dbfs/FileStore/'

If you choose to use Databricks, after running the pipeline, you can download the generated files as follows:

https://community.cloud.databricks.com/files/pre-processed.csv?o=189989883924552#
https://community.cloud.databricks.com/files/normalized.csv?o=189989883924552#
https://community.cloud.databricks.com/files/extracted.csv?o=189989883924552#
https://community.cloud.databricks.com/files/integrated.csv?o=189989883924552#

where ?o=189989883924552# is my account's url. Please replace it with yours.
Just to make it more clear, my Home url looks like this:
https://community.cloud.databricks.com/?o=189989883924552#)

The pipeline was exported as IPython Notebook file, please use one (Spider, Jupiter Notebook, Colabs, Azure, etc.) to run the pipeline properly.