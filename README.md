![Logo](https://media.forgecdn.net/attachments/123/815/red-protect-plus1.png)  
RedProtect World is an area protection plugin made for users. No longer do you need to have an admin worldguard a region
for you. The user can take care of themselves now.

Chat with the developer online on Discord: https://discord.gg/RyEVJC3

## WIKI

See the WIKI for Help with commands, permissions and all features: https://github.com/FabioZumbi12/RedProtect/wiki

## Available Versions:

Spigot: https://www.spigotmc.org/resources/redprotect.15841/  
Bukkit: http://dev.bukkit.org/bukkit-plugins/region-protect-plus/  
Sponge: https://ore.spongepowered.org/FabioZumbi12/RedProtect

## RedProtect Add-ons:

This add-ons extends RedProtect flags, functions and more.

### Killer Projectiles:

> How to use: https://github.com/FabioZumbi12/RedProtect/tree/master/Addons/KillerProjectiles
> Download: https://github.com/FabioZumbi12/RedProtect/tree/master/add-ons

### BuyRent Regions:

> How to use: https://github.com/FabioZumbi12/RedProtect/tree/master/Addons/BuyRentRegion
> Download: https://github.com/FabioZumbi12/RedProtect/tree/master/add-ons

## Source:

The source is available on GitHub: https://github.com/FabioZumbi12/RedProtect

## Dev builds:

Available on
jenkins: [![Build Status](http://host.areaz12server.net.br:8081/buildStatus/icon?job=RedProtect)](http://host.areaz12server.net.br:8081/job/RedProtect/)

## Maven repository:

Now you can hook with uchat using maven repository (from Github) to use in your projects.

**Repository:**

```xml
<repositories>  
    <repository>  
        <id>redprotect-repo</id>  
        <url>https://raw.githubusercontent.com/FabioZumbi12/RedProtect/mvn-repo/</url>  
    </repository>  
</repositories>  
```

**Dependency:**

```xml
<dependencies>  
    <dependency>  
        //Core is needed
        <groupId>br.net.fabiozumbi12.RedProtect</groupId>  
        <artifactId>RedProtect-Core</artifactId>  
        <version>LATEST</version>  
        <scope>provided</scope>  
    </dependency>

    <dependency>  
        <groupId>br.net.fabiozumbi12.RedProtect</groupId>  
        <artifactId>RedProtect-[Check below for dependency names]</artifactId>  
        <version>LATEST</version>  
        <scope>provided</scope>  
    </dependency>
    <dependency>  
        <groupId>br.net.fabiozumbi12.RedProtect</groupId>  
        <artifactId>RedProtect-[Check below for dependency names]</artifactId>  
        <version>LATEST</version>
        <classifier>javadoc</classifier>
    </dependency>   
</dependencies>  
```

**Check the dependency names and
APIs:** [Click here](https://github.com/FabioZumbi12/RedProtect/tree/mvn-repo/br/net/fabiozumbi12/RedProtect)