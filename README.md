# TopLD API

This is the execution code for TOPLD API.



## Usage
```
git clone https://github.com/linnabrown/topld_api.git
cd topld_api
./topld_api -thres 0.8 -pop AFR -maf 0.01 -inFile input.txt -outputLD outputLD.txt -outputInfo outputInfo.txt
```
### Prameters

```
-inFile string
        The file path of query markers. Seperated by \n. Default=input.txt  (default "input.txt")
-maf string
        The minimum value for minor allele frequency for query and LD proxy. Default=0.01. (default "0.01")
-outputInfo string
        The file path of output file for query info. Default=outputInfo.txt (default "outputInfo.txt")
-outputLD string
        The file path of output file for LD. Default = outputLD.txt (default "outputLD.txt")
-pop string
        Population for SNP in LD. You can input on of 4 populations (AFR, SAS, EAS, and EUR). Default=AFR. (default "AFR")
-thres string
        R2 threshold. Default=0.8. (default "0.8")
```

## Commit History

[![Commit History Chart](https://commit-history-api.herokuapp.com/svg?repos=linnabrown/topld_api&type=Date)](https://the-commit-history.vercel.app/#linnabrown/topld_api&Date)