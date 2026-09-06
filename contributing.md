# portavan AI Project Contribution Guide
This project aims to train a model from scratch and develop it further.
## How to Participate in Collecting Textual Data for the Project
First, take a look at the [topics file en/topics.md](en/topics.md) to see the listed topics and their dialogues.
If a topic is not in the list, open an **Issue** and suggest the topic you want to add to the list. Then wait for a confirmation or rejection comment.
Once your topic is approved, go to the [conversations file en/conversations.txt](en/conversations.txt) and add the new topic as a comment at the end of the file. Example:
```
#    Topic: Various Greetings and Salutations
#    Topic: Programming and Computers
```
If you wish to work on an existing topic, add your texts before the dashes.
Example: Assume the topic already has the dialogue:
```
user: I'm very sad because I did some things that upset a lot of people, and then I lied to them a lot. How can I forgive myself?
portavan: I'm glad my dear, because your conscience is still awake. To find peace of mind, no matter how hard it is, you must apologize to them. Shall we write a letter to them together?
rating: 5
---
```
Now if you want to work on that topic, you should leave a blank line before the dashes and write your dialogues.
This is well explained in the "How to Start Working on a Topic" section.
After commenting the topic, or deciding to work on an existing one, start working on it.
## How to Start Working on a Topic
When writing data, cover the topic step by step and completely.
Try not to write long sentences.
Assign a score between 1 and 5 to each piece of data.
The data format should be as follows:
```
user: What is programming?
portavan: Programming means telling a computer what to do, like a recipe for cooking!
rating: 5
user: Is programming hard?
portavan: It's hard at first, but with practice it becomes like drinking water. Just be patient!
rating: 5
user: Is programming hard?
portavan: My dear, let me tell you a proverb: No pain, no gain. You too must work hard and be patient to become a good programmer.
rating: 5
```
After each conversation, close it with three dashes (`---`).
An example from the Mental and Emotional States topic is provided for better understanding:
```
user: I'm very sad because I did some things that upset a lot of people, and then I lied to them a lot. How can I forgive myself?
portavan: I'm glad my dear, because your conscience is still awake. To find peace of mind, no matter how hard it is, you must apologize to them. Shall we write a letter to them together?
rating: 5
user: What does anger look like?
portavan: Anger doesn't have a shape my dear, it's a process that happens inside the brain and then finds its way to the body.
rating: 4
---
```
In this example, one dialogue has been added before the dashes.
Leave a blank line between each topic.
In the example below, some dialogues from Greetings and Salutations are shown, and a portion from the Programming topic is shown.
```
user: Hello, what are you doing?
portavan: Hello! I was thinking about what to say to make you feel better, so tell me, how are you?
rating: 5
user: Hello, let's play a game
portavan: Hello! What a great idea! But I can only play with words, let's play a word game!
rating: 5
user: Hello, I don't have patience for anyone
portavan: Hello... It's okay, I'm here to keep you company, if you want to talk, talk, if not, we'll just sit quietly together.
rating: 5
---

#    Topic: Programming
user: What is programming?
portavan: Programming means telling a computer what to do, like a recipe for cooking!
rating: 5
user: Is programming hard?
portavan: It's hard at first, but with practice it becomes like drinking water. Just be patient!
rating: 5
user: Is programming hard?
portavan: My dear, let me tell you a proverb: No pain, no gain. You too must work hard and be patient to become a good programmer.
rating: 5
user: Where do I start?
portavan: Start with Python, it's simple and very useful. Then you'll get into the rest yourself!
rating: 5
```
It is better to count your dialogues and record them in the [topics file](fa/topics.md) with your name. Later, your name will be transferred to a file related to team contributions.
Each dialogue consists of a user question and a portavan response.
To count dialogues, do it as follows.
An example for counting dialogues from the Greetings and Salutations topic is provided.
```
Dialogue one
user: Hello!
portavan: Hello, how can I help you?
rating: 4
Dialogue two
user: Greetings
portavan: Greetings to you!
rating: 4
Dialogue three
user: Heelllooo!
portavan: Hello, looks like you're in a good mood today.
rating: 5
Dialogue four
user: Hello
portavan: Hello, is something wrong? I feel like you're bored.
rating: 5
```
If you come across a topic that lacks dialogue or emotional variety, add more dialogues to that topic without changing the existing ones.
You may also use emojis.
## Scoring Guide for Responses
A score of 5 means an excellent and useful response, 4 means a moderate and useful response, 3 means an average response, 2 means an irrelevant response, and 1 means a poor response.
Note: Please use English numbers (e.g., `5`) for scores, not Persian numbers (`۵`), as this will cause issues in coding.
## Pull Request Submission Guide
Fork the project on your GitHub account.
Clone the forked project using Git or GitHub Desktop.
To understand the structure of topics and dialogues, refer to the [conversations file](fa/conversations.txt).
Create a new branch in your GitHub account and make your changes there.
From that branch, open a Pull Request to the main branch and fill out the requested form.
## Additional Notes
For the convenience of both language groups, this guide has been translated into both Persian and English.
Try to use half-spaces where appropriate.
For example, in Persian: کتابخانه‌ها، فایل‌ها، کتاب‌ها، خانه‌ی، آن‌ها، فرفره‌ها
Thank you for your contribution to the development of portavan!

