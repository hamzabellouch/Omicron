Privacy Policy - Omicron
Last Updated: July 30, 2026


1. Executive Summary & Overview

Omicron is an open-source Android media downloader application designed to assist users in downloading, extracting, and processing online videos, audio files, images, and thumbnails from user-provided URLs to their local device storage. Core Privacy Commitment > Omicron operates "100% on-device". We do not collect, store, transmit, share, or sell any personal data, download histories, user-provided URLs, device identifiers, or media files to external servers, analytics providers, or third parties.


2. Information Processed On-Device
To deliver its core media downloading and post-processing features, Omicron reads and processes the following information "locally on your device":

- User-Provided URLs & Download Links: Links entered manually or shared to Omicron via the Android Share sheet are processed strictly on-device to extract, convert, and download media.
- Optional Cookies & Authentication Sessions: If you manually import a `cookies.txt` file (to download media from accounts or platforms you own), the credentials remain encrypted and stored strictly on your local device.
- Local Download History & Metrics: Records of completed or active downloads, target save folders, and engine options are saved locally to display download progress in the app interface.
- Local Preferences: App settings (such as preferred video resolution, audio format, output path, and theme options) are stored locally using Android `SharedPreferences` and `MMKV`.


3. Permissions Used & Their Purposes
Omicron requests specific Android permissions strictly to deliver its core media downloading functionality:

A. Internet & Network Access (`INTERNET`, `ACCESS_NETWORK_STATE`)
- Purpose: Allows Omicron to connect to online media sources to download video, audio, and image content requested by the user, and to check network availability.
- Scope: Used exclusively to perform user-initiated downloads and engine binary updates.

B. Storage Access (`WRITE_EXTERNAL_STORAGE`, `MANAGE_EXTERNAL_STORAGE`)
- Purpose: Enables Omicron to save downloaded videos, audio, images, and thumbnails directly to your device storage or external SD card.
- Scope: Used strictly to write user-requested media files to designated download directories.

C. Foreground Service (`FOREGROUND_SERVICE`, `FOREGROUND_SERVICE_SPECIAL_USE`)
- Purpose: Keeps active media downloads and post-processing operations (such as FFmpeg video remuxing or audio extraction) running reliably in the background without being interrupted by the OS.

- Scope: Active only while a download or conversion task is in progress.
D. Notifications (`POST_NOTIFICATIONS`)

- Purpose: Displays real-time download progress, completion alerts, and control actions (pause/cancel/resume) in the Android notification shade.
E. Battery Optimization Exemption (`REQUEST_IGNORE_BATTERY_OPTIMIZATIONS`)
- Purpose: Allows users to optionally exempt Omicron from system battery restrictions so large media downloads finish without being terminated when the device screen turns off.

F. Package Installation (`REQUEST_INSTALL_PACKAGES`)
- Purpose: Allows users to update in-app downloader engine binaries or app builds directly within the app when initiated by the user.


4. Third-Party Engines & Local Processing Disclosure
Omicron incorporates open-source binary engines (including `yt-dlp`, `gallery-dl`, `FFmpeg`, and `aria2c`) to process media locally on your device:

- Local Execution Only: All media parsing, video downloading, and audio/video conversions are executed locally on your Android device.
- Zero External Telemetry: The bundled open-source tools do not report telemetry, device identifiers, or user activity to external servers.
- User Control: Users can customize command flags, update engine binaries, or clear local engine caches at any time within the app settings.


5. Content Rights & Copyright Responsibility
Omicron is a utility tool intended solely for downloading media content that users have the legal right, permission, or license to access and save. 

- User Responsibility: Users are solely responsible for complying with applicable copyright laws, terms of service of third-party platforms, and intellectual property rights.
- No Hosted Content: Omicron does not host, upload, re-transmit, or index any media files or copyright-protected material.


