# YAPP CL BETA
YAPP or (Yet Another Print-head Project) is a custom 3D printer tool-head designed to print with two materials in the same print. With minimal to no oozing thanks to OPS (Ooze Prevention System.) Shares the EVA 2.0 form factor to maximize compatibility with other modifications. Was built for a RatRig V-Core 3 400, but should work for other sizes. For V-Core 3.1, I'm unsure of the belt spacing. USE WITH CAUTION. Later updates will include patches for such issues.

Currently only supporting Orbiter 2.0 and Vz-HextrudORT with Phaetus Rapido and Slice Engineering Mosquito. More options to come shortly.

Proper documentation will be made ASAP. For now use the STEP files, *Cap Head screws are not all the correct length in the assembly, only use as a guide until further notice.


Hardware specifics 

M3x4mm OD 4.6mm Heat sink inserts

M2x3mm OD 3.5mm Heat sink inserts

25x10mm 24v Frameless Fan (You can cut or sand screw holes on a standard 25mm fan as an option)

9G Servo MG90S metal gear servo recommended 

10mm Long 4mm OD, 0.3mm wire diameter extension spring McMaster Car has them part # (1942N51)

(More specific BOM will be made ASAP)



<img src="https://user-images.githubusercontent.com/132520137/236590256-be258728-d882-4ef1-9caf-7d97f98ce2d9.png" width="500" /> 


General Intro
Expectations:

YAPP is created and managed only by one person, thus the updates aren't going to be released on a strict schedule, but more at random; prioritizing mechanical problems over new features.
 
The printed parts are designed with as little support as possible, having a well calibrated printer is highly recommended! These parts are almost a stress test for a printer. Tolerances are tight and cannot be off by more than ± 0.07. You'll find that some sanding is required to get the mechanism running smoothly.

If you have a heated chamber, the servo may overheat, most servos can't handle temperatures over 65c-70c. This will mostly affect the function. It shouldn't damage anything. In the future, a high temp version will be released.

The OPS may not work with all the nozzles, you can still use them on the primary and secondary without the ooze wedge.

YAPP fits within the stock frame of all RatRig V-Core 3 300-500 versions. No modifications required.

There are no solutions provided for mounting the second bowden extruder.

Second hot-end print area is reduced by 20 mm in the Y axis near the back of the build plate. Primary hot-end is unaffected. 
 
Uses:
YAPP will make your printer even more capable with dissolvable support. This unlocks so many design opportunities and more intricate geometry that would otherwise be impossible to print.

Multi material prints to achieve different mechanical properties like live hinges, or print in place nylon bushings etc… 

Making parts or models with different colored elements, make them parts pop. 


What version do I want?
Let me start off by saying that the Slice Engineering hot end is overpriced, I believe the clones will work just fine. I want this project to be accessible by as many folks as possible, so I'll release a version with a more affordable and better performing hot end ASAP.

At the moment YAPP CL (Classic) has 3 variants.
Orbiter 2.0 with Rapido & Mosquito, and bowden extruder of your choice. No belt tensioners*
Vz-HextrudORT with Rapido & Mosquito, and a bowden extruder of your choice. No belt tensioners*
Version one or two, but with stock EVA2 backplate with fan duct and belt tensioners. A bowden extruder of your choice.

Preparations
What’s to come Start to end

Choose your variant.             
Print the parts.
Deburr, drill holes, sand.
Heat inserts.
Mounting & Assembly.
Software (printer.cfg and slicer set up.)
Calibration print.
Test print.

1 . What version to choose from?
Let me make it easy to choose. My recommendation is option 1 mentioned above. It's the version I know will work without any issues. However the others are similar enough that I feel confident in saying you could choose any of them. Perhaps start with the option with the components you already own.
2. Printed parts.
Please print the parts to these specifications:
YAPP CL Main Chassis: 0.15-0.2mm Layer Height | 0.32mm External Perimeters | 0.4mm Internal Perimeters | Detect Thin Walls | 60% Infill PC,ASA,ABS,PA12 CF*
Mosquito Carriage V2 (Option 1&2): 0.2mm Layer Height | 0.32mm External Perimeters | Detect Thin Walls | 85% Infill PC,ASA,ABS
OPS Cam Link: 0.15mm Layer Height 100% Infill | Brim | Seam Position Random ASA,ABS, or HIPS
Remaining parts: Print with discretion 0.2-0.3mm Layer Height.
