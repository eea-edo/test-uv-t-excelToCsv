### Description

Transformer for Excel files (.XLS, .XLSX) which well extract selected sheet (or sheets) into CSV file. 

### Configuration parameters

| Name | Description |
|:----|:----|
|**Sheet names** | Sheet names separated by colon that will be transoformed to CSV file. Sheet names are case insensitive. If sheet names is not specified then all sheets are transformed to csv.|
|**CSV file name pattern** | Pattern used to create name of generated CSV file.|

### Inputs and outputs

|Name |Type | DataUnit | Description | Mandatory |
|:--------|:------:|:------:|:-------------|:---------------------:|
|input |i |FilesDataUnit |Input files |x|
|output |o |FilesDataUnit |Produced CSV files |x|
