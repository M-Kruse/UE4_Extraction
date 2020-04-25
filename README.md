# UE4_Extraction

Unreal Engine example project for an extraction mechanic such as in Escape From Tarkov where to successfully finish the current match the player must make it to one of many points on the map and wait for their extraction.

This demonstrates server authoritiative "extraction" logic by creating an actor class that uses collision based timers to handle the extraction logic and timing.

# Demonstration

https://imgur.com/dqfQAHC


# Getting Started

For the project to work, you will need to install Unreal Engine >=4.23.1 or take a change migrating the project to your newer engine version.

## Unreal Engine 4 Setup

You will need to download the [Epic Games Launcher](https://launcher-public-service-prod06.ol.epicgames.com/launcher/api/installer/download/EpicGamesLauncherInstaller.msi) and go to the Library Tab. From there click on the + sign to add an engine version. Select version 4.23.1 from the list. The engine will download and install. There should also be an administrative prompt for prerequisite installation which will install required libraries and associate the project files to UE4. At this point, you should be able to go into the /UE4/ folder and launch the Django_REST.uproject by double clicking on it.

The project is configured to work with a dedicated server, so you need to click on the arrow of the "Play" button and check the box for dedicated server and set the players to at least 2.

![image](https://user-images.githubusercontent.com/46699116/77601255-80ff8c80-6ec7-11ea-8bd4-9f4a424aec99.png)

You may now use the Play button in UE4.