6. Children's Privacy Notice
Omicron is not directed to children under the age of 13 (or 16 in certain jurisdictions). Because Omicron operates 100% locally and does not collect or transmit any personal data, we do not knowingly solicit or collect personal information from children.


7. Data Sharing, Analytics & Advertising

- No External Data Sharing: No URLs, downloaded files, or personal information leave your device.
- No Third-Party Analytics / Tracking: Omicron does not integrate third-party tracking SDKs, behavioral analytics, or telemetry frameworks.
- No Ads: Omicron is 100% clean and does not display targeted or third-party advertisements.


8. Data Retention & Lifecycle

- Temporary Media Buffers: All transient file fragments, segment buffers, and temporary FFmpeg files are automatically deleted upon download completion or task cancellation.
- Complete Local Removal: Clearing app data or uninstalling Omicron immediately and permanently removes all saved download histories, preferences, and imported cookies stored in app-private storage. (Downloaded media saved to your public device folders remains untouched on your device).


9. Managing Permissions & User Rights
You maintain full control over the permissions granted to Omicron. You may review or revoke any permission at any time via Android Settings:

1. Storage & Notification Permissions: `Settings > Apps > Omicron > Permissions`
2. Special Access & Battery Optimization: `Settings > Apps > Omicron > Battery / Special App Access`


10. Changes to This Privacy Policy
We may update our Privacy Policy from time to time to reflect app updates or regulatory requirements. Any changes will be posted within this document with an updated "Last Updated" date.


11. Contact & Support
If you have any questions or feedback regarding this Privacy Policy or permission usage, please contact us at:  
Email: hamzabellouchcontact@gmail.com


---


سياسة الخصوصية - Omicron
آخر تحديث: ٣٠ يوليو ٢٠٢٦

١. الملخص التنفيذي والنظرة العامة

Omicron هو تطبيق مفتوح المصدر لنظام Android لتنزيل الوسائط، صُمم لمساعدة المستخدمين في تنزيل واستخراج ومعالجة مقاطع الفيديو عبر الإنترنت، والملفات الصوتية، والصور، والصور المصغرة من عناوين URL التي يوفرها المستخدم إلى وحدة التخزين المحلية على جهازه. الالتزام الأساسي بالخصوصية > يعمل Omicron بنسبة "١٠٠٪ على الجهاز". نحن لا نجمع أو نخزن أو ننقل أو نشارك أو نبيع أي بيانات شخصية، أو سجلات التنزيل، أو عناوين URL التي يوفرها المستخدم، أو معرّفات الجهاز، أو ملفات الوسائط إلى خوادم خارجية، أو مزودي التحليلات، أو أطراف ثالثة.

٢. المعلومات التي تتم معالجتها على الجهاز
لتقديم ميزاته الأساسية الخاصة بتنزيل الوسائط ومعالجتها بعد التنزيل، يقوم Omicron بقراءة ومعالجة المعلومات التالية "محليًا على جهازك":

* عناوين URL وروابط التنزيل التي يوفرها المستخدم: تتم معالجة الروابط التي يتم إدخالها يدويًا أو مشاركتها مع Omicron عبر Android Share Sheet بشكل صارم على الجهاز لاستخراج الوسائط وتحويلها وتنزيلها.
* ملفات تعريف الارتباط الاختيارية وجلسات المصادقة: إذا قمت باستيراد ملف `cookies.txt` يدويًا (لتنزيل الوسائط من الحسابات أو المنصات التي تملكها)، فستظل بيانات الاعتماد مشفرة ومخزنة بشكل صارم على جهازك المحلي.
* سجل التنزيل المحلي والمقاييس: يتم حفظ سجلات التنزيلات المكتملة أو النشطة، ومجلدات الحفظ المستهدفة، وخيارات المحرك محليًا لعرض تقدم التنزيل داخل واجهة التطبيق.
* التفضيلات المحلية: يتم تخزين إعدادات التطبيق (مثل دقة الفيديو المفضلة، وتنسيق الصوت، ومسار الإخراج، وخيارات السمة) محليًا باستخدام Android `SharedPreferences` و `MMKV`.

