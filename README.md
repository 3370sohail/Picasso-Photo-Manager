# Picasso-Photo-Manager
Picasso Photo Manager is a photo tagging photo managing software that allows user to rename photos. 
The front-end is done with a JavaFX framework, the backend is done with Java and data is persisted 
through a local SQLite database. 

INSTRUCTIONS ON OPENING THE PROGRAM FROM THE COMMAND LINE
==========================================================
1) cd to the project directory

2) Run the appropriate command

Unix Shell Script (CDF Labs)
============================
gradlew run

Windows Batch File
==================
gradlew.bat run

Sometimes file permissions have 
issues on some OSs like Macs.
===============================
sh gradlew run

----------------------------------------------------------

INSTRUCTIONS ON CREATING NEW INTELLIJ PROJECT FROM SOURCE FILES
===============================================================
1) Import Project

2) From the project directory

    i) Select 'build.gradle'
    ii) Continue by clicking 'OK'

3) Continue by clicking 'OK'

4) Project SDK is not defined, open any java file under 'src/' directory.
   Click 'Setup SDK' to choose Java 1.8 as project SDK.

5) Before testing JUnit tests,

    i) Expand imports at the top of any of our test files,
    ii) Place cursor above the highlighted red word 'jupiter'
    iii) alt+enter and select "Add 'JUnit5' to class path".
    iv) press 'OK' to "use 'JUnit5' from IntelliJ IDEA distribution.

PROGRAM NOTES
==============
-   When adding tag in the “Image tab” or searching images by tag,
    User can seperate tags by ",".

-   User can add tags from the tag repo to the selected image by clicking 
    `on “<< Add Tag(s) to Image” button. Multiple can be selected by 
    holding ctrl down while selecting.

-   The textfield at the top of the program updates when user searches new 
    directory or clicks on an image (it will display the image’s parent directory).

-   User can hover over root name, tags, and the absolute path in the 
    “Image” tab to see the whole text.
