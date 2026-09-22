# FrameDistill

**FrameDistill: Decoupled Frame-Grounded Rationale Distillation for Implicit Aspect-Based Sentiment Analysis**

FrameDistill studies sentiment classification for a specified aspect when the sentiment is implied by an event or its consequences rather than expressed by an explicit opinion word.

The approach uses semantic frame evidence to identify events and the role of the target aspect. During training, a teacher model provides frame-grounding and semantic-implication explanations as auxiliary supervision, while the sentiment labels come from dataset annotations. A Flan-T5 student learns these auxiliary tasks alongside sentiment prediction. At inference time, the student predicts the sentiment label without the teacher.

## Code

**Code coming soon.**

This repository currently contains only this README. Selected implementation files, experiment configurations, and usage instructions are being prepared for release. No source code, datasets, or model weights are available here yet.
