<!-- Generated from one source together with
     lib/features/privacy/domain/privacy_policy_text.dart (M8).
     Change both in the same commit; the app shows the same text. -->

# Pinwake Privacy Policy

_Effective: 9 November 2026 · applies to Pinwake 0.8.3 and later_

[Українська версія нижче](#політика-приватності-pinwake)

## 1. In short

Pinwake is a location alarm and reminder for Android, made by one developer, Artem Panin (contact: pinwake.dev@gmail.com).

- All your data is stored only on your phone.
- Your coordinates are not sent to Pinwake servers — Pinwake has no servers.
- No analytics, no advertising, no trackers, no crash-reporting services.
- No collection of personal data, no accounts, no cloud sync.
- Your data is never sold and never shared for advertising or any other purpose.

## 2. What is stored on your phone

- Your places and reminders: name, point on the map, radius, type, icon, optional note, on/off state, times created / started / fired and the last "inside / outside the zone" state.
- The last distance to active places (for the home-screen widget; overwritten, not a history).
- App settings (theme, language, start screen, signal, tracking accuracy, GPS warnings, update check).
- Wi-Fi fingerprints of places (can be switched off in Settings → Location): only salted hashes of nearby access-point addresses — never network names, passwords or your position; at most 40 per place; deleted with the place or when the switch is turned off. Used only to recognise a place when GPS is jammed or spoofed.
- A diagnostic log, only if you turn it on (Settings → Support → For testers; off by default): technical decisions of the background service, place codes (p1, p2) and distances, with date and time — no coordinates, no place names, no Wi-Fi identifiers; at most about 5 MB.

Everything is kept in the app's private storage; other apps cannot read it. Pinwake keeps no movement history.

## 3. How location is used

Location (precise or approximate, as you allow, "while using the app") is used to show you on the map, to calculate distances and — only while a place is active — to watch for entering or leaving its zone through a visible foreground service with a permanent notification. Pinwake does not ask for "Allow all the time" location. While a place is active, Android's approximate network position is also used to check that GPS is not jammed or spoofed; it is used at once and not stored.

On phones with Google Play services, positions come from the system Fused Location Provider, which is governed by your phone's Google location settings. Pinwake itself sends no positions anywhere.

## 4. What leaves the phone

Pinwake works offline except for these requests, made directly from your phone:

- Map tiles from the OpenStreetMap Foundation tile server: your IP address, the part of the map being shown and an app identifier. Not your GPS position or your places.
- Search by name (only when you search, or share a text without coordinates): the text and, to show nearby results first, an area of about 100 km around your position rounded to about 10 km go to OpenStreetMap Nominatim.
- Short Google Maps links that you share into Pinwake are opened once, without cookies, to read the coordinates.
- Update check (versions from GitHub; can be turned off in Settings → Support): at most once a day a request for the latest release is sent to GitHub — with your IP address and the app name, nothing about you or your places. Versions from Google Play are updated by the store and make no such request.

These services have their own privacy policies (OpenStreetMap Foundation, GitHub, Google). Pinwake does not send them anything else.

## 5. Support and diagnostics

Settings → Support → "Report a problem" prepares an e-mail to pinwake.dev@gmail.com in your own e-mail app with a diagnostics package (diagnostics.zip): app version and build, Android version, phone model, the state of monitoring, GPS and the background service, and the diagnostic log if it is on. The package does not contain coordinates, saved places, movement history or notes. Pinwake never sends it by itself: you check the e-mail and press Send. "Send diagnostics" shares the same package with an app you choose.

E-mails you send are used only to answer you and to fix the problem, are not shared with anyone, and are deleted when no longer needed, at the latest 12 months after the last message.

## 6. Permissions

- Location — the location alarm.
- Notifications — alarms and reminders.
- Foreground service (location) — reliable monitoring while a place is active.
- Full-screen alarm, vibration — showing the alarm over the lock screen.
- Start after reboot — offering to resume active places.
- Wi-Fi state — Wi-Fi fingerprints of places (hashes only).
- Music and audio (on Android 12 and older: storage) — only to show the file name of a sound you picked from a file manager; asked only then. Pinwake does not list, copy or send your files.
- Internet — map, search by name, update check.

## 7. Backups

Pinwake has no cloud of its own. If Android backup is turned on on your phone, Android may include the app's data in the backup of your Google account, under Google's terms; Pinwake cannot read that backup. You can turn backup off in your phone's settings.

Settings → Support → "Save a backup" writes your settings and saved places — with their points on the map and notes — to a file in the place you choose (for example Downloads or a cloud folder of your choice). Pinwake makes it only when you ask and does not send it anywhere by itself; anyone who has the file can see your places, so keep it safe. "Restore from a backup" reads such a file back.

## 8. Children

Pinwake is not directed at children under 13 and collects no personal data from anyone.

## 9. Your choices

You can delete any place in the app, turn off the Wi-Fi fingerprints, the diagnostic log and the update check, and change or revoke permissions in Android settings at any time. "Clear storage" in Android settings or uninstalling the app deletes all of Pinwake's data from the phone.

## 10. Changes

If this policy changes, the new version with a new date is shown in the app (Settings → Privacy → Privacy policy) and published at the same address.

## 11. Contact

Artem Panin, developer of Pinwake — pinwake.dev@gmail.com

---

# Політика приватності Pinwake

_Чинна з 9 листопада 2026 року · для Pinwake 0.8.3 і новіших_

[English version above](#pinwake-privacy-policy)

## 1. Коротко

Pinwake — будильник і нагадування за місцем для Android, створений одним розробником, Артемом Паніним (зв'язок: pinwake.dev@gmail.com).

- Усі ваші дані зберігаються лише на вашому телефоні.
- Координати не передаються на сервери Pinwake — у Pinwake немає серверів.
- Немає аналітики, реклами, трекерів і сервісів звітів про збої.
- Не збираються персональні дані, немає акаунтів і хмарної синхронізації.
- Ваші дані ніколи не продаються і не передаються ні для реклами, ні для чогось іншого.

## 2. Що зберігається на телефоні

- Ваші точки й нагадування: назва, точка на карті, радіус, тип, іконка, необов'язкова нотатка, увімкнено/вимкнено, час створення / запуску / спрацювання і останній стан «у зоні / поза зоною».
- Остання відстань до активних точок (для віджета; перезаписується, це не історія).
- Налаштування (тема, мова, стартовий екран, сигнал, точність відстеження, попередження GPS, перевірка оновлень).
- Wi-Fi відбитки місць (вимикаються в Налаштування → Місцеположення): лише солені хеші адрес точок доступу поруч — ніколи назви мереж, паролі чи ваше місцеположення; до 40 на точку; видаляються разом із точкою або вимкненням перемикача. Потрібні лише, щоб упізнати місце, коли GPS глушать або підміняють.
- Журнал діагностики, лише якщо ви його увімкнете (Налаштування → Підтримка → Для тестувальників; за замовчуванням вимкнений): технічні рішення фонового сервісу, коди точок (p1, p2) і відстані з датою й часом — без координат, назв точок і ідентифікаторів Wi-Fi; до ~5 МБ.

Усе зберігається в приватному сховищі застосунку; інші застосунки не можуть це прочитати. Історія переміщень не ведеться.

## 3. Як використовується місцеположення

Місцеположення (точне або приблизне — як ви дозволите, «під час використання») потрібне, щоб показати вас на карті, рахувати відстані і — лише поки точка активна — стежити за входом у зону чи виходом із неї через видимий фоновий сервіс із постійним сповіщенням. Pinwake не просить дозволу «Дозволити завжди». Поки точка активна, також використовується приблизне мережеве місцеположення Android, щоб перевірити, що GPS не глушать і не підміняють; воно використовується одразу і не зберігається.

На телефонах із сервісами Google Play місцеположення надає системний Fused Location Provider, який працює за налаштуваннями геолокації Google на вашому телефоні. Сам Pinwake нікуди не надсилає місцеположення.

## 4. Що залишає телефон

Pinwake працює без інтернету, крім таких запитів безпосередньо з телефона:

- Фрагменти карти з сервера OpenStreetMap Foundation: ваша IP-адреса, ділянка карти, яку показано, і ідентифікатор застосунку. Не ваше GPS-місцеположення і не ваші точки.
- Пошук за назвою (лише коли ви шукаєте або ділитеся текстом без координат): текст і, щоб спершу показати найближче, район ~100 км навколо вашого місцеположення, округленого приблизно до 10 км, ідуть до OpenStreetMap Nominatim.
- Короткі посилання Google Maps, якими ви ділитеся з Pinwake, відкриваються один раз без cookies, щоб прочитати координати.
- Перевірка оновлень (версії з GitHub; вимикається в Налаштування → Підтримка): не частіше ніж раз на добу GitHub отримує запит про останній реліз — з вашою IP-адресою і назвою застосунку, нічого про вас чи ваші точки. Версії з Google Play оновлює магазин, такого запиту вони не роблять.

Ці сервіси мають власні політики приватності (OpenStreetMap Foundation, GitHub, Google). Нічого іншого Pinwake їм не надсилає.

## 5. Підтримка і діагностика

Налаштування → Підтримка → «Повідомити про проблему» готує лист на pinwake.dev@gmail.com у вашому поштовому застосунку з пакетом діагностики (diagnostics.zip): версія і збірка застосунку, версія Android, модель телефона, стан моніторингу, GPS і фонового сервісу та журнал діагностики, якщо він увімкнений. Пакет не містить координат, збережених точок, історії переміщень і нотаток. Pinwake ніколи не надсилає його сам: ви перевіряєте лист і натискаєте «Надіслати». «Надіслати діагностику» передає той самий пакет вибраному вами застосунку.

Надіслані вами листи використовуються лише для відповіді й виправлення проблеми, нікому не передаються і видаляються, коли більше не потрібні, — не пізніше ніж через 12 місяців після останнього листа.

## 6. Дозволи

- Місцеположення — робота геобудильника.
- Сповіщення — будильники та нагадування.
- Фоновий сервіс (місцеположення) — надійний моніторинг, поки точка активна.
- Будильник на весь екран, вібрація — сигнал поверх екрана блокування.
- Запуск після перезавантаження — пропозиція відновити активні точки.
- Стан Wi-Fi — Wi-Fi відбитки місць (лише хеші).
- Музика та аудіо (на Android 12 і старіших — сховище) — лише щоб показати назву файлу мелодії, яку ви вибрали через менеджер файлів; запитується тільки тоді. Pinwake не переглядає, не копіює і нікуди не надсилає ваші файли.
- Інтернет — карта, пошук за назвою, перевірка оновлень.

## 7. Резервні копії

У Pinwake немає власної хмари. Якщо на телефоні увімкнене резервне копіювання Android, Android може включити дані застосунку в резервну копію вашого акаунта Google на умовах Google; Pinwake не може прочитати цю копію. Резервне копіювання можна вимкнути в налаштуваннях телефона.

Налаштування → Підтримка → «Зберегти резервну копію» записує ваші налаштування і збережені точки — з їхніми місцями на карті й нотатками — у файл у вибраному вами місці (наприклад, «Завантаження» або хмарна папка на ваш вибір). Pinwake створює його лише на ваш запит і сам нікуди не надсилає; хто має файл, бачить ваші точки, тож зберігайте його надійно. «Відновити з резервної копії» читає такий файл назад.

## 8. Діти

Pinwake не призначений для дітей до 13 років і ні в кого не збирає персональних даних.

## 9. Ваш вибір

Ви можете будь-коли видалити будь-яку точку, вимкнути Wi-Fi відбитки, журнал діагностики і перевірку оновлень, змінити чи відкликати дозволи в налаштуваннях Android. «Очистити сховище» в налаштуваннях Android або видалення застосунку стирає всі дані Pinwake з телефона.

## 10. Зміни

Якщо політика зміниться, нова версія з новою датою з'явиться в застосунку (Налаштування → Приватність → Політика приватності) і за тією самою адресою.

## 11. Контакти

Артем Панін, розробник Pinwake — pinwake.dev@gmail.com
