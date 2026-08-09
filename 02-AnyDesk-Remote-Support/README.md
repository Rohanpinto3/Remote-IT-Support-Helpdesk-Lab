# Remote Troubleshooting Using AnyDesk (Hands-On Lab)
### Project Overview
In this hands-on lab, I implemented and tested remote desktop troubleshooting using AnyDesk to simulate real-world IT support scenarios. The objective was to gain practical experience in remote access configuration, client support, connectivity troubleshooting, and basic software assistance, similar to tasks performed by Help Desk and IT Support Technicians in production environments.

#### Tools & Environment
  * AnyDesk Remote Desktop Software
  * Windows 10 / Windows 11
  * Two separate devices (Local support machine and Remote client machine)
  * Stable internet connection

#### Lab Objectives
  * Install and configure AnyDesk on multiple devices
  * Establish secure remote connections
  * Simulate common user issues during remote sessions
  * Troubleshoot connectivity and software-related problems
  * Practice clear communication and support workflow

#### Step 1: Installing AnyDesk
I downloaded AnyDesk from the official website and installed it on both the support machine and the client machine.

##### During installation, I verified:
  * AnyDesk service was running
  * The device generated a unique AnyDesk address
  * Outbound and inbound connections were allowed
    <img width="1920" height="1040" alt="image" src="https://github.com/user-attachments/assets/8cc47238-9152-4154-89ca-b9466fb060b0" />


#### Step 2: Configuring AnyDesk for Remote Access
On the client machine, I configured AnyDesk to allow remote connections by:
  * Enabling Unattended Access
  * Setting a secure password
  * Adjusting permission settings for keyboard, mouse, and file transfer
  * Verifying firewall rules did not block the connection
This setup simulates a real user workstation that requires remote IT assistance.
  <img width="1920" height="1038" alt="image" src="https://github.com/user-attachments/assets/24720a68-52da-4282-8931-c070637c3f8c" />


#### Step 3: Establishing a Remote Connection
From the support machine, I entered the client’s AnyDesk address and initiated a remote session.

I confirmed:
  * Successful authentication
  * Full desktop access
  * Responsive keyboard and mouse control
  * Stable connection quality
This step mirrors how IT support staff remotely access employee systems for troubleshooting.




#### Step 4: Simulated User Support Scenarios
I simulated multiple common help desk issues, including:

##### Scenario 1: Connectivity Issue
The client reported intermittent connection drops.

##### Troubleshooting steps taken:
  * Checked AnyDesk connection status and latency
  * Verified internet stability on the client machine
  * Restarted AnyDesk service
  * Re-established the remote session successfully



##### Scenario 2: Software Installation Assistance
The client required help installing a third-party application.

##### Actions performed:
  * Remotely guided the user through the download process
  * Installed the software on the client machine
  * Verified successful installation
  * Confirmed application functionality
This reflects real-world remote assistance for end users unfamiliar with software installation.




#### Step 5: Security and Best Practices
During the lab, I followed standard IT security practices:
  * Used strong passwords for unattended access
  * Avoided leaving permanent access enabled after support
  * Ensured user consent before remote control
  * Logged out and terminated sessions properly
    <img width="1920" height="1038" alt="image" src="https://github.com/user-attachments/assets/28507152-6fa8-4dd3-9e70-3b60234d9303" />

#### Outcome & Skills Demonstrated
Through this project, I demonstrated:
  * Remote desktop configuration and management
  * Basic network and connectivity troubleshooting
  * User-focused technical support
  * Secure remote access handling
  * Real-world Help Desk workflow simulation

### Conclusion
This lab strengthened my practical understanding of remote IT support, a core responsibility of Help Desk and IT Support roles. Using AnyDesk allowed me to simulate real support scenarios involving connectivity issues, software installation, and end-user assistance in a controlled environment.
