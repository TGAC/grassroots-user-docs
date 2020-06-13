## Submitting Studies

The form for submitting or editing an existing Study is available at [https://grassroots.tools/private/service/field_trial-submit_study](https://grassroots.tools/private/service/field_trial-submit_study).

A Study is an experiment that takes place at a location to measure a variety of phenotypes. It is one of the
main forms that you will need to complete and has a number of fields:

 * **Name** *: The name of the Study.
 * **Field Trial** *: This is the Field Trial that this Study belongs to. If the Field Trial
      that you require is not in this list, then you’ll need to create it by following the instructions for
      [creating a Field Trial](submit_trial.md).
 * **Location** *: This is the Location where the Study is taking place. If the Locations that
      you require is not in this list, then you’ll need to create it by following the instructions for
       [creating a Location](submit_location.md) 
 * **Soil**: This is a free-text field to give any details about the soil condition for the
      Study
 * **Link**: If there is a web page relating to this Study with more information that will be
      of interest to users, it can be specified here.
 * **Sowing date**: This is the date when the seeds are shown in the field.
 * **Harvest date:** This is the date when the crops are harvested. The plots data can be
      entered at the drilling stage in which case this field can be left blank.
 * **Description**: This is a free-text field where a general description of this Study can be
      defined.
 * **Growing Conditions**: This is a free-text field where any notes about the growing
      conditions for this Study can be placed.
 * **Design**: This is a free-text field where any notes about the experimental design of this
      Study can be set. 
 * **Phenotype gathering notes**: This is a free-text field where any notes about the
      collection of phenotypes for this Study can be set.
 * **Weather**: If there is a system with the weather details for this Study, enter the web
      page for it here.
 * **Aspect**: The direction of the plots layout. If this is not known, choose *unknown*. 
 * **Slope**: The slope of the field.
 * **Crop**: This is the crop that has been sown for this Study. If the required crop is
      missing, please contact us to make it available in the system.
 * **Previous crop**: This is the crop that was previously sown in the field that this Study
      is in. If the required crop is missing, please contact us to make it available in the system. 
 * **pH minimum**: If the pH levels of the soil are known, enter the minimum value here.
 * **pH maximum:** If the pH levels of the soil are known, enter the maximum value here.
  

### Default plot data

To make the plots data easier to enter if you have a standard layout, you can set some default parameters
here and Grassroots will automatically create a partially-completed spreadsheet for plots data for this
Study. The values that can be set are:

 * **Number of plot rows**: How many rows of plots there are in this Study.
 * **Number of plot columns**: How many columns of plots there are in this Study.
 * **Number of replicates**: The number of genotype replicates in this Study. If left blank, it is assumed to be 1.
 * **Plot width**: This is the width, in metres, of each plot.
 * **Plot height**: This is the length, in metres, of each plot.

To automatically generate the spreadsheet of Plot data, at least both of the *Number of plot rows* and
*Number of plot columns* parameters need to be specified. Grassroots will generate a row in the
spreadsheet for each unique possible combination of the row, column and replicate values.

