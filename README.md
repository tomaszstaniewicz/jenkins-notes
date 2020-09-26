1.  check where docker stores images
    >docker info | grep -i root

2. Show linux user id
    >id

3. Start jenkins container 
    > docker-compose up

4. Add jenkins to local DNS
    > subl /etc/hosts
    > add line
    >  127.0.0.1	jenkins
                          
                            