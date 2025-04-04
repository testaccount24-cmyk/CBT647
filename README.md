# CBT647
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. GitHub repos will be deleted and created during this period...

```
//***FILE 647 is an XML parser written in REXX, from Andrew J.      *   FILE 647
//*           Armstrong.                                            *   FILE 647
//*                                                                 *   FILE 647
//*           email:  andrew_armstrong@unwired.com.au               *   FILE 647
//*                                                                 *   FILE 647
//*     NAME     - PARSEXML                                         *   FILE 647
//*                                                                 *   FILE 647
//*     TITLE    - A REXX XML PARSER                                *   FILE 647
//*                                                                 *   FILE 647
//*     VERSION  - 2.0.0                                            *   FILE 647
//*                                                                 *   FILE 647
//*     FUNCTION - This is a Rexx XML parser that you can           *   FILE 647
//*                append to your own Rexx source. You can then     *   FILE 647
//*                parse xml files into an in-memory model and      *   FILE 647
//*                access the model via a DOM-like API.             *   FILE 647
//*                                                                 *   FILE 647
//*                This version has been tested on TSO (using       *   FILE 647
//*                TSO/REXX) and on Win32 and Ubuntu Linux 6.06     *   FILE 647
//*                LTS (using Regina Rexx 3.3).                     *   FILE 647
//*                                                                 *   FILE 647
//*     MEMBERS  - The list of members in the distribution PDS      *   FILE 647
//*                are:                                             *   FILE 647
//*                                                                 *   FILE 647
//*                README    - This file.                           *   FILE 647
//*                ASSERT    - Unit test assertion plumbing.        *   FILE 647
//*                DEVISIO   - An example of removing unwanted      *   FILE 647
//*                            XML tags.                            *   FILE 647
//*                IDLFILE   - An example IDL input for for         *   FILE 647
//*                            IDL2WSDL rexx.                       *   FILE 647
//*                IDL2WSDL  - EntireX IDL to WSDL file converter.  *   FILE 647
//*                IO        - Basic Rexx I/O routines.             *   FILE 647
//*                JCL2XML   - JCL to XML and GraphML file converter*   FILE 647
//*                PARSEXML  - The Rexx parser source.              *   FILE 647
//*                PRETTY    - A pretty printer showing how to      *   FILE 647
//*                            use the parser.                      *   FILE 647
//*                REXXPP    - A Rexx INCLUDE pre-processor.        *   FILE 647
//*                SOAP      - A Rexx SOAP client.                  *   FILE 647
//*                TESTMOD   - Unit tests for XML modification API  *   FILE 647
//*                TESTNEW   - Unit tests for XML creation API      *   FILE 647
//*                TESTXML   - A sample xml file                    *   FILE 647
//*                                                                 *   FILE 647
//*     NOTES    - 1. The image files will have to be downloaded    *   FILE 647
//*                   to your PC in BINARY mode and renamed to:     *   FILE 647
//*                                                                 *   FILE 647
//*                     CARDPNG -> card.png                         *   FILE 647
//*                    PAPERPNG -> paper.png                        *   FILE 647
//*                   ...or, you can source your own images.        *   FILE 647
//*                                                                 *   FILE 647
//*     USAGE      - See the PARSEXML rexx procedure for more       *   FILE 647
//*                  information                                    *   FILE 647
//*                                                                 *   FILE 647
//*     AUTHOR     - Andrew J. Armstrong                            *   FILE 647
//*                  email:  <andrew_armstrong@unwired.com.au>      *   FILE 647
//*                                                                 *   FILE 647
//*     HISTORY                                                     *   FILE 647
//*     Date     By       Reason (most recent at the top pls)       *   FILE 647
//*     -------- -------- ------------------------------------      *   FILE 647
//*                                                                 *   FILE 647
//*     20051014 AJA      Version 1.7                               *   FILE 647
//*     20050610 AJA      Version 1.6                               *   FILE 647
//*     20040706 AJA      Added creation/modification support.      *   FILE 647
//*     20031216 AJA      Bugfix: _parseElement with no attrs       *   FILE 647
//*                       causes crash.                             *   FILE 647
//*     20031031 AJA      Correctly parse '/' in attributes.        *   FILE 647
//*                       Fixed entity resolution.                  *   FILE 647
//*     20030912 AJA      Bugfix: Initialize sXmlData first.        *   FILE 647
//*                       Bugfix: Correctly parse a naked '>'       *   FILE 647
//*                       present in an attribute value.            *   FILE 647
//*                       Enhancement: DUMP option now displays     *   FILE 647
//*                       first part of each text node.             *   FILE 647
//*     20030901 AJA      Initial version.                          *   FILE 647
//*                                                                 *   FILE 647
```
