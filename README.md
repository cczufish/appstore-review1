appstore-review1
================


2021年12月22日


* 
* 		2021年12月22日 上午5:47 发件人 Apple
    * 		Other App Store Review Guideline Issue
* 		Hello,
* 		
* 		The review of your app is taking longer than expected. Once we have completed our review, we will notify you via Resolution Center.
* 		
* 		If you would like to inquire about the status of this review, you may file a request via the Apple Developer Contact Us page.
* 		
* 		Best regards,
* 		
* 		App Store Review



这个等就可以了 


10月23号

Reasons

2.2: Apps that exhibit bugs will be rejected 
16.1: Apps that present excessively objectionable or crude content will be rejected 
----- 2.2 -----

We found that your app exhibited one or more bugs, when reviewed on iPad running iOS 8.0.2 and iPhone 5s running iOS 8.0.2, on both Wi-Fi and cellular networks, which is not in compliance with the App Store Review Guidelines.

During our review, we found the QQ log in option unresponsive when tapped. Please see the attached screenshot/s for more information.

----- 16.1 -----

We also found that your app contains content that many audiences would find objectionable, which is not in compliance with the App Store Review Guidelines.

Specifically, we noticed your app contains objectionable content in the app.

Please see the attached screenshot/s for more information.

We encourage you to review your app content and evaluate whether you can modify the content to bring it into compliance with the Guidelines.

For discrete code-level questions, you may wish to consult with Apple Developer Technical Support. When the DTS engineer follows up with you, please be ready to provide:

- complete details of your rejection issue(s)
- screenshots
- steps to reproduce the issue(s)
- symbolicated crash logs - if your issue results in a crash log

If you have difficulty reproducing a reported issue, please try testing the workflow as described in Technical Q&A QA1764: How to reproduce bugs reported against App Store submissions.   

两个问题，一个是说在ipad和iphone5s，ios8.0.2上审核的时候发现登陆点击qq登陆没反，测试后发现确实是这样，原因就是腾讯qq不能直接调用客户端登录，在用户木有安装客户端的时候，当时我就给了个提示（说木有安装客户端，用其他方式登录），然后就有了之后的一次被拒（汗颜）。
另一个说是我们的app包含色情信息，苹果附了两张截图。这种情况可以通过回复跟苹果工程师沟通解决，我就说色情内容已经从后台撤销了。。。。另外也可以从app评级上解决，年龄12+就可以。

            
11月3号

Reasons
17.2: Apps that require users to share personal information, such as email address and date of birth, in order to function will be rejected

we found that your app requires customers to register with personal information such as a phone number to access non-account-based features, which is not in compliance with the App Store Review Guidelines.

Apps cannot require user registration prior to allowing access to app features and content that are not associated specifically to the user. User registration that requires the sharing of personal information must be optional or tied to account-specific functionality. Additionally, the requested information must be relevant to the features.

screenshot_0

增加了注册协议在app上，在itunesconnect添加了隐私协议。再次提交

11月11号：

Reasons

17.2: Apps that require users to share personal information, such as email address and date of birth, in order to function will be rejected 
----- 17.2 -----

We continue to find that your app requires customers to register with personal information such as a phone number to access non-account-based features, which is not in compliance with the App Store Review Guidelines.

Apps cannot require user registration prior to allowing access to app features and content that are not associated specifically to the user. User registration that requires the sharing of personal information must be optional or tied to account-specific functionality. Additionally, the requested information must be relevant to the features.

screenshot_0 1

应该是说的注册协议那个是不是要弄一个复选框啊。。。。

11月17

当时我是回复了一次，然后苹果又回复了一次。。

Reasons

17.2: Apps that require users to share personal information, such as email address and date of birth, in order to function will be rejected 
Hello, and thank you for your response.

While the app does not require registration, the app still requires the user's phone number in order to register for an account. 

We look forward to reviewing your app once this information is optional when registering.



紧接着就是另外一个app出现的问题

11月26

Reasons

16.1: Apps that present excessively objectionable or crude content will be rejected 
Information Needed 
----- 16.1 -----

We found that your app contains content that many audiences would find objectionable, which is not in compliance with the App Store Review Guidelines.

Specifically, we noticed your app contains imagery that may be considered objectionable to users.

Please see the attached screenshot/s for more information.

We encourage you to review your app content and evaluate whether you can modify the content to bring it into compliance with the Guidelines.

