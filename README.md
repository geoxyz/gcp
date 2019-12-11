# Deploying reverse geocoder lite VM on GCP

The reverse geocode lite is a very fast reverse geocoding API. It takes as input a Latitude, Longitude pair and outputs either XML (default) or JSON text with the name of the nearest major locality name, as well as the nearest location name and other regional information from both geonames.org and openstreetmap.org neighborhood/administrative area data.

## Launching the server

Navigate to the solution page: 
![Start-page](https://github.com/geoxyz/gcp/blob/master/Screen%20Shot%202019-11-26%20at%207.47.42%20PM.png)

Configure the project where you are going to host the API
![Configure](https://github.com/geoxyz/gcp/blob/master/Screen%20Shot%202019-11-26%20at%207.53.30%20PM.png)
If you get a warning, configure your project with the sufficient quota. The solution needs only minimal computing resources to run, however a fasterm machine with at least 4GB of Memory will provide better performance.

Then allow network access to port 80 (and possibly port 443 if you want to access the API over SSL). 
![Network](https://github.com/geoxyz/gcp/blob/master/Screen%20Shot%202019-11-26%20at%207.53.56%20PM.png)

Click "Deploy"
![Deploy](https://github.com/geoxyz/gcp/blob/master/Screen%20Shot%202019-11-26%20at%207.54.05%20PM.png)

Then wait for the service to be deployed.
[Deployed](https://github.com/geoxyz/gcp/blob/master/Screen%20Shot%202019-11-26%20at%207.54.20%20PM.png)

Once successful you will see this message:
![Success](https://github.com/geoxyz/gcp/blob/master/Screen%20Shot%202019-11-26%20at%207.56.22%20PM.png)

You may also access the service over SSH. There are scripts in the home directory to get you started.
![Success](https://github.com/geoxyz/gcp/blob/master/Screen%20Shot%202019-11-26%20at%207.56.50%20PM.png)

Your server is now ready to use.

## Access the API on port 80 (http://<your ip>
  ![API](https://github.com/geoxyz/gcp/blob/master/Screen%20Shot%202019-11-26%20at%207.58.57%20PM.png)
  
## What If I Need Help?
Go to the [Support Page](https://geocode.xyz/contact) and either chat, email or tweet to us.

