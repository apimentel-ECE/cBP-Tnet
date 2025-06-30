# cBP-Tnet
cBP-Tnet: Continuous Blood Pressure Estimation using Multitask Transformer Network with Automatic Photoplethysmogram Feature Extraction

Knly cite our cBP-Tnet research paper, thank you:

Abstract—Traditional cuff-based blood pressure (BP) monitoring methods provide only intermittent readings, while invasive alternatives pose clinical risks. Recent studies have demonstrated feasibility of estimating continuous non-invasive cuff-less BP using photoplethysmogram (PPG) signals alone. However, existing approaches rely on complex manual feature engineering and/or multiple model architectures, resulting in inefficient epoch training numbers and limited performance. This research proposes cBP-Tnet, an efficient single channel and model Multitask Transformer Network designed for PPG signal automatic feature extraction. cBP-Tnet employed specialized hyperparameters — integrating adaptive Kalman filtering, outlier elimination, signal synchronization, and data augmentation, leveraging multi-head self-attention and multi-task learning strategies to identify subtle and shared waveform patterns associated with systolic blood pressure (SBP) and diastolic blood pressure (DBP). We used MIMIC-II public dataset (500 patients with 202,956 samples) for experimentations. Results achieved mean absolute errors of 4.32 mmHg for SBP and 2.18 mmHg for DBP. For first time, both SBP and DBP meet the Association for the Advancement of Medical Instrumentation’s international standard (<5 mmHg, >85 subjects). Furthermore, it efficiently cuts epochs’ training number by 13.67% when compared to recent deep learning method. Thus, establishes cBP-Tnet’s higher potential for integration into wearable and home-based healthcare devices with continuous non-invasive cuff-less blood pressure monitoring.

Keywords—Non-invasive continuous cuffless blood pressure estimation, Photoplethysmogram, Multitask learning Transformer, Automatic PPG feature extraction, Deep Learning


