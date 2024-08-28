NameSorter

NameSorter is a Java application designed to read names from a file, sort them alphabetically, and remove any duplicates. The application processes each line of the file to output both the original and the processed list of names.
Features

    Read Names: Reads names from a file.
    Remove Duplicates: Eliminates duplicate names.
    Sort Names: Sorts names in alphabetical order.
    Display Results: Prints both the original and processed lists of names.

Getting Started

To get started with NameSorter, follow these steps:
Prerequisites

    Java Development Kit (JDK) 8 or later.
    A file named names.dat containing names separated by spaces.

Installation

    Clone the Repository:

    bash

git clone https://github.com/yourusername/NameSorter.git

Navigate to the Project Directory:

bash

cd NameSorter

Compile the Java Program:

bash

    javac NameReader.java

    Create or Place the names.dat File:

    Ensure names.dat is in the same directory as the compiled NameReader.class file.

Usage

    Run the Program:

    bash

    java NameReader

    Output:

    The program will print the original list of names followed by the sorted and deduplicated list for each line in the names.dat file.

Example

Given the names.dat file with the following content:

Alice Bob Alice Charlie Bob
Dave Eve Charlie Alice

The output will be:

Alice Bob Alice Charlie Bob 
Alice Bob Charlie 

Dave Eve Charlie Alice 
Alice Charlie Dave Eve 

Contributing

If you'd like to contribute to NameSorter, follow these steps:

    Fork the repository.
    Create a new branch (git checkout -b feature-branch).
    Commit your changes (git commit -am 'Add new feature').
    Push to the branch (git push origin feature-branch).
    Create a new Pull Request.
