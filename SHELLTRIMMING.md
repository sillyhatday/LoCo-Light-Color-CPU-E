When it come time to assemble, there are a few points that require attention. Some of these I could fix in the PCB layout, but I cdon't see many poeple actually building this.

The contrast wheel is now replaced with the toggle wheel. This is larger than the original. The back shell requires the gap making larger.

<img width="800" height="533" alt="LoCo-Contrast" src="https://github.com/user-attachments/assets/d82254bd-ad3a-46d2-a958-5890fbe7c46c" />

The donor GBC crystal will likely be the wrong footprint. This was my temporary fix until getting a different crystal.

<img width="800" height="518" alt="LoCo-CPU-Crystal" src="https://github.com/user-attachments/assets/5015d789-4c8f-489a-8326-648576b63fc6" />

Here you can see there are some parts that will interfere with the back shell. It seem the last GBC rev comes with some fat fuses which are close to the back shell. One of the filters is also directly under the back shell, that is an issue in the original design. I could fix it, but it's an easy shell trim.

Some of these parts are removed in the newest model.

<img width="800" height="543" alt="LoCo-Power-2" src="https://github.com/user-attachments/assets/2db93f06-8c43-4a6c-a735-068bf429a884" />

A clearer look without the shell. If using the Bucket Mouse voltage regulator, keep in mind where the extra wire is run. I could add a solder jumper for if the user wants to use that regulator. Maybe I will, but not right now.

<img width="800" height="451" alt="LoCo-Power" src="https://github.com/user-attachments/assets/24babd7a-6c3c-49fa-b70e-bfa1669fb231" />

Extra Optional Tips:

If using an alternative power regulator, I suggest removing the black part once the pins are all soldered. The height of the regulator from the main PCB pushes it into the front shell. I have not removed them and should do that.

<img width="800" height="752" alt="regulatorSdeProfile" src="https://github.com/user-attachments/assets/41413d7c-6160-4488-8297-5bcef300547b" />

These pins collide with the front shell.

<img width="800" height="642" alt="regulatorAngledView" src="https://github.com/user-attachments/assets/d11be8aa-4a27-4910-833b-4ecf8353d1b6" />

I prefer the screen controls to be different from the assignments on the PCB. Swapping A and Select seems more intuitive to me.

<img width="800" height="665" alt="buttonSolderPads" src="https://github.com/user-attachments/assets/9783d457-a03f-41c1-9338-e83a5de39e47" />
