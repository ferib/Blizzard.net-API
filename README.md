WOWSharp is a .NET Library for accessing Blizzard's World of Warcraft and Diablo Community APIs on Battle.net. The Library is written in C# and is available for .NET Framework 4, Silverlight 4 (or higher), Windows Phone 7.5 (or higher) and .NET for Windows Store Apps. Originally this project was created by Grendizer @ https://wowsharp.codeplex.com/ under the MIT license. Since codeplex is going to be closed i am copying the project here.

## Downloading the Package

Download NuGet package using the following Command from Package Manager Console: Install-Package WOWSharp

## Features

* The library handles all HTTP connections, error handling and JSON deserialization
* Uses Task based async operations which makes developing responsive application easier.
* The following World of WarCraft API functions are currently supported
    * Get Character Profile
    * Get Guild Profile
    * Get Realm Status
    * Get Current Auctions Data
    * Get Item Information
    * Get PVP Leaderboards (Arena and Rated Battlegrounds)
    * Get Character Classes
    * Get Character Races
    * Get Guild Perks
    * Get Guild Rewards
    * Get Item Classes
    * Get Guild Achievements
    * Get Character achievements
    * Get Quest information
    * Get Battlegroups
    * Get Recipe
    * Get Item Set Information
    * Get Spell Information
    * Get Battle Pet Ability
    * Get Battle Pet Species Info
    * Get Talents
    * Get Battle Pet Types
    * Get Challenge Mode Leaderboard Information
* The following Diablo 3 API functions are currently supported
    * Get Diablo profile information
    * Get Hero information
    * Get Item or recipe information
    * Get Artisan information
    * Get Follower information
* SilverLight library (Requires a proxy on the site of origin to route calls to battle.net if it's running in browser mode)
* Supports basic caching functionality (Cache Manager implementation not included, but the library supports hooking to any cache manager such as enterprise manager caching block, or MemoryCache)
* Supports API Key authorization (Requires .NET 4). It's not supported in Silverlight.
* An HTTP Handler to be added on the Silverlight application's site that handles routing calls to battle.net
