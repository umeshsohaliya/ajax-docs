---
title: Right-to-left Support
page_title: Right-to-left Support | UI for ASP.NET AJAX Documentation
description: Right-to-left Support
slug: window/accessibility-and-internationalization/right-to-left-support
tags: right-to-left,support
published: True
position: 2
---

# Right-to-left Support



## 

The __RadWindow__ fully supports right-to-left (RTL) language locales. The __RadWindows__are rendered to the page as children of the form element and in order to turn on the RTL support you should set__dir=rtl to the html or body__ elements.

````ASPNET
	        html
	        {
	            direction: rtl;
	        }
````



````ASPNET
	    <telerik:RadWindow runat="server" Width="550" Title="RadWindow can be used in right-to-left scenarios"
	        Height="450px" VisibleOnPageLoad="true" NavigateUrl="http://www.bing.com/" Skin="Sunset"
	        ID="Radwindow1">
	    </telerik:RadWindow>
````

![right-to-left-screenshot](images/right-to-left-screenshot.png)

# See Also

 * [See this live in an online demo](http://demos.telerik.com/aspnet-ajax/window/examples/righttoleft/defaultcs.aspx)