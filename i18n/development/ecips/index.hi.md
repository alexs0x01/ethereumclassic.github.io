---
title: ईसीआईपी
seo: एथेरियम क्लासिक इम्प्रूवमेंट प्रस्ताव (ईसीआईपी) प्रक्रिया का सारांश, और स्वीकृत ईसीआईपी की सूची।
license: CC-BY
contribute: true
updated: 2022-02-22
contributors:
  - gitr0n1n
  - IstoraMandiri
  - TheEnthusiasticAs
---

## [एथेरियम क्लासिक सुधार प्रस्ताव](https://ecips.ethereumclassic.org/)

### सारांश

यह दस्तावेज़ एथेरियम क्लासिक इम्प्रूवमेंट प्रस्ताव (ईसीआईपी) प्रक्रिया का सारांश है। ईसीआईपी प्रक्रिया का पूरा विवरण देखने के लिए कृपया ईसीआईपी-1000 पढ़ें जो कि औपचारिक दस्तावेज है जिसे आम तौर पर एथेरियम क्लासिक (ईटीसी) पारिस्थितिकी तंत्र द्वारा स्वीकार किया जाता है, मोटे तौर पर आम सहमति से, ईटीसी प्रोटोकॉल में नए मानक परिवर्तनों का प्रस्ताव करने के लिए सबसे उपयुक्त प्रणाली के रूप में, सूचनात्मक दस्तावेज़, या ईसीआईपी प्रक्रिया सुझाव।

### शुरू करना

ईसीआईपी-1000 पढ़ने के बाद, रिपोजिटरी को फोर्क करें और दिए गए ईसीआईपी मार्कडाउन टेम्पलेट का उपयोग करके इसमें अपना ईसीआईपी जोड़ें। एथेरियम क्लासिक ईसीआईपी रिपोजिटरी में पुल अनुरोध बनाकर सबमिट करें।

### प्रतिभागियों के प्रकार

जैसा कि आप इस सारांश और ऊपर सुझाए गए अन्य दस्तावेजों को पढ़कर देखेंगे, ऐसे कई पक्ष हैं जो ईसीआईपी के जीवन चक्र में भाग लेते हैं:

- **ईसीआईपी लेखक:** यह आप हैं! लेखक एक नया ईसीआईपी बनाकर ईटीसी में सुधार करने में रुचि रखने वाला व्यक्ति है। इसलिए, यह सीखने के लिए जिम्मेदार है कि प्रक्रिया कैसे काम करती है, इसलिए वह प्रोटोकॉल परिवर्तन, सूचनात्मक या प्रक्रियात्मक सुधारों को प्रभावी ढंग से प्रस्तावित कर सकता है। लेखक नीचे वर्णित अनुसार 'ड्राफ्ट' से 'सक्रिय' तक, सभी स्थिति चरणों में ईसीआईपी जीवन चक्र का अनुसरण करने के लिए भी जिम्मेदार है, इसलिए प्रस्ताव एक वास्तविकता बन जाता है। यदि नहीं, तो यह संभव है कि ईसीआईपी अंततः खारिज कर दिया जाएगा।
- **संपादक:** संपादक डेवलपर्स हैं, मुख्य रूप से ईटीसी स्वयंसेवक, एथेरियम क्लासिक जीथब संगठन के सदस्य जिनकी जिम्मेदारियों में शामिल हैं, लेकिन इन तक सीमित नहीं हैं, ईसीआईपी को नंबर असाइन करना, उनका विलय करना, उन्हें ईसीआईपी निर्देशिका में सूचीबद्ध करना, यह जांचना कि वे तैयार हैं या नहीं, ध्वनि और पूर्ण, यदि स्थिति चरणों का पालन किया जाता है, और उनकी प्रेरणा, सटीकता और उचित लाइसेंसिंग शर्तों की जांच करने के लिए।
- **डेवलपर टीमें:** ईटीसी में कई डेवलपर कंपनियां और स्वयंसेवी डेवलपर्स हैं जो विभिन्न नोड क्लाइंट पर काम करते हैं। चूंकि ये डेवलपर्स एथेरियम क्लासिक के मुख्य प्रोटोकॉल को बनाए रखने के लिए समर्पित हैं, इसलिए उन्हें "कोर डेवलपर्स" या "कोर डेवलपर टीम" के रूप में वर्गीकृत किया गया है। कोर डेवलपर्स नए प्रस्ताव बनाने या अन्य डेवलपर्स या टीमों के प्रस्तावों की समीक्षा करने और स्वीकार करने या अस्वीकार करने के प्रभारी हैं। जब वे नए परिवर्तन स्वीकार करते हैं, तो वे उन्हें ईटीसी नेटवर्क के लिए बनाए गए संबंधित ग्राहकों में मिला देते हैं।
- **कार्यान्वयनकर्ता:** एक बार ईसीआईपी स्वीकार और विलय हो जाने के बाद, अंतिम चरण खनिकों, खनन पूलों, वॉलेट ऑपरेटरों, एक्सचेंजों और अन्य पूर्ण नोड ऑपरेटरों के लिए नए परिवर्तनों को एकीकृत करने के लिए अपने नोड्स को स्थापित या अपग्रेड करके परिवर्तनों को लागू करने के लिए है। इन ऑपरेटिंग नेटवर्क प्रतिभागियों को "कार्यान्वयनकर्ता" कहा जाता है।
- **उपयोगकर्ता:** उपयोगकर्ता या अंतिम उपयोगकर्ता नियमित उपभोक्ता, व्यवसाय, सरकार, गैर-आर्थिक नोड ऑपरेटर, निवेशक, या अन्य प्रकार के उपयोगकर्ता हो सकते हैं जो देखते हैं कि कार्यान्वयनकर्ताओं ने अपने सिस्टम को कब अपग्रेड किया और लेनदेन भेजने और स्मार्ट अनुबंधों के प्रबंधन के लिए नए नियमों को अपनाया। या ईटीसी के शीर्ष पर अनुप्रयोगों का उपयोग करना। चर्चा प्रतिभागी: ईसीआईपी प्रक्रिया के अनुसार, ईसीआईपी को आगे बढ़ाते समय, लेखक अपने प्रस्तावों पर चर्चा के लिए खुलेंगे। ये चर्चा सार्वजनिक मंचों, जीथब या डेवलपर कॉल में स्थित हैं। चर्चा में भाग लेने वाले कोर या स्वयंसेवी एथेरियम क्लासिक क्लाइंट डेवलपर्स हो सकते हैं, जीथब पर कोई भी डेवलपर्स अपनी अच्छी तरह से तर्कपूर्ण राय देने के इच्छुक हैं, और अन्य इच्छुक हितधारक या ईटीसी पारिस्थितिक तंत्र में प्रतिभागी हो सकते हैं।

### योगदान कदम

- ईसीआईपी-1000 की समीक्षा करें।
- ऊपर दाईं ओर "फोर्क" पर क्लिक करके रिपॉजिटरी को फोर्क करें।
- अपने ईसीआईपी को भंडार के अपने कांटे में जोड़ें। एक ईसीआईपी मार्कडाउन टेम्प्लेट है।
- एथेरियम क्लासिक के ईसीआईपी रिपोजिटरी में पुल अनुरोध सबमिट करें।

ईसीआईपी वेबसाइट: https://ecips.ethereumclassic.org/

## स्वीकृत ईसीआईपी

निम्नलिखित सुविधाओं को एथेरियम क्लासिक प्रोटोकॉल में अनुमोदित और एकीकृत किया गया था।
