# Fashion-Search-Engine

This Fashion Search Engine is a project that combines the power of the CLIP (Contrastive Language-Image Pre-training) model for text and image search, the YOLO-NAS (You Only Look Once Neural Architecture Search) model for object detection and feature extraction, and a Faiss vector store for efficient similarity search. The goal of this project is to enable users to search for fashion items using both text queries and images, making it a powerful tool for fashion enthusiasts, shoppers, and e-commerce platforms.

## Introduction
Introduction
Fashion Search Engine is designed to streamline the process of finding fashion items online. It combines the power of natural language processing (NLP) and computer vision to provide an enhanced search experience. Whether you want to describe an item in text or upload an image, this search engine will help you find visually similar fashion items.


## Features
Text and Image Search: Users can search for fashion items by entering text queries or uploading images. The system will return relevant fashion items based on both the textual description and visual features of the input.

Object Detection and Feature Extraction: The YOLO-NAS model is used to detect objects and extract relevant features from fashion images. This allows for precise matching and retrieval of similar items.

Efficient Similarity Search: Faiss is used as a vector store to efficiently search for similar items in a large fashion database. Faiss enables fast retrieval of the most relevant fashion items based on the extracted features.
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
