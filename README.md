
# CraftAPIClient

## Description

changes done on read me

This is Minecraft library for contacting the Mojang API. It features modern features of Java and flexible way of
communicating with Mojang. Furthermore, this project is used for experimenting with Unit-Tests

## Planned

* Unit testing for HTTP requests like in [google-http-client](https://github.com/google/google-http-java-client)
* Service registration for Bukkit and Sponge
* Cache cracked username requests
* HTTP request interceptor to redirect to this library
* Wait a customizable interval for sending bulk requests (although this increases latency)
* Add multiple remote APIs besides Mojang:
    * [MineTools](https://api.minetools.eu/)

## Requirements

* Java 8+
* Gson (2.2.4+)
* Guava (10.0.

This project is open for suggestions (including breaking changes between major version) and contributions. If you have 
an idea to make this library, you are welcome to create an issue ticker or pull request. Please provide units for pull 
requests if possible.

## Maven repository

```xml
	<repositories>
        <!-- CodeMc -->
        <repository>
            <id>codemc-repo</id>
            <url>https://repo.codemc.org/repository/maven-public/</url>
        </repository>
    </repositories>

    <dependencies>
        <!--Common component for contacting the Mojang API-->
        <dependency>
            <groupId>com.github.games647</groupId>
            <artifactId>craftapi</artifactId>
            <version>VERSION</version>
        </dependency>
    </dependencies>
```

## Credits

* [Fast-UUID](https://github.com/jchambers/fast-uuid) - MIT license
  * Remember to include its license file

Inspired by

* Sponge's
[GameProfileManager](https://jd.spongepowered.org/7.0.0/org/spongepowered/api/profile/GameProfileManager.html)
[GameProfileCache](https://jd.spongepowered.org/7.0.0/org/spongepowered/api/profile/GameProfileCache.html)
* [SquirrelId](https://github.com/EngineHub/SquirrelID)
* [Mojang Authlib](https://github.com/Techcable/Authlib)
* [Mojang AccountsClient](https://github.com/JonMcPherson/AccountsClient/)
* [API proxy Interceptor](https://github.com/Shevchik/MojangAPIProxy)
