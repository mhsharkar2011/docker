# Docker Basic Command:
 1) docker-compose up -d
 2) docker-compose down
 
# Docker with Sail
 1) ./vendor/bin/sail up (Running in terminal)
 2) ./vendor/bin/sail up -d ()
 2) ./vendor/bin/sail down -v (To remove container with volume)
 3) alias sail='[ -f sail ] && sh sail || sh vendor/bin/sail' (using sail ...  without ./vendor/bin/sail ...)
