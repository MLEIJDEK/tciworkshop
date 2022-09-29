![](https://docs.google.com/drawings/d/s4himmmN4z0jrmu0q8t7kTA/image?parent=1ww6ZDEVSSYTpPvQnRchtAP4vJfpXYGd9VkDc60bSPe4&amp;rev=1&amp;drawingRevisionAccessToken=zbrjbKIwtJ7jWw&amp;h=135&amp;w=1063&amp;ac=1)

![](https://docs.google.com/drawings/d/sYsv0Js4f8eXOl5X10XUJ5A/image?parent=1ww6ZDEVSSYTpPvQnRchtAP4vJfpXYGd9VkDc60bSPe4&amp;rev=1&amp;drawingRevisionAccessToken=xV8U75p2HkfujQ&amp;h=110&amp;w=736&amp;ac=1)![](https://docs.google.com/drawings/d/s6I8uHbz72GPHPKU7CofT0g/image?parent=1ww6ZDEVSSYTpPvQnRchtAP4vJfpXYGd9VkDc60bSPe4&amp;rev=1&amp;drawingRevisionAccessToken=gUiZqcHMTaUC1w&amp;h=111&amp;w=737&amp;ac=1)


![](https://lh6.googleusercontent.com/e7VS2rZ3shuDI-DMKUnPBlxEC2g84K0mcYlYfN-_6MQbPguRuRML8Bi3KIO4Zds1S1aP5NCG4f40Qx7x6YKAOjHTdybJL7jaEkJe7_iqwK0g8ubXdfGSc-mKLUiwaDYmz3Ic0Y-7KV5MfuqT2-ACHWENXaz0MlRld_vs6KeODCPgYP182Gfs7MgTvw)![](https://docs.google.com/drawings/d/swFd1ClsnvsFvvEpbPC4UDw/image?parent=1ww6ZDEVSSYTpPvQnRchtAP4vJfpXYGd9VkDc60bSPe4&amp;rev=1&amp;drawingRevisionAccessToken=hVmFOe3bN2FXcw&amp;h=412&amp;w=231&amp;ac=1)![](https://docs.google.com/drawings/d/sh7aheNbgeSxbAWUdbS9s4Q/image?parent=1ww6ZDEVSSYTpPvQnRchtAP4vJfpXYGd9VkDc60bSPe4&amp;rev=1&amp;drawingRevisionAccessToken=bBVmeXqMO8YMVw&amp;h=135&amp;w=1063&amp;ac=1)

**iPaaS Workshop**

![](https://docs.google.com/drawings/d/s_zsbwhntM-O1MbxIwGdDGg/image?parent=1ww6ZDEVSSYTpPvQnRchtAP4vJfpXYGd9VkDc60bSPe4&amp;rev=1&amp;drawingRevisionAccessToken=GPEnQW_wFBzrMA&amp;h=44&amp;w=312&amp;ac=1)

![](https://docs.google.com/drawings/d/s2Og0evCLD4QX8sn8Id-Pdg/image?parent=1ww6ZDEVSSYTpPvQnRchtAP4vJfpXYGd9VkDc60bSPe4&amp;rev=1&amp;drawingRevisionAccessToken=hQKNddqZ2tGI7g&amp;h=632&amp;w=868&amp;ac=1)

* * *

![](https://docs.google.com/drawings/d/ssZSfxD9gbAO_p3sC1NOzyw/image?parent=1ww6ZDEVSSYTpPvQnRchtAP4vJfpXYGd9VkDc60bSPe4&amp;rev=1&amp;drawingRevisionAccessToken=gGUq6soTUgBRig&amp;h=492&amp;w=823&amp;ac=1)![](https://docs.google.com/drawings/d/sfKZd6dzK7i9uU4NBveam0w/image?parent=1ww6ZDEVSSYTpPvQnRchtAP4vJfpXYGd9VkDc60bSPe4&amp;rev=1&amp;drawingRevisionAccessToken=mSj_PoqltS4-Fw&amp;h=347&amp;w=391&amp;ac=1)

Table of Contents

Introduction        4

Overview        4

1. Validate Your Environment        5

1.1 Sign up for Cloud Trial Environment        5

1.2 Sign in to TIBCO Cloud        7

1.2.1 Getting Ready        7

1.2.2 How to Do It        7

2. Design an API and Create a Mock Application        10

2.1 Design an API        10

2.1.1 Getting Ready        10

2.1.2 How to Do It        11

2.2 Create a Mock App        15

2.2.1 Getting Ready        15

2.2.2 How to Do It        16

2.3 Import API Specs        17

2.3.1 Getting Ready        17

2.3.2 How to Do It        18

2.4 Additional Reading        22

3. Build and Deploy Your API        23

3.1 BusinessWorks Apps in TIBCO Cloud Integration        23

3.1.1 How to Do it: Import the Business Works Application via EAR import        23

3.2 Flogo Apps in TIBCO Cloud Integration        27

3.2.1 Getting Ready        27

3.2.2 How to Do It: Create the Skeleton Flogo App from the API Specification        27

3.2.3 How to Do It: Implement the Flogo App        29

3.2.4 Push the Integration App to TIBCO Cloud and Test It        38

3.3 Additional Reading        42

Extra LAB: Business Events Simple Decision Service        43

What You Will Learn        43

Getting Ready        43

Creating a Base TCE Project        44

Implementing a Simple decision service        46

Deploying the Decision Service        49

Testing the Decision Service        51

Summary        52

Extra Lab: BusinessWorks Apps in TIBCO Cloud Integration        53

1 Getting Ready        53

2 How to Do It: Connect Business Studio to TIBCO Cloud        53

3 How to Do It: Import a Project in to Business Studio        55

4 How to Do It: Push the Project to TIBCO Cloud and Test        56

* * *

# **Introduction**

In this lab exercise you will learn the Tibco Cloud Integration capabilities. You will define new API’s in the API management by an API-Led approach. Then you will implement this API using the Integration capabilities. For the connection to the Business Applications, you will deploy existing on-premise Business Works integrations into the Tibco Cloud.

## Overview

The use case that you will build is a sales order processing scenario.

![](https://lh4.googleusercontent.com/Jtdw_ZaFWOrlvoOY16sTaXLqA7dYJLqd42_3N7r22Ez0jGwrzlmgp_JwfCvCjeEWqXVkdPS-H8DtBSHOig7c6FR6ivmmQr94paP5mj6GZhr4PpPMOPgHt3WyvDs4OzhGWuaf9Ia_PrpjkH-jWikGRKx7FCcyeGWvfijMLf9EuwGPg0pnf5FGByR12Q)

In a step by step lab instruction, you will learn the Tibco Cloud Integration service and experience the low code development capabilities of our platform.

* * *

# **1. Validate Your Environment**

In this section, you'll validate your lab environment, which consists of a TIBCO Cloud Integration trial environment.

## 1.1 Sign up for Cloud Trial Environment

You need access to TIBCO Cloud Events subscription. If you do not have one, you can request for free trial via the below link.

TIBCO Cloud™: [https://account.cloud.tibco.com/signup/tci](https://account.cloud.tibco.com/signup/tci)

![](https://lh3.googleusercontent.com/f0RqUDFuajOLswEzbGRS4VYSuGE-_xKQ8dg2AwyF83kWqUo_MnPreK7aHRi2iRM8jvz_faiuVvjzNIVF-hmcBrSVnTD1y-7tmsULHA08yw1gncKTOeKvtjVa1SmdL_ym6mcI-wViGKqagH1khukOuTXuC3kVq3lNccAaxw_j-J7a4OjZqLkyLxAlxQ)

- choose the **“AWS United States”** as a region and click “**Start Free Trial**”
- Wait for the Welcome email to activate your trial account.


![](https://lh5.googleusercontent.com/dhPKu3JSU2qmEs6gMvF3vCEiEFYX8M45gs08wKMPtuekb3Bk1QoorxN3aDIuGTlv97xtVCCmiCpfmCeNGVenQHwgvpFW3CSy1Fg4WUwJhLh8KAmQyeUVQHsk_0buH30aLUski-_EhqLPsHv5kJfjzHOnl8f3x0zv302HrFzaYjXx__rZd7C_MW55AA)

- Click the “Activate your Account” button and set your password in the form.


![](https://lh6.googleusercontent.com/r4yVFzKdQc0zXEduwlDEaAqiu250vN1DRQDoznyVugSOXQDc7uAvr2vii9-H4ykam99lPgeJFQcqNBPvhqEFAJ-K7xmqWajO9H4BSaSTxM8G6ZKBQBjhWJhpPcJVLI6IQNY9_ZMP6eNrvXaVsN2ajook6lFjYED9_uLA5C1HukrDuujSpEkreTi-0A)

## 1.2 Sign in to TIBCO Cloud

### 1.2.1 Getting Ready

This lab assumes you have started a trial of TIBCO Cloud™ Integration (If you haven't, [click here](https://www.tibco.com/products/tibco-cloud-integration/sign-up?_ga=2.96144156.1661410125.1557311514-1465520282.1557311514) and follow the instructions below)

![](https://lh6.googleusercontent.com/GqpUfg78yBgRz-Vi4lvo44h-JP3Wb2_osdK8IPH4o-BcmowAI3z0W5YDUNkBUGwQ4dy452fZTx57qhIKNct4Urzidx4ear7q3036J4t79WM0-blso-B7a94AOhgBSEbUqJK1RLnYDS_Whm88EsrH7wV_8IZ7MDRbWOa1L33bC_0lcCxtTy1-VJkd9A)

### 1.2.2 How to Do It

1. Browse to [https://cloud.tibco.com/](https://cloud.tibco.com/).


![](https://lh6.googleusercontent.com/wJUDeqsauOMLmE4ayKW9n6nb3QvkFqWp6RPJehWRSlGiv7NN2nIQynelzaUI1fNEvljITWdOeUnnBJbJNjPIhlG2zy-NgLyfrZiAHZLKpBQ9vDVWE1Yxgv6C2nww-Ob-Q50fnhqCmX5mJ-KAjF_vU3gbUBgObD0uKY0Do2hLc83H4XOEVOBs0TJa8g)

1. Click **SIGN IN** (at the right top) and select the **United States – West** Region


![](https://lh4.googleusercontent.com/HPHkFMwr0b7MUdklpi7dIRwlhmt0xIBOWnV-UsCOM5yD1pFLe_fI9pW1Ml8L-l-W-mBlkwoRxDSNS9mHqYal1Y7KF1AdMpBo2CzvYYXo3ateh7C_WS2K-m2EY1xrbA8_b6oxpEoepS7BbOI42kSYCMp9QJklHschHmf0ZHCOld6C-29ekW-ek1QloA)

1. Fill out the relevant account details (**Email Address** and **Password**) in the following screen.


![](https://lh6.googleusercontent.com/eh4fvVmfmCTezxCp5cK5fUsKJiTte5HBc9-RyHY6UuPv1OQ1F_96UCSaPtbJ5YcJSNCQL84nNLo3eahwvs3cdEeKlY66lgSTCFKfMdtI5HB0nLSI71y0fe2S14hpoo-aB88kwb_5QMAsypV29ckWJvIWJ5IgX_UbcaeB0EjgOxp7Niwdxo2hMwhhjw)

1. After this, you should see a landing page which looks similar to this:


![](https://lh6.googleusercontent.com/GqpUfg78yBgRz-Vi4lvo44h-JP3Wb2_osdK8IPH4o-BcmowAI3z0W5YDUNkBUGwQ4dy452fZTx57qhIKNct4Urzidx4ear7q3036J4t79WM0-blso-B7a94AOhgBSEbUqJK1RLnYDS_Whm88EsrH7wV_8IZ7MDRbWOa1L33bC_0lcCxtTy1-VJkd9A)

* * *

# **2. Design an API and Create a Mock Application**

**API Modeler** is a web-based tool that provides you with the capability to graphically create and model a REST API.

With API Modeler, you can import REST API specifications either in a YAML or JSON file for further editing, or model your own REST API step-by-step in a visual interface. After modelling an API, you can choose to mock it and see the API in action, or directly implement it.

In this section, you'll design an API using API Modeler and generate a mock application based on it. Furthermore, you'll import several API specs.

- Design an API
- Create a Mock App
- Import API Specs


## 2.1 Design an API

### 2.1.1 Getting Ready

In this lab, you'll create an API using the API Modeler. To navigate from the landing page to the API Modeler, do the following:

1. Navigate from the TIBCO Cloud landing page to Cloud Integration by clicking the **APIs** hexagon.
2. Click on the **API Model and Mock** link.
3. After this, your screen should look similar to this:


![](https://lh4.googleusercontent.com/eXFebYmKFdO3RXGvlwzVOgUHbPF1a1zLpx6tXjsT4MaNg66P95gRjnImcP2ECVKKjLMYuO8z2Qq7mPmOTNpvgbHdaZ6CmCt6x64mwBPmOPrlKNlviiAx8kAGvwOOeKopDjX4yWlUgoV53mCedNfTigXcqTYTU0SevA8RCtVr1iivv2acesYTM8tEag)

### 2.1.2 How to Do It

1. Create a group (this is optional) by clicking the **+** sign to the right from **GROUP** and give it a name e.g. **MyTCIWorkshop**.


![](https://lh5.googleusercontent.com/t0cPJpfmo9lUCjstQAML70_HgAljSBajbKajCk9gogxrqnUATLBO7PeHBEQIeH85bngaL8iG17nMczu9a4oWlE95RLQCdPA6YZlyxL0b3Il037GVqKDEEgWf1EOnn7iUG6fg9NbL_xCLRYb6Sxf3JqBFrRBRoTLCG_VREY4OTN3OOgsActTBt7iIkQ)

1. Create an API spec by clicking on **MyTCIWorkshop**, and click on the orange **Create** button.
2. In the form, use the following values:



| Field | Value |
| --- | --- |
| **API name** | SalesOrders |
| **Version** | 1.0 |
| **Select Group** | MyTCIWorkshop |


1. It should look something like this:


![](https://lh5.googleusercontent.com/y2fDeQVKzy32P--aIOPtbktfzdgxcpxTheknZwmGYJwW6dt8ifQ0oXfh0pJm6qemMBVOyFlQlms512jvw9g-VO8ea_ZO-FC7ZOPpsh-Ne8Sdg-6YtjsPdaEo2D13s57gWN9QQWOpCixXpxQrKWa1d05Rpi3AYftsoizugzedZRi1As2Qt6Fom9KJMg)

1. Click the blue **Create** button
2. Add a resource to the API spec by clicking on the orange **Add Resource** button in the next **SalesOrders** screen.


![](https://lh3.googleusercontent.com/FcTN4WXmuP66mYcjiIThbXt5Dhf12QbhJhe6IgIAth590h-CdTpK-oJnYfxTpoeNlYjsDhXS_um3EayJCTEAAkmK6HutYYKXhfENNCdE17nLzmmOmeJwnKzlqhxWm9KcJX1zk5Yt1ipLFrVIUo8bXrFSHW1kUFmbxyh6F7If5NA5Eo1vEoH-LcpRDA)

1. In the form, use the following values:



| Field | Value |
| --- | --- |
| **Resource path** | /sync/{orderId} |
| **Method** | POST |


1. The form should look something like this:


![](https://lh6.googleusercontent.com/Eaqs_ql6nEhWuBcBqONFryeJA5PSn7o3M09zA-1N9_tKSpKohFvcwKaJjCyKQruBuExBvqo-G_Mi-UZlKzyuIi3gfnHYlWwCs7CchzOv2oyxmsBRNYHD1JFwtuHJK7b0YDUviduis0eXvZTTnu39likHQh_xtLxW7K7fbMjZ2o4sAc1br9AMlvFR5w)

1. Click on the blue **Save** button.
2. Edit the success response of the **POST** method by first clicking on the white **Response** button in the next **POST /sync/{orderId}** screen, and then clicking on the **Success response** (**200/OK**) card.


![](https://lh5.googleusercontent.com/UHygPgdHK2U6YX3GGaq-bhF5geLRQnIICDR278-peHDeBUod5ujDErP2-D29GhrcqsGBAQwAwPFD7SdQOeqnWzhK8I17vJ6_K8ZZ_AA9I8e80g2BNnRM3o3q5jcb5kKsqHR9ESALJHKCZEnWWrL74Z1HGUM0MWGDUo886VZG-V4SZuVF3CHz73YRKA)

1. In the form, click on the **Generate Schema from Sample Data** link.


![](https://docs.google.com/drawings/d/s4rpZtxQLfdKb_tCDISbeWQ/image?parent=1ww6ZDEVSSYTpPvQnRchtAP4vJfpXYGd9VkDc60bSPe4&amp;rev=1&amp;drawingRevisionAccessToken=EUeqL5xuNzi-Hw&amp;h=99&amp;w=603&amp;ac=1)

Then on the orange **Continue** button. Copy the below sample json in the **Provide Sample Data** field:

{  "\_response\_string": "Order has been created with SalesDocumentID 00000013572"}

The form should look something like this:

![](https://lh5.googleusercontent.com/6EIAyBGgES0C1LuIYZN72EHaBh7p4nQlKxYRQlsnezON_3KBpqSORk8Ftwkj5BT8XXDOmOxbRLpNOTwkM7xwNw45vmeykQHyCgi3SsxzY_PDShQ1TXZQilnPwNcNPMJ7Rlrlh5Z4dpTRvsrD47HZZOHLoC_uUHXSVtLBTDw_wYjk4UgB0Mp7EW3Baw)

Click on the orange **Generate Schema** button, and replace **GiveNewSchemaNameHere** by **salesOrderSyncResponse** in the next form. The form should look something like this:

![](https://lh4.googleusercontent.com/pOV4PhpqwIGrlngXQgF3REt2TAtJGjHrWGis3GTTJgn4HRA7bSFrzOV1QPvYSqGNxATCvdOjAY3BKlbCvcAda-Fh9QqBOhStFeosa-vG0KPwm6Awg2tS-Jgtgwz1ZiPDQLweiNhRscbPn0qCf4EWoVXsdkesJIxThaye_YcZ1KHrcyFFNkG19xBgUQ)

Click on the blue **Save** button.

1. Click on the **Preview** icon, and your screen should look similar to this:


![](https://lh4.googleusercontent.com/rcuSdoN1sMh0Rlf9QFH0RO4J4urDyjc3wIiMiZmF_bT-NWVN_IEdpZsDV2GH7hNu7gO5owF8Yxokl66XrkGhmWHZq9_PLJ0ZTOZoMdIP6-XF21J3hCEqjDtxxKOT3lz4qP8k_hDhigJIE8mDpElfJKw3WPBZgQjnhIZzXE1-y1u78tb1r9_i_zbxcw)

## 2.2 Create a Mock App

### 2.2.1 Getting Ready

In this lab you'll create a mock application based on the API specification created in the previous lab. In order to do this:

1. Navigate to the API specifications by clicking on the **API Specs** menu item.
2. Select the group you've created the **SalesOrders** API specification in, e.g. **MyTCIWorkshop**.
3. Your screen should look similar to:


![](https://lh3.googleusercontent.com/Yu6FwA10R3npOqKivWFi1j2qe_xrLhDEIgFj7VBJxnqQGBAISH4bG1BEzKVTyFXeqjOlFbbmT3s83u3TIgq5kuuyODPzd1U9K7nVD5zpl-BPpD4eutFu17g0fO7rO1Gu90MvS2-pQpTT4vHGVYnPI8aszIGHBb1hEP0tDI4xddVDEPxpx7tqn5XTMg)

### 2.2.2 How to Do It

1. Hover over the **SalesOrders** record to the right of the preview icon, and select **Create Mock app** from the menu:


![](https://lh6.googleusercontent.com/LI2AHn9nGV0ZO-5eHZceAZ3dsM02Xy6z-6J3aVlZkD23wGLbHoDgxYS6jiITlLqf-ByDMV9f0rG_LDaFG1p8_Dg5WP6oDnnh13oXGkY3QKoOYYVXgFCnqC5gjYsHkBHY-NnbXWhvUrs9h8Rq7TrwLPXss2YcyTDrYZIc0JK8jCZtRwWhSXPA8lzekQ)

1. Create a mock app by clicking on the **Create** button in next form:


![](https://lh5.googleusercontent.com/Rtb0PAtasAK2uDG4ZzFxnSxhkheGoyv2l5onGP5XoRzyrEb3pJ0PV1s32CSbHzlzfSjw2YshsVml6sMEOav71YsCV6Zen7g3ELLap66Ojeinur7v6kbm4Ej9Fc9TSrx48ZI5XPMFz8qK6rMKVdVKYy0frsoQBMnyNLuo26EILaVt1YcBJKexPr6exA)

1. Once the mock app is running, hover over the **Endpoint** link, and select **View and Test** from the menu:


![](https://lh4.googleusercontent.com/x9tTF9XGZIAJOMESh3z83YmbZEQJb8_0n1joM0ygxfbFgjwjD9Q_xXIxrlAuw9d7T8LzcOLFEXIP1JD77JqXUsrdcnxycinRXqqjzz0HJPRI4tv4JCyA3-lGsp_or2HsXgts-OAlTRpOiFP7bqGUFhyLhfOI6BhVzgFX3dp05igtRVyeesH7H1Waog)

1. Test the mock app by filling out a value in the **orderId** field, and clicking on the **Try it out!** button:


![](https://lh4.googleusercontent.com/D-H3L_3UQZIDxepQYOMjJ7CO0Sovsq8pc16zOcnWfbjYcQZqAAbVeGr9ruJxEz89sRdMZEsXdcbyyLqGhhKrfEcoKsDKyBfmzYjPPmMpK9JMbvR91JsODewbUZYxlpiBrvOov2HvYAUMYeN944cznP7fnIR8-V74AGS0JA-4NkKlbNsL9ABarvtIzQ)

## 2.3 Import API Specs

### 2.3.1 Getting Ready

In this lab you'll import additional API specifications. In order to do this:

1. Navigate to the API specifications by clicking on the **API Specs** menu item.
2. Select the group you've created the **SalesOrders** API specification in, e.g. **MyTCIWorkshop**.
3. Your screen should look similar to:


![](https://lh3.googleusercontent.com/Yu6FwA10R3npOqKivWFi1j2qe_xrLhDEIgFj7VBJxnqQGBAISH4bG1BEzKVTyFXeqjOlFbbmT3s83u3TIgq5kuuyODPzd1U9K7nVD5zpl-BPpD4eutFu17g0fO7rO1Gu90MvS2-pQpTT4vHGVYnPI8aszIGHBb1hEP0tDI4xddVDEPxpx7tqn5XTMg)

### 2.3.2 How to Do It

1. Click on the **Import** button to import the API specifications:


![](https://lh6.googleusercontent.com/8euB1e8nedpDsMiCACKfkgIUQgo-vfzT2530J1aQIkrkUz23q_7-SPerpI6N5qwvRrDGLzhGO7RRj-ORWE5T3N8V4fekkACxYpKF6uDQNHUBHlJKNclkNy4GdaaQqypsYCnPuC139LSIJ3QUV-TylSeqw15x52eFXUcW2FxkQw5gAJAigN0_fFRdAQ)

1. Select **Import from filesystem**,


![](https://lh4.googleusercontent.com/yF8gL6m5CXqozMdK1tThcRKhQ6mQ8lbL078S_J-vvCFZIFhld46y3z11m9DTlZn9gRhcEegknIsNlMSdnlEOckNaFaK5TVAcMqhPpJ-acYlIcdD__Nx3NHZA4mOlFRG3qxWq1AxyDmO-hK7rO7isgB8eZSHrsG7eXYwVcSiSWZGradaqQvA-RUzVkQ)

and select the following files from the github  /[api\_specs](https://github.com/MLEIJDEK/tciworkshop/tree/master/src/api_specs)/ directory:

- [**SAPHanaPurchaseOrders.json**](https://github.com/TIBCONL/tciworkshop/blob/master/src/api_specs/SAPHanaPurchaseOrders.json)
- [**SAPOrders.json**](https://github.com/TIBCONL/tciworkshop/blob/master/src/api_specs/SAPOrders.json)
- [**sfContacts.json**](https://github.com/TIBCONL/tciworkshop/blob/master/src/api_specs/sfContacts.json)


1. Once these files have been uploaded, your screen should look similar to this:


![](https://lh4.googleusercontent.com/aHWxMQqiXQQGmmT70tL_r39XQmTq-Vtz3KKa6NlgSGZQULTCS3U3ZS3raZLkpl5xw_7R1q1uqNtfVOQEx4AGgZhANO1PmBJE2Wke0z00zZDH5WojGZmMoXFPrSaqPqYscCE47uTtgBA5Uv8HWsJUdmDxakPPefjN3olspxvUUYt8s5K6cRMzK8UjGA)

1. For the SAPHanaPurchaseOrders we also create a Mock application as we did in 2.2.2.


- Hover over the **SAPHanaPurchaseOrders** record to the right of the preview icon, and select **Create Mock app** from the menu:


![](https://lh6.googleusercontent.com/qVv8Qr8Cqh0G9qMzJhzfJcuABUh37bQbS1ZAhaQ1jd5YBBjes0Dlxo-DUxGkZFWIhNca28E5SYxeMVYNlmhzV7B_6OkCWUFuoRbm8i7Zl9sw8_THrHnoJ9RV1xGLoTHa5wVRUuuI45YP9bFkEzlUnR2LRgmvHrC4GJjDfCRJrj6QF9HrJaoU3Ecmgw)

- Create a mock app by clicking on the **Create** button in next form:


![](https://lh4.googleusercontent.com/L5vnWT-9dXiJh88zD_U-jHL6VX8m-dRDeUzi-NemvEY4U3-2i4Dat3PKkbn8_KtEkn0p01mj13QFj8VekE-8Mm9QQlcjUHszUpFlW4H-GItEPwcixzYa7IbCo8tUK1pT_PPRKmGrAtYaDincFQQZ1WI0nfmmvenvxNooWyVgLFLLR86Mq3-JwBRvHg)

- Click on the **Simple Mock Responses** Tile to specify the response message that the mock service will return.![](https://lh3.googleusercontent.com/bt6wGVwBkg2SLwGqu4FmxY4ckvbk7hzTppuRFdVesXNn-fauB46DpwRSIpKgX580uJXnZSaFgjnQRcVr-LdLTAbz0cEBYGWSEK8qAsPh_DF4s8VPlxUlGzDS9_2IQ7V2pa7QByOHPSYLWMr6C03TZdPgpwatkT-aHDoXrLh4pHojTc053avV9jzayA)


In the Edit Mock reponse wizard, copy and paste the following .json snippet

{    "d": {        "CreationDate": "/Date(1472774400000)/",        "CreatedByUser": "CB9980000027",        "DistributionChannel": "10",        "OverallSDProcessStatus": "20",        "OverallTotalDeliveryStatus": "B",        "SalesDistrict": " ",        "SoldToParty": "17100001",        "TotalNetAmount": "353.50",        "TransactionCurrency": "USD",        "SalesOrderType": "OR",        "CustomerPurchaseOrderDate": "/Date(1472774400000)/",        "OverallSDDocumentRejectionSts": "A",        "ShippingCondition": "01",        "IncotermsTransferLocation": "Palo Alto",        "IncotermsVersion": " ",        "SalesOrderDate": "/Date(1472774400000)/",        "HeaderBillingBlockReason": " ",        "SalesGroup": " ",        "SalesOrder": "2",        "ShippingType": " ",        "IncotermsLocation2": " ",        "DeliveryBlockReason": " ",        "IncotermsLocation1": "Palo Alto",        "AssignmentReference": " ",        "OrganizationDivision": "00",        "PurchaseOrderByCustomer": "John::Fisher::jfisher@acme.com",        "SalesOrganization": "1710",        "IncotermsClassification": "123",        "SalesOffice": " ",        "TotalCreditCheckStatus": " ",        "CustomerPurchaseOrderType": "123",        "PricingDate": "/Date(1472774400000)/",        "CustomerPaymentTerms": "0004",        "LastChangeDate": "/Date(1472774400000)/",        "SDDocumentReason": " ",        "RequestedDeliveryDate": "/Date(1472774400000)/",        "PaymentMethod": " ",        "LastChangeDateTime": "/Date(1472774400000)/"    }}

- Click **“Save”**


![](https://lh3.googleusercontent.com/5hsHOdBTITAhySgBcuLb9ejoiGGbjrnH1dVaKutY_SurIlOK0uBOMGw9ObRAGQ15-B7t7HqFkm_QklFmbhva5eFZ4d1avR1elCJooUxH4meSlnensZqeDRxWx6-WMSb9UuNC8N7Bp5hjXZofrl1XbgHZ6EdhXsmGm3fnk71XbidX4-NZF_1JiFDkqg)

- After the save action click **Update Mock app** in the top right corner.
- Once the mock app is running again, hover over the **Endpoint** link, and select **View and Test** from the menu:![](https://lh3.googleusercontent.com/XNu1_PM3TUonZYT-Klb8mSoraechpFqXexgGutOjvyyVDEC9TqaBzrAc3FjglESPXzHuCkAyWqCO5I9EERO6gaE7bDy9hzI_WV-iLb1oIHs26zj4KiO6HZQYDVvwUnEkp6PEBYj95LZSUBRUItEzUIzQdG8WYR9zyn11IbQd7TkH8XlN-BYiJ0rAQw)
- Verify if the mock service response is as expected.


![](https://lh3.googleusercontent.com/qtb1hIWjSw3bS7bOl6QDb6YLcKfseJ01KsFu800G7oKLzw9oWZlCubj5QCetZWo8vfFU9B9KANNcMk3DWalqwM0YXE8Cz4grx35Op93E1jl8_X-b7nHz3Lp9w75T1s-0c_mRni4ZvCOqe2rkg9UvepP3AkkQITxdfeVAcNIYT6zL9tPrkWjfkGH9ng)

- If everything is fine, we can change the endpoint visibility to refer to the Tibco Cloud Mesh. This will make sure the endpoint is only available as a private endpoint. To do this, click the **&lt;**** **icon to navigate back to the API overview screen. From the menu on the top right corner, select the option **“Set endpoints private to my Tibco Cloud”** and click **Update**.![](https://lh5.googleusercontent.com/rTd06DgS2ga96G4tEb83oC-RwCRfZPUac1l-Rj5hea9imwMgBNEyDyovg0Vggnz1TPFhOTyloB07hcZFjKM2mrNIivthoIOaXm7gARSY2Cfixj5nuW0XD584ioC9Uw461iJZMS9CuEZBAEaVq9-2fr93V_CrYQtx5d4z_XpWsPXKYApr9Bv6_dB1Mg)


## 2.4 Additional Reading

- [How to Model Your API with TIBCO Cloud Integration](https://www.tibco.com/resources/tutorial-video/how-model-your-api-tibco-cloud-integration)
- [TIBCO Cloud Integration - API Modeler](https://integration.cloud.tibco.com/docs/apimodeler/index.html)
- [My first API with API Modeler](https://community.tibco.com/wiki/my-first-api-api-modeler)
- [TIBCO Cloud Integration - API Mock App](https://integration.cloud.tibco.com/docs/mockapp/index.html)
- [Testing APIs with Mock apps](https://community.tibco.com/wiki/testing-apis-mock-apps)
- [Meter Data Service API Mock for TIBCO Cloud Integration](https://community.tibco.com/wiki/meter-data-service-api-mock-tibco-cloud-integration)


* * *

# **3. Build and Deploy Your API**

In this section you have two options:

1. You will import the exported Business Works applications into the TIBCO Cloud Business Works runtime environment.
2. You'll push an app implemented in BusinessWorks from Business Studio to TIBCO Cloud. The lab instructions for this part has been added as an additional lab, since it will require the install of a local Business Works Studio environment.


Functionally, the app implements a system API that gets purchase orders from SAP Hana.

After that you'll create a Flogo app that implements a process API that creates sales orders, by first invoking the system API that gets a purchase order from SAP Hana, then invoking a system API that gets contact details from Salesforce, and finally creates a sales order by invoking a system API for SAP ERP.

- BusinessWorks Apps in TIBCO Cloud Integration


- Option 1: Import the Business Works Application via EAR import.
- Option 2: Connect Business Studio to TIBCO Cloud


- Import a Project in to Business Studio
- Push the Project to TIBCO Cloud and Test It


- Flogo Apps in TIBCO Cloud Integration


- Create the Skeleton Flogo App from the API Specification
- Implement the Flogo App
- Push the Flogo App to TIBCO Cloud and Test It


## 3.1 BusinessWorks Apps in TIBCO Cloud Integration

### 3.1.1 How to Do it: Import the Business Works Application via EAR import

1. We will import the EAR export files and the corresponding manifest files into the Tibco Cloud Integration.


1. In the Integration Apps, click the Create/Import button![](https://lh6.googleusercontent.com/EBOQ2zY4Chrr9oVVXc1tCTPxg98RfIeP-Pq_af50HCBfgzacrs47F1MZX0hw7IbKhRm72uOiNmvPnRi1SWi2vHpllxG7KPkqyAgQSS776xMpkYBtzgcpjL6dGixgLFPtjhFrq03Y_UaDTQK4_1hBQ5lW03PfmUTf17TwsS8N_H6HUI30NOrcakfUKg)


1. Then select the “**All app types**” menu option from the wizard and select the “**Import a BusinessWorks app**”


![](https://lh6.googleusercontent.com/XIpYrjWCZZOZMNwZHGMPTEssh0VQKq2q0MTJTbUzvCfAgske0p7fEJAZxbFCojDvpNNy5Ivem9Di-hr8LFQfrQJyU8kQjklK3mO5So3MyDPgBG7iMgQtFWcrT3fFOvkd-4f9sVGClQBz4rtCpN9Q1XkwpCRDbRezO0ztIq1QTy9CtXkCoBKiD5EtBA)

![](https://lh4.googleusercontent.com/BkEKE_Jh5stSCcnsv_BpDQ98DOP4dB-E2YPWw9LYv655Lt2VX6PdGZwVUO4u9kTX799dMocPoDlZq5SwazFIapU-vbGffKVEoRBzhy-f7LdzrtkbqE8vULZLuz7PQA3ABZWCvbapVEPIynQb6lx-73TxZVHIXAG9B0dR_VKNr0T8ubUX8ffoMGgW-Q)

1. Select the following EAR- and manifest files.



| Service | Files |
| --- | --- |
| Contact Service | [SalesForceAPI\_1.0.0.ear + manifest.json](https://github.com/MLEIJDEK/tciworkshop/tree/master/src/bw_projects/SalesForceAPI_1.0.0/) |
| Orders Service | [SAPOrdersAPI\_1.0.0.ear + manifest.json](https://github.com/MLEIJDEK/tciworkshop/tree/master/src/bw_projects/SAPOrdersAPI_1.0.0/) |
| Sales Order Service | [SAPHanaAPI\_1.0.0.ear + manifest.json](https://github.com/MLEIJDEK/tciworkshop/tree/master/src/bw_projects/SAPHanaAPI_1.0.0/) |


![](https://lh3.googleusercontent.com/kCBP2b1-IdIzz1p1MTSxumKo7JVtr50ee6FB6ui6GfC0M_R9wptiAIwTxdbMEytP0_cGZlyn9RfcW3lM3H0uN0G-tK05pE97VzI-vZv-WSse_qbo3xAr6kfC6dETzYxpSZFVaCVkZvlQyJV9WVDRiwfIXGxWU-u5jTaKEa6PVDjjzw2p50OcBy7vOA)

1. After successful installation of the 3 Business Works applications, your screen should look similar to the following:![](https://lh3.googleusercontent.com/yp_MMg82yqQRaMG1GoyrYLu6nizzOYgA3vNsQ4BJP3wkea-_CAjNmTZyvISuJ9SSIKwKoOl071CY_9sZvC-q5ztUJEMcZyrzg567pmpgkgyDRrKaOkRWDgUlI_IiX-hfoF1PZmoSgrQohE73qnLGaKiFWicF3uHv9SepzPgLVzAKPREPboUnEDlfpA)



| **Important Note:** The trial subscription only allows to run two apps at the same time. Therefor we will use an API Mock to simulate 1 of the 3 required Business Works solutions. |
| --- |


* * *

## 3.2 Flogo Apps in TIBCO Cloud Integration

In this lab you'll implement a process API that creates sales orders, by first invoking the system API that gets a purchase order from SAP Hana, then invoking a system API that gets contact details from Salesforce, and finally creates a sales order by invoking a system API for SAP ERP.

You will first create a "skeleton" Flogo app from the **SalesOrders** API specification. Then you will implement the flow with the 3 system API calls, to finally push the Flogo app and test it.

### 3.2.1 Getting Ready

To be able to create the "skeleton" Flogo app from the **SalesOrders** API specification, do the following:

1. Navigate to the Integration Apps specifications by clicking on the **Integration** hexacon in the main menu.
2. Your screen should look similar to:


![](https://lh3.googleusercontent.com/yp_MMg82yqQRaMG1GoyrYLu6nizzOYgA3vNsQ4BJP3wkea-_CAjNmTZyvISuJ9SSIKwKoOl071CY_9sZvC-q5ztUJEMcZyrzg567pmpgkgyDRrKaOkRWDgUlI_IiX-hfoF1PZmoSgrQohE73qnLGaKiFWicF3uHv9SepzPgLVzAKPREPboUnEDlfpA)

### 3.2.2 How to Do It: Create the Skeleton Flogo App from the API Specification

To create a "skeleton" Flogo app from on the **SalesOrders** API specification, do the following:

1. Click on the blue Create/Import button, this will open the following wizard
2. Select the API based Integration option from the left menu and select your SalesOrders API specification.


![](https://lh4.googleusercontent.com/cO9EMzGMqN4b-Hx3QX4R75nKnyM5m576QH0O69NvrroV-DYpFwGN6IIhZQDA3GAZLK6Z51VE33I6ooAtJCDvMTc24n0IXiwcg63v_bRu0YkmzPEDKS-UlAmNUPDLyR0erZ-jPTqssJ6XQDZdT0DU2pOBrVxJ461WQJmMxJnThe0f0RwHmMRR0eKS3g)

1. Click on the **Import OpenAPI spec** button, to generate the skeleton.After generation, your screen should look like this.


![](https://lh5.googleusercontent.com/tu7SgA7iEoSKagsR0V-Cih3gpljRrdJ0nGf4do_ij8VsvACxcsxJ53IALn1n13hZg5Xf_MM-2btWjPfOItTK41QqnKvQMxsY-R6hMJC7Xw17LjOR20HgSQp6vw5RY3QFwQ5pr0f-XeQ0QsvVBjPCDCzowNGuZjEagi3vEay7hQ5VLUvrUooLKO22Qw)

1. Click on the “New\_Flogo\_App\_0” name of the integration and rename it to “**salesorders\_1\_0\_flogo\_app**”.


### 3.2.3 How to Do It: Implement the Flogo App

In this lab, you'll create a process API that creates sales orders by making 3 system API calls. The address of first system API call is the URL of the BusinessWorks app you have pushed and tested in the previous lab. The adresses of the other API calls are from apps we have already deployed, and their URLs are specified below.

To implement the process API, do the following:

1. Navigate from the app **salesorders\_1\_0\_flogo\_app** to the skeleton flow **postSync\_orderId\_POST**.![](https://docs.google.com/drawings/d/slOtNSQKS-I71Iyil0r8ZpA/image?parent=1ww6ZDEVSSYTpPvQnRchtAP4vJfpXYGd9VkDc60bSPe4&amp;rev=1&amp;drawingRevisionAccessToken=eht00QruK6H9lQ&amp;h=138&amp;w=568&amp;ac=1)
2. To enable data to flow between the trigger and the flow, you first need to map the trigger output to the flow input, and flow data to the trigger reply. Click on the ![](https://lh5.googleusercontent.com/cNwMG_oIjz5PTXfH5cTx4L5NDBAW-DH4OQZgC5HuTO9H4-hNecz7LKrc-ksxCqYBsGVuqwPJ3LPdBWltY92GLecji0QCVPDodeJYtxP5gXS9dK4xN9u-f7QUZ1hsHbyKA4GjrAizcdsb6s__yV0zYIMxyG0OkaWeEUH3tqeGQgFJFFKcnEho4eQQYQ) icon to open the configuration of the **ReceiveHTTPMessage** trigger.
3. Check the auto mapped mappings from the trigger output to the flow input as follows:


![](https://lh6.googleusercontent.com/rNTKlJ2yfayjWaV1jj87rEN47VzzQvF8TZAlSqniURqp60oENcrAedlIo9VaXiLZOQYq9eRjkJAZ_kOUTsFYlO_6fscPveuevfcr1WnqrFrMVmIaMC0F4RiwiddhQr6056tpcThAJ7PjBx_4cFQRYdaSckYZop9p4HLvCDpz5rMuTB-HS6AMSEe02Q)

1. Also check the mapping of the flow data to the trigger reply as follows:


![](https://lh5.googleusercontent.com/roUF4h0RY6HKexXhT6h3BdhM9JdhhQEN8NVhL0MywyeFuJecLkhXW6WogcoyWncOZEPiYpo7HSt0kU8BNAlVk_SHN_WwLOm8mDpZy3jRA_fpXRMq48NNfVe0i87oFt4v6ySwL5MJbi5n1Lq8vUFBNFG7U8S5WrnIZqHhu-T85-gXpmIeCzfoG-Ophg)

1. Close the trigger configuration screen, and move the **ConfigureHTTPResponse** and **Return** tiles at least 3 positions to the right.


![](https://lh3.googleusercontent.com/8lXkEyQNcrstnqVIIL0j9JUyzMDMdlm0kX9kySJCkLDW0CbNzZzC0p1ztkaZRt9vD6dS_69ykKiHWhewaAHJjPiZ_d6ZF2UQNN5P2Rw3aU3SVNMFE90NYaNb539CZGhz0COXX2yrs3FxdywRXa2T_FtCuVpL7uAvWh5Pb93tPQg33mpb6-Y-ZuIkXQ)

**Creating the Activities**

1. Create a first activity, by clicking on the left-most + and navigate through **General &gt; Invoke REST Service**.


![](https://lh3.googleusercontent.com/Sagq0aVdx-D_8RkWbOGrP8KNejBMb8QQrEwwT-3ApMZL2Vw9W1FnlsiX8GoO1ZaA__fh05Ti-SmsRlNunouEow1QCcrF4NSpKkQTKJ1T4EZfYJWuMtJ_npaMENF1uKp3BqLjG_Kb9XYdMY876nJP17s979QE3Kq2GFjKqHZ6wWQVCLMige9WyPiWNw)

1. Configure this activity as follows:


- Give it a name: **GetPurchaseOrder**.
- The SalesOrder Service that connects to SAP Hana, we will retrieve from the Tibco Cloud Mesh. Select the **True** button for  Discovering Services from the Tibco Cloud Mesh. Click **Browse..**


![](https://lh6.googleusercontent.com/9TaIOEbAapjkoXY_76ktwgOGevcvyX_SrsU5zcBHWH4JaysyfslKsW3apB9Z3p6i-WoaL6tbhDJj24sloInx_BBO3eawJOEPZEQgLYMZjOG-yn3n6foHEuQEikaKHF-vF8uxrPJHgacdsxQfpgtjixd85BwEpzGp-U5Duk_AlgD5Z_7X61DJST4_lA)

- Click on the **SAPHanaPurchaseOrders** API Definition from the list. In the next wizard screen **select** the operation.![](https://lh5.googleusercontent.com/k0OBCR0_64G7YC6fJ_Q5qJ7YYyNpUDRfKNr_NiFCLIzZaCjpoGao95dVNsLlcjJ8uFH2tfpLz3ftv3mI13ptp1FTkZfrWlM-GXTyXSukSJU_Cwcwpq5xgWZ9K8PzaT_ts70TLV4X-wSJvUUsiu82rsnFoxNzBeC1hwjS3UoIJ4QhFxNO49eTgsi_gw)
- In the **Input** section, create the following mapping:



| Activity Input | Upstream Output |
| --- | --- |
| pathParams.orderId | $flow.pathParams.orderId |


![](https://lh4.googleusercontent.com/gMwqR9RmcdDME1Pc7aYDWDBOK9Ts5RtjaTnx4ncxUzK60U-2qrCnrDTKWevVq1Ty-VawZoRY-bXVJLTntmPtXK57n2Np_NHvi_Ly5rCZhzTj0j1fXsk_wjsKwhBD7gO2YIw8vbvQ0akcc_rB1bwME9P7RozAed2OAQqZy141j5zLATPDHMCUnGeKcA)

1. Close the activity configuration screen, the integration should now look like the picture below.


![](https://lh6.googleusercontent.com/pPaNosDIQnrOGZNDQiwqj0DTqEv3JN261NMEQ9lPOWzFlPVygxNYCNzrxRUqd28VksfA6qitkUqw2_nBvEWpdpJY4YaYUE0NOZyuGDjSMyCw8oIo3mgIiV1q5F9saZ6kh2dNMJHESR4oeh0tPntKFXCkKm4rQam-gnowJ9QKpr86IL5Nb2D4EWuzVg)

1. Now create a second activity, by clicking on the next + and navigate through **General &gt; Invoke REST Service**. Configure this activity as follows:


- Give it a name: **GetContact**.
- The Contact Service that connects to SalesForce, we will retrieve from the Tibco Cloud Mesh. Select the **True** button for  Discovering Services from the Tibco Cloud Mesh. Click **Browse..**![](https://lh3.googleusercontent.com/o3maS0rxU0KjG8AOfROXRbvemEont7aSb0-k-d49m01rECwDSMXhQ-SNnSCnVhI24p2OulF0Xs3ZNgMbj8Mv86WRwpuP62bv_dhpuvEyOmtm03pmvpAOdk_H-mPdcBJsbzgl29JQN7VE1gzpHipBz1wdnwy-vpaPBQVcPet7RmLL94DiYPYQDXk2Wg)
- Click on the **sfContacts** API Definition from the list. In the next wizard screen select the operation.


![](https://lh3.googleusercontent.com/oFJQT4xjUQ5hffnP50nqsXhtCLQQ_hj-R6AnXvpEqh2vK2543_0jwwBtjvaly4tnffaiAiLmfjbuAW2sxoAbSJHpbFbOYQsffLoQLG6HrUUG45hrP135UR4oX74ZvbAwzdVMfORYxyZ93Jfy2jSJTIMXegikkbWPxYX_rxWXvHXMxRjPd30qyyGxcg)

- In the **Input Settings** section, check the imported query parameters.
- In the **Input** section, create the mapping.



| Activity Input | Upstream Output |
| --- | --- |
| queryParams.firstName | string.substringBefore($activity[GetPurchaseOrder].responseCodes["200"].d.PurchaseOrderByCustomer, "::") |
| queryParams.lastName | string.substringBefore(string.substringAfter($activity[GetPurchaseOrder].responseCodes["200"].d.PurchaseOrderByCustomer, "::"), "::") |
| queryParams.email | string.substringAfter(string.substringAfter($activity[GetPurchaseOrder].responseCodes["200"].d.PurchaseOrderByCustomer, "::"), "::") |


- The first mapping we will create manually using the Function wizard.


1. Select the *Activity Input* : **queryParams.firstName **and click on the Functions button.![](https://lh6.googleusercontent.com/fXkoalOTySY3DOwYcCpPrpbYPQsUmrHxIQYxaQu-ORUkBpa3cvi-z2dj6JpV_Ve30e6Ng8r0rGy-jal0Cf7L2z77nvhge6uTRrM8aEQBslgqjaSMdEL6rNRJlphsF5vvzNPNsfZkfdrphutmaVEcfFDFG9q6DtMaY5CgmjKilRLS6X9zBTuVo-GOGQ)
2. In the Functions dropdown Search in the string functions for the **substringBefore** function and select this to drop it to the mapping area.![](https://lh5.googleusercontent.com/jUYSoXi44rvqmrrXbCNMqnYxugghKX9NVDUqQB2EXu044ae98ihREVlO_Y35LYfTNxcLDUwx0Hjo4xBTu4suVK5HI8SzNF6HVMzGHBCwjpBPF8ooEpkY_Ka5qF8cXo6sJcvDiIwDAn48XjetwZZ3H6EF28bEogO6DhFOQQcd8H41jZPQDbGqZqjhJA)
3. Set the first string ***str*** parameter to the PurchaseOrderByCustomer field from the responsebody of the GetPurchaseOrder Activity.


![](https://lh4.googleusercontent.com/fECdeOg42-H8itW3-fWraVUiGO1UlsNrgHTKpNfoqeVdbrrkiDxf73QJU-YErN0qDxC5rp-pDnAh1WkKaUxUMkaHPdgiUVe8BY8q6S4TRorakP5JD6CXAxAxKoywYd8hKmCOjAAsU3TfEL9Y-IQradPEGP8dWIhfm1UHi74LSkHy_m5RWSFAMJ1xIQ)

1. Set the second string ***beforestr*** to **"::", **by typing into the mapping.


![](https://lh4.googleusercontent.com/jbZv9ol-7W08bI2lOGiV7_Syo7Z7YoC9n9i52IlClkJp39OdNkeWpqKT8ylFmW-7UbJ8G93cT9ODlmeyWVy_jobplwwdn4AA60rOkgrqqGjtNnV2UOy51n4eboBYsRk0_MlAx_lLFnG1sElmeg62uxsmS8RFpvlFmRdwB5E2i6gwP6j1QwT77QZIqQ)

- Now create the other two mappings for the other two fields, by copy and pasting from this table.



| Activity Input | Upstream Output |
| --- | --- |
| queryParams.lastName | string.substringBefore(string.substringAfter($activity[GetPurchaseOrder].responseCodes["200"].d.PurchaseOrderByCustomer, "::"), "::") |
| queryParams.email | string.substringAfter(string.substringAfter($activity[GetPurchaseOrder].responseCodes["200"].d.PurchaseOrderByCustomer, "::"), "::") |


1. Close the activity configuration screen, the integration flow now should look like this![](https://lh5.googleusercontent.com/okJ_qs05QVgWCr2prE2ZL9F7q5YhKhdMSsS66L-QR_SZfkSGMTHnKyp_eEOE8Kx0hkkwt_ppMjkyILX-sKlScdhjcZq2FQqeffdOYzY-49wLRdcS7IkVupUDcy2_Ca6wW1Ux4eTtnDXSo0ueEAXaX6cHDCx0TpPec3mgY1eZFECzZ0ZU8E3qmRM59Q)
2. Now we create the third activity, which corresponds to the SAP Order Creation Service. Click on the next + and navigate through **General &gt; Invoke REST Service**. Configure this activity as follows:


- Give it a name: **PostSalesOrder**.


- The Sales Order Create Service that connects to SAP, we will retrieve from the Tibco Cloud Mesh. Select the **True** button for Discovering Services from the Tibco Cloud Mesh. Click **Browse..**![](https://lh5.googleusercontent.com/WHOHYbZIwLYAtqQds4XZMqUOU1eqYTIdddur7RRPzbzqzSNfJuiGybUcuxiANzO2XrTSFE7fqgzj8kZwaz8_qNsrDlrnLvuH364Tm0d5h4IaTgPe6Hnu6DGS0ijLB-Umak1O_ogyV7510v3sQrd_ec2B5bEyEG-bp0QxUX7H9QQ1C6c4PhjMfkVU6Q)
- Now select the SAPOrders from the list and select the postOrders Operation.![](https://lh3.googleusercontent.com/lN3UKRkONhVduwfURQ1K8oGbFX4raJpVBtNlRnbYhjBUj5K4uzJYTe3_o7cjr9s18CMPX7XrLd1jMIq73qWcBNljl33SuOAy6NwATnIyd5C8ioYJZ1IYi_gN3UycjpGd15KjTePXI9mXgMnGyLe0ppJHWTh-RRw-4KHyp8uQbBp6ZBFCIWBn-PryoQ)


- In the **Input** section, create the following mapping:



| Activity Input | Upstream Output |
| --- | --- |
| body.Email | $activity[GetContacts].responseCodes["200"].email |
| body.firstName | $activity[GetContacts].responseCodes["200"].firstName |
| body.item | "1" |
| body.lastName | $activity[GetContacts].responseCodes["200"].lastName |
| body.phone | $activity[GetContacts].responseCodes["200"].mobile |
| body.price | $activity[GetPurchaseOrder].responseCodes["200"].d.TotalNetAmount |


1. Close the activity configuration screen. The flow now looks similar to the following picture.![](https://lh3.googleusercontent.com/fOzdzDAPVRC_PpOXvrIqAEkU4xVrYd7_Dxo8Q83pWIFLl0MRzlPXVy-pUavgREAOEhJ6ha-jzMhlHSaciFWBA6IWYTJOH5NrATWUW2HHI1wj70gk5pBA5SolDZwVYbUCSb2HTZVOJlgaVB-AXtvvKfcB8c43yAuwwe4rJAeGAhnKkytJi95cJSE71A)


1. Now configure the **ConfigureHTTPResponse** activity as follows:


- In the **Input** section, create the following mapping:



| Activity Input | Upstream Output |
| --- | --- |
| code | 200 |
| Input.body.\_response\_string | $activity[PostSalesOrder].responseCodes["200"].\_response\_string |


1. Close the activity configuration screen.
2. Now Validate the Integration, the result should look something like:


![](https://lh5.googleusercontent.com/YL862J-v1dYuKO8zMQqKPcEke9D0d5FUrstOXOo0sh8ImFBeMYMLuivbWrM5yKWaNKsxm3JOChnsObgR20neV7bdeiYd-5sjgsaTw0t80Bin-hj3B3VBAqhAUVi9JRwDs87Y0T_rR0kimdJ8rkwCUr_nekPtM5SIdv2BbD6i-sp5YRKzAFhDRDqhDg)

### 3.2.4 Push the Integration App to TIBCO Cloud and Test It

1. Click on the Blue **Test** Button to start the Test configuration wizard.First you need to create a Launch Configuration for this test.![](https://lh3.googleusercontent.com/PuSBb_IfwSsF0FG3XEKzpYFXC1VHd5yTNZnbs_nJENJMEr0zSxqxt3i67jumw8dl6ewIadciXyvo8xzow4Yg4ftu6OPz9lnvz5p4U6Bx7XMIajZiz6sFCCEl3-tm79D176F7J-CJpg2tF9EZELT5MmN5n91pbGSNg5SlnEHk2Zfox8lovmaMWFAyRw)
2. Click on the corresponding tile and give your configuration a name.Create a mapping for the integration input parameter **orderId** as shown below.


![](https://lh6.googleusercontent.com/7v6DuJMQSikVS8gHQCTHHkDfN0aPz_GzqaT3qzVbc3l-DdVjPVgIQPCo5xfv3rF7svz5-B8KZcLm4kmTx7i4GAjr-K2q2RlLbiScySlb-FoicSiDQfMj7MrwfHu1Y5vJ6f-eyXYv4lJ2e9s3v_YQbkveajv4fY5INe6uhpAWUw5_k3xJUagMebhkMQ)

1. Click the **Next** button in the right lower corner and check the summary. Now click the Run button in the bottom right corner to start the test run.![](https://lh3.googleusercontent.com/U8jt1yBd3gBvUnAL2A_h0EwCXI5imy9HhUMqsIcSthMK4wnBiGQ4e3osBQPXS18Q6Tf2LPlntKD3yWTi8rUs8qBmZjBGxOSPRKZug4UxHJtPeBiKLkG_xjQE05i0OhhLfi8wDl3PoQa-cVbsTgd2CHxAOPrAIJerEk0pB63zmtQ1E4kFQHYO_4VcKg)
2. Now the integration flow test log will open and show the status of the test run.![](https://lh3.googleusercontent.com/PUjXXEYPRUBDacXQjBhT-UoegYGghhQXMfzzcMwJa_-dqx0-9zMI6dCdO06nc4A3n7mqrceE8p2dpMLtvbQA9Yk_SsrsH-1PJS4PIcOTtLAoHK2gRo2bWPQ9bl2nggfX-fuLE-6AsAK9lvN-jh_t5zNEe7H-Kw1DJt47YyP9Nf0GUzs-ffZ0mQ7bEA)
3. You can introspect individual service and API calls on input and output result, by just clicking on the flow diagram and select the activity you want to inspect.![](https://lh6.googleusercontent.com/HJpg7Cvx5XMS0bQu2FeyZWFiX0cxcNHg6YeP0TwjwTBTzuDzm-OeX_IcIcx9gwUbZ67qA-zrW7zc8Z5Lql6B5Iz9yXnUca6PztMK7R9DFHUTA6BenmWVyGrmW_fgAF3JpRHFVws-2PdvD5Z1zf-Qpvl7lB--f0TX3AHaEYJvpLlIN9ebn8scSfM45w)


To push the Integration app to the runtime environment and test it, do the following:

1. Click the **Push app** button.![](https://lh6.googleusercontent.com/jazw0r4AYuKWXScQHeIRAzboj1KxtTMzbY9p9vtqu5Qeqk05X6EcseraATDubeWQsD58rOrGKouYsNEcJx6ZAN-Yn_kMT_GC1H-h8YEgPtTi3l7ENlWUljtVUS5yQtnJKWLEdJYlImfASYxAhFhFyTreR1q31qTu4pDEeAVjfmcMSXce4zYsp4b2Wg)
2. Now we have to scale the application to start an instance of the integration


![](https://lh4.googleusercontent.com/pw0sE7hLeMRZKSHdmJwfeG2Fj0xbX5HqlXEiVTnuW02K_eSNk6f2QgCAwcKvnQOyOgMQeMN1SgRi2wcEgxo5dXPwgUa9ukWYVOgCEmPkedyRxyOH0fpjZPxE81ZtlY_YFuATbYf56MgeapSdDxu0d0pGHbbZxPsuguaxdidAzlpm6pgzYnRHDAOdKA)

1. Once the **salesorders\_1\_0\_flogo\_app** app is running, click on the app and select the **Endpoint** tab. Select **Test** from the possible actions![](https://lh3.googleusercontent.com/12RaQBXuNk79zkk2ZNehB1wIWVnqZ-7JI9YnTsDhLtGMaF7RPLYuqEvFFAOu9nmLRd-xEB4vfqtjHvx7WKWM1Qc8eCRl_AaKuhp9klTwMkljT0Z7yE3FIZS3kme8Ky0VbLNmKWradY2MvMlQFOSgzxxnBkfE49vfvUUzwX2QSNxd-6CnUjDbZp03ug)
2. Click on the green POST operation to open the API details.![](https://lh6.googleusercontent.com/kLdZeWmjmT2whOyuVOxrC2mEZR3EbRfzvIb3C-lp5lzPy6Tmvut4UMAobT1jk3m6Un09nt_IsdQp4iRX2CkLEMlemTqO3k2UYxEooqJaTc-3Z29wzIBoo3vsRjUaGAXputTu6oQ-Dg8ATatHeech9WOAYdRpkMtWQ343KL1lqDpC7HSWRLc0JUzzyw)
3. Test the **salesorders\_1\_0\_flogo\_app** app by clicking on the **Try it out!** button.Fill out a value in the **orderId** field, and click on the blue Execute bar. Now watch the result.![](https://lh4.googleusercontent.com/ZgvSV07tno2dX34ymDrj_A_nkN4IzGsp7K6Bz8RROMfm5wX5I35n7QmdF3pjEOhO9-Y569GtbcwFAxggY8Y3hz8iXHUbFh9HwMqyTeNv_g5lagVqsr6tTY7sTiofVaKPpN9Dr8_YvR8N4YF0auTJKA7SVShm3WDo2tBXVHMyQW2-xL8caDI3p9V29A)You now have successfully build the Sales Orders integration, that uses Tibco Business Works integrations, API definitions and Mock Applications.


## 3.3 Additional Reading

**BusinessWorks (Cloud Integration)**

- [TIBCO Cloud Integration: Getting Started with BusinessWorks Applications](https://community.tibco.com/wiki/tibco-cloud-integration-getting-started-businessworks-applications)
- [TIBCO Business Studio™ - Cloud Edition](https://integration.cloud.tibco.com/docs/bw/index.html)
- [TIBCO ActiveMatrix BusinessWorks™ Plug-ins](https://integration.cloud.tibco.com/docs/connectors/index.html)
- [TIBCO® Cloud Integration Frequently Asked Questions](https://community.tibco.com/wiki/tibcor-cloud-integration-frequently-asked-questions)


**Flogo (Cloud Integration)**

- [TIBCO Cloud Integration: Getting Started with Flogo](https://community.tibco.com/wiki/tibco-cloud-integration-getting-started-flogo)
- [TIBCO Flogo® apps](https://integration.cloud.tibco.com/docs/flogo/index.html)
- [TIBCO Flogo® Connectors](https://integration.cloud.tibco.com/docs/flogo_connectors/index.html)


**Project Flogo**

- [Project Flogo™ Community Wiki](https://community.tibco.com/wiki/project-flogo-community-wiki)
- [Project Flogo](http://www.flogo.io/)
- [Project Flogo Documentation](https://tibcosoftware.github.io/flogo/)
- [Project Flogo Github Repos](https://github.com/project-flogo)


# **Extra LAB: Business Events Simple Decision Service**

**Simple Decision Services (SDS)** is a capability of **TIBCO Cloud Events. (TCE)**

SDS is an easy and simplified approach to create stateless decision tables. It has browser-based authoring experience without any complexity.

Business (or non-technical) users can now easily define their business logic in the form of simple conditions and actions in an excel like format called as a "Decision Service". These services can be exposed as RESTful APIs for internal and external consumption.

This walkthrough provides a step-by-step journey to create a Simple Decision Service.  You can have one or more Simple Decision Services as part of a single TCE application.

## What You Will Learn 

- Understanding the concept of Simple Decision Service(s).
- How to create, deploy and test a Simple Decision Service(s).


## Getting Ready

1. Extend your trial with a Business Events trial. In the Home screen, navigate to the Event Processing hexacon and Start trial.![](https://lh5.googleusercontent.com/DlpgeuL8lnrOaWW9h3_GglQtFF7MU_IVbrGzcaYZt-bsphJm5dmdz4Prp-tqESS0bkQ8fKWdveM8MaTK0I9ePLSG5kUCNKg8LVGtrC47vBvHEVTnIuDt1_HV6J8aa8L4Tm_KcgjtofFrtPp31RGTqXnH9v1u30cZRP2PsUkdqSRBi1IKOa3doJ1KBw)
2. Follow the necessary registration steps. After registration, the Cloud Event environment opens in the window. Close this window and return to the Home menu. This should now show the Event Processing as opened.


![](https://lh3.googleusercontent.com/UsvQxpFXK0ngBcTJFRQ81y62w1HokZGUsAux_lfbz-hxfiUbe_z0GUOntC_SLFLtlG-G1K7Z3Xg2AQuDJCNjAT96RF2V9FrpFgbhpTKIxtPr4066uBELo7Pg2oKUVjkHKOStALAMj9JOti_5gGh6nf1XTndiTX-U62y2T7h9rc-yKIVcmFSwUfZA1Q)

## Creating a Base TCE Project 

1. Login to TIBCO Cloud Events and select the Org you want to use.
2. Click the Push App button (on the top right side).


![](https://lh4.googleusercontent.com/glWr5Nc-kFb8A8CPfcmZragdtVQ9hYRbH9yYUUuyuK4SX7Fl-lPZGNzSWZWueKAi-ptHwZDsh7Z_cIHIHU0oS2mwQ8YBzJ03vSV7Lafk-SXuqwQGNEFY7z_D0Y0cw4Gb6ktRRp2oQKYkn_8YwyvIV5sCLTRD_E4iTuAMcly2E0oC7n7QA0R9T91UfA)

*Figure 1: Push App Button*

1. On clicking the Push App button, select the Decision Service tab in the wizard shown below.
2. Select the desired Application Size, No.of Instances and the Name of the Application before pushing the application using the Push button.


![](https://lh6.googleusercontent.com/RFMSNmHQhP9JpDYe53vWKRTnkHFLxr-s5lCAQPuD9Mb7Y0rXqcM-OzRxkibMdP8Hx-d1nkSpbu8cPrdtZtMtofZburQRzRNnBz7ysmPARD4Ek9cMPF8djncAkzIR7mzQ6ZgZaWn-mV02mQE4JnUWe-Vybz-52qfyKSLBy-ogQ2uhCs3MAit-LrCAEw)

*Figure 2: SDS - Push Application*

1. Once you Push the application, it takes a few seconds to Scale and come to the Running state. The Application itself is in the Draft stage scaled to the number of instances mentioned during deployment.


![](https://lh3.googleusercontent.com/KaTbt_NGZ0F1w2uK6zwEYRLc8DXC-8NmGpv7thUNCiM1Ah6HYnibVsu0AiJwWjvSft35ZgmTul8FQl_OG7EkySTc5DRq6mNywvT2ZtwBgugmpB4fSXcdUXgvTpGzfkn7mHWTEii6TSCEPVfael9LPEqdgWRfyMSYSY4gh8Me4cqzPZS0GTmKPJiwow)

*Figure 3: Application Push Stages*

![](https://lh3.googleusercontent.com/R1oPbvFN1Q9qQvy_EEdnxuJSI4ZIK3H_5lIzBSxGuHj9vmyHTA8SwejEY2c9HCx9Mot8QdI5Ie-8gPpxyDtuvbxzr0rDyZtYkCy-JxHAkPKH2r7umWcHFZQypxQYfK98dUFtZwJVAR7wfXr581xSAExvTu8r1Dy0Cf18W1pjXSn_TwazsY3nQl6Iow)

*Figure 4: Application Deployment*

1. Now the base TCE project to create a SDS is available and deployed. Let's proceed ahead to implement a SDS now.


## Implementing a Simple decision service 

1. Leverage TIBCO Cloud Events WebStudio to implement a Simple Decision Service.
2. Click the WebStudio button (on the top right) to begin the implementation steps.


![](https://lh5.googleusercontent.com/HQiQ8wwTw1S0hYDqsXM5votLNWSXGmUWnoVaXqMCc37A_fU8BFptmBO3I2Xx763i49GHmCt9QYudhYG644MiqXw0ummUrae2nrYjY_So6JMs0CKe9PTYUc3PObAJHpPkV38EgU_3OMZ6R7N9U8OuYFcoQlrlV654OWyMI5mN4W4VitJUqJdwg7m1_A)

*Figure 5: TIBCO Cloud Events Home - WebStudio option*

1. Within the WebStudio, click + sign on the Project Explorer tab (on the left) and then "Create a new decision service" option to add a new implementation of SDS.


![](https://lh3.googleusercontent.com/RenxvM3gjvKVj7q1OTMg0GzOV2Gw-G7rkbfhC_u0TZXWkDzklmNmsK8ckhs0442eVgz2G_psxgIPa3HRJ9blt6GuvjeTgsX0WVSA1UGsaSxxjE4hULqOLAlypXiWh1i2TsszVtuXy38iBBqHfJLFcoNV5ND3tgZIXx7AFTGT41kUi7fCopLtx2aY6w)

*Figure 6: Create a new Decision Service option*

1. Provide the required input details as prompted by the wizard. Project name from the dropdown list are the ones already deployed as part of the previous step. If the project is not previously checked out, it will be checked out during the SDS creation process.
2. Enter the input and output fields in the following wizards. The inputs and outputs are defined in the form of a simple name and data type format.


![](https://lh4.googleusercontent.com/86BfvzvQntmFmXraR4cMz8duN5726eYn7Aob11OStjT9Up6BNMyfc_zTZcF8WKtbjfhwuDCjMQyIzvDJY6kIj57yRL5PTtBlq9rO1qZ0IpQFhI1Fgqz8hpbq1XBzXVGgI497lpFbRoGv9FxW1EuZERrWj4GBZVhpm2OkV7V8TN7l3JmYpXg_2Niwvg)

*Figure 7: Create Decision Service wizard*

![](https://lh4.googleusercontent.com/uQm1P6EmO1hept3jXkZ0tpJ-Q-fuKWmKLRpZS6lEMKn72S4QhO5Pls1Ex84iHtSAGrnKtvpLG7MX1tTmDLG3b6YM6IqHtcu3g1d40USKgBAvjBS5QclS6naqmPWursDyEgjmSAi40qHBg1VgxosxOUAffP2QAWjigLLMApIpkC85ALYKnJG0FuUgGg)

*Figure 8: Input fields of SDS*

![](https://lh6.googleusercontent.com/sXfh4lmReHSNs2BfqEGlWA4kKJ5-gjfDSAqVWfoyV0irHr33sqgYfnLsMJYZH1tubCPC74JRv1pCCeYNOsR87QysmJupPEn6SpbdJfPczBVnrf55vWctn9F2vC9iSNufJVK0baZJcM90rud4wq9mFZG10GcGS2Q0qTh-SeR6Q6hScpW2EmOYr41vvA)

*Figure 9: Output fields of SDS*

1. Click Finish once the input and output fields are defined to create the default implementation of a SDS.
2. Click on Add row button to add the desired conditions (inputs) and actions (outputs).


![](https://lh5.googleusercontent.com/d1UPMfIGoraJ6v7mN4J7TQ2cKxF7DrR75nudFQJS4czLEN1NeDSUzVQLmrs4g_3I7db-107MTrrC1YL9YJZSWf3NFcKkEA0qQn1QZX_MXYfWEkg86voBVIgyVUYmcbcYBhob-8tyFcBq3M7vHRkSTYUkaO3q4v-GJdOcirRRje3yp1wGmJrPUKQzOg)

*Figure 10: Decision Service Implementation*

Once the rows are defined, click Save button - this will enable the Commit option to commit the changes for an Approval process.

- Commit the changes with appropriate message for the Admin user to approve the changes. The changes need to be committed and approved before they can be deployed to the TCE application.


## Deploying the Decision Service

1. After Commit action, the changes are available for Admin Approval process.


![](https://lh4.googleusercontent.com/87cM7_SBj0tKDk64WLXts2IzgYJsnXgYTtIiwTQs0S51US4yAbL0Q_5-8-MpanWOHV0YxieUlSyo5bemol2c5htCGQx-zBl3S-p2DK7UeSPeZq_Csb_Exa5SKf8LPSQbbTQ8AMzUjvnTB17EQfqlbKuRlcqznEGdx_dZgbDPdVuIhlDzrBfxZC9jtA)

*Figure 11: Deployment Dashboard*

1. Admin user can click on the eye button on the left side under the Recent User Activity log to Approve/Reject the committed changes.


1. Once the changes are approved, under the Project Snapshots section, left click on the Option menu (3 dots icon on the right side specific to your Project) and select “Generate Deployable” as shown below.


![](https://lh3.googleusercontent.com/TcgsQV0Aj6YZUE763usOwkluXuCBWulofaNCQBL_moNPEmISWeU_6y5ceb-x_lmgmp6KTJyivLQn59Jx6ePwU-_hq2NwYy4M5GyJuF8GWJNHaD7P8NZ1df9VYkn_qLCzbMWqZO42M5D9SN9ADAGJmYn3NZ1URxldi_Fzwx2fninmBolXg324WElX3g)

*Figure 12: Generate Deployable*

1. This step generates a deployable (an EAR file) for the project and hot deploys the changes to the running engine. No need to redeploy the changes.


1. Click on "Back to Home Page" option on the top right to view the endpoints of SDS.


![](https://lh4.googleusercontent.com/EboHRUdVA31ZYLgU8_GMHDEmuwzRaVa27Wsd1drhvB5VPpzGN_Z1WmeGDMfM45QlsJ4qY-5apU3Gd2h6h043qlBMTzvBzqK4nifUykEQVtxaDcEMP4JuuTRfrUKk0r3Zya0QgK016haEI67ujMKWwe7R647Sfct8kZe3Uqozw2FPpZqKTqFkEyIPJw)

*Figure 13: Home page - view Endpoints option*

The next section describes the steps for Testing the Decision Service.

## Testing the Decision Service

Once the deployable is generated and deployed, the decision service can be tested using the exposed REST API Endpoints.

![](https://lh3.googleusercontent.com/syDhXC4GN5eTVpP4hNOYYeqsn-fAI_KEDuFOrVyegeqD_jbRx1CLFgDNlJxOS4tBufnmKpqe92QTcP-dIGPeSLg546pJXjikuDawRg3WAIwyjg8uUXpwxjduu1x8wdwiIkVzOofBeeOz48Htlc7iroUyktxz6QP7rtaMMx3UGrz_xt3cQevwIcu9Og)

*Figure 14: REST Endpoints*

![](https://lh6.googleusercontent.com/U2whsUjlTwIS2iS7Xhy36cqUBaZwUNoOQaWSIPk1VXVYB0YAfUIFVv_XQ2YmiHfGLcXJmDVb1W8BjviWe43Un8Vv3By82uO0NH4X0tnF3JeQrBtUdyCaBVOkcGw0S-riq6G4c3Xi7JLwc1eBNnHYNuPo3-qjKCpbDbAQJ3Ork5tMGDhVudg45zgSqQ)

*Figure 15: Swagger Client*

**Note**:

- The serviceName is case-sensitive and expects the name as entered while creating the decision service in the WebStudio.


- The input and output  are both in the JSON format.


![](https://lh4.googleusercontent.com/alxsjtbpi6C2hKOvhi-sOHqyEjimkFhox-gI7nfXdAPetWL1zbg2kL4z9hMkTFVOnHQdQcaXUKi8p6RURtQou4YeCssC5HxrxNzNWL2brVX45l_7POJl42CPiVikVG8VAfzG0q1-q5s2BpmMNdCu7lBgxseTTEQXpXbZD1s8ba5QRHTjVpWE89PDBw)

*Figure 16: Swagger Output*

## Summary

- As you've noticed, creating a Simple Decision Service via TIBCO Cloud Events is straightforward and provides a strong rules and decisioning capability via REST APIs which can be easily integrated with any other systems or applications within an organization.
- For any feedback, queries or additional information, please reach out to [mailto:support@tibco.com](mailto:support@tibco.com)


* * *

# **Extra Lab: BusinessWorks Apps in TIBCO Cloud Integration**

In this lab, you'll first connect TIBCO Business Studio™ for BusinessWorks from your workstation to TIBCO Cloud. You'll then import a BusinessWorks project into Business Studio that implements a system API that gets purchase orders from SAP Hana. Finally, you'll push the BusinessWorks app to TIBCO Cloud and test it.

## 1 Getting Ready

To get ready, open TIBCO Business Studio™ for BusinessWorks. Assuming you start with a clean enviroment, your screen should look similar to this:

![](https://lh4.googleusercontent.com/btzR702-Biwh-ehoT9PTJ5jFYntW8IESG0z5bHqPKnkCvP-QpfQo2Vq3pLNanVgw2x83_e8QayMj97TkP_2FHbGZfPt1f1XOb-B8KPpM53vCjDm4gvgWzImmcFS-yTxQDokCUjx8n_DibqdBrSszGEsaBwy3JTkUKeJetH5OvQ4j6iZVRiGsVyxYGg)

## 2 How to Do It: Connect Business Studio to TIBCO Cloud

To setup a connection from TIBCO Business Studio™ for BusinessWorks to TIBCO Cloud that enables you to push an app to the cloud directly from TIBCO Business Studio, do the following:

1. Go to API Explorer, click the down arrow in the upper right corner, and click Settings.


![](https://lh3.googleusercontent.com/kyQpyBwiDDfIobEKEVAj0a8ZTC99vvJu7TrttP2X0AGqzNjQLVh-QoVJ26xVic3FQj8f3NFsPXVjA5VX2Xat8fJhhlzpJBj23-y0BPdJIV0wI166vwCHqigvQ8JhslK-K8YVpFMkk58rXofiOVtnRBnJu9eRipXqvJFQQf1TJBJnx556N5Sh7_VlLw)

1. In the **Configure API Settings** form, click the **New** button. Fill out the **URL** and your TIBCO Cloud Integration username and password in the new form.



| Field | Value |
| --- | --- |
| **URL** | https://integration.cloud.tibco.com:443 |
| **Username** | your@email.com |
| **Password** | YoUrPassWoRd |


1. Your screen should look like this:


![](https://lh4.googleusercontent.com/SDQv6RPHo5TA-PKhUcTt8RvS19wow_6MLb_MIw7643EOBZvGRj9oqU-NdPyY6oWJNGSNqlG5yBRcUc6LlflglYYe5kVnkHG_Lr-KP8UVqlPWuU3vq9HjMD4sGmMke6cKykbIG9H3dkqDuKQH86NvLFMyrafx4foeNYSOZcklQTecffXSU5VRDmSWsA)

1. Click the **Finish** button when your done done, and click the **Close** button in the **Configure API Settings** form. The API Explorer should look like this:


![](https://lh3.googleusercontent.com/U_ODeAXgsBPQVCV0F-pgrUduI6hdEmHem-J1roraYLjXWL5O8ioNM5eULpXCSngEmq_mKQ9jb5SihxGJdxWlA8Zin1zfmoz0aGqNPFGnfggx3hlyYd6Fdh5-3bAjC-RaGfPzVMAutevmcigo9RNhiibNMDORJir21Nd3N1-ImW0CV4zbgNbRXdeHGA)

## 3 How to Do It: Import a Project in to Business Studio

To import a BusinessWorks project into Business Studio that implements a system API, do the following:

1. From the menu, select **File &gt; Import**. In the new form, select **General &gt; Existing Studio Projects into Workspace**.
2. Select the [tci\_workshop\_stubs.zip](https://github.com/TIBCONL/tciworkshop/blob/master/src/bw_projects/tci_workshop_stubs.zip) file from the [src/bw\_projects](https://github.com/TIBCONL/tciworkshop/blob/master/src/bw_projects) directory. Your screen should look like this:


![](https://lh4.googleusercontent.com/R8nO1FXn9Ach-PQmPR_sVheZLqj1up34znXI2mY8z7NZbPS3Cu6CXjBsY_Ba6aHjo1V_PWY-KMbU0wSAsLzKeUv9b6Q5ugnw3_zFy_tNDnmYGcddxtkJlFLeHDzmcJjwITOP0Ff49k6mhm026iEoHUTxJ85qS29O-NLuvSlnAdCuaBkQmQjXKVY1Ow)

1. Click the **Finish** button. The Project Explorer should look like this:


![](https://lh5.googleusercontent.com/ujNk7yhQnLEX53UJDRAF8ovn7ScHznJtlTsUmV_zMdv9yd_-coIwQbjWzv2_3UCsSwqrx4xXHBoYhdoEzPDg_q3aLut7n3sE_J0xVk_8zD3bZZkl8RgvX5CRJtZeKy1_vKxaCl3f9RCFbaO3tDok8GPIqUv799cSgd2CCQfhHnO_PIdAU9MM-eHJ2g)

## 4 How to Do It: Push the Project to TIBCO Cloud and Test

To push the SAP Hana system API app to TIBCO Cloud, do the following:

1. In the Project Explorer, select **SAPHanaAPI &gt; Push to Cloud ...**:


![](https://lh3.googleusercontent.com/6pVDudneqogPTZWYPu7LHDz3r_b8U8A_CH0atKJzSQEDm-wRn_D0RT7Y7cyOZtftYW_jqDOowY5e4ZFIjrU69HcEckQeZno_lvXgMWkziRbRndVXCl_XZgO8CGUxLMHZClYrKX8ciyTo4motSPPH33FgkRl4hUCvn9My8vdji4p2ZoW2XsGqimaqtw)

1. Navigate to TIBCO Cloud, and once the app has been successfully pushed, your screen should look like this:


![](https://lh6.googleusercontent.com/BI1JvNkJDlBPmQ2emmvyAKyrDr_M55hKfcZbt7iU6thCdAWX-4Qs7fxOGlXVolbAbl13ppMOf2qYmOd3gfgtcEuLKXen7i73gA_IL6V7abxNaAtVHTMRMTPNgVFHBYbGWO3A4VEcC9XM46hFgVtE3gd1ieUNTHQmSftFNWhMi2avPYXSRw9VSDV4SQ)

1. Once the **SAPHanaAPI** app is running, hover over the **Endpoint** link, and select **View and Test** from the menu
2. Test the **SAPHanaAPI** app by filling out a value in the **orderId** field, and clicking on the **Try it out!** button:


![](https://lh4.googleusercontent.com/neznbYFjhYH--quXwQTDdXAyZ_r3kb_Syb5-_Cgm_dfbPA9uBfEDcA_3xeDfo7CxXj_p5MhIpIWwGjSo_YNKfZv4zMFLLObseqr-hcPrGX1jcQyYicoQYV4YUPA7UBY-GaGQ8nUeHFxdbHvkIcxgVDnkxogDG7yOqyfS5YwDWP4gqBMjwqA3LRtW6Q)

1. Copy the URL, which has a pattern like https://integration.cloud.tibcoapps.com:443/xxxxx/PurchaseOrders/purchaseOrders/{orderId}, and store it somewhere. You will need it when you implement the process API in the next lab.
* * *


![](https://docs.google.com/drawings/d/sLf0QUsQaQ54H2HFBYlqtnA/image?parent=1ww6ZDEVSSYTpPvQnRchtAP4vJfpXYGd9VkDc60bSPe4&amp;rev=1&amp;drawingRevisionAccessToken=hP0yML9vj7Zybw&amp;h=412&amp;w=231&amp;ac=1)![](https://docs.google.com/drawings/d/sG5MBzzTL75zp_f09-SeF2w/image?parent=1ww6ZDEVSSYTpPvQnRchtAP4vJfpXYGd9VkDc60bSPe4&amp;rev=1&amp;drawingRevisionAccessToken=uqiaZaGfv1sbbg&amp;h=445&amp;w=801&amp;ac=1)![](https://docs.google.com/drawings/d/sLE2qsDUwwWwq82fSHngPAQ/image?parent=1ww6ZDEVSSYTpPvQnRchtAP4vJfpXYGd9VkDc60bSPe4&amp;rev=1&amp;drawingRevisionAccessToken=5kaxX0wGJCZZ1w&amp;h=444&amp;w=806&amp;ac=1)

![](https://lh3.googleusercontent.com/Z7tbA3iZeNVlt3h3bLoqnY8Jy04lsl8mAyZrH3tP4x2E-1NwTyNVJgmglrTIvN7oYUqPdN0UM-bBvR1pqp3c-6lUeMtp4YGkb5JHZ6ROiCrqirbpTcx8L72eEG0ZHfO2cNOmhwCKqhQMmi588dUrhRLbfJ1rrBx3BudaasABKsFMlYbDZ8oD9VZMRQ)
