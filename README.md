# nmr-dataset1


## Preparing and uploading data

Each dataset corresponding to one molecule is stored in a folder that has as name the cas number of the product.

In this folder we will find the corresponding jcamps as well as a file `structure.mol` that contains the molfile of the chemical structure.

- 13c.dx
- 13c.fid.dx
- 1h.dx
- 1h.fid.dx
- cosy.dx
- cosy.ser.dx
- dept135.dx
- dept135.fid.dx
- hmbc.dx
- hmbc.ser.dx
- hsqced.dx
- hsqced.ser.dx
- structure.mol

In order to export property the data from topspin the following settings should be used:

Select 'save data set ain a JCAMP-DX file'. The most space-saving option (type of archive file) is JCAMP DIFF/DUP. To only store the FID, change the content of the field 'Included these data types' to FID. 
