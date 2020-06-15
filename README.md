# thingsboardinstructions

To access ThingsBoard Sandbox navigate to:
```
http://52.149.231.47:8080/
```

ThingsBoard is a multi-tenant application which means:


  **ThingsBoard Admin 1::many Tenants**   
  > Admin creates tenants and assigns admins to each tenant. Tenants are siloed entities managed by tenant admins
  
  **Tenant 1::many Tenant Admins**  
  > Tenant Admins create/manage/assign resources such as dashboards to their respecitve customer/end users
  
  **Tenant Admin 1::many customers**  
  > Customers can view assets
  

The **admin** login is:
sysadmin@thingsboard.org - password: RapidPhoto1

The existing users are:

* Tenant Name: AOMSConsumerEnd
  - Tenant **admins** 
    - john@doe.com - password: userdemo
      - The tenant's **customers**: 
          - monitoring@team.com - password: userdemo
          
          
The VideoStreaming Dashboard relies on the video player running on my local machine, which may not be running at the time of the dashboard being viewed. I will soon deploy the video player on Azure also where it will be avaialbe at all times.
