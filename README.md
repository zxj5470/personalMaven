# personalMaven
:joy: :joy:


##Gradle  
```gradle
repositories {
//......mavenCentral()
	maven {
		url 'https://raw.github.com/zxj5470/personalMaven/master/'
	}
}

dependencies {
	compile "com.oracle:ojdbc6:11.1.0.7.0"
}
```

##Maven repositories  
```xml
<repositories>  
    <repository>  
        <id>personalMavenByzxj5470</id>  
        <name>personalMavenByzxj5470</name>  
        <url>https://raw.github.com/zxj5470/personalMaven/master/</url>  
    </repository>  
</repositories>  


<dependencies>
    <dependency>
        <groupId>com.oracle</groupId>
        <artifactId>ojdbc6</artifactId>
        <version>11.1.0.7.0</version>
    </dependency>
<dependencies>
```
