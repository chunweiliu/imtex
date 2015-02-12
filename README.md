# CBIR
A Content-based image retrieval using visual and textual features

## Prerequisites for the system
1. OpenCV (v3.0, built from the source code)
2. Boost (the latest version download from Homebrew)
3. CMake

## Image features

## Text features
1. Build a Lexicon
The top 20 words in the description of files are:

        3393 [a]
        3220 [and]
        2586 [with]
        2382 [the]
        1297 [;]
        1212 [leather]
        1185 [of]
        1058 [in]
        1013 [The]
        1004 [for]
         980 [to]
         872 [your]
         836 [-]
         811 [from]
         764 [is]
         646 [This]
         520 [A]
         494 [clutch]
         488 [Leather]
         432 [features]

The good words for lexicon are "leather", "clutch", "Leather", and "features".
## Log
1. 01/29/2015 Install OpenCV
2. 02/04/2015 Commit ImageRetrieval v1.0