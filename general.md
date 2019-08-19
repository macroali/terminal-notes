# Borrar cache symfony
sudo rm -rf var/cache/* && sudo rm -rf var/logs/* && php bin/console cache:clear --no-warmup --env=prod <br<br> 
sudo rm -rf var/cache/* && sudo rm -rf var/logs/* && php bin/console cache:clear --no-warmup --env=dev && php bin/console assets:install --env=dev <br>
sudo rm -rf var/cache/* && sudo rm -rf var/logs/* && php bin/console cache:clear --no-warmup --env=prod && php bin/console assets:install --env=prod <br>
