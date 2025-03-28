# Surveying and Preserving the Digital Crime Scenes

## **Aim:**
Data recovery from unallocated space, using forensic tools(Autospy) to extract and analyze data.

## **Implementation steps:**

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
<img width="952" alt="Screenshot 2025-03-27 at 8 35 12 PM" src="https://github.com/user-attachments/assets/2f9ef0fc-15bc-43b4-81ba-06e3fa8113d0" />



- Enter a **Case Name** (e.g., `Autopsy1`).  
- Choose a **Case Folder** location.  
- Click **Next** → Click **Finish**.  
<img width="1291" alt="Screenshot 2025-03-27 at 8 36 19 PM" src="https://github.com/user-attachments/assets/be55be40-5616-408a-a0e0-37d53d63f603" />



### **Add the Virtual Disk as an Evidence Source**  
- Click **Add Data Source**  → **Select Host**
<img width="1288" alt="Screenshot 2025-03-27 at 8 37 26 PM" src="https://github.com/user-attachments/assets/5d67cc77-3479-4e20-b862-d333ecbe0484" />



- Select **Local Disk** → **next** 
<img width="1293" alt="Screenshot 2025-03-27 at 8 38 15 PM" src="https://github.com/user-attachments/assets/602458dd-5b9a-4469-bbe3-57f2989f02ff" />



- Select Disk → **Choose the VHD drive (`Drive1`)**

<img width="1291" alt="Screenshot 2025-03-27 at 8 38 57 PM" src="https://github.com/user-attachments/assets/926ebba2-93d0-42f0-a431-e1968533af7b" />


- Click **Next** → Keep default settings → Click **Finish**.  
- Wait for Autopsy to process the disk.  

### **Recover Deleted Files**  
- Go to **File Views** (left panel).  
<img width="1290" alt="Screenshot 2025-03-27 at 8 39 35 PM" src="https://github.com/user-attachments/assets/7871ddcd-05fa-4ce1-80ac-bb0a95ddde4e" />




<img width="1291" alt="Screenshot 2025-03-27 at 8 39 55 PM" src="https://github.com/user-attachments/assets/1e1f01e1-9ba9-48ae-8e4b-3ccae0ff7c9d" />






- Click **Deleted Files** → Find your deleted images.  
- Right-click an image → Click **Extract File**.  
<img width="1291" alt="Screenshot 2025-03-27 at 8 41 11 PM" src="https://github.com/user-attachments/assets/1cccb3a2-d540-4faa-8c56-58eb8f2803a0" />



- Select a folder to see the recovered files (e.g., `C:\forensic`).  
- Image is recovered successfully.


## Output :
### Folder before deleting the files
<img width="1680" alt="Screenshot 2025-03-27 at 8 47 46 PM" src="https://github.com/user-attachments/assets/d8710eed-32c3-4e45-ab83-d4197a4c0284" />


### Folder after deleting the files
<img width="1680" alt="Screenshot 2025-03-27 at 8 49 54 PM" src="https://github.com/user-attachments/assets/eca5f441-7077-4df5-9e75-cc6d76824e68" />





### Folder after extracting the deleted images using autopsy
<img width="1680" alt="Screenshot 2025-03-27 at 8 51 12 PM" src="https://github.com/user-attachments/assets/e0afa1b6-81e4-44d8-9c0d-f3387d2649ab" />


## Result:
Successfully extracted the deleted files from unallocated space using the Autospy tool.
