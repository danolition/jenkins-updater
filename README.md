# jenkins-updater

Updater script that allows you to keep the version numbers connected to the war files 
and also makes it easy to roll back in case there should be any issues with the new jenkins version

A suggested use scenario for these scripts could be to run periodically on a jenkins instance somewhere.
I would suggest to run it with anacron every few weeks to make sure the new jenkins version is stable enough. Another possible use case would be in an ansible playbook.
