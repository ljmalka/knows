---
title: "Facebook Ads"
slug: "facebook-ads"
excerpt: "Discover how to seamlessly integrate AnyTrack with the Facebook Conversion API to effectively measure, optimize, and report your Facebook Ads performance, boosting your ROAS."
hidden: false
metadata: 
  description: "Discover how to seamlessly integrate AnyTrack with the Facebook Conversion API to effectively measure, optimize, and report your Facebook Ads performance, boosting your ROAS (Return on Advertising Spend)"
createdAt: "2023-04-07T22:17:01.970Z"
updatedAt: "2023-08-08T06:33:44.200Z"
---
> 🚧 Prerequisites
> 
> 1. You must have a Facebook Business Manager with Admin permissions
> 2. You must have an AnyTrack account with a paid subscription (Basic or higher)
> 3. **Prevent duplication:** Once you've connected your Facebook Pixel & Ad Account you should remove all other Facebook Integrations from your platform (ex: Shopify, Google Tag Manager, Wordpress, Woocommerce etc...)

### Facebook Ads integration features

The AnyTrack & Facebook integration is packed with features that are meant to simplify and streamline your workflow and data collection. In most cases implementation is code free, and fully automated.

1. **Real-time Tracking:** Integrating AnyTrack and Facebook's API ensures up-to-the-minute monitoring of your campaign's performance.

2. **Data Privacy:** This integration complies with privacy regulations.

3. **Measurement Accuracy:** AnyTrack and Facebook's API together bypass browser limitations that affect data accuracy, giving you a true picture of your return on ad spend (ROAS).

4. **Event Data Attributes:** Send detailed conversion data attributes such as matching parameters and product attributes.

5. **Offline Conversions:** You can report and monitor conversions happening out of reach of the standard Facebook Pixel.

6. **Cross-channel Attribution:** AnyTrack lets you attribute conversions across multiple customer touchpoints, allowing for complex, multi-touch attribution models.

7. **Ad Spend Optimization:** Accurate, real-time tracking aids in improving campaign effectiveness and reducing ad spend wastage.

8. **Custom Audience Creation:** Detailed user behavior tracking enables the development of highly targeted custom audiences, boosting the efficiency of your ad campaigns.

9. **Tag Management:** Anytrack loads your facebook pixel and AutoTrack web event as well as server side events automatically.

10. **Automatic Deduplication:** Anytrack deduplicates conversions before it sends them to your Facebook Pixel guaranteeing clean and accurate data and preventing warnings.

11. **Automatic Conversion Mapping:** Leverage Facebook standard events automatically regardless where you conversions are triggered from. Whether eCommerce, Lead generation or Affiliate marketing, AnyTrack sends accurate and granular conversion data to Facebook.

12. **Unlimited Attribution window:** AnyTrack is not bound by any attribution window so you can measure short and long sales cycle.

13. **Campaign reports:** Access campaign reports with all metrics and campaign performances breakdowns.

14. **Real time Attribution:** Real time attribution reports on any of your conversion data.

### How AnyTrack works with Facebook Ads

