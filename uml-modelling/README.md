# PlantUML

Examples for making UML type diagrams in PlantUML

## Installing PlantUML
Make sure you have the necessary PlantUML jar from [here](http://plantuml.com/download)

## Installing Java

Use Brew:

``` brew cask install java ```

If you don't have Brew installed check out instrustions [here](https://brew.sh/)

## Creating outputs
Outputs created as either PNG or PDF. Using the following scrips: 

``` java -jar plantuml.jar <input_plantUML_file> ```
* In order to create readable PNG outputs a line to define image size should be included: ```scale 4000*8000``` (or similar)

``` java -jar plantuml.jar -pdf <input_plantUML_file> ```
* Creating PDFs requires additional dependencies. These can be found for download here -- http://plantuml.com/pdf

## Examples! 

* [Box Diagram](./examples/box_diagram/connected_box_diagram.pdf)
* [Process Flow Diagram](./examples/process_diagram/example_process_diagram_CI.pdf)
* [Sequence Diagram](./examples/sequence_diagram/example_sequence_diagram.pdf)
* [Use Case Diagram](./examples/use_case_diagram/example_use_case_diagram.pdf)

## Web Examples!

* [Real World Plant UML](https://real-world-plantuml.com/)