Files belonging to the publication:
	J.C. de Valença, A. Kurniawan, R.M. Wagterveld, J.A. Wood and R.G.H. Lammertink
	Influence of Rayleigh-Bénard convection on electrokinetic instability in overlimiting current conditions
	Physical Review Fluids 2, 033701 (2017)


General description

	The data set contains the electrochemical, flow and concentration measurements of different
	constant current measurements at a cation exchange membrane (see paper for details). 
	
	For the electrochemical measurements the chronopotentiometric response was measured between the 
	anode and a reference electrode. The applied current was between 60 and 600 uA (4.4 and 44.4 A/m2).

	For the flow measurements the displacement of polystyrene particle images (d=2um) were recorded 
	at a imaging frequency of 10 or 32 frames per second. From series of 50-200 of these images 
	overlays/stacks were made to quickly see the regions with motion and without. From two 
	consecutive particle images the velocity vector field can be calculated using Particle Image 
	Velocimetry (PIV algorithms). From this the mixing layer size can be extracted using custom 
	made MATLAB codes.

	For the concentration measurements the fluorescent lifetime of Alexa 488 dye was measured, which depends 
	on the ion concentration.





Folder content:
	060 uA 04A/p2 2Ilim:	Applied constant current (= 4.4A/m2 = 1.6*I_lim)
	CMX:			Membrane type (CMX, Neosepta)
	10 mM CuSO4:		Electrolyte concentration
	co orientation:		Orientation of the concentration polarization towards the gravitational field
	PIV:			Simultanious PIV and chronopotentiometric measurements (optional FLIM + CP)


060uA 04Apm2 2Ilim CMX 10mM CuSO4 - co orientation - PIV
	-Chronopotentiometric and PIV data: 	electrochemical data and final PIV average speed		
	-Final Movies				movie of stack images
	-Raw images in tif format t=0-500s:	particle images at 10 frames per second
	-Stacks of 50 frames jpg:		stacks of 50 images
	-ImageJ scripts to make stacks from images
	-ImageJ scripts to make movie from stacks
	-Timing and scaling file contains the image at which t=0 and the pixel size	

120uA 09Apm2 3Ilim CMX 10mM CuSO4 - counter orientation - FLIM
	-FLIM images (fig6) and movies (supplemental m4):	Images and movies used for paper		
	-FLIM reference images and length scale callibration:	Reference image and pixel size
	-Time dependent FLIM and electrical data (9Apm2 1000s):	FLIM and electrical data set 
	-FLIM info:						Text file with extra info

300uA 20Apm2 8Ilim CMX 10mM CuSO4 - co orientation - PIV
	-Chronopotentiometric and PIV data: 	electrochemical data and final PIV average speed		
	-Final Movies				movie of stack images
	-Raw images in tif format t=0-100s:	particle images at 10 frames per second
	-Stacks of 50 frames jpg:		stacks of 50 images
	-ImageJ scripts to make stacks from images
	-ImageJ scripts to make movie from stacks
	-Timing and scaling file contains the image at which t=0 and the pixel size	
400uA 30Apm2 12Ilim CMX 10mM CuSO4 - co orientation - PIV
	-Chronopotentiometric and PIV data: 	electrochemical data and final PIV average speed		
	-Final Movies				movie of stack images
	-Raw images in tif format t=0-500s:	particle images at 10 frames per second
	-Stacks of 50 frames jpg:		stacks of 100 images
	-ImageJ scripts to make stacks from images
	-ImageJ scripts to make movie from stacks
	-timing and scaling file contains the image at which t=0 and the pixel size	

400uA 30Apm2 12Ilim CMX 10mM CuSO4 - counter orientation - PIV
	-Chronopotentiometric and PIV data: 	electrochemical data and final PIV average speed		
	-Final Movies				movie of stack images
	-Raw images in tif format t=0-500s:	particle images at 32 frames per second
	-Stacks of 50 frames jpg:		stacks of 50 images
	-ImageJ scripts to make stacks from images
	-ImageJ scripts to make movie from stacks
	-Timing and scaling file contains the image at which t=0 and the pixel size	

540uA 40Apm2 15Ilim CMX 10mM CuSO4 - co orientation - PIV
	-Chronopotentiometric and PIV data: 	electrochemical data and final PIV average speed		
	-Final Movies				movie of stack images
	-Raw images in tif format t=0-100s:	particle images at 10 frames per second
	-Stacks of 50 frames jpg:		stacks of 50 images
	-ImageJ scripts to make stacks from images
	-ImageJ scripts to make movie from stacks
	-Timing and scaling file contains the image at which t=0 and the pixel size	

Figures for in paper
	-Figures and movies of the paper

Model to calculate concentration profile
	-Analytical with fourier series:	The run_*.m file executes the script using the f_*.m functions	
	-Numerical with PEPDE fuction:		The run_*.m file executes the script using the f_*.m functions	

Scripts to calculate the transition times
	-The run_*.m file executes the script using the f_*.m functions	







-----------------------------File types----------------------------------
MATLAB files (for version R2013b):
	*.mat 	MATLAB workspaces that contain data
	*.m	MATLAB script for calculations and data processing
	*.fig 	MATLAB figures that display data 

Various image formats are used, which are all well known
	*.tif	high resolution images
	*.jpg	compressed images 
	*.png	compressed images
	*.eps	vector image
	*.avi	movie files compressed
	*.mp4	movie files compressed further

Data compression
	*.z7 	compressed data using open source 7-zip software

Data compression
	*.z7 	compressed data using open source 7-zip software

FLIM data
	*.fli	FLIM data in commercial software LI-FLIM from Lambert instruments
