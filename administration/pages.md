# Pages

OneBody ships with a boilerplate text for static pages on your site. Select the *Pages* button from the administration dashboard to access the pages you can update.

![pages-1](../img/admin/pages-1.png)

You can update these pages within OneBody using the provided in-place text editor. Select the article that you want to update by clicking the name.

![pages-1](../img/admin/pages-2.png)

Save and view the page you just created by using the buttons at the bottom of the page.

### Inserting dynamic fields from OneBody

You can also insert selected values from fields from Onebody into your page text.The table below shows the text you can insert:

| Tab | Field |
| -- | -- |
| Contact | Bug Notification Email |
| Contact | Tech Support Email |
| Contact | Send Updates To |
| Contact | Community Address |
| Contact | Send Email Changes To |
| Contact | Community Office Phone |
| Contact | Community Email |
| Name | Site |
| Name | Community |
| System | Time Zone |
| System | Adult Age |
| URL | Site |
| URL | Visitor |



## Formatting the text

To insert the text held in the field, wrap the *tab* and *field* columns from the table above with brackets, and break with a pipe the middle. Replace spaces for underscores "_" for any field that has multiple words.

The format is: [[Tab|Field]]

To show:
* the name of the site: [[name|site]]
* the Tech Support Email:[[contact|tech_support_email]]
* the Adult Age:[[system|adult_age]]

> **note** all field and tabs must be **lowercase**.
