# portavan AI Project Contribution Guide
This project aims to train a model from scratch and develop it further.
## How to Participate in Collecting Textual Data for the Project
First, take a look at the [topics file](en/topics.md) to see the listed topics and their dialogues.
If a topic is not in the list, open an **Issue** and suggest the topic you want to add to the list. Then wait for a confirmation or rejection comment.
Once your topic is approved, go to the [conversations file](en/conversations.txt) and add the new topic as a comment at the end of the file. Example:
```
#    Topic: Various Greetings and Salutations
#    Topic: Programming and Computers
```
After commenting the topic, start working on it.
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
Leave a blank line between each topic.
It is better to count your dialogues and record them in the [topics file](en/topics.md) with your name. Later, your name will be transferred to a file related to team contributions.
Each dialogue consists of a user question and a portavan response.
If you come across a topic that lacks dialogue or emotional variety, add more dialogues to that topic without changing the existing ones.
## Scoring Guide for Responses
A score of 5 means an excellent and useful response, 4 means a moderate and useful response, 3 means an average response, 2 means an irrelevant response, and 1 means a poor response.
Note: Please use English numbers (e.g., `5`) for scores, not Persian numbers (`۵`), as this will cause issues in coding.
## Pull Request Submission Guide
Fork the project on your GitHub account.
Clone the forked project using Git or GitHub Desktop.
To understand the structure of topics and dialogues, refer to the [conversations file](en/conversations.txt).
Create a new branch in your GitHub account and make your changes there.
From that branch, open a Pull Request to the main branch and fill out the requested form.
## Additional Notes
For the convenience of both language groups, this guide has been translated into both Persian and English.
Try to use half-spaces where appropriate.
Thank you for your contribution to the development of portavan!

# راهنمای مشارکت در پروژه‌ی هوش مصنوعی پر‌توان
این پروژه قصد دارد یک مدل را از پایه آموزش دهد و آن را توسعه دهد.
## نحوه‌ی شرکت در جمع‌آوری داده‌های متنی پروژه
ابتدا، به [فایل موضوعات](fa/topics.md) نگاهی بیندازید تا موضوعات موجود و دیالوگ‌های آن‌ها را ببینید.
اگر موضوعی در لیست موضوعات نبود، یک **Issue** باز کنید و موضوع مدنظر خود را برای اضافه شدن به لیست، پیشنهاد دهید. سپس منتظر کامنت تأیید یا رد بمانید.
در صورت تأیید موضوع، به [فایل مکالمات](fa/conversations.txt) بروید و در انتهای فایل، موضوع جدید را به‌صورت کامنت بنویسید. مثال:
```#    موضوع: سلام و احوالپرسی‌های متنوع
#    موضوع: برنامه‌نویسی و کامپیوتر
```
پس از کامنت کردن موضوع، کار روی آن را شروع کنید.
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
پر‌توان: عزیزم، بذار یه ضربالمثل برات بگم، نابرده‌رنج گنج میسر نمی‌شود. تو هم باید تلاش کنی با سختی‌ها صبوری کنی تا یه برنامه‌نویس خوب بشی.
امتیاز: 5
```
پس از پایان هر مکالمه، آن را با سه خط تیره (`---`) ببندید.
بین هر موضوع، یک خط خالی قرار دهید.
بهتر است تعداد دیالوگ‌های خود را بشمارید و در [فایل موضوعات](fa/topics.md) با نام خود ثبت کنید. بعداً نام شما به فایل مربوط به مشارکت‌های تیمی منتقل می‌شود.
هر دیالوگ شامل یک پرسش کاربر و یک پاسخ پر‌توان است.
اگر موضوعی دارای تنوع دیالوگی یا احساسی کمی بود، بدون تغییر دیالوگ‌های دیگر، به اضافه کردن دیالوگ به آن موضوع بپردازید.
## راهنمای امتیازدهی به پاسخ‌ها
امتیاز ۵ به معنای پاسخ عالی و مفید، امتیاز ۴ به معنای پاسخ متوسط و مفید، امتیاز ۳ به معنای پاسخ معمولی، امتیاز ۲ به معنای پاسخ نامرتبط، و امتیاز ۱ به معنای پاسخ بد است.
توجه: لطفاً از اعداد انگلیسی (مثلاً `5`) برای امتیازها استفاده کنید، نه اعداد فارسی (`۵`)، زیرا در کدنویسی با مشکل مواجه می‌شویم.
## راهنمای ارسال درخواست (Pull Request)
پروژه را در حساب گیت‌هاب خود فورک (Fork) کنید.
با استفاده از گیت یا گیت‌هاب دسکتاپ، پروژه‌ی فورک‌شده را کلون (Clone) کنید.
برای آشنایی با ساختار موضوعات و دیالوگ‌ها، به [فایل مکالمات](fa/conversations.txt) مراجعه کنید.
یک شاخه (Branch) جدید در گیت‌هاب خود ایجاد کرده و تغییرات را در آن انجام دهید.
از آن شاخه، یک درخواست (Pull Request) به شاخه‌ی اصلی باز کنید و فرم خواسته‌شده را پر نمایید.
## نکات تکمیلی
به منظور سهولت برای هر دو گروه زبانی، این راهنما به هر دو زبان فارسی و انگلیسی ترجمه شده است.
سعی کنید تا حد امکان از نیم‌فاصله در جای مناسب استفاده کنید.
با تشکر از همراهی شما در توسعه‌ی پر‌توان!