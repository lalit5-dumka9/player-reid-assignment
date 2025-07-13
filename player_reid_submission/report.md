# Report: Player Re-Identification

## Problem Statement

Identify and match players between two videos — broadcast and tacticam — ensuring consistent IDs.

## Methodology

- Use the YOLOv11-based model to detect players in both videos.
- Extracted HSV color histograms as feature vectors.
- Used cosine similarity for player matching.

## Techniques Tried

- Color histogram (baseline)
- Cosine similarity

## Challenges

- Low resolution crops
- No jersey numbers
- Occlusion and overlap

## Improvements

- Use deep features (e.g. ResNet)
- Apply tracking (e.g. DeepSORT)
