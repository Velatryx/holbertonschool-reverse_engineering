
1. enumerate list of sections

In this task, you are asked to analyze a binary file and identify the sections it uses. Specifically, you need to focus on an unusual section and determine its size.

Steps

1- Identify the Sections in the Binary.

2- Use the readelf command to list all sections of the ELF file. This command will show you the different sections that make up the binary. Optionally, use objdump to accomplish the same result.

3- Obtain the Size of the Unusual Section.

4- Once the unusual section is identified, obtain its size from the output of the readelf command.

Expected Files

    size.txt: Contains the size of the unusual section.
    command.txt: Contains the command used to list the sections and identify the size of the unusual section.

NOTE: If you used objdump instead of readelf, you should provide the command to show only the details of the unusual section (using the short option syntax).

downlaod the file from here:

target_binary for task 1`

Repo:

    GitHub repository: holbertonschool-reverse_engineering
    Directory: re_fundamentals
    File: size.txt, command.txt

