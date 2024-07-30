# SIEM-Visualization-Example-2-Failed-Logon-Attempts-Disabled-Users-
SIEM Visualization Example 2: Failed Logon Attempts (Disabled Users)

 In this lab focused on SIEM (Security Information and Event Management) fundamentals, I engaged in a task to create visualizations for monitoring failed login attempts against disabled user accounts using Kibana. The process began with me accessing the SIEM dashboard, where my goal was to either edit an existing visualization or create a new one that specifically captured security incidents related to disabled users.

Key steps I completed in the lab included:

Accessing the Visualization Tool: I navigated to Kibana using the specified IP address, accessed the dashboard, and initiated the creation of a new visualization by clicking the "Create visualization" button.

Setting Data Filters: I set filters to specifically isolate failed login attempts tied to disabled user accounts. This was crucial since such logins are inherently unsuccessful due to the account status, marked by a SubStatus code of 0xC0000072 indicating a disabled user account.

Choosing and Configuring the Visualization Type: After filtering the data appropriately, I selected the type of visualization that best suited the data. I opted for a table format, which allowed for a clear, structured display of the failed attempts.

Configuring Data Display Settings: I adjusted the table settings to include specific data elements. I set up rows to display the disabled user involved in the failed login attempt, the machine where the attempt occurred, and the count of such attempts. This setup helped in identifying patterns or recurring issues across the network.

![Screenshot 2024-07-30 at 7 15 47 AM](https://github.com/user-attachments/assets/188b453e-df9c-48d6-aeb4-a85f555de290)

Finalizing and Viewing the Data: After configuring the visualization to my satisfaction, I saved the setup and returned to the dashboard to view the newly added visualization. This allowed me to monitor the specified events effectively within the broader context of the network's security posture.

![Screenshot 2024-07-30 at 7 23 24 AM](https://github.com/user-attachments/assets/3f087000-e16e-496c-b843-87665d502fa3)


The lab provided a comprehensive understanding of how to utilize SIEM tools for targeted security monitoring, enhancing my ability to respond to and analyze specific security threats within an organizational network.
