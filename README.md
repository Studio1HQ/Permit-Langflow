# Langflow LLM Chain Setup and Custom Component Integration (Permit.io)

## Prerequisites

- **Langflow**: Make sure Langflow is installed on your machine. You can install it via pip if you haven’t already:
  ```bash
  pip install langflow
  ```

- **Python**: Ensure you have Python 3.8 or higher.

## Step 1: Installing the JSON File in Langflow

1. **Open Langflow**:
   Run Langflow in your terminal to start the server.
   ```bash
   python3 -m langflow run
   ```

2. **Access the Web Interface**:
   Go to the local host web pag in your web browser to access the Langflow web interface. The local host web link will be generated by the langflow bash script

3. **Import the JSON File**:
   - In the Langflow web interface, locate the **"Import Chain"** button.
   - Click **"Import Chain"** and select the JSON file you want to upload.
   - Once uploaded, your chain configuration will be displayed on the canvas.

## Step 2: Integrating the Custom Code Component

1. **Add the Custom Component to Langflow**:
   - In the Langflow web interface, add a **"Custom Component"** node to your chain.
   - Click on component and the click on code button
   - Copy the CustomComponent.py file contents on the Langflow's web IDE's Custom Component that you have created.

2. **Connect the Component in the Chain**:
   - Link your custom component to other nodes in your Langflow chain as needed.
   - Ensure that the component’s output is routed to the appropriate places within your chain for permission-based checks.

Once everything is set up, you can start using your LLM Langflow chain with the integrated custom component. Run your queries or interactions, and the custom component will handle permission checks based on the specified inputs.
