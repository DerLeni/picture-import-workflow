# picture-import-workflow

Create a workflow to import camera pictures from SD-card(s) into local archive / workbench.
The process should
* Store images to archive into subfolders by date
  * Archive RAW images and if a similar JPEG co-exists, a scaled down version should also be archived
  * Archive single JPEG images
* Copy pictures from archive into workbench
  * Only RAW 'or' JPEG
* Clean up SD-Card