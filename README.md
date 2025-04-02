# acit4640-lab13

- When is the state file created?

The state file is created during the terraform apply process.

- When is the lock file present?

The lock file is only present when the file is being used. For example, if you use terraform plan, your Terraform will start using the file, and the lock file will appear ensuring no other changes can be made until Terraform finishes.

- Is the lock file always in the bucket after it is created?

No. When I created added my state file initially, there was no lock file. However, upon using terraform plan, the lock file appeaered.


state-file
![image](https://github.com/user-attachments/assets/81a34b77-e1e2-4d7e-8c79-a99a5c5e011b)

lock-file
![image](https://github.com/user-attachments/assets/59bff9c6-2e6e-4d94-871a-39b61e5d6133)
