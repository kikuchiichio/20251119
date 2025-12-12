This repositry contains the scripts to generate algenraic quantum error correction codes. 
The details are describe in the preprint article from which you visited here.

You need to install Singular package. Then you can process the script by Singular:

>>>> Singular < MyLIB3.txt >MyLIB3.out.txt

The matrix data written in MyLIB3.out.text must be converted as a QECC. 

To this end, the author converted the text data of matrices into matrices of Sympy and constructed the QECC.
The necessary item is a short Python program written in WriteAsLatexMath.ipynb.