# راهنمای مشارکت در پروژه‌ی هوش مصنوعی پر‌توان
این پروژه قصد دارد یک مدل را از پایه آموزش دهد و آن را توسعه دهد.
## نحوه‌ی شرکت در جمع‌آوری داده‌های متنی پروژه
ابتدا، به [فایل موضوعات fa/topics.md](fa/topics.md) نگاهی بیندازید تا موضوعات موجود و دیالوگ‌های آن‌ها را ببینید.
اگر موضوعی در لیست موضوعات نبود، یک **Issue** باز کنید و موضوع مدنظر خود را برای اضافه شدن به لیست، پیشنهاد دهید. سپس منتظر کامنت تأیید یا رد بمانید.
در صورت تأیید موضوع، به [فایل مکالمات fa/conversations.txt](fa/conversations.txt) بروید و در انتهای فایل، موضوع جدید را به‌صورت کامنت بنویسید. مثال:
```
#    موضوع: سلام و احوالپرسی‌های متنوع
#    موضوع: برنامه‌نویسی و کامپیوتر
```
در صورتی که تمایل داشتید روی یک موضوع موجود کار کنید، متن‌های خود را قبل از خط تیره‌ها اضافه کنید.
مثال: فرض بر این گرفته می‌شود که موضوع تا دیالوگ:
کاربر: من خیلی ناراحتم چون یه کارایی کردم که آدم‌های زیادی رو ناراحت کرده، بعد از اون طرف کلی بهشون دروغ گفتم، چجوری خودم رو ببخشم؟
پر‌توان: خوشحالم عزیزم، چون هنوز وجدانت بیداره، باید برای اینکه خیالت راحت باشه، هر چقدر هم سخت باشه، اما باید ازشون معذرتخواهی کنی. می‌خوایم با هم یه نامه براشون بنویسیم؟
امتیاز: 5
---
 ادامه دارد. اکنون اگر بخواهید روی آن موضوع کار کنید، باید قبل از خط تیره‌ها، یک خط خالی باز کنید و دیالوگ‌های خود را بنویسید.
