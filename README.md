# Lip Sync

## 1. Deepfake Detect

|                      | dfdc_1st   | dfdc_2nd   | local_relation | xception   | f3net      | com_evaluate |
| -------------------- | ---------- | ---------- | -------------- | ---------- | ---------- | ------------ |
| **ours_output_ofd**  | **0.0182** | **0.2515** | **0.0026**     | **0.3132** | **0.0133** | **0.1843**   |
| groundtruth          | 0.0033     | 0.2464     | 0.0193         | 0.2999     | 0.0127     | 0.179        |
| TK_AVS_G_Pose_Driven | 0.0044     | 0.1258     | 0              | 0.3072     | 0.0182     | 0.1402       |
| TK_AVS_audio_part    | 0.3745     | 0.2132     | 0              | 0.2951     | 0.0228     | 0.2787       |
| LIipGAN_audio_part   | 0.2216     | 0.2386     | 0.2517         | 0.3093     | 0.3475     | 0.4213       |
| Wav2Lip_demo_00      | 0.4307     | 0.252      | 0.5872         | 0.3025     | 0.6765     | 0.6922       |
| Wav2Lip_audio_part   | 0.4018     | 0.2551     | 0.594          | 0.3076     | 0.6765     | 0.6879       |
| LipGAN_demo_00       | 0.1972     | 0.2343     | 0.3083         | 0.301      | 0.3969     | 0.4425       |



## 2. Image Quality

|          | Size           | PSNR       | SSIM       | MSE         |
| :------: | -------------- | ---------- | ---------- | ----------- |
|  LipGAN  | (512, 512)     | 20.3095    | 0.7690     | 0.1859      |
| Wav2Lip  | (512, 512)     | 30.4198    | 0.8917     | 0.05296     |
|  TK_AVS  | (224, 224)     | 13.8606    | 0.4022     | 0.3583      |
| **ours** | **(256, 256)** | **34.300** | **0.9562** | **0.03580** |





## 3. Sync Quality