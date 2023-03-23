# TARge21SolarPlanets


#School setup:

* TARge21SciCalculator/Properties/launchSettings.json 
"commandName": "Project"

* TARge21SciCalculator/TARge21SciCalculator/TARge21SciCalculator.csproj
<ApplicationVersion>1</ApplicationVersion> -- After that line
<WindowsPackageType Condition="$([MSBuild]::GetTargetPlatformIdentifier('$(TargetFramework)')) == 'windows'">None</WindowsPackageType>

* Install nuGet:

<PackageReference Include="Microsoft.UI.Xaml" Version="2.8.2" />
