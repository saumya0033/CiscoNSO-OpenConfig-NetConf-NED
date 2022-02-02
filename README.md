# CiscoNSO-OpenConfig-NetConf-NED
Create OpenConfig-Netconf NED in NSO using Openconfig yang files and implement a netsim device in NSO based on OpenConfig YANG modules.

1- Download and install Cisco NSO from -- https://developer.cisco.com/docs/nso/#!getting-and-installing-nso 
follow the guidelines as described in the document.

Some additional helping packages which are good to have are as below.. 
2- Download and install Confd from Tail-f portal.
3- Download and install pioneer package from https://github.com/saumya0033/pioneer 
*there are some issues with this*.
*Also, as per Tail-F document on 'how to work with NSO' ---- chrome-extension://efaidnbmnnnibpcajpcglclefindmkaj/viewer.html?pdfurl=https%3A%2F%2Finfo.tail-f.com%2Fhubfs%2FWhitepapers%2FTail-f%2520NSO%2520interop%2520User%2520Guide%2520V2%2520Rev%2520H%25202019-11-20.pdf&clen=873805&chunk=true 
“Building and Installing a NED using the NETCONF NED Builder” describes how to build a NETCONF NED for managing the connected devices.  It is important to note that the NETCONF NED Builder is now a built-in feature of NSO starting with NSO 5.2 and it replaces  the  need  for  installing  the  Pioneer  package  as  was  previously  required  and discussed  in  an  earlier  version  of  this  guide.

4- The process to create OpenConfig based NED is explained here - https://community.cisco.com/t5/nso-developer-hub-discussions/nso5-5-failes-to-create-openconf-netconf-ned/m-p/4539234/thread-id/6778 
*this process doesn't create the netsim direcotry so, you can't generate any netsim devices based on this*.
*Also, even if you create netsim directory by going straight for ncs-make-package command, even then it's giving errors related to the netsim folder not being present.

