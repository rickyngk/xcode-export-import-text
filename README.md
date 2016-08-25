# XCode exporting/importing text (strings file) tool
Export all localization texts of XCode project to excel then import again after correcting 

**DISCLAIMER:** This project is a side project for specific purpose, so I did not optimize yet. Use it at your own risk!

## Requirement:
- Python 2.7
- xlsxwriter: http://xlsxwriter.readthedocs.io/
- xlrd: https://pypi.python.org/pypi/xlrd

## Export to excel
- Update path in export-text.py: `os.walk('./')`
- Run: `python export-text.py`

## Import from excel
- **IMPORTANT**: always backup your project before running this script
- Use result of exporting process `lang.xlsx`
- Correct your copy as need
- Update path in import-text.py: `os.walk('./')`
- Run: `python import-text.py`
