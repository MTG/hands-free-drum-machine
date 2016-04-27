# Hands-free Sound Machine

## Installation instructions

### Web app
  1. Download code, open terminal and cd into folder
  2. Install python requirements (pip install -r requirements.txt, vortualenv recommended)
  3. Get a [Freesound API api key](http://www.freesound.org/apiv2/apply/) and paste it into line 214, static/js/all.js.
  3. Run web werver with 'python app.py'
  4. Open browser and point at localhost:5000
  5. Enjoy!

If no messages are being received from the RiOT sensor, make sure ports and IP addresses are configured correctly in app.py. 

The speech control only works with Chrome.
