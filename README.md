ایجاد پوشه پروژه در درایو و یا در گیت یا کامند پرامپت با دستور    mkdir nameProject
رفتن روی پوشه پروژه با دستور     cd nameProject
برای ایجاد فایل در ترمینال گیت دستور   touch filename
برای ایجاد فایل در ترمینال کامند پرامپت ویندوز echo. > filename 
برای مشاهده وضعیت فایل ها   git status
اضافه کردن فایل یا فایل ها دستور  git add filename   or   git add -A
برای ثبت تغییرات   git commit -m "message …. Add filename"
و برای مشاهده جزئیات تغییرات     git log
برای مشاهده فایل ها در پروژه در ترمینال گیت دستور ls
برای مشاهده فایل ها در پروژه در کامند پرامپت ویندوز دستور dir
حذف فایل از گیت و از سیستم:
1-	با دستور  git rm nameFile
2-	git commit -m "message … nameFile"
3-	git push
حذف فایل از گیت ولی نگه داشتن روی سیستم:
1-	git rm --cached filename
2-	git commit -m "message … filename"
3-	git push
نکته : برای حذف کل پروژه  git rm nameProject
برای مشاهده اینکه به گیت هاب وصل شدیم دستور git remote -v
برای وصل شدن به گیت هاب دستور  git remote add origin

نکته : دیدن محتوای فایل در ترمینال ویندوز   type filename
باز کردن با Notepad در ترمینال : notepad filename
باز کردن فایل در ترمینال با پای چارم و کار کردن  روی آن:  pycharm filename


برای بردن پروژه به گیت هاب از سیستم :
1-	رفتن روی پوشه پروژه با دستور     cd nameProject
2-	گیت کردن پروژه با دستور   git init
3-	اضافه کردن فایل ها با دستور git add -A   or   git add .
4-	ثبت تغییرات با دستور  git commit -m "message….."
5-	تغییر نام برنچ با دستور  git branch -M main
6-	اتصال پروژه به مخزن ریپازیتوری گیت با دستور  git remote add origin repositoryAddress
7-	نکته : ریپازیتوری که در گیت هاب ایجاد کردیم یک لینک ادرس دارد که در مرحله 6 استفاده می کنیم
8-	بررسی می کنیم با دستور git remote -v
9-	ارسال پروژه به گیت با دستور main  git push -u origin
10-	نکته: اگر مرحله 5 را انجام ندهیم در واقع در برنچ master هستیم و د ستور 9 کار نمی کند.

اگر آدرس مخزن گیت هاب درست نبود آدرس را با دستور روبرو حذف می کنیم   git remote remove origin .
و آدرس اصلاح شده را مجدد اجرا می کمیم تا مخزن اضافه شود  با دستور git remote add origin address git project   .
اکنون بعد از اصلاح آدرس مخزن گیت هاب ، آن را می بریم روی شاخه master با دستور git push -u origin master    .
