# STNTrack-Demo
Example needle segmentation and tracking results of **STNTrack-Seg** on ultrasound sequences.

**In each video:**
- **Green:** predicted needle mask
- **Yellow dot:** predicted needle tip

| Video | Description |
|---|---|
| `stntrack_sequence_15.mp4` | Typical case: the needle is segmented and its tip tracked in nearly all frames of the sequence. |
| `stntrack_sequence_08.mp4` | A second example of accurate needle segmentation and tip tracking. |
| `stntrack_sequence_02.mp4` | The needle is absent in most frames. STNTrack-Seg makes no detection in most of these frames (59 of 72) and then tracks the needle once it appears. |

**About the videos:**
- All sequences are test data: none was used for training or model selection.
- Results are shown without any temporal smoothing.
- The ultrasound data are de-identified and shown for illustration only. 
