# Fashion-Search-Engine

This is a Fashion Search Engine project that utilizes the CLIP model for searching with text and images and the YOLO-NAS model for object detection and feature extraction. With this search engine, users can search for fashion items by either providing textual descriptions or uploading images, making it easier to find specific fashion items or similar styles.

## Introduction
Introduction
Fashion Search Engine is designed to streamline the process of finding fashion items online. It combines the power of natural language processing (NLP) and computer vision to provide an enhanced search experience. Whether you want to describe an item in text or upload an image, this search engine will help you find visually similar fashion items.

## Usage

You can perform two types of searches:

Text Search: Enter a textual description of the fashion item you are looking for in the search bar and click "Search." The CLIP model will analyze your input and retrieve relevant images of fashion items.

Image Search: Click the "Upload Image" button to upload an image of a fashion item. The YOLO-NAS model will perform object detection on the image and extract features to find visually similar items.

View the search results, which will display images of fashion items similar to your query.

Click on an item to view more details and potentially find links to purchase the item online.

Models Used
This project utilizes two key models:

CLIP (Contrastive Language-Image Pre-training): CLIP is a deep learning model developed by OpenAI that is capable of understanding the relationship between textual descriptions and images. It can be used for various vision and language tasks, including text-based image retrieval.

You can find pre-trained CLIP models at OpenAI's CLIP repository.
YOLO-NAS (You Only Look Once Neural Architecture Search): YOLO-NAS is a variant of the YOLO (You Only Look Once) object detection model, optimized for real-time performance and accuracy. It is used in this project for object detection and feature extraction from uploaded images.

You can find pre-trained YOLO-NAS models and more information at YOLO's official repository.
