# IoT-HelloWorld
HelloWorld sample application for Windows IoT Core.

The HelloWorld sample application is a Windows Universal Application that can be deployed to an IoT device.  In order to debug on the remote device:  
  1. In the top menu area of Visual Studio, make sure you choose 'ARM' for the target architecture  
  2. Right-click on the 'HelloWorld' project in Visual Studio  
  3. Choose 'Properties'  
  4. Choose 'Debug' on the left-hand menu  
  5. Under the 'Start options' section, make sure 'Remote Machine' is selected for Target Device  
  6. Enter the IP address of the remote IoT device in the text box next to 'Remote Machine'  
  7. Now, with your IoT device connected to the network, simply debug the applicaton and Visual Studio will automatically deploy the application to the remote IoT device  
  8. When you stop debugging, Visual Studio will automatically close the application on the remote device
