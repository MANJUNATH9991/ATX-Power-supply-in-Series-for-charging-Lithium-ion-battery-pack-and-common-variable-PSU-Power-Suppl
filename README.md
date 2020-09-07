# ATX Power supply in Series for charging Lithium-ion battery pack and common variable PSU(Power Supply unit).
 Two ATX power supply is taken out of a old computer with approximately similar power,in our case it is a 350W power supply.These system can serve a wide range of output voltage for different applications.
 ![](https://i.imgur.com/8X3XKLn.jpg)
Fig 1:Two ATX Power supply of similar watts.
 The main aim of this project is to obatin higher voltage. Since the ATX power supply only offersv a maximum of 12V, we are gonna connect the PSU's in Series.For eg.if we are using 2 PSU's in series we get a maximum of 24V(12V+12V=24V).If we need a higher output voltage then we need to add up the no. of PSU's in series to obtain the required output voltage.
##  Testing PSU's
![](https://i.imgur.com/6ruaYb9.jpg)
Fig2:Testing the power supply units.
In order to check the power supply, we need to power them first to AC mains power and then connect a small jumper wire accross the green and black wire has show in the Fig2.Once this is done you should see the cooler fan starts to run. At this point we can check the outputs of thr ATX power supply,the orange one should output  3.3V,the red 5V and the yellow one 12V respectively.if there is no voltage accross these wires then that PSU is not in working condition.
(NOTE:the color of the wire may vary depending on the Power supply that you use)

## Isolating the ground wire from earthing.
 Isolating the ground wire from earthing is really very important in case we are connect amny PSU's in series.follow the steps below to accomplish the task as above
*  Remove the AC mains cord from the PSU.
*  Make sure u wear a glove to avoid shocks from huge charged capacitors inside the PSU.
*  Remove the screw to access inside of the PSU.
*  After removing u can see the circuit board screwed to bottom of the cabinate.
*  Unscrew these screw to access tyhe bottom side of the PCB.
*  After unscrewin the PCB make sure to short the huge capacitors present at the input and output side.
*  Once the capacitors are discharged, it s safe to proceed further.
*  Find the track where the black wires are soldered to, that is ground wire.
*  Use a multimeter to check the continuity between the ground and earth connection point.
*  If there is a continuity, we should remove the track where ground and earthing is connected.
*  After removing the track ,check continuity again, if there is not continuity we can proceed the same steps for the next PSU's,else find the tracks to which the ground and earthing is connects and remove them.
## Adding some connectors 
 To easily access these different voltages from different wire, we can use female banana connectors so that it will be easy to access them from outside.
 ![](https://i.imgur.com/UwsAK5V.jpg)
 Fig3:adding some connectors.
(NOTE:Make sure there is no continuity between the conneccors and to the body)

 Cut the wires to required lenght and connect all the respective color wires for connection.
 ![](https://i.imgur.com/OSt3sfj.jpg)
 Fig4:soldering the wires to the connectors.
 In my case im connecting the green and black wire directly insted of using a switch.
 Solder these wires to the connector as shown above. Make sure there is not short between these connectors and to the body.
##  Connecting the AC from both PSU's to a common cable
 Just connect the live wire to the live wire and neutral to neutral wire from different power supplies.
 dont connect the earthing wire to both the PSU's.
 In my case im not using earthing for both the power supply.
 i have tapped the AC wire from one PSU and soldered it to AC cord connector directly, so that i can make use of that connector to connect to Ac mains as shown in the figure below.
    ![](https://i.imgur.com/c3kYfml.jpg)
    Fig5:connecting the AC from both PSU's to a common cable.
 make sure to disconnect the cooler fan connection from one of the PSU.you can the power that cooler with 12v from the other one. As you can see i have tapped a 12v connection from bottom PSU to top one as shown in the above pic.
 Once the connections are complete close the enclosures of the PSU'S.
 I highly recommend you to isolate the PSU from each other by using plastic plate or acrylic sheet in between them.you can see i have used waste peaces of acraylic to isolate ,which can be seen in the picture above.
 
## Testing the final result
 Once everything is done and completed ,it is time to test the unit.
 I use a multimeter to check the output voltages of the PSU's.
 Measuring the output from individual ports with respect to ground.
 The first port from left is 3.3V,the second one is 5V, thired one is 12V and the last one is ground.
 ![](https://i.imgur.com/TsK6LwO.jpg)
 Fig6: 12V output from PSU1.
![](https://i.imgur.com/PC9gWWp.jpg)
Fig7: 5V output from PSU1.
![](https://i.imgur.com/OqipLBV.jpg)
Fig8: 3.3V output from PSU1.
![](https://i.imgur.com/MxLFsHR.jpg)
Fig9: 3.3V output from PSU2.
![](https://i.imgur.com/tkWWPeN.jpg)
Fig10: 5V output from PSU2.
![](https://i.imgur.com/L5u9i7D.jpg)
Fig11: 12V output from PSU2.
Connecting to PSU's in series using a male connecting wire.
![](https://i.imgur.com/uGCaPvm.jpg)
Fig12: 12V+12V=24V.
![](https://i.imgur.com/hctfp1w.jpg)
Fig13: 12V+5V=17V.
![](https://i.imgur.com/sa7QdMn.jpg)
Fig14: 12V+3.3V=15.3V
![](https://i.imgur.com/Jd2Zi70.jpg)
Fig15: 5V+12V=17V
![](https://i.imgur.com/8RRoRTK.jpg)
Fig16: 5V+5V=10V
![](https://i.imgur.com/iraCLch.jpg)
Fig17: 5V+3.3V=8.3V 
![](https://i.imgur.com/IX5eEz1.jpg)
Fig18: 3.3V+3.3V=6.6V
![](https://i.imgur.com/Wi84XMo.jpg)
Fig19: 3.3V+5V=8.3V
![](https://i.imgur.com/Kk76OWM.jpg)
Fig20: 3.3V+12V=15.3V

As we can from above images it is easy to obatin different ranges of voltage from two PSU's.
 In futher stacking of more PSU's is to be accomplished to have higher output voltage range and more range for varity of voltages.