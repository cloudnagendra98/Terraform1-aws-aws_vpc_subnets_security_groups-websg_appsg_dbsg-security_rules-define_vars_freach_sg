* web
    * ingress
        * http (80): allow to all
        * ssh (22) : allow to all
* app
    * ingress
        * ssh (22) : allow to all
        * http (8080) : allow within the vpc range 
*  db
    * ingress 
        * tcp (3306) : allow within the vpc range 