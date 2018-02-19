# دستورات موجود در کنسول دروپال

**یادداشت:** دستورات کنسول دروپال *باید* از درون یک محیط دروپال ۸ اجرا شوند.

دستور | توضیحات
------------ | -------------
**misc**  |
[about](about.md) | نمایش اطلاعات پایه درباره پروژه کنسول دروپال
[chain](chain.md) | اجرای زنجیره‌وار دستورات
[check](check.md) | بررسی‌کننده نیازمندی‌های سیستم
[exec](exec.md) | اجرای یک دستور خارجی
[help](help.md) | نمایش راهنما برای یک دستور
[init](init.md) | رونوشت‌گیری از فایل‌های پیکربندی
[list](list.md) | نمایش فهرستی از دستورات موجود
[shell](shell.md) | باز کردن یک پوسته و حالت تعاملی REPL یا Read–Eval–Print-Loop
[server](server.md) | اجرای وب سرور درونی PHP
**cache**  |
[cache:rebuild](cache-rebuild.md) | بازسازی و پاکسازی حافظه نهان در سایت
**config**  |
[config:delete](config-delete.md) | حذف پیکربندی
[config:diff](config-diff.md) | نمایش گزینه‌هایی از پیکربندی که متفاوت با گزینه‌های موجود در یک دایرکتوری دیگر باشد
[config:edit](config-edit.md) | تغییر یک شی پیکربندی با استفاده از ویرایشگر متنی
[config:export](config-export.md) | خروجی گرفتن از پیکربندی فعلی برنامه
[config:export:content:type](config-export-content-type.md) | خروجی گرفتن از یک نوع محتوای خاص و فیلدهای آن
[config:export:single](config-export-single.md) | خروجی گرفتن از یک پیکربندی یا مجموعه پیکربندی‌های مشخص شده در فایل YAML
[config:export:view](config-export-view.md) | خروجی گرفتن از یک View در قالب YAML به صورت افزونه که قابل استفاده در سایت دیگری باشد
[config:import](config-import.md) | وارد کردن پیکربندی به برنامه
[config:import:single](config-import-single.md) | وارد کردن یک پیکربندی یا مجموعه‌ای از پیکربندی‌ها
[config:override](config-override.md) | بازنویسی مقادیر در پیکربندی فعال سایت
[config:validate](config-validate.md) | ارزیابی یک پیکربندی دروپال در مقایسه با ساختار اصلی آن
**create**  |
[create:comments](create-comments.md) | ایجاد دیدگاه‌های آزمایشی برای سایت دروپال ۸
[create:nodes](create-nodes.md) | ایجاد مطالب آزمایشی برای سایت دروپال ۸
[create:terms](create-terms.md) | ایجاد عبارت‌های آزمایشی برای سایت دروپال ۸
[create:users](create-users.md) | ایجاد کاربران آزمایشی برای سایت دروپال ۸
[create:vocabularies](create-vocabularies.md) | ایجاد واژگان آزمایشی برای سایت دروپال ۸
**cron**  |
[cron:execute](cron-execute.md) | اجرای پیاده‌سازی کرون توسط افزونه‌ها یا کل سیستم
[cron:release](cron-release.md) | آزادسازی قفل سیستم کرون به منظور اجرای مجدد
**database**  |
[database:add](database-add.md) | افزودن پایگاه‌داده به settings.php
[database:client](database-client.md) | اجرای کلاینت پایگاه‌داده در صورت موجود بودن
[database:connect](database-connect.md) | نمایش پیوند ارتباط پایگاه‌داده
[database:drop](database-drop.md) | حذف تمام جدول‌ها درون یک پایگاه‌داده
[database:dump](database-dump.md) | نمونه‌گیری از ساختار و محتوای موجود در یک پایگاه‌داده
[database:log:clear](database-log-clear.md) | حذف رویدادها از جدول DBLog، فیلترها موجود هستند
[database:log:poll](database-log-poll.md) | نظارت بر watchdog چاپ گزارش‌ها هر x ثانیه
[database:query](database-query.md) | اجرای مستقیم یک دستور SQL به عنوان آرگومان
[database:restore](database-restore.md) | بازیابی ساختار و محتوای یک پایگاه‌داده
**debug**  |
[debug:breakpoints](debug-breakpoints.md) | نمایش breakpoint موجود در برنامه
[debug:cache:context](debug-cache-context.md) | نمایش محدوده حافظه نهان فعلی در برنامه
[debug:chain](debug-chain.md) | فهرستی از فایل‌های زنجیره‌ای موجود
[debug:config](debug-config.md) | فهرستی از نام اشیای پیکربندی موجود
[debug:config:settings](debug-config-settings.md) | نمایش کلید:مقدار فعلی از فایل settings
[debug:config:validate](debug-config-validate.md) | ارزیابی پیاده‌سازی جدول پیش از فعال‌سازی افزونه
[debug:container](debug-container.md) | نمایش سرویس‌های فعلی در برنامه
[debug:cron](debug-cron.md) | فهرستی از افزونه‌هایی که کرون را پیاده‌سازی می‌کنند
[debug:database:log](debug-database-log.md) | نمایش رویدادهای لاگ فعلی در برنامه
[debug:database:table](debug-database-table.md) | نمایش تمام جدول‌ها از یک پایگاه‌داده
[debug:entity](debug-entity.md) | دیباگ انواع entity موجود در سیستم
[debug:event](debug-event.md) | نمایش رویدادهای فعلی
[debug:features](debug-features.md) | فهرستی از ویژگی‌های ثبت شده
[debug:image:styles](debug-image-styles.md) | فهرست سبک‌های تصویری موجود در سایت
[debug:libraries](debug-libraries.md) | نمایش کتابخانه‌های موجود در برنامه
[debug:migrate](debug-migrate.md) | نمایش طرح مهاجرت فعلی در برنامه
[debug:module](debug-module.md) | نمایش افزونه‌های موجود در برنامه
[debug:multisite](debug-multisite.md) | فهرستی از تمام سایت‌های موجود در سیستم
[debug:permission](debug-permission.md) | نمایش تمام مجوزهای کاربران
[debug:plugin](debug-plugin.md) | نمایش تمام انواع پلاگین
[debug:queue](debug-queue.md) | نمایش صف‌های موجود در برنامه
[debug:rest](debug-rest.md) | نمایش منابع rest موجود در سیستم
[debug:router](debug-router.md) | نمایش مسیرهای فعلی در برنامه یا جزئیات یک مسیر خاص
[debug:settings](debug-settings.md) | فهرستی از تنظیمات کاربری مرتبط با کنسول دروپال
[debug:site](debug-site.md) | فهرستی از تمام سایت‌های محلی و راه‌دور
[debug:state](debug-state.md) | نمایش کلیدهای حالت وضعیت سایت
[debug:test](debug-test.md) | فهرستی از Unit Test های موجود در برنامه
[debug:theme](debug-theme.md) | نمایش قالب فعلی در برنامه
[debug:update](debug-update.md) | نمایش بروزرسانی‌های موجود برای برنامه
[debug:user](debug-user.md) | نمایش کاربران فعلی برای برنامه
[debug:views](debug-views.md) | نمایش منابع مرتبط با Views در برنامه
[debug:views:plugins](debug-views-plugins.md) | نمایش پلاگین‌های Views موجود در برنامه
**devel**  |
[devel:dumper](devel-dumper.md) | تغییر در پلاگین dumper
**develop**  |
[develop:contribute](develop-contribute.md) | 
[develop:example](develop-example.md) | 
[develop:example:container:aware](develop-example-container-aware.md) | 
[develop:gitbook](develop-gitbook.md) | بروزرسانی gitbook
**dotenv**  |
[dotenv:debug](dotenv-debug.md) | دیباگ مقادیر مرتبط با Dotenv
[dotenv:init](dotenv-init.md) | راه‌اندازی اولیه Dotenv
**entity**  |
[entity:delete](entity-delete.md) | حذف یک entity بخصوص
**extend**  |
[extend:example:one](extend-example-one.md) | مثالی از توسعه کنسول دروپال
[extend:example:two](extend-example-two.md) | مثالی از توسعه کنسول دروپال
**features**  |
[features:import](features-import.md) | واردکردن پیکربندی افزونه
**field**  |
[field:info](field-info.md) | مشاهده اطلاعات درباره فیلدها
**generate**  |
[generate:authentication:provider](generate-authentication-provider.md) | تولید یک Authentication Provider
[generate:breakpoint](generate-breakpoint.md) | تولید breakpoint
[generate:cache:context](generate-cache-context.md) | تولید یک محدوده برای حافظه نهان
[generate:command](generate-command.md) | تولید دستورات برای کنسول
[generate:controller](generate-controller.md) | تولید و ثبت یک کنترلر
[generate:doc:cheatsheet](generate-doc-cheatsheet.md) | commands.generate.doc.cheatsheet.description
[generate:doc:dash](generate-doc-dash.md) | commands.generate.doc.dash.description
[generate:doc:data](generate-doc-data.md) | commands.generate.doc.data.description
[generate:doc:gitbook](generate-doc-gitbook.md) | commands.generate.doc.gitbook.description
[generate:entity:bundle](generate-entity-bundle.md) | تولید یک نوع محتوای جدید (node / entity bundle)
[generate:entity:config](generate-entity-config.md) | تولید یک entity پیکربندی
[generate:entity:content](generate-entity-content.md) | تولید یک entity محتوایی
[generate:event:subscriber](generate-event-subscriber.md) | تولید یک event subscriber
[generate:form](generate-form.md) | تولید یک "%s" جدید
[generate:form:alter](generate-form-alter.md) | تولید یک پیاده‌سازی از hook_form_alter() یا hook_form_FORM_ID_alter
[generate:form:config](generate-form-config.md) | commands.generate.form.description
[generate:help](generate-help.md) | تولید یک پیاده‌سازی از hook_help()
[generate:module](generate-module.md) | تولید یک افزونه
[generate:module:file](generate-module-file.md) | تولید یک فایل .module
[generate:permissions](generate-permissions.md) | commands.generate.permission.description
[generate:plugin:block](generate-plugin-block.md) | تولید یک بلاک پلاگین
[generate:plugin:ckeditorbutton](generate-plugin-ckeditorbutton.md) | تولید پلاگین دکمه برای CKEditor
[generate:plugin:condition](generate-plugin-condition.md) | تولید یک شرط برای پلاگین
[generate:plugin:field](generate-plugin-field.md) | تولید نوع فیلد، ویجت و قالب‌دهنده آن
[generate:plugin:fieldformatter](generate-plugin-fieldformatter.md) | تولید پلاگین قالب‌دهنده فیلد
[generate:plugin:fieldtype](generate-plugin-fieldtype.md) | تولید پلاگین نوع فیلد
[generate:plugin:fieldwidget](generate-plugin-fieldwidget.md) | تولید پلاگین ویجت فیلد
[generate:plugin:imageeffect](generate-plugin-imageeffect.md) | تولید پلاگین تصویری
[generate:plugin:imageformatter](generate-plugin-imageformatter.md) | تولید پلاگین قالب‌دهنده تصویری
[generate:plugin:mail](generate-plugin-mail.md) | تولید پلاگین ایمیل
[generate:plugin:migrate:process](generate-plugin-migrate-process.md) | تولید پلاگین فرآیند مهاجرت
[generate:plugin:migrate:source](generate-plugin-migrate-source.md) | تولید پلاگین منبع مهاجرت
[generate:plugin:rest:resource](generate-plugin-rest-resource.md) | تولید پلاگین منبع rest
[generate:plugin:rulesaction](generate-plugin-rulesaction.md) | تولید پلاگین اقدامات rule
[generate:plugin:skeleton](generate-plugin-skeleton.md) | تولید یک پیاده‌سازی از پلاگین اولیه
[generate:plugin:type:annotation](generate-plugin-type-annotation.md) | تولید نوع پلاگین همراه با annotation discovery
[generate:plugin:type:yaml](generate-plugin-type-yaml.md) | تولید نوع پلاگین همراه با Yaml discovery
[generate:plugin:views:field](generate-plugin-views-field.md) | تولید فیلد نمایش یک پلاگین سفارشی
[generate:post:update](generate-post-update.md) | commands.generate.post:update.description
[generate:profile](generate-profile.md) | تولید یک پروفایل
[generate:routesubscriber](generate-routesubscriber.md) | تولید یک RouteSubscriber
[generate:service](generate-service.md) | تولید سرویس
[generate:theme](generate-theme.md) | تولید یک قالب
[generate:twig:extension](generate-twig-extension.md) | تولید یک افزونه Twig
[generate:update](generate-update.md) | تولید یک پیاده‌سازی از hook_update_N()
**image**  |
[image:styles:flush](image-styles-flush.md) | اجرای تابع flush توسط سبک تصویری یا اجرای آن برای همه سبک‌ها
**locale**  |
[locale:language:add](locale-language-add.md) | افزودن یک زبان به منظور پشتیبانی در سایت
[locale:language:delete](locale-language-delete.md) | حذف یک زبان پشتیبانی شده توسط سایت
[locale:translation:status](locale-translation-status.md) | فهرست بروزرسانی‌های موجود برای ترجمه
**migrate**  |
[migrate:execute](migrate-execute.md) | اجرای طرح مهاجرت موجود برای برنامه
[migrate:rollback](migrate-rollback.md) | بازگردانی یک یا چند طرح مهاجرت
[migrate:setup](migrate-setup.md) | بارگیری و ایجاد مهاجرت‌های موجود از پایگاه‌داده قدیم
**module**  |
[module:dependency:install](module-dependency-install.md) | commands.module.install.dependencies.description
[module:download](module-download.md) | دانلود افزونه یا افزونه‌ها در برنامه
[module:install](module-install.md) | نصب افزونه یا افزونه‌ها در برنامه
[module:path](module-path.md) | بازگرداندن مسیر نسبی یا مطلق یک افزونه
[module:uninstall](module-uninstall.md) | حذف افزونه یا افزونه‌های موجود در برنامه
[module:update](module-update.md) | بروزرسانی هسته، افزونه یا افزونه‌ها در برنامه
**multisite**  |
[multisite:new](multisite-new.md) | برپایی فایل‌های مورد نیاز برای یک محیط چند-سایته
**node**  |
[node:access:rebuild](node-access-rebuild.md) | بازسازی مجوزهای دسترسی به node
**queue**  |
[queue:run](queue-run.md) | پردازش صف انتخابی
**quick**  |
[quick:start](quick-start.md) | دانلود، نصب و راه‌اندازی یک سایت چدید
**rest**  |
[rest:disable](rest-disable.md) | غیرفعال کردن یک منبع rest برای برنامه
[rest:enable](rest-enable.md) | فعال کردن یک منبع rest برای برنامه
**router**  |
[router:rebuild](router-rebuild.md) | بازسازی مسیرها برای برنامه
**sample**  |
[sample:default](sample-default.md) | commands.sample.default.description
**settings**  |
[settings:set](settings-set.md) | تغییر یک مقدار بخصوص در فایل پیکربندی DrupalConsole
**site**  |
[site:import:local](site-import-local.md) | واردکردن/پیکربندی یک پروژه دروپال موجود
[site:install](site-install.md) | نصب یک پروژه دروپال
[site:maintenance](site-maintenance.md) | تعویض حالت نگهداری موجود در سایت
[site:mode](site-mode.md) | تعویض پیکربندی عملکرد سیستم
[site:new](site-new.md) | دانلود یک پروژه جدید دروپال
[site:statistics](site-statistics.md) | نمایش آمار و ارقام موجود از وبسایت
[site:status](site-status.md) | مشاهده گزارش وضعیت فعلی دروپال
**state**  |
[state:delete](state-delete.md) | حذف State
[state:override](state-override.md) | بازنویسی یک کلید State
**taxonomy**  |
[taxonomy:term:delete](taxonomy-term-delete.md) | حذف عبارت‌های دسته‌بندی از یک واژگان
**test**  |
[test:run](test-run.md) | اجرای Unit Test های موجود در برنامه
**theme**  |
[theme:download](theme-download.md) | دانلود قالب در برنامه
[theme:install](theme-install.md) | نصب قالب یا قالب‌ها در برنامه
[theme:path](theme-path.md) | بازگرداندن مسیر نسبی یا مطلق یک قالب
[theme:uninstall](theme-uninstall.md) | حذف قالب یا قالب‌ها در برنامه
**translation**  |
[translation:cleanup](translation-cleanup.md) | commands.translation.cleanup.description
[translation:pending](translation-pending.md) | commands.translation.pending.description
[translation:stats](translation-stats.md) | commands.translation.stats.description
[translation:sync](translation-sync.md) | commands.translation.sync.description
**update**  |
[update:entities](update-entities.md) | اعمال بروزرسانی‌های Entity
[update:execute](update-execute.md) | اجرای یک تابع بروزرسانی بخصوص در یک افزونه یا تمام سایت
**user**  |
[user:create](user-create.md) | ایجاد کاربران برای برنامه
[user:delete](user-delete.md) | حذف کاربران برای برنامه
[user:login:clear:attempts](user-login-clear-attempts.md) | پاکسازی تلاش‌های ناموفق ورود برای یک حساب کاربری
[user:login:url](user-login-url.md) | بازگرداندن یک نشانی یکبار مصرف ورود کاربری
[user:password:hash](user-password-hash.md) | تولید هش از یک گذرواژه ساده
[user:password:reset](user-password-reset.md) | بازنشانی گذرواژه برای یک کاربر بخصوص
[user:role](user-role.md) | افزودن/حذف نقش‌های کاربری
**views**  |
[views:disable](views-disable.md) | غیرفعال کردن یک View
[views:enable](views-enable.md) | فعال کردن View

