# Distributed Ledger Technology Exploration Demo

| Filename    | SHA-256 Checksum                                                 |
|-------------|------------------------------------------------------------------|
| genesis.csv | 342ef4107a985b08a0be64a743b022b96a93ff825de830426025b92cbacce74a |
| day1.csv    | 0757176e05fc9b4588021dd468579a4176539e3c637fe44e0f7b32328d48dfc0 |
| day2.csv    | aabf48872b7db3c2c830d7c803bbadda9b2001d0a307602113f56c137d8c11fc |
| day3.csv    | ae67c000c1a7e364787bc2e99a48b2b6051464872316659df48633875856df07 |


## Compute the hash value for a file

Windows Powershell:
```Powershell
Get-FileHash genesis.csv | Format-List

Algorithm : SHA256
Hash      : 342ef4107a985b08a0be64a743b022b96a93ff825de830426025b92cbacce74a
Path      : C:\Users\username\Downloads\dlt_demo\genesis.csv
```

Linux Shell & MacOS Terminal
```shell
shasum -a 256 genesis.csv

342ef4107a985b08a0be64a743b022b96a93ff825de830426025b92cbacce74a  genesis.csv
```
