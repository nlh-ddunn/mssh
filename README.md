# mssh
####
#
#
# mssh -- magento-cloud ssh helper tool
#
#
# expects a single argument, the project url (including the environment/branch name
# no validation beyond ensuring that the format of the url is correct is done
#
# ex:
# https://REGION.magento.cloud/projects/PROJECTID/environments/BRANCH
#
####

This is a very simple python wrapper around the magento-cloud cli tool that allows you to ssh in without having to visit the cloudUI dashboard (provided you're sending a correctly formatted URL string)
