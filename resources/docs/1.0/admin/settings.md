# Settings

Manage Eventmie global settings here.

---

![Admin Panel - Settings](https://eventmie-docs.classiebit.com/images/settings-1.jpg "Admin Panel - Settings")

---

- [Site](#Site)
- [SEO](#SEO)
- [Social](#Social)
- [Contact](#Contact)
- [Booking](#Booking)
- [Admin](#Admin)
- [Mail](#Mail)
- [Regional](#Regional)

<a name="Site"></a>
## Site

Setup website brand identity.


|Setting Name|Type|Description|
|:-|:-|
|Site Name|`alpha`|brand name|
|Site Slogan|`alpha`|Tagline|
|Site Logo|`image:jpg|jpeg|png`|Logo|
|Site Favicon|`image:jpg|jpeg|png`|Favicon/icon|



<a name="SEO"></a>
## SEO

Website SEO


|Setting Name|Type|Description|
|:-|:-|
|Meta Title|`alpha`|short title explaining your business|
|Meta Keywords|`alpha`|comma separated unique keywords that describe your website in-short|
|Meta Description|`alpha`|short description of your website|



<a name="Social"></a>
## Social

About your social-media existence.


|Setting Name|Type|Description|
|:-|:-|
|Facebook Page Username|`alpha`|Facebook page **username** only|
|Twitter Account Username|`alpha`|Twitter account **username** only|
|Instagram URL|`url`|Instagram profile **URL**|
|Linkedin URL|`url`|Linkedin profile/company **URL**|




<a name="Contact"></a>
## Contact

Contact details


|Setting Name|Type|Description|
|:-|:-|
|Address|`alpha`|office address|
|Phone|`numeric`|office phone number|
|Email|`email`|office email|




<a name="Booking"></a>
## Booking

Bookings & Events global settings.

|Setting Name|Type|Description|
|:-|:-|
|Maximum Ticket Quantity|`integer`|Max ticket quantity per booking|
|Hide Expired Events|`bool`|Show/Hide expired events on event listing page|


<a name="Admin"></a>
## Admin

Admin panel content settings


|Setting Name|Type|Description|
|:-|:-|
|Admin Background Image|`image:jpg,jpeg,png`|admin login page background image|
|Admin Title|`alpha`|admin login page title & header title|
|Admin Description|`alpha`|admin login page sub-title|
|Admin Loader|`image:jpg,jpeg,png`|admin login page sub-title|
|Admin Icon Image|`image:jpg,jpeg,png`|admin panel logo|



<a name="Mail"></a>
## Mail

Mail sending configurations


|Setting Name|Type|Description|
|:-|:-|
|Mail Driver|`string`|Mail driver name e.g smtp|
|Mail Host|`string`|Mail host e.g 127.0.0.1|
|Mail Port|`string`|Mail Port e.g 1025|
|Mail Username|`string`|Mail Username e.g testuser|
|Mail Password|`string`|Mail Password e.g testpwd|
|Mail Encryption|`list`|disable, SSL, TLS|
|Mail Sender Email|`email`|Sender email e.g eventmie@classiebit.com|
|Mail Sender Name|`string`|Sender Name e.g Eventmie|



<a name="Regional"></a>
## Regional

Region-specific configurations.


|Setting Name|Type|Description|
|:-|:-|
|Timezone|`list`|Choose your region specific timezone|

<br>

---

#### Setting Default Timezone affects Events Date & Time that are storing in the database, they're converted accordingly.

- Suppose the default timezone is `America/Los_Angeles` and a customer visiting the site from `India/Kolkata`, then the customer will see the date & time according to `India/Kolkata` timezone

>{info} i.e Auto Timezone Conversion from `Server-side` to `Client-side` & vice versa.

---

> {success} Eventmie detects visitor's timezone and does all the conversions behind the scenes.

---

> {warning} Please read the guidelines provided below each setting, and follow exactly mentioned, or else it may break down your site.

