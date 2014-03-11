Usage
-----

    buildscript {
        repositories {
            mavenCentral()
        }
        dependencies {
            classpath 'com.android.tools.build:gradle:0.4.2'
        }
    }
    
    apply plugin: 'android'
    
    repositories {
        mavenCentral()
            maven {
                url "https://github.com/dahlgren/pulltorefresh-aar/raw/master"
            }
    }
    
    dependencies {
        compile 'com.github.chrisbanes.pulltorefresh:library:2.1.2-SNAPSHOT'
    }

