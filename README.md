# vlm-rag-crop-diagnosis

> vlm-rag-crop-diagnosis

<p align="center"><img src="abstract.png" alt="System Architecture" width="100%"></p>

## 🌟 Core Features

* ✅ **Lightweight Visual Diagnosis:** Utilizes an efficient visual model (e.g., MobileNetV3-large) for rapid, high-accuracy disease recognition from crop images. *(Achieved 98% accuracy on 11 crop disease categories)*
* ✅ **RAG-based Management Advice:** Leverages Retrieval-Augmented Generation with a fine-tuned Large Language Model (e.g., Qwen 2.5 7B Instruct) to generate targeted, knowledge-backed management strategies from reliable agricultural texts.
* ✅ **Crop QA System:** Integrates visual results and a RAG-powered knowledge base for interactive disease question answering.

## 🚀 Process Flow

1. **Image Upload & Visual Analysis:** The system captures an image, and the lightweight visual model identifies the crop disease.
2. **RAG-powered Knowledge Retrieval:** Based on the identified disease, relevant management practices and expert knowledge are retrieved from the text corpus (extracted from 11 agricultural textbooks).
3. **Advice Generation:** The LLM integrates the visual diagnosis and retrieved knowledge to generate personalized diagnosis reports and management advice.

---

## 🛠️ Quick Start

**1. Prerequisite**
Ensure you have Python 3.9+ installed.

```bash
pip install -r requirements.txt
