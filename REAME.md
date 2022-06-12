# Virtual machines in Azure.
###  Practice 1
This is a practice in which we will show all the steps we use to create a virtual machine inside another virtual machine in Azure.
1. Creating the first virtual machine in AZURE:tw-1f4cc: 
        ![](img\1.png)
        ![](img\2.png)
1. Creation of Subscription (Resource group, name and region)
        ![](img\3.png)
        ![](img\4.png)
        ![](img\5.png)

1. We created it
        ![](img\6.png)
        ![](img\7.png)
        ![](img\8.png)
1. We verify that it is in the same virtual network.
        ![](img\9.png)
1. Esperemos la impletemtacion de los recursos
        ![](img\10.png)
1. Select the resource group
        ![](img\11.png)
1. Here we can see the created virtual machines
        ![](img\12.png)
1. Enter a virtual machine and select connect and select RDP.
        ![](img\13.png)
        ![](img\14.png)
1. Press select files
        ![](img\15.png)
1. We select the downloaded file and connect
        ![](img\16.png)
1. Enter the user name and password you have entered above
        ![](img\17.png)
1. Press yes
        ![](img\18.png)
1. let's wait for it to start the virtual machine
        ![](img\19.png)
1. We verify that they are connected
        ![](img\20.png)
1. We indicate that we accept the virtual machine
        ![](img\21.png)
        ![](img\22.png)
1.  Here we can see the internet speed of the virtual machine
        ![](img\23.png)
1. Verify with the private IP if the other Virtual Machine is connected.
        ![](img\24.png)
1. Dentro del powersheel Escribimos `mstsc /v:10.0.04`(It is the private ip of the machine). <br>para conectarnos a la otra maquina virtual dentro de la maquina virtual.
        ![](img\25.png)
1. We do the same process inside the virtual machine when we log in.
        ![](img\26.png)
1. Here you can see the virtual machine inside a virtual machine.
        ![](img\27.png)
        ![](img\28.png)
1. It is advisable to stop them in the azure portal ([azure](https://portal.azure.com/)) once you stop using them.
        ![](img\29.png)
