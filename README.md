# Guide for gathering HumDiv & HumVar datasets and matching AlphaFold structures

## 1) Download data from PolyPhen-2 website or 2) use the data from provided HumDiv_HumVar_sets directory

### 1) Download data from PolyPhen-2
go to `PolyPhen-2` website to gather the datasets:

```
http://genetics.bwh.harvard.edu/pph2/dokuwiki/downloads#datasets
```

scroll down to `Datasets`

![Screenshot](Pictures/Picture_1.png)

click `README` under the `File(s)` column for the first row

![Screenshot](Pictures/Picture_2.png)

Click `Open Finder.app` on Mac or `File Explorer` on Windows computer

![Screenshot](Pictures/Picture_3.png)

download and extract the files

### 2) Use data in HumDiv_HumVar_sets directory

open `humdiv-2011_12.deleterious.humdiv.output` file with `Microsoft Excel`

![Screenshot](Pictures/Picture_4.png)

Column `F` (acc) contains the `UniProt` ids

#### Example

Selected `UniProt` id is `P26439`

Go to `https://www.uniprot.org/`

and search for the id

![Screenshot](Pictures/Picture_5.png)

When you click enter it will go to the following page:

![Screenshot](Pictures/Picture_6.png)

Scroll all the way down to `Structure` heading

![Screenshot](Pictures/Picture_7.png)

![Screenshot](Pictures/Picture_8.png)

Select the `AlphaFold` structure from the `Yellow` highlighted panel and click the `Download` button on the right side between `AlphaFold <> Foldseek`
