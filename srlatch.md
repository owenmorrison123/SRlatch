# SR Latch 
A latch is a type of memory device that remembers one bit. SR latch has 2 inputs, S and RT. S for set and R for reset. There is also an output called Q. 

![sr latch table](https://github.com/user-attachments/assets/b4988f00-c472-40c7-be08-60141ae61f49)
As you can see, this is how the table works for the operation of an SR latch. 

However, by design, when you press S and R at the same time, it is an invalid input and the value of Q is undefined. 

![SR NOR gate](https://github.com/user-attachments/assets/32fff1ac-5cba-4037-b2a2-ceed5d079b1c)

Here is the diagram of an SR NOR

![SR latch initial state](https://github.com/user-attachments/assets/68457a30-f72e-47fe-ad15-52cbfd925c39)
![Screenshot 2025-02-19 124305](https://github.com/user-attachments/assets/ed46522c-306d-4d0f-a5c1-80a7ab17b503)
# SR Latch Examples

![SR set](https://github.com/user-attachments/assets/224e76c9-dd53-4578-9426-b9c894184421)

<h3>This is what set looks like. Set is when you insert the coing into the machine. The first switch is on representing that we just inserted a coin.</h3>

![SR hold](https://github.com/user-attachments/assets/d7703607-10c1-4e7b-bf6f-1f59ffbe5a75)

<h3>Now it remembers that we have the coin so it is "holding" the knowledge. We just turned off the first switch showing that it remembers the coin being inserted</h3>

![SR reset](https://github.com/user-attachments/assets/5c1dcab3-b072-4eb2-9ed9-e61c7c0f317e)

<h3>Finally, this is reset. This is after you have your item and it knows you used the coin. When we flip the second swithc it resets the machine.</h3>

![SR latch wiring](https://github.com/user-attachments/assets/8975bc2a-f6ea-4818-8bb4-f11d0f9f2aad)

<h2>This is a diagram of what the wiring looks like for an SR Latch</h2>

# Vending Machine

<p>When building a vending machine circuit, you will need a capacitor because it will delay the reset. When you use a vending machine it doesn't reset right away because if it did you would not get your item. So we want to build this so that it delays it a few seconds and it has time to give you your item. </p>

![vending machine explanation](https://github.com/user-attachments/assets/0a702760-1c42-406b-bc05-23035d06b133)

<p>This is an explanation from the book about the vending machine. The 7408 number is known as an AND gate. The AND gate is a logic gate that can accept two or more inputs but gives out only one output. It can be implemented by using universal gates as well as diodes. In digital electronics, data transmissions and alarm circuits are monitored by using AND gates. Digital measuring instruments also use AND gates. The 7402 is a NOR gate (UNACADEMY)</p>

![complete vending machine](https://github.com/user-attachments/assets/06346f8f-52a1-436a-9669-640197fdfb4e)

<h2>The picture above is a complete vending machine with labels so that you know what is what and how it works.</h2>

![DIY-Vending-Machine-Arduino-based-Mechatronics-Project-Cirucit-Schematic](https://github.com/user-attachments/assets/7637c3cd-315c-4f9f-b9ab-9a75b3faef37)

![03535FBB-748C-4713-8991-39A6F6BF2195](https://github.com/user-attachments/assets/347e6976-0787-491e-8f1e-b9c576c8d2c7)

<h2>SET</h2>

![FFF62544-6B63-4E2C-91E7-96F826C82563](https://github.com/user-attachments/assets/d27620a3-06d4-42df-b076-9c579fc18ef2)

<h2>VEND</h2>

![3D16C8B1-4371-49E6-B076-DF4F681F06BB](https://github.com/user-attachments/assets/cb097d72-9d76-4399-b944-1e5f31af9dea)

<h2>RESET</h2>


# Sources

Unacademy. (n.d.). AND gate. Unacademy. Retrieved February 26, 2025, from 
    https://unacademy.com/content/jee/study-material/physics/and-gate/
    
Matthew Justice. (n.d.). How Computers Really Work. Retrieved February 26, 2025, from
    https://platform.virdocs.com/read/1541540/16/#/4/14,/1:0,/1:0

How To Mechatronics. (n.d.). DIY vending machine – Arduino-based mechatronics project. How To Mechatronics. 
    https://howtomechatronics.com/projects/diy-vending-machine-arduino-based-mechatronics-project/
