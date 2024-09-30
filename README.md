## StackSpot Plugin

## Jinja

You can use jinja to make a template-data folder more dynamic.

complete documentation of jinja: https://jinja.palletsprojects.com/en/3.0.x/templates/

### Example Inputs:
- Resource: 
- Method:   full_name_comp: "julio souza"
  full_name_uppercase_comp: "{{FULL_NAME_COMP}}"
  full_name_formatted_comp: "{{Full_name_comp}}"
  welcome_message_comp: "Welcome {{full_name_formatted_comp}}"
  goodbye_message_comp: "Goodbye {{full_name_formatted_comp}}"