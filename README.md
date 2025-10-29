# Detecting-steganography-with-tools-like-StegExpose-analyzing-file-signatures

### Name : Mohammed ibrahim mn 
### Reg No : 212223100034

## AIM:
To detect hidden data using steganography detection tools like StegExpose and analyze file signatures for authenticity and manipulation.

# DESIGN STEPS:
## Step 1:
Install StegExpose or use the JAR version to detect steganography in image files.

## Step 2:
Run StegExpose on a directory of suspected image files using the command:

## Step 3:
Analyze file signatures using tools like file, binwalk, or xxd to check for inconsistencies or embedded content.

# PROGRAM:
StegExpose and File Signature Analysis Commands

## OUTPUT:
### 1.Install and Set Up StegExpose
• Download the StegExpose .jar file from the official repository. • Ensure Java Runtime Environment (JRE) is installed. • Run the tool on an image or a folder of images:\
• The output will list detection scores and a "suspect" verdict if steganography is found.

### 2.Scan Individual Files • Run StegExpose on a single image:
The tool uses statistical analysis methods like RS analysis, Sample Pair analysis, and Chi-square attack to detect hidden content.

### 3.Analyze File Signatures • Use Linux commands to verify the file's true format:
Every file type has a magic number (e.g., JPEG files start with FFD8). Comparing the actual signature with the file extension helps identify mismatches or embedded file tricks.

### 4. Cross-Check File Behavior • Rename the file (e.g., mv suspicious.jpg suspicious.zip) and try extracting it:
o Sometimes, files are disguised (e.g., a ZIP file hidden as a JPG), and this trick helps uncover such embedded archives.

### 5.Optional: Use Other Tools
o Tools like binwalk, stegsolve, or zsteg can be used for deeper analysis, especially for PNG files or binary dumps.

![image](https://github.com/user-attachments/assets/bcca4ee9-42f3-490e-ab65-e160c8ac0794)

![438094466-1a6903cd-cfa0-4fa7-837f-a34efa0a809c](https://github.com/user-attachments/assets/f4a36b69-b9ea-4319-b828-ae2123b19d6f)


![438095150-89fdac1b-baf2-4600-9490-f9eb4dd4eee1](https://github.com/user-attachments/assets/6fedf058-d672-4bbd-ac2c-5899800cc897)

![438095781-1482628d-4f2c-4a26-bfb1-62edd5b5efe1](https://github.com/user-attachments/assets/e266a1e1-d4fe-4209-bf15-71ec359aac89)


![438102343-4400dbfd-0fc9-4233-a6f3-9261bb569eca](https://github.com/user-attachments/assets/ebedee28-3a7d-4437-8cce-a3a664625983)



# RESULT:
Hidden data was successfully detected and file signatures were analyzed for irregularities.
