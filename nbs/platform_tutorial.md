# Trusted Research Environment User Guide

Trusted Research Environment (TRE) is a cloud solution that provides secure access to data, tooling, and compute power that researchers need. Researchers can focus on achieving research missions and completing essential work in minutes in a trusted research environment.

# Getting Started

## Sign Up

Use this section if this is your first time connecting to the system.

1. Open your browser and navigate to the TRE URL.
1. Click on the **Sign up** link.

![](platform_imgs/Aspose.Words.eb2aa5b5-7f63-4203-881b-2ae5083537c6.001.png)

3. Fill out your **Username** (email address), **Name**, **Family name** and pick a **Password.**

![](platform_imgs/Aspose.Words.eb2aa5b5-7f63-4203-881b-2ae5083537c6.002.png)

4. Click the **Sign up** button.

## Login

1. Open your browser and navigate to the TRE URL.
1. Type in your **Username** (the email you used to sign up) and your **Password.**
1. Click the **Sign In** button.

![](platform_imgs/Aspose.Words.eb2aa5b5-7f63-4203-881b-2ae5083537c6.001.png)

## User Interface

![](platform_imgs/Aspose.Words.eb2aa5b5-7f63-4203-881b-2ae5083537c6.003.png)

**Dashboard** - Displays AWS charges over the past 30 days

**SSH Keys** - SSH Keys for EC2 authorization

**Studies** - Data sets saved in Amazon S3

**Workspaces** - The combination of a study with a compute![](platform_imgs/Aspose.Words.eb2aa5b5-7f63-4203-881b-2ae5083537c6.004.png)

# Using Trusted Research Environment

## Launching a new Research Environment

A user can select a Study or multiple Studies and launch a Workspace to access and analyze data. To launch a Research Environment, follow these steps:

1. In the portal navigate to the **Studies** page using the menu on the left.
1. Select the Studies to be attached to the new Workspace.
1. Once you have selected all the Studies you want, click the **Next** button.

![](platform_imgs/Aspose.Words.eb2aa5b5-7f63-4203-881b-2ae5083537c6.005.jpeg)

4. Choose the type of Workspace you want and click the **Next** button.

![](platform_imgs/Aspose.Words.eb2aa5b5-7f63-4203-881b-2ae5083537c6.006.jpeg)

5. Type a name for the Workspace in the **Name** field.
5. Select a project that this Workspace will belong to in the **Project ID** drop down field.
5. Select the **Configuration** type.

Configuration types:

1. **Jupyter Notebook General** - for general usage
1. **Jupyter Notebook CPU** - CPU intensive
1. **Jupyter Notebook Memory** - memory optimized
1. **Jupyter Notebook GPU** - GPU intensive
8. Type a description for the Workspace in the **Description** field.
9. Click the **Create Research Workspace** button.

This will deploy the new Workspace and attach the Studies that were selected. You will automatically be redirected to the Workspaces tab on the portal.

![](platform_imgs/Aspose.Words.eb2aa5b5-7f63-4203-881b-2ae5083537c6.007.jpeg)

## Connecting to an Existing Research Environment

1. In the portal navigate to the **Workspaces** page using the menu on the left.
1. Click on the **Connections** button, below the **Workspace** name.

![](platform_imgs/Aspose.Words.eb2aa5b5-7f63-4203-881b-2ae5083537c6.008.jpeg)

3. Click on the **Generate URL** button on the right, under HTTP Connections.

![](platform_imgs/Aspose.Words.eb2aa5b5-7f63-4203-881b-2ae5083537c6.009.jpeg)

4. Click on the **Copy icon** to copy the notebook link, and click **Connect.**

![](platform_imgs/Aspose.Words.eb2aa5b5-7f63-4203-881b-2ae5083537c6.010.jpeg)

5. Wait for the system to load.

![](platform_imgs/Aspose.Words.eb2aa5b5-7f63-4203-881b-2ae5083537c6.011.jpeg)

6. Click on the Apps icon on the top left, and pick **Chrome.**

![](platform_imgs/Aspose.Words.eb2aa5b5-7f63-4203-881b-2ae5083537c6.012.jpeg)

7. Click the paste icon in the top menu, and paste the notebook URL you copied on **Step 4**.

![](platform_imgs/Aspose.Words.eb2aa5b5-7f63-4203-881b-2ae5083537c6.013.jpeg)

8. Go to **Chrome**, right click and **Paste/Paste and go to.**

![](platform_imgs/Aspose.Words.eb2aa5b5-7f63-4203-881b-2ae5083537c6.014.jpeg)

9. You can now access your Jupyter Notebook.

![](platform_imgs/Aspose.Words.eb2aa5b5-7f63-4203-881b-2ae5083537c6.015.jpeg)

## Attach Files to a Research Environment

**Create a Study**

1. Navigate to the **Studies** page using the menu on the left.
1. Click the **Create Study** button.

![](platform_imgs/Aspose.Words.eb2aa5b5-7f63-4203-881b-2ae5083537c6.016.jpeg)

3. Provide an ID for the Study in the **ID** field.
4. Choose either **My Study** or **Organizational Study** as the type of Study you are creating.
4. Enter a name for the Study in the **Name** field.
4. Enter a description for the Study in the **Description** field.
4. Select the **Project** that this Study relates to in the **Project ID** drop down field.
4. Click the **Create Study** button.

![](platform_imgs/Aspose.Words.eb2aa5b5-7f63-4203-881b-2ae5083537c6.017.jpeg)

**Upload files to a Study**

1. Navigate to the **Studies** page using the menu on the left.
1. Find the Study on the list and click **Upload Files** on the right.
1. You can upload files either by dragging and dropping, or by clicking the **Upload Files** or **Upload Folder** button.

**Attach Study to Research Environment**

1. Navigate to the **Studies** page using the menu on the left.
1. Mark the **Study** checkbox and follow the instruction on creating a new Research Environment .

## Collaborating and Sharing Data Between Environments

TODO

![](platform_imgs/Aspose.Words.eb2aa5b5-7f63-4203-881b-2ae5083537c6.018.png) shared storage - cd /efs inside 2 jupyter notebooks

Terminating a Research Environment

When you no longer need a Research Environment you can terminate it. Follow these steps:

1. In<a name="_page8_x0.00_y588.94"></a> the portal navigate to the **Workspaces** page using the menu on the left.
1. In the list of Workspaces, find the Workspace that you want to terminate.
1. Click on the **Terminate** button, the Workspace must be in the **Ready** state to terminate it.

![](platform_imgs/Aspose.Words.eb2aa5b5-7f63-4203-881b-2ae5083537c6.008.jpeg)

# Tools Installation

## Installing Python Packages TODO

Installing Linux Packages

<a name="_page9_x0.00_y396.60"></a>TODO
