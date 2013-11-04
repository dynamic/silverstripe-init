SilverStripe Git Submodule Project Starter
=================

A customized git submodule based SilverStripe project installer. Works well with FTP-based git deployment tools like Beanstalkapp and DeployHQ. Suited for LAMP stacks with PHP 5.4 +

Installation
=================

1. `git clone git@github.com:dynamic/silverstripe-init.git my-silverstripe-project`
2. `cd my-silverstripe-project`
3. configure your environment and database settings by editing `_ss_environemnt.example.php`. Rename file to `_ss_environment.php`
4. `git remote rm origin` to remove this repository as origin. 
5. `git remote add origin git@your-remote-repository:repository-name.git` to add your repository as remote origin

When you visit http://my-silverstripe-project.com SilverStripe will use the information in `_ss_environemnt.php` to connect to or create your database and populate it with default records for a fresh SilverStripe CMS project.

Inspired by silverstripe-init by Ryan Wachtl - https://github.com/ryanwachtl/silverstripe-init