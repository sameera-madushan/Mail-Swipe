# Mail-Swipe | Keep your real mailbox clean and secure. 

Mail Swipe is a python script that helps you to create temporary email addresses and receive emails at that address. It uses the API provided by [1secmail](https://www.1secmail.com/api/) to create emails addresses and fetch emails.

You can either generate your own email address or you can generate a random email address using this script. Once you receive an email it will be save in a text file inside the **"All Mails"** folder.

***For security reason you cannot read messages from addresses: abuse@domain, webmaster@domain, contact@domain, postmaster@domain, hostmaster@domain, admin@domain. All other addresses are free to use.*** - 1secmail team -

![mailswipe](https://user-images.githubusercontent.com/55880211/94339230-e61e7100-0015-11eb-942a-cd1085179ff4.gif)

## Git Installation
```
# clone the repo
$ git clone https://github.com/sameera-madushan/Mail-Swipe.git

# change the working directory to Mail-Swipe
$ cd Mail-Swipe

# install the requirements
$ pip3 install -r requirements.txt
```

## Usage

```
python mailSwipe.py
```

## Credits
This script is inspired by [sdushantha's](https://github.com/sdushantha) [tmpmail](https://github.com/sdushantha/tmpmail) script. 

Special thanks to [Sandakelum Priyamantha](https://github.com/wijewardhane).

Special thanks to devolopers of [1secmail](https://www.1secmail.com/api/) API. 
