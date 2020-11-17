 <p align="center"> 
 <img src = "https://raw.githubusercontent.com/zaidalyafeai/ARBML/master/logo.png" width = "200px"/>
 </p>

## <div dir="rtl">الدافع</div>
<div dir="rtl">
تعلم الآلة والذكاء الإصطناعي اصبح له أهمية كبرى في الكثير من المجالات كالرؤية الحاسوبية ، معالجة اللغة الطبيعية ، الخ ... ولكن لسوء الحظ ليس هناك الكثير من المصادر مفتوحة المصدر لتسهيلها للناطقين باللغة العربية.
</div>

<br>
<br>

## <div dir="rtl">هدفنا</div>
<div dir="rtl"> 
  إثراء المحتوى العربي لمجال تعلم الآلة بإنشاء عدد من المشاريع مفتوحة المصدر لكي نشير لأهمية تعلم الآلة في حياتنا. لذلك نريد إنشاء برامج لتسهيل العرب من التعرف على أهمية الذكاء الإصطناعي وتعلم الآلة . 
</div>

<br>
<br>

## <div dir="rtl">التحديات</div>
<div dir="rtl">
 اللغة العربية تمتلك الكثير من الصفات التي تجعلها أكثر تعقيدا مقارنة مع اللغات الأخرى مثل الإنجليزية. أولا, كتابة اللغة العربية تتم من اليمين إلى اليسار. ثانيا, تحتوي اللغة العربية على أحرف
لايمكن لأغلب غير الناطقين بها تعلم نطقها بسهولة مثل حرف ` الضاد, الغين, الحاء والخاء والظاء. ` بالإضافة,
تحتوي اللغة العربية على التشكيل, الضمة, الفتحة والكسرة تساعد متحدثي العربية على معرفة النطق الصحيح للكلمة. كمثال: جملة `السَّلامُ عَلَيْكُمْ وَرَحْمَةُ اللَّهِ وَبَرَكَاتُهُ` تحتوي على تشكيل متعدد للكلمات يتبع قوانين وأسس النحو والصرف. مقارنة مع اللغة الإنجليزية, كلمات اللغة العربية تتميز باتصال الأحرف, هذا الإتصال يجعل فصل الأحرف مهمة صعبة وغير مفيدة للقارئ. أخيرا, يتحدث قرابة النصف مليار شخص اللفة العربية, مما نتج عنه تواجد لكنات مختلفة لكل مقطع من العالم العربي.
</div>

<br>
<br>

## <div dir="rtl">الطريقة</div>
<div dir="rtl">
 طريقتنا يمكن تعميمها على مختلف نماذج اللغة وليست محصورة على اللغة العربية. خطوات هذه الطريقة تبدأ من تدريب النماذج على مذكرة الكولاب وتمثيل النماذج على صفحات الويب

<br>
<br>

<p align="center"> 
<img src = "https://raw.githubusercontent.com/zaidalyafeai/ARBML/master/procedure.png"/>

</div>

## <div dir="rtl">النماذج</div>

<table class="tg" dir="rtl">
  <tr>
    <th class="tg-yw4l"><b>الإسم</b></th>
    <th class="tg-yw4l"><b>الوصف</b></th>
    <th class="tg-yw4l"><b>النوت</b></th>
    <th class="tg-yw4l"><b>تجربة</b></th>
  </tr>
  <tr>
    <td class="tg-yw4l">تشكيل</td>
    <td class="tg-yw4l"> RNN  <a href ="https://github.com/Barqawiz/Shakkala">Shakkala</a></td>
    <td class="tg-yw4l"><a href="https://colab.research.google.com/github/zaidalyafeai/ARBML/blob/master/Interfaces/Notebooks/Arabic_Diactrization.ipynb">
    <img src="https://colab.research.google.com/assets/colab-badge.svg" height = '20px' >
    </a></td>
    <td><a href = "#"><img src ="https://raw.githubusercontent.com/alrra/browser-logos/master/src/main-desktop-browser-logos.png" height = '20px'/></a></td>
  </tr>

  <tr>
    <td class="tg-yw4l">التعرف على الأرقام</td>
    <td class="tg-yw4l"> RNN </td>
    <td class="tg-yw4l"><a href="https://colab.research.google.com/github/zaidalyafeai/ARBML/blob/master/Interfaces/Notebooks/Arabic_Digits_Classification.ipynb">
    <img src="https://colab.research.google.com/assets/colab-badge.svg"height = '20px' >
    </a></td>
    <td><a href = "#"><img src ="https://raw.githubusercontent.com/alrra/browser-logos/master/src/main-desktop-browser-logos.png" height = '20px'/></a></td>
  </tr>

  <tr>
    <td class="tg-yw4l">التعرف على الحروف </td>
    <td class="tg-yw4l"> RNN </td>
    <td class="tg-yw4l"><a href="https://colab.research.google.com/github/zaidalyafeai/ARBML/blob/master/Interfaces/Notebooks/Arabic_Letters_Classification.ipynb">
    <img src="https://colab.research.google.com/assets/colab-badge.svg" height = '20px' >
    </a></td>
    <td><a href = "#"><img src ="https://raw.githubusercontent.com/alrra/browser-logos/master/src/main-desktop-browser-logos.png" height = '20px'/></a></td>
  </tr>

  <tr>
    <td class="tg-yw4l">الترجمة من العربي للإنجليزي</td>
    <td class="tg-yw4l">seq2seq</td>
    <td class="tg-yw4l"><a href="https://colab.research.google.com/github/zaidalyafeai/ARBML/blob/master/Interfaces/Notebooks/Arabic_nmt_attention.ipynb">
    <img src="https://colab.research.google.com/assets/colab-badge.svg" height = '20px' >
    </a></td>
    <td><a href = "#"><img src ="https://raw.githubusercontent.com/alrra/browser-logos/master/src/main-desktop-browser-logos.png" height = '20px'/></a></td>
  </tr>

   <tr>
    <td class="tg-yw4l">إنشاء الشعر العربي</td>
    <td class="tg-yw4l">CharRNN </td>
    <td class="tg-yw4l"><a href="https://colab.research.google.com/github/zaidalyafeai/ARBML/blob/master/Interfaces/Notebooks/Arabic_Poem_Generation.ipynb">
    <img src="https://colab.research.google.com/assets/colab-badge.svg" height = '20px' >
    </a></td>
    <td><a href = "#"><img src ="https://raw.githubusercontent.com/alrra/browser-logos/master/src/main-desktop-browser-logos.png" height = '20px'/></a></td>
  </tr>

  <tr>
    <td class="tg-yw4l">تضمين اللغة العربية</td>
    <td class="tg-yw4l">N-Grams  <a href ="https://github.com/bakrianoo/aravec">Aravec</a></td></td>
    <td class="tg-yw4l"><a href="https://colab.research.google.com/github/zaidalyafeai/ARBML/blob/master/Interfaces/Notebooks/Arabic_Words_Embedding.ipynb">
    <img src="https://colab.research.google.com/assets/colab-badge.svg" height = '20px' >
    </a></td>
    <td><a href = "#"><img src ="https://raw.githubusercontent.com/alrra/browser-logos/master/src/main-desktop-browser-logos.png" height = '20px'/></a></td>
  </tr>
