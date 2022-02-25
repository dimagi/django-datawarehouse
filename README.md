django-datawarehouse
====================

**This repository is fully deprecated. It has been merged with [the cStock codebase](https://github.com/dimagi/logistics).**


Simple utility wrapper for doing data warehousing in django

To use add a subclass of warehouse.runner.WarehouseRunner to your project and 
add the following to your settings.py

WAREHOUSE_RUNNER = 'path.to.my.runner.MyRunnerClassName'

Then use 

$ ./manage.py update_warehouse 
