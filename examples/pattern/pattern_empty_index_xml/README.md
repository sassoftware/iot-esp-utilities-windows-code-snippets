# pattern_empty_index Instructions

This project includes a single source window and a pattern window with three EOIs and a temporal condition.

Use the following steps to execute the pattern_empty_index code snippet:

1.  Create a directory on the ESP server for the example.

2.  Upload the `50k.csv` file to the server directory you just created.

3.  Upload the `modelpattern.xml` file to SAS ESP Studio. Refer to the [Uploading a Model to ESP Studio](../../../docs/Uploading_a_Model_to_ESP_Studio.pdf) document for instructions.
  
4.  Double-click the project named `pattern_empty_index` to open it.

5.  Edit the Input Data Connector for the `sourceWindow_01` window to include the full path to the `50k.csv` file you uploaded. Refer to the [Editing Connectors](../../../docs/Connectors.pdf) document for instructions.

6.  Edit the Subscriber Connector for the `patternWindow_01` window to include the full path to the `output.csv` to be created. Refer to the [Editing Connectors](../../../docs/Connectors.pdf) document for instructions.

7.  Save your changes and test your model. Refer to the [Testing Models](../../../docs/Testing_Models.pdf) document for instrcutions.

8.  Execute the model on the ESP Server and Subscribe to the `patternWindow_01` window using ESP Streamviewer. Refer to the [Executing a Model and Viewing the Output](../../../docs/Executing_a_Model_and_Viewing_the_Output.pdf) document for instructions.

