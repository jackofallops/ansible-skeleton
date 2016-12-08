# ansible-skeleton
This project aims to short-cut the set-up of a new Configuration Management system by providing the basic directory structure and common tooling hooks.


## Directory Layout

* dynamic_environments
    * ini files and scripts for using external config e.g. inventories, ENC etc
* environments
    * Top level environmental common configurations
* group_vars
    * group level configurations and overrides
* host_vars
    * Host level configs and overrides
* inventories
    * Inventory files to describe environments and groups
* library
    * 
* roles
    * playbooks to configure your infrastructure to do the things you want it to do!

    
## Key Files
* site.yml
    * here lies the top level - use this to include the parts you want to use from the skeleton
    * as a rule-of-thumb, don't use this file to "hard code" items into the plays, use includes

## Guidance


