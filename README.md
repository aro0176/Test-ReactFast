  # Test-ReactFast
  First, ansible must be installed in your server before executed the script. 
  This is a link for step install ansible : https://docs.ansible.com/ansible/latest/installation_guide/index.html
  
  I made a simple test on how to automate the deployment of reactjs and fastapi applications with a postgresql data base using ansible.
  Don't forget to change the variables and the git link of the application in the script:
      - roles/frontend/tasks/site.yml 
              and 
      - roles/backend/tasks/back.yml
