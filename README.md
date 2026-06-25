# VEHICLE MAINTAINENCE SCHEDULER MICROSERVICE

* This project is used to manage vehicle maintenance scheduling.
* It fetches depot and vehicle data from the API.
* Each depot has limited mechanic hours available.
* Each vehicle has a duration and impact value.
* The system selects vehicles based on maximum impact.
* It uses an optimization algorithm for scheduling.

* API to get the vehicle allocation
   #### localhost:3000/schedule

* The `/schedule` API returns the best vehicle allocation.
* It also records logs for API calls and errors.
* This helps in efficient maintenance planning.
