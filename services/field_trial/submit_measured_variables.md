##Submit Measured Variables

Within an experiment various phenotypes can be measured and these are called **Measured Variables**. Each of these consist of unique *triples* (three distinct pieces of information) that define:

 * A phenotype
 * How it has been measured
 * Which units have been used

Before the Plots data that contains phenotypic values can be submitted, the required *Measured Variables* need to have been imported into the system. The form for submitting these ontology terms is available at [https://grassroots.tools/private/service/field_trial-submit_measured_variables](https://grassroots.tools/private/service/field_trial-submit_measured_variables)

The data is submitted as a spreadsheet where each row contains the information for a single *Measured Variable*. 
you can download a [spreadsheet](empty_measured_variables.csv) with the correct column headings ready for you to add your measured variable definitions to.
The column headings are described below: 

 * **Variable Identifier** *: This is the unique URI for this variable.
 * **Variable Name** *: The name of the phenotype being measured. This is the column header that you should use when submitting the Plots data for a Study and it cannot contain any spaces.
 * **Variable Description**: An optional description of the phenotype being measured.
 * **Variable Abbreviation**: An optional abbreviation of the phenotype being measured.
 * **Trait Identifier** *: This is the unique URI for this trait.
 * **Trait Name** *: The name of the trait being measured.
 * **Trait Description**: An optional description of the trait being measured.
 * **Trait Abbreviation**: An optional abbreviation of the trait being measured.
 * **Method Identifier** *: This is the unique URI for this method.
 * **Method Name** *: The name of the method used.
 * **Method Description**: An optional description of the method being used.
 * **Method Abbreviation**: An optional abbreviation of the method being used.
 * **Unit Identifier** *: This is the unique URI for this unit.
 * **Unit Name** *: The name of the unit used.
 * **Unit Description**: An optional description of the unit being used.
 * **Unit Abbreviation**: An optional abbreviation of the unit being used.
 * **Scale Class** *: This denotes that type of values that this Measured Variable can take and we use the possible options defined by the Crop Ontology. These are:

    * **Date**:
The date class is for events expressed in a time format, *e.g.* “yyyymmdd hh:mm:ss –
UTC” or “dd-mm-yy”. A good practice recommended by the Breeding API (BrAPI) is to
use the Date and timestamp fields coded in the ISO 8601 standard, extended format.
Check the [relevant BrAPI docs](https://github.com/plantbreeding/BrAPI/blob/brapi-V2.1/Specification/GeneralInfo/Date_Time_Encoding.md) for more information.
    * **Duration**:
    The duration class is for time elapsed between two events expressed in a time format,
   *e.g.* “days”, “hours”, “months”.
    * **Nominal**:
Categorical scale that can take one of a limited number of categories. There is no
intrinsic ordering to the categories e.g. r=“red”, g=“green”, p=“purple”.
    * **Numerical**:
Numerical scales express the trait with real numbers. The numerical scale defines the
unit *e.g.* centimetre, ton per hectare, number of branches.
    * **Ordinal**:
Ordinal scales are composed of ordered and fixed number of categories *e.g.* 1=low,
2=moderate, 3=high
    * **Text**:
A free text is used to express the scale value. Also known as Character variable
(varchar) *e.g.* “Preferred when slightly undercooked”.
    * **Code**:
This scale class is exceptionally used to express complex traits. Code is a nominal
scale that combines the expressions of the different traits composing the complex trait.
For example, a disease related code might be expressed by a 2-digit code for intensity
and 2-character code for severity. The first 2 digits are the proportion of plants affected
by a fungus and the 2 characters refer to the severity, *e.g.* “75HD” means “75% of the
plants are infected and plants are highly damaged”. It is recommended to create
variables for every component of the code.



The required attributes are denoted with * and the column headings can be in any order.