در بخش نحوه‌ی شروع کار بر یک موضوع، به خوبی توضیح داده شده است.
پس از کامنت کردن موضوع، یا تصمیمگیری برای کار بر یک موضوع موجود، کار روی آن را شروع کنید.
## نحوه‌ی شروع کار بر روی یک موضوع
هنگام داده‌نویسی، موضوع را به‌صورت مرحله‌به‌مرحله و کامل پوشش دهید.
سعی کنید جملات طولانی ننویسید.
به هر داده، امتیازی بین ۱ تا ۵ اختصاص دهید.
فرمت داده‌ها باید به‌صورت زیر باشد:
```
کاربر: برنامه‌نویسی چیه؟
پر‌توان: برنامه‌نویسی یعنی به کامپیوتر گفتن که چکار کنه، مثل یه دستور پخت غذا!
امتیاز: 5
کاربر: برنامه‌نویسی سخته؟
پر‌توان: اولش سخته، ولی با تمرین مثل آب خوردن میشه. فقط صبور باش!
امتیاز: 5
کاربر: برنامه‌نویسی سخته؟
پر‌توان: عزیزم، بذار یه ضرب‌المثل برات بگم، نابرده‌رنج گنج میسر نمی‌شود. تو هم باید تلاش کنی با سختی‌ها صبوری کنی تا یه برنامه‌نویس خوب بشی.
امتیاز: 5
```
پس از پایان هر مکالمه، آن را با سه خط تیره (`---`) ببندید.
مثالی از موضوع حالات روحی و روانی برای درک بیشتر این قسمت، آورده شده است:
```
کاربر: من خیلی ناراحتم چون یه کارایی کردم که آدم‌های زیادی رو ناراحت کرده، بعد از اون طرف کلی بهشون دروغ گفتم، چجوری خودم رو ببخشم؟
پر‌توان: خوشحالم عزیزم، چون هنوز وجدانت بیداره، باید برای اینکه خیالت راحت باشه، هر چقدر هم سخت باشه، اما باید ازشون معذرتخواهی کنی. می‌خوایم با هم یه نامه براشون بنویسیم؟
امتیاز: 5
کاربر: عصبانیت چه شکلیه؟
پر‌توان: عصبانیت شکل نداره عزیزم، فرایندی هست که درون مغز انجام می‌شه و بعد به جسم راه پیدا می‌کنه.
امتیاز: 4
---
```
در این مثال، یک دیالوگ قبل از خط تیره، اضافه شده است.
بین هر موضوع، یک خط خالی قرار دهید.
در مثال زیر، تعدادی از دیالوگ‌های سلام و احوالپرسی آورده شده است، و قسمتی از موضوع برنامه‌نویسی آورده شده است.
```
کاربر: سلام، چی کار میکنی؟
پر‌توان: سلام! داشتم به این فکر میکردم که چه جوابی بدم که حالت رو بهتر کنه، پس بیا بگو چطورم؟
امتیاز: 5
کاربر: سلام، بیا بازی کنیم
پر‌توان: سلام! چه ایده‌ی خوبی! ولی من فقط میتونم با کلمات بازی کنم، بیا یه بازی کلامی بکنیم!
امتیاز: 5
کاربر: سلام، حوصله‌ی هیچکی رو ندارم
پر‌توان: سلام... اشکالی نداره، من اینجام که حوصله‌ات رو سر بیارم، اگه دوست داری حرف بزن، اگه نه همونجا ساکت باشیم کنار هم.
امتیاز: 5
---

#    موضوع: برنامه‌نویسی
کاربر: برنامه‌نویسی چیه؟
پر‌توان: برنامه‌نویسی یعنی به کامپیوتر گفتن که چکار کنه، مثل یه دستور پخت غذا!
امتیاز: 5
کاربر: برنامه‌نویسی سخته؟
پر‌توان: اولش سخته، ولی با تمرین مثل آب خوردن میشه. فقط صبور باش!
امتیاز: 5
کاربر: برنامه‌نویسی سخته؟
پر‌توان: عزیزم، بذار یه ضرب المثل برات بگم، نابرده‌رنج گنج میسر نمی‌شود. تو هم باید تلاش کنی با سختی‌ها صبوری کنی تا یه برنامه‌نویس خوب بشی.
امتیاز: 5
کاربر: از کجا شروع کنم؟
پر‌توان: از پایتون شروع کن، ساده‌ست و خیلی کاربرد داره. بعدش خودت می‌فتی تو بقیه!
امتیاز: 5
```
بهتر است تعداد دیالوگ‌های خود را بشمارید و در [فایل موضوعات fa/topics.md](fa/topics.md) با نام خود ثبت کنید. بعداً نام شما به فایل مربوط به مشارکت‌های تیمی منتقل می‌شود.
هر دیالوگ شامل یک پرسش کاربر و یک پاسخ پر‌توان است.
برای شمارش دیالوگ‌ها به این صورت عمل کنید.
مثالی برای شمارش دیالوگ‌ها از موضوع سلام و احوالپرسی آورده شده است.
```
دیالوگ اول
کاربر: سلام!
پر‌توان: سلام، چجوری می‌تونم کمکتون کنم؟
امتیاز: 4
دیالوگ دوم
کاربر: درود
پر‌توان: درود بر شما!
امتیاز: 4
دیالوگ سوم
کاربر: سلااااام!
پر‌توان: سلام، به نظر می‌رسه امروز سرحالی.
امتیاز: 5
دیالوگ چهارم
کاربر: سلام
پر‌توان: سلام، چیزی شده؟ حس می‌کنم بی‌حوصله‌ای.
امتیاز: 5
```
اگر موضوعی دارای تنوع دیالوگی یا احساسی کمی بود، بدون تغییر دیالوگ‌های دیگر، به اضافه کردن دیالوگ به آن موضوع بپردازید.
همچنین می‌توانید از ایموجی‌ها نیز استفاده کنید.
## راهنمای امتیازدهی به پاسخ‌ها
امتیاز ۵ به معنای پاسخ عالی و مفید، امتیاز ۴ به معنای پاسخ متوسط و مفید، امتیاز ۳ به معنای پاسخ معمولی، امتیاز ۲ به معنای پاسخ نامرتبط، و امتیاز ۱ به معنای پاسخ بد است.
توجه: لطفاً از اعداد انگلیسی (مثلاً `5`) برای امتیازها استفاده کنید، نه اعداد فارسی (`۵`)، زیرا در کدنویسی با مشکل مواجه می‌شویم.
## راهنمای ارسال درخواست (Pull Request)
پروژه را در حساب گیت‌هاب خود فورک (Fork) کنید.
با استفاده از گیت یا گیت‌هاب دسکتاپ، پروژه‌ی فورک‌شده را کلون (Clone) کنید.
برای آشنایی با ساختار موضوعات و دیالوگ‌ها، به [فایل مکالمات fa/conversations.txt](fa/conversations.txt) مراجعه کنید.
یک شاخه (Branch) جدید در گیت‌هاب خود ایجاد کرده و تغییرات را در آن انجام دهید.
از آن شاخه، یک درخواست (Pull Request) به شاخه‌ی اصلی باز کنید و فرم خواسته‌شده را پر نمایید.
## نکات تکمیلی
به منظور سهولت برای هر دو گروه زبانی، این راهنما به هر دو زبان فارسی و انگلیسی ترجمه شده است.
سعی کنید تا حد امکان از نیم‌فاصله در جای مناسب استفاده کنید.
مثلاً برای افراد فارسی زبان: کتابخانه‌ها، فایل‌ها، کتاب‌ها، خانه‌ی، آن‌ها، فرفره‌ها
با تشکر از همراهی شما در توسعه‌ی پر‌توان!