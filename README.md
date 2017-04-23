# seaf-share.py
python script for Seafile downloading/uploading share link

# Usage scenario
Download/upload shared file or directory from/to Seafile shared link without using the web browser. 

# Features
- Support the download and upload shared link
- Support the password protected link
- Support the link for a single file or directory

# Dependency
- For Ubuntu 16.04
``sudo apt install python-pip``
``pip install clint``
``pip install requests``
``pip install requests_toolbelt``

# Example
- Download a shared directory to current directory
``python seaf-share.py get https://share_url ./``
- Upload the directory "test" to a shared link
``python seaf-share.py put https://share_url ./test``
