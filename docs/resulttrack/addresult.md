---
hide:
  - toc
full-width: true
---


# Adding a New Result

### Getting Started

!!! info "Reminder"
    **Your first step each time you open the tool should be to set your working data package directory.** 
    
    * If you have not yet set your working data package directory this session, do so before attempting to annotate.
    * If you have not set your working package directory before attempting to annotate a result, the tool cannot automatically generate your result-ID or connect your result to your data package folder. You will receive the error message below.

        ![](../app-screenshots/set-work-dir-result-error.PNG)

1. Navigate to the "Add Results" tab and select "Add a new result."
    
    <figure markdown>
        ![](../app-screenshots/add-result-new.PNG)
        <figcaption></figcaption>
    </figure>

2. The tool will look through your set working data package directory to determine whether there are existing annotated results files saved in the folder and will automatically generate the next sequential Result ID (e.g., result-1, result-2, etc.).
    1. The User Status Message Box will display a message to acknowledge this:

    <figure markdown>
        ![](../app-screenshots/usmb-results-track-1.PNG)
        <figcaption></figcaption>
    </figure>

    
### Filling Out the Form

!!! Tip
    * For additional information about each form field, please refer to the [Results Tracker schema](../schemas/md_results_tracker.md).
    * Hovering over each field in the form will provide additional information about what should be contained within the field. For example, for the Result Category field:
        ![](../app-screenshots/tooltip-ex.PNG)

2. Fill out a short **Result Description.**

    <figure markdown>
        ![](../app-screenshots/result-id-desc.PNG)
        <figcaption></figcaption>
    </figure>

1. Select a **Result Category.** 
    1. Based on the Result Category selected, additional questions will appear within the form.

    <figure markdown>
        ![](../app-screenshots/result-category.PNG)
        <figcaption></figcaption>
    </figure>

3. **Experiment Result 'Belongs' To**: You can define the experiment with which your result is associated here.
    1. This option allows you to associate your results directly with experimental research questions and hypotheses, which can be useful for future researchers trying to understand your experiments and findings. 
    2. This field pipes in all existing experiment names from the Experiment Tracker into a drop-down menu.

     <figure markdown>
        ![](../app-screenshots/result-assoc-exp.PNG)
        <figcaption></figcaption>
    </figure>  

2. **Associated Multi-Result File(s)**: You will also need to provide the path for the Associated Multi-Result File (e.g., manuscript, poster, etc.), in which the individual result appears. To add, select the arrow below the field:

    <figure markdown>
        ![](../app-screenshots/assoc-multi-result-file-2.PNG)
        <figcaption></figcaption>
    </figure>
        
    *If the result is associated with multiple multi-result files*, select the arrow again and enter the paths to each of the multi-result files here. This will allow the tool to create a results tracker for each of those multi-result files in future steps (or add the individual result to the right results trackers), all of which will be associated with this result.

    <figure markdown>
        ![](../app-screenshots/assoc-multi-result-file-multi.PNG)
        <figcaption></figcaption>
    </figure>

3. **Figure Number/Table Number**: If you selected "Figure" or "Table" within "Result Category," you will need to provide a corresponding figure/table number for each "Associated Multi-Result File."
    1. Click on the arrow to insert each figure/table number. 
        1. Ensure that the figure/table numbers are in the same order as the multi-result files. You can adjust the order using the green up and down arrows.
        
        <figure markdown>
            ![](../app-screenshots/figure-num.PNG)
            <figcaption></figcaption>
        </figure>
        
4. **Associated Files/Dependencies**: There are two ways to add "Associated Files/Dependencies," manually or via batch add. See below for descriptions of each.

    !!! Warning

        **You should only utilize one of the below methods for entering dependencies when adding a specific result.** If you add some files as associated files/dependencies manually and then utilize the "Add Multiple Results Dependencies" option, those files may overwrite the files you entered manually.

    2. *Manually adding Associated Files/Dependencies*

        1. If you are adding only a few associated files/dependencies, you can add each row individually using the arrow button:

        ![](../app-screenshots//results-assoc-single.PNG)

    3. *Batch adding Associated Files/Dependencies*

        1. If you would like to add many associated files at once, you can use the "Add Multiple Results Dependencies" option, which can be found at the top of the "Add Results" window:

            ![](../app-screenshots/multi-depend-add.PNG)

            1. Fill in this field with associated files/dependencies using drag-and-drop from your file explorer.

            ![](../app-screenshots/results-multi-depend.PNG)

            2. The files you drag and drop will automatically appear in the "Associated Files/Dependencies" section in the form.

            ![](../app-screenshots/results-multi-auto.PNG)


1. **Result Supports**:  describes the larger claim that the result is used to support in the multi-result file. This is not required but can be very useful for data reuse and interpretation for future researchers.

    ![](../app-screenshots/results-support.PNG)

### Saving Your Result

1. When you are done filling out the form, select "Save result."

!!! warning

    **Make sure that you do not have your Results Tracker open before trying to save.**

    If you attempt to save a result but have the corresponding Results Tracker open, the annotated result file *will* save to your dsc-pkg folder, but the tool *will not* be able to automatically save the information to the Results Tracker. You will receive this error:
        <figure markdown>
            ![](../app-screenshots/result-tracker-open-error.PNG)
            <figcaption></figcaption>
        </figure>
    
    As the printed message explains, in this case, you will have to use the ["Batch add existing result(s) to tracker" option](batchresult.md) to add this annotated result file to the Results Tracker.

2. If your result saves successfully, The User Status Message Box will display this message to indicate your result saved successfully and that the result has been written to the Results Tracker file.

    <figure markdown>
        ![](../app-screenshots/usmb-results-save.png)
        <figcaption></figcaption>
    </figure>


1. Although the tool will generate the necessary Results Trackers and add your result automatically as part of the "save" process, your individual result annotation file will also be saved within your dsc-pkg folder as a .txt file. 

    <figure markdown>
        ![](../app-screenshots/result-track-output.PNG)
        <figcaption></figcaption>
    </figure>

    !!! note
        Once you have created them, you will not generally need to interact with the annotation files (.txt files) unless:
        
        1. You need to [edit an existing annotated result](editresult.md)
        2. There is an error in automatically adding results to the Results Tracker, which would necessitate manually [batch adding results to the tracker](batchresult.md)

3. Clear the form. When the form resets, the next sequential Result ID will be generated, so you can start annotating a new result right away.

    <figure markdown>
        ![](../app-screenshots/result-clear-form.PNG)
        <figcaption></figcaption>
    </figure>




            