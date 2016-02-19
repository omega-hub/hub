function(process_omegalib_modules)
#>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>> MODULE DEFINITION START

#--------------------------------------------------------------------------------
# Third party support modules
module_def(omegaOsg https://github.com/omega-hub/omegaOsg.git
  "An OpenSceneGraph and Bullet Physics integration library for omegalib")

module_def(omegaOsgEarth https://github.com/omega-hub/omegaOsgEarth.git
  "An OpenSceneGraph module for terrain rendering")

module_def(omegaVtk https://github.com/omega-hub/omegaVtk.git
  "VTK support for omegalib")
  
module_def(omegaThreejs https://github.com/omega-hub/omegaThreejs.git
  "Three.js support for omegalib")
  
module_def(rift https://github.com/omega-hub/rift.git
  "DEPRECATED - use the oculus module")

module_def(oculus https://github.com/omega-hub/oculus.git
  "Oculus Rift support for omegalib")
  
module_def(sage https://github.com/omega-hub/sage.git
  "SAGE support for omegalib")

module_def(scsound https://github.com/omega-hub/scsound.git
  "A preconfigured SuperCollider desktop sound server for omegalib")

module_def(s2plot https://github.com/ajhub1/s2plot.git
  "The s2plot Library for Omegalib")
  
module_def(oav https://github.com/omega-hub/oav.git
  "An ffmpeg-based video stream reader ")

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
 
module_def(orbNavigation https://github.com/tmarrinan/orbitNavigation.git
  "Translational and rotational motion for an omegalib camera.")
  
module_def(sceneTools https://github.com/omega-hub/sceneTools.git
  "A toolkit to simplify export/import and runtime editing of cyclops scenes")

#--------------------------------------------------------------------------------
# Misc modules
module_def(llenc https://github.com/omega-hub/llenc.git 
  "Low-latency encoder using the NVIDIA GRID SDK")
  
module_def(mvi https://github.com/omega-hub/mvi.git 
  "A module with utility functions for multiview immersion support")

module_def(porthole https://github.com/omega-hub/porthole.git 
  "Porthole is a framework that helps Virtual Environment applications developers to generate decoupled HTML5 interfaces. The goal is to ease the interaction between VE systems and smartphones, tablets, laptops or desktop computers, without the need of ad-hoc client applications")

module_def(flipbookPlayer https://github.com/omega-hub/flipbookPlayer.git 
  "a multicore image-based player for cluster systems")

module_def(templateModule https://github.com/omega-hub/templateModule.git 
  "An example C++ module for omegalib")  

module_def(common-modules https://github.com/omega-hub/common-modules.git 
  "A set of modules often installed with omegalib")  

module_def(official https://github.com/omega-hub/official.git 
  "Official modules included in omegalib release distributions")  

module_def(evl https://github.com/omega-hub/evl.git 
  "Configuration files for systems in the Electronic Visualization Lab (like CAVE2  and OmegaDesk)")  

module_def(cami https://github.com/omega-hub/cami.git 
  "Configuration files and application for the display wall at the Center for Advanced Molecular Imaging, Northwestern University")  

module_def(webView https://github.com/omega-hub/webView.git
  "HTML5 support for omegalib")

module_def(buildbot https://github.com/omega-hub/buildbot-autobuild-modules.git
  "(INTERNAL) bundle module with for buildbot automatic builds")

module_def(volrend https://github.com/omega-hub/volrend.git
  "Shader-based Volume Rendering module by NUVis")

module_def(signac https://github.com/omega-hub/signac.git
  "Fast scatterplot analysis tool")

#--------------------------------------------------------------------------------
# Tools and applications
module_def(modelView https://github.com/omega-hub/modelView.git
  "A simple 3D model viewer for omegalib")
  
module_def(ISS https://github.com/omega-hub/ISS
  "The omegalib International Space Station demo")

#--------------------------------------------------------------------------------
# EVL Tools and applications
# NOTE: This apps are used internally in EVL, in the future these should be 
# listed in a repo forked from this one.
module_def(railSim https://github.com/uic-evl/railSim
  "rail deformation visualization")

module_def(icecloud https://github.com/omega-hub/icecloud
  "sonar data visualization for under-ice AUVs")

#<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<< MODULE DEFINITION END
endfunction()
