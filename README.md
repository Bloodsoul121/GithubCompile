# GithubCompile
Github依赖测试

如果一直下载不下来，可以修改一下仓库依赖，如下

allprojects {
    repositories {
        google()
        maven { url "http://jcenter.bintray.com"}
        mavenCentral()
        maven { url 'https://jitpack.io' }
    }
}