—————

Additionally, we have begun the review of your app but aren't able to continue because we need additional information about your app.

At your earliest opportunity, please review the following question/s and provide as detailed information as you can in response. The more information you can provide upfront, the sooner we can complete your review.

We noticed you've included QQ and Sina login for the app. 

- What QQ features are implemented into the app?
- What Sina features are implemented into the app?

Please reply to this message in the Resolution Center and make any necessary changes to the app so we can proceed with your review.

说了两个问题，一个就是 16.1：应用程序包含的信息过渡敏感或者过度反感或粗的内容将被拒绝
另外一个：问我们的app包含qq和新浪登陆功能，在那些地方用到了qq，那些地方用到了微博。
这次不需要重新上传，再排队等待7天。

苹果说回复就可以：Please reply to this message in the Resolution Center and make any necessary changes to the app so we can proceed with your review.
我就撤掉敏感内容，然后回复苹果第一个敏感内容我们已经从后台撤掉，另外一个，在用户评论的时候会用到qq登陆，sina登陆。需要用户发表评论的时候的昵称，以及分享的时候用到了

12月3号

Reasons

16.1: Apps that present excessively objectionable or crude content will be rejected 
Information Needed 
Hello, and thank you for your response.

With regard to social network logins such as QQ and Sina, it would be appropriate to implement additional account features into the app or provide users the option to log in via a native account. 

We look forward to reviewing your app once the issue is resolved.


12月15号 

Reasons

10.6: Apple and our customers place a high value on simple, refined, creative, well thought through interfaces. They take more work but are worth it. Apple sets a high bar. If your user interface is complex or less than very good, it may be rejected 
----- 10.6 -----

We found that your app requires the installation of another app before it can be used, which is not in compliance with the App Store Review Guidelines. Apps should be able to run on launch, without requiring additional applications to be installed.

Specifically, if we choose to log in via QQ, we were required to install QQ before we could use your app. Please refer to the attached screenshot/s for more information.

Please revise your app so that a user can use it upon launch. If your app requires authentication before use, please use a method that can authenticate users from within your app.
之前app用qq登录的时候是用户安装了qq客户端或者qq空间客户端就会调用客户端直接登录，如果木有登录客户端则会打开网页端，让用户输入账户，密码授权登录。
最近腾讯在SDK里面取消了网页登陆的功能，默认用客户端登陆。显然苹果的审核人员不会安装qq客户端，然后在木有安装的话用户没办法登录，之后就加了一个提示，显然这样提示苹果也不让我们审核通过，

到此时的时候前面两个app都已经审核通过了，上线appstore

2015年1月4号

另外的app，我们的app有自己的登录，注册，和新浪，qq登录。

Reasons

17.2: Apps that require users to share personal information, such as email address and date of birth, in order to function will be rejected 
----- 17.2 -----

We found that your app uses 新浪 and Qzone logins for authentication purposes only - but does not include any account-based features offered by that site. This is not in compliance with the App Store Review Guidelines.

It would be appropriate to modify your app to include account-based features of that social network - or use your own authentication mechanism.

我看了苹果的意思，我理解是我们有新浪和qq空间登录认证功能，但是木有基于社交网络的功能。将会被拒绝，我就回复苹果，我们的app有分享功能，用到了社交网络认证。

首先，感谢你的Review。
我们注意到你提到了我们用了新浪和QQ的授权登录，但没有使用他们的其他的account-based的功能。但实际上，我们在App中的以下几处用到了他们的基于用户的社交网络的功能。

第一个就是在用户对文章感兴趣的时候，进行评论需要用户的昵称和性别属性：在首页文章列表任意一个文章点击，进入文章详情，在下面四个button的第一个就是评论。

第二个就是在用户对感兴趣的文章进行分享的时候，就会把这篇文章分享到他的社交网络账号里面。

First of all, thank you for your review.
We note that you mentioned we used Sina and QQ authorized login, and did not use other account-based functions of them. But in fact, that's not true.

The first, If the user is interested in the article and want to submit comment, the nickname and the gender attribute are needed. To found out this function, you just need enter the detail page of any article(click an item on home page), the first button of the buttons at the bottom of the detail page is the comment button.

The second is when the user share the article to his/her socail network, the information of the third party account will be used.To found out this function, you just need enter the detail page of any article(click an item on home page), the last button of the buttons at the bottom of the detail page is the shared button.

