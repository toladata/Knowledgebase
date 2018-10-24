****
# Design a Form
---

Data collection forms can be created directly on the TolaData platform or integrated from other data collection tools directly to Track. Read more about how to do it in [Import Datasets](https://help.toladata.com/en/track/import-datasets.html) article on the Knowledge Base.

### Build your form 

Select `Form Library` on the Navigation Bar and hit the orange `+` button. 

![](/assets_en/add_form.PNG)

Then `Add Field` to add questions to your form. You will be able to use validation rules or set up skip logic to make it easier for your enumerators to collect data and best ensure data quality.

> **Quick Tip:** Remember! You won't be able to change a form that has been already used for data collection.

#### Choose suitable question types
Choose from a wide range of available question types:

![](/assets_en/form_fields.PNG)

> **Quick Tip:** **Field name** is how your data column header will be called in your data table in Track, while **Field label** is the question that anyone who will be collecting data with your form will see. 

| Field type | Description |
| :--- | :--- |
| number | Number input |
| text | Free text response |
| email | Email input |
| url | Webpage URL or link input |
| date | Date input |
| dropdown | Multiple choice question; multiple answers can be selected |
| cascading dropdown | Sequence of dependent multiple choice question; multiple answers can be selected for each |

TolaData will only allow for a specified data type (e.g. text, date or number) input in response to a question. Providing ready answers in a **dropdown** is a way to prevent typos, as only specified answer options will be available. Question type selector is an example of a dropdown menu. **Cascading dropdowns** are combined sets of dropdown menus, when specific options roll out based on previous answers. See an example below. 

Edit your **cascading dropdown** question:
![](/assets_en/casc1.PNG)

See it live:
![](/assets_en/casc.gif)

#### Data validation

Oftentimes you might expect answers to be in a specific range, e.g. it is unusual to have 15 or more siblings and you might want to prevent such an input. To do that, define the accepted range while creating your form.

![](/assets_en/val1.PNG)

After you `Publish` the form and open a `Webform`, you'll be notified every time you or your enumerators try to input a record out of the allowed range.

![](/assets_en/val2.PNG)

### Create a template

If you're going to use a similar form repeatedly across programs or projects, you might consider building a template. Create it once and simply `Clone`, rename and reuse every time you need to.

![](/assets_en/template.PNG)



  


