DotNetRocks
===========

Setup

* Create a new Azure Mobile Services Table Called "PodcastEpisode"
* Follow this guide to setup the Table for Authentication: http://www.windowsazure.com/en-us/develop/mobile/tutorials/get-started-with-users-dotnet/
* Setup Azure Scripts for Insert, Read, Update: http://www.windowsazure.com/en-us/develop/mobile/tutorials/authorize-users-in-scripts-dotnet/
* Setup Twitter App for Authentication: http://www.dotnetcurry.com/ShowArticle.aspx?ID=860
* Optionally you can setup Facebook, Microsoft, or Google, however the sample is setup for Twitter
* Open "AzureWebService.cs" in DNR.Portable
* Edit: podcastClient = new MobileServiceClient(
        "https://"+"PUT-SITE-HERE" +".azure-mobile.net/",
        "PUT-YOUR-API-KEY-HERE");
* This information can be found on Azure
        


Integrating Azure Mobile Services into your project and PCL:

Here is a guide with step by step instructions on: http://motzcod.es/post/70038987318/azure-mobile-services-xamarin-pcl
        


