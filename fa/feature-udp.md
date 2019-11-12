## پروتکل انتقال روی UDP

پروتکل QUIC یک پروتکل انتقال پیاده‌سازی شده بر روی UDP است. اگر گاهی ترافیک شبکه‌ی خود‌ را زیر نظر بگیرید، می‌بیند که QUIC به شکل بسته‌های UDP نمایان می‌شود.

بر اساس UDP، این پروتکل نیز از شماره پورت‌های UDP برای شناسایی سرویس‌های مشخصِ شبکه روی یک آدرس IP خاص استفاده می‌کند.

تمام پیاده‌سازی‌های شناخته شده‌ی QUIC در حال حاضر در فضای کاربری هستند چرا که این امر منجر به بالا رفتن سرعت توسعه نسبت به آن چیزی خواهد بود که فضای هسته برای پیاده‌سازی‌ اجازه خواهد داد.

## آیا کارساز خواهد بود؟

شرکت‌ها و دیگر نهادهای شبکه‌ای وجود دارند که ترافیک UDP روی پورت‌های غیر از ۵۳ (که برای DNS استفاده می‌شود) را مسدود می‌کنند. دیگری‌ها نیز داده‌ها را به گونه‌ای محدود می‌کنند که باعث می‌شود QUIC از پروتکل‌های مبتنی بر TCP هم بدتر عمل کند. پایانی برای کارهای برخی از اپراتورها نیست.

تا آن‌جایی که می‌توان آینده را پیش‌بینی کرد، شاید تمام استفاده‌های انتقال‌های مبتنی بر QUIC باید بتوانند به طور خوشایند به دیگر جایگزین‌ها (مبتنی بر TCP) بازگردند. مهندس‌های گوگل پیشتر نرخِ شکست در درصدهای تک‌رقمیِ پایین را پیش‌بینی کرده‌اند.

## آیا پیشرفت خواهد کرد؟

 اگر ثابت شود  QUIC چیزی با ارزش به دنیای اینترنت اضافه می‌کند، آن‌وقت احتمال دارد افراد بخواهند از آن استفاده کنند و در نتیجه بخواهند تا آن در شبکه‌هایشان کار کند و بدین ترتیب ممکن است شرکت‌ها شروع به بازنگری و بررسی موانع موجودِ خود کنند. در طول سال‌هایی که توسعه‌ی QUIC پیشرفت کرده، نرخ موفقیت برای ایجاد و استفاده‌ی اتصال‌های QUIC در اینترنت افزایش یافته است.