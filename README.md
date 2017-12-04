# JitPackReleaseDemo
用Jitpack发布开源库

包含String工具类和SharedPerference工具类

[![](https://jitpack.io/v/JamesPxy/JitPackReleaseDemo.svg)](https://jitpack.io/#JamesPxy/JitPackReleaseDemo)



如何接入本开源库：

To get a Git project into your build:

Step 1. Add the JitPack repository to your build file

		allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}

Step 2. Add the dependency

	dependencies {
            //始终依赖最新的开源库

	        compile 'com.github.JamesPxy:JitPackReleaseDemo:+'
	}
