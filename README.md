to install this module:
Run this on magento root folder

composer config repositories.jaybeerivera/testjaybee git git@github.com:jaybeerivera/testjaybee.git
composer require jaybeerivera/testjaybee:dev-master
php bin/magento module:enable Test_Jaybee
php bin/magento setup:static-content:deploy
php bin/magento setup:upgrade
php bin/magento cache:flush
