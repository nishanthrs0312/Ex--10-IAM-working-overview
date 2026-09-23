## Ex--10-IAM-working-overview

## Name : Nishanth R S
# Reg No: 212224040223

## Aim:
To explore and configure AWS Identity and Access Management (IAM) users, groups, and policies, and to verify permissions for accessing Amazon S3 and Amazon EC2 resources.

## Procedure
1. Start the AWS Lab and open the AWS Management Console.

2. Open IAM → Users and verify user-1, user-2, and user-3.

3. Open User groups and verify the groups S3-Support, EC2-Support, and EC2-Admin and their attached policies.

4. Add:

     user-1 → S3-Support

     user-2 → EC2-Support

     user-3 → EC2-Admin

5. Open the IAM Sign-in URL and sign in as each user using the given lab credentials.

6. Test user-1: verify S3 access and confirm EC2 access is denied.

7. Test user-2: verify EC2 read-only access and confirm that stopping an EC2 instance is denied; verify S3 access is denied.

8. Test user-3: open EC2, select LabHost, and stop the instance successfully.

9. Submit the lab and check the Grades/Submission Report.

10. End the lab after completing all tasks.

## Output:

<img width="1607" height="747" alt="image" src="https://github.com/user-attachments/assets/387cf75d-fac7-4267-993f-044587a4d9b5" />
<img width="1271" height="639" alt="image" src="https://github.com/user-attachments/assets/376bc945-2f3b-4859-a80e-dad1fcc6432f" />
<img width="1273" height="638" alt="image" src="https://github.com/user-attachments/assets/7dd1d09a-2391-46f7-85a6-dca484f20344" />
<img width="1275" height="794" alt="image" src="https://github.com/user-attachments/assets/c943eea1-c73f-4dc0-80f5-4941a8e8cefd" />
<img width="1274" height="645" alt="image" src="https://github.com/user-attachments/assets/991eee28-78e2-42a9-8ff3-dfd020173fd8" />

## Result
The IAM users were successfully assigned to their respective groups, and the required permissions were verified. user-1 received S3 read-only access, user-2 received EC2 read-only access, and user-3 received EC2 administrative access to start/stop instances. Thus, IAM users, groups, policies, and permissions were successfully explored and tested.
