# Advanced

## Add a New Experiment Based on an Existing Experiment

If you need to annotate an experiment that is very similar to a previously annotated experiment, with only slight changes, you may want to use the "Add a new experiment based on existing experiment" option. 

With this feature, you will select a previously annotated experiment, and tool will copy the information from the chosen experiment into a new experiment form with a unique experiment-ID. You will then only need to edit the information rather than reproduce it.

1. Select "Add a new experiment based on an existing experiment."

    <figure markdown>
        ![](../app-screenshots/new-based-on-old.PNG)
        <figcaption></figcaption>
    </figure>

2. Your working data package folder will open automatically. Select the experiment on which you want to base your new experiment annotation. 

    <figure markdown>
        ![](../app-screenshots/select-old-exp.PNG)
        <figcaption></figcaption>
    </figure>

3. The annotate experiment form will open and populate with the selected experiment information with a unique ID.

    <figure markdown>
        ![](../app-screenshots/populate-new-exp.PNG)
        <figcaption></figcaption>
    </figure>

4. Edit the form to reflect the differences in this new experiment. Save the form.

## Batch Add Experiment(s) to Tracker

This feature allows you to manually add existing annotated experiments to the Experiment Tracker. You should not generally need to use this feature, but it is included to account for the possibility that an error in the saving process could cause your annotated experiment to be saved as a .txt file but not automatically added to the Experiment Tracker. In this case, you will be able to use the "Batch add existing experiment(s) to tracker" option to add these experiment(s) to the appropriate tracker.

1. Ensure that your Experiment Tracker is closed before attempting to batch add experiments.
1. Navigate to the "Add Experiment" tab and select "Batch add existing experiment(s) to tracker" under "Advanced."

    <figure markdown>
        ![](../app-screenshots/batch-add-exp-1.PNG)
        <figcaption></figcaption>
    </figure>

3. Select the experiments that you want to add.
    1. It may be easiest to select all existing annotated experiment files when using this feature. The tool will scan the experiment files you select and only add those that are not already included in the Experiment Tracker.
    2. Note: These files follow the naming convention "exp-trk-exp-"

    <figure markdown>
        ![](../app-screenshots/select-exp-batch.PNG)
        <figcaption></figcaption>
    </figure>

4. If your files are successfully added to the Experiment Tracker, the User Status Message Box will provide a confirmation message:

    <figure markdown>
        ![](../app-screenshots/usmb-batch-add-exp.PNG)
        <figcaption></figcaption>
    </figure>