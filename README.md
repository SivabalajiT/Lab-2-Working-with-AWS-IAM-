
# **Lab 2: Working with AWS IAM**

## **Overview**
This lab demonstrates how to work with **AWS Identity and Access Management (IAM)** to manage access to AWS resources securely. The lab includes creating users, groups, roles, and policies to control access in AWS.

---

## **Technologies Used**
- **AWS IAM**: For user, role, and policy management.
- **AWS Management Console**: For creating and managing IAM resources.

---

## **Steps Covered**

### **1. Create an IAM User**
- Navigate to the IAM service in the AWS Management Console.
- Create a new IAM user and assign programmatic and/or console access.
- Set permissions:
  - Attach an existing policy (e.g., `AdministratorAccess`) or create a custom policy.

### **2. Create an IAM Group**
- Create a group to organize IAM users.
- Attach appropriate policies to the group (e.g., `Amazonec2FullAccess` for Ec2 access).
- Add users to the group.

### **3. Create an IAM Role**
- Create a role for AWS services or external identity providers.
- Define a trusted entity (e.g., **EC2**, **Lambda**, or **S3**).
- Attach a policy to specify what actions the role allows.


### **4. Test Access**
- Use the credentials of the IAM user to log in and verify access permissions.
- Test role-based access using AWS CLI or services.

---

## **How to Use This Repository**
1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. The repository includes:
   - Example JSON policies.
   - Screenshots of IAM configuration (if applicable).
3. Follow the instructions above to replicate the lab.

---

## **Expected Outcome**
- IAM user, group, and role successfully configured with appropriate permissions.
- A custom policy tested and validated.
- Understanding of IAM best practices.

---

## **Best Practices**
- Always follow the **principle of least privilege** when assigning permissions.
- Enable **MFA (Multi-Factor Authentication)** for IAM users.
- Regularly rotate credentials and audit permissions.

---

## **License**
This project is licensed under the MIT License. See the `LICENSE` file for more details.

---

Feel free to adjust based on your specific lab content or project files!
