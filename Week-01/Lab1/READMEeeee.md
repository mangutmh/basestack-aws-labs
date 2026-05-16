# Lab Name: IAM User Creation & MFA Setup

## Overview
Brief description of what this lab is about and what problem it solves.

## Learning Objectives
- Create an IAM user with least-privilege permissions
- Enable MFA on the root and IAM accounts
- Understand the difference between root and IAM users

## AWS Services Used
- AWS IAM (Identity and Access Management)
- AWS Console

## Prerequisites
- AWS account (free tier)
- MFA device (Google Authenticator or Authy)

## Step-by-Step Instructions

### Step 1: Log in to AWS Console
1. Go to https://console.aws.amazon.com
2. Sign in with your root account email
3. Navigate to IAM service

### Step 2: Create IAM User
1. Click **Users** in the left sidebar
2. Click **Add users**
3. Enter username: `basestack-admin`

*(continue for each step...)*

## Screenshots
![IAM Dashboard](../../screenshots/week01-iam-dashboard.png)
![User Created](../../screenshots/week01-iam-user-created.png)

## Key Concepts Learned
- The root account should NEVER be used for day-to-day operations
- IAM policies follow the principle of least privilege
- MFA adds a critical second layer of security

## Challenges Faced & Solutions
| Challenge | Solution |
|-----------|----------|
| MFA QR code not scanning | Increased screen brightness and tried a different angle |
| Permission denied error | Attached the correct policy to the IAM user |

## Cleanup
To avoid charges, the following resources were deleted after the lab:
- IAM user `basestack-admin` was disabled (kept for practice)

---
*Completed: May 2026 | BaseStack AWS Cloud Accelerator — Cohort 1*