1月5号苹果回复

Reasons

17.2: Apps that require users to share personal information, such as email address and date of birth, in order to function will be rejected

Thank you for your response. However, sharing and commenting features are not significant enough. Please include your own authentication in the app. We look forward to your resubmission.

至此又汗颜了。。。。。继续斗智斗勇进行中

Thank you for your patience, but we still not too clear about the issue.
The login method of the third party(such as Sina, QQ) is just an assistant way which would make our app be convenient for the users who already have Sina and QQ account and don’t want to regist more account in other platform, such as our app.
But we still have our own account authentication in our app.Users can use their mobile phone numbers to sign in our app.The reason that mobile phone number is used here is that we can prevent the problem of one person having too much account in our app.
Anyhow, the third party and the mobile phone number(or email) is a common way of app authentication in china. In fact, there are a lot of apps in AppStore are like that.
So, we are confused and we would be very thank you if you are willing to point out exactly what feature we should add or remove. Thank you.



另外一个app

Reasons

14.3: Apps that display user generated content must include a method for filtering objectionable material, a mechanism for users to flag offensive content, and the ability to block abusive users from the service
----- 14.3 -----

Your app still enables the display of user-generated content but does not have the recommended precautions in place, as required by the App Store Review Guidelines.

It is necessary that you put all of the following precautions in place:

- Require that users agree to terms (EULA) and these terms must make it clear that there is no tolerance for objectionable content
- Use moderators to flag and remove inappropriate content and offensive users
- Users need a mechanism to flag objectionable content and report users generating this content 
- Developer must act on objectionable content reports within 24 hours by removing the content and ejecting the user who provided the offending content
- Developer needs a method for ejecting users who violate the terms of the EULA
- 

这个个人理解就是对于完全是UGC（用户产生内容）类型的app，需要一个举报的功能，就像游记，微博，完全由用户产生内容，而新闻app就不需要吧，加了个举报功能继续提交审核。。。。。

至此四个app都上线了。

苹果appstore审核团队简直无语了，app新版本审核的时候，因为里面有屌丝两个字被拒绝。。。。。。

1月14

Reasons

3.6: Apps with App icons, screenshots, and previews that do not adhere to the 4+ age rating will be rejected 
----- 3.6 -----

Your Application Description, app icon, screenshots, or previews includes content that is not appropriate for all age groups, as required by the App Store Review Guidelines.

Since the metadata is visible to all users on the App Store, this content must meet the 4+ rating requirement, even when purchasing is restricted by a higher rating.

Specifically, it would be appropriate to remove or revise 屌丝 in the screenshots.

We’ve attached screenshot(s) for your reference.


http://weibo.com/p/1001603798850686053616





2017年11月

1 Performance: App Completeness
3 Performance: Accurate Metadata Guideline 2.1 - Information Needed
We have started the review of your app, but we are not able to continue because we need access to a video that demonstrates your app in use on a physical iOS device.

Please demonstrate the following features of your app:

Background audio
Please ensure the video you provide shows a physical iOS device (not a simulator).

Next Steps

To help us proceed with the review of your app, please provide us with a link to a demo video in the App Review Information section of iTunes Connect and reply to this message in Resolution Center.

To provide a link to a demo video:

Log in to iTunes Connect
Click on “My Apps”
Select your app
Click on the app version on the left side of the screen
Scroll down to “App Review Information”
Provide demo video access details in the “Notes” section
Click “Save”
Once you’ve completed all changes, click the “Submit for Review” button at the top of the App Version Information page.
Once this information is available, we can continue with the review of your app.

Guideline 2.1 - Information Needed

We have started the review of your app, but we are not able to continue because we need additional information about your app.

Next Steps

To help us proceed with the review of your app, please review the following questions and provide as much detailed information as you can.

Does your app access any paid content or services?
What are the paid content or services, and what are the costs?
Do individual customers pay for the content or services?
If no, does a company or organization pay for the content or services?
Where do they pay, and what’s the payment method?
If users create an account to use your app, are there fees involved?
How do users obtain an account?
Once you reply to this message in Resolution Center with the requested information, we can proceed with your review.

Guideline 2.3.8 - Performance - Accurate Metadata

