# Design Journal

So, I really want a HOTAS flight stick, something like this:

![image](https://github.com/user-attachments/assets/b3d32661-1bde-44a2-8c84-264a3f0a83ee)

But commercial HOTAS kits and stuff already online is either too expensive or too complicated for me. I want something minimal (at least mechanically) and functional.

# Part 1: The gimbal

Before going crazy on the actual stick, I thought it would be nice to get the gimal out of the way. The first choice for most DIYers out there (according to Reddit) is a gimbal designed by (Oluleko)[https://www.thingiverse.com/thing:2496028/comments].

I really liked how compact and simple the gimbal was, but looking at the thingiverse, there are STEP files missing from the assembly and no assembly readily available to use. Plus, the project came out nearly 8 years ago. So, I started with making my own Oluleko assembly. 

I started first with redesigning all the parts that were missing from the open source files:

![image](https://github.com/user-attachments/assets/fa609722-1a9d-4dc2-8dd0-1e82f51cb95f) ![image](https://github.com/user-attachments/assets/4655475a-aff5-4456-9771-13a2cb79dde1) ![image](https://github.com/user-attachments/assets/224fc93c-8e72-484a-a387-41c300c41106)

Then, I had to find parts. I did some digging to figure out the bearings that Oluleko had used in his design (Thank you Reddit), and scrounged up some CAD for it (No, I don't want to make it myself):

![image](https://github.com/user-attachments/assets/90c580e0-c193-4615-8355-aeb541fe35a0) ![image](https://github.com/user-attachments/assets/c7bdb811-e268-4f5f-a989-4239397d00ee)

Now, I could assemble the gimbal. I used some pictures as reference and made up stuff as I went, adding washers where extra space was neccesary:

![image](https://github.com/user-attachments/assets/d4ff2c61-60e1-4791-b779-ede2e6e6cd0e) ![image](https://github.com/user-attachments/assets/8da9320c-6535-4139-a7ff-453a7f38d9bd)

But wait. This isn't satisfying. There's nothing to move, nothing to prove this actually works. Why not actually make it work in CAD, so I don't have to worry later? Welp, that's what I wasted time doing.

![Screen Recording 2025-06-22 at 10 00 04 PM](https://github.com/user-attachments/assets/efaea724-4660-4948-ad7c-04959a51f2ef)

# Part 2: The box

The other problem with Olukelo's design is that, well, it's just a gimbal. To make this a worthwhile design, I have to design an enclosure for the gimbal. 

Quick sketch of the enclosure:

![image](https://github.com/user-attachments/assets/bfb6bd52-d135-4bdd-8d0a-63dd34acff9e)

After extruding everything out, I get something like this:

![image](https://github.com/user-attachments/assets/29858521-1ab0-4029-b560-bfcadbe042ef)

Then, I can add it to my assembly to check. Enclosure done! There's also enough space underneath for the microcontroller!

![image](https://github.com/user-attachments/assets/fdda8427-1979-4a91-a710-1ae91bebc342) ![image](https://github.com/user-attachments/assets/e1c031cf-2f32-4bbf-98ac-ad7cfea5e78e)

# Part 3: The stick

I want to make this HOTAS as realistic as possible, but I don't exactly have an F-16 manual or HOTAS controller lying around to use to design one myself. I started with (this)[https://www.thingiverse.com/thing:4544115] old project to get the basic shape, something like this that I can add to:

![image](https://github.com/user-attachments/assets/b5e717db-8d99-403d-aa36-bfcb03672117)

Now, I can start actually making the working assembly for the stick!

Working trigger (for fun):

![Screen Recording 2025-06-23 at 11 43 04 AM](https://github.com/user-attachments/assets/03149178-5201-4f3f-90e7-37b9b6ca3487)

Added all the button mechanisms (this took a good amount of mating and part sourcing):

![image](https://github.com/user-attachments/assets/7c7b6a8d-ad74-4a52-a60e-ad486bb8a392)

Final assembly complete!

![image](https://github.com/user-attachments/assets/be48f1fc-3eed-46d5-9dc3-27b8f096dbcd)

Now, for the final touch, I used some eyeballing and measurement to add screws into the right places, so it is truly exactly what I will be building
