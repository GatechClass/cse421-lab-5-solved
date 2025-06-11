# cse421-lab-5-solved
**TO GET THIS SOLUTION VISIT:** [CSE421 Lab 5 Solved](https://mantutor.com/product/cse421-lab-5-instructions-solved/)


---

**For Custom/Order Solutions:** **Email:** mantutorcodes@gmail.com  

*We deliver quick, professional, and affordable assignment help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;113567&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE421  Lab 5 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
Background:

A PKA task is provided for this lab where a network address is given along with some host requirements for different networks. You need to apply VLSM and find out the network addresses for all the networks present in the topology. Based on these network addresses, you have to assign IP configuration to the devices.

Steps:

1. Write your ID, section, and name beside PC1 in the given format.

ID_Section_Full Name. Failing to do so even by mistake will result in a 0 in the entire assessment.

2. You are given the network address 1.17.0.0/16. Now you have to use VLSM to subnet this network address according to the following necessity. (All the requirements are including default gateway)

a. LAN connected to Switch1 has 2046 devices in total.

b. LAN connected to Switch2 has 4000 devices in total.

c. LAN connected to Switch3 has 1024 devices in total.

d. LAN connected to Switch4 has 1000 devices in total.

e. LAN connected to Switch5 has 750 devices in total.

There are some Switch network and WAN networks too in the topology. You need to find out the network addresses for those networks too. As all the WANs have the same requirements, allocate the network addresses based on the location and start allocating from left to right.

3. As you have the network addresses, now you need to assign the IP addresses, and subnet masks to the devices present in the topology. For PCs and Servers, you have to set the default gateway too. Now, if the network address is

1.1.0.0/24, you should start assigning from 1.1.0.1/24, 1.1.0.2/24 and so on.

a. For LAN networks, start assigning in this sequence, the default gateway of the network, then PCs, and then Servers. If there are multiple PCs/Servers, allocate the lower address to the PC or Server that has the lower number. Like PC10’s address should be less than PC11’s address.

b. For Switch/WAN networks, assign IP addresses based on the interface’s location, and start allocating from left to right.

Sanity Checking:

1. Successfully setting IP configuration for all the devices of Switch1 LAN will increase the percentage to 10%.

2. Successfully setting IP configuration for all the devices of Switch2 LAN will increase the percentage to 32%.

3. Successfully setting IP configuration for all the devices of Switch3 LAN will increase the percentage to 42%.

4. Successfully setting IP configuration for all the devices of Switch4 LAN will increase the percentage to 53%.

5. Successfully setting IP configuration for all the devices of Switch5 LAN will increase the percentage to 63%.

6. Successfully setting IP configuration for all the devices of the Switch network(s) will increase the percentage to 75%.

7. Successfully setting IP configuration for all the devices of the WAN network(s) will increase the percentage to 100%.