We noticed your app name, subtitle, icon, or screenshots to be displayed on the App Store includes the term 少儿, which implies that this app is made specifically for children. However, this app was not submitted as a Kids category app.

Next Steps

To resolve this issue, please revise your app category and select the Kids category for this app. Please note that all Kids category apps must comply with the Kids category-specific sections of the App Store Review Guidelines.

If this app is not meant solely for children, it would be appropriate to remove any terms from your app name, subtitle, icon, or screenshots that imply the main audience of this app is children.

给苹果拍了一段视频，用百度网盘发过去，然后。。。。

We have started the review of your app, but we are not able to continue because we could not directly access the video that your provided. Please make sure the the access of the video does not require registration or login.

然后又是再来一次，加了文字回复。。。。。

演示视频地址：

我们的官网地址：

我们的app主要是专注于4-12岁孩子数学思维的开发和培养，孩子和老师是一对一在线直播上课的，上课是在家长的监护陪同时进行的。另外我们的app没有内购的场景，家长通过线下报名付费，我们给每个家长分配一个账号，学生在规定的时间在父母陪同下打开app和我们的老师一起上课。每一节课上课前都会有一个预习视频，点课程日历列表中的预习按钮开始播放视频，学生预习完在课前5分钟点击进入教室按钮就可以进入开始上课了。

12月22日

Guideline 3.1.1 - Business - Payments - In-App Purchase

We noticed that your app provides access to external payment mechanisms for purchases or subscriptions to be used in the app, which is not appropriate for the App Store.

Specifically, we found that your app allows users to access content that is paid outside of the app.

Next Steps

To resolve this issue, please remove any external payment mechanisms from this app. If you feel that we have misunderstood how your app uses this payment mechanism, please respond to this message and explain what users are able to purchase via this payment mechanism and how we can locate the purchases in your app.

您好，感谢您审核我们的应用程序：

我们的app主要是专注于4-12岁孩子数学思维的开发和培养，孩子和老师是一对一和一对六在线直播的方式上课的，上课是在家长的监护陪同时进行的。家长通过线下报名付费， 因为作为一家在线教育公司提供教学服务，我们只需要我们的客户在我们的应用程序中上课。用户支付在教学过程中产生的人工成本和教学教研成本，并不会购买仅在APP中需要的信息，所以没有内购的场景。

12月23日。。。。

Hello,

Thank you for your response.

Regarding the 3.1.1 issue, it would be appropriate to implement in-app purchase.

We look forward to your resubmission.

Best regards,

TestFlight Beta Review

12月28日

您好：

我们的app是给学生上课用的，没有应用内支付，学生通过线下购买充值卡，卡里包含上课使用的次数，这个钱都支付给了老师，我们的场景不符合苹果要求内购的任何一个条款，在中国很多这样的公司都在做类似的业务，比如说51talk.com,vipkid.com.cn等等都是在做的在线教育，他们的app审核也没有走内购。麻烦您再看看审核的标准。

审核通过了，xcode9.2打包的程序在ios8上有bug。。。。。。。

1月10日

2018年1月11日 上午3:08 发件人 Apple

1.1 Business: Payments - In-App Purchase Guideline 3.1.1 - Business - Payments - In-App Purchase
We noticed that your app or its metadata enables the purchase of content, services, or functionality in the app by means other than the in-app purchase API, which is not appropriate for the App Store.

Specifically, your app allows users to access content that is paid outside of the app.

The next submission of this app may require a longer review time, and this app will not be eligible for an expedited review until this issue is resolved.

Next Steps

Review the In-App Purchase section of the App Store Review Guidelines.
Ensure your app is compliant with all sections of the App Store Review Guidelines and the Terms & Conditions of the Apple Developer Program.
Once your app is fully compliant, resubmit your app for review.
If you believe your app is compliant with the App Store Review Guidelines, you may submit an appeal. Alternatively, you may provide additional details about your app by replying directly to this message.

In-App Purchase

It may be appropriate to revise your app to use the in-app purchase API to provide content purchasing functionality.

In-app purchase provides several benefits, including:

The flexibility to support a variety of business models.
Impacting your app ranking by consolidating your sales to one app rather than distributing them across multiple apps.
An effective marketing vehicle to drive additional sales of new content.
For information on in-app purchase, please refer to the following documentation:

In-App Purchase for Developers

In-App Purchase Programming Guide

For step-by-step instructions on in-app purchase creation within iTunes Connect, refer to In-App Purchase for Developers.

