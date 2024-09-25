
# Twingate Zero Trust Security Network Setup Using Twin Gate


## Overview

![MAST HEAD](https://github.com/user-attachments/assets/8026ef35-9784-4974-9eeb-beb515d8cebd)

In this project, I demonstrate the setup of a Zero Trust Security Network using Twingate. This setup connects devices like a laptop, mobile, and iPad to AWS, ensuring secure and continuous verification of access.

## Why Zero Trust?
Zero Trust Networks continuously verify every access request, ensuring a higher level of security than traditional VPNs. With Twingate, I can seamlessly secure connections across multiple devices.

## Tools Used:
- **Twingate** for Zero Trust Network setup
- **AWS** as the cloud infrastructure
- **macOS, iPadOS, iOS/Android** for device integration

## Security Benefits of Zero Trust with Twingate
1. Continuous access verification.
2. No reliance on traditional perimeter security (VPN).
3. Simple and secure device management.

## Steps to Set Up Twingate

### 1. Setting Up Twingate on a Laptop
1. Sign up for a Twingate account at [Twingate](https://www.twingate.com).

## 3. ![twigate success sign in ](https://github.com/user-attachments/assets/9b3102ce-1aff-41a0-a4e9-133d881869a5)
## 4. After a successful sign in, you add a remote network for which will host your instance in AWS

## 5.  ![TG add remote network](https://github.com/user-attachments/assets/bae1048d-167c-4bd5-8382-2940e1a8d5b0)


## 6. You copy these code and paste in your power shell to create the instances

  ![Connector deployment instructions](https://github.com/user-attachments/assets/1b3b6794-f61c-4861-8528-74b11e556015)

## 7.   Create a new network and configure resources (e.g., AWS EC2 instances).

   ![INSTANCES ](https://github.com/user-attachments/assets/8eae2aae-77b1-48b7-abf8-27abc2ed58bd)


## 8. On your Twingate GUI you see the green dot indicating a successful connection deployment

  ![twingate connected to ec2](https://github.com/user-attachments/assets/1def9b1c-e3d6-47df-9920-83486d90092f)




After the instance is created for your test, make sure there is no public IP we are only authenticating with the private Ip of the test EC2 instance

![no public IP](https://github.com/user-attachments/assets/f7d2e08a-aa68-4aa9-a05c-0eb18249f700)

## 9.We need to create resources with our private IP address, providing granular access control to our resources

![aaaddd resources](https://github.com/user-attachments/assets/c382f02f-5927-424e-a6b7-dddb0a4c6a78)

![granular access](https://github.com/user-attachments/assets/4ce16e44-fb85-456f-a469-47c87c8abea1)

Access has been granted to my EC2 via Twingate

![access granted ](https://github.com/user-attachments/assets/fd96ebba-1bdd-4dd4-9e99-2ec3b44b5f0b)

From the aws cloud shell and my m
local machine i was able to ping my EC2 with the help of my private IP.

![ping test](https://github.com/user-attachments/assets/7adcefa3-bae6-468b-ac15-e1532f682148)


Further test with mt android device .

![remote android connection](https://github.com/user-attachments/assets/daa4e51a-ffa6-4716-bf00-1438c6759e55)


Yon can connect as many machine to gain granular access to resources. The fact that it re-authenticates continuoisly is a must try for sensitive infrastructure


Twingate can integrate well with a variety of IdP (Identity Providers) see some sample below.

![IdP](https://github.com/user-attachments/assets/64806f51-a251-49be-8fad-8c5e58b4d903)


## Video Walkthrough
Here is a link to a video where I walk through the entire setup:


Not by me but one of my mentors in the field feel free to like, share and subcribe to his channel.


Rahul Wagh
https://www.youtube.com/watch?v=l_tgiXEsEgU&t=364s




