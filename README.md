# Curriculum Vitae

This is my personal Curriculum Vitae. Feel free to take everything in this repo

## File structure

```
.
+-- mcdowellcv.cls
+-- resume.tex
+-- .github/workflows
|   +-- build.yml
+-- resume.pdf
+-- resume-1.png

```

1. mcdowellcv - Cls file containing all the formating for the latex file.
2. resume.tex - Latex file where my resume is written.
3. build.yml - Contains the Github action to generate a new PDF and a new resume-1.png everytime something is pushed into Github.
4. resume.pdf - My resume compiled into PDF.
5. resume-1.png - My resume in PNG generated from PDF. This is used in my personal [website](http://goncalves-diogo.me).

## Usage

In order to use this template follow these steps.

1. Fork the repository into your own repository.
2. Change the content of the resume.tex for your own.
3. Push the code into Github and everything should work out of the box.

(NOTE: In case you wish to generate resume-1.png you may need to remove it manually, still working on it)


## Contributing

In order to contribute to this repo follow these steps.

1. Fork the repository into your own repository.
2. Make the changes you consider relevant.
3. Create a Pull-request. I will review it and approve it.

## McDowell CV
McDowell CV is a LuaLaTeX class for building neat and space-efficient CVs using the design originally proposed by Gayle L. McDowell at
http://www.careercup.com/resume