</table>
  
## <div dir="rtl">النماذج المخطط إضافتها</div>
<table class="tg" dir="rtl">
  <tr>
    <td class="tg-yw4l">تصنيف الملفات</td>
  </tr>

  <tr>
    <td class="tg-yw4l">تصنيفات الكلمات</td>
  </tr>

  <tr>
    <td class="tg-yw4l">الإكمال التلقائي</td>
  </tr>
</table>

## <div dir="rtl">النماذج</div> 

<table class="tg" dir="rtl">
  <tr>
    <td class="tg-yw4l"><a href = "https://www.kaggle.com/mloey1/ahdd1"> الأرقام</a> و <a href = "https://www.kaggle.com/mloey1/ahcd1">الحروف</a></td>
  </tr>

  <tr>
    <td class="tg-yw4l">قصائد <a href = "https://www.aldiwan.net/">الديوان</a></td>
  </tr>
  
  <tr>
    <td class="tg-yw4l">الترجمة من  <a href = "http://www.manythings.org">manythings</a></td>
  </tr>
</table>

## <div dir="rtl">البيانات</div>

<table class="tg" dir="rtl">

  <tr>
    <th class="tg-yw4l"><b>الإسم</b></th>
    <th class="tg-yw4l"><b>الوصف</b></th>
  </tr>

  <tr>
    <td class="tg-yw4l">الأرقام العربية </td>
    <td class="tg-yw4l">70,000 images (28x28) converted to binary from <a href = "https://www.kaggle.com/mloey1/ahdd1"> Digits</a> </td>
  </tr>

  <tr>
    <td class="tg-yw4l">الأحرف العربية </td>
    <td class="tg-yw4l">16,759 images (32x32) converted to binary from <a href = "https://www.kaggle.com/mloey1/ahcd1">Letters</a></td>
  </tr>

  <tr>
    <td class="tg-yw4l">القصائد العربية </td>
    <td class="tg-yw4l">146,604 poems scrapped from <a href = "https://www.aldiwan.net/">aldiwan</a></td>
  </tr>
  
  <tr>
    <td class="tg-yw4l">ترجمة اللغة العربية </td>
    <td class="tg-yw4l">100,000 paralled arabic to english translation ported from  <a href = "http://opus.nlpl.eu/OpenSubtitles-v2018.php">OpenSubtitles</a></td>
  </tr>

  <tr>
    <td class="tg-yw4l">مراجعة المنتجات على الويب </td>
    <td class="tg-yw4l">1,648 reviews on products ported from <a href = "https://github.com/hadyelsahar/large-arabic-sentiment-analysis-resouces">Large Arabic Resources For Sentiment Analysis</a></td>
  </tr>

  <tr>
    <td class="tg-yw4l">التعليق على الصور </td>
    <td class="tg-yw4l">30,000 Image paths with captions extracted and translated from <a href = "http://cocodataset.org/#home">COCO 2014</a></td>
  </tr>

  <tr>
    <td class="tg-yw4l">ويكيبيديا العربي </td>
    <td class="tg-yw4l">4,670,509 words cleaned and processed from <a href = "https://linguatools.org/tools/corpora/wikipedia-monolingual-corpora/">Wikipedia Monolingual Corpora</a></td>
  </tr>

  <tr>
    <td class="tg-yw4l">عداد الشعر العربي </td>
    <td class="tg-yw4l">55,440 verses with their associated meters collected from  <a href = "https://www.aldiwan.net/">aldiwan</a></td>
  </tr>
  
  <tr>
    <td class="tg-yw4l">الخطوط العربية</td>
    <td class="tg-yw4l">516 100×100 images for two classes.</td>
  </tr>
  
  
</table>
