# CDJ Project: Economics/Public Policy, Social Security

CDJ Social Security Project (Economics/Public Policy)

Document Draft: https://docs.google.com/document/d/1FsSazChXf3dEOhyjQnCldxN5hucJfPn4H32vFxe8J3U/edit?usp=sharing

## Purpose of Project: 
To analyze current ongoing social security insolvency crisis and help readers understand the issue. Since this issue impacts all u.s. citizens, it is something that is worth analyzing. 

## Instruction for reproduction:
All source code, data, and figures are contained in the **/CDJ/Social_Security/For_WebDev_Editorial** folder for convinience.

On the google doc with our draft, each figure has a google doc comment with the **file path** of the file (ipynb) to reproduce that figure. For each code file, check code comments for the stpes. Every ipynb file should be runnable on a base environment, with the exception of the file named below.

Installation instructions (for socialsecurity_3dchloropleth_effectofcrisis.ipynb file)
For the socialsecurity_3dchloropleth_effectofcrisis.ipynb file, import the geoconda environment using the geoconda.yaml file. Then run jupyter notebook and run the file. 
To generate the different maps by agi stub, change the tax bracket variable and the monetary range variable.  Here's a table of the revenues with the matching agi stub:
| Stub | Range           |
|------|-----------------------------|
| 2    | $1 under $10,000            |
| 3    | $10,000 under $25,000       |
| 4    | $25,000 under $50,000       |
| 5    | $50,000 under $75,000       |
| 6    | $75,000 under $100,000      |
| 7    | $100,000 under $200,000     |
| 8    | $200,000 under $500,000     |



## Additional Notes 
- Current figure colors and styles are placeholders. Please, standardize Colors and Chart Styles of all plots. WebDev/Editorial can choose the color palette and style to use. Potentially something similar to NYT data visualization styles. 

- Standardize: 
Font
Title
X-axis label/ticks
Y-axis label/ticks
Legends/location
Gridlines
Style (e.g., line style, marker style, colors)
Axes (including scale and range)
Ticks
Background color
Plot area
Border
Etc. etc. NOT LIMITED TO THE ABOVE
