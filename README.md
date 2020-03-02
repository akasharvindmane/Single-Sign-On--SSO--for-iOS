The scope of this repo is to detail out the complete design and architecture for the iOS application that uses Microsoft Authentication library for iOS (MSAL) to implement Authentication with Active Directory (Azure AD).
MSAL will automatically renew tokens, deliver single sign-on (SSO) between other apps on the device, and manage the Account(s).
This document covers how to integrate existing iOS application that uses MSAL authentication to sign in users from a single Azure Active Directory. All the design and development changes made will be covered in this document. 
This document is a step-by-step guide for implementation and configuration. 
the various lifecycle events of your app to achieve the following objectives.
•	Sign-in a user
•	Device-wide SSO and Conditional Access support through the Auth Broker
•	Select between Single Account Mode and Multiple Account Mode
•	Get a token for the Microsoft Graph
•	Sign out the user
