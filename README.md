CUSMART is a collection of exact string matching algorithms implemented in CUDA C/C++. This project is inspired by another great project called SMART by Simone Faro and Thierry Lecroq which is also included for the CPU benchmarks.

Our aim is to improve the performance of notable string matching algorithms by leveraging GPGPU architecture features and create a toolkit to test, design, evaluate and understand the existing solutions for the exact string matching problem.

The project is still under active development.

## How to compile it from source?
There are build scripts under "scripts" folder for Linux and Windows platforms. You need Cmake v3.9 or later and CUDA v6.0 or later to compile the project.

## List of Implemented Algorithms

There are around 85 algorithms implemented so far.
Many are getting added as the development continues.

| Name                                                        | Code      | Year |
|-------------------------------------------------------------|-----------|------|
| Brute Force                                                 | bf        |      |
| Deterministic Finite Automaton                              | aut       |      |
| Morris Pratt                                                | mp        | 1970 |
| Knuth Morris-Pratt                                          | kmp       | 1977 |
| Boyer Moore                                                 | bm        | 1977 |
| Horspool                                                    | hor       | 1980 |
| Apostolico Giancarlo                                        | ag        | 1986 |
| Karp Rabin                                                  | kr        | 1987 |
| Zhu Takaoka                                                 | zt        | 1987 |
| Optimal Mismatch                                            | om        | 1990 |
| Maximal Shift                                               | ms        | 1990 |
| Quick Search                                                | qs        | 1990 |
| Apostolico Crochemore                                       | ac        | 1991 |
| Two Way                                                     | tw        | 1991 |
| Tuned Boyer Moore                                           | tunedbm   | 1991 |
| Colussi                                                     | col       | 1991 |
| Smith                                                       | smith     | 1991 |
| Galil Giancarlo                                             | gg        | 1992 |
| Raita                                                       | raita     | 1992 |
| String Matching on Ordered Alphabet                         | smoa      | 1992 |
| Reverse Factor                                              | rf        | 1992 |
| Shift Or                                                    | so        | 1992 |
| Shift And                                                   | sa        | 1992 |
| Not So Naive                                                | nsn       | 1993 |
| Simon                                                       | simon     | 1993 |
| Turbo Boyer Moore                                           | tbm       | 1994 |
| Reverse Colussi                                             | rcol      | 1994 |
| Turbo Reverse Factor                                        | trf       | 1994 |
| Forward DAWG Matching                                       | fdm       | 1994 |
| Backward DAWG Matching                                      | bdm       | 1994 |
| Skip Search                                                 | skip      | 1998 |
| KMP Skip Search                                             | kmpskip   | 1998 |
| Backward Nondeterministic DAWG Matching                     | bndml     | 1998 |
| Berry Ravindran                                             | br        | 1999 |
| Backward Oracle Matching                                    | bom       | 1999 |
| Double Forward DAWG Matching                                | dfdm      | 2000 |
| Ahmed Kaykobad Chowdhury                                    | akc       | 2003 |
| Fast Search                                                 | fs        | 2003 |
| Simplified Backward Nondeterministic DAWG Matching          | sbndm     | 2003 |
| Two-Way Nondeterministic DAWG Matching                      | tndm      | 2003 |
| Backward Nondeterministic DAWG Matching for long patterns   | lbndm     | 2003 |
| Shift Vector Matching                                       | svm0      | 2003 |
| Forward Fast Search                                         | ffs       | 2004 |
| Backward Fast Search, Fast Boyer Moore                      | bfs       | 2004 |
| Tailed Substring                                            | ts        | 2004 |
| SSABS                                                       | ssabs     | 2004 |
| Wide Window                                                 | ww        | 2005 |
| Linear DAWG Matching                                        | ldm       | 2005 |
| Backward Nondeterministic DAWG Matching with loop unrolling | bndmq2    | 2005 |
| Simplified BNDM with loop unrolling                         | sbndm2    | 2005 |
| Backward Nondeterministic DAWG Matching with Horspool Shift | sbndm-bmh | 2005 |
| Horspool with BNDM test                                     | bmh-sbndm | 2005 |
| Forward Nondeterministic DAWG Matching                      | fndm      | 2005 |
| Bitparallel Wide Window                                     | bww       | 2005 |
| Fast Average Optimal Shift Or                               | faoso2    | 2005 |
| Average Optimal Shift Or                                    | aoso2     | 2005 |
| TVSBS                                                       | tvsbs     | 2006 |
| Boyer Moore Horspoolusing Probabilities                     | pbmh      | 2006 |
| Improved Linear DAWG Matching                               | ildm1     | 2006 |
| Improved Linear DAWG Matching 2                             | ildm2     | 2006 |
| Franek Jennings Smyth                                       | fjs       | 2007 |
| Two Sliding Window                                          | tsw       | 2008 |
| Extended Backward Oracle Matching                           | ebom      | 2009 |
| Forward Backward Oracle Matching                            | fbom      | 2009 |
| Simplified Extended Backward Oracle Matching                | sebom     | 2009 |
| Simplified Forward Backward Oracle Matching                 | sfbom     | 2009 |
