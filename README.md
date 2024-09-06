# Assignment: Working with Virtual Machines in Azure and GCP

## Objective
The objective of this assignment is to provide hands-on experience with managing Virtual Machines (VMs) in both Azure and Google Cloud Platform (GCP). You will learn how to start, stop, and monitor the costs associated with running VMs on these cloud platforms.

### 1. Start and Stop a Virtual Machine
- **Azure:**
  - Navigate to the Azure portal and create a new Virtual Machine.
  - Choose a basic configuration (e.g., Ubuntu Server, Standard B1s size).
  - Start the VM and allow it to run for a few minutes.
  -   ![Screenshot_6-9-2024_102649_portal azure com](https://github.com/user-attachments/assets/6bd294c5-bf96-4251-bd66-b8e6d650b595)
  - Stop the VM and take note of the actions you took.
  - 
       After creating the Azure VM I notcies a few problems with the size optioning, When I was able to select an option this error still came up. What I notice though is that it estimate the total cost to run the VM monthly based on the sizing option.
    
- **GCP:**
  - Access the Google Cloud Console and create a new VM instance using Compute Engine.
  - Select a basic configuration (e.g., Debian GNU/Linux, e2-micro instance type).
  - Start the VM and let it run for a few minutes.
  - Stop the VM and document the steps you followed.
 
  - 
![Screenshot_6-9-2024_11503_console cloud google com](https://github.com/user-attachments/assets/1276a33b-cfcd-4b8f-a601-18bb4e68d042)

  -   Login to google cloud platform and created a new instance, verified that everything was in basic ocnfiguration. and created the VM instance. After running for a few minutes that instance status provided a green checkmark and gave us relative actions. like bining report, monitor VM, backup . To the side of the instance were 3 little dots to the side where I was able to stop VM.

### 2. Monitor VM Costs
- **Azure:**
  - After starting and stopping the VM, navigate to the Cost Management and Billing section.
  - Find the cost associated with running your VM for the time it was active.
   ![Screenshot_6-9-2024_11358_portal azure com](https://github.com/user-attachments/assets/395a1013-6cff-443f-8a82-d0c4f9810602)
- **GCP:**
  - In the GCP Console, go to the Billing section and identify the cost incurred by your VM during its runtime.
  
![Screenshot_6-9-2024_115655_console cloud google com](https://github.com/user-attachments/assets/04765320-7678-4c4f-9806-f2c401606219)


### 3. Compare and Reflect
- Compare the costs of running a VM in Azure versus GCP. Consider factors such as the configuration used, the duration for which the VM was active, and any differences in cost visibility between the platforms.

  I am not to sure if google was correct , or if google doesn't populate the instance that way and it uses credits but when checking it stated $0.00. It realistic is probably not but because it only goes to the nearest 10th I assume that the cost was reletively low. As for Azure. Instantly it populate the amount of it utilizes over a estimated monthly period as soon as it is created which is nice visually .
  
- Reflect on the ease of starting, stopping, and monitoring VMs on each platform. Which platform did you find more intuitive or user-friendly? Why?
- OVerall using both google and Azure cloud platforms to start, stop , and monitoring VM's google is much easier than Azure's platform. I found initating it was easy and no hops to overcome to start the actual VM. Googles stop feature was also super easy. I like though as noted in the previous question. Azure doesn't hind the fee, it is right there as soon as you create the VM which is really nice becuase compared to google. I feel like I didn't have to search or go to a different page in order to find the amount it used based on utilization

