# Twin-Gate-Zero-Trust-Network-No-VPN-
Say no to traditional VPN


# Twingate Zero Trust Security Network Setup

## Overview
In this project, I demonstrate the setup of a Zero Trust Security Network using Twingate. This setup connects devices like a laptop, mobile, and iPad to AWS, ensuring secure and continuous verification of access.

## Why Zero Trust?
Zero Trust Networks continuously verify every access request, ensuring a higher level of security than traditional VPNs. With Twingate, I can seamlessly secure connections across multiple devices.

## Tools Used:
- **Twingate** for Zero Trust Network setup
- **AWS** as the cloud infrastructure
- **macOS, iPadOS, iOS/Android** for device integration

## Steps to Set Up Twingate

### 1. Setting Up Twingate on a Laptop
1. Sign up for a Twingate account at [Twingate](https://www.twingate.com).

2. 
3. ![twigate success sign in ](https://github.com/user-attachments/assets/9b3102ce-1aff-41a0-a4e9-133d881869a5)
4. After a successful sign in, you add a remote network for which will host your instance in AWS

5.  ![TG add remote network](https://github.com/user-attachments/assets/bae1048d-167c-4bd5-8382-2940e1a8d5b0)


6.8. You copy these code and paste in your power shell to create the instances

  ![Connector deployment instructions](https://github.com/user-attachments/assets/1b3b6794-f61c-4861-8528-74b11e556015)

7.
8.   Create a new network and configure resources (e.g., AWS EC2 instances).

9. ![INSTANCES ](https://github.com/user-attachments/assets/8eae2aae-77b1-48b7-abf8-27abc2ed58bd)



10. 
After the instance is created
11. Download the Twingate client for your laptop (Windows, macOS, or Linux).
12. Install and sign in with your credentials.
13. Follow the setup wizard to connect your laptop to the Zero Trust Network.

### 2. Setting Up Twingate on an iPad
1. Download Twingate from the App Store.
2. Sign in and follow instructions to connect the iPad to the network.

### 3. Setting Up Twingate on a Mobile Device
1. Download Twingate from the App Store or Google Play Store.
2. Sign in and complete the setup for Zero Trust access on mobile.

## AWS Integration
- Connect to AWS resources securely using Twingate. This allows only authorized devices to access sensitive cloud resources.
- Set up AWS security groups and IAM roles to ensure seamless integration with Twingate.

## Video Walkthrough
Here is a link to a video where I walk through the entire setup:
[Link to YouTube Video]

## Screenshots
Include screenshots of Twingate running on different devices and how they connect to your AWS network.

## Security Benefits of Zero Trust with Twingate
1. Continuous access verification.
2. No reliance on traditional perimeter security (VPN).
3. Simple and secure device management.
