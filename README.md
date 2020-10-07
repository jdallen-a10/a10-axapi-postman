# a10-axapi-postman
A Postman collection to support A10 aXAPI v3.0 API calls

To use:
1. Create a environment with the following variables or add the variables as global variables in Postman:
   - HOST - IP address of the primary ADC
   - HOST_S - IP address of the secondary ADC, used for the sync process
   - PORT - `:PORT` This if the port is standard SSL (:443), leave this variable blank
   - username - Username to login to the ADC  
   - password - Password to login to the ADC
   - authkey - This is populated after sending the Authorization request
1. Run the `Authorize - RUN ME FIRST!` postman command to retrieve an Authorization key from the A10.  The Authorization key will populate the authkey variable, and is sent as an authorization header in the subsequent API Calls.

After running the Authorize command, run the commands to demo and test the aXAPI Calls
