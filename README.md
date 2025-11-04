

# 🐾 **WildSense.AI**

### **AI-Powered Animal Recognition, Behaviour Analysis & Health Management Platform**

WildSense.AI is a **multimodal wildlife intelligence system** built on **Base44**, integrating **computer vision, audio analysis, disease prediction, behavioural understanding, conservation insights, community science, and an AI chatbot** — all in a modern, responsive web application.

🔗 **Base44 Workspace:** *(internal)*
🔗 **Preview:** [https://app.base44.com/apps/690228e5e51f2be7926dd2b8/editor/preview](https://app.base44.com/apps/690228e5e51f2be7926dd2b8/editor/preview)

---

## 🌍 **About WildSense.AI**

WildSense.AI is built to help users:

✅ Identify animals from photos & webcam
✅ Detect animal diseases instantly
✅ Analyse animal behaviour (aggression, stress, play, resting, mating, etc.)
✅ Interpret animal sounds & distress signals
✅ Explore species info, habitats, conservation status
✅ Generate health reports, reminders & timelines
✅ Interact with an Image-Aware AI Chatbot
✅ Share posts, join community challenges, and learn wildlife facts

This project transforms wildlife analytics using **Base44 + Hugging Face + Advanced AI**.

---

# 🚀 **Features**

## 🧠 **1. Animal Species Recognition**

* Image upload + webcam capture
* Uses HF Vision Model for species classification
* Confidence scores + habitat & conservation insights

✅ **Model Used:**
`shaktibiplab/Animal-Classification`

---

## 🦠 **2. Disease Prediction System**

* Image-based disease detection
* Severity scoring
* Treatment suggestions
* Differential diagnosis (multi-model ensemble)

✅ **Models Used:**
`mobassir/animal-disease-detection`
`aniketmaurya/animal-disease-classifier`

---

## 🎥 **3. Behaviour Detection**

* Detects **10+ behaviours** (aggression, distress, feeding, mating, resting…)
* Emotional state prediction
* Provides recommended actions

✅ **Models Used:**
`aaraki/animal-behavior-detection`
`microsoft/VideoCLIP` (for video behaviour recognition)

---

## 🤖 **4. Multimodal AI Chatbot (Image + Text + Voice)**

* Understands animal images
* Can diagnose symptoms from images
* Voice input available
* Multi-language (Tamil + 20 languages)
* 4 Professional Modes:
  ✅ Vet Advisor
  ✅ Wildlife Educator
  ✅ Behaviour Expert
  ✅ Community Guide

✅ **Models Used:**

* Multimodal LLM → `microsoft/Phi-3-vision`
* Speech-to-Text → `facebook/wav2vec2-base-960h`
* Speech-to-Speech → `suno/bark-small`
* Translator → `Helsinki-NLP/opus-mt-en-ta`

---

## 🌍 **5. Conservation & Habitat Intelligence**

* Habitat maps
* IUCN conservation status
* Diet, lifespan, migration pattern predictions
* Ecosystem insights & AI-generated summaries

---

## 📊 **6. Analytics Dashboard**

Includes:

* Species distribution
* Disease frequency
* Behaviour heatmaps
* Geographic mapping
* Community engagement analytics
* Health trends visualization

---

## 🐾 **7. Community Hub**

* Post images → AI auto-tags species
* AI Comment Assist
* “Ask the Vet” feature
* Challenges, badges, leaderboards
* User follows, chats, groups
* Auto-generated captions using BLIP model

✅ Model Used: `Salesforce/blip-image-captioning-large`

---

## 📖 **8. Learning Hub**

Wildlife education modules include:
✅ Lessons
✅ Video support
✅ Quizzes with instant scoring
✅ Badges (80% or above)
✅ Points & progress tracking

Entities: EducationModule, Badge, Challenge, BehaviourRecord

---

## 🗺️ **9. Smart Timeline + Health Report Export**

* Complete medical & behaviour history
* CSV/PDF exports for veterinarians
* Weekly AI-generated report

---

## 📡 **10. IoT & Offline Support (Optional)**

Supports:

* ESP32
* MQTT sensors (temperature, movement, feeding activity)
* Offline mode with sync
* Push notifications for vaccination reminders

---

# ⚙️ **Tech Stack**

## 🧩 **Core Platform**

* **Base44** (No-code + AI builder)
* Responsive UI
* Cross-platform
* Realtime DB
* Custom API integrations
* Edge deployment

---

## 🤖 **AI / ML Models (Hugging Face)**

### **Vision Models**

* `shaktibiplab/Animal-Classification`
* `aniketmaurya/animal-disease-classifier`
* `mobassir/animal-disease-detection`
* `aaraki/animal-behavior-detection`
* `microsoft/Phi-3-vision`
* `microsoft/VideoCLIP`
* `stabilityai/stable-diffusion-2` (AI profile avatar images)

### **NLP Models**

* `mistralai/Mistral-7B-Instruct`
* `facebook/bart-large-cnn` (Summarization)
* `sentence-transformers/all-MiniLM-L6-v2` (Recommendations)

### **Audio Models**

* `facebook/wav2vec2-base-960h`
* `sanchit-gandhi/whisper-medium-en`
* `openai/whisper-large-v3`
* `suno/bark-small`

### **Translation**

* `Helsinki-NLP/opus-mt-en-ta`

---

## 🖥️ **Frontend**

* Base44 Pages
* Image Upload Blocks
* Webcam Blocks
* Chart Blocks
* Map Blocks
* Floating Chatbot
* Animations & parallax design

---

## 🗄️ **Backend & APIs**

* Base44 API Blocks
* HF Inference API
* Custom Disease Diagnosis APIs
* Open-Meteo API (climate)
* OpenStreetMap API (habitat maps)

---

## 🗃️ **Database Entities**

* **Animal**
* **DiseaseRecord**
* **BehaviourRecord**
* **ChatLog**
* **Challenge**
* **Badge**
* **CommunityPost**
* **EducationModule**
* **HealthReminder**
* **IoTData**

---

# 🧪 **How It Works**

### ✅ 1. Upload Image → AI Species Recognition

### ✅ 2. Detect Disease → Severity + Treatment

### ✅ 3. Analyse Behaviour → Emotional & Physical State

### ✅ 4. Chat with AI → Ask Anything About the Animal

### ✅ 5. Save to Profile → Auto Health Timeline

### ✅ 6. Explore Dashboard → Track Trends

### ✅ 7. Join Community → Share & Learn

### ✅ 8. Earn Badges → Complete Modules & Challenges

---

# 📦 **Deployment**

* Fully deployed on **Base44 Cloud**
* Auto-scaling
* Secure endpoints
* Multilingual support
* Cross-device responsive

---

# 🏆 **Why WildSense.AI Stands Out**

✅ Multimodal AI (Vision + Audio + Text + Voice)
✅ Real-time behaviour understanding
✅ Disease prediction with severity & treatment
✅ AI-powered community insights
✅ Built entirely on **Base44** with 20+ Hugging Face models
✅ Wildlife + Veterinary + Education + Conservation ecosystem

---