我们的app主要是专注于4-12岁孩子数学思维的开发和培养，孩子和老师是一对一和一对六在线直播的方式上课的，上课是在家长的监护陪同时进行的。 因为作为一家在线教育公司提供教学服务，我们只需要我们的客户在我们的应用程序中上课，并不会购买仅在APP中需要的信息，所以没有内购的场景。 老师端可以随时进入教室，学生端会在课前10分钟才能进入教室，图中的倒计时代表离上课还有多少时间，您当前的时间是11:03am，课程开始时间是15:00pm，距离上课时间还有3:57:33，课前学生可以通过预习了解上课内容，当时间到了14:50学生就可以进入教室了，不需要支付。

3.1.3 “Reader” Apps: Apps may allow a user to access previously purchased content or content subscriptions (specifically: magazines, newspapers, books, audio, music, video, access to professional databases, VoIP, cloud storage, and approved services such as educational apps that manage student grades and schedules), as well as consumable items in multi-platform games, provided that you agree not to directly or indirectly target iOS users to use a purchasing method other than in-app purchase, and your general communications about other purchasing methods are not designed to discourage use of in-app purchase.

https://developer.apple.com/app-store/review/guidelines/#content-based-reader-apps

2018年1月18日 上午4:56 发件人 Apple

3. 1.1 Business: Payments - In-App Purchase Hello,
Thank you for your response. In regards of the 3.1.1 rejection, we found that your app allows user to purchase classes by means other than the in-app purchase API, which is not appropriate for the App Store. It would be appropriate to implement in-app purchase for the one to many classes before resubmitting for review.

We hope you can make the necessary revision and we look forward to review your app again.

Best regards,

TestFlight Beta Review

http://a1194.phobos.apple.com/us/r30/Purple128/v4/d2/5d/a1/d25da10b-46fc-9b25-8edf-2e5ca104dcc9/attachment-25867357965228491302749638fe489817e963d21f8aac87c8f.png?downloadKey3=1516440184_56abe507de65b9e6f5fc8fde8298c72e

2018年7月3日 下午11:16 发件人 Apple

5 Performance: Software Requirements
Design: Preamble Guideline 2.5.2 - Performance - Software Requirements
During review, your app installed or launched executable code, which is not permitted on the App Store. Specifically, your app uses the itms-services URL scheme to install an app.

Please note that while educational apps designed to teach, develop, or allow students to test executable code may, in limited circumstances, download code, such code may not be used for other purposes and such apps must make the source code completely viewable and editable by the user.

The next submission of this app may require a longer review time, and this app will not be eligible for an expedited review until this issue is resolved.

Next Steps

Review the Software Requirements section of the App Store Review Guidelines.
Ensure your app is compliant with all sections of the App Store Review Guidelines and the Terms & Conditions of the Apple Developer Program.
Once your app is fully compliant, resubmit your app for review.
Submitting apps designed to mislead or harm customers or evade the review process may result in the termination of your Apple Developer Program account. Review the Terms & Conditions of the Apple Developer Program to learn more about our policies regarding termination.

If you believe your app is compliant with the App Store Review Guidelines, you may submit an appeal. Alternatively, you may provide additional details about your app by replying directly to this message.

Guideline 4.0 - Design

Your app includes an update button or alerts the user to update the app, but the update button or alert does not link directly to the app’s page on the App Store.

Next Steps

To resolve this issue, please ensure that tapping the update button takes the user directly to the app’s page on the App Store to update the app.

Since your App Store Connect status is Rejected, a new binary will be required.

用了 。。。。 fir.im


2019年3月7日 录制ipv6的视频发过去 

IPv6 and App Store Requirements

Compatibility with IPv6 DNS64/NAT64 networks will be an App Store submission requirement, so it is essential that apps ensure compatibility. The good news is that the majority of apps are already IPv6-compatible. For these apps, it’s still important to regularly test your app to watch for regressions. Apps that aren’t IPv6-compatible may encounter problems when operating on DNS64/NAT64 networks. Fortunately, it’s usually fairly simple to resolve these issues, as discussed throughout this chapter.

Common Barriers to Supporting IPv6

Several situations can prevent an app from supporting IPv6. The sections that follow describe how to resolve these problems.

