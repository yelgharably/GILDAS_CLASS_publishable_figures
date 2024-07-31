# GILDAS_CLASS_publishable_figures
Python script designed to take in text files produced by GILDAS CLASS of radio astronomical observations and produce publishable figures from it automatically. 
This is for my fellow astrononmers :)

# Script Strucutre:
The script takes in text files produced by the sic output command in CLASS formatted in with two columns (velocity in km/s and intensity in K.) This script will be entering a directory the user specifies and should essentially do all the work by itself, assuming the text files are named as follow: "SOURCENAME_MOLECULE_TRANSITION.txt" ex: "IRAS05113+1347_HCN_32" for source IRAS05113+1347 with an observation of J=3-2 (IN THAT ORDER) of HCN. 

The script automatically detects source names, molecule observed, and transition level. It then puts all of that stuff on the plot automatically. NEAT, right? It'll also produce observations of the same source (but different molecules) in one subplot.

The script is very accesible and modifiable based on your needs. This should save you a lot of time in formatting plots for your papers.

Feel free to use the script in your research! Here are a few plots to show you what the script can produce:

![IRAS05113+1347](https://github.com/user-attachments/assets/3db2cf53-c0f6-4799-b6ad-8b809a3a1256)

![IRAS23321+6545](https://github.com/user-attachments/assets/5bf867c2-e273-4dc8-ab30-338409065ad8)



