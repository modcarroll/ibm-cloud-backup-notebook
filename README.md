# IBM Cloud Backup Notebook

This notebook was inspired by the [IBM Cloud backup tool](https://github.com/modlanglais/ibm-cloud-backup) and is meant to be used in [Watson Studio](https://dataplatform.cloud.ibm.com/). This notebook will, given the credentials, backup the data in Watson Assistant and Watson Discovery. The data will be saved in the Watson Studio project it is executed in, as a set of assets.

## Get Started

1.) `git clone https://github.com/modlanglais/ibm-cloud-backup-notebook`

2.) Navigate to https://dataplatform.cloud.ibm.com

3.) Either create a new project or open an existing project where you would like the notebook to run. It is recommended to create a new project as this notebook saves large number of files as assets.

4.) Once you open the project, click the blue 'Add to project' button, then 'Notebook.'

5.) Under the heading for the new notebook page, click 'From File.'

6.) Give your notebook description (optional) and select the runtime. Make sure to select a Python runtime. (Note: The Name field will be automatically populated during the next step.)

7.) Click 'Choose file' and select 'IBM Cloud Backup.ipynb' from your machine. If you prefer a different name, edit the Name field here. Select 'Create notebook.'

8.) Once the notebook loads, position your cursor in the block near the top that says, "# Insert project credentials here by clicking the three ellipses on the toolbar above then 'Insert project token'". Click the three ellipses on the toolbar above and click 'Insert project token.'

9.) Scroll down to the credentials section. Modify the credentials in the specified fields for the Assistant and Discovery instances you would like to backup.

10.) On the toolbar, click Cell > Run All.



## To schedule your notebook:

1.) Click the jobs icon from the notebook’s menu bar and select Create a job.

2.) Enter a name, a description and select a version. The most recently saved version of the notebook is used by default. If no version of the notebook exists, you must create a version by clicking the versions icon from the notebook action bar.

3.) Select the runtime. By default, the job uses the same environment definition which is selected for the notebook.

4.) Optional: Add a one-time or repeating schedule for the notebook run. Ensure that you define meaningful date and time ranges. You can’t change the time zone; the schedule uses the time zone setting on your browser.

5.) Create a notebook job and run it immediately, or create a job and run it later. All notebook code cells are run and all output cells are updated.
