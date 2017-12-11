# OE Resource Manager

The `oe-resource-manager` component is a plugin to `oe-studio` and helps managing files required for rule engine.

## Navigating to Rule Manager and adding a new rule file

To navigate to rule manager, first Go to [oe-designer](http://localhost:3000/designer) and click on the Rule Manager icon as marked in the below image:

![Start Page][start-page]

you will be navigated to Rule Manager, now to add new rule file, click on `ADD RULE` button.

![Rule Manager][rule-manager-home]

A dialogue box will appear to select and upload file and to add scope. Upload the file by clicking on `Choose or drop files` or drop the file there.

![Upload File][upload-file]

Provide rule name and add scope ***if needed***, and save. To understand more about scope or personalisation, click [here](/guide/datapersonalization)

The file data will get posted in DecisionTable Model. 

![Upload Rule Config][upload-rule-config]

After save, the rule name will appear in left panel, you can click on that to see the rule and to evaluate sample data.

![Show Rule][show-rule]

To evaluate rule, you can provide sample data in payload section and evaluate it by clicking Evaluate button as shown below.

![Evaluate Rule][evaluate-rule]

If You want to re-upload or download rule file, use the buttons in top right corner as shown below.

![Re-Upload Download][reupload-download]

## How to use uploaded rule

These rules can be added to the model by addiing in ModelRule model.

[start-page]:  images/designer-home.PNG "Start Page"
[rule-manager-home]: images/rule-manager-home.PNG "Rule Manager"
[upload-file]:images/upload-file.PNG "Upload File"
[upload-rule-config]:images/add-rule-config.PNG "Upload Rule Config"
[show-rule]:images/show-rule.PNG "Show Rule"
[evaluate-rule]:images/evaluate-rule.PNG "Evaluate Rule"
[reupload-download]:images/reupload-download.PNG "Re-Upload Download"