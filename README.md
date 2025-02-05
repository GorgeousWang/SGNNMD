# fork notes
The datasets were derived from the following sources in the public domain, the miRNA-disease association from https://www.cuilab.cn/hmdd, the disease MeSH descriptors from https://meshb.nlm.nih.gov/ and the gene functional interaction network is downloaded from https://www.inetbio.org/humannet/download.php. 

At last, we construct the benchmark dataset with 4264 miRNA- disease associations between 348 miRNAs and 210 diseases, including 2284 up-regulation and 1980 down- regulation associations.

# SGNNMD
SGNNMD: Signed Graph Neural Network for Predicting Deregulation Types of MiRNA-disease Associations
## Run
```shell
python main.py -i ./data/m_d.csv -m ./data/m_m.csv -d ./data/d_d.csv -e 20 -s 44
```
## Dependences
```text
Package                 Version
----------------------- ----------
matplotlib              3.4.3
networkx                2.6.2
numpy                   1.19.5
pandas                  1.3.3
pip                     21.2.4
scipy                   1.7.1
setuptools              56.0.0
six                     1.15.0
wheel                   0.37.0
```
