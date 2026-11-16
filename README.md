# jiazuowang

**Computer Vision | Robotics Perception | Embedded AI**

I work on practical machine learning problems, with an interest in the path from real sensor data to model evaluation and deployment. My experience includes RGB-D data preparation, image segmentation, 6D pose estimation demos, and embedded inference debugging.

## How I approach projects

- **Start with the data.** Work with camera captures, inspect inputs, and check assumptions before comparing models.
- **Make experiments inspectable.** Separate model selection from evaluation, examine class-wise errors, and record the trade-offs behind a result.
- **Connect models to engineering constraints.** Consider memory, tensor layout, quantization, and integration alongside predictive performance.

## Selected projects

### [Text Review — NLP Desktop Application](https://github.com/jiazuowang/text-review-nlp)

A group NLP project that I initiated and developed into a working prototype with Codex assistance, followed by team revisions and demonstration work.

- Connected dataset preparation, model comparison, evaluation, and a local desktop interface.
- Published three trained classifiers with document import, model comparison, batch analysis, and report export.
- Preserved aggregate experiment results and limitations; public-release checks: **67 passed, 1 dataset-dependent check skipped**.
- Included anonymous team acknowledgements; personal details and the original text corpus are excluded.

### [RGB-D Cup Dataset for 6D Pose Estimation](https://github.com/jiazuowang/FoundationPose-dataset-cup)

Custom RGB-D sequences and demo integration for NVIDIA FoundationPose using an Intel RealSense D405 and a cup mesh generated with Tencent Hunyuan.

- Two documented sequences: 115 frames at 1280 x 720 and 233 frames at 640 x 480.
- Custom data loading for pose registration, tracking, and visualization.
- Focus: connecting real camera data with a pose-estimation pipeline. The underlying FoundationPose method is NVIDIA's work.

### [Product Review Sentiment Classification](https://github.com/jiazuowang/ee6483-sentiment-classification)

My implementation work within an EE6483 group course project, using an instructor-provided dataset.

- Compared 19 configurations with grouped cross-validation to keep normalized duplicate reviews together.
- Selected a class-weighted word-and-character TF-IDF SVM using development macro F1.
- Recorded **91.42% accuracy** and **0.8357 macro F1** on a separate labelled holdout; these are not official test-set scores.
- Published code and aggregate results. The course data and original group report are excluded.

## Technical experience

**Vision and learning:** Python, PyTorch, TensorFlow, OpenCV, scikit-learn, YOLO, U-Net, FoundationPose.

**Sensors and deployment:** RealSense D405, ONNX export, RK3588 / RKNN calibration and quantization, AXERA tensor-layout and inference debugging.

I am interested in internship opportunities in computer vision, robotics perception, and embedded AI.

我关注真实数据、可信的实验比较和模型落地，希望通过具体实现、清楚的个人贡献和可检查的结果展示工程能力。
