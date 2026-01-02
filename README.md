# FEMM -CUSTOMIZED-

I made this customized version of the Oct2023 FEMM release to improve its usability.

[FEMM HomePage](https://www.femm.info/wiki/HomePage)

[FEMM Examples](https://www.femm.info/wiki/Examples) (I highly recommend looking into these)

---

<img width="1918" height="1078" alt="Screenshot 2026-01-02 122128" src="https://github.com/user-attachments/assets/eca69e34-9192-42d8-a86b-6e7cd10097c9" />
<img width="1918" height="1078" alt="Screenshot 2026-01-02 122049" src="https://github.com/user-attachments/assets/b78ac68a-6106-4ea1-b2ee-54af7407ffe3" />
<img width="1918" height="1078" alt="Screenshot 2026-01-02 122000" src="https://github.com/user-attachments/assets/094c6dc4-f0f7-4fdb-aabf-16ccce3e6fe0" />
<img width="1918" height="1078" alt="Screenshot 2026-01-02 121938" src="https://github.com/user-attachments/assets/fc65198c-c160-4339-be3d-7b6b71468d77" />


## Changes

-	The colormap was changed to something usable. Because:

	[Choosing color palettes](https://seaborn.pydata.org/tutorial/color_palettes.html) : "hue variations are not well suited to representing numeric data"

	I implemented Seaborn's [rocket](https://cmap-docs.readthedocs.io/en/latest/catalog/sequential/seaborn%3Arocket/) colormap because its the best perceptually uniform colormap I have come across.

---

-	The output window that popped up on viewing results was deleted (it annoyed me).

-	Points on rendered results are now hidden by default.

-	Flux line, grid and mesh colors were changed.

-	The sidebar is removed and integrated into the topbar.

-	Panning directions were inverted (feels more intuitive to me), and panning distance was reduced.

-	Mesh is now finer (low resolution previously impacted results).
    NOTE: I do see the compromised solving time ...

-	The app opens in fullscreen.

-	"Fit to screen" (natural zoom) now centers the screen's content.

-	Mousewheel zoom was added.

## How to use

Clone the repository and ...

... run "femm.exe" found in the "release64" folder.

or

... open "femm43_VS2026.sln" in Visual Studio and build FEMM yourself.

You are free to look into my commits to only apply those you agree with onto the original source code.
