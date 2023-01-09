[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-c66648af7eb3fe8bc4f294546bfd86ef473780cde1dea487d3c4ff354943c9ae.svg)](https://classroom.github.com/online_ide?assignment_repo_id=9703419&assignment_repo_type=AssignmentRepo)

# 開源程式的使用

##### Data Structure Assignment 4
##### 通訊二110503504林巧翎


## Introduction

根據兩種不同壓縮演算法 (Arithemtic Coding, Huffman Coding) 的開源程式，比較與分析兩種演算法的性能

## Compile and excute

####  Arithemtic Coding 

在compare資料夾 
```
cd arcd-master
cd examples
```
compile
```
make
```
excute

壓縮
```
./arcd_stream -e < input.file | tee output.file
```
解壓縮
```
./arcd_stream -d < input.file | tee output.file
```

#### Huffman Coding
在compare資料夾

```
cd huffman-main
```
compile
```
make
```
execute
壓縮
```
./huffcode -i input.file -o output.file -c
```
解壓縮
```
./huffcode -i input.file -o output.file -d
```

## 使用者說明
照上面的Compile and excute指示

將input.file和output.file改成自己想要的檔名

就能分別壓縮與解壓縮檔案

並且在最下方顯示執行時間