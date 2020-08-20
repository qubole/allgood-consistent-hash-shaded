# README #

Shades allgood-consistent-hash library (https://github.com/ishugaliy/allgood-consistent-hash) under com.qubole groupId in order to publish it to maven central

## Building

Add following to your maven <i>settings.xml</i> (~/.m2/settings.xml), merge with existing <i>servers</i> tag if the file already has other servers configured

    <settings>
        <servers>
            <server>
                <id>github</id>
                <username>{your_github_username}</username>
                <password>{your_github_access_token}</password>
            </server>
        </servers>
    </settings>

Build via `mvn install`, use <i>release</i> profile while releasing
