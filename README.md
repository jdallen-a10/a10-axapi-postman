# a10-axapi-postman
A Postman collection to support A10 aXAPI v3.0 API calls

To use:
1. Create an environment with the following variables:
   - HOST - IP address of the primary ADC
   - HOST_S - IP address of the secondary ADC, used for the sync process
   - PORT - `:PORT` This if the port is standard SSL (:443), leave this variable blank
   - username - Username to login to the ADC  
   - password - Password to login to the ADC
   - authkey - This is populated after sending the Authorization request
1. Run the `Authorize - RUN ME FIRST!` postman command

After running the Authorize command, run the commands to demo and test the aXAPI Calls
