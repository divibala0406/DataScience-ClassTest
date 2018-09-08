Create "custinsight" project

set label for the project as prod
   a) oc adm  new-project <custinsight> --node-selector=’region=prod’   //example “region=dev”  or “ region=prod”

create DNS request for the project URL
   a) Use the SNOW URL below to access the infrastructure service catalog request templates
https://frb.service-now.com/nav_to.do       uri=%2Fcom.glideapp.servicecatalog_category_view.do%3Fv%3D1%26sysparm_parent%3D53ac9c5b6f6b820002092ddd5d3ee4bf%26sysparm_catalog%3D74bbc5176fae9e404f75cf30be3ee4c4%26sysparm_catalog_view%3Dcatalog_is_engineering_catalog 
          
          ![image](files/Users/vjulu/Desktop/snow-request-template.png)
          
          
          
          
          
