# Documentação dos vídeos gerados

## 1) Video w32_512.avi 
- Comando: `python ./scripts/live-demo.py --filename panoptic.mp4 --save_video`

- Tempo de execução: **1889s = 31min 29s**
- Framerate: **0.147703 fps**

## 2) Video w32_640.avi 
- Comando: `./scripts/live-demo.py --filename panoptic.mp4 -c 32 -r 640 --save_video -w ./weights/pose_higher_hrnet_w32_640.pth.tar`

- Tempo de execução: **3383s = 00:56:23**
- Framerate: **0.088132 fps**

## 3) Video w48_640.avi 
- Comando: `python ./scripts/live-demo.py --filename panoptic.mp4 -c 48 -r 640 --save_video -w ./weights/pose_higher_hrnet_w48_640.pth.tar`

- Tempo de execução: **3571s = 59min 31s**
- Framerate: **0.086666 fps**
