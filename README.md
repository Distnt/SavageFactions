# SavageFactions
[![issues](https://img.shields.io/github/issues/illyria-io/illyriaFactions)](https://github.com/illyria-io/illyriaFactions/issues) [![forks](https://img.shields.io/github/forks/illyria-io/illyriaFactions)](https://github.com/illyria-io/illyriaFactions/network) [![stars](https://img.shields.io/github/stars/illyria-io/illyriaFactions)](https://github.com/illyria-io/illyriaFactions/stargazers) ![gradle](https://img.shields.io/badge/build-gradle-brightgreen)

## Discontinued - We are currently working on a [new coded from scratch Factions plugin called FactionsX](https://www.patreon.com/prosavage), more details soon!

SavageFactions is a fork of the popular Factions plugin FactionsUUID. Our goal is to make the ultimate competitive factions experience.

The plugin contains lots of new revolutionary features, which can be looked at in further detail on the wiki.

Currently the plugin is marketed on [Spigot](https://www.spigotmc.org/forums/),  a platform for Minecraft Servers which has an API that SavageFactions uses to enhance the game.

The plugin page can be found [here](https://www.spigotmc.org/resources/savagefactions-the-ultimate-factions-plugin-1-7-1-13.52891/), it contains a few gifs which show features of the plugin.

## Users
The installation guide can be found on the [installation page](https://github.com/ProSavage/SavageFactions/wiki/Installation-Guide) of the [wiki](https://github.com/ProSavage/SavageFactions/wiki)

Dependencies
 - [Vault](https://www.spigotmc.org/resources/vault.34315/)

Soft Dependencies
 - [EssentialsX](https://ci.ender.zone/job/EssentialsX/)
 - [CoreProtect (for /f inspect)](https://www.spigotmc.org/resources/coreprotect.8631/)

## Developers
This plugin has an extensive API and viewable Javadocs.
The Javadocs can be found in the javadocs folder, they are generated at every major release.
They are also hosted on my webserver and can be found [here](http://prosavage.net/factions_javadoc/)

If you would like to fork/contribute to SavageFactions I have made a video on how to compile the plugin correctly.
The video can be found [here](https://www.youtube.com/watch?v=fnDwjA2gX-E).


If you would like to use the plugin as a dependency in your project, you can use maven.

   ```xml
<repository>
    <id>illyria</id>
    <url>https://nexus.illyria.io/repository/maven-public/</url>        
 </repository>

<dependency>
    <groupId>com.massivecraft</groupId>
    <artifactId>SavageFactions</artifactId>
    <version>1.6.9.5-U0.2.1-RC-1.6.2-RC-2.5-RC-6</version>
</dependency>
```

If you would like to learn how to use the API there are lots of examples that can be found in the [wiki](https://github.com/ProSavage/SavageFactions/wiki) on the [API-Usage](https://github.com/ProSavage/SavageFactions/wiki/API-Usage) page.