٣. الأذونات المستخدمة وأغراضها
يطلب Omicron أذونات Android محددة فقط لتقديم وظائفه الأساسية الخاصة بتنزيل الوسائط:

أ. الوصول إلى الإنترنت والشبكة (`INTERNET`, `ACCESS_NETWORK_STATE`)

* الغرض: يسمح لـ Omicron بالاتصال بمصادر الوسائط عبر الإنترنت لتنزيل محتوى الفيديو والصوت والصور الذي يطلبه المستخدم، والتحقق من توفر الشبكة.
* النطاق: يُستخدم حصريًا لتنفيذ عمليات التنزيل التي يبدأها المستخدم وتحديثات ملفات المحرك الثنائية.

ب. الوصول إلى التخزين (`WRITE_EXTERNAL_STORAGE`, `MANAGE_EXTERNAL_STORAGE`)

* الغرض: يمكّن Omicron من حفظ مقاطع الفيديو والملفات الصوتية والصور والصور المصغرة التي تم تنزيلها مباشرةً في وحدة تخزين جهازك أو بطاقة SD الخارجية.
* النطاق: يُستخدم بشكل صارم لكتابة ملفات الوسائط التي يطلبها المستخدم في أدلة التنزيل المحددة.

ج. خدمة المقدمة (`FOREGROUND_SERVICE`, `FOREGROUND_SERVICE_SPECIAL_USE`)

* الغرض: تحافظ على تشغيل تنزيلات الوسائط النشطة وعمليات المعالجة اللاحقة (مثل إعادة تغليف الفيديو باستخدام FFmpeg أو استخراج الصوت) بشكل موثوق في الخلفية دون أن يقاطعها نظام التشغيل.

* النطاق: تكون نشطة فقط أثناء تقدم مهمة تنزيل أو تحويل.
  د. الإشعارات (`POST_NOTIFICATIONS`)

* الغرض: تعرض تقدم التنزيل في الوقت الفعلي، وتنبيهات الاكتمال، وإجراءات التحكم (إيقاف مؤقت/إلغاء/استئناف) في لوحة إشعارات Android.

هـ. الإعفاء من تحسين البطارية (`REQUEST_IGNORE_BATTERY_OPTIMIZATIONS`)

* الغرض: يسمح للمستخدمين بإعفاء Omicron اختياريًا من قيود بطارية النظام حتى تكتمل تنزيلات الوسائط الكبيرة دون إنهائها عند إطفاء شاشة الجهاز.

و. تثبيت الحزم (`REQUEST_INSTALL_PACKAGES`)

* الغرض: يسمح للمستخدمين بتحديث ملفات محرك التنزيل الثنائية داخل التطبيق أو إصدارات التطبيق مباشرةً من داخل التطبيق عند بدء العملية من قبل المستخدم.

٤. الإفصاح عن محركات الطرف الثالث والمعالجة المحلية
يتضمن Omicron محركات ثنائية مفتوحة المصدر (بما في ذلك `yt-dlp` و `gallery-dl` و `FFmpeg` و `aria2c`) لمعالجة الوسائط محليًا على جهازك:

* التنفيذ المحلي فقط: يتم تنفيذ جميع عمليات تحليل الوسائط وتنزيل الفيديو وتحويلات الصوت/الفيديو محليًا على جهاز Android الخاص بك.
* عدم وجود قياس عن بُعد خارجي: لا تقوم الأدوات مفتوحة المصدر المضمنة بالإبلاغ عن بيانات القياس عن بُعد، أو معرّفات الجهاز، أو نشاط المستخدم إلى خوادم خارجية.
* تحكم المستخدم: يمكن للمستخدمين تخصيص علامات الأوامر، أو تحديث ملفات المحرك الثنائية، أو مسح ذاكرة التخزين المؤقت المحلية للمحرك في أي وقت من داخل إعدادات التطبيق.

