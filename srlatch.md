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

