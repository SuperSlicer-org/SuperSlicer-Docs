---
title: Print Notes
description: SuperSlicer print notes
---

# Notes

## Notes
![Image Notes](assets/notes_dark.png)

| Parameter | Parameter Name | Parameter CLI flag | Description                                                                                  | Default Value |
| --------- | -------------- | ------------------ | -------------------------------------------------------------------------------------------- | ------------- |
| Notes     | notes          | --notes            | Here you can put your personal notes. This text will be added to the G-code header comments. | default: ""   |

## Custom Variables
![Image Notes](assets/custom_variables_dark.png)
For usage examples see [Using custom variables](/advanced-usage-guides/using-custom-variables)

| Parameter        | Parameter Name         | Parameter CLI flag       | Description                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | Default Value |
| ---------------- | ---------------------- | ------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------- |
| Custom variables | print_custom_variables | --print-custom-variables | You can add data accessible to custom-gcode macros. Each line can define one variable. The format is 'variable_name=value'. the variable name should only have [a-zA-Z0-9] characters or ''. A value that can be parsed as a int or float will be avaible as a numeric value. A value that is enclosed by double-quotes will be available as a string (without the quotes) A value that only takes values as 'true' or 'false' will be a boolean) Every other value will be parsed as a string as-is. Advice: before using a variable, it's safer to use the function 'default_XXX(variable_name, default_value)' (enclosed in bracket as it's a script) in case it's not set. You can replace XXX by 'int' 'bool' 'double' 'string'. | default: ""   |
