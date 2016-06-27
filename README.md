# ANCLAFS
## ASP.NET Core Library and Framework Support

In the process of writing a [book](https://www.packtpub.com/application-development/aspnet-core-10-high-performance) on ASP.NET Core and .NET Core I've done lots of research into what .NET libraries and frameworks are currently supported by these new platforms. Here are the results, hopefully you'll find this useful. Obviously these will change over time, send me a pull request if you'd like to make a correction or add something. This is a living document.

# Categories

## Experimenting
Project | NuGet Install Command | .NET Core Support | ASP.NET Core Support | Website
------- | --------------------- | ----------------- | -------------------- | -------
[Scientist.NET](https://github.com/Haacked/Scientist.net) | Install-Package Scientist -Pre | Yes | Yes | [Blog](http://haacked.com/archive/2016/01/20/scientist)

## Feature Switching
Project | NuGet Install Command | .NET Core Support | ASP.NET Core Support | Website
------- | --------------------- | ----------------- | -------------------- | -------
[FeatureSwitcher](https://github.com/mexx/FeatureSwitcher) | Install-Package FeatureSwitcher | No | No
[FeatureToggle](https://github.com/jason-roberts/FeatureToggle) | Install-Package FeatureToggle | [Planned](https://github.com/jason-roberts/FeatureToggle/issues/109) | [Planned](https://github.com/jason-roberts/FeatureToggle/issues/109) | [Blog](http://dontcodetired.com/blog/?tag=/featuretoggle)

## Profiling
Project | NuGet Install Command | .NET Core Support | ASP.NET Core Support | Website
------- | --------------------- | ----------------- | -------------------- | -------
[MiniProfiler](https://github.com/MiniProfiler/dotnet) | Install-Package MiniProfiler | [Planned for RC2](https://github.com/MiniProfiler/dotnet/issues/116) | [Planned for RC2](https://github.com/MiniProfiler/dotnet/issues/116) | [miniprofiler.com](http://miniprofiler.com)
[Glimpse](https://github.com/Glimpse/Glimpse.Prototype) | Install-Package Glimpse -Pre | [Yes (beta)](http://blog.getglimpse.com/2015/11/19/installing-glimpse-v2-beta1) | [Yes (beta)](http://blog.getglimpse.com/2015/11/19/installing-glimpse-v2-beta1) | [getglimpse.com](http://getglimpse.com)
Prefix | N/A (download installer) | [Planned for RC2](http://stackify.com/prefix-for-asp-net-core-rc1-is-available) | [Yes](http://stackify.com/prefix-for-asp-net-core-rc1-is-available) | [prefix.io](http://www.prefix.io)

## O/RMs
Project | NuGet Install Command | .NET Core Support | ASP.NET Core Support | Website
------- | --------------------- | ----------------- | -------------------- | -------
[Dapper](https://github.com/StackExchange/dapper-dot-net) | Install-Package Dapper -Pre | Yes | Yes | [github.io](https://stackexchange.github.io/dapper-dot-net)
[Simple.Data](https://github.com/markrendle/Simple.Data) | Install-Package Simple.Data.SqlServer | [Planned](https://blog.rendle.io/another-simple-data-update) | [In progress](https://blog.rendle.io/net-core-a-call-to-action/)  | [GH Issue](https://github.com/markrendle/Simple.Data/issues/389)
[EF Core](https://github.com/aspnet/EntityFramework) | Install-Package EntityFramework.MicrosoftSqlServer -Pre | Yes | Yes | [efproject.net](http://docs.efproject.net/en/latest/)

## Background Tasks
Project | NuGet Install Command | .NET Core Support | ASP.NET Core Support | Website
------- | --------------------- | ----------------- | -------------------- | -------
[Hangfire](https://github.com/HangfireIO/Hangfire) | Install-Package Hangfire | [Planned](https://github.com/HangfireIO/Hangfire/issues/365) | [Possible](https://discuss.hangfire.io/t/how-to-config-hangfire-with-asp-net-5/945) | [hangfire.io](http://hangfire.io)

## Image Manipulation
Project | NuGet Install Command | .NET Core Support | ASP.NET Core Support | Website
------- | --------------------- | ----------------- | -------------------- | -------
[ImageResizer](https://github.com/imazen/resizer) | Install-Package ImageResizer.WebConfig | No | No | [imageresizing.net](http://imageresizing.net)
[DynamicImage](https://github.com/tgjones/dynamic-image) | Install-Package DynamicImage | No | No | [dynamicimage.apphb.com](https://dynamicimage.apphb.com/)
[ImageProcessorCore](https://github.com/JimBobSquarePants/ImageProcessor/tree/Core) | Not yet ([myget](https://www.myget.org/gallery/imageprocessor)) | Yes (WIP) | Yes (WIP) | [imageprocessor.org](http://imageprocessor.org)

## Message Queuing
Project | NuGet Install Command | .NET Core Support | ASP.NET Core Support | Website
------- | --------------------- | ----------------- | -------------------- | -------
[RestBus](https://github.com/tenor/RestBus) | Install-Package RestBus.AspNet -Pre ([guide](https://github.com/tenor/RestBus/wiki/ASP.NET-Core-service-%28RabbitMQ-callable%29)) | Yes | Yes | [restbus.org](http://restbus.org) ([Blog](http://ahuwanya.net/blog/post/Introducing-RestBus))
[EasyNetQ](https://github.com/EasyNetQ/EasyNetQ) | Install-Package EasyNetQ | [Planned](https://github.com/EasyNetQ/EasyNetQ/issues/508) | [Planned](https://github.com/EasyNetQ/EasyNetQ/issues/508) | [easynetq.com](http://easynetq.com)
[RabbitMQ client](https://github.com/rabbitmq/rabbitmq-dotnet-client) | Install-Package RabbitMQ.Client | [Planned (new)](https://github.com/rabbitmq/rabbitmq-dotnet-client/issues/148) | [Planned (new)](https://github.com/rabbitmq/rabbitmq-dotnet-client/issues/148) | [rabbitmq.com](https://www.rabbitmq.com/dotnet.html)
[MassTransit](https://github.com/MassTransit/MassTransit) | Install-Package MassTransit.RabbitMQ | [Planned](https://github.com/MassTransit/MassTransit/issues/527) | [Planned](https://github.com/MassTransit/MassTransit/issues/527) | [masstransit-project.com](http://masstransit-project.com)
[RdKafka](https://github.com/ah-/rdkafka-dotnet) | Install-Package RdKafka -Pre | Yes | Yes | [https://ah-.github.io/rdkafka-dotnet/](https://ah-.github.io/rdkafka-dotnet/)

## Windows Services
Project | NuGet Install Command | .NET Core Support | ASP.NET Core Support | Website
------- | --------------------- | ----------------- | -------------------- | -------
[Topshelf](https://github.com/Topshelf/Topshelf) | Install-Package Topshelf | [In progress](https://github.com/Topshelf/Topshelf/issues/277) | [In progress](https://github.com/Topshelf/Topshelf/issues/277) | [topshelf-project.com](http://topshelf-project.com)

## Web
Project | NuGet Install Command | .NET Core Support | ASP.NET Core Support | Website
------- | --------------------- | ----------------- | -------------------- | -------
[Nancy](https://github.com/NancyFx/Nancy/tree/coreclr) | Install-Package Nancy -Pre | [In progress](http://thecodejunkie.com/2016/02/22/working-full-time-on-getting-nancy-running-on-coreclr) | [In progress](http://thecodejunkie.com/2016/02/22/working-full-time-on-getting-nancy-running-on-coreclr) | [nancyfx.org](http://nancyfx.org)
[SignalR](https://github.com/SignalR/SignalR) | Install-Package Microsoft.AspNet.SignalR | [After RTM (v3)](https://github.com/aspnet/home/wiki/roadmap#future-work) | [After RTM (v3)](https://github.com/aspnet/home/wiki/roadmap#future-work) | [signalr.net](http://signalr.net/)
[ReactJS.NET](https://github.com/reactjs/React.NET) | Install-Package React.AspNet | No, Linux via [Mono](http://reactjs.net/guides/mono.html) | [Yes](http://reactjs.net/2016/05/2.4.0-release.html) | [ReactJS.NET](http://reactjs.net/)
[Swashbuckle](https://github.com/domaindrivendev/Ahoy) | Install-Package Swashbuckle -Pre | Yes (beta) | Yes (beta) | 

## DI / IoC Containers
Project | NuGet Install Command | .NET Core Support | ASP.NET Core Support | Website
------- | --------------------- | ----------------- | -------------------- | -------
[Windsor](https://github.com/castleproject/Windsor) | {no .NET Core support} | [In progress](https://github.com/castleproject/Core/releases/tag/v4.0.0-alpha001) | [In progress](https://github.com/castleproject/Windsor/issues/120) | [castleproject.org](http://www.castleproject.org/)
[Ninject](https://github.com/ninject/Ninject) | {no .NET Core support} | [No](https://github.com/ninject/Ninject/issues/177) | [No](https://github.com/ninject/Ninject/issues/177) | [ninject.org](http://www.ninject.org/)
[Autofac](https://github.com/autofac/Autofac) | {no .NET Core support} | [In progress](https://github.com/autofac/Autofac/issues/594) | [In progress](https://github.com/autofac/Autofac/issues/594) | [autofac.org](http://autofac.org/)
[SimpleInjector](https://github.com/simpleinjector/SimpleInjector) | Install-Package SimpleInjector -Version 3.1.5 | Yes | Yes | [simpleinjector.org](https://simpleinjector.org)
ASP.NET Core contains built-in [DI](https://docs.asp.net/en/latest/fundamentals/dependency-injection.html) (and [logging](https://docs.asp.net/en/latest/fundamentals/logging.html))

## Other
Project | NuGet Install Command | .NET Core Support | ASP.NET Core Support | Website
------- | --------------------- | ----------------- | -------------------- | -------
[Orleans](https://github.com/dotnet/orleans) | [Multiple](https://github.com/dotnet/orleans#installation) | [In progress](https://github.com/dotnet/orleans/tree/coreclr-compatibility) | [In progress](https://github.com/dotnet/orleans/issues/368) | [dotnet.github.io/orleans](https://dotnet.github.io/orleans/)
[Huxley](https://github.com/jpsingleton/Huxley) | N/A | [Planned](https://github.com/jpsingleton/Huxley/issues/44) | [Planned](https://github.com/jpsingleton/Huxley/issues/44) | [huxley.unop.uk](https://huxley.unop.uk/)
[AutoMapper](https://github.com/AutoMapper/AutoMapper) | Install-Package AutoMapper -Pre | Yes (beta) | Yes (beta) | [automapper.org](http://automapper.org/)
[protobuf-net](https://github.com/mgravell/protobuf-net) | Install-Package protobuf-net | [Not yet](https://github.com/mgravell/protobuf-net/issues/159) | [Not yet](https://github.com/mgravell/protobuf-net/issues/159)
[Stuntman](https://github.com/ritterim/stuntman) | Install-Package RimDev.Stuntman | [Not yet](https://github.com/ritterim/stuntman/issues/62) | [Not yet](https://github.com/ritterim/stuntman/issues/62) | [rimdev.io/stuntman](http://rimdev.io/stuntman/)
