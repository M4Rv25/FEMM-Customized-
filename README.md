# FEMM -CUSTOMIZED-

I made this customized version of the Oct2023 FEMM release to improve its usability.

[FEMM HomePage](https://www.femm.info/wiki/HomePage)

[FEMM Examples](https://www.femm.info/wiki/Examples) (I highly recommend looking into these)

---

<img width="1918" height="1078" alt="Screenshot 2025-12-31 191410" src="https://github.com/user-attachments/assets/e07035a2-6ec6-4f2a-bd2c-673225d70ea5" />
<img width="1918" height="1078" alt="Screenshot 2025-12-31 191433" src="https://github.com/user-attachments/assets/82fd63b3-f55e-4f5a-81bf-f0e9e3812f15" />
<img width="1918" height="1078" alt="Screenshot 2025-12-31 185957" src="https://github.com/user-attachments/assets/21bcdf89-52ef-4547-a285-f20c1e9d4978" />
<img width="1918" height="1078" alt="Screenshot 2025-12-31 190010" src="https://github.com/user-attachments/assets/15042313-954a-4779-a307-888df6931908" />


## Changes

-	The colormap was changed to something usable. Because:

	[Choosing color palettes](https://seaborn.pydata.org/tutorial/color_palettes.html) : "hue variations are not well suited to representing numeric data"

	I implemented Seaborn's [rocket](https://cmap-docs.readthedocs.io/en/latest/catalog/sequential/seaborn%3Arocket/) colormap because its the best perceptually uniform colormap I have come across.

---

-	The output window that popped up on viewing results was deleted (it annoyed me).

-	Points on rendered results are now hidden by default.

-	Flux line, grid and mesh colors were changed.

-	The sidebar is removed and integrated into the topbar (except for lua buttons; they were removed).

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