1. **When visitors land on your website** the AnyTrack Tracking Tag does a few things:
   1. It loads the Facebook Pixel (if it isn't already found on the page)
   2. Collects traffic related data points - utm, referrer data, `clickid` values.
   3. Collects first party data such as Facebook Cookies, Google Analytics
   4. Sets AnyTrack first party data - cookies, session id and more.
   5. Scans the page and activate AutoTag on trackable elements such carts, product links, forms, checkout links.
2. **When visitor engages with your content**, Anytrack AutoTracks events such as `AddToCart`, `OutboundClick`, `FormSubmit`.
   1. On specific events and connected integrations (i.e. Shopify, ClickFunnels, Woocommerce), AnyTrack AutoTags forms, links and carts with tracking parameters (e.g. `click_id`).
3. **Events** are tracked through the AnyTrack Tracking Tag or the Server-Side API (Webhooks, Postback URL, or API) and in some cases the same event is tracked with both methods.
   1. Events are processed in real time before being sent to Facebook Conversion API:
      1. **Event processing:** Deduplication, normalization, hashing according to Facebook Requirements.
      2. **Event Mapping:** Tracked Events are Mapped to Facebook Standard Events.
      3. **Event Attributes:** The payload of the conversion event received from your integrations is then mapped (read: Translated) to what Facebook expects.
4. **Real time tracking data**  is reported across the AnyTrack dashboard.
   1. The Event Data stream is also available in the Conversion Event Logs.
   2. The raw conversion data from your Conversion Sources is available through the Integration Logs.
5. **The Campaign Reports** is then built with several datasets collected from the various data sources:
   1. **The Facebook Insights API** from where we fetch your campaign metrics, performances, budgets, spent and attributed revenues and conversions.
   2. **The AnyTrack Tracking Tag** which collects the traffic and session data.
   3. **The AnyTrack Server-Side Tracking Server** which receives real time conversion data from your Conversion sources (ex: Shopify, Woocommerce).
   4. **The AnyTrack Attribution Server**, which constantly processes all data streams to provide calculated metrics such as conversion rates.

> 👍 Server Events ONLY
> 
> AnyTrack sends **exclusively Server Side Events to Facebook**. So when you inspect your data in the Facebook Event Manager you should not see any events originating from the Browser.
> 
> **Note**: The `PageView` event is the only event being sent through the Browser and not through the Server API.

### How to set up Facebook Ads in AnyTrack

[block:html]
{
  "html": "<iframe width=\"700px\" height=\"400px\" src=\"https://embed.app.guidde.com/playbooks/f6EomHfVarMdoapyix39a9\" title=\"Tracking Pixels - Facebook Ads\" frameborder=\"0\" allowfullscreen allow=\"clipboard-write\" ></iframe>"
}
[/block]

### Facebook Integration Validation Checklist

> 🚧 Event manager
> 
> Before being alarmed to see or not see some data please keep in mind the following cardinal rules:
> 
> AnyTrack sends conversions in real time to the facebook api, but conversion are being displayed in Facebook with the following delays:
> 
> - **Event Manager**: Approximately 10-20 minutes delay.
> - **Ads Manager:** officially up to 72 hours, but it's usually within hours.
> 
> **Warnings**: It's normal to get some warnings when you implement a new integration. In fact, it's healthy as it will indicate that the data started sending is different from the data you've previously sent.

### Facebook Integration Checklist

- [ ] Check that you've connected the correct pixel id.
- [ ] Check that you've connected your ad account.
- [ ] Check that you've enabled the Facebook Conversion API.
- [ ] If you've updated the Event Mapping, verify that the events are being recorded in the Event Manager.
- [ ] You've added the UTM Tracking template to all your Ads.
- [ ] Check that you've selected the correct pixel and optimization Event in your campaigns
- [ ] Check the Facebook Event Manager to make sure you don't see any Browser Events.

## FAQ and Troubleshooting

- ### Do I need to add the Facebook Token in AnyTrack?
  No. AnyTrack app automatically generates the Facebook Token when you connect your AnyTrack account with Facebook.
- ### How do I verify that my Conversion API is connected?
  1. Open the event manager to see where the events are coming from.
  2. You can see the AnyTrack app integration in your [Business Manager Integration](https://www.facebook.com/settings/?tab=business_tools) Page.

[block:image]
{
  "images": [
    {
      "image": [
        "https://files.readme.io/aa817b9-Screen_Shot_2023-05-24_at_7.06.57_PM.png",
        null,
        ""
      ],
      "align": "center",
      "border": true
    }
  ]
}
[/block]

- ### How do I inspect conversions sent to Facebook Conversion API?
  1. Go to the Facebook Event manager select the Event, then click on the Event Details. You can then open each section and inspect the data sent via Anytrack. 

[block:image]
{
  "images": [
    {
      "image": [
        "https://files.readme.io/1fd39a5-Screen_Cast_2023-05-24_at_7.00.13_PM.gif",
        null,
        ""
      ],
      "align": "center",
      "border": true
    }
  ]
}
[/block]

- ### What is Facebook Ads integration in AnyTrack?
  Facebook Ads integration in AnyTrack is a feature that allows you to track and attribute conversions from your Facebook Ads. It automatically syncs your conversions with your Facebook Ads account, enabling you to optimize your ads based on accurate and real-time data.

- ### How do I set up Facebook Ads integration in AnyTrack?
  Setting up Facebook Ads integration in AnyTrack involves a few steps. First, you need to connect your Facebook Ads account to AnyTrack. Then, you need to set up the event mapping to define how your conversions are tracked and attributed. Finally, you need to add the AnyTrack TAG to your website.

- ### What is event mapping in AnyTrack?
  Event mapping in AnyTrack is a feature that allows you to define how your conversions are tracked and attributed. You can map your conversion events to standard Facebook events or create custom events based on your specific needs.

- ### What is the AnyTrack TAG?
  The AnyTrack TAG is a piece of code that you add to your website. It enables AnyTrack to track conversions and attribute them to your ads. The AnyTrack TAG works with any website and is compatible with all major ad platforms, including Facebook Ads.

- ### How do I add the AnyTrack TAG to my website?
  You can add the AnyTrack TAG to your website by copying the TAG from your AnyTrack dashboard and pasting it into the head section of your website's HTML code. If you're using a website builder or CMS, you can usually add the TAG through the platform's settings or by using a plugin.

- ### What are the benefits of using AnyTrack with Facebook Ads?
  Using AnyTrack with Facebook Ads allows you to accurately track and attribute conversions from your ads. It provides you with real-time data, enabling you to optimize your ads based on actual performance. Additionally, it automates the tracking process, saving you time and reducing the risk of errors.

- ### Can I use AnyTrack with other ad platforms?
  Yes, AnyTrack is compatible with all major ad platforms, including Google Ads, Bing Ads, and more. You can track and attribute conversions from all your ad platforms in one place, making it easier to manage and optimize your ad campaigns.

- ### Do I need to have coding skills to use AnyTrack?
  No, you don't need to have coding skills to use AnyTrack. The platform is designed to be user-friendly and easy to set up. If you can copy and paste, you can set up AnyTrack.

- ### Can I use AnyTrack if I'm using a website builder or CMS?
  Yes, AnyTrack works with any website, whether it's built from scratch or using a website builder or CMS like WordPress, [Shopify](doc:shopify), or [ClickFunnels](doc:clickfunnels). You can add the AnyTrack TAG to your website through the platform's settings or by using a plugin.
