# Sunbird_Lern
**Project Details:**

User account creation and management, user login as well as platform administration capabilities is powered by the User-Org Service of Sunbird Lern Building Block.
This component enables the users to create accounts to save their platform preferences, access relevant content based on their preferences etc. Users with accounts on the system who login also get access to richer platform features such as Courses and Learner passbook.
Platform administrators can be granted capabilities to manage user roles on the platform, as well as manage platform master data (eg. Location data, Framework values etc.)

**Features to be implemented:**

UserOrg currently supports authentication using Keycloak 7.0.1. An upgrade from 7.0.1 to 20.0.0 version needs to be done.

**Setting up User-org service and LMS service**

Follow the README.md file for setting up the service locally - https://github.com/Sunbird-Lern/userorg-service/tree/release-5.3.0

**Setting up keycloak 7 locally**

This setup file contains the instruction to set up the required configuration for sunbird-user org service in the development environment. : https://github.com/Sunbird-Lern/userorg-service/blob/release-5.3.0/lernsetup.md

After setting up required configurations follow the this README.md file for setting running the admin web interface for keycloak 7. : https://github.com/Sunbird-Lern/userorg-service/blob/release-5.3.0/keycloak_local_setup/keycloak_local_setup.md
