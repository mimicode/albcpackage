# 阿里百川SDK JitPack发布项目

此项目用于将阿里百川SDK相关的AAR和JAR库发布到JitPack，使它们可以通过Maven依赖方式使用。

## 如何使用

### 使用单个库

```gradle
repositories {
    maven { url 'https://jitpack.io' }
}

dependencies {
    // 使用特定的库，例如：
    implementation 'com.github.mimicode.albcpackage:ut-analytics-6.5.8.28-bc:1.0.0'
    // 或者
    implementation 'com.github.mimicode.albcpackage:utdid4all-1.5.3_proguard:1.0.0'
}
```

### 使用所有库

```gradle
repositories {
    maven { url 'https://jitpack.io' }
}

dependencies {
    // 使用包含所有库的依赖
    implementation 'com.github.mimicode.albcpackage:all-libs:1.0.0'
}
```

## 可用的库

- utdid4all-1.5.3_proguard
- ut-analytics-6.5.8.28-bc
- osmss3rd-core-android-0.0.1
- osmss3rd-android-0.0.7
- mtopsdk_allinone_open-3.1.22-opt
- nb_trade-4.1.0.9
- osmss3rd-adapter-0.0.4
- alibc_link_partner-4.1.31-SNAPSHOT
- alibabauth_core-2.2.1-sg
- alibabauth_ext_baichuan-2.2.1-sg
- alibabauth_ui-2.2.1-sg
- AlibcTradeBiz-4.1.0.9
- AlibcTradeCommon-4.1.0.9

## 发布步骤

1. 将此代码库克隆到您的计算机
2. 提交所有更改并推送到您的GitHub仓库
3. 在GitHub上创建发布版本（Release）或者标签（Tag）
4. 访问 https://jitpack.io/com/github/mimicode/albcpackage/1.0.0 触发构建

## 注意事项

- 确保您有权利发布这些第三方库
- JitPack构建可能需要几分钟时间 