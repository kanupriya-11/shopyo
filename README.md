

<h1 align="center">
  <br>
  <a href="https://github.com/Abdur-rahmaanJ"><img src="https://github.com/Abdur-rahmaanJ/shopyo/blob/master/screenshots/shoyo_social.png" alt="shopyo" width="" height=""></a>
</h1>


Featured on [Weekly Python issue 436](https://newsletry.com/Home/Python%20Weekly/9a578693-14ba-47c5-8a8e-08d7b0139fe7) 🌟

🎁 Open inventory management  and Point of sales (powered by python) for small shops. Slowly becoming the hybrid between a CMS and an ERP

- ⚡ Spin websites quickly
- 🔥 Plug and Play modules (Just copy paste folder)
- 🖍️ Themes!
- 📒 Administrative management
- ⚽ Public-facing (landing page, contact page, etc) management
- 🍓 Intuitive: is also a great Flask base and supports Django commands commands such as:

`python manage.py startapp loans` 

## 💬 Community: Discord¶

Join the [Shopyo Discord](https://discord.gg/k37Ef6w/)


# 🍜 Test it out!

| Info | Value |
|---|---|
| Link | [shopyo.pythonanywhere.com](http://shopyo.pythonanywhere.com/) |
| Credentials | User: testuser - password: pass |

**By code**

[Important] Create a virtual environment and activate it (not needed when installing [via github](https://abdur-rahmaanj.github.io/shopyo/setup.html#install-from-github)).

`pip install shopyo`

then

`shopyo new /home/profiles/arj/desktop shopyotest`

then cd into the folder

`cd /home/profiles/arj/desktop/shopyotest`

then install requirements

`pip install -r requirements.txt`

then

```
python manage.py initialise  # or `shopyo initialise`
python manage.py runserver  # or `shopyo runserver` or rundebug
```

go to url ^^

_Note: If the command does not get recognised, close and reopen your cmd_

```
default login
  mail: admin@domain.com
  password: pass
```

# 📚 Docs

👉 [Link](https://abdur-rahmaanj.github.io/shopyo/)

* Setting up Shopyo
* Education section
* Contributing to Shopyo
* Modules/Apps
* Templates
* Models
* Views
* Commandline
* Shopyoapi
* Docs
* Unittests

# ⚗️ Stability

**beta** - now in beta!


# 💌 Contributing Countries

🇲🇺 🇩🇪 🇨🇳 🇬🇧 🇸🇬 🇺🇬 🇲🇽

# 🔥 Default Modules:

Basics:

- Control Panel
- Admin
- Base
- Login
- Settings
- Theme

Shop:

- Appointment
- Products
- People
- Internals
- Page
- Contact

More:
 - www

If you want to use the project as a Flask base, just remove 
the shop modules in modules/

# ⚙️ The engine

Shopyo's engine which provides a Django-like structure and awesome mechanisms has been abstracted into [hadbox](https://www.github.com/hadbox/hadbox)





# 📜 Testimonial

 >  This is my first time contributing to a public repo and I have quite enjoyed it. If you're a ``first-time-contributor`` the community is very helpful and can help you progress. Since I have been helping in this repo, I have also learnt a few things myself. The owner of the repo is active and is always willing to help.
>
> Also, if I'm around and you're stuck give us a shout. I'll help if I can. ``@blips5``



# 📖 History


See [this](https://www.linkedin.com/feed/update/urn:li:activity:6551367967978979328) linked-in article!

# 📰 In The News

- Shopyo is [announced on LinkedIn](https://www.linkedin.com/feed/update/urn:li:activity:6551367967978979328)
- Featured on Python Weekly issue 436
- [Bhavesh Solanki](https://www.linkedin.com/in/bhavesh-solanki26/) tells about his Open Source experience [contributing to Shopyo](https://www.linkedin.com/feed/update/urn:li:activity:6569959051420098560/) on LinkedIn
- [Arthur Nangai](https://www.linkedin.com/in/arthur-nangai/) from Andela joins the project as 3rd core committer
- Project goes officially in Beta, v1.0.0 released
- Duckduckgo recognises Shopyo
![](screenshots/shopyo_duckduckgo.png)
- Shopyo becomes a trending OpenSource project
![](screenshots/shopyo_trending.png)



# Who uses Shopyo?

| site name | description
|:---:|:---:|
|Maurilearn.com|Elearning platform|

# TODO modules

- Point of Sales
- Accounting
- Contact [done]
- Pages [in progress]


# 📞 Contact

Support team if you are stuck

- [Abdur-Rahmaan Janhangeer](https://github.com/Abdur-rahmaanJ) - arj.python@gmail.com
- [Nathan](https://github.com/blips5) - 
- [Arthur Nangai](https://github.com/arthurarty) - arthurnangaiarty@yahoo.co.uk 


# Roadmap

- ✔️ Models
- ✔️ Migrations
- ✔️ Restful Api
- ✔️ Manage.py
- ✔️ CSRF protection
- ✔️ Easy dev/production mode switch
- ✔️ Login
- ✔️ Api namespacing / apps
- ✔️ Django-like structure (where models, views and templates all in one  folder)
- ✔️ Relative reference (.forms for example)
- ✔️ Roles management
- ✔️ Themes

In Progress

- 🔃 Unit tests
- 🔃 Integration tests
- 🔃 Permission levels

## 🍳 In Action

![](screenshots/theme_boogle.png)
![](screenshots/theme_mistrello.png)
![](screenshots/module_v2.png)

## Supporters

[![Stargazers repo roster for @abdur-rahmaanj/shopyo](https://reporoster.com/stars/abdur-rahmaanj/shopyo)](https://github.com/abdur-rahmaanj/shopyo/stargazers)

[![Forkers repo roster for @abdur-rahmaanj/shopyo](https://reporoster.com/forks/abdur-rahmaanj/shopyo)](https://github.com/abdur-rahmaanj/shopyo/network/members)


