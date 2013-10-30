#--------------------------------------------------------------------------------
# Third party support modules
module_def(omegaOsg https://github.com/omega-hub/omegaOsg.git
  "An OpenSceneGraph and Bullet Physics integration library for omegalib")

module_def(omegaVtk https://github.com/omega-hub/omegaVtk.git
  "VTK support for omegalib")
  
module_def(rift https://github.com/omega-hub/rift.git
  "This module adds Oculus Rift support to omegalib, reading sensor data from the device and rendering using a post-processing shader that corrects for the Oculs Rift lens distortion and chromatic aberration")
  
module_def(sage https://github.com/omega-hub/sage.git
  "SAGE support for omegalib")
  
#--------------------------------------------------------------------------------
# Cyclops and libraries
module_def(cyclops https://github.com/omega-hub/cyclops.git
  "Cyclops is a utility library that sits on top of omegalib and OpenSceneGraph. It is designed to speed-up development of simple graphical applications, without having to deal with the low-level details of osg")

module_def(pointCloud https://github.com/omega-hub/pointCloud.git
  "This module contains classes used to load and handle point cloud data")

module_def(polytri https://github.com/omega-hub/polytri.git
 "Takes a boundary / polygon (in 2D) and creates a surface made out of triangles")
 
module_def(skyboxes https://github.com/omega-hub/skyboxes.git
 "A collection of skyboxes for omegalib applications, plus a skybox switcher utility script")

module_def(sprite  https://github.com/omega-hub/sprite.git
  "A module adding support for 3D sprites to omegalib. Sprites can be placed in 3D space but have a fixed pixel size")

module_def(navigator https://github.com/omega-hub/navigator.git
 "Provides ground collision and wall collisions for CAVE2 applications that have a need for users to navigate a virtual space where they can climb stairs, jump off platforms, and not walk through walls")

module_def(cavevoc https://github.com/omega-hub/cavevoc.git
 "CAVEVOC is a means to get speech recognition into the CAVE")

module_def(caveutil https://github.com/omega-hub/caveutil.git
 "CAVEutil is a Python module that bundles together a number of useful API calls that are convenient for developing VR applications, which are missing in the core Omegalib library")
 
module_def(wandaid https://github.com/omega-hub/wandaid.git
 "Provides a form of tool-tip for the CAVE2's wand. Whenever you raise your wand above a certain height (default is 1.5 meters) Wandaid will kick in and show a virtual wand with labels on it to explain what the buttons do. An application can customize the labels by using the Wandaid API")
 
module_def(orbNavigation https://github.com/tmarrinan/orbitNavigation/
  "Translational and rotational motion for an omegalib camera.")
#--------------------------------------------------------------------------------
# Misc modules
module_def(mvi https://github.com/omega-hub/mvi.git 
  "A module with utility functions for multiview immersion support")

module_def(porthole https://github.com/omega-hub/porthole.git 
  "Porthole is a framework that helps Virtual Environment applications developers to generate decoupled HTML5 interfaces. The goal is to ease the interaction between VE systems and smartphones, tablets, laptops or desktop computers, without the need of ad-hoc client applications")

module_def(flipbookPlayer https://github.com/omega-hub/flipbookPlayer.git 
  "a multicore image-based player for cluster systems")

module_def(templateModule https://github.com/omega-hub/templateModule.git 
  "An example C++ module for omegalib")  

module_def(vr-bundle https://github.com/omega-hub/vr-bundle.git 
  "A set of useful modules for Virtual Reality application development")  

module_def(evl https://github.com/omega-hub/evl.git 
  "Configuration files for systems in the Electronic Visualization Lab (like CAVE2  and OmegaDesk)")  
