## ✅ Task 1: AWS Account Configuration Submission

### 1. 📸 Versions
- `aws --version`:  
  ![aws version](https://raw.githubusercontent.com/Twitty97/rsschool-devops-course-tasks/task_1/terraform-lambda-project-fara%20(all%20the%20screenshots)/aws-iam.png
  )

- `terraform version`:  
  ![terraform version](https://raw.githubusercontent.com/Twitty97/rsschool-devops-course-tasks/task_1/terraform-lambda-project-fara%20(all%20the%20screenshots)/terraform-ver.png
  )

---

### 2. ☁️ Terraform Plan + Apply
- Plan output (with S3 bucket + IAM resources):

  ![terraform init](https://raw.githubusercontent.com/Twitty97/rsschool-devops-course-tasks/task_1/terraform-lambda-project-fara%20(all%20the%20screenshots)/01_init.png)

  ![S3 Bucket Created](https://raw.githubusercontent.com/Twitty97/rsschool-devops-course-tasks/task_1/terraform-lambda-project-fara%20(all%20the%20screenshots)/bucket-created.png)

---

### 3. 📁 AWS Console Screenshots
- S3 bucket visible in console:  
  ![S3 Bucket in AWS Console](https://raw.githubusercontent.com/Twitty97/rsschool-devops-course-tasks/task_1/terraform-lambda-project-fara%20(all%20the%20screenshots)/bucket-in-aws.png)


- IAM Role for GitHub Actions:  
![Terraform Plan Output](https://raw.githubusercontent.com/Twitty97/rsschool-devops-course-tasks/task_1/terraform-lambda-project-fara%20(all%20the%20screenshots)/terraform-plan.png)

![Terraform Apply Output](https://raw.githubusercontent.com/Twitty97/rsschool-devops-course-tasks/task_1/terraform-lambda-project-fara%20(all%20the%20screenshots)/terraform-apply.png)

- MFA enabled (non-root account):  
  ![mfa](https://raw.githubusercontent.com/Twitty97/rsschool-devops-course-tasks/task_1/terraform-lambda-project-fara%20(all%20the%20screenshots)/MFA-setup-new.png
  )

---

### 4. ⚙️ GitHub Actions Workflow
- Link to successful run (push or PR):  
  [GitHub Actions Run](https://github.com/Twitty97/rsschool-devops-course-tasks/actions/runs/15622578538)

- Jobs included:
  - [x] `terraform-check`
  - [x] `terraform-plan`
  - [x] `terraform-apply`

---

### 5. 📚 Code Structure
- `main.tf`, `variables.tf`, `outputs.tf` properly organized ✅
- Code split by logical resource ✅

---

### 6. 📘 Additional Tasks (💫)
- Trust policy with GitHub OIDC provider ✅
- `GithubActionsRole` with appropriate permissions ✅
- README file with setup & usage docs ✅
