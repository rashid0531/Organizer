# Organizer

Application that detects images of same names and then checks if they exactly are same, if no, then renames the files and saves it to the same repo to prevent contentions in naming (duplicated name with 'copy' or '(1)' name in the files), if yes, then deletes the redundant copies to save disk space. 

One of the real life usecase is, when I import images from several sources (iphone, ipad, or SSD) and save them into the same folder, the images can have identical name (e.g IMG_777) and in that case, the identical files are named with postfix like img_number (IMG_777_1) or 'img_copy' depending on the OS that you are using. If the images are actually identical then this application will keep only one copy and delete the rest of them however if not then the similarly named images will be renamed to something else.
