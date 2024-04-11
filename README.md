# 2364-GPU-Power-Collection

In the terminal, the following command was run to extract power and temperature data in .csv format from an NVIDIA 4090 GPU

```console
nvidia-smi --query-gpu=power.draw,temperature.gpu --format=csv,noheader,nounits -lms 1000 > gpu_metrics.csv
```
The outputs of this command after executing on several different ML models performing inference was saved in this repository, and plotted in the attached python notebook

