# Single or Multiple speakers detection

# Survey

![sgle_mtp_spk_diarization](https://user-images.githubusercontent.com/30165828/218372288-5a5e8408-82ec-4d0a-93f0-203f46d21e0f.png)

## Dataset

### Original source:
- Vivos: [https://huggingface.co/datasets/vivos](https://huggingface.co/datasets/vivos)
- Room Impulse Response: [https://www.openslr.org/28/](https://www.openslr.org/28/)
- Musan Noise: [https://www.openslr.org/17/](https://www.openslr.org/17/)

### Mixture Dataset
#### Algorithm
![mixing algorithm overlap](https://user-images.githubusercontent.com/30165828/218371159-eea80a74-d488-4484-91a4-791ac1800f5e.png)
![mixing algorithm non overlap](https://user-images.githubusercontent.com/30165828/218371062-46675d6e-4ecc-4895-9f35-4b935c7936cf.png)
#### Source
- Overlap: [tuannguyenvananh/vivos-mixture-simulation-nonoverlap-dataset](https://www.kaggle.com/datasets/tuannguyenvananh/vivos-mixture-simulation-nonoverlap-dataset)
- Non-Overlap: [tuannguyenvananh/vivos-mixture-simulation-overlap-dataset](https://www.kaggle.com/datasets/tuannguyenvananh/vivos-mixture-simulation-overlap-dataset)

## Code to create mixture dataset
- Overlap: [tuannguyenvananh/mixture-simulation-overlap](https://www.kaggle.com/code/tuannguyenvananh/mixture-simulation-overlap)
- Non-Overlap: [tuannguyenvananh/mixture-simulation-non-overlap](https://www.kaggle.com/code/tuannguyenvananh/mixture-simulation-non-overlap)

## Image Recognition task

### Code to train ConvNeXt
- Overlap: [tuannguyenvananh/convnext-on-vivox-overlap-binary](https://www.kaggle.com/code/tuannguyenvananh/convnext-on-vivox-overlap-binary)
- Non-Overlap: [tuanio/convnext-on-vivox-nonoverlap-binary](https://www.kaggle.com/code/tuanio/convnext-on-vivox-nonoverlap-binary)

### Code to train Conformer
- Overlap: [tuannguyenvananh/conformer-on-vivox-overlap-binary](https://www.kaggle.com/code/tuannguyenvananh/conformer-on-vivox-overlap-binary)
- Non-Overlap: [tuannguyenvananh/conformer-on-vivox-nonoverlap-binary](https://www.kaggle.com/code/tuannguyenvananh/conformer-on-vivox-nonoverlap-binary)

## Speaker Diarization

### Speech Activity Detection:
- pyannot/voice-activity-detection: [huggingface.co/pyannote/voice-activity-detection](https://huggingface.co/pyannote/voice-activity-detection)

### Speaker Embedding 
- TDNN-based x-vectors: [tuannguyenvananh/x-vector-vivos](https://www.kaggle.com/code/tuannguyenvananh/x-vector-vivos)
- MFA-Conformer: [tuannguyenvananh/mfaconformer-vivos](https://www.kaggle.com/code/tuannguyenvananh/mfaconformer-vivos)

### Clustering:
- TDNN-based x-vectors: [tuannguyenvananh/x-vector-clustering](https://www.kaggle.com/code/tuannguyenvananh/x-vector-clustering)
- MFA-Conformer: [tuannguyenvananh/mfaconformer-clustering](https://www.kaggle.com/code/tuannguyenvananh/mfaconformer-clustering)

# Wandb experiment logging (train, test)
- [wandb.ai/tuanio/detect_single_or_multiple_spks](https://wandb.ai/tuanio/detect_single_or_multiple_spks/reports/Single-Or-Multiple-Speakers-Detection--VmlldzozNTQyNDg0?accessToken=f6riwa44igdw3c3ilqs32tnmtxeao32fv8e66g0vkglu5as795rmx1zq0s8el6ae)
