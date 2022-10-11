# How to show the map using online GeoJson file using the .NET MAUI Maps

This article contains sample to show the map using online GeoJson file using the [Syncfusion .NET MAUI Maps](https://help.syncfusion.com/maui/maps/getting-started) control.

Please refer the KB through this [link]().

## Syncfusion controls

This project used the following Syncfusion control(s):
* [SfMaps](https://www.syncfusion.com/maui-controls/maui-maps)

## Supported platforms

.NET Multi-platform App UI (.NET MAUI) apps can be written for the following platforms:

* Android 5.0 (API 21) or higher.
* iOS 10 or higher.
* macOS 10.13 or higher, using Mac Catalyst.
* Windows 11 and Windows 10 version 1809 or higher, using [Windows UI Library (WinUI) 3](https://learn.microsoft.com/en-us/windows/apps/winui/winui3/).

## Requirements to run the sample

* [Visual Studio 2022 Preview](https://learn.microsoft.com/en-us/visualstudio/releases/2022/release-notes-preview) version 17.3.4 or higher (.NET MAUI version 6.0.486) or [Visual Studio 2022 for Mac 17.4 Preview](https://visualstudio.microsoft.com/vs/mac/preview/).
* .NET 6.0

Refer to the following link for more details: [System Requirements](https://help.syncfusion.com/maui/system-requirements)

## How to run the sample

1. Clone the sample and open it in Visual Studio 2022 Preview.

   *Note: If you download the sample using the "Download ZIP" option, right-click it, select Properties, and then select Unblock.*

2. Register your license key in the App.cs file as demonstrated in the following code.

		public App()
		{
			//Register Syncfusion license
			Syncfusion.Licensing.SyncfusionLicenseProvider.RegisterLicense("YOUR LICENSE KEY");
		
			InitializeComponent();
		
			MainPage = new MainPage();
		}
		
	Refer to this [link](https://help.syncfusion.com/maui/licensing/overview) for more details.
	
3. Clean and build the application.

4. Run the application.

## License

Syncfusion has no liability for any damage or consequence that may arise by using or viewing the samples. The samples are for demonstrative purposes, and if you choose to use or access the samples, you agree to not hold Syncfusion liable, in any form, for any damage that is related to use, for accessing, or viewing the samples. By accessing, viewing, or seeing the samples, you acknowledge and agree Syncfusion’s samples will not allow you seek injunctive relief in any form for any claim related to the sample. If you do not agree to this, do not view, access, utilize, or otherwise do anything with Syncfusion’s samples.
