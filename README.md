# NLP_augmentation_using_translation

---
This code utilizes the machine translation library or APIs to augment texts.
### 1. PORORO: Platform Of neuRal mOdels for natuRal language prOcessing (Library)
- A Deep Learning based Multilingual Natural Language Processing Library
- github: https://github.com/kakaobrain/pororo
- Language ID: korean='ko', english='en', japanese='ja', chinese='zh'

### 2. PAPAGO: the neural machine translator served to Naver (https://papago.naver.com/) (API).
- If you want to use this, you need to get a translation API at Naver Developers (https://developers.naver.com/docs/papago/papago-nmt-overview.md) and fill the client_id and client_secret in the below code.
- Free API is limited to 10,000 characters per day.
- Language ID: korean='ko', english='en', japanese='ja', chinese='zh-CN' (https://developers.naver.com/docs/papago/papago-nmt-api-reference.md)

### 3. Google Cloud Translate (API)
- If you want to use this, you need to get a translation API at Google Cloud Platform (https://cloud.google.com/translate) and fill the GOOGLE_APPLICATION_CREDENTIALS in the below code.
- Language ID: english='en', japan='ja', chinese='zh_CN', finnish='fi', svenska='sv', welsh='cy' (https://cloud.google.com/translate/docs/languages)

The APIs (not PORORO) are limited in usage, or money is charged when a certain usage is exceeded.

The usages are in the NLP_augmentation_using_MT.ipynb
