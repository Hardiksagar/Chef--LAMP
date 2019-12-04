# CHEF-LAMP Assignment
Created a Vagrant file which creates two virtual machines, and an Chef cookbook$

Specfications:

Linux Distro: Ubuntu, Centos
Created one VM as a Chef Server(Workstation).
The second VM as the chef client.
This Chef cookbook playbooik deployed and configured: Wordpress, MySQL or Maria-$


Command to run the cookbook:

chef-client --local-mode --runlist 'recipe[cookbook_repo-name]'
or
chef-apply <cookbook_repo-name>/recipes/default.rb

# Chef--LAMP
