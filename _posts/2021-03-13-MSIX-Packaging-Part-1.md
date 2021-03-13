---
published: false
layout: post
date: '2021-03-13 15:21 +0100'
author: Sander Speelman
categories: MSIX
---
## Introduction
During my work as an Application Specialist, I come across applications that need to be mass deployed to endpoints. Before that can happen the vendor either deliver unattended parameters to their installation process or they deliver another installation format like MSI.

Currently we do alot of this in App-v. However Microsoft is ending support for this format in 2026 and wants us to move to MSIX. So to kick of my blog I thought it might be a fun idea to make a little guide on how to get started with MSIX packaging.

By going through these steps, you will have a basic setup to start building MSIX packages.

I recommend to read the fundamentals of MSIX which can be downloaded [here](https://www.advancedinstaller.com/msix-packaging-fundamentals.html). Tim Mangan, Bogdan Mitrache and Kevin Kaminski did an excellent job.

To start with we need to create our packaging machine. On my laptop I use Hyper-v to run virtual machines. Using Hyper-V you can easily create a MSIX Packaging Tool Enviroment using Hyper-V Quick Create.

Step 1: Open Hyper-V Quick Create and select MSIX Packaging Tool Enviroment and click on Create Virtual Machine,
![2021-03-13 15_02_58-Hyper-V Manager.png]({{site.baseurl}}/_posts/2021-03-13 15_02_58-Hyper-V Manager.png)

Hyper-V will then download the latest version and create the virtual machine.
![2021-03-13 15_05_22-Hyper-V Manager.png]({{site.baseurl}}/_posts/2021-03-13 15_05_22-Hyper-V Manager.png)
