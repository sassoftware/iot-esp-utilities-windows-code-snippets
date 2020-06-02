# geofence2_xml Instructions

This example shows the use of geofences with simulated automatic number-plate recognition (ANPR) technology. A watch list of vehicle registration plates of “wanted” vehicles are tracked to determine whether they cross into geofences around “critical” infrastructure.

Use the following steps to execute the geofence2_xml code snippet:

1.  Create a directory on the ESP server for the example.

2.  Upload the `anpr.csv`, `infrastructure.csv` and `wantedvehicle.csv` files to the server directory you just created.

3.  Upload the `ANPR.xml` file to SAS ESP Studio. Refer to the [Uploading a Model to ESP Studio](../../../docs/Uploading_a_Model_to_ESP_Studio.pdf) document for instructions.
  
4.  Double-click the project named `Project4` to open it.

5.  Edit the Input Data Connector for the `ANPR` source window to include the full path to the `anpr.csv` file you uploaded. Refer to the [Editing Connectors](../../../docs/Connectors.pdf) document for instructions.

6.  Edit the Input Data Connector for the `VehicleWatchlist` source window to include the full path to the `wantedvehicle.csv` file you uploaded. Refer to the [Editing Connectors](../../../docs/Connectors.pdf) document for instructions.

7.  Edit the Input Data Connector for the `CriticalInfrastructure` source window to include the full path to the `infrastructure.csv` file you uploaded. Refer to the [Editing Connectors](../../../docs/Connectors.pdf) document for instructions.

8.  Edit the Subscriber Connector for the `GeofenceMatches` filter window to include the full path to the `result.out` file to be created.

9.  Save your changes and test your model. Refer to the [Testing Models](../../../docs/Testing_Models.pdf) document for instrcutions.

10.  Execute the model on the ESP Server and Subscribe to the `GeofenceMatches` window using ESP Streamviewer. Refer to the [Executing a Model and Viewing the Output](../../../docs/Executing_a_Model_and_Viewing_the_Output.pdf) document for instructions.
