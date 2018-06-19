---
layout: post
title: Syncfusion Licensing Overview | Syncfusion
description: Overview of the license key, how to generate the license key, how to register the license key
platform: common
control: Essential Studio
documentation: ug
---

# Syncfusion Licensing Overview

We have introduced a new licensing system starting with version 16.2.0.x release of Essential Studio. These changes apply to all evaluators and only to paid customers who use NuGet packages. Starting with v16.2.0.x, if you reference Syncfusion assemblies from evaluation builds or from the NuGet feed, you also have to include a license key in your projects. Please note that this license key is different from the setup unlock key that you might have used in the past, and needs to be separately generated from Syncfusion website. A licensing error will show if this license key is missing.

## How to generate Syncfusion license key

License keys can be generated from the License & Downloads section of the Syncfusion website. 

![](licensing-images/generate-license.png)

## How to register the Syncfusion license key

The generated license key is just a string that needs to be registered before any Syncfusion control is initiated. The following code is used to register the license.

{% tabs %}
{% highlight c# %}
Syncfusion.Licensing.SyncfusionLicenseProvider.RegisterLicense("YOUR LICENSE KEY");
{% endhighlight %}
{% endtabs %}

N> Place the license key between double quotes.  Also, ensure that Syncfusion.Licensing.dll is referenced in your project where the license key is being registered.

Recommended place to register the license in the various platforms (ASP.NET Core, Xamarin, etc.) is covered in the following section.

### Windows Forms

Register the licensing code in static void main method before calling **Application.Run()** method.

{% tabs %}
{% highlight c# %}
static void Main()
{
	//Register Syncfusion license
	Syncfusion.Licensing.SyncfusionLicenseProvider.RegisterLicense("YOUR LICENSE KEY");
	
    Application.EnableVisualStyles();
    Application.SetCompatibleTextRenderingDefault(false);
    Application.Run(new Form1());
}
{% endhighlight %}
{% endtabs %}
 
### WPF

Register the license key in App constructor of **App.xaml.cs** 
{% tabs %}
{% highlight c# %}
public partial class App : Application
{
	//Register Syncfusion license
	Syncfusion.Licensing.SyncfusionLicenseProvider.RegisterLicense("YOUR LICENSE KEY");
		
} 
{% endhighlight %}
{% endtabs %}

### ASP.NET	

Register the license key in Application_Start method of **Global.asax.cs**

{% tabs %}
{% highlight c# %}
void Application_Start(object sender, EventArgs e)
{
	//Register Syncfusion license
	Syncfusion.Licensing.SyncfusionLicenseProvider.RegisterLicense("YOUR LICENSE KEY");
	
	// Code that runs on application startup
	RouteConfig.RegisterRoutes(RouteTable.Routes);
	BundleConfig.RegisterBundles(BundleTable.Bundles);
}
{% endhighlight %}
{% endtabs %}

### ASP.NET MVC

Register the license key in Application_Start method of **Global.asax.cs**

{% tabs %}
{% highlight c# %}
void Application_Start(object sender, EventArgs e)
{
	//Register Syncfusion license
	Syncfusion.Licensing.SyncfusionLicenseProvider.RegisterLicense("YOUR LICENSE KEY");
	
	// Code that runs on application startup
	RouteConfig.RegisterRoutes(RouteTable.Routes);
	BundleConfig.RegisterBundles(BundleTable.Bundles);
}
{% endhighlight %}
{% endtabs %} 

### ASP.NET Core

Register the license key in Configure method of **Startup.cs**

{% tabs %}
{% highlight c# %}
// This method gets called by the runtime. Use this method to configure the HTTP request pipeline.
public void Configure(IApplicationBuilder app, IHostingEnvironment env, ILoggerFactory loggerFactory)
{
	//Register Syncfusion license
	Syncfusion.Licensing.SyncfusionLicenseProvider.RegisterLicense("YOUR LICENSE KEY");
	
	loggerFactory.AddConsole(Configuration.GetSection("Logging"));
	loggerFactory.AddDebug();

	...
	
}
{% endhighlight %}
{% endtabs %} 

### UWP

Register the license key in **App.xaml.cs** constructor before InitializeComponent()

{% tabs %}
{% highlight c# %}
public App()
{
	//Register Syncfusion license
	Syncfusion.Licensing.SyncfusionLicenseProvider.RegisterLicense("YOUR LICENSE KEY");

	this.InitializeComponent();
	this.Suspending += OnSuspending;
}
{% endhighlight %}
{% endtabs %}

### Xamarin.Forms

Register the license key in **App.xaml.cs** constructor before InitializeComponent()

{% tabs %}
{% highlight c# %}
public App()
{
	//Register Syncfusion license
	Syncfusion.Licensing.SyncfusionLicenseProvider.RegisterLicense("YOUR LICENSE KEY");
	
	InitializeComponent();
	
	MainPage = new App1.MainPage();
}
{% endhighlight %}
{% endtabs %}

### Xamarin.Android

Register the license key in OnCreate override method of **MainActivity.cs** before initializing any Syncfusion control.

{% tabs %}
{% highlight c# %}
protected override void OnCreate(Bundle savedInstanceState)
{
	//Register Syncfusion license
	Syncfusion.Licensing.SyncfusionLicenseProvider.RegisterLicense("YOUR LICENSE KEY");

	base.OnCreate(savedInstanceState);

	// Set our view from the "main" layout resource
	SetContentView(Resource.Layout.Main);
}
{% endhighlight %}
{% endtabs %}
 

### Xamarin.iOS

Register the license key in **FinishedLaunching** override method of **AppDelegate.cs**

{% tabs %}
{% highlight c# %}
public override bool FinishedLaunching(UIApplication application, NSDictionary launchOptions)
{
	//Register Syncfusion license
	Syncfusion.Licensing.SyncfusionLicenseProvider.RegisterLicense("YOUR LICENSE KEY");

	// create a new window instance based on the screen size
	Window = new UIWindow(UIScreen.MainScreen.Bounds);

	// If you have defined a root view controller, set it here:
	// Window.RootViewController = myViewController;

	// make the window visible
	Window.MakeKeyAndVisible();

	return true;
} 
{% endhighlight %}
{% endtabs %}

## Registering key in a User control that contains Syncfusion controls
We recommend registering the license key at application level as shown in the previous sections

## NuGet.org users without a Syncfusion account

If you have directly obtained Syncfusion assemblies from NuGet.org and do not have a Syncfusion account, follow the steps to obtain a free 30-day license key:

* Register for a free Syncfusion account [here](https://www.syncfusion.com/account/register)
* Go to the start trials [page](https://syncfusion.com/account/manage-trials/start-trials) and start a trial
* Finally proceed to the [License & Downloads](https://syncfusion.com/account/downloads) section to obtain the license key

