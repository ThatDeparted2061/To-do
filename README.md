# To-do

The major issues that i faced in the repositories - 
- deprecated node version - version 16 is being used which is incompatible with es build, 
I think of comparing a better lts version and work on bumping to that version say 18 or 20 or 22.
I recommend using NVM for future version control of the node modules
- ruby version is 2.3.1 which is incompatible with ubuntu 22.04 so we use openssl but we use **libssl1.0-dev** in out setup which has been deprecated
I think we shud bump it up to to a newer version say 3.1.2
