How to use:
==========

<repositories>
    <repository>
        <id>BranflakeMavenRepo-snapshots</id>
        <url>https://github.com/branflake2267/BranflakeMavenRepo/raw/master/snapshots</url>
    </repository>
</repositories>

<properties>
    <paypaladaptiveapi.version>0.0.2-SNAPSHOT</paypaladaptiveapi.version>
</properties>

<dependencies>
    <dependency>
        <groupId>com.paypal.adaptive</groupId>
        <artifactId>paypalx-gae-toolkit-fork</artifactId>
        <version>${paypaladaptiveapi.version}</version>
    </dependency>
<dependencies>