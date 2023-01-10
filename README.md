# Latex Templates

This contains various templates specific to QUT and ACC that you may find useful. Please add your own. Each template should be contained in its own semantically meaningfully named folder. Each template should contain at least a `main.tex` and a PDF example, and if required a README to provide any special notes.

## Available Templates

- [Simple Technical Note](/simple_technical_note/) - basic lightweight template for producing simple technical notes.
- [Work Instruction](/work_instruction_/) - a template for producing work instructions (QUT Specific).
- [Compentency To Operate](/compentency_to_operate/) - a template for producing CTOs (QUT Specific).

## Auto Generation

A simple script has been provided (acc_latex_templates) to create your new document from the available templates. To use this script, see the below instructions:

1. Make the script executable with the following command:
```bash
chmod +x acc_latex_templates
```
2. Navigate to your desired folder, the script (when run) will prompt for the type of template you want (see Available Templates) and copy across all required files to the new destination. Note that the new destination is where the script is run (see example below)
```bash
# Make a folder for your document (assuming a simple technical note)
mkdir ~/test_technical_note

# Navigate to your destination folder
cd ~/test_technical_note

# Run the script from your desired destination folder (please replace <LOCATION OF THIS REPO> with the location of this cloned repository)
~/<LOCATION OF THIS REPO>/latex-templates/./acc_latex_templates
```