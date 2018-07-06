# 3. Preferences

In the module preferences you can set various options for this module:<br/>

![](.gitbook/assets/3preferences.png)

## 3.1 Options in detail
#### Keywords
You can add keywords, which are added to the meta tags. Seperate the keywords by comma.

#### Admin pager
You can define the number of items for lists in admin area.

#### User pager
You can define the number of items for lists in user area.

#### Start page
Define, what should be shown when calling the module (index.php)
You have following options:
* An overview with all teams (but without members)
* All teams with all members
* The first team

#### Editor
You can decide, which editor should be used for editing on admin sides.
Xoops offers by default 3 editors:
###### 1) onlyText
This editor can be used for saving pure text
###### 2) DHTML with xCode
An Editor with various Xoops-Tags
###### 3) TinyMCE
Extended texteditor with a lot of options for formatting, lists, and so on.
The text will be save as HTML-Code in your database.

Attention: if you display text, which is created with TinyMCE, diplay later with e.g. the DHTML-Editor, you will see all the Html-Tags. Please use in this case again TinyMCE or remove all HTML-Tags.

#### Max size
Please define the maximum file size foruploads file. You have to enter the value for bytes (10485760 = 1 MB).

#### Mime-Types
Define which mime-types are allowed for file upload.

#### Show labels
Please decide, whether there should be a label before the information, e.g. before the name the label 'first and last name' will be shown on user sides. If you select 'No', only the name himself, the phone number himself an so one will be shown.

#### Show breadcrumbs-navigation
Please decide, whether a breadcrumbs-navigation should be shown on user sides.
