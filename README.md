Sinatra with MySQL
====================

This git repository will help you get up and running quickly with Sinatra and a MySQL database on [OpenShift](https://www.openshift.com/).


Running this application locally
----------------------------------

Before running any of these examples, you should run the below command to make sure that you have the correct ruby gems installed

		bundle install --without production

To run this application locally, cd into the sinatra-mysql directory that you cloned and run

		shotgun

To create a database migration file run

		rake db:create_migration NAME=create_users

To run the migrations and create a local sqlite database run

		rake db:migrate


Thanks to:

The original [Sinatra QuickStart by OpenShift](https://hub.openshift.com/quickstarts/118-sinatra)

License
-------

This code is dedicated to the public domain to the maximum extent
permitted by applicable law, pursuant to CC0
http://creativecommons.org/publicdomain/zero/1.0/
