!SLIDE 
# Migrating a 18 people dev company to Rails 3


!SLIDE
# Agenda

!SLIDE bullets incremental
# Agenda

* Be convinced of the need to upgrade.
* Convince customer of the need to upgrade.
* Find an upgrade strategy for your company.
* Help your developers to learn Rails 3.

!SLIDE bullets incremental
# Motivation #

* Rails is a fast evolving framework
* It's allows a very time efficient web application development

!SLIDE 
# BUT #

!SLIDE 
# Rails changes a lot and ... #

!SLIDE 
# API changes are painful! #


!SLIDE smbullets incremental
# Brief history of pain #

* Rails 1.x -> Rails 1.2.6
* Rails 1.2.x -> Rails 2.0
* Rails 2.0 -> Rails 2.3
* Rails 2.3 -> Rails 3.0
* Rails 3.0 -> Rails 3.1

!SLIDE center transition=scrollUp
![pain](pain.jpg)

!SLIDE
# Can you feel the pain?


!SLIDE
# So what is the conclusion? #

!SLIDE
# Is Rails bad because its API changes? #

!SLIDE
# No! #

!SLIDE
## Every car, every house and every software application requires maintenance. ##
### That's a universal fact! ###


!SLIDE
# Rails upgrades 
# = 
# Software Maintenance

!SLIDE
## The (software) environment changes (ruby, rails, gems, ...). ##

!SLIDE
#Your application has to adapt.#
 
!SLIDE
# So keep on updating. #

!SLIDE
# Convinced. #

!SLIDE
# But how to convice the customer? #

!SLIDE center transition=scrollUp
![check](gun_l.jpg)

!SLIDE smbullets
## You might run in to a discussion like this: ##

* Why should I update at all?

* It doesn't bring my any new features.

* It doesn't gain my profit.

* Why should I then spend money for it?

!SLIDE
## Help your customer to understand the ##
# nature of software development! #

!SLIDE bullets incremental
# Reasons to migrate to Rails 3 #

* Feature costs will remain low
* Security
* Be prepared for investor audits
* Keep your developers
* Get ready for Rails 3.1 and Rails 4

!SLIDE bullets incremental
# Reasons to migrate to Rails 3 #
* Mostly faster
* Way more modularity
* Router
* Bundler
* Arel

!SLIDE
# Need more tech stuff?

!SLIDE
# Have a look at
## http://www.slideshare.net/crnixon/rails-3-7983843


!SLIDE
# By not updating to rails3 your today's code is your legacy code of tomorrow. 

!SLIDE
# Costs for future features increase rapidly.

!SLIDE center transition=scrollUp
![check](atommuell.jpg)

!SLIDE
# Surely a ...

!SLIDE center transition=scrollUp
![deadend](deadend_l.jpg)

!SLIDE
# Holding back upgrades is like a rubber band. #

!SLIDE
# You can strecht it, ... #

!SLIDE
# ... but only to some extend.

!SLIDE
# How to avoid the rubber band slapping your face?#
## Or when to update your app? ##

!SLIDE
# As a rule of thumb:

!SLIDE smbullets incremental
# 1. A Rails beta comes out:

* Check whether it is somehow stable.
* Try it implementing internal non-mission critical projects.
* Collect experience and get a rough picture about pros and cons.
* BTW: this is a good chance to submit bugs and create pull requests.

!SLIDE smbullets incremental
# 2. New a Rails final comes out:

* Upgrade your internal projects to the new version.
* Remove deprication warnings!
* See whether there are some show stoppers, performance issues, etc.
* If there are issues, you can wait for the next patch level before proceed migrating your projects.
* New projects will be started with the final version.
* Keep on upgrading: One by one. 

!SLIDE smbullets incremental
# 3. A new Rails beta comes out:
- You should have migrate at least 70% of your apps.
- Some of them won't ever see the next major release. They will die a slow but painful death. That's life.
- Go back to step 1.

!SLIDE
# How to help your developers to learn Rails 3

!SLIDE bullets incremental
* Show them all those wonderful screencasts
* Buy the books the need

!SLIDE
# Give them **space**
## to **read**, **watch** and **play**! 
### (This is the most difficult one)

!SLIDE
# Hire people who care

!SLIDE
## fire those who don't :-)

!SLIDE
## We'll this sounds all very nice in theory but ...

!SLIDE
# there are **obstacles**

!SLIDE
# Crapy Code

!SLIDE
# Legacy plugins, gems, ...
## being not maintained any more

!SLIDE
# No or sloppy tests

!SLIDE
# No or not enough money

!SLIDE
# This actually not related to the upgrade process!

!SLIDE
# But it turns out that ...

!SLIDE
# the process of upgrading your app becomes your **doomsday**
## of all sins committed in the project.

!SLIDE
# So ...

!SLIDE
# Keep your code clean!

!SLIDE
# Select your 3rd party code carefully
## gems, plugins, ...
## Contribute.

!SLIDE
# Test coverage!

!SLIDE
# Marry rich or get customers with cashflow :-)
## Check your/their business model.
## When does it break even? 
## And when realistically?

!SLIDE smbullets incremental
# Recap

* Will to upgrade early ![check](check.png)
* Arguments to convince customers ![check](check.png)
* Long term upgrade strategy ![check](check.png)
* Help dev people to learn ![check](check.png)
* Prevent project sins whenever possible ![check](check.png)

!SLIDE
## ... and they lived happily ever after.