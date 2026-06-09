## 6/6/26 - Making the weapon

So far today, I have made the initial weapon design. For this weapon, I started by trying to make a basic asymmetrical weapon, but it just didn't look good to me, so then I tried to make a more axe-ish shaped weapon, but no matter what I did, I just couldn't get it to look right, so I restarted again. That's how I ended up with the newest design. The total weapon diameter is around 5 inches and will weigh about 48 grams per weapon, which is over half of the weight of a normal fairy, but bristle bots get weight bonuses of 1.5x, so I'm chilling, I think… here's how the weapon looks <img width="839" height="446" alt="Screenshot 2026-06-06 203950" src="https://github.com/user-attachments/assets/ce8ded3c-a4b1-4a8b-8b2b-a2a98413bdae" />
I spent an hour and 46 minutes on this, according to hakatime <img width="1244" height="36" alt="image" src="https://github.com/user-attachments/assets/60e88f77-d093-4adc-920b-370472b9d799" />


## 6/8/26

This is going to be a long one. Over the last two days, I finished the whole robot. idk why, but yesterday I just forgot to journal at all, and I just wanted to lock in on the cad today instead of journaling. For this long journal, I'm going to use Fusion's timeline to go back and forth. I started the bot by making a flat body and the beginning of the truss that connected the weapon to the body. <img width="751" height="427" alt="Screenshot 2026-06-08 192132" src="https://github.com/user-attachments/assets/172e1448-2a51-4b0a-b70a-25b14f718a95" />

Once I finished that, I made the initial body shape, which had a rounded back, holes for the standoffs to go in, and fairly thick walls because it was going to be printed out of TPU.

<img width="668" height="530" alt="Screenshot 2026-06-08 192436" src="https://github.com/user-attachments/assets/aea035f9-6be6-4d59-a07c-a4fc6482c9be" />

After that, I made the whole chassis a little bit thinner to try to save on weight and optimize the design, and made the top truss, which consisted of mirroring the bottom up to the top and editing it to be lighter.

<img width="638" height="513" alt="Screenshot 2026-06-08 192521" src="https://github.com/user-attachments/assets/17bfa2a1-092c-4fd5-91ad-3d2e604ee628" />

Then I had an idea to make the bot way stronger. I could make the body solid UHMW. Doing this makes it better because then I wouldn't have to worry about layer lines being a failure point, and UHMW is lighter than TPU while being tougher overall. To account for it being solid, I thinned the walls out to about 3mm thick. I then added a top lid, which is going to be made of 1.5mm tegris, and I filled out all the holes on the truss.

<img width="723" height="539" alt="Screenshot 2026-06-08 192740" src="https://github.com/user-attachments/assets/410b80d5-da17-4a17-b80b-b8bc79472c22" />

By this point, I still didn't have a weapon hub or any real optimization because I didn't even start weight calcs, and because this was a fairy, I thought I was only going to be able to run 1 weapon. Once I started the weight calcs, I realized if I switched to a slightly smaller motor, I might have a chance to run two steel weapons in the fairy weight class, which is unheard of. So I switched the motor out to a BetaFPV 2006 motor, which should still have plenty of torque. And I also decided to switch the battery from 3s to 2s to save weight. After I decided to change the weapon motor out I started making the pullies and once I made those I put them in the slicer to get a inital weight and I relized that that the weapons weighed way to much like each weighed 48g which is a third of the weight of a normal fairy and I had two of them... so I downsized the center of the weapon to use m2 screws instead of m3 screws but because im using so many of them it should have any issues with shearing. By this point, I had thinned the truss's thickness from 3.2mm to 2.5mm to save more weight. I also thinned out the whole robot even more because with a smaller motor, I had more wiggle room. Heres how it looked.

<img width="918" height="532" alt="Screenshot 2026-06-08 192920" src="https://github.com/user-attachments/assets/10c2ffe6-82b1-4e34-9015-f84aa2589707" />

At this point, I decided to pocket the weapon even more and make the hub slightly smaller again to save on more weight. Once I redid the weight calcs, I realized I was still going to be overweight, so I made the body smaller again, this time by bringing in the back of the bot, which is going to make wiring tighter, but I should still have plenty of room. After that, I started adding all my hardware and actually making the pulleys I would use. Thankfully, I found a tool in Fusion to make the GT2 pulleys easily. For this bot, I'm using two different types of bearings to make it super smooth: needle roller bearings inside the weapon hub and thrust washers on the outside to keep it centered. After I got everything aligned, I pocketed the weapon even more, which ended up getting the weight per weapon down to 43g, which is still absurd. The weapons at this point are bigger than the rest of the bot, by a lot, so there might be a chance the body just spins around the weapons, but we'll see. After that, I made the actual bristles, which are angled little rectangles that connect to the screw holes that hold the trusses and top lids onto the bot. These are what allow the movement of the bot. And that's it, that's somehow 9 hours of work, well, it's actually more than that because I had to work on the BOM. Overall, the bot's materials are AR500 for the weapon, UHMW for the body, TPU for the weapon hub, pullies, and bristles, and aluminium for the truss. According to my weight calcs I should have about 11 grams for screws and wires. Here's how the bot looks now with all the screws <img width="723" height="443" alt="image" src="https://github.com/user-attachments/assets/7917ed29-2287-4571-9502-50d716edaf0e" />
I spent 9 hours and 26 minutes according to Hackatime <img width="1211" height="50" alt="image" src="https://github.com/user-attachments/assets/ac9fb307-cdd9-4409-a8d1-1b7e80af3f42" />

## Total Time Spent on Cad: 11 hours and 16 minutes.
## Total Time Spent: 12.5 hours


