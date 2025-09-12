# <img src="https://srtcdnstorage.blob.core.windows.net/software/nextgen/slserver/titansyslog48.png" alt="Titan Neo Server logo"> Titan Neo Server - Cloud Edition for Linux </img>

Thank you for choosing Titan Neo Server - Cloud Edition from South River Technologies. This is the Pay-as-you-go version of our solution, meaning that it will run fully featured without the need to purchase a license from South River Technologies. Simply fire up your Titan Neo Server VM, and run your business.

## What's on the VM?

This Titan Neo Server Virtual Machine (VM) contains a pre-built and pre-configured installation of the product.

## Features of Titan Neo Server

Titan Neo Server can be used with Titan SFTP or Titan MFT to provide AI capabilities to those products

## Usage Instructions / Getting Started

1) Connect securely to your instance over SSH using your own keypair or password.
2) Once you are connected to the instance terminal session the initial Titan Neo administrator account needs to be configured. To configure the Titan Neo administrator account, use the following command and supply your new administrator credentials. It's imporant to use a complex password consisting of a minimum of 8 characters in length, both upper and lower case, one or more numbers, and one or more special characters consisting of the following characters "(~!@#$%^&*_-+=`|\\(){}[]:;\"'<>,.?/)", and it must not included the username in the password.

```
sudo /opt/southriver/neoserver/aiserver /LASINIT /username=`<admin-username>` /password=`<admin-password>`
```

[Titan Neo Getting Started Guide](https://github.com/southrivertech/titanneo.pub/blob/main/cloud-marketplace/gettingstarted.pdf)


3) Once the Titan Neo administrative credentials have been established you can now connect to the Titan Neo web-based admin console through your web-browser by pointing it to https://`<ipaddress>`:46443. Note that this is a secure connection. However, since Titan Neo is using a temporary certificate, you will see a security warning in the browser. Proceed past the security warning and log in to the Titan Neo Server Admin console. At this point you will be able to configure the Titan Neo application including adding your own TLS certificate. To import your own certificate click on "Manage Certificate" in the "Local Domain" section to import your certificate, then select this certificate from the list in the domain dialog (click on edit action).

## Database and Files location

The Titan Neo database location is /var/southriver/neoserver/database. 

## Upgrading

The Titan software will periodically check for updates to the software and allow you to download the release notes and upgrade the software. You can also trigger a check for update manually from the Product Info tab in the admin user interface.

## Tech Support

Complimentary technical support is available on our website at https://helpdesk.southrivertech.com (use TitanNeoPAYG as your registration code)

## WebSite(s)

South River Technologies corporate WebSite:  [https://www.southrivertech.com](https://www.southrivertech.com)<br/>
Titan MFT (Enterprise grade Managed File Transfer Solution): [https://www.TitanMFT.com](https://www.TitanMFT.com)<br/>
Titan DMZ Server (Secure reverse proxy server for Titan MFT): [https://www.TitanDMZ.com](https://www.TitanDMZ.com)<br/>
Titan SFTP Server micro site: [https://www.TitanFTP.com](https://www.TitanFTP.com)<br/>
WebDrive (Virtual Drive Mapping Client): [https://www.WebDrive.com](https://www.webdrive.com)<br/>
