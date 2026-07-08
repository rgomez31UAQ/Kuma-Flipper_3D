Welcome here, and thanks for your support!
If you own a 3D printer, you can now print a ⭐ better-looking and 😎 more personalized enclosure for yourself!
And if you have enough time, you can also choose finer print settings for higher quality results.

I used **PETG** material for printing. With proper printer settings, the result should come out pretty good.

> [!WARNING]
> Warning: Disassembling the enclosure may damage your device. You are responsible for any risks or consequences.

> [!IMPORTANT]
> Disclaimer: If you like the FlipperZero project and have the financial ability, please consider purchasing the original device through official channels. Building such a strong community is not easy, and they have open-sourced a large amount of valuable information.
> My device is **not** intended for counterfeiting or piracy. It includes targeted modifications and a completely new appearance for clear differentiation. The enclosure and structural parts are **fully incompatible** with the original device.
> The goal is to create a more affordable device and help the project ecosystem grow.

> [!IMPORTANT]
> Additional Disclaimer: This device is intended only for legal technical learning, professional research, and lawful analysis/testing purposes (you should know what you are doing).

---

### Before printing your own enclosure, you should know:

1. Due to cost constraints and limited development resources, the structure is not perfect. Disassembly carries some risk. Please read the instructions carefully and make sure you have steady hands and a solder station.

2. Replacing and installing the enclosure requires hands-on skills. Make sure you are confident before starting. Any damage caused during disassembly is your own responsibility.

3. Make sure your 3D printer build plate is clean and has good adhesion. Some narrow lines and characters require a well-prepared print surface.
   (My early prints failed many times because the build plate wasn’t clean enough.)

4. Be mentally prepared — since the device is hand-assembled and soldered, there will be visible soldering marks inside 🙄.

---

### File Description: Latest Version [V1](./V1)

<sub>*This directory includes 5 parts: Top Shell, Middle Layer, Bottom Shell, Buttons, and Light Pipe.*</sub>

![print\_view\_1](./V1/image/print_view_1.JPG)
![print\_view\_1](./V1/image/print_view_2.JPG)

> [!TIP]
> `LED_Light_Pipe.step` is the front light pipe of the device and should be printed using transparent filament.
> If you don’t have transparent material, you can leave it empty, fill it with semi-transparent glue, or reuse the light pipe from an existing enclosure.

### File Description: [Transparent Version of V1](./V1_Transparent)

![print_view_1](./V1_Transparent/image/IMG_0002.JPG)

This is an experimental transparent-version enclosure. If you'd like to try a transparent appearance, you can print this version.

Compared to the standard model, the separate light guide columns have been removed, and the original one-piece button model has been redesigned into six individual keycaps to reduce obstruction.

<sub>*This directory includes 4 parts: top shell, middle layer, bottom shell, and buttons.*</sub>

![print_view_1](./V1_Transparent/image/IMG_0001.JPG)

> [!TIP]
> `Botton_One.STEP` is the keycap model, and you need to print 6 pieces.If the keycaps are a little loose, you'll need to use a small amount of glue to secure them, but be careful not to let the glue drip under the key contacts.

---

### Disassembly and Assembly Instructions:

> [!TIP]
> Before disassembly, touch a grounded metal object nearby or use an anti-static wrist strap to avoid damaging the circuit board with static electricity.

---

**1. Remove the Top Shell**

On the front side of the device, you will find four screws at the corners. Remove them using a hex screwdriver.

![Step\_1](./Step/IMG_0735.JPG)

You will then see the circuit board.

![Step\_1](./Step/IMG_0730.JPG)

---

**2. Disconnect the Cable**

Use tweezers or your fingernail to disconnect the power connector located at the lower-right side of the PCB.

> [!TIP]
> If you use metal tweezers, be careful not to short-circuit anything.

Remove the four small screws at the upper-left corner using a screwdriver.

> [!TIP]
>To ensure a stable connection, the method has been changed to welding. If you received the equipment after May 2026, it is of the welding type. In that case, you need to use a soldering iron to remove it.

![Step\_1](./Step/IMG_0732.JPG)
![Step\_1](./Step/IMG_0731.JPG)

---

**3. Remove the Main Board**

Take out the main board.
This is what the back side looks like:

![Step\_1](./Step/IMG_2486.JPG)

---

**4. Remove the Coil**

Remove the middle layer, then take out the battery.

You will notice that the coil wires pass through four small holes at the upper-left corner of the middle layer part:

* The **upper two holes** contain the **red wires**
* The **lower two holes** contain the **yellow wires**

Make sure not to mix them up during reassembly.

> [!TIP]
> RFID and NFC use AC signals, so coil polarity does not matter.
> Just make sure the top holes use the red wires, and the same logic applies to the yellow wires.

![Step\_1](./Step/IMG_0728.JPG)

You will also find a magnetic shielding sticker under the battery. Carefully peel it off using tweezers.

![Step\_1](./Step/IMG_0727.JPG)

When fixing the red coil earlier, I added a small piece of double-sided tape underneath to prevent movement. You only need to gently pry it up to remove the coil.

> [!TIP]
> During disassembly, avoid scratching the insulation coating on the coil wire.
> Damage may cause short circuits between windings and affect read/write performance.

---

**5. Recover the Nuts**

If you don’t have heat-set threaded inserts, you can reuse the ones from the old enclosure.

Use a lighter or soldering iron to locally heat the area, then pry the nuts out with tweezers.

![Step\_1](./Step/IMG_0726.JPG)

---

If you completed all the steps above — congratulations, disassembly is finished.

Now simply repeat all steps **in reverse order** to assemble everything into the new enclosure.

---

**6. Assembly Notes**

Due to batch variations, the bottom casing may differ slightly. The latest version features optimized component placement, improving the RFID analog range. When installing the coil and magnetic shielding sticker, please note that you need to move the sticker from the right side of the image to the left side and trim it appropriately.

Additionally, due to the change in position, the RFID coil (red coil) wire will be shorter. You will need to remove one loop of wire before soldering it to the PCB (don't worry, missing one loop won't significantly affect the frequency).
![Step_1](./Step/betterRFID.JPG)

When reconnecting the coil:

If you have a soldering iron, it is strongly recommended to solder the connection for better reliability.

If not, you may continue using screws — but do **not** tighten them too much.
If 100% represents maximum tightness, stop at about **75%**.
Over-tightening can easily crush and break the wires (I’ve damaged quite a few this way 🙄).

![Step\_1](./Step/IMG_0732.JPG)

In the final step, the top shell includes a raised feature that presses against the four screws, preventing them from loosening or falling out.

![Step\_1](./Step/IMG_0736.JPG)
