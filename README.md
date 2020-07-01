# 42-Fillit
An algorithm that takes tetrominos and fit them together to make the smallest square possible.

Subject : [English](https://github.com/ssfar/42-Subjects.pdf/blob/master/fillit.en.pdf) - [Français](https://github.com/ssfar/42-Subjects.pdf/blob/master/fillit.fr.pdf)

## Installation
#### Pre required : make and gcc 

First open a terminal and clone the project (git required) : 
```
git clone https://github.com/ssfar/42-Fillit.git
```
Or [donwload](https://github.com/ssfar/42-Fillit/archive/master.zip) and extract it.

Then go into the project folder via a terminal :

```
cd Fillit
```
and compile it by typing :

```
make
```

## How to use

### Input

Execute the program whit a valid tetromino file as first argument :
```
./fillit valid_file
```
Some valid examples files are given into ``` valid_samples ``` folder.

A valid tetromino is made out of 4 jointed blocks represented by '#' characters inside a 4 by 4 square field of '.' characters.  
#### A few exemples of valid descriptions of Tetrominos

![vt](https://user-images.githubusercontent.com/45463065/86272939-b22adf80-bbcf-11ea-9b2a-a31a990aff8b.PNG)

A valid tetromino file contain 1 to 26 tetrominos separated by a newline (the file must be in unix file format without an ending newline).  
(For more informations read the subject).



### Output

The program give the solution square into the terminal via the standard output, each different letters represent a tetrimino.
#### Here is an exemple of the program output 
![a](https://user-images.githubusercontent.com/45463065/86276737-ba861900-bbd5-11ea-8cbe-3bfb02c4d6b3.jpg)

If the input file is not valid, the program will simply output "error"