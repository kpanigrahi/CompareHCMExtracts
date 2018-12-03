# Compare HCM Extracts
Compares different versions of HCM Extracts

## Getting started
We use HCM Extracts to extract data from Oracle HCM Cloud application. When we try to migrate the HCM Extract from one environment to the other, we would need a tool to compare the current/existing HCM Extract with the new one. For this reason I developed this tool which will help user to compare two versions of HCM Extract.

### command to execute
`compareHCMExtract <source fsm package name .zip> <target fsm package name .zip> <output file name .html>`

The program generates .html file using which we can actually see the differences between the two versions of the same HCM Extract.

The below will be applied in the next version
~~compareHCMExtract -s <source fsm package name.zip> -t <target fsm package name .zip> -o <HTML> -f <output file name .html>~~

## Prerequisites
- Create FSM package for HCM Extract
First create a FSM package for the HCM Extract by going to:
    Setup and Mainteance -> Manage Implementation Projects
Create a new project and then download the FSM package by going to:
    Manage Configuration Pacakges
Note: This step is required only if you are trying to compare two HCM Extracts that are generated using FSM package.

## Installing
Just execute the .exe file with the parameters mentioned in "command to execute" section and it should generate the required output in .html file.

## Running the tests
How to execute the test cases

## Built with
Right now I am planning to use golang, but if there are any other technology that are being used to complete this software, then I will make sure that I include all the details in this section.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## Authors
Kiran Panigrahi - panigrahi.kiran@gmail.com

## License
This software is licensed under MIT, for more details please read the LICENSE file.