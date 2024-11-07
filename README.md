# Cloud Storage Management Lab Record

---

## Table of Contents
1. [Exercise 1: Creating an Instance](#exercise-1-creating-an-instance)
2. [Exercise 2: Creating a Volume](#exercise-2-creating-a-volume)
3. [Exercise 3: Attaching Volume to Instance](#exercise-3-attaching-volume-to-instance)
4. [Exercise 4: Creating Snapshots for Volumes](#exercise-4-creating-snapshots-for-volumes)
5. [Exercise 5: Hosting a Static Website using S3 Bucket](#exercise-5-hosting-a-static-website-using-s3-bucket)
6. [Exercise 6: Attaching Snapshot to an Instance](#exercise-6-attaching-snapshot-to-an-instance)
7. [Exercise 7: Migrating a File Between Storage Classes](#exercise-7-migrating-a-file-between-storage-classes)
8. [Exercise 8: Managing Access Control Over a File/Storage](#exercise-8-managing-access-control-over-a-filestorage)
9. [Exercise 9: Enabling Client and Server Encryption for an Object](#exercise-9-enabling-client-and-server-encryption-for-an-object)
10. [PDF Link](#pdf-link)

---

## Exercise 1: Creating an Instance
- **Aim**: To create an instance in AWS.
- **Procedure**:
    1. Go to AWS Console.
    2. Search for "EC2" and select it.
    3. Click on **Launch Instance**.
    4. Name your instance.
    5. Select or create a key pair for SSH access.
    6. Review and click **Launch**.
    7. The instance is created.

- **Result**: The instance is created successfully.

---

## Exercise 2: Creating a Volume
- **Aim**: To create a volume in AWS.
- **Procedure**:
    1. Go to AWS Console.
    2. Click on **EC2**.
    3. Scroll down and select **Volumes** under Elastic Block Store.
    4. Click **Create Volume**.
    5. Set the desired size.
    6. Click **Create Volume** to complete the creation.

- **Result**: The volume is created successfully.

---

## Exercise 3: Attaching Volume to Instance
- **Aim**: To attach a volume to an instance.
- **Procedure**:
    1. After creating a volume, right-click on it and select **Attach Volume**.
    2. Choose the instance from the dropdown menu and attach it.

- **Result**: The volume is attached to the instance successfully.

---

## Exercise 4: Creating Snapshots for Volumes
- **Aim**: To create a snapshot for a volume.
- **Procedure**:
    1. Go to AWS Console and open **EC2 Dashboard**.
    2. Under **Elastic Block Store**, click **Volumes**.
    3. Select the volume, right-click, and choose **Create Snapshot**.
    4. Confirm by clicking **Create Snapshot**.
    5. Go to **Snapshots** to view the created snapshot.

- **Result**: Snapshots for volumes are created successfully.

---

## Exercise 5: Hosting a Static Website using S3 Bucket
- **Aim**: To host a static website using an S3 bucket.
- **Procedure**:
    1. Go to AWS Console and select **S3**.
    2. Create a bucket and provide a name.
    3. Open the bucket, click **Upload**, and upload your static website files.
    4. In the **Properties** tab, enable **Static Website Hosting** and select **Host a static website**.
    5. Set bucket permissions to public in the **Permissions** tab.
    6. Copy the endpoint URL and visit it to see the hosted website.

- **Result**: The static website is hosted using an S3 bucket.

---

## Exercise 6: Attaching Snapshot to an Instance
- **Aim**: To attach a snapshot to an instance.
- **Procedure**:
    1. In AWS Console, go to **EC2 Dashboard** and then **Snapshots**.
    2. Select the snapshot and choose **Create Volume**.
    3. Go to **Volumes**, right-click the newly created volume, and select **Attach Volume**.
    4. Choose the instance from the dropdown menu and attach it.

- **Result**: The snapshot is attached to the instance successfully.

---

## Exercise 7: Migrating a File Between Storage Classes
- **Aim**: To migrate a file among different storage classes.
- **Procedure**:
    1. Open the S3 bucket and locate the file.
    2. Select **Actions > Change Storage Class**.
    3. Choose the target storage class and save changes.
    4. Confirm the updated storage class in the file’s properties.

- **Result**: The file is migrated between storage classes.

---

## Exercise 8: Managing Access Control Over a File/Storage
- **Aim**: To manage access control over a file or storage.
- **Procedure**:
    1. Open the S3 bucket, go to **Permissions**, and adjust the **Bucket Policy** or **ACL**.
    2. In IAM service, create policies for specific users to control access.
    3. Attach policies to grant users controlled access.

- **Result**: Access control is managed successfully.

---

## Exercise 9: Enabling Client and Server Encryption for an Object
- **Aim**: To enable client-side and server-side encryption for an object.
- **Procedure**:
    - **Client-Side Encryption**:
        1. Use an encryption library (e.g., AWS SDK) to encrypt the file on your machine.
        2. Upload the encrypted file to S3 and decrypt upon download.
    - **Server-Side Encryption (SSE)**:
        1. In the S3 upload process, enable **Server-Side Encryption**.
        2. Go to the **Properties** of the object, enable SSE, and save.

- **Result**: Client-side and server-side encryption are enabled for the object.

---

## PDF Link
[PDF of Lab Record](https://drive.google.com/drive/folders/1XcZzFs2ZvvzfBenlvbb27zxBH8wcVZiI?usp=sharing)
