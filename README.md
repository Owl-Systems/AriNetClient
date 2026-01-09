# WazoNet - .NET Client for Wazo Platform

A comprehensive .NET client library for interacting with Wazo Platform APIs.

## Installation

```bash
dotnet add package WazoNet

## الخطوة 13: التجميع والنشر

```bash
# بناء المكتبة
dotnet build -c Release

# إنشاء حزمة NuGet
dotnet pack -c Release

# نشر إلى NuGet
dotnet nuget push bin/Release/WazoNet.1.0.0.nupkg -k YOUR_API_KEY -s https://api.nuget.org/v3/index.json