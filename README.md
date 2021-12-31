# ESP32_Project
TFLite Micro code for esp32.

This repo contains two folders:
1. Basic-Image-Classification - The code used to run the model on the ESP32-CAM device. This code was downloaded from Edge-Impulse repository here (https://github.com/edgeimpulse/example-esp32-cam) and from the tutorial here (https://www.survivingwithandroid.com/tinyml-esp32-cam-edge-image-classification-with-edge-impulse/)
With slight modifications:

`
 if(psramInit()){
 `
  
 `
      heap_caps_malloc_extmem_enable(1024 * 1024 * 4); //added after meeting with Itai from Intel
`

2. Models folder containing different models that were created and downloaded from Edge-Impulse. 


