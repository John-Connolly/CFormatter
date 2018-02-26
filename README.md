# CFormatter


### Before
<p align="center">
	
    <img src="https://user-images.githubusercontent.com/8390081/36652685-8f44b23a-1a86-11e8-9fcc-6500f6044bbd.png"  alt="">
   
  </p>

### After
<p align="center">
	
    <img src="https://user-images.githubusercontent.com/8390081/36652682-8d0dd2f8-1a86-11e8-8475-27c219951d4d.png"  alt="">
   
  </p>


## Install

Run ``sudo apt-get install clang-format-5.0`` in terminal

``git clone https://github.com/John-Connolly/CFormatter.git``
Copy the contents of clang-format.txt into a file named ``.clang-format`` into the top most folder that your assignments are contained in. .clang-format is a hidden file so you might need to show hidden files in order to see it. 

```
.
├── Assignments
├── a1
│	 └── a1p1.c
│── a2
│   └── a2p1.c
└── .clang-format
```



## Usage

The -i flag will edit the file in place otherwise, the
result is written to the standard output.
``clang-format-5.0 style=file -i a5p2.c``


Instruction to integrate it with vim and emacs ``https://clang.llvm.org/docs/ClangFormat.html``