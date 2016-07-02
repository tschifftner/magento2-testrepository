=== ONLY FOR TESTING ===

# Magento 2 Sample Repository

This is a sample repository for Magento 2 including all available sample data

### Installation

_1) Clone the repository_
```
git clone https://github.com/tschifftner/magento2-sample-repository.git
```

_2) Update composer managed repositories (first time this is time consuming!)_
```
bin/composer.phar update
```

_3a) Open url in your browser and use the installation wizzard_

_3b) Run magento-cli installation_

Ensure database exists

```
php bin/magento setup:install \
    --base-url=http://magento2demo.local/ \
    --db-host=localhost \
    --db-name=magento2demo \
    --db-user=root \
    --db-password=root \
    --admin-firstname=Magento \
    --admin-lastname=User \
    --admin-email=user@example.com \
    --admin-user=admin \
    --admin-password=magento2 \
    --language=de_DE \
    --currency=EUR \
    --timezone=Europe/Berlin \
    --use-rewrites=1
```    
