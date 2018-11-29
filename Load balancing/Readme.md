deploying a bunch of nginx webservers using gcloud and startup.sh
gcloud compute instance-templates create nginx-template \
         --metadata-from-file startup-script=startup.sh
