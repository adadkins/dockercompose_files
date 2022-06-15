This creates a container with shreddit, and then the entry script adds the schreddit exec as a cron job inside the container

For this to work, you just need to create a new directory `/config` and add your shreddit `praw.init` and `shreddit.yml` files 

Then run `docker-compose up -d` to build the image and run the container
