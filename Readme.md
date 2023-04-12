
\learn how information travels on the internet as well
as about important devices which make it possible. 

\
create a virtual network using Cisco Packet Tracer
----------------------------------------------------------------


\Learn about the internet.
\
● Download and Install Cisco Packet Tracer.
\
● Create network simulation

--------------------------------------------------------------
what is a internet, how the internet works and what are the key components of a internet.
-------------------------------------------------------------
SCenario-1
----------
you do not have any internet and any storage devic with you.
\how would you transfer the files/projects to the other computer?

Ans:
Use USB ports where you connect the USB cable with the other computer and transfer the files.
This is the very basic type of a network where two computers are connected with each other and sharing the
data.
-----------------------
Scenario-2
---------
now instead of sharing the file with only 1 computer, you want to share the files with your entire class.

\
In your school’s computer lab, you have 20 computers and you want to share your project with all the other students as
well. How can we do this?
\

Ans:

There is a need for a device that can function as an extension device, providing us with a lot of USB ports for
connecting to other computers.Fortunately, we have such a device. It is known as the Switch.
\
Switch: Switch is a device that is used to connect multiple computer devices
\--------
With the help of the switch, we can connect more than two computers with each other.
One problem is solved, we are able to connect all the computers in our lab.
\
Scenario-3
--------

How would you choose the computer onto which you want to send the data?

The IP address is a unique set of numbers assigned to a computer on a network.
\
Here IP stands for Internet Protocol which simply means a set of rules which govern the internet.
\The IP address is a set of 4 numbers separated by a . dot.
\● Each number can range from 0-255.
\● A special number 255 is used in some computing tasks. It is the maximum value that can be represented by an eight-digit binary number.
\● 192.168.1.1 is an example of an IP address.


\\\
on a network of computers, two computers can not have the same IP address.
\So with the help of a networking device we can connect multiple computers and using an IP address we can identify the computer.
\Once you know the IP address of the computer you will be able to share the information with that computer
\This is called a Local Area Network or LAN because all the computers are on the same network.
------------------------------------------------------------------------------------

Local Area Network: A local area network (LAN) consists of a group of devices connected in one physical location,
such as a building, office, or home. The computers in a LAN connection to each other via the Internet and using IP
address we will find the exact address of the computer. Here we cannot communicate with the outside world. By
outside world, we mean with other LANs
-----------------------------------------
\\\\
Screnario-4
-----------

But let’s say you have one school in one city and another school in a different city. How can we transmit the data
\now? That is where we can use a different set of devices. First, we need a place where we can send all the
\information; this is usually called a server.

Servers :
-------
\
Server:It is a computer that provides data of many kinds to a user or client. Typically, a server will only perform a few
\actions for many clients. Every action taken by a server is called a service. Services are used by computers called
\clients.

-------------------------------------------

Scenario-5
---------
\what if we want to communicate with two or more servers?
\
For that we need a different device called Routers
\Routers: Routers are computers that are specialized to move data between servers and computers. They ensure
\that data transfers between computers take place where they should. So we connect our computer with the router and the router
\connects us to the server

\Internet\
Now we can send the information to the server and through that server the information will reach the other lab.
So basically when all devices combined they form a network which is called Internet network
Basically, all devices combine to form a network, which is called the Internet
\
---------------------------

\Cisco Packet tracer is a free software from Cisco. We will download this softwar

download --install---

CiscoPacket Tracer or CPT is a very powerful software we
can create and simulate various networks.
The screen interface is very simple. At the top we have allthe menu options and at the bottom we have networking

devices such as computers, servers, routers etc.
We will explore these devices in upcoming classes.
-----------------------------------------------------------


The first network we are going to make is
connecting two computers together with the help of
a cable.
2. Choosing the end device tab and then selecting the
PC option will be our first step.
3. Drag the computer to the empty area of the
software.
4. We must perform this twice since we need two
computers

Alignment & Connections:
1. We will place both the computers in a line.
2. Now we will connect them with a cable.

 We have an electric spark sign on the device menu,
which has the different cable options.

Each cable is suitable for a specific device. If we connect
the two devices with the wrong cable type, it won't work.
1. We have a spark logo in the connections menu that
will automatically choose the correct cable for the
device.
2. Thus, select this option and then click on the first
PC, then click on the second PC.
3. The cable connection between the computers is
shown here, and we can see two green triangles,
which indicates that our connection is working.


 Let's see what we can do with it now.
1. Computers like these are just like real computers.
2. Double clicking on any computer will open a
window. It shows the various options we have for
the PC.

This window contains options such as physical, config
Desktop Programming Attributes.
These options can be used to perform a variety of tasks.
In this case, we are interested in the Desktop option.
If we select the desktop, we will see various options.

Both computers will not be able to communicate yet. IP
addresses must be assigned to both computers so that
they can communicate with each other
1. The IP address of the computer can be set by
clicking on the IP configuration option.
2. This will open a new tab where we can set the IP

in the tab IPv4 address we will write our IP address we can
assign the IP address of our choice.
IP address is a string of binary numbers.
The most basic format includes a simple set of 4 blocks of
numbers with a minimum of 0.0.0.0 and a maximum of

255.255.255.255
● IPv4: IPv4 is 32-bit binary number.
● IPv4 address are separated by periods or dots.
● IPv4 addresses are written in four parts separated
by dots like this:
● IPv4 is a numeric address.
● Example :12.244.233.165
Types of Address
1. Public IP Address
2. Private IP Address
Public IP Address: All websites on the Internet use public
IP addresses.
EXAMPLE:
google.com, Amazon.com, gmail.com
Whitehatjr.com, Flipkart.com. Myntra.com
Private IP Address: A private IP address is used within a
private network to connect securely to other devices within
that same network.
Example: Your home devices, residential, office, and
enterprise environments.


Phone, Laptop, Tablet, Desktop inside your home or office
use private IP Address.
We have reserved IP for Private network:
Address ranges to be use by private networks are:
Class A: 10.0.0.0 to 10.255.255.255
Class B: 172.16.0.0 to 172.31.255.255
Class C: 192.168.0.0 to 192.168.255.255


For your cisco packet tracer PC let’s assign 10.0.0.1
Once we assign the IP address, this will automatically set
the subnet mask as 255.0.0.0
Subnetting is the act of dividing a network into two or
smaller networks. By increasing routing efficiency, it
enhances the security of the network as well as divides a
network into smaller subnets.
It also helps you to reduce the size of the routing tables,
which is stored in routers. This method also helps you to
extend the existing IP address base & restructures the IP
address.
Once this is done click on the cross button above to close
this window.

Then we will do the same thing with the other computer.
Click on the computer and select the IP configuration
option. Set the IP address to 10.0.0.2 and click on the
cross to close the window.
We have now assigned IP addresses to both computers.

We now need to test whether both computers can able to
communicate with each other or not?
1. To do that, we need to open the computer's
Command prompt and run a command.
2. The command is called ping.
3. By using the ping command, you can send data to a
computer and receive some data back.

4. It means that both computers are connected if you
are able to send and receive data from them.
Let’s see how to use the ping command.
First double click on the PC and go to Desktop option,
and select the Command Prompt.

This will open a terminal, there we can run our commands.
So first write ping and then the IP address of the second
computer.
1. Such as ping 10.0.0.2
2. This will send data to the other computer and then
receive some data.This will also give the information
about how fast our network is.
3. When we receive data it shows the time taken to
receive the data in milliseconds.
4. The faster the connection, the less time it takes.


