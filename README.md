appstore-review1
================
10月23

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

12月3���号

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







