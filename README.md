# ServiceNow Ticket Management Lab
## Overview 
This lab introduces students to ServiceNow’s ticket management system by guiding them through the process of creating, assigning, updating, resolving, and closing incident tickets. Through hands-on activities, participants gain practical experience in handling IT service requests and simulating real-world support workflows.

## Objectives 

- Set up and access a personal ServiceNow developer instance.
- Create and manage incident tickets, including assigning, updating, and resolving them.
- Document ticket activity using work notes and resolution information.
-  Simulate escalation and automate tasks using basic Business Rules.
- Practice managing multiple incidents in a structured support workflow.

# ServiceNow Ticket Mangement & Active Directory 🗄️
## 📺 Watch the video
<div>
    <a href="https://www.loom.com/share/6351498aeba4476b9d10ddd193a3ae3d">
      <p>Creating and Resolving Tickets in ServiceNow and Active Directory</p>
    </a>
    <a href="https://www.loom.com/share/6351498aeba4476b9d10ddd193a3ae3d">
      <img style="max-width:300px;" src="https://cdn.loom.com/sessions/thumbnails/6351498aeba4476b9d10ddd193a3ae3d-b5a50df15b7c2f21-full-play.gif">
    </a>
  </div

--- 
 

  
## Creating and Resolving a ServiceNow Ticket in Active Directory

**1. Create a New User Account** [0:17](https://loom.com/share/6351498aeba4476b9d10ddd193a3ae3d?t=17)

- Click 'Sign In' to create a new user account.
- Use a temporary email address for the account.
- Fill in the first name (e.g., Jane Doe) and select the country (e.g., United States).
- Complete the CAPTCHA and click 'Sign Up'.
- Save the password for future reference.

**2. Verify Email Address** [1:17](https://loom.com/share/6351498aeba4476b9d10ddd193a3ae3d?t=77)

- Check the inbox for a verification email.
- Click on the verification link to confirm the email address.

**3. Access ServiceNow Instance** [1:54](https://loom.com/share/6351498aeba4476b9d10ddd193a3ae3d?t=114)

- Wait for the instance to be ready (may take a few minutes).
- Open the ServiceNow instance.

**4. Navigate to Users and Departments** [2:36](https://loom.com/share/6351498aeba4476b9d10ddd193a3ae3d?t=156)

- Click on 'Users' and filter by department.
- Select a user (e.g., Ashley Parker) and update her email to reflect the domain.

**5. Start Domain Controllers** [5:45](https://loom.com/share/6351498aeba4476b9d10ddd193a3ae3d?t=345)

- Start both domain controller virtual machines to ensure replication.

**6. Create User in Active Directory** [9:33](https://loom.com/share/6351498aeba4476b9d10ddd193a3ae3d?t=573)

- Open 'Active Directory Users and Computers'.
- Create a new user for Ashley Parker with a temporary password and mark the account as disabled.

**7. Create a Ticket in ServiceNow** [11:05](https://loom.com/share/6351498aeba4476b9d10ddd193a3ae3d?t=665)

- Navigate to 'Incidents' and click 'New'.
- Change the form view to 'Default'.
- Fill in the ticket details: 
  - Caller: Ashley Parker
  - Category: Password Reset
  - Description: Email account locked out.
- Set priority to Medium and submit the ticket.

**8. Assign the Ticket** [13:38](https://loom.com/share/6351498aeba4476b9d10ddd193a3ae3d?t=818)

- Open the created ticket and assign it to the Help Desk.
- Add work notes indicating the assignment for troubleshooting.

**9. Resolve the Ticket in Active Directory** [16:51](https://loom.com/share/6351498aeba4476b9d10ddd193a3ae3d?t=1011)

- Unlock the user account in Active Directory and reset the password.
- Ensure the option for 'User must change password at next logon' is checked.

**10. Update Ticket Resolution Notes** [18:08](https://loom.com/share/6351498aeba4476b9d10ddd193a3ae3d?t=1088)

- Add resolution notes in the ticket indicating the user was unlocked and password reset.
- Change the ticket state to 'Resolved'.

**11. Close the Ticket** [20:36](https://loom.com/share/6351498aeba4476b9d10ddd193a3ae3d?t=1236)

- Verify that the user can log in successfully.
- If successful, close the incident.

**12. Create a Change Ticket** [21:39](https://loom.com/share/6351498aeba4476b9d10ddd193a3ae3d?t=1299)

- Navigate to 'Change' and create a new change request for the email server issue.
- Fill in the necessary details and request approval.

### Cautionary Notes

- Ensure that all user data is handled in compliance with company policies.
- Double-check email addresses and user details to avoid errors.

### Tips for Efficiency

- Use templates for common ticket types to save time.
- Regularly update your knowledge of ServiceNow features to streamline processes.