٥. حقوق المحتوى ومسؤولية حقوق النشر
Omicron هو أداة مساعدة مخصصة فقط لتنزيل محتوى الوسائط الذي يمتلك المستخدمون الحق القانوني أو الإذن أو الترخيص للوصول إليه وحفظه.

* مسؤولية المستخدم: يتحمل المستخدمون وحدهم مسؤولية الامتثال لقوانين حقوق النشر المعمول بها، وشروط خدمة المنصات التابعة لجهات خارجية، وحقوق الملكية الفكرية.
* عدم استضافة المحتوى: لا يقوم Omicron باستضافة أو رفع أو إعادة نقل أو فهرسة أي ملفات وسائط أو مواد محمية بحقوق النشر.

٦. إشعار خصوصية الأطفال
Omicron غير موجه للأطفال دون سن ١٣ عامًا (أو ١٦ عامًا في بعض الولايات القضائية). ونظرًا لأن Omicron يعمل بنسبة ١٠٠٪ محليًا ولا يجمع أو ينقل أي بيانات شخصية، فإننا لا نطلب أو نجمع عن علم أي معلومات شخصية من الأطفال.

٧. مشاركة البيانات والتحليلات والإعلانات

* عدم مشاركة البيانات خارجيًا: لا تغادر أي عناوين URL أو ملفات تم تنزيلها أو معلومات شخصية جهازك.
* عدم وجود تحليلات أو تتبع من جهات خارجية: لا يدمج Omicron أي SDKs للتتبع من جهات خارجية، أو تحليلات سلوكية، أو أطر عمل للقياس عن بُعد.
* لا توجد إعلانات: Omicron نظيف بنسبة ١٠٠٪ ولا يعرض إعلانات موجهة أو إعلانات من جهات خارجية.

٨. الاحتفاظ بالبيانات ودورة حياتها

* المخازن المؤقتة المؤقتة للوسائط: يتم حذف جميع أجزاء الملفات المؤقتة، ومخازن المقاطع، وملفات FFmpeg المؤقتة تلقائيًا عند اكتمال التنزيل أو إلغاء المهمة.
* الإزالة المحلية الكاملة: يؤدي مسح بيانات التطبيق أو إلغاء تثبيت Omicron إلى إزالة جميع سجلات التنزيل المحفوظة، والتفضيلات، وملفات تعريف الارتباط المستوردة المخزنة في مساحة التخزين الخاصة بالتطبيق فورًا وبشكل دائم. (تظل الوسائط التي تم تنزيلها والمحفوظة في مجلدات جهازك العامة دون تغيير على جهازك).

٩. إدارة الأذونات وحقوق المستخدم
تحتفظ بالتحكم الكامل في الأذونات الممنوحة لـ Omicron. يمكنك مراجعة أو إلغاء أي إذن في أي وقت عبر إعدادات Android:

١٠. أذونات التخزين والإشعارات: `Settings > Apps > Omicron > Permissions`

١١. الوصول الخاص وتحسين البطارية: `Settings > Apps > Omicron > Battery / Special App Access`

١٢. التغييرات على سياسة الخصوصية هذه
قد نقوم بتحديث سياسة الخصوصية الخاصة بنا من وقت لآخر لتعكس تحديثات التطبيق أو المتطلبات التنظيمية. سيتم نشر أي تغييرات داخل هذا المستند مع تحديث تاريخ "آخر تحديث".

١٣. التواصل والدعم
إذا كانت لديك أي أسئلة أو ملاحظات بشأن سياسة الخصوصية هذه أو استخدام الأذونات، فيرجى التواصل معنا على:

البريد الإلكتروني: [hamzabellouchcontact@gmail.com](mailto:hamzabellouchcontact@gmail.com)

