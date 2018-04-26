# Making Your Dataset Analysis-Ready

---

Read on to make sure your dataset integrates well into dashboarding/analytical tools. Below you will be shown some common practices in compiling datasets to facilitate data analysis and use.

If you follow the following best practices, **the data that you have spent so much time and energy collecting will be very useful to you and your team. **

### Data Layout and Column Headers

**Common practice:**

Formatting your dataset in this way \(see example below\)  makes intuitive sense - it is visually appealing and it is easy for users to understand.

![](/assets/Bildschirmfoto 2017-12-29 um 11.00.51.png)

> **Here:**
>
> * multiple rows at the top of the data are used for levels of column headers
> * the actual data starts a few rows below the top of the sheet
>
> **That:**
>
> * leaves some room at the top for explanatory, introductory information or to stylize it 
> * makes it easier for team members who need to quickly understand the data they are looking at
>
> **But:**
>
> This can create **problems** down the road in the analysis stage

**Best practice:**

To better enable the data in your dataset to be analyzed and visualized, it is necessary to make some changes to the dataset layout:

1. **Only one row of column headers for the dataset, with no multi-level or merged cells.** In places where you have been using a two-level column header, you will need to combine the info in the top level and bottom level for each column.

2. There should be **no blank rows above your data - data should start in cell A1** of the spreadsheet. This is to facilitate the importation of your data into analysis and dashboarding software.

3. **No merged cells** anywhere ** in your dataset.**

4. **Notes, comments, associated graphics **or** images belong in a separate read-me file,** and out of the dataset itself.

Once you've updated your dataset layout to follow these guidelines, it should look something like this: ![](/assets/Bildschirmfoto 2017-12-29 um 11.53.48.png)Example for "wide" format

---

### Data Structure

When entering data into your dataset there are some specific do's and don'ts that will have substantial impact on how easy or hard it is to analyze your data and create helpful dashboards and visualizations based off of it.

**Number 1: "Long" vs "Wide" Format**

|  | Do | Don't |
| :--- | :--- | :--- |
|  | enter data in the** "long" format** _\(see example below:\)_ | enter data on the** "wide" format** _\(see example above:\)_ |
| Meaning: | additional **rows** holding the information | additional  **columns** holding the information |
| Reason: | **easier** to analyze data | **harder** to analyze data |
| Example: | If the dataset were to be organized into a "long" format, rather then separate columns for each month, there would be a single column labeled "Month", with values in the rows below indicating what month the data corresponds to. | the dataset is organized into a "wide" format - there are additional columns added to the dataset for each month of data that is being tracked. |

![](/assets/Bildschirmfoto 2017-12-29 um 12.36.13.png)Example for "long" format

> If you have already set up a dataset in the "wide" format, don't feel the need to spend lots of time reorganizing it to be "long". If you are setting up a new dataset, however, or don't have much in your data set, consider using the "long" format as it will make analysis and visualization of your data much easier.

**Number 2: Amount of Information Per Cell**

|  | Do | Don't |
| :--- | :--- | :--- |
|  | **each cell** of the dataset only contains **one piece of information** | enter **lots of information in a single cell** |
| Meaning: | if you have multiple values split them into TWO \(or more\) rows with the correct numbers tied to the correct identifying features_ \(example below\)_ | multiple values in one row \(example below\) |
| Reason: | easy to quickly calculate total beneficiaries, or beneficiaries by nationality, sex, age, or a combination | data entered in this manner is almost impossible to analyze |
| Example: |  | there is no quick way to sum all beneficiaries to arrive at a total, and if there were many cells like this there is also no quick way to total how many beneficiaries of each nationality and sex there are. |

---

### Data Entry Process

When starting to populate a dataset with data: at the beginning it is working fine because the dataset is still small and you have a good overview over all of the information that has been entered. From the moment the dataset gets bibber and bigger, difficulties may appear.

One of the most common problems is inconsistency in things that should be the same. For example, some people may enter Gaziantep as "Gaziantep", others as "GTZ", and so on.  For this reason, you will need to have a plan for how to validate \(ensure the correctness of\) the data in your dataset. **Validation** allows to **control over the type of data entered in each column of data, ensuring that numbers are numbers, dates are dates, etc.**

There are a couple of **tools for digital data collection** that can be very useful for this. They can dramatically:

* speed up data collection 
* improve data quality 

> The dataset that is produced through e.g. the Ona system is clean and easily useable for analysis.



