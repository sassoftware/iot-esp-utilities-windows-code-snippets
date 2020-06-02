# ESP Utilities Windows Code Snippets

## Overview

This repository includes code snippets that you can execute for the Utilities windows of SAS Event Stream Processing (ESP). There is a directory for each example that contains all the files you need to execute the example. There is also a document for each code snippet to provide any instructions unique to the particular example.

The following sections list the examples and provide a description of each. You can click on the name of each example to go to the appropriate diretory containing the files.

### Pattern Window

Pattern windows detect events of interest (EOIs) as they stream through. To create a Pattern window, specify a list EOIs and assemble them into an expression that uses logical operators. The expression can also include temporal conditions.

| Example | Description |
| ------ | ------ |
| [pattern_empty_index_xml](examples/pattern/pattern_empty_index_xml) | This project includes a single source window and a pattern window with three EOIs and a temporal condition. |
| [pattern_xml](examples/pattern/pattern_xml) | This project includes a single source window and a pattern window to find pattern event 1 followed by event 2 within one hour. |

### Geofence Window

A geofence is a virtual perimeter for a real-world geographic area. The Geofence window determines whether the location of an event stream is inside or close to an area of interest.

| Example | Description |
| ------ | ------ |
| [geofence2_xml](examples/geofence/geofence2_xml) | This example shows the use of geofences with simulated automatic number-plate recognition (ANPR) technology. A watch list of vehicle registration plates of “wanted” vehicles are tracked to determine whether they cross into geofences around “critical” infrastructure. |


 
## Contributing

> We welcome your contributions! Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on how to submit contributions to this project. 

## License

> This project is licensed under the [Apache 2.0 License](LICENSE).

## Additional Resources

* [SAS Event Stream Processing 6.2 Product Documentation](https://go.documentation.sas.com/?cdcId=espcdc&cdcVersion=6.2&docsetId=espov&docsetTarget=home.htm&locale=en)