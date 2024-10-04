# About This Repository

This repository is a fork of the original repository [https://github.com/orpatashnik/StyleCLIP.git] and has been independently edited. 

## Changes
optimization/run_optimization/108:
- original
  torchvision.utils.save_image(img_gen, f"results/{str(i).zfill(5)}.jpg", normalize=True, range=(-1, 1))
- edited
  torchvision.utils.save_image(img_gen, f"results/{str(i).zfill(5)}.jpg", normalize=True, value_range=(-1, 1))