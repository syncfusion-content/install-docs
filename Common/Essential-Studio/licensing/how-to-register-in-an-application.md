---
layout: post
title: Overview of Syncfusion license registration - Syncfusion
description: Learn here about how to register Syncfusion license key for Syncfusion application for license validation.
platform: common
control: Essential Studio
documentation: ug
---

<style>
#license {
    font-size: .88em!important;
margin-top: 1.5em;     margin-bottom: 1.5em;
    background-color: #fbefca;
    padding: 10px 17px 14px
}
</style>


# Register Syncfusion<sup style="font-size:70%">&reg;</sup> License key

The generated license key is just a string that needs to be registered before any Syncfusion<sup style="font-size:70%">&reg;</sup> control is initiated. The following code is used to register the license.

{% tabs %}
{% highlight c# %}
Syncfusion.Licensing.SyncfusionLicenseProvider.RegisterLicense("YOUR LICENSE KEY");
{% endhighlight %}
{% endtabs %}

N> * Place the license key between double quotes.  Also, ensure that Syncfusion.Licensing.dll is referenced in your project where the license key is being registered.
* Syncfusion<sup style="font-size:70%">&reg;</sup> license validation is done offline during application execution and does not require internet access.  Apps registered with a Syncfusion<sup style="font-size:70%">&reg;</sup> license key can be deployed on any system that does not have an internet connection.

I> Syncfusion<sup style="font-size:70%">&reg;</sup> license keys can be validated during the Continuous Integration (CI) processes to ensure proper licensing and prevent licensing errors during deployment. Refer to the [CI License Validation](/common/essential-studio/licensing/licensing-faq/ci-license-validation) section for detailed instructions on how to implement it.

## Where to register the Syncfusion<sup style="font-size:70%">&reg;</sup> License Key?

Below are the recommended place to register the license key in the various platforms (ASP.NET Core, Xamarin, etc.) 


## Windows Forms

Register the licensing code in static void main method before calling **Application.Run()** method in C#. In Visual Basic, register the licensing code in **Application.designer.vb** file constructor.

N> If the **Application.Designer.vb** file is not included by default in the project, it will be generated in the **My Project** folder in your VB project directory.

{% tabs %}
{% highlight c# %}
static void Main()
{
	//Register Syncfusion<sup style="font-size:70%">&reg;</sup> license
	Syncfusion.Licensing.SyncfusionLicenseProvider.RegisterLicense("YOUR LICENSE KEY");
	
    Application.EnableVisualStyles();
    Application.SetCompatibleTextRenderingDefault(false);
    Application.Run(new Form1());
}
{% endhighlight %}

{% highlight vb %}
Public Sub New()
		MyBase.New(Global.Microsoft.VisualBasic.ApplicationServices.AuthenticationMode.Windows)
		'Register Syncfusion License
		Syncfusion.Licensing.SyncfusionLicenseProvider.RegisterLicense("YOUR LICENSE KEY")
		Me.IsSingleInstance = False
		Me.EnableVisualStyles = True
		Me.SaveMySettingsOnExit = True
		Me.ShutdownStyle = Global.Microsoft.VisualBasic.ApplicationServices.ShutdownMode.AfterMainFormCloses
End Sub
{% endhighlight %}

{% endtabs %}
 
## WPF

Register the license key in App constructor of **App.xaml.cs** in C#. If App constructor not available in **App.xaml.cs**, create the "App()" constructor in **App.xaml.cs** and register the license key inside the constructor. In Visual Basic, register the license code in **App.xaml.vb**.
{% tabs %}
{% highlight c# %}
public partial class App : Application
{
	public App()
	{
		//Register Syncfusion<sup style="font-size:70%">&reg;</sup> license
		Syncfusion.Licensing.SyncfusionLicenseProvider.RegisterLicense("YOUR LICENSE KEY");
	}	
} 
{% endhighlight %}

{% highlight vb %}
Private Sub New()
	'Register Syncfusion<sup style="font-size:70%">&reg;</sup> License
	Syncfusion.Licensing.SyncfusionLicenseProvider.RegisterLicense("YOUR LICENSE KEY")
End Sub
{% endhighlight %}

{% endtabs %}

## ASP.NET MVC

Register the license key in Application_Start method of **Global.asax.cs/Global.asax.vb**

{% tabs %}
{% highlight c# %}
void Application_Start(object sender, EventArgs e)
{
	//Register Syncfusion<sup style="font-size:70%">&reg;</sup> license
	Syncfusion.Licensing.SyncfusionLicenseProvider.RegisterLicense("YOUR LICENSE KEY");
	
	// Code that runs on application startup
	RouteConfig.RegisterRoutes(RouteTable.Routes);
	BundleConfig.RegisterBundles(BundleTable.Bundles);
}
{% endhighlight %}

{% highlight vb %}
Protected Sub Application_Start()
        'Syncfusion<sup style="font-size:70%">&reg;</sup> Licensing Register
        Syncfusion.Licensing.SyncfusionLicenseProvider.RegisterLicense("YOUR LICENSE KEY")
        AreaRegistration.RegisterAllAreas()
        Register(GlobalConfiguration.Configuration)
        FilterConfig.RegisterGlobalFilters(GlobalFilters.Filters)
        RouteConfig.RegisterRoutes(RouteTable.Routes)
        BundleConfig.RegisterBundles(BundleTable.Bundles)
End Sub
{% endhighlight %}
	
{% endtabs %} 

## ASP.NET Core

Register the license key in the `Program.cs` file if you created the ASP.NET Core web application with Visual Studio 2022 and .NET 8.0 /.NET 9.0. 

{% tabs %}
{% highlight c# tabtitle="Program.cs" %}

var app = builder.Build();
//Register Syncfusion license
Syncfusion.Licensing.SyncfusionLicenseProvider.RegisterLicense("YOUR LICENSE KEY");

// Configure the HTTP request pipeline.
if (!app.Environment.IsDevelopment())
{
    app.UseExceptionHandler("/Home/Error");
    // The default HSTS value is 30 days. You may want to change this for production scenarios, see https://aka.ms/aspnetcore-hsts.
    app.UseHsts();
}

{% endhighlight %}
{% endtabs %}

## Blazor

### Server side application

Register the license key in Configure method of **Startup.cs**

{% tabs %}
{% highlight c# %}
// This method gets called by the runtime. Use this method to configure the HTTP request pipeline.
public void Configure(IApplicationBuilder app, IWebHostEnvironment env)
{
    //Register Syncfusion<sup style="font-size:70%">&reg;</sup> license
	Syncfusion.Licensing.SyncfusionLicenseProvider.RegisterLicense("YOUR LICENSE KEY");
	
    if (env.IsDevelopment())
    {
        app.UseDeveloperExceptionPage();
    }
    else
    {
        app.UseExceptionHandler("/Home/Error");
        // The default HSTS value is 30 days. You may want to change this for production scenarios, see https://aka.ms/aspnetcore-hsts.
        app.UseHsts();
    }

    app.UseHttpsRedirection();
    app.UseStaticFiles();

    app.UseRouting();


    app.UseEndpoints(endpoints =>
    {
         endpoints.MapBlazorHub();
         endpoints.MapFallbackToPage("/_Host");
    });
}

{% endhighlight %}
{% endtabs %} 

### Server side application using .NET 8.0/.NET 9.0

Register the license key in the **Program.cs** file if you created the Blazor server side application with Visual Studio 2022 and .NET 8.0/.NET 9.0

{% tabs %}
{% highlight c# %}
var app = builder.Build();
//Register Syncfusion<sup style="font-size:70%">&reg;</sup> license
Syncfusion.Licensing.SyncfusionLicenseProvider.RegisterLicense("YOUR LICENSE KEY");

// Configure the HTTP request pipeline.
if (!app.Environment.IsDevelopment())
{
    app.UseExceptionHandler("/Home/Error");
    // The default HSTS value is 30 days. You may want to change this for production scenarios, see https://aka.ms/aspnetcore-hsts.
    app.UseHsts();
}

{% endhighlight %}
{% endtabs %} 

### Client side application

Register the license key in main method of **Program.cs**

{% tabs %}
{% highlight c# %}
using Syncfusion.Blazor;
public static async Task Main(string[] args) 
{ 
    //Register Syncfusion<sup style="font-size:70%">&reg;</sup> license 
    Syncfusion.Licensing.SyncfusionLicenseProvider.RegisterLicense("YOUR LICENSE KEY");  
    var builder = WebAssemblyHostBuilder.CreateDefault(args); 
    builder.RootComponents.Add<App>("app");                               
    builder.Services.AddSyncfusionBlazor(); 
    await builder.Build().RunAsync(); 
} 

{% endhighlight %}
{% endtabs %} 

## UWP

Register the license key in **App.xaml.cs** constructor before InitializeComponent() in C#. If App constructor not available in **App.xaml.cs**, create the "App()" constructor in **App.xaml.cs** and register the license key inside the constructor. In Visual Basic, register the licensing code in **App.xaml.vb** file before OnLaunched event.

{% tabs %}
{% highlight c# %}
public App()
{
	//Register Syncfusion<sup style="font-size:70%">&reg;</sup> license
	Syncfusion.Licensing.SyncfusionLicenseProvider.RegisterLicense("YOUR LICENSE KEY");

	this.InitializeComponent();
	this.Suspending += OnSuspending;
}
{% endhighlight %}

{% highlight vb %}
Public Sub New()
	'Register Syncfusion<sup style="font-size:70%">&reg;</sup> License
	Syncfusion.Licensing.SyncfusionLicenseProvider.RegisterLicense("YOUR LICENSE KEY")
End Sub

Protected Overrides Sub OnLaunched(e As Windows.ApplicationModel.Activation.LaunchActivatedEventArgs)

...

End Sub
{% endhighlight %}

{% endtabs %}

## WinUI

Register the license key in App constructor of **App.xaml.cs** in C#. If App constructor not available in **App.xaml.cs**, create the "App()" constructor in **App.xaml.cs** and register the license key inside the constructor.
{% tabs %}
{% highlight c# %}
public partial class App : Application
{
	public App()
	{
		//Register Syncfusion<sup style="font-size:70%">&reg;</sup> license
		Syncfusion.Licensing.SyncfusionLicenseProvider.RegisterLicense("YOUR LICENSE KEY");
	}	
} 
{% endhighlight %}

{% endtabs %}

## Xamarin.Forms

Register the license key in **App.xaml.cs** constructor before InitializeComponent(). If App constructor not available in **App.xaml.cs**, create the "App()" constructor in **App.xaml.cs** and register the license key inside the constructor.

{% tabs %}
{% highlight c# %}
public App()
{
	//Register Syncfusion<sup style="font-size:70%">&reg;</sup> license
	Syncfusion.Licensing.SyncfusionLicenseProvider.RegisterLicense("YOUR LICENSE KEY");
	
	InitializeComponent();
	
	MainPage = new App1.MainPage();
}
{% endhighlight %}
{% endtabs %}

N> If you are developing an application using Gorilla Player SDK, it is must to register the Syncfusion<sup style="font-size:70%">&reg;</sup> license key in Xamarin.Forms.Android, Xamarin.Forms.iOS, and Xamarin.Forms.UWP.
   Refer [this link](https://help.syncfusion.com/xamarin/licensing/how-to-register-in-an-application#xamarinformsandroid) to register Syncfusion<sup style="font-size:70%">&reg;</sup> license key in Xamarin.Forms.Android
   Refer [this link](https://help.syncfusion.com/xamarin/licensing/how-to-register-in-an-application#xamarinformsios) to register Syncfusion<sup style="font-size:70%">&reg;</sup> license key in Xamarin.Forms.iOS
   Refer [this link](https://help.syncfusion.com/xamarin/licensing/how-to-register-in-an-application#xamarinformsuwp) to register Syncfusion<sup style="font-size:70%">&reg;</sup> license key in Xamarin.Forms.UWP



If you are using **Prism Framework** in your application, register the license key before InitializeComponent in OnInitialized method of **App.Xaml.cs**

{% tabs %}
{% highlight c# %}
protected override async void OnInitialized()
{
	//Register Syncfusion<sup style="font-size:70%">&reg;</sup> license
    Syncfusion.Licensing.SyncfusionLicenseProvider.RegisterLicense("YOUR LICENSE KEY");
 
    InitializeComponent();
 
    await NavigationService.NavigateAsync("NavigationPage/MainPage");
}
{% endhighlight %}
{% endtabs %}

## Xamarin.Android

Register the license key in **OnCreate** override method of your main activity class before initializing any Syncfusion<sup style="font-size:70%">&reg;</sup> control.

{% tabs %}
{% highlight c# %}
protected override void OnCreate(Bundle savedInstanceState)
{
	//Register Syncfusion<sup style="font-size:70%">&reg;</sup> license
	Syncfusion.Licensing.SyncfusionLicenseProvider.RegisterLicense("YOUR LICENSE KEY");

	base.OnCreate(savedInstanceState);

	// Set our view from the "main" layout resource
	SetContentView(Resource.Layout.Main);
}
{% endhighlight %}
{% endtabs %}
 

## Xamarin.iOS

Register the license key in **FinishedLaunching** override method of **AppDelegate.cs**

{% tabs %}
{% highlight c# %}
public override bool FinishedLaunching(UIApplication application, NSDictionary launchOptions)
{
	//Register Syncfusion<sup style="font-size:70%">&reg;</sup> license
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

## .NET MAUI

### 1.) Registering License Key in App.xaml.cs

You can register the license key in **App.xaml.cs** constructor before InitializeComponent(). If App constructor not available in **App.xaml.cs**, create the "App()" constructor in **App.xaml.cs** and register the license key inside the constructor.

{% tabs %}
{% highlight c# %}
public App()
{
	//Register Syncfusion<sup style="font-size:70%">&reg;</sup> license
	Syncfusion.Licensing.SyncfusionLicenseProvider.RegisterLicense("YOUR LICENSE KEY");
	
	InitializeComponent();
	
	MainPage = new AppShell();
}

{% endhighlight %}
{% endtabs %}

### 2.) Registering License Key in MauiProgram.cs

You can register the license key in **MauiProgram.cs** when initializing or registering any Syncfusion controls within this file. This ensures that all controls are fully licensed and functional from the moment the application starts. Add the license registration code inside the **CreateMauiApp** method in **MauiProgram.cs**.

{% tabs %}
{% highlight c# %}

public static class MauiProgram
{
    public static MauiApp CreateMauiApp()
    {
        // Register the Syncfusion license key
        Syncfusion.Licensing.SyncfusionLicenseProvider.RegisterLicense("YOUR_LICENSE_KEY");
 
        var builder = MauiApp.CreateBuilder();
        builder
            .UseMauiApp<App>()
            .ConfigureSyncfusionCore()
            .ConfigureFonts(fonts =>
            {
                fonts.AddFont("OpenSans-Regular.ttf", "OpenSansRegular");
            });

        return builder.Build();
    }
}

{% endhighlight %}
{% endtabs %}


## Java

Import ‘syncfusion.licensing' package and register the license key in the **main method** of your console application.

{% tabs %}
{% highlight JAVA %}
// Refer the licensing package
import com.syncfusion.licensing.*;

static void main() { 
// Register Syncfusion<sup style="font-size:70%">&reg;</sup> license 
SyncfusionLicenseProvider.registerLicense("YOUR LICENSE KEY"); 
}
{% endhighlight %}
{% endtabs %}

N> License key registration is not required for Java before v19.1.

## JavaScript (Essential<sup style="font-size:70%">&reg;</sup> JS 2)

Syncfusion<sup style="font-size:70%">&reg;</sup> license key should be registered, if your project using Syncfusion<sup style="font-size:70%">&reg;</sup> EJ2-JavaScript packages reference. The generated license key is a string that needs to be registered after any [Syncfusion<sup style="font-size:70%">&reg;</sup> JavaScript script reference](https://ej2.syncfusion.com/javascript/documentation/getting-started/quick-start/#configure-syncfusion-javascript-es5-control-in-the-application-1).

N> Only from 2022 Vol 1 v20.1.0.47, license key registration required for Essential<sup style="font-size:70%">&reg;</sup> JavaScript 2 products.

The following code is used to register the license.

### JavaScript es5

Register the license key by using **registerLicense** method after the [Syncfusion<sup style="font-size:70%">&reg;</sup> JavaScript script](https://ej2.syncfusion.com/javascript/documentation/getting-started/quick-start/#configure-syncfusion-javascript-es5-control-in-the-application-1) file reference as below.

{% tabs %}
{% highlight JS %}
// Registering Syncfusion<sup style="font-size:70%">&reg;</sup> license key
ej.base.registerLicense('License Key');
{% endhighlight %}
{% endtabs %}

### JavaScript es6 / TypeScript

Register the license key at the entry point of the project before using the Syncfusion<sup style="font-size:70%">&reg;</sup> controls.

{% tabs %}
{% highlight JS %}
// Registering Syncfusion<sup style="font-size:70%">&reg;</sup> license key
import { registerLicense } from '@syncfusion/ej2-base';

registerLicense('License key');
{% endhighlight %}
{% endtabs %}

### Angular

Register the license key in the **main.ts** file of the Angular project.

{% tabs %}
{% highlight JS %}
import { enableProdMode } from '@angular/core';
import { platformBrowserDynamic } from '@angular/platform-browser-dynamic';

import { AppModule } from './app/app.module';
import { environment } from './environments/environment';
import { registerLicense } from '@syncfusion/ej2-base';

// Registering Syncfusion<sup style="font-size:70%">&reg;</sup> license key
registerLicense('License Key');

if (environment.production) {
  enableProdMode();
}

platformBrowserDynamic().bootstrapModule(AppModule)
  .catch(err => console.error(err));
{% endhighlight %}
{% endtabs %}

### ReactJS

Register the license key in the **index.js** file of the React project.

{% tabs %}
{% highlight JS %}
import React from 'react';
import ReactDOM from 'react-dom';
import './index.css';
import App from './App';
import reportWebVitals from './reportWebVitals';
import { registerLicense } from '@syncfusion/ej2-base';

// Registering Syncfusion<sup style="font-size:70%">&reg;</sup> license key
registerLicense('License Key');

ReactDOM.render(
  <React.StrictMode>
    <App />
  </React.StrictMode>,
  document.getElementById('root')
);
{% endhighlight %}
{% endtabs %}

### VueJS

Register the license key in the **index.js** file of the Vue project.

{% tabs %}
{% highlight JS %}
import { createApp } from 'vue'
import App from './App.vue'
import { registerLicense } from '@syncfusion/ej2-base';

// Registering Syncfusion<sup style="font-size:70%">&reg;</sup> license key
registerLicense('License Key');
createApp(App).mount('#app')
{% endhighlight %}
{% endtabs %}

