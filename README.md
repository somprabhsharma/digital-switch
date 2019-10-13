This project is about controlling the devices using phones, smart watch and other endpoint devices. This will make the devices smarter as you can use internal smart features of phones and watches and control these devices.
- You needs to create a Device in Amazon AWS IOT and then download 3 files `(certificate, private and public key)`, you can use `root-CA.crt` from this project as its the same.
- Then you need to compile and run the hardware code into your device of choice, here we have used MediaTek LinkIt one.
- Then you need to create an API server which connects your endpoint devices with the AWS IOT.
- Finally, you need to create the frontend Apps for you endpoint devices.

#Architecture

![architecture](https://farm6.staticflickr.com/5811/23273769223_df780f6cd4_b.jpg)
