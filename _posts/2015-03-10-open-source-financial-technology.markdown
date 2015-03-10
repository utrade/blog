---
layout: post
title:  "Open Source Products in Financial Technology"
date:   2015-03-10
categories:
---

Open Source software has taken the world by storm over the last two decades or so. If you look under the hood of any of the big software applications, you will see a number of open source libraries being used in the product. For example, if we look at the number of libraries being used in the [Adobe Reader XI](http://www.adobe.com/products/eula/third_party/acrobat/11/Acrobat_Reader_XI_3rd_Party_Read_Me_ver_1.pdf), the list of third party license/notices run into 61 pages, with a variety of open source software being used ranging from graphics libraries to compression and even some libraries from marquee projects like Open Office, Mozilla and the Android projects.

However, we do not see many domain specific application softwares in the open source world. Things are slowly moving into this direction, but there is a lot of progress to be made. And, this may be the next big thing in the open source world, where one would see new companies release mainstream application products which are open source, with an "Open Core" business model and giving the Traditional vendor companies a run for their money with their quality, feature set and rapid innovation.

## Benefits of Open Source Software

It is now widely know the immense benefits of open source products:

- Quality - Open Source leads to more high quality-products or libraries. I would mention the example of Boost libraries for C++, which is a very high quality peer-reviewed cross-platform C++ libraries.

  Also, making a product open source leads to more set of eyes looking at the code, thus enabling more peer review of code and probably, leading to faster fixing of defects as well.

- Innovation - When you have open source products, there is a likelihood that more people would be using your product in the way you would never have imagined. This leads to feature requests and often redesign of the applications, making them better in general.

- No Vendor lock-in - Since you have the source code, there is no need to be locked into a particular vendor when looking for upgrades and maintenance of the product. An open source ecosystem leads to more service providers, who would work be more than willing to enhance and maintain upgrades or fulfulling special requirements of the client.

- Transparency - Software cannot get more transparent than this. With an open source product with significant community,

- Security - Obscurity does not help when it comes to information security in software products. Open Source software leads to a healthier and more secure products.

- Stand on the shoulder of giants - Lots of great open source software has been possible because of the large number of open source projects which done been done before. A lot of "big data" applications and frameworks may not had been possible without Hadoop.

## OSS being used in Financial Firms

If you look at technology stacks in any of the large institutions (particularly, financial institutions, as we are in the financial technology space), one would see a large number of open source products being used everywhere.

### Compilers

GCC and Clang have been leading the way in terms of feature support for C/C++ compilers and they have been way ahead of the commercial competitors, in terms of the new C++11 standard support.

### Application servers

Tomcat is more or less the standard application container for most Java applications. In the J2EE space, JBoss is as prevalent as WebSphere.

### Databases

MySQL and PostgreSQL have led the way for most open source databases. And, in today's you will not find many applications which do not support one of these two leading open source databases.

### Web Browsers

Firefox and Chromium have been the first browsers with support for most of the upcoming standards, be it features in the latest HTML5 standard or CSS standards. Microsoft Internet Explorer has been more of a laggard in this space. Also, commercial browser vendor [Opera](http://www.operasoftware.com/press/releases/general/opera-gears-up-at-300-million-users) has ditched their own browser rendering engine Presto in favour of Webkit ([Blink](http://www.chromium.org/blink), actually).

## Open Source Products in Financial Technology

Financial Institutions have been using open source projects throughout their technology stack. Full-suite application software is probably the last mile, where the financial institutions and the industry, in general, can adopt open source produts and bring the associated benefits for everyone in the ecosystem.

Increasingly, there have been products in Financial Technology, which are open source and are being widely adopted. QuickFIX is unarguably the most widely used FIX engine, which is probably being used in all the financial firms (big or small). And, [OpenGamma](http://www.opengamma.org) has coming up really well as an open-source Risk and Margining system, which is increasingly being deployed across various financial firms.

Another notable mention is [FinTP](http://www.fintp.org) product by [Allevo](http://www.allevo.ro), which is a very well respected product in the payments and financial transaction processing industry. Allevo has release the core engine of their product FinTP under GPLv3 license and the source code is available on [github](http://github.com/FinTP).

In the capital markets space, there have been products like Marketcetera, Tradelink, Lodestone (Deutsche Bank initiative), which have tried to fill that gap with varying success. We, at uTrade Solutions, believe there is an enormous scope here to create a truly world class open source product in capital markets space. uTrade had participated in the [Fintech Innovation Labs](http://www.fintechinnovationlablondon.co.uk/participants/participants.aspx) program last year and [presented](http://www.youtube.com/watch?v=3DhaqHkALbg) why Open Source in Capital Markets would work.

We would like to announce that we are opening up the core of our multi-asset trading platform and various other components/modules, which we have created over the past 3+ years. We would offer all this codebase to the community for criticism, adoption, contributions and collaborative development, which we think, will enable us to improve this product with the help of the vast open source community. All this code will be offered under a very liberal [Apache License](http://www.apache.org/licenses/LICENSE-2.0). We'll be releasing this product on our [github](http://github.com/utrade) page in the next 2-3 months. Watch out !!!
