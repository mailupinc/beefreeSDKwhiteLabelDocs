# How to Move Files

You can move files within the File manager using the move icon. You can access the move icon on the file within the File manager. The move icon is a folder with an arrow pointing right inside it. Use this icon to move files.

To move a file, take the following steps:

1. Enter your File manager.
2. Navigate to the file you would like to move.
3. Click the **Move** icon.

A popup will appear displaying a list of destinations for your file.

4. Select the file’s new destination from the list.
5. Click **Move** to confirm the action.

The following GIF shows an example of how to move files to new destinations within the File manager. It also shows an example of how the file URL remains the same as it travels between destinations.

<figure><img src="https://lh7-eu.googleusercontent.com/l8V8SahKaiMP4ARv_ykwpixjhbZMWGnUBXEu6K-VJDUQJezRYaUgVpMapt8e4FC-_payleKHQBdNtB7ZCr0sT7zEj1-Ajr4q58a_hvqLFss-g9Re_LJxptxkhxjKyQlUaS1NoZaGwph0IzXMcezgoJA" alt="A GIF displaying an example of how to use the move icon to move files to new destinations"><figcaption></figcaption></figure>

### Considerations

Consider the following regarding the new File manager functionality:

* When you upload new files to the File manager, the URL will have a new format compared to previously uploaded files.
* Your existing file URLs will remain the same as before.
* When you move files within the File manager, the URL does not change.
* If there is a name conflict, the File manager will ask if you want to replace the image, keep both images, or cancel the upload.&#x20;
  * **Action: Click "keep":** The image uploads with a new name, adding a suffix like \_1. Suffixes increment to a maximum of \_50 in case of conflicts.
  * **Click "replace":** The new image will overwrite the old one and appear in the File Manager. Once the CDN cache expires, you will see the updated content when browsing the URL. **Note:** The move feature also updates the content at served URLs, allowing for widespread alterations to an image's content when its URL is commonly used.
  * **Click on "cancel":** The upload will be canceled.
* After a file is deleted, the URL is unreachable when the CDN cache expires.

The following image shows an example of the modal that appears in the event there is a name conflict.

<figure><img src="../../.gitbook/assets/CleanShot 2024-05-03 at 15.30.44@2x.png" alt="Modal informing the end user that there is a name conflict and two files in the same folder have the same name. The end user can keep both files, or replace the existing file with the new file. They can also cancel the action." width="563"><figcaption></figcaption></figure>