IP address literals embedded in protocols. Many communications protocols, such as Session Initiation Protocol (SIP), File Transfer Protocol (FTP), WebSockets, and Peer-to-Peer Protocol (P2PP), include IP address literals in protocol messages. For example, the FTP parameter commands DATA PORT and PASSIVE exchange information that includes IP address literals. Similarly, IP address literals may appear in the values of SIP header fields, such as To, From, Contact, Record-Route, and Via. See Use High-Level Networking Frameworks and Don’t Use IP Address Literals.
IP address literals embedded in configuration files. Configuration files often include IP address literals. See Don’t Use IP Address Literals.
Network preflighting. Many apps attempt to proactively check for an Internet connection or an active Wi-Fi connection by passing IP address literals to network reachability APIs. See Connect Without Preflight.
Using low-level networking APIs. Some apps work directly with sockets and other raw network APIs such as gethostbyname, gethostbyname2, and inet_aton. These APIs are prone to misuse or they only support IPv4—for example, resolving hostnames for the AF_INET address family, rather than the AF_UNSPEC address family. See Use High-Level Networking Frameworks.
Using small address family storage containers. Some apps and networking libraries use address storage containers—such as uint32_t, in_addr, and sockaddr_in—that are 32 bits or smaller. See Use Appropriately Sized Storage Containers.




2018年7月3日 下午11:16
发件人 Apple
* 		2. 5 Performance: Software Requirements
* 		4. Design: Preamble
Guideline 2.5.2 - Performance - Software Requirements
  During review, your app installed or launched executable code, which is not permitted on the App Store. Specifically, your app uses the itms-services URL scheme to install an app.  Please note that while educational apps designed to teach, develop, or allow students to test executable code may, in limited circumstances, download code, such code may not be used for other purposes and such apps must make the source code completely viewable and editable by the user.  The next submission of this app may require a longer review time, and this app will not be eligible for an expedited review until this issue is resolved.  Next Steps  - Review the Software Requirements section of the App Store Review Guidelines. - Ensure your app is compliant with all sections of the App Store Review Guidelines and the Terms & Conditions of the Apple Developer Program.  - Once your app is fully compliant, resubmit your app for review.  Submitting apps designed to mislead or harm customers or evade the review process may result in the termination of your Apple Developer Program account. Review the Terms & Conditions of the Apple Developer Program to learn more about our policies regarding termination.  If you believe your app is compliant with the App Store Review Guidelines, you may submit an appeal. Alternatively, you may provide additional details about your app by replying directly to this message. 
Guideline 4.0 - Design
  Your app includes an update button or alerts the user to update the app, but the update button or alert does not link directly to the app’s page on the App Store.  Next Steps  To resolve this issue, please ensure that tapping the update button takes the user directly to the app’s page on the App Store to update the app.    Since your App Store Connect status is Rejected, a new binary will be required.
  
  加举报 ，审核功能
  
  
Guideline 2.1 - Performance - App Completeness
  We discovered one or more bugs in your app when reviewed on iPad running iOS 12 on Wi-Fi.  Specifically, the playback (回放) button is greyed out and not accessible to replay previous course video.  Next Steps  To resolve this issue, please run your app on a device to identify any issues, then revise and resubmit your app for review.  If we misunderstood the intended behavior of your app, please reply to this message in Resolution Center to provide information on how these features were intended to work.  For new apps, uninstall all previous versions of your app from a device, then install and follow the steps to reproduce the issue. For updates, install the new version as an update to the previous version, then follow the steps to reproduce the issue.  Resources  For information about testing your app and preparing it for review, please see Technical Note TN2431: App Testing Guide.   For a networking overview, please review About Networking. For a more specific overview of App Review’s IPv6 requirements, please review the IPv6 and App Review discussion on the Apple Developer Forum. 
Guideline 2.3 - Performance - Accurate Metadata
  We were unable to locate some of the features described in your metadata.   Specifically, all contents in your app are not available to access until the set future dates.  Next Steps  If these features are located in your app, please reply to this message in Resolution Center to provide information on how to locate them.   Alternatively, please revise your app to ensure that these features are fully implemented or revise your app description, release notes, and screenshots to remove all references to the features.  Please see attached screenshots for details.


Guideline 2.2 - Performance - Beta Testing


Your app appears to be a pre-release, test, or trial version with a limited feature set. Apps that are created for demonstration or trial purposes are not appropriate for the App Store.


