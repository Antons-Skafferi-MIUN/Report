# Report
https://dahlgren.miun.se/rapportmall/

The report will be written in LibreOffice / OpenOffice.
# Install the correct fonts.
The template provided by Miun uses FreeSans and FreeSerif. Make sure your version of Libreoffice has these installed. 
You can easily check these by typing in "FreeSans" as the font name in Libreoffice. If you do not get auto complete you don't have the font installed.
For Linux distributions using pacman this is solved by sudo pacman -S gnu-free-fonts.

## Naming convention
/[subject]/[name]_[subject].odt

/theory/viktor_theory.odt

[Referensguide for Vancouver](https://tools.kib.ki.se/referensguide/vancouver-en/)  
Language: English  
# Heading nr 1, font FreeSans,  font-size: 22
## Heading nr 2, font FreeSans,  font-size: 14
### Heading nr 3, font FreeSans,  font-size: 12
Textbody,     font FreeSerif, font-size: 12  
Code,    font Source Code Pro Medium, font-size: 10

[Repo for Source Code Pro](https://github.com/adobe-fonts/source-code-pro)

## Page size and margins:
It's highly recommended to use the same page size and margins that the report template uses,
so that there are no formatting issues when your texts are being incorporated into the main project report.
In order to edit the necessary values in libreoffice to achieve this;
Right-click the document you are writing, and click on "Page...".
In this window under "Paper format", make sure that "A4" is selected in the dropdown table, and that the
"Width" is = 8.27", and "Height" is = 11.69".

Then under "Margins", make sure you have the following values for the margins:
"Left" = 1.46"
"Right" = 1.46"
"Top" = 0.79"
"Bottom" = 0.53"

## Text Box Style:
* Line Style: Continuous
* Line Width: 0,00cm
* Area Style: Color
* Fill Color: Light Grey 5

## Text Box Padding:
Format, Text Box and Shape, Text Attributes...

Spacing to Border:   0,30cm (all categories)

# Assigned tasks
Below is the responsibilities for writing parts of the report.
Send to Lukas when done.

## Labs
https://w3.miun.se/dt170g/lab/  

* Anders,David,Joakim, and Sandra lab 1
* Jonathan, Malik,Lukas,Mattias Rosen lab 2
* Mikael, Maria, Simon och Viktor lab 3

# Adding a dictionary to LibreOffice
1. [Download and launch](https://extensions.libreoffice.org/extensions/english-dictionaries/2020-02.01/@@download/file/dict-en-20200201.oxt) 
3. Restart LibreOffice

# Code highlighting in LibreOffice

## Installation
1. Close LibreOffice
2. Install python3
3. sudo pip3 install pygments
4. [Download and launch](https://extensions.libreoffice.org/extensions/code-highlighter/1.6/@@download/file/codehighlighter.oxt)

## Usage
1. Insert a new Text Box (Insert -> Text Box) 
   Copy and paste/write your code snippet into the text box (You can choose any fonts based on your preference)
2. Select the text box
3. Go to Tools -> Highlight Code -> Language: Java, Style: autumn


[Further instructions](https://extensions.libreoffice.org/extensions/code-highlighter)


