# instasave
Instagram Image Downloader - Fill Size Original

# Rquired Dependencies
* Flask
* Beautiful Soup
* Requests

# Use
* Enter Image URL - https://www.instagram.com/p/BwCQQkiBnvX/ and Click Download Button.
* Right Click On Image >> Click On 'Save Image' Option.

# How it works?
* We scrap the page for 'script' tag.
* Convert paticular tag contents into JSON.
* Output the image link which is used by Flask to render inside img tag.
