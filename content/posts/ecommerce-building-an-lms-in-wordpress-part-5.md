---
title: 'eCommerce &#8211; Building an LMS in WordPress &#8211; Part 5'
date: '2014-07-03T10:06:21-07:00'
status: publish
excerpt: ''
type: post
id: 665
thumbnail: ../uploads/2014/07/ecommerce.png
category:
    - 'Learning Management Systems (LMS)'
tag:
    - ecommerce
    - jigoshop
    - lms
    - WordPress
post_format: []
kopa_forceful_total_view:
    - '69'
forceful_lite_total_view:
    - '4'
authors:
    - Glenn_Preston
path: /ecommerce-building-an-lms-in-wordpress-part-5
---
This is the second to last post on Building an LMS in WordPress. We have looked at the various plugin options available and what I personally chose, so now we are going to look at the eCommerce component.

eCommerce built into your LMS site gives you the ability to sell your courses/content without having to go through too much pain and development. Luckily for all of us, WordPress developers have done most of the work for us.

There are a large number of eCommerce solutions/plugins available but again, there were some important features or requirements I was looking for. There were:

- The purchaser should not have to leave my site to buy
- The eCommerce plugin needed to integrate with my LMS
- Minimal administrative activities in the back end for me

I chose the go with Jigoshop, a large ecommerce developer from the UK. It integrates with LearnDash, my LMS plugin and has a large number of Payment Gateways you can use. Along with the normal PayPal, I also selected to use Stripe. Strip is a full on credit card payment gateway, allows purchasers to stay on your site and because JigoShop integrates with my LMS, when you buy a course, you are automatically generated a Log In ID and password.

This means I have no back end administrative duties, a big plus for me.

I can also assign discounts for certain courses or groups of people, like a company who wishes to bulk purchase one of my courses.

**The Challenges**

Due to the fact I selected Stripe, and want my purchasers to stay on my site, I needed an SSL Certificate. This is the security piece that is very important to let your client know you are protecting their information. Certificates can range from $50 to $500 and I chose GeoTrust for mine.

There is a bit a fiddling to do to get the code required into the right place on your site, but your web host service can help you with this. Along with the SSL Certificate, you will need a static IP address. This is a minor monthly cost but necessary.

**Note:** There are some WordPress eCommerce Plugins that don’t require the SSL certificate or static IP address but you need to make sure they will work with your LMS. This is key to a seamless experience for the customer.

**So here are my costs:**

[![Jigoshop](../uploads/2014/06/Jigoshop.jpg)](http://netlearningspace.com/bksi_new/wp-content/uploads/2014/06/Jigoshop.jpg) $0 basic plugin, $80 for the Pro

[![GeoTrust](../uploads/2014/07/GeoTrust.jpg)](http://netlearningspace.com/bksi_new/wp-content/uploads/2014/07/GeoTrust.jpg) $149

Static IP Address $5.50 per month

HTTPS Plugin $0

**Conclusion**

Setting up the eCommerce portion of my site was the hardest for me, as I knew nothing about what I needed or required, so the help of my web host company was invaluable. You need to be clear on how you want the purchasing experience to be so you can decide what payment gateways you want. The more the merrier may not be the case, but if you plan to sell mainly in one country or another, or all of Europe vs North America, this could affect your payment gateway decision.

Finally, test, test, test! It is supremely important you test all aspects of the purchase process to make sure it works correctly before you launch. It was suggested I create a $2 product and have a few friends “buy” courses to see how it works. Only once all points in the process are tested, should you go live.

We have one final post next week, it will be on some other aspects of this process and plugins I found, that might be helpful.  
<script>
  (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
  (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
  m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
  })(window,document,'script','//www.google-analytics.com/analytics.js','ga');</script>

 ga('create', 'UA-52738692-1', 'auto'); ga('send', 'pageview');