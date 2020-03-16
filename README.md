ansible-simple-sinatra-deploy
=============================

Deploys the simple-sinatra application in a host

Requirements
-------------

ansible 2.8.5 or higher
Access to the container registry where the image is stored.

Dependencies
------------
None

Running the playbook
---------------------

ansible-playbook deploy-sinatra.yml -i inventory --private-key <key_file>




