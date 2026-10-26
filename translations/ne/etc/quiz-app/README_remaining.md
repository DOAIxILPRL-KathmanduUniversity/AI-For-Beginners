# क्विज एप अनुवाद स्थिति (Quiz App Translation Status) - REMAINING

यो Vue.js क्विज एप वेब इन्टरफेस हो जसले पाठ्यक्रमका पूर्व तथा पश्च क्विजहरू सञ्चालन गर्छ।

### हालको स्थिति (Current Status):
- **वेब इन्टरफेस (Web UI)**: अंग्रेजी तथा अन्य भाषाहरूमा उपलब्ध छ, तर नेपाली भाषाको अनुवाद (`ne.json`) थप्न बाँकी छ।
- **क्विज प्रश्नहरू (Quiz Questions)**: [etc/quiz-src/questions-ne_remaining.txt](../../../etc/quiz-src/questions-ne_remaining.txt) मा नेपाली अनुवाद बाँकी रहेको ढाँचा राखिएको छ।

### नेपाली भाषा थप्न आवश्यक चरणहरू:
1. `etc/quiz-src/questions-ne_remaining.txt` मा रहेका प्रश्नहरू नेपालीमा अनुवाद गर्नुहोस्।
2. `etc/quiz-src/qzmkjson.py` चलाएर `ne.json` सिर्जना गर्नुहोस्।
3. सिर्जना भएको `ne.json` लाई `etc/quiz-app/src/assets/translations/` मा राख्नुहोस्।
4. `etc/quiz-app/src/App.vue` को भाषा ड्रपडाउनमा `Nepali (नेपाली)` थप्नुहोस्।
