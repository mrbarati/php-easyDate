

### Timezone
```php
(new easyDate())->setTimezone('Asia/Tehran'); // set timezone
(new easyDate())->setTimezone('Asia/Tehran',true); // set timezone globally
(new easyDate())->getTimezone(); // get current timezone. output sample: Asia/Tehran
```

### Calendar system
```php
(new easyDate())->setCalendar('jalali'); // set calendar system
(new easyDate())->setCalendar('jalali',true); // set calendar globally
(new easyDate())->getCalendar(); // get current calendar system. output sample: Jalali

(new easyDate())->addCalendar('jalali',className); // for developing calendar. check developing section
```

### Languages
```php
(new easyDate())->setLang('fa'); // set language
(new easyDate())->setLang('fa',true); // set language globally
(new easyDate())->getLang(); // get current language. output sample: Fa

(new easyDate())->addLang('fa',$translates); // for developing laguages. check developing section
```

