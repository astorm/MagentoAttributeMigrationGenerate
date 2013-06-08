MagentoAttributeMigrationGenerate
=================================

A Magento shell script to automatically create an attribute migration script for a specific attribute.  This allows developers to tweak their attributes in the UI, and then generate a script for deployment. 

###Magento Attribute Migration Generator

This script generates a setup resource script for any existing Magento attribute.

    ./magento-create-setup.php attribute_code
    
NOTE: Must be run from the root of the Magento system with the existing attribute.    

Original Post: http://alanstorm.com/magento_attribute_migration_generator

N98-Magerun
--------------------------------------------------
There's currently an effort (fully blessed) to <a href="https://github.com/netz98/n98-magerun/issues/137">migrate this to the `n98-magerun` platform</a>. 