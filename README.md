# SeoBaseView
For Android BaseView(BaseActivity, BaseFragment, BaseDialogFragment) and SingleLiveEvent

- BaseView (BaseActivity, BaseFragment, BaseDialogFragment)
- SingleLiveEvent
를 구현해놓은 라이브러리


# 사용법
```
// setting.gradle

dependencyResolutionManagement {
    repositoriesMode.set(RepositoriesMode.FAIL_ON_PROJECT_REPOS)
    repositories {
        google()
        mavenCentral()
        // 아래 추가
        maven { url 'https://jitpack.io' }
    }
}
```


```
// module build.gradle

// BaseView and SingleLiveEvent
    implementation 'com.github.skw4223:SeoBaseView:1.3'
추가
```
