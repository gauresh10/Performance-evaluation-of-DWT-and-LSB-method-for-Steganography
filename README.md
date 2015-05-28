# Performance evaluation of DWT and LSB method for Steganography

===============================================
Data secrecy became a main concern in the recent period. Many new techniques are employed to hide the secret data in some or the other form. This method of hiding the data into another form is called as Steganography. Likely, an old term in Ancient Greek, Steganography is derived from steganos meaning “concealed” and graphein meaning “writing”. This paper emphasizes on the two major techniques employed in Steganography – Discrete Wavelet Transform and LSB Substitution. 


Steps:
------------------------------------------
1. Unzip the code file.
2. Open the LSB_METHOD.m or DWT_METHOD.m file in matlab.
3. Input the cover image and secret image of same size.
4. Press F5 to see the output.


Results:
---------------------------------------
Comparative analysis
![image](https://github.com/gauresh10/Performance-evaluation-of-DWT-and-LSB-method-for-Steganography/blob/master/IMAGES/results.PNG)

Conclusion:
-----------------------------------------------
In this paper, some commonly known steganography techniques were implemented. LSB substitution and DWT are widely used for the same. Each of the method has its own advantage. LSB method embedded about 60% of data bits and retained the same size of the image because only the pixels values were shuffled. In DWT method, the given data is decomposed to get uncorrelated data which changes the image composition. This operation affects the entire image and hence the reconstructed image is smaller in size. DWT method has high privacy and hides secret image very well. 

Paper Publication:
--------------------------------------------------
[PAPER](https://github.com/gauresh10/Performance-evaluation-of-DWT-and-LSB-method-for-Steganography/blob/master/PAPER/V5I3-0437.pdf)
