# Tinder Match Preview Image Downloader

This script downloads the unblurred photos of users that have liked your Tinder profile.
It exploits a Tinder API vulnerability explained in Sanskar Jethi's [Medium post](https://medium.com/@sansyrox/hacking-tinders-premium-model-43f9f699d44).

# Requirements

This has been developed and tested in Python 3.7.3, on Ubuntu 18.0.4. 

# Installation

1. Clone this repository.
2. Install Python 3.7.3.
3. Install dependencies with `pip install -r requirements.txt`.
4. You can find your Tinder X-Auth-Token using the instructions in Sanskar Jethi's [Medium post](https://medium.com/@sansyrox/hacking-tinders-premium-model-43f9f699d44).
5. Run the script with `python exploit_tinder.py "X-Auth-Token".
    * The script creates a directory called **tinder_photos**, which contains a directory for each user who liked your profile. Each directory contains the pictures of that user.
	
# Credits

* **@jidicula**, whose [script](https://github.com/jidicula/tinderizer) I took inspiration from.