## گزینه‌های موجود
گزینه | توضیحات
-------|-------------
--help | نمایش این پیام راهنما
--quiet | حذف تمام خروجی‌های دستور
--verbose | افزایش درجه خروجی پیام‌ها: ۱ برای خروجی عادی، ۲ برای خروجی بیشتر و ۳ برای دیباگ
--version | نمایش نسخه فعلی از برنامه
--ansi | تحمیل خروجی ANSI
--no-ansi | غیرفعال کردن خروجی ANSI
--no-interaction | هیچ پرسش تعاملی پرسیده نشود
--env | نام محیط
--root | مسیر پروژه دروپال که برای اجرای دستورات لازم است
--debug | application.options.debug
--learning | تولید یک خروجی کد آموزشی
--generate-chain | نمایش گزینه‌ها و آرگومان‌های دستور به عنوان خروجی YAML که می‌تواند در دستور زنجیره‌ای قرار بگیرد
--generate-inline | نمایش گزینه‌ها و آرگومان‌های دستور به عنوان خروجی inline
--generate-doc | نمایش گزینه‌ها و آرگومان‌های دستور به عنوان خروجی markdown
--target | نام سایتی که می‌خواهید با آن در تعامل باشید (محلی یا راه‌دور)
--uri | نشانی سایت دروپال مورد استفاده (در صورت استفاده از محیط چند-سایته یا درگاه‌های مختل)
--yes | حذف تاییدیه‌ها و ادامه مسیر

## آرگومان‌های موجود
آرگومان | توضیحات
---------|-------------
command | دستور قابل اجرا
