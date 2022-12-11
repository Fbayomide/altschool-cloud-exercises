## [Exercise]() 8

### Task:
* Create an Ansible Playbook to setup a server with Apache
* The server should be set to the Africa/Lagos Timezone
* Host an index.php file with the following content, as the main file on the server:
```php
<?php
date_default_timezone_set('Africa/Lagos');
echo date("F d, Y h:i:s A e", time());
?>
```

### Instruction:
- [ ] Submit the Ansible playbook, the output of `systemctl status apache2` after deploying the playbook and a screenshot of the rendered page.  

## Solution  

Below are playbook contents **'Setup.yml'**  

![playbook-1](https://user-images.githubusercontent.com/67663655/197807315-d9902209-3698-46a4-8bb2-c35e3ad9887c.png)  
  
![playbook-2](https://user-images.githubusercontent.com/67663655/197807386-f8947d99-5494-4349-92bf-352dec396a3a.png)  

  
# Inventory file  
  
![inventory](https://user-images.githubusercontent.com/67663655/197808113-16098316-9e18-43f5-999c-a4546abad389.png)  

  
# systemctl status apache2  

![systemctl status apache2](https://user-images.githubusercontent.com/67663655/197808394-8312f6de-1a3f-4917-a487-60bdbf9ce6f7.png)  
  
# Rendered Pages  

![Deployed page (apache2)](https://user-images.githubusercontent.com/67663655/197808632-4e150354-c9c1-4794-a57a-ce23e8109a5f.png)  
  
 # ipaddress/index.php  
 
![Deployed page (index php)](https://user-images.githubusercontent.com/67663655/197808643-77358fc4-1a14-48c7-b670-19defc818142.png)


