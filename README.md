# Claude tool:
https://jhtcode.github.io/Specimen-Screening-Tool/donor_automation_tool.html

# Gemini tool:
https://jhtcode.github.io/Specimen-Screening-Tool/gemini_auto_screen.html

This is a tool to screen potential donors 

## Instruction
### Claude
insert this prompt and upload the donor summary into AI model to extract the fields:
I am uploading a new donor PDF. Please extract all fields and screening data in this exact JSON format: {"tissueBank":"","donorId":"","age":"","gender":"","heightIn":"","weightLbs":"","bmi":"","race":"","location":"","cod":"","medHistory":"","serology":"","osteoCount":"","structuralMalformation":""}

copy the json output into the donor_automation_tool input

### Gemini
just put in the PDF and API key from GOOGLE AI Studio
