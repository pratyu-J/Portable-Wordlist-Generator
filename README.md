# Portable-Wordlist-Generator
Portable-Wordlist-Creator is an application that creates a wordlist, with a million, billions of words, with a tremendous size of hundreds of GBs, to a very compact size. This Application not only compresses the file but also successfully and efficiently decompresses it.


We have divided our model into two parts to achieve this:

1) Compression

    • We have set a threshold for the number of words in a text file.
    
    • On generating words in the file, once the threshold is achieved, the text file is then compressed, simultaneous to it, the generation switches to another file, and the cycle goes on till the complete wordlist is obtained.
    
    • Once the complete wordlist is obtained, all the compressed files are then compressed together into a single compressed file.
 2) De-Compression
 
    • According to the user need the model decompresses a file, uses it to compare to the target, if the desired result is not found, re-compresses it, sequentially de-compresses the next file, and the cycle goes on till the desired target is achieved or wordlist ends.
    
    