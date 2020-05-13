## Submitting Field Trial Plots

The form for submitting or editing existing Plots is available at  [https://grassroots.tools/private/service/field_trial-submit_plots](https://grassroots.tools/private/service/field_trial-submit_plots)

Plots can be added to the study using a table:

![The form for submitting field trial plots](images/Image_2.png)

Firstly, select the study from the drop down menu.

Then the table below will either load the plot info already in the database or showing empty.

![Add Measured Variables dialogue](images/Image_3.png)

The spreadsheet contains:

 * **Sowing date**: Sowing date of the plot.
 * **Harvest date**: Harvest date of the plot, can be left empty.
 * **Width**: Width of the plot fill the values with unit.
 * **Length**: Length of the plot fill the values with unit.
 * **Plot ID**: The ID of the plot.
 * **Row**: Row number of the plot.
 * **Column**: Column number of the plot.
 * **Replicate**: Replicate number of the plot.
 * **Rack**: Rack number of the plot.
 * **Accession**: Accession name, currently the Germplasm Resource Unit of the John Innes Centre, can be empty, more genbanks will be added. 
 * **Comment**: Any comments for the plot.
 * **and measured variables columns**: Extra columns you added with the method below:

To add data or import an Excel file, make sure to add the [Measured Variables](https://grassroots.tools/public/service/field_trial-search_measured_variables)
 first. They can be found
            from the page in the link above, when a Measured Variable is entered in the above popup window (*e.g.*
            SLA_M_m2kg1), three new columns will be created in the table. These three columns are for the phenotypic
            value, the date in YYYY-MMM-DD format that the value was measured and a column for any corrected value that
            is calculated after further analysis. These columns are the name of the Measured Variable, the name followed
            by “ date” and the name followed by “ corrected”. So for our example Measured Variable above, the three
            columns would be: 

- **SLA_M_m2kg1**: This is the raw phenotypic value for SLA_M_m2kg1.
- **SLA_M_m2kg1 date**: This is the date in YYYY-MMM-DD format that the value was measured.
- **SLA_M_m2kg1 corrected**: If the value was subsequently adjusted, the update value is
                placed here. This entry can be blank.
    
![New columns](images/Image_4.png)

Press “Add Row” for each row of the plots to be added with the relevant info, or you can download an Excel file to edit offline.
            

Once completed, a filled Excel file can be imported to the table using the drop zone above the table with the
            heading <i>Plot data to upload</i>. The table will then be filled with the information from the uploaded
            Excel file. The spreadsheet columns are matched by the column header name so it is important if a treatment
            is added make sure they are present in the web form’s table too. The import will work without them but those
            columns will be ignored.