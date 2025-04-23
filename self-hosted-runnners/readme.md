# CI/CD using Self hosted Github runners

## Create an EC2 instance 
   1. Go to AWS Console -> Compute -> Launch Instance
      ![Screenshot (106)](https://github.com/user-attachments/assets/394fd500-b0c9-448e-b82e-533301601ee5)

   2. Create Security Rules -> Inbound , Outbound
      ![Screenshot (107)](https://github.com/user-attachments/assets/de54780b-28b7-4f3f-aacf-68ae25d07e87)
      ![Screenshot (108)](https://github.com/user-attachments/assets/664c9184-39f4-40a6-9ebb-1a69f4d52377)

## Configure Self Hosted runners on Github
   1. Settings -> Actions -> Runners
      ![Screenshot (109)](https://github.com/user-attachments/assets/59083d0a-63b7-4566-9a27-3f8ee4cb74ee)

   2. SSH into your EC2 instance and run the following list of commands given below
      ![Screenshot (112)](https://github.com/user-attachments/assets/f9e586de-9bc6-49c9-aa6f-dc851d036c9d)

   4. Run your github-actions pipeline using self hosted runner
      ![Screenshot (111)](https://github.com/user-attachments/assets/4319ca79-223a-4c1b-b4cd-46484d58e657)

   5. Commit any changes in your code to check whether the pipeline is working fine or not
      ![Screenshot (113)](https://github.com/user-attachments/assets/f9def7d8-94f4-4cf3-97db-82e2ff9d323c)
   

      
   


   
