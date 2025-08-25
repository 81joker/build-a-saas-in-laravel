# 1- Install [Duster](https://github.com/tighten/duster)

✅ الفوائد الرئيسية لـ Duster
تحسين جودة الكود: تقوم بفحص الكود بحثًا عن الأخطاء أو التنسيقات غير المتوافقة مع المعايير، وتصلحها تلقائيًا.

توفير الوقت: بدلاً من مراجعة الكود يدويًا، تقوم Duster بذلك بضغطة زر.

توحيد تنسيق الكود: تجعل الكود متناسقًا بين أعضاء الفريق باستخدام قواعد Tighten.

دعم أدوات متعددة:

TLint: لفحص كود Laravel.

PHP_CodeSniffer: لاكتشاف مشاكل لا يمكن إصلاحها تلقائيًا.

PHP CS Fixer: لإصلاح مشاكل التنسيق.

Pint: لتطبيق قواعد Laravel الرسمية مع تعديلات Tighten.

سهولة الاستخدام: أوامر بسيطة مثل:

bash
./vendor/bin/duster lint # لفحص الكود
./vendor/bin/duster fix # لإصلاح الكود
./vendor/bin/duster lint --dirty # لفحص الملفات المعدلة فقط
قابلية التخصيص: يمكنك تعديل الملفات التي يتم فحصها أو استثناؤها عبر ملف duster.json.

تكامل مع GitHub Actions و Husky Hooks: لتشغيل Duster تلقائيًا أثناء عمليات الـ commit أو في CI/CD.
✅ Key Benefits of Duster
Improved Code Quality: It scans code for errors or non-standard formatting and automatically fixes them.

Time Savings: Instead of manually reviewing code, Duster does this with the push of a button.

Coding Standardization: It makes code consistent across team members using Tighten's rules.

Multiple Tool Support:

TLint: For scanning Laravel code.

PHP_CodeSniffer: For automatically detecting issues that cannot be fixed.

PHP CS Fixer: For fixing formatting issues.

Pint: For applying official Laravel rules with Tighten modifications.

Ease of Use: Simple commands like:

bash
./vendor/bin/duster lint # For scanning code
./vendor/bin/duster fix # For fixing code
./vendor/bin/duster lint --dirty # For scanning only modified files
Customizability: You can modify which files are scanned or excluded via the duster.json file.

Integration with GitHub Actions and Husky Hooks: Automatically trigger Duster during commits or in CI/CD.

# 2- [How to set up Prettier On a Laravel](https://mattstauffer.com/blog/how-to-set-up-prettier-on-a-laravel-app-to-lint-tailwind-class-order-and-more/)
