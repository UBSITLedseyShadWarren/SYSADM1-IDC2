+-----------------------+-----------------------+-----------------------+
| ![](vertopal_5        |                       |                       |
| f230b20d77d417da1cd65 |                       |                       |
| 1243ef9c10/media/imag |                       |                       |
| e1.png){width="2.4in" |                       |                       |
| height="0.5875in"}    |                       |                       |
|                       |                       |                       |
| SCHOOL OF INFORMATION |                       |                       |
| AND TECHNOLOGY        |                       |                       |
+=======================+=======================+=======================+
| > NAME: Ledsey Shad   | > DATE PERFORMED:     |                       |
| > Warren A            | > 12/9/2024           |                       |
+-----------------------+-----------------------+-----------------------+
| > Section: IDC2       | > DATE                |                       |
|                       | > SUBMITTED:12/9/2024 |                       |
+-----------------------+-----------------------+-----------------------+

SYSADM1 -- Managing Services in Linux\
Requirement:\
• A virtual machine running Linux

![](vertopal_5f230b20d77d417da1cd651243ef9c10/media/image2.png){width="4.136111111111111in"
height="1.8027777777777778in"}

Complete this lab as follows:\
1. Use the service --status-all command to list all active and inactive
services.\
List down active and inactive services in the table below. Provide five
(5) services for each column.

+-----------------------------------+-----------------------------------+
| **Active**                        | **Inactive**                      |
+===================================+===================================+
| > Cron                            | > Bluetooth                       |
+-----------------------------------+-----------------------------------+
| > dbus                            | > Alsa-utils                      |
+-----------------------------------+-----------------------------------+
| > cups                            | > Grub-common                     |
+-----------------------------------+-----------------------------------+
| > Annacron                        | > saned                           |
+-----------------------------------+-----------------------------------+
| > apparmor                        | > rsync                           |
+-----------------------------------+-----------------------------------+

> SS:
>
> ![](vertopal_5f230b20d77d417da1cd651243ef9c10/media/image3.png){width="6.688888888888889in"
> height="5.031944444444444in"}

2\. Start the Bluetooth service using the systemctl command.

> Ex. sudo systemctl start httpd

  ---------------------------------------------------------------------------------------------
  ![](vertopal_5f230b20d77d417da1cd651243ef9c10/media/image4.png){width="4.359721128608924in"
  height="1.1875in"}
  ---------------------------------------------------------------------------------------------

  ---------------------------------------------------------------------------------------------

3\. Check the status of the Bluetooth service. What is its status?

Page **2** of **4**

> SS:
>
> ![](vertopal_5f230b20d77d417da1cd651243ef9c10/media/image5.png){width="7.027777777777778in"
> height="2.5277777777777777in"}

4\. Check the status of the cups services. Since when was it running?
SS:

> ![](vertopal_5f230b20d77d417da1cd651243ef9c10/media/image6.png){width="7.027777777777778in"
> height="4.177777777777778in"}

5\. Stop cups services.

> ![](vertopal_5f230b20d77d417da1cd651243ef9c10/media/image7.png){width="7.027777777777778in"
> height="0.8569444444444444in"}

6\. Verify if the service was stopped.

Page **3** of **4**

> ![](vertopal_5f230b20d77d417da1cd651243ef9c10/media/image8.png){width="7.027777777777778in"
> height="3.8777777777777778in"}
>
> 7\. Restart the cups services

![](vertopal_5f230b20d77d417da1cd651243ef9c10/media/image9.png){width="7.027777777777778in"
height="0.20416666666666666in"}

> 8\. Verify if the service was restarted.
>
> ![](vertopal_5f230b20d77d417da1cd651243ef9c10/media/image10.png){width="7.027777777777778in"
> height="3.3805544619422574in"}

Page **4** of **4**
