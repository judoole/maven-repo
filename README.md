Judoole maven repo
==================

Small maven repository for different artifacts at built at github.com/judoole

Implemented using the step-by-step from Chas Emerick blog post [Hosting Maven Repos on Github](http://cemerick.com/2010/08/24/hosting-maven-repos-on-github/)

# Usage
Add this repository in your pom.xml, settings.xml, Nexus or its likes
````xml
<repositories>
    <repository>
        <id>judoole-snapshots</id>
        <url>https://github.com/judoole/judoole-mvn-repo/raw/master/snapshots</url>
    </repository>
</repositories>

````

## Deploy new
Ask for a pull request and I will build and git push. Or if I find you to be a nice person I'll give you push admin rights.