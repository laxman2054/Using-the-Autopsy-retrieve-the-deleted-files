# Using-the-Autopsy-retrieve-the-deleted-files
## AIM:
To use Autopsy in Kali Linux to retrieve and analyze deleted files from a disk image.

## DESIGN STEPS:
### Step 1:
Open Autopsy and create a new case with appropriate case details.

### Step 2:
Add a disk image as a data source and let Autopsy analyze the content.

### Step 3:
Navigate to the "Deleted Files" section in Autopsy and examine or recover the deleted files.

## PROGRAM:
### **1. Copy Files to the Virtual Disk**  
- Open **File Explorer** → Go to the new drive (`C: or D:`), where the folder created in the New Virtual Disk
- Create a new folder (`Autospy`) and copy **images or files** into it.  

### **2. Delete the Files**  
- Select any one or two images → Press **Delete**.  
- Empty the **Recycle Bin** to permanently delete them.  

### **3. Recover Deleted Files Using Autopsy**  
### **Open Autopsy & Create a New Case** 

- Launch **Autopsy** and **Run as a administrator**  
- Click **Create New Case**.  

![image](https://github.com/user-attachments/assets/92923157-b1ef-4812-bd00-b4590e4a3661)

- Enter a **Case Name** (e.g., `Autopsy1`).  
- Choose a **Case Folder** location.  
- Click **Next** → Click **Finish**.  

![image](https://github.com/user-attachments/assets/f866d138-0b87-4539-a28b-1e09874925cd)

### **Add the Virtual Disk as an Evidence Source**  
- Click **Add Data Source**  → **Select Host**

![image](https://github.com/user-attachments/assets/51084192-b57c-4960-96fb-1da13f94993e)

- Select **Local Disk** → **next** 

![image](https://github.com/user-attachments/assets/1bfe3c9b-f463-4802-b9cf-ff1fa661c126)

- Select Disk → **Choose the VHD drive (`Drive1`)**

![image](https://github.com/user-attachments/assets/ab8b703e-f613-472b-b2a0-944069732425)

- Click **Next** → Keep default settings → Click **Finish**.  
- Wait for Autopsy to process the disk.  

### **Recover Deleted Files**  
- Go to **File Views** (left panel).  

![image](https://github.com/user-attachments/assets/3c69a803-b6c1-499f-b1c6-a4660b712920)

![image](https://github.com/user-attachments/assets/2fb0f0bf-4bbe-4ea6-acb1-3bc0664bfc89)

- Click **Deleted Files** → Find your deleted images.  
- Right-click an image → Click **Extract File**.  

![image](https://github.com/user-attachments/assets/128f3196-4367-4851-a158-73aaee0cd497)

- Select a folder to see the recovered files (e.g., `C:\forensic`).  
- Image is recovered successfully.


## Output :
### Folder before deleting the files
![image](https://github.com/user-attachments/assets/99c04e40-7485-4d86-ace7-901dd7994644)

### Folder after deleting the files
![image](https://github.com/user-attachments/assets/fb6bae9c-2deb-4f17-b290-d2b6c36cc804)

### Folder after extracting the deleted images using autopsy
![image](https://github.com/user-attachments/assets/579319d4-f6c8-4aec-a773-df4d8a61cb16)

## RESULT:
Deleted files were successfully retrieved and analyzed using Autopsy.
