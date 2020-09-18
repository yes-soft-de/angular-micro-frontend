# Micro Frontend Example Using Angular Elements
This is a small example of how micro frontend works with angular and how will be displayed and how does the structure for angular micro frontend components will be.


## Collect all micro frontend components :
After creating ou workspace in angular and create a separate application for every micro frontend inside that workspace and after build all our applications we have been created, we follow these steps :
- Collect all application build folders in one folder called for instance as `apps` .
- Collect all micro frontend components in `index.html` file with the script file for every micro frontend application we created with angular


### Notes : I have just tested the following in this example :
- Passing String in one micro front application (mainApp)
- Use route inside one micro front application (sideApp)
- Passing data between two micro frontend using `click event` (subApp and mainApp)