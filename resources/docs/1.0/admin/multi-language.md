# Multiple Languages

Eventmie supports multiple languages, including Russian, Portuguese, Chinese, Japanese and even RTL languages such as Arabic, Persian, Urdu, etc. 

---

![Multi-language](https://eventmie-docs.classiebit.com/images/multi-langauge-1.jpg "Multi-language")

---

> {success} Eventmie `Auto-detects` **RTL** language and changes the website direction to **RTL**

---

- [Add New Language](#Add-New-Language)


<a name="Add-Language"></a>
## Add Language

When you run Eventmie install command, it publishes all the languages to your application `resources/lang/vendor/eventmie` directory. So that if you wanna change something in existing language, you can do so. 

And, to add a new language, simply copy the `en` directory and paste it as `<your_language_name_shortcode>`. Then translate all the file `em.php` inside the new language folder.

---

>{warning} Translate variable **VALUES** only and not **VARIABLE NAMES**

---

e.g Suppose you wanna add `mandarin` language. Simply copy the `en` folder and paste it as `zh`.

```bash

    resources
        │
        ├── lang
            ├── vendor
                ├── eventmie
                    ├── en
                    └── zh

```

---

>{success} Once you add a new language, the new language will be added to the language list automatically.