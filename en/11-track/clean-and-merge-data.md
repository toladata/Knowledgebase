****
# Clean and Merge Datasets
---

### Edit Columns

Once you've imported data you can then do basic edits on your data table, like for example change column names or create new columns with values dependent on your existing ones. You can also make sure that you'll find the expected information in your data columns by running column validation function. 

Under `Your Tables` navigation, click on the `Edit` tab and you will see the option to `Edit or Delete Columns`, `Add New Column`, `Add New Formula Column` and `Add Column Validation`. You can even `set new default value` for any of your columns.

![](/assets/table_edit.PNG)

### Merging Multiple Tables

You can merge all columns in your selected merge tables, by mapping just one similar column and the rest will automatically be mapped.

When **Appending Tables** the rows in a Table will add additional rows to the existing table extending the overall table.

When **Merging Tables** the specified rows \(e.g. User ID\) in Table will be mapped across the two datasets and additional columns linked to each beneficiary/User ID will be added.

In order to do that go to Your Tables:

  1. Choose `Merge` next to the Table you want to merge **from**.

  2. Next, choose the Table you want to merge **to**.

  3. Choose the columns you want to be in your table.

  4. Most users choose `Select All`, but you might want to leave out columns automatically added by your data collection tool, like record logs.

  5. Next, map at least one column and choose `Map Selected Columns`.

  6. Click `Submit` and the rest will automatically map if the column names match.
  
> **Quick Tip:**   
> What if you wish to map two columns with different names? Don't worry! Select them (step 5 above) as if they had the same name and the rest will be done for you automatically.



#### Merging Columns - Join \(Concatenate\)

Follow the [Merging steps](https://tola.hackpad.com/4.-Multiple-Tabs-in-your-GSheet-Currently-we-can-only-import-the-first-sheettab-in-your-GSheet.-BlUMTgJoO8v#:h=Merging-Table-and-Mapping-Colu) above

In Step 2:

  * Select the `Table 1 column` \(example: `firstname` and `lastname`) you want to map

  * Next Select the `Table 2 column` to map to the `Table 1 column` \(example: `Name`).

  * Choose `Map Selected Columns`

  * You will be prompted to choose how to merge the columns: `Join, Sum or Average`

  * Choose `Join`

  * Choose `Submit`

![](https://lh5.googleusercontent.com/O0nzP6BW1XhcRavO6ovvqyx_5gZLzDIA0gIl20EG6x53jEmh7X3lpHqVsymssJ12PTbURT83agWuSI9FdCDKLgPMeiKGEYKaMEuLPRLwAjEEfaVamGyLKWg8Ib-I51DO-jupsvnf)

#### Append rows from two datasets

Follow the [Merging steps](https://tola.hackpad.com/4.-Multiple-Tabs-in-your-GSheet-Currently-we-can-only-import-the-first-sheettab-in-your-GSheet.-BlUMTgJoO8v#:h=Merging-Table-and-Mapping-Colu) above 

In Step 2:

  * Map at least one column and choose `Map Selected Columns`

  * Select the `Table 1 column` \(example: `User ID`) you want to map

  * Next, Select the `Table 2 column` you want to map to the other column \(example: `User ID`).

  * Choose `Map Selected Columns`

  * Choose `Submit`

  * Then choose the `Append` option to join the additional rows of data to your new dataset.

![](https://lh4.googleusercontent.com/Eouu57QO-g429zSTVaIKHCnoLRURWK9QerLKqWxRzw0A9MRNsQ23WmWVYh4mvBtHMmNe74Cdt61YTQhMumXDhlLU-N1cJJe2d1Y1u36poQZcDhfz8bMmHGNBkdIkZS7VmqR_vU1J)

  


