# docking_extractor.py

## 概要
Program to extract docking snapshots from pdbqt file generated from autodock or vina.


## 使用方法
```sh
$docking_extractor.py [-h] -i STRUCTURE.pdbqt -f STRUCTURE_NUMBER [STRUCTURE_NUMBER ...] -o OUTPUT.pdb [-O]
```

* `-h`, `--help`
	: show this help message and exit
* `-i STRUCTURE.pdbqt`
	: docking snapshots file
* `-f STRUCTURE_NUMBER [STRUCTURE_NUMBER ...]`
	: snapshot number to be extracted
* `-o OUTPUT.pdb`
	: output structure file
* `-O`
	: overwrite forcibly


## 動作要件
* Python3


## License
The MIT License (MIT)

Copyright (c) 2022 Tatsuya Ohyama


## Authors
* Tatsuya Ohyama


## ChangeLog
### Ver. 1.0 (2022-10-26)
* Released
