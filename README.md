# Password-Writeback

# What is the purpose of Password Writeback?
- Synchronization process is only a one-way process from local AD to Azure AD. However, to sync Azure AD changes to local AD. Use Password Writeback.
- Password Writeback is used to sync password changes from Azure AD to local Active Directory environment

# How to enable password writeback?
- Navigate to adconnect server > configure > customize sychronization options > enter credentials > enable password writeback > configure
- Now whenever a password change is made within Azure AD, it is written back onto the local AD.

<p align="center">
  
<img src="https://user-images.githubusercontent.com/104326475/167276683-7183a991-a4bb-4baf-b53b-c7f420302921.png" height="80%" width="80%" alt="Conditional Access"/>
  
<p/>
