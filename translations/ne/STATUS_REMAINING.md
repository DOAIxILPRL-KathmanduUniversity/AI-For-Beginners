# नेपाली अनुवाद स्थिति विवरण (Nepali Localization & Completion Status)

यो पाठ्यक्रमको नेपाली संस्करणको समग्र स्थिति र बाँकी रहेका कामहरूको विस्तृत विवरण:

---

## ✅ १००% सम्पन्न भएका सामग्रीहरू (Fully Ready & Completed)

1. **सबै २४+ मुख्य पाठहरू (All Core Lessons 01 - 25 + Extras)**:
   - **५५ वटा विस्तृत पाठ निर्देशिका (55 Markdown Lesson Guides)**:
     - `0-course-setup/`: वातावरण सेटअप तथा सञ्चालन विधि
     - `1-Intro/`: एआईको परिचय तथा इतिहास
     - `2-Symbolic/`: प्रतीकात्मक एआई, ज्ञान प्रतिनिधित्व, र विशेषज्ञ प्रणाली
     - `3-NeuralNetworks/`: पर्सेप्ट्रोन, आफ्नै फ्रेमवर्क, र ढाँचाहरू (PyTorch/TF)
     - `4-ComputerVision/`: कम्प्युटर भिजन, सीएनएन, ट्रान्सफर लर्निङ, अटोइन्कोडर, GAN, वस्तु पहिचान, र सेगमेन्टेसन
     - `5-NLP/`: पाठ प्रतिनिधित्व, इम्बेडिङ, RNN, ट्रान्सफर्मर, BERT, NER, र LLM
     - `6-Other/`: जेनेटिक एल्गोरिदम, रिइन्फोर्समेन्ट लर्निङ, र मल्टि-एजेन्ट प्रणाली
     - `7-Ethics/`: एआई नैतिकता र जिम्मेवार एआई सिद्धान्त
     - `X-Extras/`: मल्टिमोडल नेटवर्क (CLIP र VQGAN)
   - **५३ वटा जुपिटर नोटबुकहरू (53 Jupyter Notebooks)**:
     - सबै नोटबुकका व्याख्यात्मक पाठ तथा सेलहरू नेपाली देवनागरीमा अनुवादित छन्।
   - **१२१ वटा नेपाली रेखाचित्र तथा स्केचनोटहरू (121 Localized Images)**:
     - `translated_images/ne/` मा सबै प्राविधिक रेखाचित्र र फ्लोचार्टहरू नेपाली पाठसहित उपलब्ध छन्।
   - **सबै डेटा तथा ल्याब सम्पत्तिहरू (Data & Lab Assets)**:
     - आवश्यक सबै डेटा फाइलहरू (जस्तै `onto.ttl`, `tsars.ged`, भिडियोहरू `palm-movement.mp4`, र तस्बिरहरू) नेपाली पाठहरूसँगै सिधै चल्ने गरी मिलाइएको छ।

2. **आधारभूत उदाहरणहरू (Starter Examples)**:
   - `examples/README.md`: पूर्ण नेपालीमा
   - `examples/03-image-classifier.ipynb`: पूर्ण नेपालीमा

---

## ⏳ अनुवाद बाँकी रहेका सामग्रीहरू (Marked as `_remaining`)

तलका सामग्रीहरू प्राविधिक रूपमा कार्यात्मक छन् तर तिनको टिप्पणी वा पाठ नेपालीमा अनुवाद गर्न बाँकी छ:

| फाइल / स्थान | स्थिति | विवरण |
| :--- | :--- | :--- |
| [`examples/01-hello-ai-world_remaining.py`](file:///Users/paramanada/Desktop/newari_expansion/AI-For-Beginners/translations/ne/examples/01-hello-ai-world_remaining.py) | `_remaining` | पहिलो एआई ढाँचा पहिचान स्क्रिप्ट (अंग्रेजी टिप्पणी बाँकी) |
| [`examples/02-simple-neural-network_remaining.py`](file:///Users/paramanada/Desktop/newari_expansion/AI-For-Beginners/translations/ne/examples/02-simple-neural-network_remaining.py) | `_remaining` | २-लेयर न्यूरल नेटवर्क स्क्र्याचबाट (अंग्रेजी टिप्पणी बाँकी) |
| [`examples/04-text-sentiment_remaining.py`](file:///Users/paramanada/Desktop/newari_expansion/AI-For-Beginners/translations/ne/examples/04-text-sentiment_remaining.py) | `_remaining` | पाठ सेन्टिमेन्ट वर्गीकरण स्क्रिप्ट (अंग्रेजी टिप्पणी बाँकी) |
| [`etc/quiz-src/questions-ne_remaining.txt`](file:///Users/paramanada/Desktop/newari_expansion/AI-For-Beginners/translations/ne/etc/quiz-src/questions-ne_remaining.txt) | `_remaining` | पूर्व तथा पश्च क्विज प्रश्नहरूको भण्डार (अनुवाद बाँकी) |
| [`etc/quiz-app/README_remaining.md`](file:///Users/paramanada/Desktop/newari_expansion/AI-For-Beginners/translations/ne/etc/quiz-app/README_remaining.md) | `_remaining` | Vue.js क्विज वेब एपको इन्टरफेस अनुवाद (`ne.json`) बाँकी |
| [`etc/Mindmap_remaining.html`](file:///Users/paramanada/Desktop/newari_expansion/AI-For-Beginners/translations/ne/etc/Mindmap_remaining.html) | `_remaining` | अन्तरक्रियात्मक माइन्डम्याप रेखाचित्र (अंग्रेजी मूल रूप) |

---

## स्थानीय वातावरणमा कसरी चलाउने (How to Run Locally)

कुनै डकर वा कन्टेनर आवश्यक छैन। सिधै टर्मिनलमा:

```bash
# १. आवश्यक पाइथन प्याकेजहरू इन्स्टल गर्नुहोस्
pip install -r requirements.txt

# २. जुपिटर नोटबुक खोल्नुहोस्
jupyter notebook
```
त्यसपछि ब्राउजरमा `lessons/` (अंग्रेजी संस्करण) वा `translations/ne/lessons/` (नेपाली संस्करण) मा गई सिधै अध्ययन सुरु गर्न सक्नुहुन्छ।
