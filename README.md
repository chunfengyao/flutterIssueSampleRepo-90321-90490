# issueSimpleProject
simple project for flutter issue.
[flutter #90321](https://github.com/flutter/flutter/issues/90321)
[flutter #90490](https://github.com/flutter/flutter/issues/90490)

# steps to reproduce.
- `cd module_flutter/`
- `flutter build aar`
- open Android Studio (my Version is : 2020.3.1 Patch 2)
- change Configurations to 'app'
- click 'run' button.

### the output message:

```
Executing tasks: [:app:assemble_testDebug] in project /Volumes/Storage/AS_WS/issueSimpleProject


> Configure project :app
WARNING: DSL element 'annotationProcessorOptions.includeCompileClasspath' is obsolete.
It will be removed in version 5.0 of the Android Gradle plugin.
It does not do anything and AGP no longer includes annotation processors added on your project's compile classpath

> Task :app:preBuild UP-TO-DATE
> Task :app:pre_testDebugBuild UP-TO-DATE
> Task :module_aliyun:AlivcMedia:preBuild UP-TO-DATE
> Task :module_aliyun:AlivcMedia:preDebugBuild UP-TO-DATE
> Task :module_aliyun:AliyunFileDownLoader:downloadermanager:preBuild UP-TO-DATE
> Task :module_aliyun:AliyunFileDownLoader:downloadermanager:preDebugBuild UP-TO-DATE
> Task :module_aliyun:AlivcMedia:packageDebugRenderscript NO-SOURCE
> Task :module_aliyun:AlivcMedia:compileDebugAidl NO-SOURCE
> Task :module_aliyun:AliyunFileDownLoader:downloadermanager:compileDebugAidl NO-SOURCE
> Task :app:compile_testDebugAidl NO-SOURCE
> Task :module_aliyun:AliyunFileDownLoader:downloadermanager:packageDebugRenderscript NO-SOURCE
> Task :app:compile_testDebugRenderscript NO-SOURCE
> Task :app:generate_testDebugBuildConfig UP-TO-DATE
> Task :app:javaPreCompile_testDebug UP-TO-DATE
> Task :app:generate_testDebugResValues UP-TO-DATE
> Task :app:generate_testDebugResources UP-TO-DATE
> Task :module_aliyun:AlivcMedia:generateDebugResValues UP-TO-DATE
> Task :module_aliyun:AlivcMedia:compileDebugRenderscript NO-SOURCE
> Task :module_aliyun:AlivcMedia:generateDebugResources UP-TO-DATE
> Task :module_aliyun:AlivcMedia:packageDebugResources UP-TO-DATE
> Task :module_aliyun:AliyunFileDownLoader:downloadermanager:generateDebugResValues UP-TO-DATE
> Task :module_aliyun:AliyunFileDownLoader:downloadermanager:compileDebugRenderscript NO-SOURCE
> Task :module_aliyun:AliyunFileDownLoader:downloadermanager:generateDebugResources UP-TO-DATE
> Task :module_aliyun:AliyunFileDownLoader:downloadermanager:packageDebugResources UP-TO-DATE
> Task :app:create_testDebugCompatibleScreenManifests UP-TO-DATE
> Task :app:extractDeepLinks_testDebug UP-TO-DATE
> Task :module_aliyun:AlivcMedia:extractDeepLinksDebug UP-TO-DATE
> Task :module_aliyun:AlivcMedia:processDebugManifest UP-TO-DATE
> Task :module_aliyun:AliyunFileDownLoader:downloadermanager:extractDeepLinksDebug UP-TO-DATE
> Task :app:merge_testDebugResources UP-TO-DATE
> Task :module_aliyun:AliyunFileDownLoader:downloadermanager:processDebugManifest UP-TO-DATE
> Task :app:process_testDebugManifest UP-TO-DATE
> Task :module_aliyun:AlivcMedia:compileDebugLibraryResources UP-TO-DATE
> Task :module_aliyun:AlivcMedia:parseDebugLocalResources UP-TO-DATE
> Task :module_aliyun:AlivcMedia:generateDebugRFile UP-TO-DATE
> Task :module_aliyun:AliyunFileDownLoader:downloadermanager:compileDebugLibraryResources UP-TO-DATE
> Task :module_aliyun:AliyunFileDownLoader:downloadermanager:parseDebugLocalResources UP-TO-DATE
> Task :module_aliyun:AliyunFileDownLoader:downloadermanager:generateDebugRFile UP-TO-DATE
> Task :app:process_testDebugResources UP-TO-DATE
> Task :module_aliyun:AlivcMedia:generateDebugBuildConfig UP-TO-DATE
> Task :module_aliyun:AlivcMedia:javaPreCompileDebug UP-TO-DATE
> Task :module_aliyun:AlivcMedia:compileDebugJavaWithJavac UP-TO-DATE
> Task :module_aliyun:AlivcMedia:bundleLibCompileToJarDebug UP-TO-DATE
> Task :module_aliyun:AliyunFileDownLoader:downloadermanager:generateDebugBuildConfig UP-TO-DATE
> Task :module_aliyun:AliyunFileDownLoader:downloadermanager:javaPreCompileDebug UP-TO-DATE
> Task :module_aliyun:AliyunFileDownLoader:downloadermanager:compileDebugJavaWithJavac UP-TO-DATE
> Task :module_aliyun:AliyunFileDownLoader:downloadermanager:bundleLibCompileToJarDebug UP-TO-DATE
> Task :app:compile_testDebugJavaWithJavac UP-TO-DATE
> Task :app:compile_testDebugSources UP-TO-DATE
> Task :app:desugar_testDebugFileDependencies UP-TO-DATE
> Task :app:check_testDebugDuplicateClasses UP-TO-DATE
> Task :app:mergeExtDex_testDebug UP-TO-DATE
> Task :module_aliyun:AliyunFileDownLoader:downloadermanager:bundleLibRuntimeToJarDebug UP-TO-DATE
> Task :module_aliyun:AlivcMedia:bundleLibRuntimeToJarDebug UP-TO-DATE
> Task :app:dexBuilder_testDebug UP-TO-DATE
> Task :app:mergeLibDex_testDebug UP-TO-DATE
> Task :app:mergeProjectDex_testDebug UP-TO-DATE
> Task :app:merge_testDebugShaders UP-TO-DATE
> Task :app:compile_testDebugShaders NO-SOURCE
> Task :app:generate_testDebugAssets UP-TO-DATE
> Task :flutter:cleanPackageDebugAssets
> Task :flutter:compileFlutterBuildDebug
> Task :flutter:preBuild UP-TO-DATE
> Task :flutter:preDebugBuild UP-TO-DATE
> Task :flutter:mergeDebugShaders UP-TO-DATE
> Task :flutter:compileDebugShaders NO-SOURCE
> Task :flutter:generateDebugAssets UP-TO-DATE
> Task :flutter:packageDebugAssets
> Task :flutter:copyFlutterAssetsDebug
> Task :module_aliyun:AlivcMedia:mergeDebugShaders UP-TO-DATE
> Task :module_aliyun:AlivcMedia:compileDebugShaders NO-SOURCE
> Task :module_aliyun:AlivcMedia:generateDebugAssets UP-TO-DATE
> Task :module_aliyun:AlivcMedia:packageDebugAssets UP-TO-DATE
> Task :module_aliyun:AliyunFileDownLoader:downloadermanager:mergeDebugShaders UP-TO-DATE
> Task :module_aliyun:AliyunFileDownLoader:downloadermanager:compileDebugShaders NO-SOURCE
> Task :module_aliyun:AliyunFileDownLoader:downloadermanager:generateDebugAssets UP-TO-DATE
> Task :module_aliyun:AliyunFileDownLoader:downloadermanager:packageDebugAssets UP-TO-DATE
> Task :app:merge_testDebugAssets UP-TO-DATE
> Task :app:process_testDebugJavaRes NO-SOURCE
> Task :module_aliyun:AlivcMedia:processDebugJavaRes NO-SOURCE
> Task :module_aliyun:AlivcMedia:bundleLibResDebug NO-SOURCE
> Task :module_aliyun:AliyunFileDownLoader:downloadermanager:processDebugJavaRes NO-SOURCE
> Task :module_aliyun:AliyunFileDownLoader:downloadermanager:bundleLibResDebug NO-SOURCE
> Task :app:merge_testDebugJavaResource UP-TO-DATE
> Task :app:merge_testDebugJniLibFolders UP-TO-DATE
> Task :module_aliyun:AlivcMedia:mergeDebugJniLibFolders UP-TO-DATE
> Task :module_aliyun:AlivcMedia:mergeDebugNativeLibs UP-TO-DATE
> Task :module_aliyun:AlivcMedia:stripDebugDebugSymbols NO-SOURCE
> Task :module_aliyun:AlivcMedia:copyDebugJniLibsProjectOnly UP-TO-DATE
> Task :module_aliyun:AliyunFileDownLoader:downloadermanager:mergeDebugJniLibFolders UP-TO-DATE
> Task :module_aliyun:AliyunFileDownLoader:downloadermanager:mergeDebugNativeLibs UP-TO-DATE
> Task :module_aliyun:AliyunFileDownLoader:downloadermanager:stripDebugDebugSymbols NO-SOURCE
> Task :module_aliyun:AliyunFileDownLoader:downloadermanager:copyDebugJniLibsProjectOnly UP-TO-DATE
> Task :app:merge_testDebugNativeLibs UP-TO-DATE
> Task :app:strip_testDebugDebugSymbols NO-SOURCE
> Task :app:validateSigning_testDebug UP-TO-DATE
> Task :app:package_testDebug UP-TO-DATE
> Task :app:assemble_testDebug UP-TO-DATE
generateLockfiles
Starting a Gradle Daemon, 1 busy and 1 incompatible and 4 stopped Daemons could not be reused, use --status for details

> Configure project :app
WARNING: DSL element 'annotationProcessorOptions.includeCompileClasspath' is obsolete.
It will be removed in version 5.0 of the Android Gradle plugin.
It does not do anything and AGP no longer includes annotation processors added on your project's compile classpath

> Task :app:dependencies

------------------------------------------------------------
Project :app
------------------------------------------------------------

_internal_aapt2_binary - The AAPT2 binary to use for processing resources.
\--- com.android.tools.build:aapt2:4.0.1-6197926

_testAnnotationProcessor - Classpath for the annotation processor for '_test'. (n)
No dependencies

_testApi - API dependencies for '_test' sources. (n)
No dependencies

_testApk - Apk dependencies for '_test' sources (deprecated: use '_testRuntimeOnly' instead). (n)
No dependencies

_testCompile - Compile dependencies for '_test' sources (deprecated: use '_testImplementation' instead). (n)
No dependencies

_testCompileOnly - Compile only dependencies for '_test' sources. (n)
No dependencies

_testDebugAabPublication - Bundle Publication for _testDebug (n)
No dependencies

_testDebugAndroidTestAnnotationProcessorClasspath - Resolved configuration for annotation-processor for variant: _testDebugAndroidTest
No dependencies

_testDebugAndroidTestCompileClasspath - Resolved configuration for compilation for variant: _testDebugAndroidTest
+--- androidx.appcompat:appcompat:1.2.0
|    +--- androidx.annotation:annotation:1.1.0
|    +--- androidx.core:core:1.3.0 -> 1.3.1
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.lifecycle:lifecycle-runtime:2.0.0 -> 2.1.0
|    |    |    +--- androidx.lifecycle:lifecycle-common:2.1.0
|    |    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.arch.core:core-common:2.1.0
|    |    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    \--- androidx.versionedparcelable:versionedparcelable:1.1.0
|    |         +--- androidx.annotation:annotation:1.1.0
|    |         \--- androidx.collection:collection:1.0.0 -> 1.1.0
|    |              \--- androidx.annotation:annotation:1.1.0
|    +--- androidx.cursoradapter:cursoradapter:1.0.0
|    |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    +--- androidx.fragment:fragment:1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    +--- androidx.collection:collection:1.1.0 (*)
|    |    +--- androidx.viewpager:viewpager:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    |    \--- androidx.customview:customview:1.0.0
|    |    |         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |         \--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    +--- androidx.loader:loader:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-livedata:2.0.0
|    |    |    |    +--- androidx.arch.core:core-runtime:2.0.0
|    |    |    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    +--- androidx.lifecycle:lifecycle-livedata-core:2.0.0
|    |    |    |    |    +--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    |    +--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    |    \--- androidx.arch.core:core-runtime:2.0.0 (*)
|    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0
|    |    |         \--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.activity:activity:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-runtime:2.1.0 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-viewmodel:2.1.0 (*)
|    |    |    \--- androidx.savedstate:savedstate:1.0.0
|    |    |         +--- androidx.annotation:annotation:1.1.0
|    |    |         +--- androidx.arch.core:core-common:2.0.1 -> 2.1.0 (*)
|    |    |         \--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.1.0 (*)
|    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0 (*)
|    +--- androidx.appcompat:appcompat-resources:1.2.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.0.1 -> 1.3.1 (*)
|    |    +--- androidx.vectordrawable:vectordrawable:1.1.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    |    \--- androidx.collection:collection:1.1.0 (*)
|    |    \--- androidx.vectordrawable:vectordrawable-animated:1.1.0
|    |         +--- androidx.vectordrawable:vectordrawable:1.1.0 (*)
|    |         +--- androidx.interpolator:interpolator:1.0.0
|    |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         \--- androidx.collection:collection:1.1.0 (*)
|    \--- androidx.drawerlayout:drawerlayout:1.0.0
|         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|         +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|         \--- androidx.customview:customview:1.0.0 (*)
+--- com.google.android.material:material:1.3.0
|    +--- androidx.annotation:annotation:1.0.1 -> 1.1.0
|    +--- androidx.appcompat:appcompat:1.1.0 -> 1.2.0 (*)
|    +--- androidx.cardview:cardview:1.0.0
|    |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    +--- androidx.coordinatorlayout:coordinatorlayout:1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    +--- androidx.customview:customview:1.0.0 (*)
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.constraintlayout:constraintlayout:2.0.1 -> 2.0.4
|    |    +--- androidx.appcompat:appcompat:1.2.0 (*)
|    |    +--- androidx.core:core:1.3.1 (*)
|    |    \--- androidx.constraintlayout:constraintlayout-solver:2.0.4
|    +--- androidx.core:core:1.2.0 -> 1.3.1 (*)
|    +--- androidx.dynamicanimation:dynamicanimation:1.0.0
|    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    +--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    |    \--- androidx.legacy:legacy-support-core-utils:1.0.0
|    |         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |         +--- androidx.documentfile:documentfile:1.0.0
|    |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         +--- androidx.loader:loader:1.0.0 (*)
|    |         +--- androidx.localbroadcastmanager:localbroadcastmanager:1.0.0
|    |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         \--- androidx.print:print:1.0.0
|    |              \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    +--- androidx.annotation:annotation-experimental:1.0.0
|    +--- androidx.fragment:fragment:1.0.0 -> 1.1.0 (*)
|    +--- androidx.lifecycle:lifecycle-runtime:2.0.0 -> 2.1.0 (*)
|    +--- androidx.recyclerview:recyclerview:1.0.0 -> 1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    +--- androidx.customview:customview:1.0.0 (*)
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.transition:transition:1.2.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.0.1 -> 1.3.1 (*)
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.vectordrawable:vectordrawable:1.1.0 (*)
|    \--- androidx.viewpager2:viewpager2:1.0.0
|         +--- androidx.annotation:annotation:1.1.0
|         +--- androidx.fragment:fragment:1.1.0 (*)
|         +--- androidx.recyclerview:recyclerview:1.1.0 (*)
|         +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|         \--- androidx.collection:collection:1.1.0 (*)
+--- androidx.constraintlayout:constraintlayout:2.0.4 (*)
+--- project :module_aliyun:AliyunFileDownLoader:downloadermanager
+--- project :module_aliyun:AlivcMedia
+--- androidx.appcompat:appcompat:{strictly 1.2.0} -> 1.2.0 (c)
+--- com.google.android.material:material:{strictly 1.3.0} -> 1.3.0 (c)
+--- androidx.constraintlayout:constraintlayout:{strictly 2.0.4} -> 2.0.4 (c)
+--- androidx.annotation:annotation:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.core:core:{strictly 1.3.1} -> 1.3.1 (c)
+--- androidx.cursoradapter:cursoradapter:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.fragment:fragment:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.appcompat:appcompat-resources:{strictly 1.2.0} -> 1.2.0 (c)
+--- androidx.drawerlayout:drawerlayout:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.cardview:cardview:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.coordinatorlayout:coordinatorlayout:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.dynamicanimation:dynamicanimation:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.annotation:annotation-experimental:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.lifecycle:lifecycle-runtime:{strictly 2.1.0} -> 2.1.0 (c)
+--- androidx.recyclerview:recyclerview:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.transition:transition:{strictly 1.2.0} -> 1.2.0 (c)
+--- androidx.vectordrawable:vectordrawable:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.viewpager2:viewpager2:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.constraintlayout:constraintlayout-solver:{strictly 2.0.4} -> 2.0.4 (c)
+--- androidx.versionedparcelable:versionedparcelable:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.collection:collection:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.viewpager:viewpager:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.loader:loader:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.activity:activity:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.lifecycle:lifecycle-viewmodel:{strictly 2.1.0} -> 2.1.0 (c)
+--- androidx.vectordrawable:vectordrawable-animated:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.customview:customview:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.legacy:legacy-support-core-utils:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.lifecycle:lifecycle-common:{strictly 2.1.0} -> 2.1.0 (c)
+--- androidx.arch.core:core-common:{strictly 2.1.0} -> 2.1.0 (c)
+--- androidx.lifecycle:lifecycle-livedata:{strictly 2.0.0} -> 2.0.0 (c)
+--- androidx.savedstate:savedstate:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.interpolator:interpolator:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.documentfile:documentfile:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.localbroadcastmanager:localbroadcastmanager:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.print:print:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.arch.core:core-runtime:{strictly 2.0.0} -> 2.0.0 (c)
\--- androidx.lifecycle:lifecycle-livedata-core:{strictly 2.0.0} -> 2.0.0 (c)

_testDebugAndroidTestRuntimeClasspath - Resolved configuration for runtime for variant: _testDebugAndroidTest
+--- androidx.appcompat:appcompat:1.2.0
|    +--- androidx.annotation:annotation:1.1.0
|    +--- androidx.core:core:1.3.0 -> 1.3.1
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.lifecycle:lifecycle-runtime:2.0.0 -> 2.1.0
|    |    |    +--- androidx.lifecycle:lifecycle-common:2.1.0
|    |    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.arch.core:core-common:2.1.0
|    |    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.versionedparcelable:versionedparcelable:1.1.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0
|    |    |         \--- androidx.annotation:annotation:1.1.0
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.cursoradapter:cursoradapter:1.0.0
|    |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    +--- androidx.fragment:fragment:1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    +--- androidx.collection:collection:1.1.0 (*)
|    |    +--- androidx.viewpager:viewpager:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    |    \--- androidx.customview:customview:1.0.0
|    |    |         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |         \--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    +--- androidx.loader:loader:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-livedata:2.0.0
|    |    |    |    +--- androidx.arch.core:core-runtime:2.0.0
|    |    |    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    +--- androidx.lifecycle:lifecycle-livedata-core:2.0.0
|    |    |    |    |    +--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    |    +--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    |    \--- androidx.arch.core:core-runtime:2.0.0 (*)
|    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0
|    |    |         \--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.activity:activity:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-runtime:2.1.0 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-viewmodel:2.1.0 (*)
|    |    |    \--- androidx.savedstate:savedstate:1.0.0
|    |    |         +--- androidx.annotation:annotation:1.1.0
|    |    |         +--- androidx.arch.core:core-common:2.0.1 -> 2.1.0 (*)
|    |    |         \--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.1.0 (*)
|    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0 (*)
|    +--- androidx.appcompat:appcompat-resources:1.2.0
|    |    +--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.0.1 -> 1.3.1 (*)
|    |    +--- androidx.vectordrawable:vectordrawable:1.1.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    |    \--- androidx.collection:collection:1.1.0 (*)
|    |    \--- androidx.vectordrawable:vectordrawable-animated:1.1.0
|    |         +--- androidx.vectordrawable:vectordrawable:1.1.0 (*)
|    |         +--- androidx.interpolator:interpolator:1.0.0
|    |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         \--- androidx.collection:collection:1.1.0 (*)
|    +--- androidx.drawerlayout:drawerlayout:1.0.0
|    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    \--- androidx.customview:customview:1.0.0 (*)
|    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
+--- com.google.android.material:material:1.3.0
|    +--- androidx.annotation:annotation:1.0.1 -> 1.1.0
|    +--- androidx.appcompat:appcompat:1.1.0 -> 1.2.0 (*)
|    +--- androidx.cardview:cardview:1.0.0
|    |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    +--- androidx.coordinatorlayout:coordinatorlayout:1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    +--- androidx.customview:customview:1.0.0 (*)
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.constraintlayout:constraintlayout:2.0.1 -> 2.0.4
|    |    +--- androidx.appcompat:appcompat:1.2.0 (*)
|    |    +--- androidx.core:core:1.3.1 (*)
|    |    \--- androidx.constraintlayout:constraintlayout-solver:2.0.4
|    +--- androidx.core:core:1.2.0 -> 1.3.1 (*)
|    +--- androidx.dynamicanimation:dynamicanimation:1.0.0
|    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    +--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    |    \--- androidx.legacy:legacy-support-core-utils:1.0.0
|    |         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |         +--- androidx.documentfile:documentfile:1.0.0
|    |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         +--- androidx.loader:loader:1.0.0 (*)
|    |         +--- androidx.localbroadcastmanager:localbroadcastmanager:1.0.0
|    |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         \--- androidx.print:print:1.0.0
|    |              \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    +--- androidx.annotation:annotation-experimental:1.0.0
|    +--- androidx.fragment:fragment:1.0.0 -> 1.1.0 (*)
|    +--- androidx.lifecycle:lifecycle-runtime:2.0.0 -> 2.1.0 (*)
|    +--- androidx.recyclerview:recyclerview:1.0.0 -> 1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    +--- androidx.customview:customview:1.0.0 (*)
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.transition:transition:1.2.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.0.1 -> 1.3.1 (*)
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.vectordrawable:vectordrawable:1.1.0 (*)
|    \--- androidx.viewpager2:viewpager2:1.0.0
|         +--- androidx.annotation:annotation:1.1.0
|         +--- androidx.fragment:fragment:1.1.0 (*)
|         +--- androidx.recyclerview:recyclerview:1.1.0 (*)
|         +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|         \--- androidx.collection:collection:1.1.0 (*)
+--- androidx.constraintlayout:constraintlayout:2.0.4 (*)
+--- project :module_aliyun:AliyunFileDownLoader:downloadermanager
|    +--- androidx.appcompat:appcompat:1.2.0 (*)
|    \--- com.google.android.material:material:1.3.0 (*)
+--- project :module_aliyun:AlivcMedia
|    +--- androidx.appcompat:appcompat:1.2.0 (*)
|    \--- com.google.android.material:material:1.3.0 (*)
+--- androidx.appcompat:appcompat:{strictly 1.2.0} -> 1.2.0 (c)
+--- com.google.android.material:material:{strictly 1.3.0} -> 1.3.0 (c)
+--- androidx.constraintlayout:constraintlayout:{strictly 2.0.4} -> 2.0.4 (c)
+--- androidx.annotation:annotation:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.core:core:{strictly 1.3.1} -> 1.3.1 (c)
+--- androidx.cursoradapter:cursoradapter:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.fragment:fragment:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.appcompat:appcompat-resources:{strictly 1.2.0} -> 1.2.0 (c)
+--- androidx.drawerlayout:drawerlayout:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.collection:collection:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.cardview:cardview:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.coordinatorlayout:coordinatorlayout:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.dynamicanimation:dynamicanimation:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.annotation:annotation-experimental:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.lifecycle:lifecycle-runtime:{strictly 2.1.0} -> 2.1.0 (c)
+--- androidx.recyclerview:recyclerview:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.transition:transition:{strictly 1.2.0} -> 1.2.0 (c)
+--- androidx.vectordrawable:vectordrawable:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.viewpager2:viewpager2:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.constraintlayout:constraintlayout-solver:{strictly 2.0.4} -> 2.0.4 (c)
+--- androidx.versionedparcelable:versionedparcelable:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.viewpager:viewpager:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.loader:loader:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.activity:activity:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.lifecycle:lifecycle-viewmodel:{strictly 2.1.0} -> 2.1.0 (c)
+--- androidx.vectordrawable:vectordrawable-animated:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.customview:customview:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.legacy:legacy-support-core-utils:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.lifecycle:lifecycle-common:{strictly 2.1.0} -> 2.1.0 (c)
+--- androidx.arch.core:core-common:{strictly 2.1.0} -> 2.1.0 (c)
+--- androidx.lifecycle:lifecycle-livedata:{strictly 2.0.0} -> 2.0.0 (c)
+--- androidx.savedstate:savedstate:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.interpolator:interpolator:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.documentfile:documentfile:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.localbroadcastmanager:localbroadcastmanager:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.print:print:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.arch.core:core-runtime:{strictly 2.0.0} -> 2.0.0 (c)
\--- androidx.lifecycle:lifecycle-livedata-core:{strictly 2.0.0} -> 2.0.0 (c)

_testDebugAnnotationProcessor - Classpath for the annotation processor for '_testDebug'. (n)
No dependencies

_testDebugAnnotationProcessorClasspath - Resolved configuration for annotation-processor for variant: _testDebug
No dependencies

_testDebugApi - API dependencies for '_testDebug' sources. (n)
No dependencies

_testDebugApiElements - API elements for _testDebug (n)
No dependencies

_testDebugApk - Apk dependencies for '_testDebug' sources (deprecated: use '_testDebugRuntimeOnly' instead). (n)
No dependencies

_testDebugApkPublication - APK publication for _testDebug (n)
No dependencies

_testDebugCompile - Compile dependencies for '_testDebug' sources (deprecated: use '_testDebugImplementation' instead). (n)
No dependencies

_testDebugCompileClasspath - Resolved configuration for compilation for variant: _testDebug
+--- androidx.appcompat:appcompat:1.2.0
|    +--- androidx.annotation:annotation:1.1.0
|    +--- androidx.core:core:1.3.0 -> 1.3.1
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.lifecycle:lifecycle-runtime:2.0.0 -> 2.1.0
|    |    |    +--- androidx.lifecycle:lifecycle-common:2.1.0
|    |    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.arch.core:core-common:2.1.0
|    |    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    \--- androidx.versionedparcelable:versionedparcelable:1.1.0
|    |         +--- androidx.annotation:annotation:1.1.0
|    |         \--- androidx.collection:collection:1.0.0 -> 1.1.0
|    |              \--- androidx.annotation:annotation:1.1.0
|    +--- androidx.cursoradapter:cursoradapter:1.0.0
|    |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    +--- androidx.fragment:fragment:1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    +--- androidx.collection:collection:1.1.0 (*)
|    |    +--- androidx.viewpager:viewpager:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    |    \--- androidx.customview:customview:1.0.0
|    |    |         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |         \--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    +--- androidx.loader:loader:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-livedata:2.0.0
|    |    |    |    +--- androidx.arch.core:core-runtime:2.0.0
|    |    |    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    +--- androidx.lifecycle:lifecycle-livedata-core:2.0.0
|    |    |    |    |    +--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    |    +--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    |    \--- androidx.arch.core:core-runtime:2.0.0 (*)
|    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0
|    |    |         \--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.activity:activity:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-runtime:2.1.0 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-viewmodel:2.1.0 (*)
|    |    |    \--- androidx.savedstate:savedstate:1.0.0
|    |    |         +--- androidx.annotation:annotation:1.1.0
|    |    |         +--- androidx.arch.core:core-common:2.0.1 -> 2.1.0 (*)
|    |    |         \--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.1.0 (*)
|    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0 (*)
|    +--- androidx.appcompat:appcompat-resources:1.2.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.0.1 -> 1.3.1 (*)
|    |    +--- androidx.vectordrawable:vectordrawable:1.1.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    |    \--- androidx.collection:collection:1.1.0 (*)
|    |    \--- androidx.vectordrawable:vectordrawable-animated:1.1.0
|    |         +--- androidx.vectordrawable:vectordrawable:1.1.0 (*)
|    |         +--- androidx.interpolator:interpolator:1.0.0
|    |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         \--- androidx.collection:collection:1.1.0 (*)
|    \--- androidx.drawerlayout:drawerlayout:1.0.0
|         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|         +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|         \--- androidx.customview:customview:1.0.0 (*)
+--- com.google.android.material:material:1.3.0
|    +--- androidx.annotation:annotation:1.0.1 -> 1.1.0
|    +--- androidx.appcompat:appcompat:1.1.0 -> 1.2.0 (*)
|    +--- androidx.cardview:cardview:1.0.0
|    |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    +--- androidx.coordinatorlayout:coordinatorlayout:1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    +--- androidx.customview:customview:1.0.0 (*)
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.constraintlayout:constraintlayout:2.0.1 -> 2.0.4
|    |    +--- androidx.appcompat:appcompat:1.2.0 (*)
|    |    +--- androidx.core:core:1.3.1 (*)
|    |    \--- androidx.constraintlayout:constraintlayout-solver:2.0.4
|    +--- androidx.core:core:1.2.0 -> 1.3.1 (*)
|    +--- androidx.dynamicanimation:dynamicanimation:1.0.0
|    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    +--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    |    \--- androidx.legacy:legacy-support-core-utils:1.0.0
|    |         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |         +--- androidx.documentfile:documentfile:1.0.0
|    |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         +--- androidx.loader:loader:1.0.0 (*)
|    |         +--- androidx.localbroadcastmanager:localbroadcastmanager:1.0.0
|    |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         \--- androidx.print:print:1.0.0
|    |              \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    +--- androidx.annotation:annotation-experimental:1.0.0
|    +--- androidx.fragment:fragment:1.0.0 -> 1.1.0 (*)
|    +--- androidx.lifecycle:lifecycle-runtime:2.0.0 -> 2.1.0 (*)
|    +--- androidx.recyclerview:recyclerview:1.0.0 -> 1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    +--- androidx.customview:customview:1.0.0 (*)
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.transition:transition:1.2.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.0.1 -> 1.3.1 (*)
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.vectordrawable:vectordrawable:1.1.0 (*)
|    \--- androidx.viewpager2:viewpager2:1.0.0
|         +--- androidx.annotation:annotation:1.1.0
|         +--- androidx.fragment:fragment:1.1.0 (*)
|         +--- androidx.recyclerview:recyclerview:1.1.0 (*)
|         +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|         \--- androidx.collection:collection:1.1.0 (*)
+--- androidx.constraintlayout:constraintlayout:2.0.4 (*)
+--- project :module_aliyun:AliyunFileDownLoader:downloadermanager
+--- project :module_aliyun:AlivcMedia
+--- androidx.appcompat:appcompat:{strictly 1.2.0} -> 1.2.0 (c)
+--- com.google.android.material:material:{strictly 1.3.0} -> 1.3.0 (c)
+--- androidx.constraintlayout:constraintlayout:{strictly 2.0.4} -> 2.0.4 (c)
+--- androidx.annotation:annotation:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.core:core:{strictly 1.3.1} -> 1.3.1 (c)
+--- androidx.cursoradapter:cursoradapter:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.fragment:fragment:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.appcompat:appcompat-resources:{strictly 1.2.0} -> 1.2.0 (c)
+--- androidx.drawerlayout:drawerlayout:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.cardview:cardview:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.coordinatorlayout:coordinatorlayout:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.dynamicanimation:dynamicanimation:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.annotation:annotation-experimental:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.lifecycle:lifecycle-runtime:{strictly 2.1.0} -> 2.1.0 (c)
+--- androidx.recyclerview:recyclerview:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.transition:transition:{strictly 1.2.0} -> 1.2.0 (c)
+--- androidx.vectordrawable:vectordrawable:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.viewpager2:viewpager2:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.constraintlayout:constraintlayout-solver:{strictly 2.0.4} -> 2.0.4 (c)
+--- androidx.versionedparcelable:versionedparcelable:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.collection:collection:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.viewpager:viewpager:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.loader:loader:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.activity:activity:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.lifecycle:lifecycle-viewmodel:{strictly 2.1.0} -> 2.1.0 (c)
+--- androidx.vectordrawable:vectordrawable-animated:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.customview:customview:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.legacy:legacy-support-core-utils:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.lifecycle:lifecycle-common:{strictly 2.1.0} -> 2.1.0 (c)
+--- androidx.arch.core:core-common:{strictly 2.1.0} -> 2.1.0 (c)
+--- androidx.lifecycle:lifecycle-livedata:{strictly 2.0.0} -> 2.0.0 (c)
+--- androidx.savedstate:savedstate:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.interpolator:interpolator:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.documentfile:documentfile:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.localbroadcastmanager:localbroadcastmanager:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.print:print:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.arch.core:core-runtime:{strictly 2.0.0} -> 2.0.0 (c)
\--- androidx.lifecycle:lifecycle-livedata-core:{strictly 2.0.0} -> 2.0.0 (c)

_testDebugCompileOnly - Compile only dependencies for '_testDebug' sources. (n)
No dependencies

_testDebugImplementation - Implementation only dependencies for '_testDebug' sources. (n)
No dependencies

_testDebugProvided - Provided dependencies for '_testDebug' sources (deprecated: use '_testDebugCompileOnly' instead). (n)
No dependencies

_testDebugReverseMetadataValues - Metadata Values dependencies for the base Split
No dependencies

_testDebugRuntimeClasspath - Resolved configuration for runtime for variant: _testDebug
+--- androidx.appcompat:appcompat:1.2.0
|    +--- androidx.annotation:annotation:1.1.0
|    +--- androidx.core:core:1.3.0 -> 1.3.1
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.lifecycle:lifecycle-runtime:2.0.0 -> 2.1.0
|    |    |    +--- androidx.lifecycle:lifecycle-common:2.1.0
|    |    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.arch.core:core-common:2.1.0
|    |    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.versionedparcelable:versionedparcelable:1.1.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0
|    |    |         \--- androidx.annotation:annotation:1.1.0
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.cursoradapter:cursoradapter:1.0.0
|    |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    +--- androidx.fragment:fragment:1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    +--- androidx.collection:collection:1.1.0 (*)
|    |    +--- androidx.viewpager:viewpager:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    |    \--- androidx.customview:customview:1.0.0
|    |    |         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |         \--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    +--- androidx.loader:loader:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-livedata:2.0.0
|    |    |    |    +--- androidx.arch.core:core-runtime:2.0.0
|    |    |    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    +--- androidx.lifecycle:lifecycle-livedata-core:2.0.0
|    |    |    |    |    +--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    |    +--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    |    \--- androidx.arch.core:core-runtime:2.0.0 (*)
|    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0
|    |    |         \--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.activity:activity:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-runtime:2.1.0 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-viewmodel:2.1.0 (*)
|    |    |    \--- androidx.savedstate:savedstate:1.0.0
|    |    |         +--- androidx.annotation:annotation:1.1.0
|    |    |         +--- androidx.arch.core:core-common:2.0.1 -> 2.1.0 (*)
|    |    |         \--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.1.0 (*)
|    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0 (*)
|    +--- androidx.appcompat:appcompat-resources:1.2.0
|    |    +--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.0.1 -> 1.3.1 (*)
|    |    +--- androidx.vectordrawable:vectordrawable:1.1.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    |    \--- androidx.collection:collection:1.1.0 (*)
|    |    \--- androidx.vectordrawable:vectordrawable-animated:1.1.0
|    |         +--- androidx.vectordrawable:vectordrawable:1.1.0 (*)
|    |         +--- androidx.interpolator:interpolator:1.0.0
|    |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         \--- androidx.collection:collection:1.1.0 (*)
|    +--- androidx.drawerlayout:drawerlayout:1.0.0
|    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    \--- androidx.customview:customview:1.0.0 (*)
|    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
+--- com.google.android.material:material:1.3.0
|    +--- androidx.annotation:annotation:1.0.1 -> 1.1.0
|    +--- androidx.appcompat:appcompat:1.1.0 -> 1.2.0 (*)
|    +--- androidx.cardview:cardview:1.0.0
|    |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    +--- androidx.coordinatorlayout:coordinatorlayout:1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    +--- androidx.customview:customview:1.0.0 (*)
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.constraintlayout:constraintlayout:2.0.1 -> 2.0.4
|    |    +--- androidx.appcompat:appcompat:1.2.0 (*)
|    |    +--- androidx.core:core:1.3.1 (*)
|    |    \--- androidx.constraintlayout:constraintlayout-solver:2.0.4
|    +--- androidx.core:core:1.2.0 -> 1.3.1 (*)
|    +--- androidx.dynamicanimation:dynamicanimation:1.0.0
|    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    +--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    |    \--- androidx.legacy:legacy-support-core-utils:1.0.0
|    |         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |         +--- androidx.documentfile:documentfile:1.0.0
|    |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         +--- androidx.loader:loader:1.0.0 (*)
|    |         +--- androidx.localbroadcastmanager:localbroadcastmanager:1.0.0
|    |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         \--- androidx.print:print:1.0.0
|    |              \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    +--- androidx.annotation:annotation-experimental:1.0.0
|    +--- androidx.fragment:fragment:1.0.0 -> 1.1.0 (*)
|    +--- androidx.lifecycle:lifecycle-runtime:2.0.0 -> 2.1.0 (*)
|    +--- androidx.recyclerview:recyclerview:1.0.0 -> 1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    +--- androidx.customview:customview:1.0.0 (*)
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.transition:transition:1.2.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.0.1 -> 1.3.1 (*)
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.vectordrawable:vectordrawable:1.1.0 (*)
|    \--- androidx.viewpager2:viewpager2:1.0.0
|         +--- androidx.annotation:annotation:1.1.0
|         +--- androidx.fragment:fragment:1.1.0 (*)
|         +--- androidx.recyclerview:recyclerview:1.1.0 (*)
|         +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|         \--- androidx.collection:collection:1.1.0 (*)
+--- androidx.constraintlayout:constraintlayout:2.0.4 (*)
+--- project :module_aliyun:AliyunFileDownLoader:downloadermanager
|    +--- androidx.appcompat:appcompat:1.2.0 (*)
|    \--- com.google.android.material:material:1.3.0 (*)
\--- project :module_aliyun:AlivcMedia
     +--- androidx.appcompat:appcompat:1.2.0 (*)
     \--- com.google.android.material:material:1.3.0 (*)

_testDebugRuntimeElements - Runtime elements for _testDebug (n)
No dependencies

_testDebugRuntimeOnly - Runtime only dependencies for '_testDebug' sources. (n)
No dependencies

_testDebugUnitTestAnnotationProcessorClasspath - Resolved configuration for annotation-processor for variant: _testDebugUnitTest
No dependencies

_testDebugUnitTestCompileClasspath - Resolved configuration for compilation for variant: _testDebugUnitTest
+--- androidx.appcompat:appcompat:1.2.0
|    +--- androidx.annotation:annotation:1.1.0
|    +--- androidx.core:core:1.3.0 -> 1.3.1
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.lifecycle:lifecycle-runtime:2.0.0 -> 2.1.0
|    |    |    +--- androidx.lifecycle:lifecycle-common:2.1.0
|    |    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.arch.core:core-common:2.1.0
|    |    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    \--- androidx.versionedparcelable:versionedparcelable:1.1.0
|    |         +--- androidx.annotation:annotation:1.1.0
|    |         \--- androidx.collection:collection:1.0.0 -> 1.1.0
|    |              \--- androidx.annotation:annotation:1.1.0
|    +--- androidx.cursoradapter:cursoradapter:1.0.0
|    |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    +--- androidx.fragment:fragment:1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    +--- androidx.collection:collection:1.1.0 (*)
|    |    +--- androidx.viewpager:viewpager:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    |    \--- androidx.customview:customview:1.0.0
|    |    |         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |         \--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    +--- androidx.loader:loader:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-livedata:2.0.0
|    |    |    |    +--- androidx.arch.core:core-runtime:2.0.0
|    |    |    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    +--- androidx.lifecycle:lifecycle-livedata-core:2.0.0
|    |    |    |    |    +--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    |    +--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    |    \--- androidx.arch.core:core-runtime:2.0.0 (*)
|    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0
|    |    |         \--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.activity:activity:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-runtime:2.1.0 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-viewmodel:2.1.0 (*)
|    |    |    \--- androidx.savedstate:savedstate:1.0.0
|    |    |         +--- androidx.annotation:annotation:1.1.0
|    |    |         +--- androidx.arch.core:core-common:2.0.1 -> 2.1.0 (*)
|    |    |         \--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.1.0 (*)
|    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0 (*)
|    +--- androidx.appcompat:appcompat-resources:1.2.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.0.1 -> 1.3.1 (*)
|    |    +--- androidx.vectordrawable:vectordrawable:1.1.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    |    \--- androidx.collection:collection:1.1.0 (*)
|    |    \--- androidx.vectordrawable:vectordrawable-animated:1.1.0
|    |         +--- androidx.vectordrawable:vectordrawable:1.1.0 (*)
|    |         +--- androidx.interpolator:interpolator:1.0.0
|    |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         \--- androidx.collection:collection:1.1.0 (*)
|    \--- androidx.drawerlayout:drawerlayout:1.0.0
|         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|         +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|         \--- androidx.customview:customview:1.0.0 (*)
+--- com.google.android.material:material:1.3.0
|    +--- androidx.annotation:annotation:1.0.1 -> 1.1.0
|    +--- androidx.appcompat:appcompat:1.1.0 -> 1.2.0 (*)
|    +--- androidx.cardview:cardview:1.0.0
|    |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    +--- androidx.coordinatorlayout:coordinatorlayout:1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    +--- androidx.customview:customview:1.0.0 (*)
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.constraintlayout:constraintlayout:2.0.1 -> 2.0.4
|    |    +--- androidx.appcompat:appcompat:1.2.0 (*)
|    |    +--- androidx.core:core:1.3.1 (*)
|    |    \--- androidx.constraintlayout:constraintlayout-solver:2.0.4
|    +--- androidx.core:core:1.2.0 -> 1.3.1 (*)
|    +--- androidx.dynamicanimation:dynamicanimation:1.0.0
|    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    +--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    |    \--- androidx.legacy:legacy-support-core-utils:1.0.0
|    |         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |         +--- androidx.documentfile:documentfile:1.0.0
|    |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         +--- androidx.loader:loader:1.0.0 (*)
|    |         +--- androidx.localbroadcastmanager:localbroadcastmanager:1.0.0
|    |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         \--- androidx.print:print:1.0.0
|    |              \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    +--- androidx.annotation:annotation-experimental:1.0.0
|    +--- androidx.fragment:fragment:1.0.0 -> 1.1.0 (*)
|    +--- androidx.lifecycle:lifecycle-runtime:2.0.0 -> 2.1.0 (*)
|    +--- androidx.recyclerview:recyclerview:1.0.0 -> 1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    +--- androidx.customview:customview:1.0.0 (*)
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.transition:transition:1.2.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.0.1 -> 1.3.1 (*)
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.vectordrawable:vectordrawable:1.1.0 (*)
|    \--- androidx.viewpager2:viewpager2:1.0.0
|         +--- androidx.annotation:annotation:1.1.0
|         +--- androidx.fragment:fragment:1.1.0 (*)
|         +--- androidx.recyclerview:recyclerview:1.1.0 (*)
|         +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|         \--- androidx.collection:collection:1.1.0 (*)
+--- androidx.constraintlayout:constraintlayout:2.0.4 (*)
+--- project :module_aliyun:AliyunFileDownLoader:downloadermanager
+--- project :module_aliyun:AlivcMedia
+--- androidx.appcompat:appcompat:{strictly 1.2.0} -> 1.2.0 (c)
+--- com.google.android.material:material:{strictly 1.3.0} -> 1.3.0 (c)
+--- androidx.constraintlayout:constraintlayout:{strictly 2.0.4} -> 2.0.4 (c)
+--- androidx.annotation:annotation:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.core:core:{strictly 1.3.1} -> 1.3.1 (c)
+--- androidx.cursoradapter:cursoradapter:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.fragment:fragment:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.appcompat:appcompat-resources:{strictly 1.2.0} -> 1.2.0 (c)
+--- androidx.drawerlayout:drawerlayout:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.cardview:cardview:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.coordinatorlayout:coordinatorlayout:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.dynamicanimation:dynamicanimation:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.annotation:annotation-experimental:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.lifecycle:lifecycle-runtime:{strictly 2.1.0} -> 2.1.0 (c)
+--- androidx.recyclerview:recyclerview:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.transition:transition:{strictly 1.2.0} -> 1.2.0 (c)
+--- androidx.vectordrawable:vectordrawable:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.viewpager2:viewpager2:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.constraintlayout:constraintlayout-solver:{strictly 2.0.4} -> 2.0.4 (c)
+--- androidx.versionedparcelable:versionedparcelable:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.collection:collection:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.viewpager:viewpager:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.loader:loader:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.activity:activity:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.lifecycle:lifecycle-viewmodel:{strictly 2.1.0} -> 2.1.0 (c)
+--- androidx.vectordrawable:vectordrawable-animated:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.customview:customview:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.legacy:legacy-support-core-utils:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.lifecycle:lifecycle-common:{strictly 2.1.0} -> 2.1.0 (c)
+--- androidx.arch.core:core-common:{strictly 2.1.0} -> 2.1.0 (c)
+--- androidx.lifecycle:lifecycle-livedata:{strictly 2.0.0} -> 2.0.0 (c)
+--- androidx.savedstate:savedstate:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.interpolator:interpolator:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.documentfile:documentfile:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.localbroadcastmanager:localbroadcastmanager:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.print:print:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.arch.core:core-runtime:{strictly 2.0.0} -> 2.0.0 (c)
\--- androidx.lifecycle:lifecycle-livedata-core:{strictly 2.0.0} -> 2.0.0 (c)

_testDebugUnitTestRuntimeClasspath - Resolved configuration for runtime for variant: _testDebugUnitTest
+--- androidx.appcompat:appcompat:1.2.0
|    +--- androidx.annotation:annotation:1.1.0
|    +--- androidx.core:core:1.3.0 -> 1.3.1
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.lifecycle:lifecycle-runtime:2.0.0 -> 2.1.0
|    |    |    +--- androidx.lifecycle:lifecycle-common:2.1.0
|    |    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.arch.core:core-common:2.1.0
|    |    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.versionedparcelable:versionedparcelable:1.1.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0
|    |    |         \--- androidx.annotation:annotation:1.1.0
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.cursoradapter:cursoradapter:1.0.0
|    |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    +--- androidx.fragment:fragment:1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    +--- androidx.collection:collection:1.1.0 (*)
|    |    +--- androidx.viewpager:viewpager:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    |    \--- androidx.customview:customview:1.0.0
|    |    |         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |         \--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    +--- androidx.loader:loader:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-livedata:2.0.0
|    |    |    |    +--- androidx.arch.core:core-runtime:2.0.0
|    |    |    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    +--- androidx.lifecycle:lifecycle-livedata-core:2.0.0
|    |    |    |    |    +--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    |    +--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    |    \--- androidx.arch.core:core-runtime:2.0.0 (*)
|    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0
|    |    |         \--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.activity:activity:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-runtime:2.1.0 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-viewmodel:2.1.0 (*)
|    |    |    \--- androidx.savedstate:savedstate:1.0.0
|    |    |         +--- androidx.annotation:annotation:1.1.0
|    |    |         +--- androidx.arch.core:core-common:2.0.1 -> 2.1.0 (*)
|    |    |         \--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.1.0 (*)
|    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0 (*)
|    +--- androidx.appcompat:appcompat-resources:1.2.0
|    |    +--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.0.1 -> 1.3.1 (*)
|    |    +--- androidx.vectordrawable:vectordrawable:1.1.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    |    \--- androidx.collection:collection:1.1.0 (*)
|    |    \--- androidx.vectordrawable:vectordrawable-animated:1.1.0
|    |         +--- androidx.vectordrawable:vectordrawable:1.1.0 (*)
|    |         +--- androidx.interpolator:interpolator:1.0.0
|    |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         \--- androidx.collection:collection:1.1.0 (*)
|    +--- androidx.drawerlayout:drawerlayout:1.0.0
|    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    \--- androidx.customview:customview:1.0.0 (*)
|    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
+--- com.google.android.material:material:1.3.0
|    +--- androidx.annotation:annotation:1.0.1 -> 1.1.0
|    +--- androidx.appcompat:appcompat:1.1.0 -> 1.2.0 (*)
|    +--- androidx.cardview:cardview:1.0.0
|    |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    +--- androidx.coordinatorlayout:coordinatorlayout:1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    +--- androidx.customview:customview:1.0.0 (*)
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.constraintlayout:constraintlayout:2.0.1 -> 2.0.4
|    |    +--- androidx.appcompat:appcompat:1.2.0 (*)
|    |    +--- androidx.core:core:1.3.1 (*)
|    |    \--- androidx.constraintlayout:constraintlayout-solver:2.0.4
|    +--- androidx.core:core:1.2.0 -> 1.3.1 (*)
|    +--- androidx.dynamicanimation:dynamicanimation:1.0.0
|    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    +--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    |    \--- androidx.legacy:legacy-support-core-utils:1.0.0
|    |         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |         +--- androidx.documentfile:documentfile:1.0.0
|    |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         +--- androidx.loader:loader:1.0.0 (*)
|    |         +--- androidx.localbroadcastmanager:localbroadcastmanager:1.0.0
|    |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         \--- androidx.print:print:1.0.0
|    |              \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    +--- androidx.annotation:annotation-experimental:1.0.0
|    +--- androidx.fragment:fragment:1.0.0 -> 1.1.0 (*)
|    +--- androidx.lifecycle:lifecycle-runtime:2.0.0 -> 2.1.0 (*)
|    +--- androidx.recyclerview:recyclerview:1.0.0 -> 1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    +--- androidx.customview:customview:1.0.0 (*)
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.transition:transition:1.2.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.0.1 -> 1.3.1 (*)
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.vectordrawable:vectordrawable:1.1.0 (*)
|    \--- androidx.viewpager2:viewpager2:1.0.0
|         +--- androidx.annotation:annotation:1.1.0
|         +--- androidx.fragment:fragment:1.1.0 (*)
|         +--- androidx.recyclerview:recyclerview:1.1.0 (*)
|         +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|         \--- androidx.collection:collection:1.1.0 (*)
+--- androidx.constraintlayout:constraintlayout:2.0.4 (*)
+--- project :module_aliyun:AliyunFileDownLoader:downloadermanager
|    +--- androidx.appcompat:appcompat:1.2.0 (*)
|    \--- com.google.android.material:material:1.3.0 (*)
\--- project :module_aliyun:AlivcMedia
     +--- androidx.appcompat:appcompat:1.2.0 (*)
     \--- com.google.android.material:material:1.3.0 (*)

_testDebugWearApp - Link to a wear app to embed for object '_testDebug'. (n)
No dependencies

_testDebugWearBundling - Resolved Configuration for wear app bundling for variant: _testDebug
No dependencies

_testImplementation - Implementation only dependencies for '_test' sources. (n)
No dependencies

_testProvided - Provided dependencies for '_test' sources (deprecated: use '_testCompileOnly' instead). (n)
No dependencies

_testReleaseAabPublication - Bundle Publication for _testRelease (n)
No dependencies

_testReleaseAnnotationProcessor - Classpath for the annotation processor for '_testRelease'. (n)
No dependencies

_testReleaseAnnotationProcessorClasspath - Resolved configuration for annotation-processor for variant: _testRelease
No dependencies

_testReleaseApi - API dependencies for '_testRelease' sources. (n)
No dependencies

_testReleaseApiElements - API elements for _testRelease (n)
No dependencies

_testReleaseApk - Apk dependencies for '_testRelease' sources (deprecated: use '_testReleaseRuntimeOnly' instead). (n)
No dependencies

_testReleaseApkPublication - APK publication for _testRelease (n)
No dependencies

_testReleaseCompile - Compile dependencies for '_testRelease' sources (deprecated: use '_testReleaseImplementation' instead). (n)
No dependencies

_testReleaseCompileClasspath - Resolved configuration for compilation for variant: _testRelease
+--- androidx.appcompat:appcompat:1.2.0
|    +--- androidx.annotation:annotation:1.1.0
|    +--- androidx.core:core:1.3.0 -> 1.3.1
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.lifecycle:lifecycle-runtime:2.0.0 -> 2.1.0
|    |    |    +--- androidx.lifecycle:lifecycle-common:2.1.0
|    |    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.arch.core:core-common:2.1.0
|    |    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    \--- androidx.versionedparcelable:versionedparcelable:1.1.0
|    |         +--- androidx.annotation:annotation:1.1.0
|    |         \--- androidx.collection:collection:1.0.0 -> 1.1.0
|    |              \--- androidx.annotation:annotation:1.1.0
|    +--- androidx.cursoradapter:cursoradapter:1.0.0
|    |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    +--- androidx.fragment:fragment:1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    +--- androidx.collection:collection:1.1.0 (*)
|    |    +--- androidx.viewpager:viewpager:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    |    \--- androidx.customview:customview:1.0.0
|    |    |         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |         \--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    +--- androidx.loader:loader:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-livedata:2.0.0
|    |    |    |    +--- androidx.arch.core:core-runtime:2.0.0
|    |    |    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    +--- androidx.lifecycle:lifecycle-livedata-core:2.0.0
|    |    |    |    |    +--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    |    +--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    |    \--- androidx.arch.core:core-runtime:2.0.0 (*)
|    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0
|    |    |         \--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.activity:activity:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-runtime:2.1.0 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-viewmodel:2.1.0 (*)
|    |    |    \--- androidx.savedstate:savedstate:1.0.0
|    |    |         +--- androidx.annotation:annotation:1.1.0
|    |    |         +--- androidx.arch.core:core-common:2.0.1 -> 2.1.0 (*)
|    |    |         \--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.1.0 (*)
|    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0 (*)
|    +--- androidx.appcompat:appcompat-resources:1.2.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.0.1 -> 1.3.1 (*)
|    |    +--- androidx.vectordrawable:vectordrawable:1.1.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    |    \--- androidx.collection:collection:1.1.0 (*)
|    |    \--- androidx.vectordrawable:vectordrawable-animated:1.1.0
|    |         +--- androidx.vectordrawable:vectordrawable:1.1.0 (*)
|    |         +--- androidx.interpolator:interpolator:1.0.0
|    |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         \--- androidx.collection:collection:1.1.0 (*)
|    \--- androidx.drawerlayout:drawerlayout:1.0.0
|         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|         +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|         \--- androidx.customview:customview:1.0.0 (*)
+--- com.google.android.material:material:1.3.0
|    +--- androidx.annotation:annotation:1.0.1 -> 1.1.0
|    +--- androidx.appcompat:appcompat:1.1.0 -> 1.2.0 (*)
|    +--- androidx.cardview:cardview:1.0.0
|    |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    +--- androidx.coordinatorlayout:coordinatorlayout:1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    +--- androidx.customview:customview:1.0.0 (*)
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.constraintlayout:constraintlayout:2.0.1 -> 2.0.4
|    |    +--- androidx.appcompat:appcompat:1.2.0 (*)
|    |    +--- androidx.core:core:1.3.1 (*)
|    |    \--- androidx.constraintlayout:constraintlayout-solver:2.0.4
|    +--- androidx.core:core:1.2.0 -> 1.3.1 (*)
|    +--- androidx.dynamicanimation:dynamicanimation:1.0.0
|    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    +--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    |    \--- androidx.legacy:legacy-support-core-utils:1.0.0
|    |         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |         +--- androidx.documentfile:documentfile:1.0.0
|    |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         +--- androidx.loader:loader:1.0.0 (*)
|    |         +--- androidx.localbroadcastmanager:localbroadcastmanager:1.0.0
|    |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         \--- androidx.print:print:1.0.0
|    |              \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    +--- androidx.annotation:annotation-experimental:1.0.0
|    +--- androidx.fragment:fragment:1.0.0 -> 1.1.0 (*)
|    +--- androidx.lifecycle:lifecycle-runtime:2.0.0 -> 2.1.0 (*)
|    +--- androidx.recyclerview:recyclerview:1.0.0 -> 1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    +--- androidx.customview:customview:1.0.0 (*)
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.transition:transition:1.2.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.0.1 -> 1.3.1 (*)
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.vectordrawable:vectordrawable:1.1.0 (*)
|    \--- androidx.viewpager2:viewpager2:1.0.0
|         +--- androidx.annotation:annotation:1.1.0
|         +--- androidx.fragment:fragment:1.1.0 (*)
|         +--- androidx.recyclerview:recyclerview:1.1.0 (*)
|         +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|         \--- androidx.collection:collection:1.1.0 (*)
+--- androidx.constraintlayout:constraintlayout:2.0.4 (*)
+--- project :module_aliyun:AliyunFileDownLoader:downloadermanager
+--- project :module_aliyun:AlivcMedia
+--- androidx.appcompat:appcompat:{strictly 1.2.0} -> 1.2.0 (c)
+--- com.google.android.material:material:{strictly 1.3.0} -> 1.3.0 (c)
+--- androidx.constraintlayout:constraintlayout:{strictly 2.0.4} -> 2.0.4 (c)
+--- androidx.annotation:annotation:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.core:core:{strictly 1.3.1} -> 1.3.1 (c)
+--- androidx.cursoradapter:cursoradapter:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.fragment:fragment:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.appcompat:appcompat-resources:{strictly 1.2.0} -> 1.2.0 (c)
+--- androidx.drawerlayout:drawerlayout:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.cardview:cardview:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.coordinatorlayout:coordinatorlayout:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.dynamicanimation:dynamicanimation:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.annotation:annotation-experimental:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.lifecycle:lifecycle-runtime:{strictly 2.1.0} -> 2.1.0 (c)
+--- androidx.recyclerview:recyclerview:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.transition:transition:{strictly 1.2.0} -> 1.2.0 (c)
+--- androidx.vectordrawable:vectordrawable:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.viewpager2:viewpager2:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.constraintlayout:constraintlayout-solver:{strictly 2.0.4} -> 2.0.4 (c)
+--- androidx.versionedparcelable:versionedparcelable:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.collection:collection:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.viewpager:viewpager:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.loader:loader:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.activity:activity:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.lifecycle:lifecycle-viewmodel:{strictly 2.1.0} -> 2.1.0 (c)
+--- androidx.vectordrawable:vectordrawable-animated:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.customview:customview:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.legacy:legacy-support-core-utils:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.lifecycle:lifecycle-common:{strictly 2.1.0} -> 2.1.0 (c)
+--- androidx.arch.core:core-common:{strictly 2.1.0} -> 2.1.0 (c)
+--- androidx.lifecycle:lifecycle-livedata:{strictly 2.0.0} -> 2.0.0 (c)
+--- androidx.savedstate:savedstate:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.interpolator:interpolator:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.documentfile:documentfile:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.localbroadcastmanager:localbroadcastmanager:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.print:print:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.arch.core:core-runtime:{strictly 2.0.0} -> 2.0.0 (c)
\--- androidx.lifecycle:lifecycle-livedata-core:{strictly 2.0.0} -> 2.0.0 (c)

_testReleaseCompileOnly - Compile only dependencies for '_testRelease' sources. (n)
No dependencies

_testReleaseImplementation - Implementation only dependencies for '_testRelease' sources. (n)
No dependencies

_testReleaseProvided - Provided dependencies for '_testRelease' sources (deprecated: use '_testReleaseCompileOnly' instead). (n)
No dependencies

_testReleaseReverseMetadataValues - Metadata Values dependencies for the base Split
No dependencies

_testReleaseRuntimeClasspath - Resolved configuration for runtime for variant: _testRelease
+--- androidx.appcompat:appcompat:1.2.0
|    +--- androidx.annotation:annotation:1.1.0
|    +--- androidx.core:core:1.3.0 -> 1.3.1
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.lifecycle:lifecycle-runtime:2.0.0 -> 2.1.0
|    |    |    +--- androidx.lifecycle:lifecycle-common:2.1.0
|    |    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.arch.core:core-common:2.1.0
|    |    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.versionedparcelable:versionedparcelable:1.1.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0
|    |    |         \--- androidx.annotation:annotation:1.1.0
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.cursoradapter:cursoradapter:1.0.0
|    |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    +--- androidx.fragment:fragment:1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    +--- androidx.collection:collection:1.1.0 (*)
|    |    +--- androidx.viewpager:viewpager:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    |    \--- androidx.customview:customview:1.0.0
|    |    |         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |         \--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    +--- androidx.loader:loader:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-livedata:2.0.0
|    |    |    |    +--- androidx.arch.core:core-runtime:2.0.0
|    |    |    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    +--- androidx.lifecycle:lifecycle-livedata-core:2.0.0
|    |    |    |    |    +--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    |    +--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    |    \--- androidx.arch.core:core-runtime:2.0.0 (*)
|    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0
|    |    |         \--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.activity:activity:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-runtime:2.1.0 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-viewmodel:2.1.0 (*)
|    |    |    \--- androidx.savedstate:savedstate:1.0.0
|    |    |         +--- androidx.annotation:annotation:1.1.0
|    |    |         +--- androidx.arch.core:core-common:2.0.1 -> 2.1.0 (*)
|    |    |         \--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.1.0 (*)
|    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0 (*)
|    +--- androidx.appcompat:appcompat-resources:1.2.0
|    |    +--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.0.1 -> 1.3.1 (*)
|    |    +--- androidx.vectordrawable:vectordrawable:1.1.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    |    \--- androidx.collection:collection:1.1.0 (*)
|    |    \--- androidx.vectordrawable:vectordrawable-animated:1.1.0
|    |         +--- androidx.vectordrawable:vectordrawable:1.1.0 (*)
|    |         +--- androidx.interpolator:interpolator:1.0.0
|    |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         \--- androidx.collection:collection:1.1.0 (*)
|    +--- androidx.drawerlayout:drawerlayout:1.0.0
|    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    \--- androidx.customview:customview:1.0.0 (*)
|    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
+--- com.google.android.material:material:1.3.0
|    +--- androidx.annotation:annotation:1.0.1 -> 1.1.0
|    +--- androidx.appcompat:appcompat:1.1.0 -> 1.2.0 (*)
|    +--- androidx.cardview:cardview:1.0.0
|    |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    +--- androidx.coordinatorlayout:coordinatorlayout:1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    +--- androidx.customview:customview:1.0.0 (*)
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.constraintlayout:constraintlayout:2.0.1 -> 2.0.4
|    |    +--- androidx.appcompat:appcompat:1.2.0 (*)
|    |    +--- androidx.core:core:1.3.1 (*)
|    |    \--- androidx.constraintlayout:constraintlayout-solver:2.0.4
|    +--- androidx.core:core:1.2.0 -> 1.3.1 (*)
|    +--- androidx.dynamicanimation:dynamicanimation:1.0.0
|    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    +--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    |    \--- androidx.legacy:legacy-support-core-utils:1.0.0
|    |         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |         +--- androidx.documentfile:documentfile:1.0.0
|    |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         +--- androidx.loader:loader:1.0.0 (*)
|    |         +--- androidx.localbroadcastmanager:localbroadcastmanager:1.0.0
|    |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         \--- androidx.print:print:1.0.0
|    |              \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    +--- androidx.annotation:annotation-experimental:1.0.0
|    +--- androidx.fragment:fragment:1.0.0 -> 1.1.0 (*)
|    +--- androidx.lifecycle:lifecycle-runtime:2.0.0 -> 2.1.0 (*)
|    +--- androidx.recyclerview:recyclerview:1.0.0 -> 1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    +--- androidx.customview:customview:1.0.0 (*)
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.transition:transition:1.2.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.0.1 -> 1.3.1 (*)
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.vectordrawable:vectordrawable:1.1.0 (*)
|    \--- androidx.viewpager2:viewpager2:1.0.0
|         +--- androidx.annotation:annotation:1.1.0
|         +--- androidx.fragment:fragment:1.1.0 (*)
|         +--- androidx.recyclerview:recyclerview:1.1.0 (*)
|         +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|         \--- androidx.collection:collection:1.1.0 (*)
+--- androidx.constraintlayout:constraintlayout:2.0.4 (*)
+--- project :module_aliyun:AliyunFileDownLoader:downloadermanager
|    +--- androidx.appcompat:appcompat:1.2.0 (*)
|    \--- com.google.android.material:material:1.3.0 (*)
\--- project :module_aliyun:AlivcMedia
     +--- androidx.appcompat:appcompat:1.2.0 (*)
     \--- com.google.android.material:material:1.3.0 (*)

_testReleaseRuntimeElements - Runtime elements for _testRelease (n)
No dependencies

_testReleaseRuntimeOnly - Runtime only dependencies for '_testRelease' sources. (n)
No dependencies

_testReleaseUnitTestAnnotationProcessorClasspath - Resolved configuration for annotation-processor for variant: _testReleaseUnitTest
No dependencies

_testReleaseUnitTestCompileClasspath - Resolved configuration for compilation for variant: _testReleaseUnitTest
+--- androidx.appcompat:appcompat:1.2.0
|    +--- androidx.annotation:annotation:1.1.0
|    +--- androidx.core:core:1.3.0 -> 1.3.1
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.lifecycle:lifecycle-runtime:2.0.0 -> 2.1.0
|    |    |    +--- androidx.lifecycle:lifecycle-common:2.1.0
|    |    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.arch.core:core-common:2.1.0
|    |    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    \--- androidx.versionedparcelable:versionedparcelable:1.1.0
|    |         +--- androidx.annotation:annotation:1.1.0
|    |         \--- androidx.collection:collection:1.0.0 -> 1.1.0
|    |              \--- androidx.annotation:annotation:1.1.0
|    +--- androidx.cursoradapter:cursoradapter:1.0.0
|    |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    +--- androidx.fragment:fragment:1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    +--- androidx.collection:collection:1.1.0 (*)
|    |    +--- androidx.viewpager:viewpager:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    |    \--- androidx.customview:customview:1.0.0
|    |    |         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |         \--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    +--- androidx.loader:loader:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-livedata:2.0.0
|    |    |    |    +--- androidx.arch.core:core-runtime:2.0.0
|    |    |    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    +--- androidx.lifecycle:lifecycle-livedata-core:2.0.0
|    |    |    |    |    +--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    |    +--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    |    \--- androidx.arch.core:core-runtime:2.0.0 (*)
|    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0
|    |    |         \--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.activity:activity:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-runtime:2.1.0 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-viewmodel:2.1.0 (*)
|    |    |    \--- androidx.savedstate:savedstate:1.0.0
|    |    |         +--- androidx.annotation:annotation:1.1.0
|    |    |         +--- androidx.arch.core:core-common:2.0.1 -> 2.1.0 (*)
|    |    |         \--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.1.0 (*)
|    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0 (*)
|    +--- androidx.appcompat:appcompat-resources:1.2.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.0.1 -> 1.3.1 (*)
|    |    +--- androidx.vectordrawable:vectordrawable:1.1.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    |    \--- androidx.collection:collection:1.1.0 (*)
|    |    \--- androidx.vectordrawable:vectordrawable-animated:1.1.0
|    |         +--- androidx.vectordrawable:vectordrawable:1.1.0 (*)
|    |         +--- androidx.interpolator:interpolator:1.0.0
|    |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         \--- androidx.collection:collection:1.1.0 (*)
|    \--- androidx.drawerlayout:drawerlayout:1.0.0
|         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|         +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|         \--- androidx.customview:customview:1.0.0 (*)
+--- com.google.android.material:material:1.3.0
|    +--- androidx.annotation:annotation:1.0.1 -> 1.1.0
|    +--- androidx.appcompat:appcompat:1.1.0 -> 1.2.0 (*)
|    +--- androidx.cardview:cardview:1.0.0
|    |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    +--- androidx.coordinatorlayout:coordinatorlayout:1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    +--- androidx.customview:customview:1.0.0 (*)
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.constraintlayout:constraintlayout:2.0.1 -> 2.0.4
|    |    +--- androidx.appcompat:appcompat:1.2.0 (*)
|    |    +--- androidx.core:core:1.3.1 (*)
|    |    \--- androidx.constraintlayout:constraintlayout-solver:2.0.4
|    +--- androidx.core:core:1.2.0 -> 1.3.1 (*)
|    +--- androidx.dynamicanimation:dynamicanimation:1.0.0
|    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    +--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    |    \--- androidx.legacy:legacy-support-core-utils:1.0.0
|    |         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |         +--- androidx.documentfile:documentfile:1.0.0
|    |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         +--- androidx.loader:loader:1.0.0 (*)
|    |         +--- androidx.localbroadcastmanager:localbroadcastmanager:1.0.0
|    |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         \--- androidx.print:print:1.0.0
|    |              \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    +--- androidx.annotation:annotation-experimental:1.0.0
|    +--- androidx.fragment:fragment:1.0.0 -> 1.1.0 (*)
|    +--- androidx.lifecycle:lifecycle-runtime:2.0.0 -> 2.1.0 (*)
|    +--- androidx.recyclerview:recyclerview:1.0.0 -> 1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    +--- androidx.customview:customview:1.0.0 (*)
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.transition:transition:1.2.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.0.1 -> 1.3.1 (*)
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.vectordrawable:vectordrawable:1.1.0 (*)
|    \--- androidx.viewpager2:viewpager2:1.0.0
|         +--- androidx.annotation:annotation:1.1.0
|         +--- androidx.fragment:fragment:1.1.0 (*)
|         +--- androidx.recyclerview:recyclerview:1.1.0 (*)
|         +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|         \--- androidx.collection:collection:1.1.0 (*)
+--- androidx.constraintlayout:constraintlayout:2.0.4 (*)
+--- project :module_aliyun:AliyunFileDownLoader:downloadermanager
+--- project :module_aliyun:AlivcMedia
+--- androidx.appcompat:appcompat:{strictly 1.2.0} -> 1.2.0 (c)
+--- com.google.android.material:material:{strictly 1.3.0} -> 1.3.0 (c)
+--- androidx.constraintlayout:constraintlayout:{strictly 2.0.4} -> 2.0.4 (c)
+--- androidx.annotation:annotation:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.core:core:{strictly 1.3.1} -> 1.3.1 (c)
+--- androidx.cursoradapter:cursoradapter:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.fragment:fragment:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.appcompat:appcompat-resources:{strictly 1.2.0} -> 1.2.0 (c)
+--- androidx.drawerlayout:drawerlayout:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.cardview:cardview:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.coordinatorlayout:coordinatorlayout:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.dynamicanimation:dynamicanimation:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.annotation:annotation-experimental:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.lifecycle:lifecycle-runtime:{strictly 2.1.0} -> 2.1.0 (c)
+--- androidx.recyclerview:recyclerview:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.transition:transition:{strictly 1.2.0} -> 1.2.0 (c)
+--- androidx.vectordrawable:vectordrawable:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.viewpager2:viewpager2:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.constraintlayout:constraintlayout-solver:{strictly 2.0.4} -> 2.0.4 (c)
+--- androidx.versionedparcelable:versionedparcelable:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.collection:collection:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.viewpager:viewpager:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.loader:loader:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.activity:activity:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.lifecycle:lifecycle-viewmodel:{strictly 2.1.0} -> 2.1.0 (c)
+--- androidx.vectordrawable:vectordrawable-animated:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.customview:customview:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.legacy:legacy-support-core-utils:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.lifecycle:lifecycle-common:{strictly 2.1.0} -> 2.1.0 (c)
+--- androidx.arch.core:core-common:{strictly 2.1.0} -> 2.1.0 (c)
+--- androidx.lifecycle:lifecycle-livedata:{strictly 2.0.0} -> 2.0.0 (c)
+--- androidx.savedstate:savedstate:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.interpolator:interpolator:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.documentfile:documentfile:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.localbroadcastmanager:localbroadcastmanager:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.print:print:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.arch.core:core-runtime:{strictly 2.0.0} -> 2.0.0 (c)
\--- androidx.lifecycle:lifecycle-livedata-core:{strictly 2.0.0} -> 2.0.0 (c)

_testReleaseUnitTestRuntimeClasspath - Resolved configuration for runtime for variant: _testReleaseUnitTest
+--- androidx.appcompat:appcompat:1.2.0
|    +--- androidx.annotation:annotation:1.1.0
|    +--- androidx.core:core:1.3.0 -> 1.3.1
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.lifecycle:lifecycle-runtime:2.0.0 -> 2.1.0
|    |    |    +--- androidx.lifecycle:lifecycle-common:2.1.0
|    |    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.arch.core:core-common:2.1.0
|    |    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.versionedparcelable:versionedparcelable:1.1.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0
|    |    |         \--- androidx.annotation:annotation:1.1.0
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.cursoradapter:cursoradapter:1.0.0
|    |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    +--- androidx.fragment:fragment:1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    +--- androidx.collection:collection:1.1.0 (*)
|    |    +--- androidx.viewpager:viewpager:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    |    \--- androidx.customview:customview:1.0.0
|    |    |         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |         \--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    +--- androidx.loader:loader:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-livedata:2.0.0
|    |    |    |    +--- androidx.arch.core:core-runtime:2.0.0
|    |    |    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    +--- androidx.lifecycle:lifecycle-livedata-core:2.0.0
|    |    |    |    |    +--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    |    +--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    |    \--- androidx.arch.core:core-runtime:2.0.0 (*)
|    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0
|    |    |         \--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.activity:activity:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-runtime:2.1.0 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-viewmodel:2.1.0 (*)
|    |    |    \--- androidx.savedstate:savedstate:1.0.0
|    |    |         +--- androidx.annotation:annotation:1.1.0
|    |    |         +--- androidx.arch.core:core-common:2.0.1 -> 2.1.0 (*)
|    |    |         \--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.1.0 (*)
|    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0 (*)
|    +--- androidx.appcompat:appcompat-resources:1.2.0
|    |    +--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.0.1 -> 1.3.1 (*)
|    |    +--- androidx.vectordrawable:vectordrawable:1.1.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    |    \--- androidx.collection:collection:1.1.0 (*)
|    |    \--- androidx.vectordrawable:vectordrawable-animated:1.1.0
|    |         +--- androidx.vectordrawable:vectordrawable:1.1.0 (*)
|    |         +--- androidx.interpolator:interpolator:1.0.0
|    |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         \--- androidx.collection:collection:1.1.0 (*)
|    +--- androidx.drawerlayout:drawerlayout:1.0.0
|    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    \--- androidx.customview:customview:1.0.0 (*)
|    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
+--- com.google.android.material:material:1.3.0
|    +--- androidx.annotation:annotation:1.0.1 -> 1.1.0
|    +--- androidx.appcompat:appcompat:1.1.0 -> 1.2.0 (*)
|    +--- androidx.cardview:cardview:1.0.0
|    |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    +--- androidx.coordinatorlayout:coordinatorlayout:1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    +--- androidx.customview:customview:1.0.0 (*)
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.constraintlayout:constraintlayout:2.0.1 -> 2.0.4
|    |    +--- androidx.appcompat:appcompat:1.2.0 (*)
|    |    +--- androidx.core:core:1.3.1 (*)
|    |    \--- androidx.constraintlayout:constraintlayout-solver:2.0.4
|    +--- androidx.core:core:1.2.0 -> 1.3.1 (*)
|    +--- androidx.dynamicanimation:dynamicanimation:1.0.0
|    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    +--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    |    \--- androidx.legacy:legacy-support-core-utils:1.0.0
|    |         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |         +--- androidx.documentfile:documentfile:1.0.0
|    |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         +--- androidx.loader:loader:1.0.0 (*)
|    |         +--- androidx.localbroadcastmanager:localbroadcastmanager:1.0.0
|    |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         \--- androidx.print:print:1.0.0
|    |              \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    +--- androidx.annotation:annotation-experimental:1.0.0
|    +--- androidx.fragment:fragment:1.0.0 -> 1.1.0 (*)
|    +--- androidx.lifecycle:lifecycle-runtime:2.0.0 -> 2.1.0 (*)
|    +--- androidx.recyclerview:recyclerview:1.0.0 -> 1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    +--- androidx.customview:customview:1.0.0 (*)
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.transition:transition:1.2.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.0.1 -> 1.3.1 (*)
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.vectordrawable:vectordrawable:1.1.0 (*)
|    \--- androidx.viewpager2:viewpager2:1.0.0
|         +--- androidx.annotation:annotation:1.1.0
|         +--- androidx.fragment:fragment:1.1.0 (*)
|         +--- androidx.recyclerview:recyclerview:1.1.0 (*)
|         +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|         \--- androidx.collection:collection:1.1.0 (*)
+--- androidx.constraintlayout:constraintlayout:2.0.4 (*)
+--- project :module_aliyun:AliyunFileDownLoader:downloadermanager
|    +--- androidx.appcompat:appcompat:1.2.0 (*)
|    \--- com.google.android.material:material:1.3.0 (*)
\--- project :module_aliyun:AlivcMedia
     +--- androidx.appcompat:appcompat:1.2.0 (*)
     \--- com.google.android.material:material:1.3.0 (*)

_testReleaseWearApp - Link to a wear app to embed for object '_testRelease'. (n)
No dependencies

_testReleaseWearBundling - Resolved Configuration for wear app bundling for variant: _testRelease
No dependencies

_testRuntimeOnly - Runtime only dependencies for '_test' sources. (n)
No dependencies

_testWearApp - Link to a wear app to embed for object '_test'. (n)
No dependencies

androidApis - Configuration providing various types of Android JAR file
No dependencies

androidTestAnnotationProcessor - Classpath for the annotation processor for 'androidTest'. (n)
No dependencies

androidTestApi - API dependencies for 'androidTest' sources. (n)
No dependencies

androidTestApk - Apk dependencies for 'androidTest' sources (deprecated: use 'androidTestRuntimeOnly' instead). (n)
No dependencies

androidTestCompile - Compile dependencies for 'androidTest' sources (deprecated: use 'androidTestImplementation' instead). (n)
No dependencies

androidTestCompileOnly - Compile only dependencies for 'androidTest' sources. (n)
No dependencies

androidTestDebugAnnotationProcessor - Classpath for the annotation processor for 'androidTestDebug'. (n)
No dependencies

androidTestDebugApi - API dependencies for 'androidTestDebug' sources. (n)
No dependencies

androidTestDebugApk - Apk dependencies for 'androidTestDebug' sources (deprecated: use 'androidTestDebugRuntimeOnly' instead). (n)
No dependencies

androidTestDebugCompile - Compile dependencies for 'androidTestDebug' sources (deprecated: use 'androidTestDebugImplementation' instead). (n)
No dependencies

androidTestDebugCompileOnly - Compile only dependencies for 'androidTestDebug' sources. (n)
No dependencies

androidTestDebugImplementation - Implementation only dependencies for 'androidTestDebug' sources. (n)
No dependencies

androidTestDebugProvided - Provided dependencies for 'androidTestDebug' sources (deprecated: use 'androidTestDebugCompileOnly' instead). (n)
No dependencies

androidTestDebugRuntimeOnly - Runtime only dependencies for 'androidTestDebug' sources. (n)
No dependencies

androidTestDebugWearApp - Link to a wear app to embed for object 'androidTestDebug'. (n)
No dependencies

androidTestDevAnnotationProcessor - Classpath for the annotation processor for 'androidTestDev'. (n)
No dependencies

androidTestDevApi - API dependencies for 'androidTestDev' sources. (n)
No dependencies

androidTestDevApk - Apk dependencies for 'androidTestDev' sources (deprecated: use 'androidTestDevRuntimeOnly' instead). (n)
No dependencies

androidTestDevCompile - Compile dependencies for 'androidTestDev' sources (deprecated: use 'androidTestDevImplementation' instead). (n)
No dependencies

androidTestDevCompileOnly - Compile only dependencies for 'androidTestDev' sources. (n)
No dependencies

androidTestDevDebugAnnotationProcessor - Classpath for the annotation processor for 'androidTestDevDebug'. (n)
No dependencies

androidTestDevDebugApi - API dependencies for 'androidTestDevDebug' sources. (n)
No dependencies

androidTestDevDebugApk - Apk dependencies for 'androidTestDevDebug' sources (deprecated: use 'androidTestDevDebugRuntimeOnly' instead). (n)
No dependencies

androidTestDevDebugCompile - Compile dependencies for 'androidTestDevDebug' sources (deprecated: use 'androidTestDevDebugImplementation' instead). (n)
No dependencies

androidTestDevDebugCompileOnly - Compile only dependencies for 'androidTestDevDebug' sources. (n)
No dependencies

androidTestDevDebugImplementation - Implementation only dependencies for 'androidTestDevDebug' sources. (n)
No dependencies

androidTestDevDebugProvided - Provided dependencies for 'androidTestDevDebug' sources (deprecated: use 'androidTestDevDebugCompileOnly' instead). (n)
No dependencies

androidTestDevDebugRuntimeOnly - Runtime only dependencies for 'androidTestDevDebug' sources. (n)
No dependencies

androidTestDevDebugWearApp - Link to a wear app to embed for object 'androidTestDevDebug'. (n)
No dependencies

androidTestDevImplementation - Implementation only dependencies for 'androidTestDev' sources. (n)
No dependencies

androidTestDevProvided - Provided dependencies for 'androidTestDev' sources (deprecated: use 'androidTestDevCompileOnly' instead). (n)
No dependencies

androidTestDevRuntimeOnly - Runtime only dependencies for 'androidTestDev' sources. (n)
No dependencies

androidTestDevWearApp - Link to a wear app to embed for object 'androidTestDev'. (n)
No dependencies

androidTestImplementation - Implementation only dependencies for 'androidTest' sources. (n)
No dependencies

androidTestProvided - Provided dependencies for 'androidTest' sources (deprecated: use 'androidTestCompileOnly' instead). (n)
No dependencies

androidTestRuntimeOnly - Runtime only dependencies for 'androidTest' sources. (n)
No dependencies

androidTestUtil - Additional APKs used during instrumentation testing.
No dependencies

androidTestWearApp - Link to a wear app to embed for object 'androidTest'. (n)
No dependencies

androidTest_testAnnotationProcessor - Classpath for the annotation processor for 'androidTest_test'. (n)
No dependencies

androidTest_testApi - API dependencies for 'androidTest_test' sources. (n)
No dependencies

androidTest_testApk - Apk dependencies for 'androidTest_test' sources (deprecated: use 'androidTest_testRuntimeOnly' instead). (n)
No dependencies

androidTest_testCompile - Compile dependencies for 'androidTest_test' sources (deprecated: use 'androidTest_testImplementation' instead). (n)
No dependencies

androidTest_testCompileOnly - Compile only dependencies for 'androidTest_test' sources. (n)
No dependencies

androidTest_testDebugAnnotationProcessor - Classpath for the annotation processor for 'androidTest_testDebug'. (n)
No dependencies

androidTest_testDebugApi - API dependencies for 'androidTest_testDebug' sources. (n)
No dependencies

androidTest_testDebugApk - Apk dependencies for 'androidTest_testDebug' sources (deprecated: use 'androidTest_testDebugRuntimeOnly' instead). (n)
No dependencies

androidTest_testDebugCompile - Compile dependencies for 'androidTest_testDebug' sources (deprecated: use 'androidTest_testDebugImplementation' instead). (n)
No dependencies

androidTest_testDebugCompileOnly - Compile only dependencies for 'androidTest_testDebug' sources. (n)
No dependencies

androidTest_testDebugImplementation - Implementation only dependencies for 'androidTest_testDebug' sources. (n)
No dependencies

androidTest_testDebugProvided - Provided dependencies for 'androidTest_testDebug' sources (deprecated: use 'androidTest_testDebugCompileOnly' instead). (n)
No dependencies

androidTest_testDebugRuntimeOnly - Runtime only dependencies for 'androidTest_testDebug' sources. (n)
No dependencies

androidTest_testDebugWearApp - Link to a wear app to embed for object 'androidTest_testDebug'. (n)
No dependencies

androidTest_testImplementation - Implementation only dependencies for 'androidTest_test' sources. (n)
No dependencies

androidTest_testProvided - Provided dependencies for 'androidTest_test' sources (deprecated: use 'androidTest_testCompileOnly' instead). (n)
No dependencies

androidTest_testRuntimeOnly - Runtime only dependencies for 'androidTest_test' sources. (n)
No dependencies

androidTest_testWearApp - Link to a wear app to embed for object 'androidTest_test'. (n)
No dependencies

annotationProcessor - Classpath for the annotation processor for 'main'. (n)
No dependencies

api - API dependencies for 'main' sources. (n)
No dependencies

apk - Apk dependencies for 'main' sources (deprecated: use 'runtimeOnly' instead). (n)
No dependencies

archives - Configuration for archive artifacts.
No dependencies

compile - Compile dependencies for 'main' sources (deprecated: use 'implementation' instead).
No dependencies

compileOnly - Compile only dependencies for 'main' sources. (n)
No dependencies

coreLibraryDesugaring - Configuration to desugar libraries
No dependencies

debugAnnotationProcessor - Classpath for the annotation processor for 'debug'. (n)
No dependencies

debugApi - API dependencies for 'debug' sources. (n)
No dependencies

debugApk - Apk dependencies for 'debug' sources (deprecated: use 'debugRuntimeOnly' instead). (n)
No dependencies

debugCompile - Compile dependencies for 'debug' sources (deprecated: use 'debugImplementation' instead). (n)
No dependencies

debugCompileOnly - Compile only dependencies for 'debug' sources. (n)
No dependencies

debugImplementation - Implementation only dependencies for 'debug' sources. (n)
No dependencies

debugProvided - Provided dependencies for 'debug' sources (deprecated: use 'debugCompileOnly' instead). (n)
No dependencies

debugRuntimeOnly - Runtime only dependencies for 'debug' sources. (n)
No dependencies

debugWearApp - Link to a wear app to embed for object 'debug'. (n)
No dependencies

default - Configuration for default artifacts.
No dependencies

devAnnotationProcessor - Classpath for the annotation processor for 'dev'. (n)
No dependencies

devApi - API dependencies for 'dev' sources. (n)
No dependencies

devApk - Apk dependencies for 'dev' sources (deprecated: use 'devRuntimeOnly' instead). (n)
No dependencies

devCompile - Compile dependencies for 'dev' sources (deprecated: use 'devImplementation' instead). (n)
No dependencies

devCompileOnly - Compile only dependencies for 'dev' sources. (n)
No dependencies

devDebugAabPublication - Bundle Publication for devDebug (n)
No dependencies

devDebugAndroidTestAnnotationProcessorClasspath - Resolved configuration for annotation-processor for variant: devDebugAndroidTest
No dependencies

devDebugAndroidTestCompileClasspath - Resolved configuration for compilation for variant: devDebugAndroidTest
+--- androidx.appcompat:appcompat:1.2.0
|    +--- androidx.annotation:annotation:1.1.0
|    +--- androidx.core:core:1.3.0 -> 1.3.1
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.lifecycle:lifecycle-runtime:2.0.0 -> 2.1.0
|    |    |    +--- androidx.lifecycle:lifecycle-common:2.1.0
|    |    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.arch.core:core-common:2.1.0
|    |    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    \--- androidx.versionedparcelable:versionedparcelable:1.1.0
|    |         +--- androidx.annotation:annotation:1.1.0
|    |         \--- androidx.collection:collection:1.0.0 -> 1.1.0
|    |              \--- androidx.annotation:annotation:1.1.0
|    +--- androidx.cursoradapter:cursoradapter:1.0.0
|    |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    +--- androidx.fragment:fragment:1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    +--- androidx.collection:collection:1.1.0 (*)
|    |    +--- androidx.viewpager:viewpager:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    |    \--- androidx.customview:customview:1.0.0
|    |    |         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |         \--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    +--- androidx.loader:loader:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-livedata:2.0.0
|    |    |    |    +--- androidx.arch.core:core-runtime:2.0.0
|    |    |    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    +--- androidx.lifecycle:lifecycle-livedata-core:2.0.0
|    |    |    |    |    +--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    |    +--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    |    \--- androidx.arch.core:core-runtime:2.0.0 (*)
|    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0
|    |    |         \--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.activity:activity:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-runtime:2.1.0 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-viewmodel:2.1.0 (*)
|    |    |    \--- androidx.savedstate:savedstate:1.0.0
|    |    |         +--- androidx.annotation:annotation:1.1.0
|    |    |         +--- androidx.arch.core:core-common:2.0.1 -> 2.1.0 (*)
|    |    |         \--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.1.0 (*)
|    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0 (*)
|    +--- androidx.appcompat:appcompat-resources:1.2.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.0.1 -> 1.3.1 (*)
|    |    +--- androidx.vectordrawable:vectordrawable:1.1.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    |    \--- androidx.collection:collection:1.1.0 (*)
|    |    \--- androidx.vectordrawable:vectordrawable-animated:1.1.0
|    |         +--- androidx.vectordrawable:vectordrawable:1.1.0 (*)
|    |         +--- androidx.interpolator:interpolator:1.0.0
|    |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         \--- androidx.collection:collection:1.1.0 (*)
|    \--- androidx.drawerlayout:drawerlayout:1.0.0
|         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|         +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|         \--- androidx.customview:customview:1.0.0 (*)
+--- com.google.android.material:material:1.3.0
|    +--- androidx.annotation:annotation:1.0.1 -> 1.1.0
|    +--- androidx.appcompat:appcompat:1.1.0 -> 1.2.0 (*)
|    +--- androidx.cardview:cardview:1.0.0
|    |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    +--- androidx.coordinatorlayout:coordinatorlayout:1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    +--- androidx.customview:customview:1.0.0 (*)
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.constraintlayout:constraintlayout:2.0.1 -> 2.0.4
|    |    +--- androidx.appcompat:appcompat:1.2.0 (*)
|    |    +--- androidx.core:core:1.3.1 (*)
|    |    \--- androidx.constraintlayout:constraintlayout-solver:2.0.4
|    +--- androidx.core:core:1.2.0 -> 1.3.1 (*)
|    +--- androidx.dynamicanimation:dynamicanimation:1.0.0
|    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    +--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    |    \--- androidx.legacy:legacy-support-core-utils:1.0.0
|    |         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |         +--- androidx.documentfile:documentfile:1.0.0
|    |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         +--- androidx.loader:loader:1.0.0 (*)
|    |         +--- androidx.localbroadcastmanager:localbroadcastmanager:1.0.0
|    |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         \--- androidx.print:print:1.0.0
|    |              \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    +--- androidx.annotation:annotation-experimental:1.0.0
|    +--- androidx.fragment:fragment:1.0.0 -> 1.1.0 (*)
|    +--- androidx.lifecycle:lifecycle-runtime:2.0.0 -> 2.1.0 (*)
|    +--- androidx.recyclerview:recyclerview:1.0.0 -> 1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    +--- androidx.customview:customview:1.0.0 (*)
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.transition:transition:1.2.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.0.1 -> 1.3.1 (*)
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.vectordrawable:vectordrawable:1.1.0 (*)
|    \--- androidx.viewpager2:viewpager2:1.0.0
|         +--- androidx.annotation:annotation:1.1.0
|         +--- androidx.fragment:fragment:1.1.0 (*)
|         +--- androidx.recyclerview:recyclerview:1.1.0 (*)
|         +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|         \--- androidx.collection:collection:1.1.0 (*)
+--- androidx.constraintlayout:constraintlayout:2.0.4 (*)
+--- project :module_aliyun:AliyunFileDownLoader:downloadermanager
+--- project :module_aliyun:AlivcMedia
+--- androidx.appcompat:appcompat:{strictly 1.2.0} -> 1.2.0 (c)
+--- com.google.android.material:material:{strictly 1.3.0} -> 1.3.0 (c)
+--- androidx.constraintlayout:constraintlayout:{strictly 2.0.4} -> 2.0.4 (c)
+--- androidx.annotation:annotation:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.core:core:{strictly 1.3.1} -> 1.3.1 (c)
+--- androidx.cursoradapter:cursoradapter:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.fragment:fragment:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.appcompat:appcompat-resources:{strictly 1.2.0} -> 1.2.0 (c)
+--- androidx.drawerlayout:drawerlayout:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.cardview:cardview:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.coordinatorlayout:coordinatorlayout:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.dynamicanimation:dynamicanimation:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.annotation:annotation-experimental:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.lifecycle:lifecycle-runtime:{strictly 2.1.0} -> 2.1.0 (c)
+--- androidx.recyclerview:recyclerview:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.transition:transition:{strictly 1.2.0} -> 1.2.0 (c)
+--- androidx.vectordrawable:vectordrawable:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.viewpager2:viewpager2:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.constraintlayout:constraintlayout-solver:{strictly 2.0.4} -> 2.0.4 (c)
+--- androidx.versionedparcelable:versionedparcelable:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.collection:collection:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.viewpager:viewpager:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.loader:loader:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.activity:activity:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.lifecycle:lifecycle-viewmodel:{strictly 2.1.0} -> 2.1.0 (c)
+--- androidx.vectordrawable:vectordrawable-animated:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.customview:customview:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.legacy:legacy-support-core-utils:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.lifecycle:lifecycle-common:{strictly 2.1.0} -> 2.1.0 (c)
+--- androidx.arch.core:core-common:{strictly 2.1.0} -> 2.1.0 (c)
+--- androidx.lifecycle:lifecycle-livedata:{strictly 2.0.0} -> 2.0.0 (c)
+--- androidx.savedstate:savedstate:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.interpolator:interpolator:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.documentfile:documentfile:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.localbroadcastmanager:localbroadcastmanager:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.print:print:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.arch.core:core-runtime:{strictly 2.0.0} -> 2.0.0 (c)
\--- androidx.lifecycle:lifecycle-livedata-core:{strictly 2.0.0} -> 2.0.0 (c)

devDebugAndroidTestRuntimeClasspath - Resolved configuration for runtime for variant: devDebugAndroidTest
+--- androidx.appcompat:appcompat:1.2.0
|    +--- androidx.annotation:annotation:1.1.0
|    +--- androidx.core:core:1.3.0 -> 1.3.1
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.lifecycle:lifecycle-runtime:2.0.0 -> 2.1.0
|    |    |    +--- androidx.lifecycle:lifecycle-common:2.1.0
|    |    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.arch.core:core-common:2.1.0
|    |    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.versionedparcelable:versionedparcelable:1.1.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0
|    |    |         \--- androidx.annotation:annotation:1.1.0
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.cursoradapter:cursoradapter:1.0.0
|    |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    +--- androidx.fragment:fragment:1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    +--- androidx.collection:collection:1.1.0 (*)
|    |    +--- androidx.viewpager:viewpager:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    |    \--- androidx.customview:customview:1.0.0
|    |    |         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |         \--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    +--- androidx.loader:loader:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-livedata:2.0.0
|    |    |    |    +--- androidx.arch.core:core-runtime:2.0.0
|    |    |    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    +--- androidx.lifecycle:lifecycle-livedata-core:2.0.0
|    |    |    |    |    +--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    |    +--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    |    \--- androidx.arch.core:core-runtime:2.0.0 (*)
|    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0
|    |    |         \--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.activity:activity:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-runtime:2.1.0 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-viewmodel:2.1.0 (*)
|    |    |    \--- androidx.savedstate:savedstate:1.0.0
|    |    |         +--- androidx.annotation:annotation:1.1.0
|    |    |         +--- androidx.arch.core:core-common:2.0.1 -> 2.1.0 (*)
|    |    |         \--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.1.0 (*)
|    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0 (*)
|    +--- androidx.appcompat:appcompat-resources:1.2.0
|    |    +--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.0.1 -> 1.3.1 (*)
|    |    +--- androidx.vectordrawable:vectordrawable:1.1.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    |    \--- androidx.collection:collection:1.1.0 (*)
|    |    \--- androidx.vectordrawable:vectordrawable-animated:1.1.0
|    |         +--- androidx.vectordrawable:vectordrawable:1.1.0 (*)
|    |         +--- androidx.interpolator:interpolator:1.0.0
|    |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         \--- androidx.collection:collection:1.1.0 (*)
|    +--- androidx.drawerlayout:drawerlayout:1.0.0
|    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    \--- androidx.customview:customview:1.0.0 (*)
|    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
+--- com.google.android.material:material:1.3.0
|    +--- androidx.annotation:annotation:1.0.1 -> 1.1.0
|    +--- androidx.appcompat:appcompat:1.1.0 -> 1.2.0 (*)
|    +--- androidx.cardview:cardview:1.0.0
|    |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    +--- androidx.coordinatorlayout:coordinatorlayout:1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    +--- androidx.customview:customview:1.0.0 (*)
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.constraintlayout:constraintlayout:2.0.1 -> 2.0.4
|    |    +--- androidx.appcompat:appcompat:1.2.0 (*)
|    |    +--- androidx.core:core:1.3.1 (*)
|    |    \--- androidx.constraintlayout:constraintlayout-solver:2.0.4
|    +--- androidx.core:core:1.2.0 -> 1.3.1 (*)
|    +--- androidx.dynamicanimation:dynamicanimation:1.0.0
|    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    +--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    |    \--- androidx.legacy:legacy-support-core-utils:1.0.0
|    |         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |         +--- androidx.documentfile:documentfile:1.0.0
|    |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         +--- androidx.loader:loader:1.0.0 (*)
|    |         +--- androidx.localbroadcastmanager:localbroadcastmanager:1.0.0
|    |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         \--- androidx.print:print:1.0.0
|    |              \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    +--- androidx.annotation:annotation-experimental:1.0.0
|    +--- androidx.fragment:fragment:1.0.0 -> 1.1.0 (*)
|    +--- androidx.lifecycle:lifecycle-runtime:2.0.0 -> 2.1.0 (*)
|    +--- androidx.recyclerview:recyclerview:1.0.0 -> 1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    +--- androidx.customview:customview:1.0.0 (*)
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.transition:transition:1.2.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.0.1 -> 1.3.1 (*)
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.vectordrawable:vectordrawable:1.1.0 (*)
|    \--- androidx.viewpager2:viewpager2:1.0.0
|         +--- androidx.annotation:annotation:1.1.0
|         +--- androidx.fragment:fragment:1.1.0 (*)
|         +--- androidx.recyclerview:recyclerview:1.1.0 (*)
|         +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|         \--- androidx.collection:collection:1.1.0 (*)
+--- androidx.constraintlayout:constraintlayout:2.0.4 (*)
+--- project :module_aliyun:AliyunFileDownLoader:downloadermanager
|    +--- androidx.appcompat:appcompat:1.2.0 (*)
|    \--- com.google.android.material:material:1.3.0 (*)
+--- project :module_aliyun:AlivcMedia
|    +--- androidx.appcompat:appcompat:1.2.0 (*)
|    \--- com.google.android.material:material:1.3.0 (*)
+--- androidx.appcompat:appcompat:{strictly 1.2.0} -> 1.2.0 (c)
+--- com.google.android.material:material:{strictly 1.3.0} -> 1.3.0 (c)
+--- androidx.constraintlayout:constraintlayout:{strictly 2.0.4} -> 2.0.4 (c)
+--- androidx.annotation:annotation:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.core:core:{strictly 1.3.1} -> 1.3.1 (c)
+--- androidx.cursoradapter:cursoradapter:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.fragment:fragment:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.appcompat:appcompat-resources:{strictly 1.2.0} -> 1.2.0 (c)
+--- androidx.drawerlayout:drawerlayout:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.collection:collection:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.cardview:cardview:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.coordinatorlayout:coordinatorlayout:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.dynamicanimation:dynamicanimation:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.annotation:annotation-experimental:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.lifecycle:lifecycle-runtime:{strictly 2.1.0} -> 2.1.0 (c)
+--- androidx.recyclerview:recyclerview:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.transition:transition:{strictly 1.2.0} -> 1.2.0 (c)
+--- androidx.vectordrawable:vectordrawable:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.viewpager2:viewpager2:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.constraintlayout:constraintlayout-solver:{strictly 2.0.4} -> 2.0.4 (c)
+--- androidx.versionedparcelable:versionedparcelable:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.viewpager:viewpager:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.loader:loader:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.activity:activity:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.lifecycle:lifecycle-viewmodel:{strictly 2.1.0} -> 2.1.0 (c)
+--- androidx.vectordrawable:vectordrawable-animated:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.customview:customview:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.legacy:legacy-support-core-utils:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.lifecycle:lifecycle-common:{strictly 2.1.0} -> 2.1.0 (c)
+--- androidx.arch.core:core-common:{strictly 2.1.0} -> 2.1.0 (c)
+--- androidx.lifecycle:lifecycle-livedata:{strictly 2.0.0} -> 2.0.0 (c)
+--- androidx.savedstate:savedstate:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.interpolator:interpolator:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.documentfile:documentfile:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.localbroadcastmanager:localbroadcastmanager:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.print:print:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.arch.core:core-runtime:{strictly 2.0.0} -> 2.0.0 (c)
\--- androidx.lifecycle:lifecycle-livedata-core:{strictly 2.0.0} -> 2.0.0 (c)

devDebugAnnotationProcessor - Classpath for the annotation processor for 'devDebug'. (n)
No dependencies

devDebugAnnotationProcessorClasspath - Resolved configuration for annotation-processor for variant: devDebug
No dependencies

devDebugApi - API dependencies for 'devDebug' sources. (n)
No dependencies

devDebugApiElements - API elements for devDebug (n)
No dependencies

devDebugApk - Apk dependencies for 'devDebug' sources (deprecated: use 'devDebugRuntimeOnly' instead). (n)
No dependencies

devDebugApkPublication - APK publication for devDebug (n)
No dependencies

devDebugCompile - Compile dependencies for 'devDebug' sources (deprecated: use 'devDebugImplementation' instead). (n)
No dependencies

devDebugCompileClasspath - Resolved configuration for compilation for variant: devDebug
+--- androidx.appcompat:appcompat:1.2.0
|    +--- androidx.annotation:annotation:1.1.0
|    +--- androidx.core:core:1.3.0 -> 1.3.1
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.lifecycle:lifecycle-runtime:2.0.0 -> 2.1.0
|    |    |    +--- androidx.lifecycle:lifecycle-common:2.1.0
|    |    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.arch.core:core-common:2.1.0
|    |    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    \--- androidx.versionedparcelable:versionedparcelable:1.1.0
|    |         +--- androidx.annotation:annotation:1.1.0
|    |         \--- androidx.collection:collection:1.0.0 -> 1.1.0
|    |              \--- androidx.annotation:annotation:1.1.0
|    +--- androidx.cursoradapter:cursoradapter:1.0.0
|    |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    +--- androidx.fragment:fragment:1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    +--- androidx.collection:collection:1.1.0 (*)
|    |    +--- androidx.viewpager:viewpager:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    |    \--- androidx.customview:customview:1.0.0
|    |    |         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |         \--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    +--- androidx.loader:loader:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-livedata:2.0.0
|    |    |    |    +--- androidx.arch.core:core-runtime:2.0.0
|    |    |    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    +--- androidx.lifecycle:lifecycle-livedata-core:2.0.0
|    |    |    |    |    +--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    |    +--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    |    \--- androidx.arch.core:core-runtime:2.0.0 (*)
|    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0
|    |    |         \--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.activity:activity:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-runtime:2.1.0 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-viewmodel:2.1.0 (*)
|    |    |    \--- androidx.savedstate:savedstate:1.0.0
|    |    |         +--- androidx.annotation:annotation:1.1.0
|    |    |         +--- androidx.arch.core:core-common:2.0.1 -> 2.1.0 (*)
|    |    |         \--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.1.0 (*)
|    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0 (*)
|    +--- androidx.appcompat:appcompat-resources:1.2.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.0.1 -> 1.3.1 (*)
|    |    +--- androidx.vectordrawable:vectordrawable:1.1.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    |    \--- androidx.collection:collection:1.1.0 (*)
|    |    \--- androidx.vectordrawable:vectordrawable-animated:1.1.0
|    |         +--- androidx.vectordrawable:vectordrawable:1.1.0 (*)
|    |         +--- androidx.interpolator:interpolator:1.0.0
|    |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         \--- androidx.collection:collection:1.1.0 (*)
|    \--- androidx.drawerlayout:drawerlayout:1.0.0
|         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|         +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|         \--- androidx.customview:customview:1.0.0 (*)
+--- com.google.android.material:material:1.3.0
|    +--- androidx.annotation:annotation:1.0.1 -> 1.1.0
|    +--- androidx.appcompat:appcompat:1.1.0 -> 1.2.0 (*)
|    +--- androidx.cardview:cardview:1.0.0
|    |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    +--- androidx.coordinatorlayout:coordinatorlayout:1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    +--- androidx.customview:customview:1.0.0 (*)
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.constraintlayout:constraintlayout:2.0.1 -> 2.0.4
|    |    +--- androidx.appcompat:appcompat:1.2.0 (*)
|    |    +--- androidx.core:core:1.3.1 (*)
|    |    \--- androidx.constraintlayout:constraintlayout-solver:2.0.4
|    +--- androidx.core:core:1.2.0 -> 1.3.1 (*)
|    +--- androidx.dynamicanimation:dynamicanimation:1.0.0
|    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    +--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    |    \--- androidx.legacy:legacy-support-core-utils:1.0.0
|    |         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |         +--- androidx.documentfile:documentfile:1.0.0
|    |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         +--- androidx.loader:loader:1.0.0 (*)
|    |         +--- androidx.localbroadcastmanager:localbroadcastmanager:1.0.0
|    |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         \--- androidx.print:print:1.0.0
|    |              \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    +--- androidx.annotation:annotation-experimental:1.0.0
|    +--- androidx.fragment:fragment:1.0.0 -> 1.1.0 (*)
|    +--- androidx.lifecycle:lifecycle-runtime:2.0.0 -> 2.1.0 (*)
|    +--- androidx.recyclerview:recyclerview:1.0.0 -> 1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    +--- androidx.customview:customview:1.0.0 (*)
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.transition:transition:1.2.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.0.1 -> 1.3.1 (*)
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.vectordrawable:vectordrawable:1.1.0 (*)
|    \--- androidx.viewpager2:viewpager2:1.0.0
|         +--- androidx.annotation:annotation:1.1.0
|         +--- androidx.fragment:fragment:1.1.0 (*)
|         +--- androidx.recyclerview:recyclerview:1.1.0 (*)
|         +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|         \--- androidx.collection:collection:1.1.0 (*)
+--- androidx.constraintlayout:constraintlayout:2.0.4 (*)
+--- project :module_aliyun:AliyunFileDownLoader:downloadermanager
+--- project :module_aliyun:AlivcMedia
+--- androidx.appcompat:appcompat:{strictly 1.2.0} -> 1.2.0 (c)
+--- com.google.android.material:material:{strictly 1.3.0} -> 1.3.0 (c)
+--- androidx.constraintlayout:constraintlayout:{strictly 2.0.4} -> 2.0.4 (c)
+--- androidx.annotation:annotation:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.core:core:{strictly 1.3.1} -> 1.3.1 (c)
+--- androidx.cursoradapter:cursoradapter:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.fragment:fragment:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.appcompat:appcompat-resources:{strictly 1.2.0} -> 1.2.0 (c)
+--- androidx.drawerlayout:drawerlayout:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.cardview:cardview:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.coordinatorlayout:coordinatorlayout:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.dynamicanimation:dynamicanimation:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.annotation:annotation-experimental:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.lifecycle:lifecycle-runtime:{strictly 2.1.0} -> 2.1.0 (c)
+--- androidx.recyclerview:recyclerview:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.transition:transition:{strictly 1.2.0} -> 1.2.0 (c)
+--- androidx.vectordrawable:vectordrawable:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.viewpager2:viewpager2:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.constraintlayout:constraintlayout-solver:{strictly 2.0.4} -> 2.0.4 (c)
+--- androidx.versionedparcelable:versionedparcelable:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.collection:collection:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.viewpager:viewpager:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.loader:loader:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.activity:activity:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.lifecycle:lifecycle-viewmodel:{strictly 2.1.0} -> 2.1.0 (c)
+--- androidx.vectordrawable:vectordrawable-animated:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.customview:customview:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.legacy:legacy-support-core-utils:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.lifecycle:lifecycle-common:{strictly 2.1.0} -> 2.1.0 (c)
+--- androidx.arch.core:core-common:{strictly 2.1.0} -> 2.1.0 (c)
+--- androidx.lifecycle:lifecycle-livedata:{strictly 2.0.0} -> 2.0.0 (c)
+--- androidx.savedstate:savedstate:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.interpolator:interpolator:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.documentfile:documentfile:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.localbroadcastmanager:localbroadcastmanager:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.print:print:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.arch.core:core-runtime:{strictly 2.0.0} -> 2.0.0 (c)
\--- androidx.lifecycle:lifecycle-livedata-core:{strictly 2.0.0} -> 2.0.0 (c)

devDebugCompileOnly - Compile only dependencies for 'devDebug' sources. (n)
No dependencies

devDebugImplementation - Implementation only dependencies for 'devDebug' sources. (n)
No dependencies

devDebugProvided - Provided dependencies for 'devDebug' sources (deprecated: use 'devDebugCompileOnly' instead). (n)
No dependencies

devDebugReverseMetadataValues - Metadata Values dependencies for the base Split
No dependencies

devDebugRuntimeClasspath - Resolved configuration for runtime for variant: devDebug
+--- androidx.appcompat:appcompat:1.2.0
|    +--- androidx.annotation:annotation:1.1.0
|    +--- androidx.core:core:1.3.0 -> 1.3.1
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.lifecycle:lifecycle-runtime:2.0.0 -> 2.1.0
|    |    |    +--- androidx.lifecycle:lifecycle-common:2.1.0
|    |    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.arch.core:core-common:2.1.0
|    |    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.versionedparcelable:versionedparcelable:1.1.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0
|    |    |         \--- androidx.annotation:annotation:1.1.0
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.cursoradapter:cursoradapter:1.0.0
|    |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    +--- androidx.fragment:fragment:1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    +--- androidx.collection:collection:1.1.0 (*)
|    |    +--- androidx.viewpager:viewpager:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    |    \--- androidx.customview:customview:1.0.0
|    |    |         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |         \--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    +--- androidx.loader:loader:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-livedata:2.0.0
|    |    |    |    +--- androidx.arch.core:core-runtime:2.0.0
|    |    |    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    +--- androidx.lifecycle:lifecycle-livedata-core:2.0.0
|    |    |    |    |    +--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    |    +--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    |    \--- androidx.arch.core:core-runtime:2.0.0 (*)
|    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0
|    |    |         \--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.activity:activity:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-runtime:2.1.0 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-viewmodel:2.1.0 (*)
|    |    |    \--- androidx.savedstate:savedstate:1.0.0
|    |    |         +--- androidx.annotation:annotation:1.1.0
|    |    |         +--- androidx.arch.core:core-common:2.0.1 -> 2.1.0 (*)
|    |    |         \--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.1.0 (*)
|    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0 (*)
|    +--- androidx.appcompat:appcompat-resources:1.2.0
|    |    +--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.0.1 -> 1.3.1 (*)
|    |    +--- androidx.vectordrawable:vectordrawable:1.1.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    |    \--- androidx.collection:collection:1.1.0 (*)
|    |    \--- androidx.vectordrawable:vectordrawable-animated:1.1.0
|    |         +--- androidx.vectordrawable:vectordrawable:1.1.0 (*)
|    |         +--- androidx.interpolator:interpolator:1.0.0
|    |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         \--- androidx.collection:collection:1.1.0 (*)
|    +--- androidx.drawerlayout:drawerlayout:1.0.0
|    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    \--- androidx.customview:customview:1.0.0 (*)
|    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
+--- com.google.android.material:material:1.3.0
|    +--- androidx.annotation:annotation:1.0.1 -> 1.1.0
|    +--- androidx.appcompat:appcompat:1.1.0 -> 1.2.0 (*)
|    +--- androidx.cardview:cardview:1.0.0
|    |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    +--- androidx.coordinatorlayout:coordinatorlayout:1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    +--- androidx.customview:customview:1.0.0 (*)
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.constraintlayout:constraintlayout:2.0.1 -> 2.0.4
|    |    +--- androidx.appcompat:appcompat:1.2.0 (*)
|    |    +--- androidx.core:core:1.3.1 (*)
|    |    \--- androidx.constraintlayout:constraintlayout-solver:2.0.4
|    +--- androidx.core:core:1.2.0 -> 1.3.1 (*)
|    +--- androidx.dynamicanimation:dynamicanimation:1.0.0
|    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    +--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    |    \--- androidx.legacy:legacy-support-core-utils:1.0.0
|    |         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |         +--- androidx.documentfile:documentfile:1.0.0
|    |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         +--- androidx.loader:loader:1.0.0 (*)
|    |         +--- androidx.localbroadcastmanager:localbroadcastmanager:1.0.0
|    |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         \--- androidx.print:print:1.0.0
|    |              \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    +--- androidx.annotation:annotation-experimental:1.0.0
|    +--- androidx.fragment:fragment:1.0.0 -> 1.1.0 (*)
|    +--- androidx.lifecycle:lifecycle-runtime:2.0.0 -> 2.1.0 (*)
|    +--- androidx.recyclerview:recyclerview:1.0.0 -> 1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    +--- androidx.customview:customview:1.0.0 (*)
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.transition:transition:1.2.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.0.1 -> 1.3.1 (*)
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.vectordrawable:vectordrawable:1.1.0 (*)
|    \--- androidx.viewpager2:viewpager2:1.0.0
|         +--- androidx.annotation:annotation:1.1.0
|         +--- androidx.fragment:fragment:1.1.0 (*)
|         +--- androidx.recyclerview:recyclerview:1.1.0 (*)
|         +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|         \--- androidx.collection:collection:1.1.0 (*)
+--- androidx.constraintlayout:constraintlayout:2.0.4 (*)
+--- project :module_aliyun:AliyunFileDownLoader:downloadermanager
|    +--- androidx.appcompat:appcompat:1.2.0 (*)
|    \--- com.google.android.material:material:1.3.0 (*)
\--- project :module_aliyun:AlivcMedia
     +--- androidx.appcompat:appcompat:1.2.0 (*)
     \--- com.google.android.material:material:1.3.0 (*)

devDebugRuntimeElements - Runtime elements for devDebug (n)
No dependencies

devDebugRuntimeOnly - Runtime only dependencies for 'devDebug' sources. (n)
No dependencies

devDebugUnitTestAnnotationProcessorClasspath - Resolved configuration for annotation-processor for variant: devDebugUnitTest
No dependencies

devDebugUnitTestCompileClasspath - Resolved configuration for compilation for variant: devDebugUnitTest
+--- androidx.appcompat:appcompat:1.2.0
|    +--- androidx.annotation:annotation:1.1.0
|    +--- androidx.core:core:1.3.0 -> 1.3.1
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.lifecycle:lifecycle-runtime:2.0.0 -> 2.1.0
|    |    |    +--- androidx.lifecycle:lifecycle-common:2.1.0
|    |    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.arch.core:core-common:2.1.0
|    |    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    \--- androidx.versionedparcelable:versionedparcelable:1.1.0
|    |         +--- androidx.annotation:annotation:1.1.0
|    |         \--- androidx.collection:collection:1.0.0 -> 1.1.0
|    |              \--- androidx.annotation:annotation:1.1.0
|    +--- androidx.cursoradapter:cursoradapter:1.0.0
|    |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    +--- androidx.fragment:fragment:1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    +--- androidx.collection:collection:1.1.0 (*)
|    |    +--- androidx.viewpager:viewpager:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    |    \--- androidx.customview:customview:1.0.0
|    |    |         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |         \--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    +--- androidx.loader:loader:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-livedata:2.0.0
|    |    |    |    +--- androidx.arch.core:core-runtime:2.0.0
|    |    |    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    +--- androidx.lifecycle:lifecycle-livedata-core:2.0.0
|    |    |    |    |    +--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    |    +--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    |    \--- androidx.arch.core:core-runtime:2.0.0 (*)
|    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0
|    |    |         \--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.activity:activity:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-runtime:2.1.0 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-viewmodel:2.1.0 (*)
|    |    |    \--- androidx.savedstate:savedstate:1.0.0
|    |    |         +--- androidx.annotation:annotation:1.1.0
|    |    |         +--- androidx.arch.core:core-common:2.0.1 -> 2.1.0 (*)
|    |    |         \--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.1.0 (*)
|    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0 (*)
|    +--- androidx.appcompat:appcompat-resources:1.2.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.0.1 -> 1.3.1 (*)
|    |    +--- androidx.vectordrawable:vectordrawable:1.1.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    |    \--- androidx.collection:collection:1.1.0 (*)
|    |    \--- androidx.vectordrawable:vectordrawable-animated:1.1.0
|    |         +--- androidx.vectordrawable:vectordrawable:1.1.0 (*)
|    |         +--- androidx.interpolator:interpolator:1.0.0
|    |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         \--- androidx.collection:collection:1.1.0 (*)
|    \--- androidx.drawerlayout:drawerlayout:1.0.0
|         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|         +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|         \--- androidx.customview:customview:1.0.0 (*)
+--- com.google.android.material:material:1.3.0
|    +--- androidx.annotation:annotation:1.0.1 -> 1.1.0
|    +--- androidx.appcompat:appcompat:1.1.0 -> 1.2.0 (*)
|    +--- androidx.cardview:cardview:1.0.0
|    |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    +--- androidx.coordinatorlayout:coordinatorlayout:1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    +--- androidx.customview:customview:1.0.0 (*)
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.constraintlayout:constraintlayout:2.0.1 -> 2.0.4
|    |    +--- androidx.appcompat:appcompat:1.2.0 (*)
|    |    +--- androidx.core:core:1.3.1 (*)
|    |    \--- androidx.constraintlayout:constraintlayout-solver:2.0.4
|    +--- androidx.core:core:1.2.0 -> 1.3.1 (*)
|    +--- androidx.dynamicanimation:dynamicanimation:1.0.0
|    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    +--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    |    \--- androidx.legacy:legacy-support-core-utils:1.0.0
|    |         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |         +--- androidx.documentfile:documentfile:1.0.0
|    |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         +--- androidx.loader:loader:1.0.0 (*)
|    |         +--- androidx.localbroadcastmanager:localbroadcastmanager:1.0.0
|    |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         \--- androidx.print:print:1.0.0
|    |              \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    +--- androidx.annotation:annotation-experimental:1.0.0
|    +--- androidx.fragment:fragment:1.0.0 -> 1.1.0 (*)
|    +--- androidx.lifecycle:lifecycle-runtime:2.0.0 -> 2.1.0 (*)
|    +--- androidx.recyclerview:recyclerview:1.0.0 -> 1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    +--- androidx.customview:customview:1.0.0 (*)
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.transition:transition:1.2.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.0.1 -> 1.3.1 (*)
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.vectordrawable:vectordrawable:1.1.0 (*)
|    \--- androidx.viewpager2:viewpager2:1.0.0
|         +--- androidx.annotation:annotation:1.1.0
|         +--- androidx.fragment:fragment:1.1.0 (*)
|         +--- androidx.recyclerview:recyclerview:1.1.0 (*)
|         +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|         \--- androidx.collection:collection:1.1.0 (*)
+--- androidx.constraintlayout:constraintlayout:2.0.4 (*)
+--- project :module_aliyun:AliyunFileDownLoader:downloadermanager
+--- project :module_aliyun:AlivcMedia
+--- androidx.appcompat:appcompat:{strictly 1.2.0} -> 1.2.0 (c)
+--- com.google.android.material:material:{strictly 1.3.0} -> 1.3.0 (c)
+--- androidx.constraintlayout:constraintlayout:{strictly 2.0.4} -> 2.0.4 (c)
+--- androidx.annotation:annotation:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.core:core:{strictly 1.3.1} -> 1.3.1 (c)
+--- androidx.cursoradapter:cursoradapter:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.fragment:fragment:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.appcompat:appcompat-resources:{strictly 1.2.0} -> 1.2.0 (c)
+--- androidx.drawerlayout:drawerlayout:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.cardview:cardview:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.coordinatorlayout:coordinatorlayout:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.dynamicanimation:dynamicanimation:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.annotation:annotation-experimental:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.lifecycle:lifecycle-runtime:{strictly 2.1.0} -> 2.1.0 (c)
+--- androidx.recyclerview:recyclerview:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.transition:transition:{strictly 1.2.0} -> 1.2.0 (c)
+--- androidx.vectordrawable:vectordrawable:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.viewpager2:viewpager2:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.constraintlayout:constraintlayout-solver:{strictly 2.0.4} -> 2.0.4 (c)
+--- androidx.versionedparcelable:versionedparcelable:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.collection:collection:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.viewpager:viewpager:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.loader:loader:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.activity:activity:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.lifecycle:lifecycle-viewmodel:{strictly 2.1.0} -> 2.1.0 (c)
+--- androidx.vectordrawable:vectordrawable-animated:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.customview:customview:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.legacy:legacy-support-core-utils:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.lifecycle:lifecycle-common:{strictly 2.1.0} -> 2.1.0 (c)
+--- androidx.arch.core:core-common:{strictly 2.1.0} -> 2.1.0 (c)
+--- androidx.lifecycle:lifecycle-livedata:{strictly 2.0.0} -> 2.0.0 (c)
+--- androidx.savedstate:savedstate:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.interpolator:interpolator:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.documentfile:documentfile:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.localbroadcastmanager:localbroadcastmanager:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.print:print:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.arch.core:core-runtime:{strictly 2.0.0} -> 2.0.0 (c)
\--- androidx.lifecycle:lifecycle-livedata-core:{strictly 2.0.0} -> 2.0.0 (c)

devDebugUnitTestRuntimeClasspath - Resolved configuration for runtime for variant: devDebugUnitTest
+--- androidx.appcompat:appcompat:1.2.0
|    +--- androidx.annotation:annotation:1.1.0
|    +--- androidx.core:core:1.3.0 -> 1.3.1
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.lifecycle:lifecycle-runtime:2.0.0 -> 2.1.0
|    |    |    +--- androidx.lifecycle:lifecycle-common:2.1.0
|    |    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.arch.core:core-common:2.1.0
|    |    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.versionedparcelable:versionedparcelable:1.1.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0
|    |    |         \--- androidx.annotation:annotation:1.1.0
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.cursoradapter:cursoradapter:1.0.0
|    |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    +--- androidx.fragment:fragment:1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    +--- androidx.collection:collection:1.1.0 (*)
|    |    +--- androidx.viewpager:viewpager:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    |    \--- androidx.customview:customview:1.0.0
|    |    |         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |         \--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    +--- androidx.loader:loader:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-livedata:2.0.0
|    |    |    |    +--- androidx.arch.core:core-runtime:2.0.0
|    |    |    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    +--- androidx.lifecycle:lifecycle-livedata-core:2.0.0
|    |    |    |    |    +--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    |    +--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    |    \--- androidx.arch.core:core-runtime:2.0.0 (*)
|    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0
|    |    |         \--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.activity:activity:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-runtime:2.1.0 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-viewmodel:2.1.0 (*)
|    |    |    \--- androidx.savedstate:savedstate:1.0.0
|    |    |         +--- androidx.annotation:annotation:1.1.0
|    |    |         +--- androidx.arch.core:core-common:2.0.1 -> 2.1.0 (*)
|    |    |         \--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.1.0 (*)
|    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0 (*)
|    +--- androidx.appcompat:appcompat-resources:1.2.0
|    |    +--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.0.1 -> 1.3.1 (*)
|    |    +--- androidx.vectordrawable:vectordrawable:1.1.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    |    \--- androidx.collection:collection:1.1.0 (*)
|    |    \--- androidx.vectordrawable:vectordrawable-animated:1.1.0
|    |         +--- androidx.vectordrawable:vectordrawable:1.1.0 (*)
|    |         +--- androidx.interpolator:interpolator:1.0.0
|    |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         \--- androidx.collection:collection:1.1.0 (*)
|    +--- androidx.drawerlayout:drawerlayout:1.0.0
|    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    \--- androidx.customview:customview:1.0.0 (*)
|    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
+--- com.google.android.material:material:1.3.0
|    +--- androidx.annotation:annotation:1.0.1 -> 1.1.0
|    +--- androidx.appcompat:appcompat:1.1.0 -> 1.2.0 (*)
|    +--- androidx.cardview:cardview:1.0.0
|    |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    +--- androidx.coordinatorlayout:coordinatorlayout:1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    +--- androidx.customview:customview:1.0.0 (*)
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.constraintlayout:constraintlayout:2.0.1 -> 2.0.4
|    |    +--- androidx.appcompat:appcompat:1.2.0 (*)
|    |    +--- androidx.core:core:1.3.1 (*)
|    |    \--- androidx.constraintlayout:constraintlayout-solver:2.0.4
|    +--- androidx.core:core:1.2.0 -> 1.3.1 (*)
|    +--- androidx.dynamicanimation:dynamicanimation:1.0.0
|    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    +--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    |    \--- androidx.legacy:legacy-support-core-utils:1.0.0
|    |         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |         +--- androidx.documentfile:documentfile:1.0.0
|    |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         +--- androidx.loader:loader:1.0.0 (*)
|    |         +--- androidx.localbroadcastmanager:localbroadcastmanager:1.0.0
|    |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         \--- androidx.print:print:1.0.0
|    |              \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    +--- androidx.annotation:annotation-experimental:1.0.0
|    +--- androidx.fragment:fragment:1.0.0 -> 1.1.0 (*)
|    +--- androidx.lifecycle:lifecycle-runtime:2.0.0 -> 2.1.0 (*)
|    +--- androidx.recyclerview:recyclerview:1.0.0 -> 1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    +--- androidx.customview:customview:1.0.0 (*)
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.transition:transition:1.2.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.0.1 -> 1.3.1 (*)
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.vectordrawable:vectordrawable:1.1.0 (*)
|    \--- androidx.viewpager2:viewpager2:1.0.0
|         +--- androidx.annotation:annotation:1.1.0
|         +--- androidx.fragment:fragment:1.1.0 (*)
|         +--- androidx.recyclerview:recyclerview:1.1.0 (*)
|         +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|         \--- androidx.collection:collection:1.1.0 (*)
+--- androidx.constraintlayout:constraintlayout:2.0.4 (*)
+--- project :module_aliyun:AliyunFileDownLoader:downloadermanager
|    +--- androidx.appcompat:appcompat:1.2.0 (*)
|    \--- com.google.android.material:material:1.3.0 (*)
\--- project :module_aliyun:AlivcMedia
     +--- androidx.appcompat:appcompat:1.2.0 (*)
     \--- com.google.android.material:material:1.3.0 (*)

devDebugWearApp - Link to a wear app to embed for object 'devDebug'. (n)
No dependencies

devDebugWearBundling - Resolved Configuration for wear app bundling for variant: devDebug
No dependencies

devImplementation - Implementation only dependencies for 'dev' sources. (n)
No dependencies

devProvided - Provided dependencies for 'dev' sources (deprecated: use 'devCompileOnly' instead). (n)
No dependencies

devReleaseAabPublication - Bundle Publication for devRelease (n)
No dependencies

devReleaseAnnotationProcessor - Classpath for the annotation processor for 'devRelease'. (n)
No dependencies

devReleaseAnnotationProcessorClasspath - Resolved configuration for annotation-processor for variant: devRelease
No dependencies

devReleaseApi - API dependencies for 'devRelease' sources. (n)
No dependencies

devReleaseApiElements - API elements for devRelease (n)
No dependencies

devReleaseApk - Apk dependencies for 'devRelease' sources (deprecated: use 'devReleaseRuntimeOnly' instead). (n)
No dependencies

devReleaseApkPublication - APK publication for devRelease (n)
No dependencies

devReleaseCompile - Compile dependencies for 'devRelease' sources (deprecated: use 'devReleaseImplementation' instead). (n)
No dependencies

devReleaseCompileClasspath - Resolved configuration for compilation for variant: devRelease
+--- androidx.appcompat:appcompat:1.2.0
|    +--- androidx.annotation:annotation:1.1.0
|    +--- androidx.core:core:1.3.0 -> 1.3.1
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.lifecycle:lifecycle-runtime:2.0.0 -> 2.1.0
|    |    |    +--- androidx.lifecycle:lifecycle-common:2.1.0
|    |    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.arch.core:core-common:2.1.0
|    |    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    \--- androidx.versionedparcelable:versionedparcelable:1.1.0
|    |         +--- androidx.annotation:annotation:1.1.0
|    |         \--- androidx.collection:collection:1.0.0 -> 1.1.0
|    |              \--- androidx.annotation:annotation:1.1.0
|    +--- androidx.cursoradapter:cursoradapter:1.0.0
|    |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    +--- androidx.fragment:fragment:1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    +--- androidx.collection:collection:1.1.0 (*)
|    |    +--- androidx.viewpager:viewpager:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    |    \--- androidx.customview:customview:1.0.0
|    |    |         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |         \--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    +--- androidx.loader:loader:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-livedata:2.0.0
|    |    |    |    +--- androidx.arch.core:core-runtime:2.0.0
|    |    |    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    +--- androidx.lifecycle:lifecycle-livedata-core:2.0.0
|    |    |    |    |    +--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    |    +--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    |    \--- androidx.arch.core:core-runtime:2.0.0 (*)
|    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0
|    |    |         \--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.activity:activity:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-runtime:2.1.0 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-viewmodel:2.1.0 (*)
|    |    |    \--- androidx.savedstate:savedstate:1.0.0
|    |    |         +--- androidx.annotation:annotation:1.1.0
|    |    |         +--- androidx.arch.core:core-common:2.0.1 -> 2.1.0 (*)
|    |    |         \--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.1.0 (*)
|    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0 (*)
|    +--- androidx.appcompat:appcompat-resources:1.2.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.0.1 -> 1.3.1 (*)
|    |    +--- androidx.vectordrawable:vectordrawable:1.1.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    |    \--- androidx.collection:collection:1.1.0 (*)
|    |    \--- androidx.vectordrawable:vectordrawable-animated:1.1.0
|    |         +--- androidx.vectordrawable:vectordrawable:1.1.0 (*)
|    |         +--- androidx.interpolator:interpolator:1.0.0
|    |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         \--- androidx.collection:collection:1.1.0 (*)
|    \--- androidx.drawerlayout:drawerlayout:1.0.0
|         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|         +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|         \--- androidx.customview:customview:1.0.0 (*)
+--- com.google.android.material:material:1.3.0
|    +--- androidx.annotation:annotation:1.0.1 -> 1.1.0
|    +--- androidx.appcompat:appcompat:1.1.0 -> 1.2.0 (*)
|    +--- androidx.cardview:cardview:1.0.0
|    |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    +--- androidx.coordinatorlayout:coordinatorlayout:1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    +--- androidx.customview:customview:1.0.0 (*)
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.constraintlayout:constraintlayout:2.0.1 -> 2.0.4
|    |    +--- androidx.appcompat:appcompat:1.2.0 (*)
|    |    +--- androidx.core:core:1.3.1 (*)
|    |    \--- androidx.constraintlayout:constraintlayout-solver:2.0.4
|    +--- androidx.core:core:1.2.0 -> 1.3.1 (*)
|    +--- androidx.dynamicanimation:dynamicanimation:1.0.0
|    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    +--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    |    \--- androidx.legacy:legacy-support-core-utils:1.0.0
|    |         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |         +--- androidx.documentfile:documentfile:1.0.0
|    |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         +--- androidx.loader:loader:1.0.0 (*)
|    |         +--- androidx.localbroadcastmanager:localbroadcastmanager:1.0.0
|    |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         \--- androidx.print:print:1.0.0
|    |              \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    +--- androidx.annotation:annotation-experimental:1.0.0
|    +--- androidx.fragment:fragment:1.0.0 -> 1.1.0 (*)
|    +--- androidx.lifecycle:lifecycle-runtime:2.0.0 -> 2.1.0 (*)
|    +--- androidx.recyclerview:recyclerview:1.0.0 -> 1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    +--- androidx.customview:customview:1.0.0 (*)
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.transition:transition:1.2.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.0.1 -> 1.3.1 (*)
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.vectordrawable:vectordrawable:1.1.0 (*)
|    \--- androidx.viewpager2:viewpager2:1.0.0
|         +--- androidx.annotation:annotation:1.1.0
|         +--- androidx.fragment:fragment:1.1.0 (*)
|         +--- androidx.recyclerview:recyclerview:1.1.0 (*)
|         +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|         \--- androidx.collection:collection:1.1.0 (*)
+--- androidx.constraintlayout:constraintlayout:2.0.4 (*)
+--- project :module_aliyun:AliyunFileDownLoader:downloadermanager
+--- project :module_aliyun:AlivcMedia
+--- androidx.appcompat:appcompat:{strictly 1.2.0} -> 1.2.0 (c)
+--- com.google.android.material:material:{strictly 1.3.0} -> 1.3.0 (c)
+--- androidx.constraintlayout:constraintlayout:{strictly 2.0.4} -> 2.0.4 (c)
+--- androidx.annotation:annotation:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.core:core:{strictly 1.3.1} -> 1.3.1 (c)
+--- androidx.cursoradapter:cursoradapter:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.fragment:fragment:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.appcompat:appcompat-resources:{strictly 1.2.0} -> 1.2.0 (c)
+--- androidx.drawerlayout:drawerlayout:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.cardview:cardview:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.coordinatorlayout:coordinatorlayout:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.dynamicanimation:dynamicanimation:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.annotation:annotation-experimental:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.lifecycle:lifecycle-runtime:{strictly 2.1.0} -> 2.1.0 (c)
+--- androidx.recyclerview:recyclerview:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.transition:transition:{strictly 1.2.0} -> 1.2.0 (c)
+--- androidx.vectordrawable:vectordrawable:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.viewpager2:viewpager2:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.constraintlayout:constraintlayout-solver:{strictly 2.0.4} -> 2.0.4 (c)
+--- androidx.versionedparcelable:versionedparcelable:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.collection:collection:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.viewpager:viewpager:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.loader:loader:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.activity:activity:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.lifecycle:lifecycle-viewmodel:{strictly 2.1.0} -> 2.1.0 (c)
+--- androidx.vectordrawable:vectordrawable-animated:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.customview:customview:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.legacy:legacy-support-core-utils:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.lifecycle:lifecycle-common:{strictly 2.1.0} -> 2.1.0 (c)
+--- androidx.arch.core:core-common:{strictly 2.1.0} -> 2.1.0 (c)
+--- androidx.lifecycle:lifecycle-livedata:{strictly 2.0.0} -> 2.0.0 (c)
+--- androidx.savedstate:savedstate:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.interpolator:interpolator:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.documentfile:documentfile:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.localbroadcastmanager:localbroadcastmanager:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.print:print:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.arch.core:core-runtime:{strictly 2.0.0} -> 2.0.0 (c)
\--- androidx.lifecycle:lifecycle-livedata-core:{strictly 2.0.0} -> 2.0.0 (c)

devReleaseCompileOnly - Compile only dependencies for 'devRelease' sources. (n)
No dependencies

devReleaseImplementation - Implementation only dependencies for 'devRelease' sources. (n)
No dependencies

devReleaseProvided - Provided dependencies for 'devRelease' sources (deprecated: use 'devReleaseCompileOnly' instead). (n)
No dependencies

devReleaseReverseMetadataValues - Metadata Values dependencies for the base Split
No dependencies

devReleaseRuntimeClasspath - Resolved configuration for runtime for variant: devRelease
+--- androidx.appcompat:appcompat:1.2.0
|    +--- androidx.annotation:annotation:1.1.0
|    +--- androidx.core:core:1.3.0 -> 1.3.1
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.lifecycle:lifecycle-runtime:2.0.0 -> 2.1.0
|    |    |    +--- androidx.lifecycle:lifecycle-common:2.1.0
|    |    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.arch.core:core-common:2.1.0
|    |    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.versionedparcelable:versionedparcelable:1.1.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0
|    |    |         \--- androidx.annotation:annotation:1.1.0
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.cursoradapter:cursoradapter:1.0.0
|    |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    +--- androidx.fragment:fragment:1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    +--- androidx.collection:collection:1.1.0 (*)
|    |    +--- androidx.viewpager:viewpager:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    |    \--- androidx.customview:customview:1.0.0
|    |    |         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |         \--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    +--- androidx.loader:loader:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-livedata:2.0.0
|    |    |    |    +--- androidx.arch.core:core-runtime:2.0.0
|    |    |    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    +--- androidx.lifecycle:lifecycle-livedata-core:2.0.0
|    |    |    |    |    +--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    |    +--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    |    \--- androidx.arch.core:core-runtime:2.0.0 (*)
|    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0
|    |    |         \--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.activity:activity:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-runtime:2.1.0 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-viewmodel:2.1.0 (*)
|    |    |    \--- androidx.savedstate:savedstate:1.0.0
|    |    |         +--- androidx.annotation:annotation:1.1.0
|    |    |         +--- androidx.arch.core:core-common:2.0.1 -> 2.1.0 (*)
|    |    |         \--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.1.0 (*)
|    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0 (*)
|    +--- androidx.appcompat:appcompat-resources:1.2.0
|    |    +--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.0.1 -> 1.3.1 (*)
|    |    +--- androidx.vectordrawable:vectordrawable:1.1.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    |    \--- androidx.collection:collection:1.1.0 (*)
|    |    \--- androidx.vectordrawable:vectordrawable-animated:1.1.0
|    |         +--- androidx.vectordrawable:vectordrawable:1.1.0 (*)
|    |         +--- androidx.interpolator:interpolator:1.0.0
|    |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         \--- androidx.collection:collection:1.1.0 (*)
|    +--- androidx.drawerlayout:drawerlayout:1.0.0
|    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    \--- androidx.customview:customview:1.0.0 (*)
|    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
+--- com.google.android.material:material:1.3.0
|    +--- androidx.annotation:annotation:1.0.1 -> 1.1.0
|    +--- androidx.appcompat:appcompat:1.1.0 -> 1.2.0 (*)
|    +--- androidx.cardview:cardview:1.0.0
|    |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    +--- androidx.coordinatorlayout:coordinatorlayout:1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    +--- androidx.customview:customview:1.0.0 (*)
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.constraintlayout:constraintlayout:2.0.1 -> 2.0.4
|    |    +--- androidx.appcompat:appcompat:1.2.0 (*)
|    |    +--- androidx.core:core:1.3.1 (*)
|    |    \--- androidx.constraintlayout:constraintlayout-solver:2.0.4
|    +--- androidx.core:core:1.2.0 -> 1.3.1 (*)
|    +--- androidx.dynamicanimation:dynamicanimation:1.0.0
|    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    +--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    |    \--- androidx.legacy:legacy-support-core-utils:1.0.0
|    |         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |         +--- androidx.documentfile:documentfile:1.0.0
|    |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         +--- androidx.loader:loader:1.0.0 (*)
|    |         +--- androidx.localbroadcastmanager:localbroadcastmanager:1.0.0
|    |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         \--- androidx.print:print:1.0.0
|    |              \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    +--- androidx.annotation:annotation-experimental:1.0.0
|    +--- androidx.fragment:fragment:1.0.0 -> 1.1.0 (*)
|    +--- androidx.lifecycle:lifecycle-runtime:2.0.0 -> 2.1.0 (*)
|    +--- androidx.recyclerview:recyclerview:1.0.0 -> 1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    +--- androidx.customview:customview:1.0.0 (*)
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.transition:transition:1.2.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.0.1 -> 1.3.1 (*)
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.vectordrawable:vectordrawable:1.1.0 (*)
|    \--- androidx.viewpager2:viewpager2:1.0.0
|         +--- androidx.annotation:annotation:1.1.0
|         +--- androidx.fragment:fragment:1.1.0 (*)
|         +--- androidx.recyclerview:recyclerview:1.1.0 (*)
|         +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|         \--- androidx.collection:collection:1.1.0 (*)
+--- androidx.constraintlayout:constraintlayout:2.0.4 (*)
+--- project :module_aliyun:AliyunFileDownLoader:downloadermanager
|    +--- androidx.appcompat:appcompat:1.2.0 (*)
|    \--- com.google.android.material:material:1.3.0 (*)
\--- project :module_aliyun:AlivcMedia
     +--- androidx.appcompat:appcompat:1.2.0 (*)
     \--- com.google.android.material:material:1.3.0 (*)

devReleaseRuntimeElements - Runtime elements for devRelease (n)
No dependencies

devReleaseRuntimeOnly - Runtime only dependencies for 'devRelease' sources. (n)
No dependencies

devReleaseUnitTestAnnotationProcessorClasspath - Resolved configuration for annotation-processor for variant: devReleaseUnitTest
No dependencies

devReleaseUnitTestCompileClasspath - Resolved configuration for compilation for variant: devReleaseUnitTest
+--- androidx.appcompat:appcompat:1.2.0
|    +--- androidx.annotation:annotation:1.1.0
|    +--- androidx.core:core:1.3.0 -> 1.3.1
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.lifecycle:lifecycle-runtime:2.0.0 -> 2.1.0
|    |    |    +--- androidx.lifecycle:lifecycle-common:2.1.0
|    |    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.arch.core:core-common:2.1.0
|    |    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    \--- androidx.versionedparcelable:versionedparcelable:1.1.0
|    |         +--- androidx.annotation:annotation:1.1.0
|    |         \--- androidx.collection:collection:1.0.0 -> 1.1.0
|    |              \--- androidx.annotation:annotation:1.1.0
|    +--- androidx.cursoradapter:cursoradapter:1.0.0
|    |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    +--- androidx.fragment:fragment:1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    +--- androidx.collection:collection:1.1.0 (*)
|    |    +--- androidx.viewpager:viewpager:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    |    \--- androidx.customview:customview:1.0.0
|    |    |         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |         \--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    +--- androidx.loader:loader:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-livedata:2.0.0
|    |    |    |    +--- androidx.arch.core:core-runtime:2.0.0
|    |    |    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    +--- androidx.lifecycle:lifecycle-livedata-core:2.0.0
|    |    |    |    |    +--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    |    +--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    |    \--- androidx.arch.core:core-runtime:2.0.0 (*)
|    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0
|    |    |         \--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.activity:activity:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-runtime:2.1.0 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-viewmodel:2.1.0 (*)
|    |    |    \--- androidx.savedstate:savedstate:1.0.0
|    |    |         +--- androidx.annotation:annotation:1.1.0
|    |    |         +--- androidx.arch.core:core-common:2.0.1 -> 2.1.0 (*)
|    |    |         \--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.1.0 (*)
|    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0 (*)
|    +--- androidx.appcompat:appcompat-resources:1.2.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.0.1 -> 1.3.1 (*)
|    |    +--- androidx.vectordrawable:vectordrawable:1.1.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    |    \--- androidx.collection:collection:1.1.0 (*)
|    |    \--- androidx.vectordrawable:vectordrawable-animated:1.1.0
|    |         +--- androidx.vectordrawable:vectordrawable:1.1.0 (*)
|    |         +--- androidx.interpolator:interpolator:1.0.0
|    |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         \--- androidx.collection:collection:1.1.0 (*)
|    \--- androidx.drawerlayout:drawerlayout:1.0.0
|         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|         +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|         \--- androidx.customview:customview:1.0.0 (*)
+--- com.google.android.material:material:1.3.0
|    +--- androidx.annotation:annotation:1.0.1 -> 1.1.0
|    +--- androidx.appcompat:appcompat:1.1.0 -> 1.2.0 (*)
|    +--- androidx.cardview:cardview:1.0.0
|    |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    +--- androidx.coordinatorlayout:coordinatorlayout:1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    +--- androidx.customview:customview:1.0.0 (*)
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.constraintlayout:constraintlayout:2.0.1 -> 2.0.4
|    |    +--- androidx.appcompat:appcompat:1.2.0 (*)
|    |    +--- androidx.core:core:1.3.1 (*)
|    |    \--- androidx.constraintlayout:constraintlayout-solver:2.0.4
|    +--- androidx.core:core:1.2.0 -> 1.3.1 (*)
|    +--- androidx.dynamicanimation:dynamicanimation:1.0.0
|    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    +--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    |    \--- androidx.legacy:legacy-support-core-utils:1.0.0
|    |         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |         +--- androidx.documentfile:documentfile:1.0.0
|    |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         +--- androidx.loader:loader:1.0.0 (*)
|    |         +--- androidx.localbroadcastmanager:localbroadcastmanager:1.0.0
|    |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         \--- androidx.print:print:1.0.0
|    |              \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    +--- androidx.annotation:annotation-experimental:1.0.0
|    +--- androidx.fragment:fragment:1.0.0 -> 1.1.0 (*)
|    +--- androidx.lifecycle:lifecycle-runtime:2.0.0 -> 2.1.0 (*)
|    +--- androidx.recyclerview:recyclerview:1.0.0 -> 1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    +--- androidx.customview:customview:1.0.0 (*)
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.transition:transition:1.2.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.0.1 -> 1.3.1 (*)
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.vectordrawable:vectordrawable:1.1.0 (*)
|    \--- androidx.viewpager2:viewpager2:1.0.0
|         +--- androidx.annotation:annotation:1.1.0
|         +--- androidx.fragment:fragment:1.1.0 (*)
|         +--- androidx.recyclerview:recyclerview:1.1.0 (*)
|         +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|         \--- androidx.collection:collection:1.1.0 (*)
+--- androidx.constraintlayout:constraintlayout:2.0.4 (*)
+--- project :module_aliyun:AliyunFileDownLoader:downloadermanager
+--- project :module_aliyun:AlivcMedia
+--- androidx.appcompat:appcompat:{strictly 1.2.0} -> 1.2.0 (c)
+--- com.google.android.material:material:{strictly 1.3.0} -> 1.3.0 (c)
+--- androidx.constraintlayout:constraintlayout:{strictly 2.0.4} -> 2.0.4 (c)
+--- androidx.annotation:annotation:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.core:core:{strictly 1.3.1} -> 1.3.1 (c)
+--- androidx.cursoradapter:cursoradapter:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.fragment:fragment:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.appcompat:appcompat-resources:{strictly 1.2.0} -> 1.2.0 (c)
+--- androidx.drawerlayout:drawerlayout:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.cardview:cardview:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.coordinatorlayout:coordinatorlayout:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.dynamicanimation:dynamicanimation:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.annotation:annotation-experimental:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.lifecycle:lifecycle-runtime:{strictly 2.1.0} -> 2.1.0 (c)
+--- androidx.recyclerview:recyclerview:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.transition:transition:{strictly 1.2.0} -> 1.2.0 (c)
+--- androidx.vectordrawable:vectordrawable:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.viewpager2:viewpager2:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.constraintlayout:constraintlayout-solver:{strictly 2.0.4} -> 2.0.4 (c)
+--- androidx.versionedparcelable:versionedparcelable:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.collection:collection:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.viewpager:viewpager:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.loader:loader:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.activity:activity:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.lifecycle:lifecycle-viewmodel:{strictly 2.1.0} -> 2.1.0 (c)
+--- androidx.vectordrawable:vectordrawable-animated:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.customview:customview:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.legacy:legacy-support-core-utils:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.lifecycle:lifecycle-common:{strictly 2.1.0} -> 2.1.0 (c)
+--- androidx.arch.core:core-common:{strictly 2.1.0} -> 2.1.0 (c)
+--- androidx.lifecycle:lifecycle-livedata:{strictly 2.0.0} -> 2.0.0 (c)
+--- androidx.savedstate:savedstate:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.interpolator:interpolator:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.documentfile:documentfile:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.localbroadcastmanager:localbroadcastmanager:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.print:print:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.arch.core:core-runtime:{strictly 2.0.0} -> 2.0.0 (c)
\--- androidx.lifecycle:lifecycle-livedata-core:{strictly 2.0.0} -> 2.0.0 (c)

devReleaseUnitTestRuntimeClasspath - Resolved configuration for runtime for variant: devReleaseUnitTest
+--- androidx.appcompat:appcompat:1.2.0
|    +--- androidx.annotation:annotation:1.1.0
|    +--- androidx.core:core:1.3.0 -> 1.3.1
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.lifecycle:lifecycle-runtime:2.0.0 -> 2.1.0
|    |    |    +--- androidx.lifecycle:lifecycle-common:2.1.0
|    |    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.arch.core:core-common:2.1.0
|    |    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.versionedparcelable:versionedparcelable:1.1.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0
|    |    |         \--- androidx.annotation:annotation:1.1.0
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.cursoradapter:cursoradapter:1.0.0
|    |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    +--- androidx.fragment:fragment:1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    +--- androidx.collection:collection:1.1.0 (*)
|    |    +--- androidx.viewpager:viewpager:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    |    \--- androidx.customview:customview:1.0.0
|    |    |         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |         \--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    +--- androidx.loader:loader:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-livedata:2.0.0
|    |    |    |    +--- androidx.arch.core:core-runtime:2.0.0
|    |    |    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    +--- androidx.lifecycle:lifecycle-livedata-core:2.0.0
|    |    |    |    |    +--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    |    +--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    |    \--- androidx.arch.core:core-runtime:2.0.0 (*)
|    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0
|    |    |         \--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.activity:activity:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-runtime:2.1.0 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-viewmodel:2.1.0 (*)
|    |    |    \--- androidx.savedstate:savedstate:1.0.0
|    |    |         +--- androidx.annotation:annotation:1.1.0
|    |    |         +--- androidx.arch.core:core-common:2.0.1 -> 2.1.0 (*)
|    |    |         \--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.1.0 (*)
|    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0 (*)
|    +--- androidx.appcompat:appcompat-resources:1.2.0
|    |    +--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.0.1 -> 1.3.1 (*)
|    |    +--- androidx.vectordrawable:vectordrawable:1.1.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    |    \--- androidx.collection:collection:1.1.0 (*)
|    |    \--- androidx.vectordrawable:vectordrawable-animated:1.1.0
|    |         +--- androidx.vectordrawable:vectordrawable:1.1.0 (*)
|    |         +--- androidx.interpolator:interpolator:1.0.0
|    |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         \--- androidx.collection:collection:1.1.0 (*)
|    +--- androidx.drawerlayout:drawerlayout:1.0.0
|    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    \--- androidx.customview:customview:1.0.0 (*)
|    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
+--- com.google.android.material:material:1.3.0
|    +--- androidx.annotation:annotation:1.0.1 -> 1.1.0
|    +--- androidx.appcompat:appcompat:1.1.0 -> 1.2.0 (*)
|    +--- androidx.cardview:cardview:1.0.0
|    |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    +--- androidx.coordinatorlayout:coordinatorlayout:1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    +--- androidx.customview:customview:1.0.0 (*)
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.constraintlayout:constraintlayout:2.0.1 -> 2.0.4
|    |    +--- androidx.appcompat:appcompat:1.2.0 (*)
|    |    +--- androidx.core:core:1.3.1 (*)
|    |    \--- androidx.constraintlayout:constraintlayout-solver:2.0.4
|    +--- androidx.core:core:1.2.0 -> 1.3.1 (*)
|    +--- androidx.dynamicanimation:dynamicanimation:1.0.0
|    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    +--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    |    \--- androidx.legacy:legacy-support-core-utils:1.0.0
|    |         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |         +--- androidx.documentfile:documentfile:1.0.0
|    |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         +--- androidx.loader:loader:1.0.0 (*)
|    |         +--- androidx.localbroadcastmanager:localbroadcastmanager:1.0.0
|    |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         \--- androidx.print:print:1.0.0
|    |              \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    +--- androidx.annotation:annotation-experimental:1.0.0
|    +--- androidx.fragment:fragment:1.0.0 -> 1.1.0 (*)
|    +--- androidx.lifecycle:lifecycle-runtime:2.0.0 -> 2.1.0 (*)
|    +--- androidx.recyclerview:recyclerview:1.0.0 -> 1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    +--- androidx.customview:customview:1.0.0 (*)
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.transition:transition:1.2.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.0.1 -> 1.3.1 (*)
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.vectordrawable:vectordrawable:1.1.0 (*)
|    \--- androidx.viewpager2:viewpager2:1.0.0
|         +--- androidx.annotation:annotation:1.1.0
|         +--- androidx.fragment:fragment:1.1.0 (*)
|         +--- androidx.recyclerview:recyclerview:1.1.0 (*)
|         +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|         \--- androidx.collection:collection:1.1.0 (*)
+--- androidx.constraintlayout:constraintlayout:2.0.4 (*)
+--- project :module_aliyun:AliyunFileDownLoader:downloadermanager
|    +--- androidx.appcompat:appcompat:1.2.0 (*)
|    \--- com.google.android.material:material:1.3.0 (*)
\--- project :module_aliyun:AlivcMedia
     +--- androidx.appcompat:appcompat:1.2.0 (*)
     \--- com.google.android.material:material:1.3.0 (*)

devReleaseWearApp - Link to a wear app to embed for object 'devRelease'. (n)
No dependencies

devReleaseWearBundling - Resolved Configuration for wear app bundling for variant: devRelease
No dependencies

devRuntimeOnly - Runtime only dependencies for 'dev' sources. (n)
No dependencies

devWearApp - Link to a wear app to embed for object 'dev'. (n)
No dependencies

implementation - Implementation only dependencies for 'main' sources. (n)
+--- androidx.appcompat:appcompat:1.2.0 (n)
+--- com.google.android.material:material:1.3.0 (n)
+--- androidx.constraintlayout:constraintlayout:2.0.4 (n)
+--- project downloadermanager (n)
\--- project AlivcMedia (n)

lintChecks - Configuration to apply external lint check jar
No dependencies

lintClassPath - The lint embedded classpath
\--- com.android.tools.lint:lint-gradle:27.0.1
     +--- com.android.tools:sdk-common:27.0.1
     |    +--- com.android.tools:sdklib:27.0.1
     |    |    +--- com.android.tools.layoutlib:layoutlib-api:27.0.1
     |    |    |    +--- com.android.tools:common:27.0.1
     |    |    |    |    +--- com.android.tools:annotations:27.0.1
     |    |    |    |    +--- com.google.guava:guava:28.1-jre
     |    |    |    |    |    +--- com.google.guava:failureaccess:1.0.1
     |    |    |    |    |    +--- com.google.guava:listenablefuture:9999.0-empty-to-avoid-conflict-with-guava
     |    |    |    |    |    +--- com.google.code.findbugs:jsr305:3.0.2
     |    |    |    |    |    +--- org.checkerframework:checker-qual:2.8.1
     |    |    |    |    |    +--- com.google.errorprone:error_prone_annotations:2.3.2
     |    |    |    |    |    +--- com.google.j2objc:j2objc-annotations:1.3
     |    |    |    |    |    \--- org.codehaus.mojo:animal-sniffer-annotations:1.18
     |    |    |    |    \--- org.jetbrains.kotlin:kotlin-stdlib-jdk8:1.3.72
     |    |    |    |         +--- org.jetbrains.kotlin:kotlin-stdlib:1.3.72
     |    |    |    |         |    +--- org.jetbrains.kotlin:kotlin-stdlib-common:1.3.72
     |    |    |    |         |    \--- org.jetbrains:annotations:13.0
     |    |    |    |         \--- org.jetbrains.kotlin:kotlin-stdlib-jdk7:1.3.72
     |    |    |    |              \--- org.jetbrains.kotlin:kotlin-stdlib:1.3.72 (*)
     |    |    |    +--- net.sf.kxml:kxml2:2.3.0
     |    |    |    +--- com.android.tools:annotations:27.0.1
     |    |    |    \--- org.jetbrains:annotations:13.0
     |    |    +--- com.android.tools:dvlib:27.0.1
     |    |    |    \--- com.android.tools:common:27.0.1 (*)
     |    |    +--- com.android.tools:repository:27.0.1
     |    |    |    +--- com.android.tools:common:27.0.1 (*)
     |    |    |    +--- com.sun.activation:javax.activation:1.2.0
     |    |    |    +--- org.apache.commons:commons-compress:1.12
     |    |    |    +--- org.glassfish.jaxb:jaxb-runtime:2.3.1
     |    |    |    |    +--- javax.xml.bind:jaxb-api:2.3.1
     |    |    |    |    |    \--- javax.activation:javax.activation-api:1.2.0
     |    |    |    |    +--- org.glassfish.jaxb:txw2:2.3.1
     |    |    |    |    +--- com.sun.istack:istack-commons-runtime:3.0.7
     |    |    |    |    +--- org.jvnet.staxex:stax-ex:1.8
     |    |    |    |    +--- com.sun.xml.fastinfoset:FastInfoset:1.2.15
     |    |    |    |    \--- javax.activation:javax.activation-api:1.2.0
     |    |    |    +--- com.google.jimfs:jimfs:1.1
     |    |    |    |    \--- com.google.guava:guava:18.0 -> 28.1-jre (*)
     |    |    |    \--- org.jetbrains.kotlin:kotlin-stdlib-jdk8:1.3.72 (*)
     |    |    +--- com.google.code.gson:gson:2.8.5
     |    |    +--- org.apache.commons:commons-compress:1.12
     |    |    +--- org.apache.httpcomponents:httpmime:4.5.6
     |    |    |    \--- org.apache.httpcomponents:httpclient:4.5.6
     |    |    |         +--- org.apache.httpcomponents:httpcore:4.4.10
     |    |    |         +--- commons-logging:commons-logging:1.2
     |    |    |         \--- commons-codec:commons-codec:1.10
     |    |    \--- org.apache.httpcomponents:httpcore:4.4.10
     |    +--- com.android.tools.build:builder-test-api:4.0.1
     |    |    \--- com.android.tools.ddms:ddmlib:27.0.1
     |    |         +--- com.android.tools:common:27.0.1 (*)
     |    |         \--- net.sf.kxml:kxml2:2.3.0
     |    +--- com.android.tools.build:builder-model:4.0.1
     |    |    \--- com.android.tools:annotations:27.0.1
     |    +--- com.android.tools.ddms:ddmlib:27.0.1 (*)
     |    +--- com.android.tools.analytics-library:shared:27.0.1
     |    |    +--- com.android.tools.analytics-library:protos:27.0.1
     |    |    |    \--- com.google.protobuf:protobuf-java:3.10.0
     |    |    +--- com.android.tools:annotations:27.0.1
     |    |    +--- com.android.tools:common:27.0.1 (*)
     |    |    +--- com.google.guava:guava:28.1-jre (*)
     |    |    +--- com.google.code.gson:gson:2.8.5
     |    |    \--- org.jetbrains.kotlin:kotlin-stdlib-jdk8:1.3.72 (*)
     |    +--- org.bouncycastle:bcpkix-jdk15on:1.56
     |    |    \--- org.bouncycastle:bcprov-jdk15on:1.56
     |    +--- org.bouncycastle:bcprov-jdk15on:1.56
     |    +--- org.jetbrains.kotlin:kotlin-stdlib-jdk8:1.3.72 (*)
     |    +--- org.jetbrains.kotlin:kotlin-reflect:1.3.72
     |    |    \--- org.jetbrains.kotlin:kotlin-stdlib:1.3.72 (*)
     |    +--- com.google.protobuf:protobuf-java:3.10.0
     |    +--- javax.inject:javax.inject:1
     |    +--- org.jetbrains.trove4j:trove4j:20160824
     |    \--- com.android.tools.build:aapt2-proto:0.4.0
     |         \--- com.google.protobuf:protobuf-java:3.4.0 -> 3.10.0
     +--- com.android.tools.build:builder:4.0.1
     |    +--- com.android.tools.build:builder-model:4.0.1 (*)
     |    +--- com.android.tools.build:builder-test-api:4.0.1 (*)
     |    +--- com.android.tools:sdklib:27.0.1 (*)
     |    +--- com.android.tools:sdk-common:27.0.1 (*)
     |    +--- com.android.tools:common:27.0.1 (*)
     |    +--- com.android.tools.build:manifest-merger:27.0.1
     |    |    +--- com.android.tools:common:27.0.1 (*)
     |    |    +--- com.android.tools:sdklib:27.0.1 (*)
     |    |    +--- com.android.tools:sdk-common:27.0.1 (*)
     |    |    +--- com.google.code.gson:gson:2.8.5
     |    |    +--- org.jetbrains.kotlin:kotlin-stdlib-jdk8:1.3.72 (*)
     |    |    \--- net.sf.kxml:kxml2:2.3.0
     |    +--- com.android.tools.ddms:ddmlib:27.0.1 (*)
     |    +--- com.android:zipflinger:4.0.1
     |    |    +--- com.google.guava:guava:27.0.1-jre -> 28.1-jre (*)
     |    |    \--- com.android.tools:common:27.0.1 (*)
     |    +--- com.android:signflinger:4.0.1
     |    |    +--- com.android.tools.build:apksig:4.0.1
     |    |    \--- com.android:zipflinger:4.0.1 (*)
     |    +--- com.android.tools.analytics-library:protos:27.0.1 (*)
     |    +--- com.android.tools.analytics-library:tracker:27.0.1
     |    |    +--- com.android.tools:annotations:27.0.1
     |    |    +--- com.android.tools:common:27.0.1 (*)
     |    |    +--- com.android.tools.analytics-library:protos:27.0.1 (*)
     |    |    +--- com.android.tools.analytics-library:shared:27.0.1 (*)
     |    |    +--- com.google.protobuf:protobuf-java:3.10.0
     |    |    +--- com.google.guava:guava:28.1-jre (*)
     |    |    \--- org.jetbrains.kotlin:kotlin-stdlib-jdk8:1.3.72 (*)
     |    +--- com.android.tools.build:apksig:4.0.1
     |    +--- com.android.tools.build:apkzlib:4.0.1
     |    |    +--- com.google.code.findbugs:jsr305:1.3.9 -> 3.0.2
     |    |    +--- com.google.guava:guava:23.0 -> 28.1-jre (*)
     |    |    +--- org.bouncycastle:bcpkix-jdk15on:1.56 (*)
     |    |    +--- org.bouncycastle:bcprov-jdk15on:1.56
     |    |    \--- com.android.tools.build:apksig:4.0.1
     |    +--- org.jetbrains.kotlin:kotlin-stdlib-jdk8:1.3.72 (*)
     |    +--- com.squareup:javawriter:2.5.0
     |    +--- org.bouncycastle:bcpkix-jdk15on:1.56 (*)
     |    +--- org.bouncycastle:bcprov-jdk15on:1.56
     |    +--- org.ow2.asm:asm:7.0
     |    +--- org.ow2.asm:asm-tree:7.0
     |    |    \--- org.ow2.asm:asm:7.0
     |    +--- javax.inject:javax.inject:1
     |    +--- org.ow2.asm:asm-commons:7.0
     |    |    +--- org.ow2.asm:asm:7.0
     |    |    +--- org.ow2.asm:asm-tree:7.0 (*)
     |    |    \--- org.ow2.asm:asm-analysis:7.0
     |    |         \--- org.ow2.asm:asm-tree:7.0 (*)
     |    +--- org.ow2.asm:asm-util:7.0
     |    |    +--- org.ow2.asm:asm:7.0
     |    |    +--- org.ow2.asm:asm-tree:7.0 (*)
     |    |    \--- org.ow2.asm:asm-analysis:7.0 (*)
     |    +--- it.unimi.dsi:fastutil:7.2.0
     |    +--- net.sf.jopt-simple:jopt-simple:4.9
     |    \--- com.googlecode.json-simple:json-simple:1.1
     +--- com.android.tools.build:builder-model:4.0.1 (*)
     +--- com.android.tools.external.com-intellij:intellij-core:27.0.1
     |    \--- org.jetbrains.trove4j:trove4j:20160824
     +--- com.android.tools.external.com-intellij:kotlin-compiler:27.0.1
     +--- com.android.tools.external.org-jetbrains:uast:27.0.1
     +--- com.android.tools.build:manifest-merger:27.0.1 (*)
     +--- com.android.tools.lint:lint:27.0.1
     |    +--- com.android.tools.lint:lint-checks:27.0.1
     |    |    +--- com.android.tools.lint:lint-api:27.0.1
     |    |    |    +--- com.android.tools:sdk-common:27.0.1 (*)
     |    |    |    +--- com.android.tools.build:builder-model:4.0.1 (*)
     |    |    |    +--- com.google.guava:guava:28.1-jre (*)
     |    |    |    +--- com.android.tools.external.com-intellij:intellij-core:27.0.1 (*)
     |    |    |    +--- com.android.tools.external.com-intellij:kotlin-compiler:27.0.1
     |    |    |    +--- com.android.tools.external.org-jetbrains:uast:27.0.1
     |    |    |    +--- com.android.tools.build:manifest-merger:27.0.1 (*)
     |    |    |    +--- org.ow2.asm:asm:7.0
     |    |    |    +--- org.ow2.asm:asm-tree:7.0 (*)
     |    |    |    +--- org.jetbrains.kotlin:kotlin-reflect:1.3.72 (*)
     |    |    |    \--- org.jetbrains.kotlin:kotlin-stdlib-jdk8:1.3.72 (*)
     |    |    +--- com.google.guava:guava:28.1-jre (*)
     |    |    +--- com.android.tools.external.com-intellij:intellij-core:27.0.1 (*)
     |    |    +--- com.android.tools.external.com-intellij:kotlin-compiler:27.0.1
     |    |    +--- com.android.tools.external.org-jetbrains:uast:27.0.1
     |    |    \--- org.ow2.asm:asm-analysis:7.0 (*)
     |    +--- com.google.guava:guava:28.1-jre (*)
     |    +--- com.android.tools.external.org-jetbrains:uast:27.0.1
     |    +--- com.android.tools.external.com-intellij:kotlin-compiler:27.0.1
     |    +--- com.android.tools.build:manifest-merger:27.0.1 (*)
     |    +--- com.android.tools.analytics-library:shared:27.0.1 (*)
     |    +--- com.android.tools.analytics-library:protos:27.0.1 (*)
     |    +--- com.android.tools.analytics-library:tracker:27.0.1 (*)
     |    +--- org.jetbrains.kotlin:kotlin-reflect:1.3.72 (*)
     |    \--- org.jetbrains.kotlin:kotlin-stdlib-jdk8:1.3.72 (*)
     +--- com.android.tools.lint:lint-gradle-api:27.0.1
     |    +--- com.android.tools:sdklib:27.0.1 (*)
     |    +--- com.android.tools.build:builder-model:4.0.1 (*)
     |    +--- com.android.tools.build:gradle-api:4.0.1
     |    |    +--- com.android.tools.build:builder-test-api:4.0.1 (*)
     |    |    +--- com.google.guava:guava:28.1-jre (*)
     |    |    \--- org.jetbrains.kotlin:kotlin-stdlib-jdk8:1.3.72 (*)
     |    +--- org.jetbrains.kotlin:kotlin-reflect:1.3.72 (*)
     |    +--- org.jetbrains.kotlin:kotlin-stdlib-jdk8:1.3.72 (*)
     |    \--- com.google.guava:guava:28.1-jre (*)
     +--- com.android:zipflinger:4.0.1 (*)
     +--- org.codehaus.groovy:groovy-all:2.4.15
     +--- org.jetbrains.kotlin:kotlin-reflect:1.3.72 (*)
     \--- org.jetbrains.kotlin:kotlin-stdlib-jdk8:1.3.72 (*)

lintPublish - Configuration to publish external lint check jar
No dependencies

provided - Provided dependencies for 'main' sources (deprecated: use 'compileOnly' instead). (n)
No dependencies

releaseAnnotationProcessor - Classpath for the annotation processor for 'release'. (n)
No dependencies

releaseApi - API dependencies for 'release' sources. (n)
No dependencies

releaseApk - Apk dependencies for 'release' sources (deprecated: use 'releaseRuntimeOnly' instead). (n)
No dependencies

releaseCompile - Compile dependencies for 'release' sources (deprecated: use 'releaseImplementation' instead). (n)
No dependencies

releaseCompileOnly - Compile only dependencies for 'release' sources. (n)
No dependencies

releaseImplementation - Implementation only dependencies for 'release' sources. (n)
No dependencies

releaseProvided - Provided dependencies for 'release' sources (deprecated: use 'releaseCompileOnly' instead). (n)
No dependencies

releaseRuntimeOnly - Runtime only dependencies for 'release' sources. (n)
No dependencies

releaseWearApp - Link to a wear app to embed for object 'release'. (n)
No dependencies

runtimeOnly - Runtime only dependencies for 'main' sources. (n)
No dependencies

testAnnotationProcessor - Classpath for the annotation processor for 'test'. (n)
No dependencies

testApi - API dependencies for 'test' sources. (n)
No dependencies

testApk - Apk dependencies for 'test' sources (deprecated: use 'testRuntimeOnly' instead). (n)
No dependencies

testCompile - Compile dependencies for 'test' sources (deprecated: use 'testImplementation' instead).
No dependencies

testCompileOnly - Compile only dependencies for 'test' sources. (n)
No dependencies

testDebugAnnotationProcessor - Classpath for the annotation processor for 'testDebug'. (n)
No dependencies

testDebugApi - API dependencies for 'testDebug' sources. (n)
No dependencies

testDebugApk - Apk dependencies for 'testDebug' sources (deprecated: use 'testDebugRuntimeOnly' instead). (n)
No dependencies

testDebugCompile - Compile dependencies for 'testDebug' sources (deprecated: use 'testDebugImplementation' instead). (n)
No dependencies

testDebugCompileOnly - Compile only dependencies for 'testDebug' sources. (n)
No dependencies

testDebugImplementation - Implementation only dependencies for 'testDebug' sources. (n)
No dependencies

testDebugProvided - Provided dependencies for 'testDebug' sources (deprecated: use 'testDebugCompileOnly' instead). (n)
No dependencies

testDebugRuntimeOnly - Runtime only dependencies for 'testDebug' sources. (n)
No dependencies

testDebugWearApp - Link to a wear app to embed for object 'testDebug'. (n)
No dependencies

testDevAnnotationProcessor - Classpath for the annotation processor for 'testDev'. (n)
No dependencies

testDevApi - API dependencies for 'testDev' sources. (n)
No dependencies

testDevApk - Apk dependencies for 'testDev' sources (deprecated: use 'testDevRuntimeOnly' instead). (n)
No dependencies

testDevCompile - Compile dependencies for 'testDev' sources (deprecated: use 'testDevImplementation' instead). (n)
No dependencies

testDevCompileOnly - Compile only dependencies for 'testDev' sources. (n)
No dependencies

testDevDebugAnnotationProcessor - Classpath for the annotation processor for 'testDevDebug'. (n)
No dependencies

testDevDebugApi - API dependencies for 'testDevDebug' sources. (n)
No dependencies

testDevDebugApk - Apk dependencies for 'testDevDebug' sources (deprecated: use 'testDevDebugRuntimeOnly' instead). (n)
No dependencies

testDevDebugCompile - Compile dependencies for 'testDevDebug' sources (deprecated: use 'testDevDebugImplementation' instead). (n)
No dependencies

testDevDebugCompileOnly - Compile only dependencies for 'testDevDebug' sources. (n)
No dependencies

testDevDebugImplementation - Implementation only dependencies for 'testDevDebug' sources. (n)
No dependencies

testDevDebugProvided - Provided dependencies for 'testDevDebug' sources (deprecated: use 'testDevDebugCompileOnly' instead). (n)
No dependencies

testDevDebugRuntimeOnly - Runtime only dependencies for 'testDevDebug' sources. (n)
No dependencies

testDevDebugWearApp - Link to a wear app to embed for object 'testDevDebug'. (n)
No dependencies

testDevImplementation - Implementation only dependencies for 'testDev' sources. (n)
No dependencies

testDevProvided - Provided dependencies for 'testDev' sources (deprecated: use 'testDevCompileOnly' instead). (n)
No dependencies

testDevReleaseAnnotationProcessor - Classpath for the annotation processor for 'testDevRelease'. (n)
No dependencies

testDevReleaseApi - API dependencies for 'testDevRelease' sources. (n)
No dependencies

testDevReleaseApk - Apk dependencies for 'testDevRelease' sources (deprecated: use 'testDevReleaseRuntimeOnly' instead). (n)
No dependencies

testDevReleaseCompile - Compile dependencies for 'testDevRelease' sources (deprecated: use 'testDevReleaseImplementation' instead). (n)
No dependencies

testDevReleaseCompileOnly - Compile only dependencies for 'testDevRelease' sources. (n)
No dependencies

testDevReleaseImplementation - Implementation only dependencies for 'testDevRelease' sources. (n)
No dependencies

testDevReleaseProvided - Provided dependencies for 'testDevRelease' sources (deprecated: use 'testDevReleaseCompileOnly' instead). (n)
No dependencies

testDevReleaseRuntimeOnly - Runtime only dependencies for 'testDevRelease' sources. (n)
No dependencies

testDevReleaseWearApp - Link to a wear app to embed for object 'testDevRelease'. (n)
No dependencies

testDevRuntimeOnly - Runtime only dependencies for 'testDev' sources. (n)
No dependencies

testDevWearApp - Link to a wear app to embed for object 'testDev'. (n)
No dependencies

testImplementation - Implementation only dependencies for 'test' sources. (n)
No dependencies

testProvided - Provided dependencies for 'test' sources (deprecated: use 'testCompileOnly' instead). (n)
No dependencies

testReleaseAnnotationProcessor - Classpath for the annotation processor for 'testRelease'. (n)
No dependencies

testReleaseApi - API dependencies for 'testRelease' sources. (n)
No dependencies

testReleaseApk - Apk dependencies for 'testRelease' sources (deprecated: use 'testReleaseRuntimeOnly' instead). (n)
No dependencies

testReleaseCompile - Compile dependencies for 'testRelease' sources (deprecated: use 'testReleaseImplementation' instead). (n)
No dependencies

testReleaseCompileOnly - Compile only dependencies for 'testRelease' sources. (n)
No dependencies

testReleaseImplementation - Implementation only dependencies for 'testRelease' sources. (n)
No dependencies

testReleaseProvided - Provided dependencies for 'testRelease' sources (deprecated: use 'testReleaseCompileOnly' instead). (n)
No dependencies

testReleaseRuntimeOnly - Runtime only dependencies for 'testRelease' sources. (n)
No dependencies

testReleaseWearApp - Link to a wear app to embed for object 'testRelease'. (n)
No dependencies

testRuntimeOnly - Runtime only dependencies for 'test' sources. (n)
No dependencies

testWearApp - Link to a wear app to embed for object 'test'. (n)
No dependencies

test_testAnnotationProcessor - Classpath for the annotation processor for 'test_test'. (n)
No dependencies

test_testApi - API dependencies for 'test_test' sources. (n)
No dependencies

test_testApk - Apk dependencies for 'test_test' sources (deprecated: use 'test_testRuntimeOnly' instead). (n)
No dependencies

test_testCompile - Compile dependencies for 'test_test' sources (deprecated: use 'test_testImplementation' instead). (n)
No dependencies

test_testCompileOnly - Compile only dependencies for 'test_test' sources. (n)
No dependencies

test_testDebugAnnotationProcessor - Classpath for the annotation processor for 'test_testDebug'. (n)
No dependencies

test_testDebugApi - API dependencies for 'test_testDebug' sources. (n)
No dependencies

test_testDebugApk - Apk dependencies for 'test_testDebug' sources (deprecated: use 'test_testDebugRuntimeOnly' instead). (n)
No dependencies

test_testDebugCompile - Compile dependencies for 'test_testDebug' sources (deprecated: use 'test_testDebugImplementation' instead). (n)
No dependencies

test_testDebugCompileOnly - Compile only dependencies for 'test_testDebug' sources. (n)
No dependencies

test_testDebugImplementation - Implementation only dependencies for 'test_testDebug' sources. (n)
No dependencies

test_testDebugProvided - Provided dependencies for 'test_testDebug' sources (deprecated: use 'test_testDebugCompileOnly' instead). (n)
No dependencies

test_testDebugRuntimeOnly - Runtime only dependencies for 'test_testDebug' sources. (n)
No dependencies

test_testDebugWearApp - Link to a wear app to embed for object 'test_testDebug'. (n)
No dependencies

test_testImplementation - Implementation only dependencies for 'test_test' sources. (n)
No dependencies

test_testProvided - Provided dependencies for 'test_test' sources (deprecated: use 'test_testCompileOnly' instead). (n)
No dependencies

test_testReleaseAnnotationProcessor - Classpath for the annotation processor for 'test_testRelease'. (n)
No dependencies

test_testReleaseApi - API dependencies for 'test_testRelease' sources. (n)
No dependencies

test_testReleaseApk - Apk dependencies for 'test_testRelease' sources (deprecated: use 'test_testReleaseRuntimeOnly' instead). (n)
No dependencies

test_testReleaseCompile - Compile dependencies for 'test_testRelease' sources (deprecated: use 'test_testReleaseImplementation' instead). (n)
No dependencies

test_testReleaseCompileOnly - Compile only dependencies for 'test_testRelease' sources. (n)
No dependencies

test_testReleaseImplementation - Implementation only dependencies for 'test_testRelease' sources. (n)
No dependencies

test_testReleaseProvided - Provided dependencies for 'test_testRelease' sources (deprecated: use 'test_testReleaseCompileOnly' instead). (n)
No dependencies

test_testReleaseRuntimeOnly - Runtime only dependencies for 'test_testRelease' sources. (n)
No dependencies

test_testReleaseWearApp - Link to a wear app to embed for object 'test_testRelease'. (n)
No dependencies

test_testRuntimeOnly - Runtime only dependencies for 'test_test' sources. (n)
No dependencies

test_testWearApp - Link to a wear app to embed for object 'test_test'. (n)
No dependencies

wearApp - Link to a wear app to embed for object 'main'. (n)
No dependencies

(c) - dependency constraint
(*) - dependencies omitted (listed previously)

(n) - Not resolved (configuration is not meant to be resolved)

A web-based, searchable dependency report is available by adding the --scan option.

Deprecated Gradle features were used in this build, making it incompatible with Gradle 7.0.
Use '--warning-mode all' to show the individual deprecation warnings.
See https://docs.gradle.org/6.1.1/userguide/command_line_interface.html#sec:command_line_warnings

BUILD SUCCESSFUL in 9s
1 actionable task: 1 executed
generateLockfiles

> Configure project :app
WARNING: DSL element 'annotationProcessorOptions.includeCompileClasspath' is obsolete.
It will be removed in version 5.0 of the Android Gradle plugin.
It does not do anything and AGP no longer includes annotation processors added on your project's compile classpath

> Task :flutter:dependencies

------------------------------------------------------------
Project :flutter
------------------------------------------------------------

_internal_aapt2_binary - The AAPT2 binary to use for processing resources.
\--- com.android.tools.build:aapt2:4.0.1-6197926

androidApis - Configuration providing various types of Android JAR file
No dependencies

androidTestAnnotationProcessor - Classpath for the annotation processor for 'androidTest'. (n)
No dependencies

androidTestApi - API dependencies for 'androidTest' sources. (n)
No dependencies

androidTestCompile - Compile dependencies for 'androidTest' sources (deprecated: use 'androidTestImplementation' instead). (n)
No dependencies

androidTestCompileOnly - Compile only dependencies for 'androidTest' sources. (n)
No dependencies

androidTestDebugAnnotationProcessor - Classpath for the annotation processor for 'androidTestDebug'. (n)
No dependencies

androidTestDebugApi - API dependencies for 'androidTestDebug' sources. (n)
No dependencies

androidTestDebugCompile - Compile dependencies for 'androidTestDebug' sources (deprecated: use 'androidTestDebugImplementation' instead). (n)
No dependencies

androidTestDebugCompileOnly - Compile only dependencies for 'androidTestDebug' sources. (n)
No dependencies

androidTestDebugImplementation - Implementation only dependencies for 'androidTestDebug' sources. (n)
No dependencies

androidTestDebugProvided - Provided dependencies for 'androidTestDebug' sources (deprecated: use 'androidTestDebugCompileOnly' instead). (n)
No dependencies

androidTestDebugPublish - Publish dependencies for 'androidTestDebug' sources (deprecated: use 'androidTestDebugRuntimeOnly' instead). (n)
No dependencies

androidTestDebugRuntimeOnly - Runtime only dependencies for 'androidTestDebug' sources. (n)
No dependencies

androidTestDebugWearApp - Link to a wear app to embed for object 'androidTestDebug'. (n)
No dependencies

androidTestImplementation - Implementation only dependencies for 'androidTest' sources. (n)
No dependencies

androidTestProvided - Provided dependencies for 'androidTest' sources (deprecated: use 'androidTestCompileOnly' instead). (n)
No dependencies

androidTestPublish - Publish dependencies for 'androidTest' sources (deprecated: use 'androidTestRuntimeOnly' instead). (n)
No dependencies

androidTestRuntimeOnly - Runtime only dependencies for 'androidTest' sources. (n)
No dependencies

androidTestUtil - Additional APKs used during instrumentation testing.
No dependencies

androidTestWearApp - Link to a wear app to embed for object 'androidTest'. (n)
No dependencies

annotationProcessor - Classpath for the annotation processor for 'main'. (n)
No dependencies

api - API dependencies for 'main' sources. (n)
No dependencies

archives - Configuration for archive artifacts.
+--- io.flutter:flutter_embedding_release:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
|    +--- androidx.lifecycle:lifecycle-common:2.2.0
|    |    \--- androidx.annotation:annotation:1.1.0
|    +--- androidx.lifecycle:lifecycle-common-java8:2.2.0
|    |    +--- androidx.lifecycle:lifecycle-common:2.2.0 (*)
|    |    \--- androidx.annotation:annotation:1.1.0
|    +--- androidx.lifecycle:lifecycle-runtime:2.2.0
|    |    +--- androidx.lifecycle:lifecycle-common:2.2.0 (*)
|    |    +--- androidx.arch.core:core-common:2.1.0
|    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    \--- androidx.annotation:annotation:1.1.0
|    +--- androidx.fragment:fragment:1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.lifecycle:lifecycle-runtime:2.0.0 -> 2.2.0 (*)
|    |    |    +--- androidx.versionedparcelable:versionedparcelable:1.1.0
|    |    |    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0
|    |    |    |         \--- androidx.annotation:annotation:1.1.0
|    |    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    |    +--- androidx.collection:collection:1.1.0 (*)
|    |    +--- androidx.viewpager:viewpager:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    +--- androidx.core:core:1.0.0 -> 1.1.0 (*)
|    |    |    \--- androidx.customview:customview:1.0.0
|    |    |         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |         \--- androidx.core:core:1.0.0 -> 1.1.0 (*)
|    |    +--- androidx.loader:loader:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    +--- androidx.core:core:1.0.0 -> 1.1.0 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-livedata:2.0.0
|    |    |    |    +--- androidx.arch.core:core-runtime:2.0.0
|    |    |    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    +--- androidx.lifecycle:lifecycle-livedata-core:2.0.0
|    |    |    |    |    +--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.2.0 (*)
|    |    |    |    |    +--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    |    \--- androidx.arch.core:core-runtime:2.0.0 (*)
|    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0
|    |    |         \--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.activity:activity:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.core:core:1.1.0 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-runtime:2.1.0 -> 2.2.0 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-viewmodel:2.1.0 (*)
|    |    |    \--- androidx.savedstate:savedstate:1.0.0
|    |    |         +--- androidx.annotation:annotation:1.1.0
|    |    |         +--- androidx.arch.core:core-common:2.0.1 -> 2.1.0 (*)
|    |    |         \--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.2.0 (*)
|    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0 (*)
|    \--- androidx.annotation:annotation:1.1.0
+--- io.flutter:armeabi_v7a_release:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
+--- io.flutter:arm64_v8a_release:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
\--- io.flutter:x86_64_release:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8

compile - Compile dependencies for 'main' sources (deprecated: use 'implementation' instead).
No dependencies

compileOnly - Compile only dependencies for 'main' sources. (n)
No dependencies

coreLibraryDesugaring - Configuration to desugar libraries
No dependencies

debugAllApiPublication - All API publication for debug (n)
No dependencies

debugAllRuntimePublication - All runtime publication for debug (n)
No dependencies

debugAndroidTestAnnotationProcessorClasspath - Resolved configuration for annotation-processor for variant: debugAndroidTest
No dependencies

debugAndroidTestCompileClasspath - Resolved configuration for compilation for variant: debugAndroidTest
+--- io.flutter:flutter_embedding_debug:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
|    +--- androidx.lifecycle:lifecycle-common:2.2.0
|    |    \--- androidx.annotation:annotation:1.1.0
|    +--- androidx.lifecycle:lifecycle-common-java8:2.2.0
|    |    +--- androidx.lifecycle:lifecycle-common:2.2.0 (*)
|    |    \--- androidx.annotation:annotation:1.1.0
|    +--- androidx.lifecycle:lifecycle-runtime:2.2.0
|    |    +--- androidx.lifecycle:lifecycle-common:2.2.0 (*)
|    |    +--- androidx.arch.core:core-common:2.1.0
|    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    \--- androidx.annotation:annotation:1.1.0
|    +--- androidx.fragment:fragment:1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.lifecycle:lifecycle-runtime:2.0.0 -> 2.2.0 (*)
|    |    |    +--- androidx.versionedparcelable:versionedparcelable:1.1.0
|    |    |    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0
|    |    |    |         \--- androidx.annotation:annotation:1.1.0
|    |    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    |    +--- androidx.collection:collection:1.1.0 (*)
|    |    +--- androidx.viewpager:viewpager:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    +--- androidx.core:core:1.0.0 -> 1.1.0 (*)
|    |    |    \--- androidx.customview:customview:1.0.0
|    |    |         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |         \--- androidx.core:core:1.0.0 -> 1.1.0 (*)
|    |    +--- androidx.loader:loader:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    +--- androidx.core:core:1.0.0 -> 1.1.0 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-livedata:2.0.0
|    |    |    |    +--- androidx.arch.core:core-runtime:2.0.0
|    |    |    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    +--- androidx.lifecycle:lifecycle-livedata-core:2.0.0
|    |    |    |    |    +--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.2.0 (*)
|    |    |    |    |    +--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    |    \--- androidx.arch.core:core-runtime:2.0.0 (*)
|    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0
|    |    |         \--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.activity:activity:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.core:core:1.1.0 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-runtime:2.1.0 -> 2.2.0 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-viewmodel:2.1.0 (*)
|    |    |    \--- androidx.savedstate:savedstate:1.0.0
|    |    |         +--- androidx.annotation:annotation:1.1.0
|    |    |         +--- androidx.arch.core:core-common:2.0.1 -> 2.1.0 (*)
|    |    |         \--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.2.0 (*)
|    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0 (*)
|    \--- androidx.annotation:annotation:1.1.0
+--- io.flutter:armeabi_v7a_debug:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
+--- io.flutter:arm64_v8a_debug:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
+--- io.flutter:x86_64_debug:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
+--- io.flutter:x86_debug:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
+--- io.flutter:flutter_embedding_debug:{strictly 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8} -> 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8 (c)
+--- io.flutter:armeabi_v7a_debug:{strictly 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8} -> 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8 (c)
+--- io.flutter:arm64_v8a_debug:{strictly 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8} -> 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8 (c)
+--- io.flutter:x86_64_debug:{strictly 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8} -> 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8 (c)
+--- io.flutter:x86_debug:{strictly 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8} -> 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8 (c)
+--- androidx.lifecycle:lifecycle-common:{strictly 2.2.0} -> 2.2.0 (c)
+--- androidx.lifecycle:lifecycle-common-java8:{strictly 2.2.0} -> 2.2.0 (c)
+--- androidx.lifecycle:lifecycle-runtime:{strictly 2.2.0} -> 2.2.0 (c)
+--- androidx.fragment:fragment:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.annotation:annotation:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.arch.core:core-common:{strictly 2.1.0} -> 2.1.0 (c)
+--- androidx.core:core:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.collection:collection:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.viewpager:viewpager:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.loader:loader:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.activity:activity:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.lifecycle:lifecycle-viewmodel:{strictly 2.1.0} -> 2.1.0 (c)
+--- androidx.customview:customview:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.lifecycle:lifecycle-livedata:{strictly 2.0.0} -> 2.0.0 (c)
+--- androidx.savedstate:savedstate:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.versionedparcelable:versionedparcelable:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.arch.core:core-runtime:{strictly 2.0.0} -> 2.0.0 (c)
\--- androidx.lifecycle:lifecycle-livedata-core:{strictly 2.0.0} -> 2.0.0 (c)

debugAndroidTestRuntimeClasspath - Resolved configuration for runtime for variant: debugAndroidTest
+--- io.flutter:flutter_embedding_debug:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
|    +--- androidx.lifecycle:lifecycle-common:2.2.0
|    |    \--- androidx.annotation:annotation:1.1.0
|    +--- androidx.lifecycle:lifecycle-common-java8:2.2.0
|    |    +--- androidx.lifecycle:lifecycle-common:2.2.0 (*)
|    |    \--- androidx.annotation:annotation:1.1.0
|    +--- androidx.lifecycle:lifecycle-runtime:2.2.0
|    |    +--- androidx.lifecycle:lifecycle-common:2.2.0 (*)
|    |    +--- androidx.arch.core:core-common:2.1.0
|    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    \--- androidx.annotation:annotation:1.1.0
|    +--- androidx.fragment:fragment:1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.lifecycle:lifecycle-runtime:2.0.0 -> 2.2.0 (*)
|    |    |    +--- androidx.versionedparcelable:versionedparcelable:1.1.0
|    |    |    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0
|    |    |    |         \--- androidx.annotation:annotation:1.1.0
|    |    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    |    +--- androidx.collection:collection:1.1.0 (*)
|    |    +--- androidx.viewpager:viewpager:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    +--- androidx.core:core:1.0.0 -> 1.1.0 (*)
|    |    |    \--- androidx.customview:customview:1.0.0
|    |    |         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |         \--- androidx.core:core:1.0.0 -> 1.1.0 (*)
|    |    +--- androidx.loader:loader:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    +--- androidx.core:core:1.0.0 -> 1.1.0 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-livedata:2.0.0
|    |    |    |    +--- androidx.arch.core:core-runtime:2.0.0
|    |    |    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    +--- androidx.lifecycle:lifecycle-livedata-core:2.0.0
|    |    |    |    |    +--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.2.0 (*)
|    |    |    |    |    +--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    |    \--- androidx.arch.core:core-runtime:2.0.0 (*)
|    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0
|    |    |         \--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.activity:activity:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.core:core:1.1.0 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-runtime:2.1.0 -> 2.2.0 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-viewmodel:2.1.0 (*)
|    |    |    \--- androidx.savedstate:savedstate:1.0.0
|    |    |         +--- androidx.annotation:annotation:1.1.0
|    |    |         +--- androidx.arch.core:core-common:2.0.1 -> 2.1.0 (*)
|    |    |         \--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.2.0 (*)
|    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0 (*)
|    \--- androidx.annotation:annotation:1.1.0
+--- io.flutter:armeabi_v7a_debug:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
+--- io.flutter:arm64_v8a_debug:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
+--- io.flutter:x86_64_debug:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
+--- io.flutter:x86_debug:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
+--- io.flutter:flutter_embedding_debug:{strictly 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8} -> 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8 (c)
+--- io.flutter:armeabi_v7a_debug:{strictly 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8} -> 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8 (c)
+--- io.flutter:arm64_v8a_debug:{strictly 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8} -> 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8 (c)
+--- io.flutter:x86_64_debug:{strictly 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8} -> 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8 (c)
+--- io.flutter:x86_debug:{strictly 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8} -> 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8 (c)
+--- androidx.lifecycle:lifecycle-common:{strictly 2.2.0} -> 2.2.0 (c)
+--- androidx.lifecycle:lifecycle-common-java8:{strictly 2.2.0} -> 2.2.0 (c)
+--- androidx.lifecycle:lifecycle-runtime:{strictly 2.2.0} -> 2.2.0 (c)
+--- androidx.fragment:fragment:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.annotation:annotation:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.arch.core:core-common:{strictly 2.1.0} -> 2.1.0 (c)
+--- androidx.core:core:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.collection:collection:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.viewpager:viewpager:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.loader:loader:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.activity:activity:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.lifecycle:lifecycle-viewmodel:{strictly 2.1.0} -> 2.1.0 (c)
+--- androidx.customview:customview:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.lifecycle:lifecycle-livedata:{strictly 2.0.0} -> 2.0.0 (c)
+--- androidx.savedstate:savedstate:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.versionedparcelable:versionedparcelable:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.arch.core:core-runtime:{strictly 2.0.0} -> 2.0.0 (c)
\--- androidx.lifecycle:lifecycle-livedata-core:{strictly 2.0.0} -> 2.0.0 (c)

debugAnnotationProcessor - Classpath for the annotation processor for 'debug'. (n)
No dependencies

debugAnnotationProcessorClasspath - Resolved configuration for annotation-processor for variant: debug
No dependencies

debugApi - API dependencies for 'debug' sources. (n)
+--- io.flutter:flutter_embedding_debug:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8 (n)
+--- io.flutter:armeabi_v7a_debug:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8 (n)
+--- io.flutter:arm64_v8a_debug:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8 (n)
+--- io.flutter:x86_64_debug:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8 (n)
+--- io.flutter:x86_debug:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8 (n)
\--- unspecified (n)

debugApiElements - API elements for debug (n)
No dependencies

debugApiPublication - API publication for debug (n)
No dependencies

debugCompile - Compile dependencies for 'debug' sources (deprecated: use 'debugImplementation' instead). (n)
No dependencies

debugCompileClasspath - Resolved configuration for compilation for variant: debug
+--- io.flutter:flutter_embedding_debug:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
|    +--- androidx.lifecycle:lifecycle-common:2.2.0
|    |    \--- androidx.annotation:annotation:1.1.0
|    +--- androidx.lifecycle:lifecycle-common-java8:2.2.0
|    |    +--- androidx.lifecycle:lifecycle-common:2.2.0 (*)
|    |    \--- androidx.annotation:annotation:1.1.0
|    +--- androidx.lifecycle:lifecycle-runtime:2.2.0
|    |    +--- androidx.lifecycle:lifecycle-common:2.2.0 (*)
|    |    +--- androidx.arch.core:core-common:2.1.0
|    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    \--- androidx.annotation:annotation:1.1.0
|    +--- androidx.fragment:fragment:1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.lifecycle:lifecycle-runtime:2.0.0 -> 2.2.0 (*)
|    |    |    +--- androidx.versionedparcelable:versionedparcelable:1.1.0
|    |    |    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0
|    |    |    |         \--- androidx.annotation:annotation:1.1.0
|    |    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    |    +--- androidx.collection:collection:1.1.0 (*)
|    |    +--- androidx.viewpager:viewpager:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    +--- androidx.core:core:1.0.0 -> 1.1.0 (*)
|    |    |    \--- androidx.customview:customview:1.0.0
|    |    |         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |         \--- androidx.core:core:1.0.0 -> 1.1.0 (*)
|    |    +--- androidx.loader:loader:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    +--- androidx.core:core:1.0.0 -> 1.1.0 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-livedata:2.0.0
|    |    |    |    +--- androidx.arch.core:core-runtime:2.0.0
|    |    |    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    +--- androidx.lifecycle:lifecycle-livedata-core:2.0.0
|    |    |    |    |    +--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.2.0 (*)
|    |    |    |    |    +--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    |    \--- androidx.arch.core:core-runtime:2.0.0 (*)
|    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0
|    |    |         \--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.activity:activity:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.core:core:1.1.0 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-runtime:2.1.0 -> 2.2.0 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-viewmodel:2.1.0 (*)
|    |    |    \--- androidx.savedstate:savedstate:1.0.0
|    |    |         +--- androidx.annotation:annotation:1.1.0
|    |    |         +--- androidx.arch.core:core-common:2.0.1 -> 2.1.0 (*)
|    |    |         \--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.2.0 (*)
|    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0 (*)
|    \--- androidx.annotation:annotation:1.1.0
+--- io.flutter:armeabi_v7a_debug:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
+--- io.flutter:arm64_v8a_debug:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
+--- io.flutter:x86_64_debug:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
+--- io.flutter:x86_debug:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
+--- io.flutter:flutter_embedding_debug:{strictly 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8} -> 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8 (c)
+--- io.flutter:armeabi_v7a_debug:{strictly 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8} -> 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8 (c)
+--- io.flutter:arm64_v8a_debug:{strictly 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8} -> 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8 (c)
+--- io.flutter:x86_64_debug:{strictly 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8} -> 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8 (c)
+--- io.flutter:x86_debug:{strictly 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8} -> 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8 (c)
+--- androidx.lifecycle:lifecycle-common:{strictly 2.2.0} -> 2.2.0 (c)
+--- androidx.lifecycle:lifecycle-common-java8:{strictly 2.2.0} -> 2.2.0 (c)
+--- androidx.lifecycle:lifecycle-runtime:{strictly 2.2.0} -> 2.2.0 (c)
+--- androidx.fragment:fragment:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.annotation:annotation:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.arch.core:core-common:{strictly 2.1.0} -> 2.1.0 (c)
+--- androidx.core:core:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.collection:collection:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.viewpager:viewpager:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.loader:loader:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.activity:activity:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.lifecycle:lifecycle-viewmodel:{strictly 2.1.0} -> 2.1.0 (c)
+--- androidx.customview:customview:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.lifecycle:lifecycle-livedata:{strictly 2.0.0} -> 2.0.0 (c)
+--- androidx.savedstate:savedstate:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.versionedparcelable:versionedparcelable:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.arch.core:core-runtime:{strictly 2.0.0} -> 2.0.0 (c)
\--- androidx.lifecycle:lifecycle-livedata-core:{strictly 2.0.0} -> 2.0.0 (c)

debugCompileOnly - Compile only dependencies for 'debug' sources. (n)
No dependencies

debugImplementation - Implementation only dependencies for 'debug' sources. (n)
No dependencies

debugProvided - Provided dependencies for 'debug' sources (deprecated: use 'debugCompileOnly' instead). (n)
No dependencies

debugPublish - Publish dependencies for 'debug' sources (deprecated: use 'debugRuntimeOnly' instead). (n)
No dependencies

debugRuntimeClasspath - Resolved configuration for runtime for variant: debug
+--- io.flutter:flutter_embedding_debug:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
|    +--- androidx.lifecycle:lifecycle-common:2.2.0
|    |    \--- androidx.annotation:annotation:1.1.0
|    +--- androidx.lifecycle:lifecycle-common-java8:2.2.0
|    |    +--- androidx.lifecycle:lifecycle-common:2.2.0 (*)
|    |    \--- androidx.annotation:annotation:1.1.0
|    +--- androidx.lifecycle:lifecycle-runtime:2.2.0
|    |    +--- androidx.lifecycle:lifecycle-common:2.2.0 (*)
|    |    +--- androidx.arch.core:core-common:2.1.0
|    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    \--- androidx.annotation:annotation:1.1.0
|    +--- androidx.fragment:fragment:1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.lifecycle:lifecycle-runtime:2.0.0 -> 2.2.0 (*)
|    |    |    +--- androidx.versionedparcelable:versionedparcelable:1.1.0
|    |    |    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0
|    |    |    |         \--- androidx.annotation:annotation:1.1.0
|    |    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    |    +--- androidx.collection:collection:1.1.0 (*)
|    |    +--- androidx.viewpager:viewpager:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    +--- androidx.core:core:1.0.0 -> 1.1.0 (*)
|    |    |    \--- androidx.customview:customview:1.0.0
|    |    |         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |         \--- androidx.core:core:1.0.0 -> 1.1.0 (*)
|    |    +--- androidx.loader:loader:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    +--- androidx.core:core:1.0.0 -> 1.1.0 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-livedata:2.0.0
|    |    |    |    +--- androidx.arch.core:core-runtime:2.0.0
|    |    |    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    +--- androidx.lifecycle:lifecycle-livedata-core:2.0.0
|    |    |    |    |    +--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.2.0 (*)
|    |    |    |    |    +--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    |    \--- androidx.arch.core:core-runtime:2.0.0 (*)
|    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0
|    |    |         \--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.activity:activity:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.core:core:1.1.0 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-runtime:2.1.0 -> 2.2.0 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-viewmodel:2.1.0 (*)
|    |    |    \--- androidx.savedstate:savedstate:1.0.0
|    |    |         +--- androidx.annotation:annotation:1.1.0
|    |    |         +--- androidx.arch.core:core-common:2.0.1 -> 2.1.0 (*)
|    |    |         \--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.2.0 (*)
|    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0 (*)
|    \--- androidx.annotation:annotation:1.1.0
+--- io.flutter:armeabi_v7a_debug:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
+--- io.flutter:arm64_v8a_debug:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
+--- io.flutter:x86_64_debug:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
\--- io.flutter:x86_debug:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8

debugRuntimeElements - Runtime elements for debug (n)
No dependencies

debugRuntimeOnly - Runtime only dependencies for 'debug' sources. (n)
No dependencies

debugRuntimePublication - Runtime publication for debug (n)
No dependencies

debugUnitTestAnnotationProcessorClasspath - Resolved configuration for annotation-processor for variant: debugUnitTest
No dependencies

debugUnitTestCompileClasspath - Resolved configuration for compilation for variant: debugUnitTest
+--- io.flutter:flutter_embedding_debug:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
|    +--- androidx.lifecycle:lifecycle-common:2.2.0
|    |    \--- androidx.annotation:annotation:1.1.0
|    +--- androidx.lifecycle:lifecycle-common-java8:2.2.0
|    |    +--- androidx.lifecycle:lifecycle-common:2.2.0 (*)
|    |    \--- androidx.annotation:annotation:1.1.0
|    +--- androidx.lifecycle:lifecycle-runtime:2.2.0
|    |    +--- androidx.lifecycle:lifecycle-common:2.2.0 (*)
|    |    +--- androidx.arch.core:core-common:2.1.0
|    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    \--- androidx.annotation:annotation:1.1.0
|    +--- androidx.fragment:fragment:1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.lifecycle:lifecycle-runtime:2.0.0 -> 2.2.0 (*)
|    |    |    +--- androidx.versionedparcelable:versionedparcelable:1.1.0
|    |    |    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0
|    |    |    |         \--- androidx.annotation:annotation:1.1.0
|    |    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    |    +--- androidx.collection:collection:1.1.0 (*)
|    |    +--- androidx.viewpager:viewpager:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    +--- androidx.core:core:1.0.0 -> 1.1.0 (*)
|    |    |    \--- androidx.customview:customview:1.0.0
|    |    |         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |         \--- androidx.core:core:1.0.0 -> 1.1.0 (*)
|    |    +--- androidx.loader:loader:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    +--- androidx.core:core:1.0.0 -> 1.1.0 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-livedata:2.0.0
|    |    |    |    +--- androidx.arch.core:core-runtime:2.0.0
|    |    |    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    +--- androidx.lifecycle:lifecycle-livedata-core:2.0.0
|    |    |    |    |    +--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.2.0 (*)
|    |    |    |    |    +--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    |    \--- androidx.arch.core:core-runtime:2.0.0 (*)
|    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0
|    |    |         \--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.activity:activity:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.core:core:1.1.0 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-runtime:2.1.0 -> 2.2.0 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-viewmodel:2.1.0 (*)
|    |    |    \--- androidx.savedstate:savedstate:1.0.0
|    |    |         +--- androidx.annotation:annotation:1.1.0
|    |    |         +--- androidx.arch.core:core-common:2.0.1 -> 2.1.0 (*)
|    |    |         \--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.2.0 (*)
|    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0 (*)
|    \--- androidx.annotation:annotation:1.1.0
+--- io.flutter:armeabi_v7a_debug:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
+--- io.flutter:arm64_v8a_debug:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
+--- io.flutter:x86_64_debug:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
+--- io.flutter:x86_debug:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
+--- io.flutter:flutter_embedding_debug:{strictly 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8} -> 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8 (c)
+--- io.flutter:armeabi_v7a_debug:{strictly 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8} -> 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8 (c)
+--- io.flutter:arm64_v8a_debug:{strictly 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8} -> 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8 (c)
+--- io.flutter:x86_64_debug:{strictly 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8} -> 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8 (c)
+--- io.flutter:x86_debug:{strictly 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8} -> 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8 (c)
+--- androidx.lifecycle:lifecycle-common:{strictly 2.2.0} -> 2.2.0 (c)
+--- androidx.lifecycle:lifecycle-common-java8:{strictly 2.2.0} -> 2.2.0 (c)
+--- androidx.lifecycle:lifecycle-runtime:{strictly 2.2.0} -> 2.2.0 (c)
+--- androidx.fragment:fragment:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.annotation:annotation:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.arch.core:core-common:{strictly 2.1.0} -> 2.1.0 (c)
+--- androidx.core:core:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.collection:collection:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.viewpager:viewpager:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.loader:loader:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.activity:activity:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.lifecycle:lifecycle-viewmodel:{strictly 2.1.0} -> 2.1.0 (c)
+--- androidx.customview:customview:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.lifecycle:lifecycle-livedata:{strictly 2.0.0} -> 2.0.0 (c)
+--- androidx.savedstate:savedstate:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.versionedparcelable:versionedparcelable:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.arch.core:core-runtime:{strictly 2.0.0} -> 2.0.0 (c)
\--- androidx.lifecycle:lifecycle-livedata-core:{strictly 2.0.0} -> 2.0.0 (c)

debugUnitTestRuntimeClasspath - Resolved configuration for runtime for variant: debugUnitTest
+--- io.flutter:flutter_embedding_debug:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
|    +--- androidx.lifecycle:lifecycle-common:2.2.0
|    |    \--- androidx.annotation:annotation:1.1.0
|    +--- androidx.lifecycle:lifecycle-common-java8:2.2.0
|    |    +--- androidx.lifecycle:lifecycle-common:2.2.0 (*)
|    |    \--- androidx.annotation:annotation:1.1.0
|    +--- androidx.lifecycle:lifecycle-runtime:2.2.0
|    |    +--- androidx.lifecycle:lifecycle-common:2.2.0 (*)
|    |    +--- androidx.arch.core:core-common:2.1.0
|    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    \--- androidx.annotation:annotation:1.1.0
|    +--- androidx.fragment:fragment:1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.lifecycle:lifecycle-runtime:2.0.0 -> 2.2.0 (*)
|    |    |    +--- androidx.versionedparcelable:versionedparcelable:1.1.0
|    |    |    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0
|    |    |    |         \--- androidx.annotation:annotation:1.1.0
|    |    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    |    +--- androidx.collection:collection:1.1.0 (*)
|    |    +--- androidx.viewpager:viewpager:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    +--- androidx.core:core:1.0.0 -> 1.1.0 (*)
|    |    |    \--- androidx.customview:customview:1.0.0
|    |    |         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |         \--- androidx.core:core:1.0.0 -> 1.1.0 (*)
|    |    +--- androidx.loader:loader:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    +--- androidx.core:core:1.0.0 -> 1.1.0 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-livedata:2.0.0
|    |    |    |    +--- androidx.arch.core:core-runtime:2.0.0
|    |    |    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    +--- androidx.lifecycle:lifecycle-livedata-core:2.0.0
|    |    |    |    |    +--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.2.0 (*)
|    |    |    |    |    +--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    |    \--- androidx.arch.core:core-runtime:2.0.0 (*)
|    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0
|    |    |         \--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.activity:activity:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.core:core:1.1.0 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-runtime:2.1.0 -> 2.2.0 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-viewmodel:2.1.0 (*)
|    |    |    \--- androidx.savedstate:savedstate:1.0.0
|    |    |         +--- androidx.annotation:annotation:1.1.0
|    |    |         +--- androidx.arch.core:core-common:2.0.1 -> 2.1.0 (*)
|    |    |         \--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.2.0 (*)
|    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0 (*)
|    \--- androidx.annotation:annotation:1.1.0
+--- io.flutter:armeabi_v7a_debug:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
+--- io.flutter:arm64_v8a_debug:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
+--- io.flutter:x86_64_debug:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
\--- io.flutter:x86_debug:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8

debugWearApp - Link to a wear app to embed for object 'debug'. (n)
No dependencies

default - Configuration for default artifacts.
No dependencies

implementation - Implementation only dependencies for 'main' sources. (n)
No dependencies

lintChecks - Configuration to apply external lint check jar
No dependencies

lintClassPath - The lint embedded classpath
\--- com.android.tools.lint:lint-gradle:27.0.1
     +--- com.android.tools:sdk-common:27.0.1
     |    +--- com.android.tools:sdklib:27.0.1
     |    |    +--- com.android.tools.layoutlib:layoutlib-api:27.0.1
     |    |    |    +--- com.android.tools:common:27.0.1
     |    |    |    |    +--- com.android.tools:annotations:27.0.1
     |    |    |    |    +--- com.google.guava:guava:28.1-jre
     |    |    |    |    |    +--- com.google.guava:failureaccess:1.0.1
     |    |    |    |    |    +--- com.google.guava:listenablefuture:9999.0-empty-to-avoid-conflict-with-guava
     |    |    |    |    |    +--- com.google.code.findbugs:jsr305:3.0.2
     |    |    |    |    |    +--- org.checkerframework:checker-qual:2.8.1
     |    |    |    |    |    +--- com.google.errorprone:error_prone_annotations:2.3.2
     |    |    |    |    |    +--- com.google.j2objc:j2objc-annotations:1.3
     |    |    |    |    |    \--- org.codehaus.mojo:animal-sniffer-annotations:1.18
     |    |    |    |    \--- org.jetbrains.kotlin:kotlin-stdlib-jdk8:1.3.72
     |    |    |    |         +--- org.jetbrains.kotlin:kotlin-stdlib:1.3.72
     |    |    |    |         |    +--- org.jetbrains.kotlin:kotlin-stdlib-common:1.3.72
     |    |    |    |         |    \--- org.jetbrains:annotations:13.0
     |    |    |    |         \--- org.jetbrains.kotlin:kotlin-stdlib-jdk7:1.3.72
     |    |    |    |              \--- org.jetbrains.kotlin:kotlin-stdlib:1.3.72 (*)
     |    |    |    +--- net.sf.kxml:kxml2:2.3.0
     |    |    |    +--- com.android.tools:annotations:27.0.1
     |    |    |    \--- org.jetbrains:annotations:13.0
     |    |    +--- com.android.tools:dvlib:27.0.1
     |    |    |    \--- com.android.tools:common:27.0.1 (*)
     |    |    +--- com.android.tools:repository:27.0.1
     |    |    |    +--- com.android.tools:common:27.0.1 (*)
     |    |    |    +--- com.sun.activation:javax.activation:1.2.0
     |    |    |    +--- org.apache.commons:commons-compress:1.12
     |    |    |    +--- org.glassfish.jaxb:jaxb-runtime:2.3.1
     |    |    |    |    +--- javax.xml.bind:jaxb-api:2.3.1
     |    |    |    |    |    \--- javax.activation:javax.activation-api:1.2.0
     |    |    |    |    +--- org.glassfish.jaxb:txw2:2.3.1
     |    |    |    |    +--- com.sun.istack:istack-commons-runtime:3.0.7
     |    |    |    |    +--- org.jvnet.staxex:stax-ex:1.8
     |    |    |    |    +--- com.sun.xml.fastinfoset:FastInfoset:1.2.15
     |    |    |    |    \--- javax.activation:javax.activation-api:1.2.0
     |    |    |    +--- com.google.jimfs:jimfs:1.1
     |    |    |    |    \--- com.google.guava:guava:18.0 -> 28.1-jre (*)
     |    |    |    \--- org.jetbrains.kotlin:kotlin-stdlib-jdk8:1.3.72 (*)
     |    |    +--- com.google.code.gson:gson:2.8.5
     |    |    +--- org.apache.commons:commons-compress:1.12
     |    |    +--- org.apache.httpcomponents:httpmime:4.5.6
     |    |    |    \--- org.apache.httpcomponents:httpclient:4.5.6
     |    |    |         +--- org.apache.httpcomponents:httpcore:4.4.10
     |    |    |         +--- commons-logging:commons-logging:1.2
     |    |    |         \--- commons-codec:commons-codec:1.10
     |    |    \--- org.apache.httpcomponents:httpcore:4.4.10
     |    +--- com.android.tools.build:builder-test-api:4.0.1
     |    |    \--- com.android.tools.ddms:ddmlib:27.0.1
     |    |         +--- com.android.tools:common:27.0.1 (*)
     |    |         \--- net.sf.kxml:kxml2:2.3.0
     |    +--- com.android.tools.build:builder-model:4.0.1
     |    |    \--- com.android.tools:annotations:27.0.1
     |    +--- com.android.tools.ddms:ddmlib:27.0.1 (*)
     |    +--- com.android.tools.analytics-library:shared:27.0.1
     |    |    +--- com.android.tools.analytics-library:protos:27.0.1
     |    |    |    \--- com.google.protobuf:protobuf-java:3.10.0
     |    |    +--- com.android.tools:annotations:27.0.1
     |    |    +--- com.android.tools:common:27.0.1 (*)
     |    |    +--- com.google.guava:guava:28.1-jre (*)
     |    |    +--- com.google.code.gson:gson:2.8.5
     |    |    \--- org.jetbrains.kotlin:kotlin-stdlib-jdk8:1.3.72 (*)
     |    +--- org.bouncycastle:bcpkix-jdk15on:1.56
     |    |    \--- org.bouncycastle:bcprov-jdk15on:1.56
     |    +--- org.bouncycastle:bcprov-jdk15on:1.56
     |    +--- org.jetbrains.kotlin:kotlin-stdlib-jdk8:1.3.72 (*)
     |    +--- org.jetbrains.kotlin:kotlin-reflect:1.3.72
     |    |    \--- org.jetbrains.kotlin:kotlin-stdlib:1.3.72 (*)
     |    +--- com.google.protobuf:protobuf-java:3.10.0
     |    +--- javax.inject:javax.inject:1
     |    +--- org.jetbrains.trove4j:trove4j:20160824
     |    \--- com.android.tools.build:aapt2-proto:0.4.0
     |         \--- com.google.protobuf:protobuf-java:3.4.0 -> 3.10.0
     +--- com.android.tools.build:builder:4.0.1
     |    +--- com.android.tools.build:builder-model:4.0.1 (*)
     |    +--- com.android.tools.build:builder-test-api:4.0.1 (*)
     |    +--- com.android.tools:sdklib:27.0.1 (*)
     |    +--- com.android.tools:sdk-common:27.0.1 (*)
     |    +--- com.android.tools:common:27.0.1 (*)
     |    +--- com.android.tools.build:manifest-merger:27.0.1
     |    |    +--- com.android.tools:common:27.0.1 (*)
     |    |    +--- com.android.tools:sdklib:27.0.1 (*)
     |    |    +--- com.android.tools:sdk-common:27.0.1 (*)
     |    |    +--- com.google.code.gson:gson:2.8.5
     |    |    +--- org.jetbrains.kotlin:kotlin-stdlib-jdk8:1.3.72 (*)
     |    |    \--- net.sf.kxml:kxml2:2.3.0
     |    +--- com.android.tools.ddms:ddmlib:27.0.1 (*)
     |    +--- com.android:zipflinger:4.0.1
     |    |    +--- com.google.guava:guava:27.0.1-jre -> 28.1-jre (*)
     |    |    \--- com.android.tools:common:27.0.1 (*)
     |    +--- com.android:signflinger:4.0.1
     |    |    +--- com.android.tools.build:apksig:4.0.1
     |    |    \--- com.android:zipflinger:4.0.1 (*)
     |    +--- com.android.tools.analytics-library:protos:27.0.1 (*)
     |    +--- com.android.tools.analytics-library:tracker:27.0.1
     |    |    +--- com.android.tools:annotations:27.0.1
     |    |    +--- com.android.tools:common:27.0.1 (*)
     |    |    +--- com.android.tools.analytics-library:protos:27.0.1 (*)
     |    |    +--- com.android.tools.analytics-library:shared:27.0.1 (*)
     |    |    +--- com.google.protobuf:protobuf-java:3.10.0
     |    |    +--- com.google.guava:guava:28.1-jre (*)
     |    |    \--- org.jetbrains.kotlin:kotlin-stdlib-jdk8:1.3.72 (*)
     |    +--- com.android.tools.build:apksig:4.0.1
     |    +--- com.android.tools.build:apkzlib:4.0.1
     |    |    +--- com.google.code.findbugs:jsr305:1.3.9 -> 3.0.2
     |    |    +--- com.google.guava:guava:23.0 -> 28.1-jre (*)
     |    |    +--- org.bouncycastle:bcpkix-jdk15on:1.56 (*)
     |    |    +--- org.bouncycastle:bcprov-jdk15on:1.56
     |    |    \--- com.android.tools.build:apksig:4.0.1
     |    +--- org.jetbrains.kotlin:kotlin-stdlib-jdk8:1.3.72 (*)
     |    +--- com.squareup:javawriter:2.5.0
     |    +--- org.bouncycastle:bcpkix-jdk15on:1.56 (*)
     |    +--- org.bouncycastle:bcprov-jdk15on:1.56
     |    +--- org.ow2.asm:asm:7.0
     |    +--- org.ow2.asm:asm-tree:7.0
     |    |    \--- org.ow2.asm:asm:7.0
     |    +--- javax.inject:javax.inject:1
     |    +--- org.ow2.asm:asm-commons:7.0
     |    |    +--- org.ow2.asm:asm:7.0
     |    |    +--- org.ow2.asm:asm-tree:7.0 (*)
     |    |    \--- org.ow2.asm:asm-analysis:7.0
     |    |         \--- org.ow2.asm:asm-tree:7.0 (*)
     |    +--- org.ow2.asm:asm-util:7.0
     |    |    +--- org.ow2.asm:asm:7.0
     |    |    +--- org.ow2.asm:asm-tree:7.0 (*)
     |    |    \--- org.ow2.asm:asm-analysis:7.0 (*)
     |    +--- it.unimi.dsi:fastutil:7.2.0
     |    +--- net.sf.jopt-simple:jopt-simple:4.9
     |    \--- com.googlecode.json-simple:json-simple:1.1
     +--- com.android.tools.build:builder-model:4.0.1 (*)
     +--- com.android.tools.external.com-intellij:intellij-core:27.0.1
     |    \--- org.jetbrains.trove4j:trove4j:20160824
     +--- com.android.tools.external.com-intellij:kotlin-compiler:27.0.1
     +--- com.android.tools.external.org-jetbrains:uast:27.0.1
     +--- com.android.tools.build:manifest-merger:27.0.1 (*)
     +--- com.android.tools.lint:lint:27.0.1
     |    +--- com.android.tools.lint:lint-checks:27.0.1
     |    |    +--- com.android.tools.lint:lint-api:27.0.1
     |    |    |    +--- com.android.tools:sdk-common:27.0.1 (*)
     |    |    |    +--- com.android.tools.build:builder-model:4.0.1 (*)
     |    |    |    +--- com.google.guava:guava:28.1-jre (*)
     |    |    |    +--- com.android.tools.external.com-intellij:intellij-core:27.0.1 (*)
     |    |    |    +--- com.android.tools.external.com-intellij:kotlin-compiler:27.0.1
     |    |    |    +--- com.android.tools.external.org-jetbrains:uast:27.0.1
     |    |    |    +--- com.android.tools.build:manifest-merger:27.0.1 (*)
     |    |    |    +--- org.ow2.asm:asm:7.0
     |    |    |    +--- org.ow2.asm:asm-tree:7.0 (*)
     |    |    |    +--- org.jetbrains.kotlin:kotlin-reflect:1.3.72 (*)
     |    |    |    \--- org.jetbrains.kotlin:kotlin-stdlib-jdk8:1.3.72 (*)
     |    |    +--- com.google.guava:guava:28.1-jre (*)
     |    |    +--- com.android.tools.external.com-intellij:intellij-core:27.0.1 (*)
     |    |    +--- com.android.tools.external.com-intellij:kotlin-compiler:27.0.1
     |    |    +--- com.android.tools.external.org-jetbrains:uast:27.0.1
     |    |    \--- org.ow2.asm:asm-analysis:7.0 (*)
     |    +--- com.google.guava:guava:28.1-jre (*)
     |    +--- com.android.tools.external.org-jetbrains:uast:27.0.1
     |    +--- com.android.tools.external.com-intellij:kotlin-compiler:27.0.1
     |    +--- com.android.tools.build:manifest-merger:27.0.1 (*)
     |    +--- com.android.tools.analytics-library:shared:27.0.1 (*)
     |    +--- com.android.tools.analytics-library:protos:27.0.1 (*)
     |    +--- com.android.tools.analytics-library:tracker:27.0.1 (*)
     |    +--- org.jetbrains.kotlin:kotlin-reflect:1.3.72 (*)
     |    \--- org.jetbrains.kotlin:kotlin-stdlib-jdk8:1.3.72 (*)
     +--- com.android.tools.lint:lint-gradle-api:27.0.1
     |    +--- com.android.tools:sdklib:27.0.1 (*)
     |    +--- com.android.tools.build:builder-model:4.0.1 (*)
     |    +--- com.android.tools.build:gradle-api:4.0.1
     |    |    +--- com.android.tools.build:builder-test-api:4.0.1 (*)
     |    |    +--- com.google.guava:guava:28.1-jre (*)
     |    |    \--- org.jetbrains.kotlin:kotlin-stdlib-jdk8:1.3.72 (*)
     |    +--- org.jetbrains.kotlin:kotlin-reflect:1.3.72 (*)
     |    +--- org.jetbrains.kotlin:kotlin-stdlib-jdk8:1.3.72 (*)
     |    \--- com.google.guava:guava:28.1-jre (*)
     +--- com.android:zipflinger:4.0.1 (*)
     +--- org.codehaus.groovy:groovy-all:2.4.15
     +--- org.jetbrains.kotlin:kotlin-reflect:1.3.72 (*)
     \--- org.jetbrains.kotlin:kotlin-stdlib-jdk8:1.3.72 (*)

lintPublish - Configuration to publish external lint check jar
No dependencies

profileAllApiPublication - All API publication for profile (n)
No dependencies

profileAllRuntimePublication - All runtime publication for profile (n)
No dependencies

profileAnnotationProcessor - Classpath for the annotation processor for 'profile'. (n)
No dependencies

profileAnnotationProcessorClasspath - Resolved configuration for annotation-processor for variant: profile
No dependencies

profileApi - API dependencies for 'profile' sources. (n)
+--- io.flutter:flutter_embedding_profile:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8 (n)
+--- io.flutter:armeabi_v7a_profile:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8 (n)
+--- io.flutter:arm64_v8a_profile:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8 (n)
\--- io.flutter:x86_64_profile:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8 (n)

profileApiElements - API elements for profile (n)
No dependencies

profileApiPublication - API publication for profile (n)
No dependencies

profileCompile - Compile dependencies for 'profile' sources (deprecated: use 'profileImplementation' instead). (n)
No dependencies

profileCompileClasspath - Resolved configuration for compilation for variant: profile
+--- io.flutter:flutter_embedding_profile:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
|    +--- androidx.lifecycle:lifecycle-common:2.2.0
|    |    \--- androidx.annotation:annotation:1.1.0
|    +--- androidx.lifecycle:lifecycle-common-java8:2.2.0
|    |    +--- androidx.lifecycle:lifecycle-common:2.2.0 (*)
|    |    \--- androidx.annotation:annotation:1.1.0
|    +--- androidx.lifecycle:lifecycle-runtime:2.2.0
|    |    +--- androidx.lifecycle:lifecycle-common:2.2.0 (*)
|    |    +--- androidx.arch.core:core-common:2.1.0
|    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    \--- androidx.annotation:annotation:1.1.0
|    +--- androidx.fragment:fragment:1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.lifecycle:lifecycle-runtime:2.0.0 -> 2.2.0 (*)
|    |    |    +--- androidx.versionedparcelable:versionedparcelable:1.1.0
|    |    |    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0
|    |    |    |         \--- androidx.annotation:annotation:1.1.0
|    |    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    |    +--- androidx.collection:collection:1.1.0 (*)
|    |    +--- androidx.viewpager:viewpager:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    +--- androidx.core:core:1.0.0 -> 1.1.0 (*)
|    |    |    \--- androidx.customview:customview:1.0.0
|    |    |         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |         \--- androidx.core:core:1.0.0 -> 1.1.0 (*)
|    |    +--- androidx.loader:loader:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    +--- androidx.core:core:1.0.0 -> 1.1.0 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-livedata:2.0.0
|    |    |    |    +--- androidx.arch.core:core-runtime:2.0.0
|    |    |    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    +--- androidx.lifecycle:lifecycle-livedata-core:2.0.0
|    |    |    |    |    +--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.2.0 (*)
|    |    |    |    |    +--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    |    \--- androidx.arch.core:core-runtime:2.0.0 (*)
|    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0
|    |    |         \--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.activity:activity:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.core:core:1.1.0 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-runtime:2.1.0 -> 2.2.0 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-viewmodel:2.1.0 (*)
|    |    |    \--- androidx.savedstate:savedstate:1.0.0
|    |    |         +--- androidx.annotation:annotation:1.1.0
|    |    |         +--- androidx.arch.core:core-common:2.0.1 -> 2.1.0 (*)
|    |    |         \--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.2.0 (*)
|    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0 (*)
|    \--- androidx.annotation:annotation:1.1.0
+--- io.flutter:armeabi_v7a_profile:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
+--- io.flutter:arm64_v8a_profile:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
+--- io.flutter:x86_64_profile:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
+--- io.flutter:flutter_embedding_profile:{strictly 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8} -> 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8 (c)
+--- io.flutter:armeabi_v7a_profile:{strictly 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8} -> 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8 (c)
+--- io.flutter:arm64_v8a_profile:{strictly 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8} -> 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8 (c)
+--- io.flutter:x86_64_profile:{strictly 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8} -> 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8 (c)
+--- androidx.lifecycle:lifecycle-common:{strictly 2.2.0} -> 2.2.0 (c)
+--- androidx.lifecycle:lifecycle-common-java8:{strictly 2.2.0} -> 2.2.0 (c)
+--- androidx.lifecycle:lifecycle-runtime:{strictly 2.2.0} -> 2.2.0 (c)
+--- androidx.fragment:fragment:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.annotation:annotation:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.arch.core:core-common:{strictly 2.1.0} -> 2.1.0 (c)
+--- androidx.core:core:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.collection:collection:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.viewpager:viewpager:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.loader:loader:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.activity:activity:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.lifecycle:lifecycle-viewmodel:{strictly 2.1.0} -> 2.1.0 (c)
+--- androidx.customview:customview:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.lifecycle:lifecycle-livedata:{strictly 2.0.0} -> 2.0.0 (c)
+--- androidx.savedstate:savedstate:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.versionedparcelable:versionedparcelable:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.arch.core:core-runtime:{strictly 2.0.0} -> 2.0.0 (c)
\--- androidx.lifecycle:lifecycle-livedata-core:{strictly 2.0.0} -> 2.0.0 (c)

profileCompileOnly - Compile only dependencies for 'profile' sources. (n)
No dependencies

profileImplementation - Implementation only dependencies for 'profile' sources. (n)
No dependencies

profileProvided - Provided dependencies for 'profile' sources (deprecated: use 'profileCompileOnly' instead). (n)
No dependencies

profilePublish - Publish dependencies for 'profile' sources (deprecated: use 'profileRuntimeOnly' instead). (n)
No dependencies

profileRuntimeClasspath - Resolved configuration for runtime for variant: profile
+--- io.flutter:flutter_embedding_profile:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
|    +--- androidx.lifecycle:lifecycle-common:2.2.0
|    |    \--- androidx.annotation:annotation:1.1.0
|    +--- androidx.lifecycle:lifecycle-common-java8:2.2.0
|    |    +--- androidx.lifecycle:lifecycle-common:2.2.0 (*)
|    |    \--- androidx.annotation:annotation:1.1.0
|    +--- androidx.lifecycle:lifecycle-runtime:2.2.0
|    |    +--- androidx.lifecycle:lifecycle-common:2.2.0 (*)
|    |    +--- androidx.arch.core:core-common:2.1.0
|    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    \--- androidx.annotation:annotation:1.1.0
|    +--- androidx.fragment:fragment:1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.lifecycle:lifecycle-runtime:2.0.0 -> 2.2.0 (*)
|    |    |    +--- androidx.versionedparcelable:versionedparcelable:1.1.0
|    |    |    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0
|    |    |    |         \--- androidx.annotation:annotation:1.1.0
|    |    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    |    +--- androidx.collection:collection:1.1.0 (*)
|    |    +--- androidx.viewpager:viewpager:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    +--- androidx.core:core:1.0.0 -> 1.1.0 (*)
|    |    |    \--- androidx.customview:customview:1.0.0
|    |    |         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |         \--- androidx.core:core:1.0.0 -> 1.1.0 (*)
|    |    +--- androidx.loader:loader:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    +--- androidx.core:core:1.0.0 -> 1.1.0 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-livedata:2.0.0
|    |    |    |    +--- androidx.arch.core:core-runtime:2.0.0
|    |    |    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    +--- androidx.lifecycle:lifecycle-livedata-core:2.0.0
|    |    |    |    |    +--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.2.0 (*)
|    |    |    |    |    +--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    |    \--- androidx.arch.core:core-runtime:2.0.0 (*)
|    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0
|    |    |         \--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.activity:activity:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.core:core:1.1.0 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-runtime:2.1.0 -> 2.2.0 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-viewmodel:2.1.0 (*)
|    |    |    \--- androidx.savedstate:savedstate:1.0.0
|    |    |         +--- androidx.annotation:annotation:1.1.0
|    |    |         +--- androidx.arch.core:core-common:2.0.1 -> 2.1.0 (*)
|    |    |         \--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.2.0 (*)
|    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0 (*)
|    \--- androidx.annotation:annotation:1.1.0
+--- io.flutter:armeabi_v7a_profile:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
+--- io.flutter:arm64_v8a_profile:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
\--- io.flutter:x86_64_profile:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8

profileRuntimeElements - Runtime elements for profile (n)
No dependencies

profileRuntimeOnly - Runtime only dependencies for 'profile' sources. (n)
No dependencies

profileRuntimePublication - Runtime publication for profile (n)
No dependencies

profileUnitTestAnnotationProcessorClasspath - Resolved configuration for annotation-processor for variant: profileUnitTest
No dependencies

profileUnitTestCompileClasspath - Resolved configuration for compilation for variant: profileUnitTest
+--- io.flutter:flutter_embedding_profile:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
|    +--- androidx.lifecycle:lifecycle-common:2.2.0
|    |    \--- androidx.annotation:annotation:1.1.0
|    +--- androidx.lifecycle:lifecycle-common-java8:2.2.0
|    |    +--- androidx.lifecycle:lifecycle-common:2.2.0 (*)
|    |    \--- androidx.annotation:annotation:1.1.0
|    +--- androidx.lifecycle:lifecycle-runtime:2.2.0
|    |    +--- androidx.lifecycle:lifecycle-common:2.2.0 (*)
|    |    +--- androidx.arch.core:core-common:2.1.0
|    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    \--- androidx.annotation:annotation:1.1.0
|    +--- androidx.fragment:fragment:1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.lifecycle:lifecycle-runtime:2.0.0 -> 2.2.0 (*)
|    |    |    +--- androidx.versionedparcelable:versionedparcelable:1.1.0
|    |    |    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0
|    |    |    |         \--- androidx.annotation:annotation:1.1.0
|    |    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    |    +--- androidx.collection:collection:1.1.0 (*)
|    |    +--- androidx.viewpager:viewpager:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    +--- androidx.core:core:1.0.0 -> 1.1.0 (*)
|    |    |    \--- androidx.customview:customview:1.0.0
|    |    |         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |         \--- androidx.core:core:1.0.0 -> 1.1.0 (*)
|    |    +--- androidx.loader:loader:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    +--- androidx.core:core:1.0.0 -> 1.1.0 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-livedata:2.0.0
|    |    |    |    +--- androidx.arch.core:core-runtime:2.0.0
|    |    |    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    +--- androidx.lifecycle:lifecycle-livedata-core:2.0.0
|    |    |    |    |    +--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.2.0 (*)
|    |    |    |    |    +--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    |    \--- androidx.arch.core:core-runtime:2.0.0 (*)
|    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0
|    |    |         \--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.activity:activity:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.core:core:1.1.0 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-runtime:2.1.0 -> 2.2.0 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-viewmodel:2.1.0 (*)
|    |    |    \--- androidx.savedstate:savedstate:1.0.0
|    |    |         +--- androidx.annotation:annotation:1.1.0
|    |    |         +--- androidx.arch.core:core-common:2.0.1 -> 2.1.0 (*)
|    |    |         \--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.2.0 (*)
|    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0 (*)
|    \--- androidx.annotation:annotation:1.1.0
+--- io.flutter:armeabi_v7a_profile:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
+--- io.flutter:arm64_v8a_profile:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
+--- io.flutter:x86_64_profile:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
+--- io.flutter:flutter_embedding_profile:{strictly 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8} -> 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8 (c)
+--- io.flutter:armeabi_v7a_profile:{strictly 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8} -> 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8 (c)
+--- io.flutter:arm64_v8a_profile:{strictly 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8} -> 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8 (c)
+--- io.flutter:x86_64_profile:{strictly 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8} -> 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8 (c)
+--- androidx.lifecycle:lifecycle-common:{strictly 2.2.0} -> 2.2.0 (c)
+--- androidx.lifecycle:lifecycle-common-java8:{strictly 2.2.0} -> 2.2.0 (c)
+--- androidx.lifecycle:lifecycle-runtime:{strictly 2.2.0} -> 2.2.0 (c)
+--- androidx.fragment:fragment:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.annotation:annotation:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.arch.core:core-common:{strictly 2.1.0} -> 2.1.0 (c)
+--- androidx.core:core:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.collection:collection:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.viewpager:viewpager:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.loader:loader:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.activity:activity:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.lifecycle:lifecycle-viewmodel:{strictly 2.1.0} -> 2.1.0 (c)
+--- androidx.customview:customview:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.lifecycle:lifecycle-livedata:{strictly 2.0.0} -> 2.0.0 (c)
+--- androidx.savedstate:savedstate:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.versionedparcelable:versionedparcelable:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.arch.core:core-runtime:{strictly 2.0.0} -> 2.0.0 (c)
\--- androidx.lifecycle:lifecycle-livedata-core:{strictly 2.0.0} -> 2.0.0 (c)

profileUnitTestRuntimeClasspath - Resolved configuration for runtime for variant: profileUnitTest
+--- io.flutter:flutter_embedding_profile:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
|    +--- androidx.lifecycle:lifecycle-common:2.2.0
|    |    \--- androidx.annotation:annotation:1.1.0
|    +--- androidx.lifecycle:lifecycle-common-java8:2.2.0
|    |    +--- androidx.lifecycle:lifecycle-common:2.2.0 (*)
|    |    \--- androidx.annotation:annotation:1.1.0
|    +--- androidx.lifecycle:lifecycle-runtime:2.2.0
|    |    +--- androidx.lifecycle:lifecycle-common:2.2.0 (*)
|    |    +--- androidx.arch.core:core-common:2.1.0
|    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    \--- androidx.annotation:annotation:1.1.0
|    +--- androidx.fragment:fragment:1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.lifecycle:lifecycle-runtime:2.0.0 -> 2.2.0 (*)
|    |    |    +--- androidx.versionedparcelable:versionedparcelable:1.1.0
|    |    |    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0
|    |    |    |         \--- androidx.annotation:annotation:1.1.0
|    |    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    |    +--- androidx.collection:collection:1.1.0 (*)
|    |    +--- androidx.viewpager:viewpager:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    +--- androidx.core:core:1.0.0 -> 1.1.0 (*)
|    |    |    \--- androidx.customview:customview:1.0.0
|    |    |         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |         \--- androidx.core:core:1.0.0 -> 1.1.0 (*)
|    |    +--- androidx.loader:loader:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    +--- androidx.core:core:1.0.0 -> 1.1.0 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-livedata:2.0.0
|    |    |    |    +--- androidx.arch.core:core-runtime:2.0.0
|    |    |    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    +--- androidx.lifecycle:lifecycle-livedata-core:2.0.0
|    |    |    |    |    +--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.2.0 (*)
|    |    |    |    |    +--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    |    \--- androidx.arch.core:core-runtime:2.0.0 (*)
|    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0
|    |    |         \--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.activity:activity:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.core:core:1.1.0 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-runtime:2.1.0 -> 2.2.0 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-viewmodel:2.1.0 (*)
|    |    |    \--- androidx.savedstate:savedstate:1.0.0
|    |    |         +--- androidx.annotation:annotation:1.1.0
|    |    |         +--- androidx.arch.core:core-common:2.0.1 -> 2.1.0 (*)
|    |    |         \--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.2.0 (*)
|    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0 (*)
|    \--- androidx.annotation:annotation:1.1.0
+--- io.flutter:armeabi_v7a_profile:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
+--- io.flutter:arm64_v8a_profile:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
\--- io.flutter:x86_64_profile:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8

profileWearApp - Link to a wear app to embed for object 'profile'. (n)
No dependencies

provided - Provided dependencies for 'main' sources (deprecated: use 'compileOnly' instead). (n)
No dependencies

publish - Publish dependencies for 'main' sources (deprecated: use 'runtimeOnly' instead). (n)
No dependencies

releaseAllApiPublication - All API publication for release (n)
No dependencies

releaseAllRuntimePublication - All runtime publication for release (n)
No dependencies

releaseAnnotationProcessor - Classpath for the annotation processor for 'release'. (n)
No dependencies

releaseAnnotationProcessorClasspath - Resolved configuration for annotation-processor for variant: release
No dependencies

releaseApi - API dependencies for 'release' sources. (n)
+--- io.flutter:flutter_embedding_release:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8 (n)
+--- io.flutter:armeabi_v7a_release:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8 (n)
+--- io.flutter:arm64_v8a_release:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8 (n)
+--- io.flutter:x86_64_release:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8 (n)
\--- unspecified (n)

releaseApiElements - API elements for release (n)
No dependencies

releaseApiPublication - API publication for release (n)
No dependencies

releaseCompile - Compile dependencies for 'release' sources (deprecated: use 'releaseImplementation' instead). (n)
No dependencies

releaseCompileClasspath - Resolved configuration for compilation for variant: release
+--- io.flutter:flutter_embedding_release:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
|    +--- androidx.lifecycle:lifecycle-common:2.2.0
|    |    \--- androidx.annotation:annotation:1.1.0
|    +--- androidx.lifecycle:lifecycle-common-java8:2.2.0
|    |    +--- androidx.lifecycle:lifecycle-common:2.2.0 (*)
|    |    \--- androidx.annotation:annotation:1.1.0
|    +--- androidx.lifecycle:lifecycle-runtime:2.2.0
|    |    +--- androidx.lifecycle:lifecycle-common:2.2.0 (*)
|    |    +--- androidx.arch.core:core-common:2.1.0
|    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    \--- androidx.annotation:annotation:1.1.0
|    +--- androidx.fragment:fragment:1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.lifecycle:lifecycle-runtime:2.0.0 -> 2.2.0 (*)
|    |    |    +--- androidx.versionedparcelable:versionedparcelable:1.1.0
|    |    |    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0
|    |    |    |         \--- androidx.annotation:annotation:1.1.0
|    |    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    |    +--- androidx.collection:collection:1.1.0 (*)
|    |    +--- androidx.viewpager:viewpager:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    +--- androidx.core:core:1.0.0 -> 1.1.0 (*)
|    |    |    \--- androidx.customview:customview:1.0.0
|    |    |         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |         \--- androidx.core:core:1.0.0 -> 1.1.0 (*)
|    |    +--- androidx.loader:loader:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    +--- androidx.core:core:1.0.0 -> 1.1.0 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-livedata:2.0.0
|    |    |    |    +--- androidx.arch.core:core-runtime:2.0.0
|    |    |    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    +--- androidx.lifecycle:lifecycle-livedata-core:2.0.0
|    |    |    |    |    +--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.2.0 (*)
|    |    |    |    |    +--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    |    \--- androidx.arch.core:core-runtime:2.0.0 (*)
|    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0
|    |    |         \--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.activity:activity:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.core:core:1.1.0 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-runtime:2.1.0 -> 2.2.0 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-viewmodel:2.1.0 (*)
|    |    |    \--- androidx.savedstate:savedstate:1.0.0
|    |    |         +--- androidx.annotation:annotation:1.1.0
|    |    |         +--- androidx.arch.core:core-common:2.0.1 -> 2.1.0 (*)
|    |    |         \--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.2.0 (*)
|    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0 (*)
|    \--- androidx.annotation:annotation:1.1.0
+--- io.flutter:armeabi_v7a_release:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
+--- io.flutter:arm64_v8a_release:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
+--- io.flutter:x86_64_release:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
+--- io.flutter:flutter_embedding_release:{strictly 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8} -> 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8 (c)
+--- io.flutter:armeabi_v7a_release:{strictly 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8} -> 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8 (c)
+--- io.flutter:arm64_v8a_release:{strictly 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8} -> 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8 (c)
+--- io.flutter:x86_64_release:{strictly 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8} -> 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8 (c)
+--- androidx.lifecycle:lifecycle-common:{strictly 2.2.0} -> 2.2.0 (c)
+--- androidx.lifecycle:lifecycle-common-java8:{strictly 2.2.0} -> 2.2.0 (c)
+--- androidx.lifecycle:lifecycle-runtime:{strictly 2.2.0} -> 2.2.0 (c)
+--- androidx.fragment:fragment:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.annotation:annotation:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.arch.core:core-common:{strictly 2.1.0} -> 2.1.0 (c)
+--- androidx.core:core:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.collection:collection:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.viewpager:viewpager:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.loader:loader:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.activity:activity:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.lifecycle:lifecycle-viewmodel:{strictly 2.1.0} -> 2.1.0 (c)
+--- androidx.customview:customview:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.lifecycle:lifecycle-livedata:{strictly 2.0.0} -> 2.0.0 (c)
+--- androidx.savedstate:savedstate:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.versionedparcelable:versionedparcelable:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.arch.core:core-runtime:{strictly 2.0.0} -> 2.0.0 (c)
\--- androidx.lifecycle:lifecycle-livedata-core:{strictly 2.0.0} -> 2.0.0 (c)

releaseCompileOnly - Compile only dependencies for 'release' sources. (n)
No dependencies

releaseImplementation - Implementation only dependencies for 'release' sources. (n)
No dependencies

releaseProvided - Provided dependencies for 'release' sources (deprecated: use 'releaseCompileOnly' instead). (n)
No dependencies

releasePublish - Publish dependencies for 'release' sources (deprecated: use 'releaseRuntimeOnly' instead). (n)
No dependencies

releaseRuntimeClasspath - Resolved configuration for runtime for variant: release
+--- io.flutter:flutter_embedding_release:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
|    +--- androidx.lifecycle:lifecycle-common:2.2.0
|    |    \--- androidx.annotation:annotation:1.1.0
|    +--- androidx.lifecycle:lifecycle-common-java8:2.2.0
|    |    +--- androidx.lifecycle:lifecycle-common:2.2.0 (*)
|    |    \--- androidx.annotation:annotation:1.1.0
|    +--- androidx.lifecycle:lifecycle-runtime:2.2.0
|    |    +--- androidx.lifecycle:lifecycle-common:2.2.0 (*)
|    |    +--- androidx.arch.core:core-common:2.1.0
|    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    \--- androidx.annotation:annotation:1.1.0
|    +--- androidx.fragment:fragment:1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.lifecycle:lifecycle-runtime:2.0.0 -> 2.2.0 (*)
|    |    |    +--- androidx.versionedparcelable:versionedparcelable:1.1.0
|    |    |    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0
|    |    |    |         \--- androidx.annotation:annotation:1.1.0
|    |    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    |    +--- androidx.collection:collection:1.1.0 (*)
|    |    +--- androidx.viewpager:viewpager:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    +--- androidx.core:core:1.0.0 -> 1.1.0 (*)
|    |    |    \--- androidx.customview:customview:1.0.0
|    |    |         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |         \--- androidx.core:core:1.0.0 -> 1.1.0 (*)
|    |    +--- androidx.loader:loader:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    +--- androidx.core:core:1.0.0 -> 1.1.0 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-livedata:2.0.0
|    |    |    |    +--- androidx.arch.core:core-runtime:2.0.0
|    |    |    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    +--- androidx.lifecycle:lifecycle-livedata-core:2.0.0
|    |    |    |    |    +--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.2.0 (*)
|    |    |    |    |    +--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    |    \--- androidx.arch.core:core-runtime:2.0.0 (*)
|    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0
|    |    |         \--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.activity:activity:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.core:core:1.1.0 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-runtime:2.1.0 -> 2.2.0 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-viewmodel:2.1.0 (*)
|    |    |    \--- androidx.savedstate:savedstate:1.0.0
|    |    |         +--- androidx.annotation:annotation:1.1.0
|    |    |         +--- androidx.arch.core:core-common:2.0.1 -> 2.1.0 (*)
|    |    |         \--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.2.0 (*)
|    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0 (*)
|    \--- androidx.annotation:annotation:1.1.0
+--- io.flutter:armeabi_v7a_release:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
+--- io.flutter:arm64_v8a_release:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
\--- io.flutter:x86_64_release:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8

releaseRuntimeElements - Runtime elements for release (n)
No dependencies

releaseRuntimeOnly - Runtime only dependencies for 'release' sources. (n)
No dependencies

releaseRuntimePublication - Runtime publication for release (n)
No dependencies

releaseUnitTestAnnotationProcessorClasspath - Resolved configuration for annotation-processor for variant: releaseUnitTest
No dependencies

releaseUnitTestCompileClasspath - Resolved configuration for compilation for variant: releaseUnitTest
+--- io.flutter:flutter_embedding_release:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
|    +--- androidx.lifecycle:lifecycle-common:2.2.0
|    |    \--- androidx.annotation:annotation:1.1.0
|    +--- androidx.lifecycle:lifecycle-common-java8:2.2.0
|    |    +--- androidx.lifecycle:lifecycle-common:2.2.0 (*)
|    |    \--- androidx.annotation:annotation:1.1.0
|    +--- androidx.lifecycle:lifecycle-runtime:2.2.0
|    |    +--- androidx.lifecycle:lifecycle-common:2.2.0 (*)
|    |    +--- androidx.arch.core:core-common:2.1.0
|    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    \--- androidx.annotation:annotation:1.1.0
|    +--- androidx.fragment:fragment:1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.lifecycle:lifecycle-runtime:2.0.0 -> 2.2.0 (*)
|    |    |    +--- androidx.versionedparcelable:versionedparcelable:1.1.0
|    |    |    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0
|    |    |    |         \--- androidx.annotation:annotation:1.1.0
|    |    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    |    +--- androidx.collection:collection:1.1.0 (*)
|    |    +--- androidx.viewpager:viewpager:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    +--- androidx.core:core:1.0.0 -> 1.1.0 (*)
|    |    |    \--- androidx.customview:customview:1.0.0
|    |    |         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |         \--- androidx.core:core:1.0.0 -> 1.1.0 (*)
|    |    +--- androidx.loader:loader:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    +--- androidx.core:core:1.0.0 -> 1.1.0 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-livedata:2.0.0
|    |    |    |    +--- androidx.arch.core:core-runtime:2.0.0
|    |    |    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    +--- androidx.lifecycle:lifecycle-livedata-core:2.0.0
|    |    |    |    |    +--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.2.0 (*)
|    |    |    |    |    +--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    |    \--- androidx.arch.core:core-runtime:2.0.0 (*)
|    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0
|    |    |         \--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.activity:activity:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.core:core:1.1.0 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-runtime:2.1.0 -> 2.2.0 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-viewmodel:2.1.0 (*)
|    |    |    \--- androidx.savedstate:savedstate:1.0.0
|    |    |         +--- androidx.annotation:annotation:1.1.0
|    |    |         +--- androidx.arch.core:core-common:2.0.1 -> 2.1.0 (*)
|    |    |         \--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.2.0 (*)
|    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0 (*)
|    \--- androidx.annotation:annotation:1.1.0
+--- io.flutter:armeabi_v7a_release:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
+--- io.flutter:arm64_v8a_release:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
+--- io.flutter:x86_64_release:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
+--- io.flutter:flutter_embedding_release:{strictly 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8} -> 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8 (c)
+--- io.flutter:armeabi_v7a_release:{strictly 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8} -> 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8 (c)
+--- io.flutter:arm64_v8a_release:{strictly 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8} -> 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8 (c)
+--- io.flutter:x86_64_release:{strictly 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8} -> 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8 (c)
+--- androidx.lifecycle:lifecycle-common:{strictly 2.2.0} -> 2.2.0 (c)
+--- androidx.lifecycle:lifecycle-common-java8:{strictly 2.2.0} -> 2.2.0 (c)
+--- androidx.lifecycle:lifecycle-runtime:{strictly 2.2.0} -> 2.2.0 (c)
+--- androidx.fragment:fragment:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.annotation:annotation:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.arch.core:core-common:{strictly 2.1.0} -> 2.1.0 (c)
+--- androidx.core:core:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.collection:collection:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.viewpager:viewpager:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.loader:loader:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.activity:activity:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.lifecycle:lifecycle-viewmodel:{strictly 2.1.0} -> 2.1.0 (c)
+--- androidx.customview:customview:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.lifecycle:lifecycle-livedata:{strictly 2.0.0} -> 2.0.0 (c)
+--- androidx.savedstate:savedstate:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.versionedparcelable:versionedparcelable:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.arch.core:core-runtime:{strictly 2.0.0} -> 2.0.0 (c)
\--- androidx.lifecycle:lifecycle-livedata-core:{strictly 2.0.0} -> 2.0.0 (c)

releaseUnitTestRuntimeClasspath - Resolved configuration for runtime for variant: releaseUnitTest
+--- io.flutter:flutter_embedding_release:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
|    +--- androidx.lifecycle:lifecycle-common:2.2.0
|    |    \--- androidx.annotation:annotation:1.1.0
|    +--- androidx.lifecycle:lifecycle-common-java8:2.2.0
|    |    +--- androidx.lifecycle:lifecycle-common:2.2.0 (*)
|    |    \--- androidx.annotation:annotation:1.1.0
|    +--- androidx.lifecycle:lifecycle-runtime:2.2.0
|    |    +--- androidx.lifecycle:lifecycle-common:2.2.0 (*)
|    |    +--- androidx.arch.core:core-common:2.1.0
|    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    \--- androidx.annotation:annotation:1.1.0
|    +--- androidx.fragment:fragment:1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.lifecycle:lifecycle-runtime:2.0.0 -> 2.2.0 (*)
|    |    |    +--- androidx.versionedparcelable:versionedparcelable:1.1.0
|    |    |    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0
|    |    |    |         \--- androidx.annotation:annotation:1.1.0
|    |    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    |    +--- androidx.collection:collection:1.1.0 (*)
|    |    +--- androidx.viewpager:viewpager:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    +--- androidx.core:core:1.0.0 -> 1.1.0 (*)
|    |    |    \--- androidx.customview:customview:1.0.0
|    |    |         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |         \--- androidx.core:core:1.0.0 -> 1.1.0 (*)
|    |    +--- androidx.loader:loader:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    +--- androidx.core:core:1.0.0 -> 1.1.0 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-livedata:2.0.0
|    |    |    |    +--- androidx.arch.core:core-runtime:2.0.0
|    |    |    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    +--- androidx.lifecycle:lifecycle-livedata-core:2.0.0
|    |    |    |    |    +--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.2.0 (*)
|    |    |    |    |    +--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    |    \--- androidx.arch.core:core-runtime:2.0.0 (*)
|    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0
|    |    |         \--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.activity:activity:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.core:core:1.1.0 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-runtime:2.1.0 -> 2.2.0 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-viewmodel:2.1.0 (*)
|    |    |    \--- androidx.savedstate:savedstate:1.0.0
|    |    |         +--- androidx.annotation:annotation:1.1.0
|    |    |         +--- androidx.arch.core:core-common:2.0.1 -> 2.1.0 (*)
|    |    |         \--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.2.0 (*)
|    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0 (*)
|    \--- androidx.annotation:annotation:1.1.0
+--- io.flutter:armeabi_v7a_release:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
+--- io.flutter:arm64_v8a_release:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
\--- io.flutter:x86_64_release:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8

releaseWearApp - Link to a wear app to embed for object 'release'. (n)
No dependencies

runtimeOnly - Runtime only dependencies for 'main' sources. (n)
No dependencies

testAnnotationProcessor - Classpath for the annotation processor for 'test'. (n)
No dependencies

testApi - API dependencies for 'test' sources. (n)
No dependencies

testCompile - Compile dependencies for 'test' sources (deprecated: use 'testImplementation' instead).
No dependencies

testCompileOnly - Compile only dependencies for 'test' sources. (n)
No dependencies

testDebugAnnotationProcessor - Classpath for the annotation processor for 'testDebug'. (n)
No dependencies

testDebugApi - API dependencies for 'testDebug' sources. (n)
No dependencies

testDebugCompile - Compile dependencies for 'testDebug' sources (deprecated: use 'testDebugImplementation' instead). (n)
No dependencies

testDebugCompileOnly - Compile only dependencies for 'testDebug' sources. (n)
No dependencies

testDebugImplementation - Implementation only dependencies for 'testDebug' sources. (n)
No dependencies

testDebugProvided - Provided dependencies for 'testDebug' sources (deprecated: use 'testDebugCompileOnly' instead). (n)
No dependencies

testDebugPublish - Publish dependencies for 'testDebug' sources (deprecated: use 'testDebugRuntimeOnly' instead). (n)
No dependencies

testDebugRuntimeOnly - Runtime only dependencies for 'testDebug' sources. (n)
No dependencies

testDebugWearApp - Link to a wear app to embed for object 'testDebug'. (n)
No dependencies

testImplementation - Implementation only dependencies for 'test' sources. (n)
No dependencies

testProfileAnnotationProcessor - Classpath for the annotation processor for 'testProfile'. (n)
No dependencies

testProfileApi - API dependencies for 'testProfile' sources. (n)
No dependencies

testProfileCompile - Compile dependencies for 'testProfile' sources (deprecated: use 'testProfileImplementation' instead). (n)
No dependencies

testProfileCompileOnly - Compile only dependencies for 'testProfile' sources. (n)
No dependencies

testProfileImplementation - Implementation only dependencies for 'testProfile' sources. (n)
No dependencies

testProfileProvided - Provided dependencies for 'testProfile' sources (deprecated: use 'testProfileCompileOnly' instead). (n)
No dependencies

testProfilePublish - Publish dependencies for 'testProfile' sources (deprecated: use 'testProfileRuntimeOnly' instead). (n)
No dependencies

testProfileRuntimeOnly - Runtime only dependencies for 'testProfile' sources. (n)
No dependencies

testProfileWearApp - Link to a wear app to embed for object 'testProfile'. (n)
No dependencies

testProvided - Provided dependencies for 'test' sources (deprecated: use 'testCompileOnly' instead). (n)
No dependencies

testPublish - Publish dependencies for 'test' sources (deprecated: use 'testRuntimeOnly' instead). (n)
No dependencies

testReleaseAnnotationProcessor - Classpath for the annotation processor for 'testRelease'. (n)
No dependencies

testReleaseApi - API dependencies for 'testRelease' sources. (n)
No dependencies

testReleaseCompile - Compile dependencies for 'testRelease' sources (deprecated: use 'testReleaseImplementation' instead). (n)
No dependencies

testReleaseCompileOnly - Compile only dependencies for 'testRelease' sources. (n)
No dependencies

testReleaseImplementation - Implementation only dependencies for 'testRelease' sources. (n)
No dependencies

testReleaseProvided - Provided dependencies for 'testRelease' sources (deprecated: use 'testReleaseCompileOnly' instead). (n)
No dependencies

testReleasePublish - Publish dependencies for 'testRelease' sources (deprecated: use 'testReleaseRuntimeOnly' instead). (n)
No dependencies

testReleaseRuntimeOnly - Runtime only dependencies for 'testRelease' sources. (n)
No dependencies

testReleaseWearApp - Link to a wear app to embed for object 'testRelease'. (n)
No dependencies

testRuntimeOnly - Runtime only dependencies for 'test' sources. (n)
No dependencies

testWearApp - Link to a wear app to embed for object 'test'. (n)
No dependencies

wearApp - Link to a wear app to embed for object 'main'. (n)
No dependencies

(c) - dependency constraint
(*) - dependencies omitted (listed previously)

(n) - Not resolved (configuration is not meant to be resolved)

A web-based, searchable dependency report is available by adding the --scan option.

Deprecated Gradle features were used in this build, making it incompatible with Gradle 7.0.
Use '--warning-mode all' to show the individual deprecation warnings.
See https://docs.gradle.org/6.1.1/userguide/command_line_interface.html#sec:command_line_warnings

BUILD SUCCESSFUL in 1s
1 actionable task: 1 executed
generateLockfiles

> Configure project :app
WARNING: DSL element 'annotationProcessorOptions.includeCompileClasspath' is obsolete.
It will be removed in version 5.0 of the Android Gradle plugin.
It does not do anything and AGP no longer includes annotation processors added on your project's compile classpath

> Task :module_aliyun:dependencies

------------------------------------------------------------
Project :module_aliyun
------------------------------------------------------------

No configurations

A web-based, searchable dependency report is available by adding the --scan option.

Deprecated Gradle features were used in this build, making it incompatible with Gradle 7.0.
Use '--warning-mode all' to show the individual deprecation warnings.
See https://docs.gradle.org/6.1.1/userguide/command_line_interface.html#sec:command_line_warnings

BUILD SUCCESSFUL in 761ms
1 actionable task: 1 executed
generateLockfiles

> Configure project :app
WARNING: DSL element 'annotationProcessorOptions.includeCompileClasspath' is obsolete.
It will be removed in version 5.0 of the Android Gradle plugin.
It does not do anything and AGP no longer includes annotation processors added on your project's compile classpath

> Task :module_flutter:dependencies

------------------------------------------------------------
Project :module_flutter
------------------------------------------------------------

No configurations

A web-based, searchable dependency report is available by adding the --scan option.

Deprecated Gradle features were used in this build, making it incompatible with Gradle 7.0.
Use '--warning-mode all' to show the individual deprecation warnings.
See https://docs.gradle.org/6.1.1/userguide/command_line_interface.html#sec:command_line_warnings

BUILD SUCCESSFUL in 760ms
1 actionable task: 1 executed
generateLockfiles

> Configure project :app
WARNING: DSL element 'annotationProcessorOptions.includeCompileClasspath' is obsolete.
It will be removed in version 5.0 of the Android Gradle plugin.
It does not do anything and AGP no longer includes annotation processors added on your project's compile classpath

> Task :module_flutter_native:dependencies

------------------------------------------------------------
Project :module_flutter_native
------------------------------------------------------------

_internal_aapt2_binary - The AAPT2 binary to use for processing resources.
\--- com.android.tools.build:aapt2:4.0.1-6197926

androidApis - Configuration providing various types of Android JAR file
No dependencies

androidTestAnnotationProcessor - Classpath for the annotation processor for 'androidTest'. (n)
No dependencies

androidTestApi - API dependencies for 'androidTest' sources. (n)
No dependencies

androidTestCompile - Compile dependencies for 'androidTest' sources (deprecated: use 'androidTestImplementation' instead). (n)
No dependencies

androidTestCompileOnly - Compile only dependencies for 'androidTest' sources. (n)
No dependencies

androidTestDebugAnnotationProcessor - Classpath for the annotation processor for 'androidTestDebug'. (n)
No dependencies

androidTestDebugApi - API dependencies for 'androidTestDebug' sources. (n)
No dependencies

androidTestDebugCompile - Compile dependencies for 'androidTestDebug' sources (deprecated: use 'androidTestDebugImplementation' instead). (n)
No dependencies

androidTestDebugCompileOnly - Compile only dependencies for 'androidTestDebug' sources. (n)
No dependencies

androidTestDebugImplementation - Implementation only dependencies for 'androidTestDebug' sources. (n)
No dependencies

androidTestDebugProvided - Provided dependencies for 'androidTestDebug' sources (deprecated: use 'androidTestDebugCompileOnly' instead). (n)
No dependencies

androidTestDebugPublish - Publish dependencies for 'androidTestDebug' sources (deprecated: use 'androidTestDebugRuntimeOnly' instead). (n)
No dependencies

androidTestDebugRuntimeOnly - Runtime only dependencies for 'androidTestDebug' sources. (n)
No dependencies

androidTestDebugWearApp - Link to a wear app to embed for object 'androidTestDebug'. (n)
No dependencies

androidTestImplementation - Implementation only dependencies for 'androidTest' sources. (n)
No dependencies

androidTestProvided - Provided dependencies for 'androidTest' sources (deprecated: use 'androidTestCompileOnly' instead). (n)
No dependencies

androidTestPublish - Publish dependencies for 'androidTest' sources (deprecated: use 'androidTestRuntimeOnly' instead). (n)
No dependencies

androidTestRuntimeOnly - Runtime only dependencies for 'androidTest' sources. (n)
No dependencies

androidTestUtil - Additional APKs used during instrumentation testing.
No dependencies

androidTestWearApp - Link to a wear app to embed for object 'androidTest'. (n)
No dependencies

annotationProcessor - Classpath for the annotation processor for 'main'. (n)
No dependencies

api - API dependencies for 'main' sources. (n)
\--- project flutter (n)

archives - Configuration for archive artifacts.
+--- project :flutter FAILED
+--- androidx.appcompat:appcompat:1.2.0
|    +--- androidx.annotation:annotation:1.1.0
|    +--- androidx.core:core:1.3.0 -> 1.3.1
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.lifecycle:lifecycle-runtime:2.0.0 -> 2.1.0
|    |    |    +--- androidx.lifecycle:lifecycle-common:2.1.0
|    |    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.arch.core:core-common:2.1.0
|    |    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.versionedparcelable:versionedparcelable:1.1.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0
|    |    |         \--- androidx.annotation:annotation:1.1.0
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.cursoradapter:cursoradapter:1.0.0
|    |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    +--- androidx.fragment:fragment:1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    +--- androidx.collection:collection:1.1.0 (*)
|    |    +--- androidx.viewpager:viewpager:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    |    \--- androidx.customview:customview:1.0.0
|    |    |         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |         \--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    +--- androidx.loader:loader:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-livedata:2.0.0
|    |    |    |    +--- androidx.arch.core:core-runtime:2.0.0
|    |    |    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    +--- androidx.lifecycle:lifecycle-livedata-core:2.0.0
|    |    |    |    |    +--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    |    +--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    |    \--- androidx.arch.core:core-runtime:2.0.0 (*)
|    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0
|    |    |         \--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.activity:activity:1.0.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-runtime:2.1.0 (*)
|    |    |    +--- androidx.lifecycle:lifecycle-viewmodel:2.1.0 (*)
|    |    |    \--- androidx.savedstate:savedstate:1.0.0
|    |    |         +--- androidx.annotation:annotation:1.1.0
|    |    |         +--- androidx.arch.core:core-common:2.0.1 -> 2.1.0 (*)
|    |    |         \--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.1.0 (*)
|    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0 (*)
|    +--- androidx.appcompat:appcompat-resources:1.2.0
|    |    +--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.0.1 -> 1.3.1 (*)
|    |    +--- androidx.vectordrawable:vectordrawable:1.1.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    |    \--- androidx.collection:collection:1.1.0 (*)
|    |    \--- androidx.vectordrawable:vectordrawable-animated:1.1.0
|    |         +--- androidx.vectordrawable:vectordrawable:1.1.0 (*)
|    |         +--- androidx.interpolator:interpolator:1.0.0
|    |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         \--- androidx.collection:collection:1.1.0 (*)
|    +--- androidx.drawerlayout:drawerlayout:1.0.0
|    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    \--- androidx.customview:customview:1.0.0 (*)
|    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
\--- com.google.android.material:material:1.3.0
     +--- androidx.annotation:annotation:1.0.1 -> 1.1.0
     +--- androidx.appcompat:appcompat:1.1.0 -> 1.2.0 (*)
     +--- androidx.cardview:cardview:1.0.0
     |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
     +--- androidx.coordinatorlayout:coordinatorlayout:1.1.0
     |    +--- androidx.annotation:annotation:1.1.0
     |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
     |    +--- androidx.customview:customview:1.0.0 (*)
     |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
     +--- androidx.constraintlayout:constraintlayout:2.0.1
     |    +--- androidx.appcompat:appcompat:1.2.0 (*)
     |    +--- androidx.core:core:1.3.1 (*)
     |    \--- androidx.constraintlayout:constraintlayout-solver:2.0.1
     +--- androidx.core:core:1.2.0 -> 1.3.1 (*)
     +--- androidx.dynamicanimation:dynamicanimation:1.0.0
     |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
     |    +--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
     |    \--- androidx.legacy:legacy-support-core-utils:1.0.0
     |         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
     |         +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
     |         +--- androidx.documentfile:documentfile:1.0.0
     |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
     |         +--- androidx.loader:loader:1.0.0 (*)
     |         +--- androidx.localbroadcastmanager:localbroadcastmanager:1.0.0
     |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
     |         \--- androidx.print:print:1.0.0
     |              \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
     +--- androidx.annotation:annotation-experimental:1.0.0
     +--- androidx.fragment:fragment:1.0.0 -> 1.1.0 (*)
     +--- androidx.lifecycle:lifecycle-runtime:2.0.0 -> 2.1.0 (*)
     +--- androidx.recyclerview:recyclerview:1.0.0 -> 1.1.0
     |    +--- androidx.annotation:annotation:1.1.0
     |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
     |    +--- androidx.customview:customview:1.0.0 (*)
     |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
     +--- androidx.transition:transition:1.2.0
     |    +--- androidx.annotation:annotation:1.1.0
     |    +--- androidx.core:core:1.0.1 -> 1.3.1 (*)
     |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
     +--- androidx.vectordrawable:vectordrawable:1.1.0 (*)
     \--- androidx.viewpager2:viewpager2:1.0.0
          +--- androidx.annotation:annotation:1.1.0
          +--- androidx.fragment:fragment:1.1.0 (*)
          +--- androidx.recyclerview:recyclerview:1.1.0 (*)
          +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
          \--- androidx.collection:collection:1.1.0 (*)

compile - Compile dependencies for 'main' sources (deprecated: use 'implementation' instead).
No dependencies

compileOnly - Compile only dependencies for 'main' sources. (n)
No dependencies

coreLibraryDesugaring - Configuration to desugar libraries
No dependencies

debugAllApiPublication - All API publication for debug (n)
No dependencies

debugAllRuntimePublication - All runtime publication for debug (n)
No dependencies

debugAndroidTestAnnotationProcessorClasspath - Resolved configuration for annotation-processor for variant: debugAndroidTest
No dependencies

debugAndroidTestCompileClasspath - Resolved configuration for compilation for variant: debugAndroidTest
+--- project :flutter
|    +--- io.flutter:flutter_embedding_debug:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
|    |    +--- androidx.lifecycle:lifecycle-common:2.2.0
|    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.lifecycle:lifecycle-common-java8:2.2.0
|    |    |    +--- androidx.lifecycle:lifecycle-common:2.2.0 (*)
|    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.lifecycle:lifecycle-runtime:2.2.0
|    |    |    +--- androidx.lifecycle:lifecycle-common:2.2.0 (*)
|    |    |    +--- androidx.arch.core:core-common:2.1.0
|    |    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.fragment:fragment:1.1.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.core:core:1.1.0 -> 1.3.1
|    |    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    |    +--- androidx.lifecycle:lifecycle-runtime:2.0.0 -> 2.2.0 (*)
|    |    |    |    \--- androidx.versionedparcelable:versionedparcelable:1.1.0
|    |    |    |         +--- androidx.annotation:annotation:1.1.0
|    |    |    |         \--- androidx.collection:collection:1.0.0 -> 1.1.0
|    |    |    |              \--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.collection:collection:1.1.0 (*)
|    |    |    +--- androidx.viewpager:viewpager:1.0.0
|    |    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    |    |    \--- androidx.customview:customview:1.0.0
|    |    |    |         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    |         \--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    |    +--- androidx.loader:loader:1.0.0
|    |    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    |    |    +--- androidx.lifecycle:lifecycle-livedata:2.0.0
|    |    |    |    |    +--- androidx.arch.core:core-runtime:2.0.0
|    |    |    |    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    |    +--- androidx.lifecycle:lifecycle-livedata-core:2.0.0
|    |    |    |    |    |    +--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.2.0 (*)
|    |    |    |    |    |    +--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    |    |    \--- androidx.arch.core:core-runtime:2.0.0 (*)
|    |    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0
|    |    |    |         \--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.activity:activity:1.0.0
|    |    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    |    |    +--- androidx.lifecycle:lifecycle-runtime:2.1.0 -> 2.2.0 (*)
|    |    |    |    +--- androidx.lifecycle:lifecycle-viewmodel:2.1.0 (*)
|    |    |    |    \--- androidx.savedstate:savedstate:1.0.0
|    |    |    |         +--- androidx.annotation:annotation:1.1.0
|    |    |    |         +--- androidx.arch.core:core-common:2.0.1 -> 2.1.0 (*)
|    |    |    |         \--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.2.0 (*)
|    |    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0 (*)
|    |    \--- androidx.annotation:annotation:1.1.0
|    +--- io.flutter:armeabi_v7a_debug:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
|    +--- io.flutter:arm64_v8a_debug:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
|    +--- io.flutter:x86_64_debug:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
|    \--- io.flutter:x86_debug:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
+--- androidx.appcompat:appcompat:1.2.0
|    +--- androidx.annotation:annotation:1.1.0
|    +--- androidx.core:core:1.3.0 -> 1.3.1 (*)
|    +--- androidx.cursoradapter:cursoradapter:1.0.0
|    |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    +--- androidx.fragment:fragment:1.1.0 (*)
|    +--- androidx.appcompat:appcompat-resources:1.2.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.0.1 -> 1.3.1 (*)
|    |    +--- androidx.vectordrawable:vectordrawable:1.1.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    |    \--- androidx.collection:collection:1.1.0 (*)
|    |    \--- androidx.vectordrawable:vectordrawable-animated:1.1.0
|    |         +--- androidx.vectordrawable:vectordrawable:1.1.0 (*)
|    |         +--- androidx.interpolator:interpolator:1.0.0
|    |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         \--- androidx.collection:collection:1.1.0 (*)
|    \--- androidx.drawerlayout:drawerlayout:1.0.0
|         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|         +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|         \--- androidx.customview:customview:1.0.0 (*)
+--- com.google.android.material:material:1.3.0
|    +--- androidx.annotation:annotation:1.0.1 -> 1.1.0
|    +--- androidx.appcompat:appcompat:1.1.0 -> 1.2.0 (*)
|    +--- androidx.cardview:cardview:1.0.0
|    |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    +--- androidx.coordinatorlayout:coordinatorlayout:1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    +--- androidx.customview:customview:1.0.0 (*)
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.constraintlayout:constraintlayout:2.0.1
|    |    +--- androidx.appcompat:appcompat:1.2.0 (*)
|    |    +--- androidx.core:core:1.3.1 (*)
|    |    \--- androidx.constraintlayout:constraintlayout-solver:2.0.1
|    +--- androidx.core:core:1.2.0 -> 1.3.1 (*)
|    +--- androidx.dynamicanimation:dynamicanimation:1.0.0
|    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    +--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    |    \--- androidx.legacy:legacy-support-core-utils:1.0.0
|    |         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |         +--- androidx.documentfile:documentfile:1.0.0
|    |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         +--- androidx.loader:loader:1.0.0 (*)
|    |         +--- androidx.localbroadcastmanager:localbroadcastmanager:1.0.0
|    |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         \--- androidx.print:print:1.0.0
|    |              \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    +--- androidx.annotation:annotation-experimental:1.0.0
|    +--- androidx.fragment:fragment:1.0.0 -> 1.1.0 (*)
|    +--- androidx.lifecycle:lifecycle-runtime:2.0.0 -> 2.2.0 (*)
|    +--- androidx.recyclerview:recyclerview:1.0.0 -> 1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    +--- androidx.customview:customview:1.0.0 (*)
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.transition:transition:1.2.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.0.1 -> 1.3.1 (*)
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.vectordrawable:vectordrawable:1.1.0 (*)
|    \--- androidx.viewpager2:viewpager2:1.0.0
|         +--- androidx.annotation:annotation:1.1.0
|         +--- androidx.fragment:fragment:1.1.0 (*)
|         +--- androidx.recyclerview:recyclerview:1.1.0 (*)
|         +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|         \--- androidx.collection:collection:1.1.0 (*)
+--- androidx.appcompat:appcompat:{strictly 1.2.0} -> 1.2.0 (c)
+--- com.google.android.material:material:{strictly 1.3.0} -> 1.3.0 (c)
+--- io.flutter:flutter_embedding_debug:{strictly 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8} -> 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8 (c)
+--- io.flutter:armeabi_v7a_debug:{strictly 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8} -> 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8 (c)
+--- io.flutter:arm64_v8a_debug:{strictly 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8} -> 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8 (c)
+--- io.flutter:x86_64_debug:{strictly 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8} -> 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8 (c)
+--- io.flutter:x86_debug:{strictly 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8} -> 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8 (c)
+--- androidx.annotation:annotation:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.core:core:{strictly 1.3.1} -> 1.3.1 (c)
+--- androidx.cursoradapter:cursoradapter:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.fragment:fragment:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.appcompat:appcompat-resources:{strictly 1.2.0} -> 1.2.0 (c)
+--- androidx.drawerlayout:drawerlayout:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.cardview:cardview:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.coordinatorlayout:coordinatorlayout:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.constraintlayout:constraintlayout:{strictly 2.0.1} -> 2.0.1 (c)
+--- androidx.dynamicanimation:dynamicanimation:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.annotation:annotation-experimental:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.lifecycle:lifecycle-runtime:{strictly 2.2.0} -> 2.2.0 (c)
+--- androidx.recyclerview:recyclerview:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.transition:transition:{strictly 1.2.0} -> 1.2.0 (c)
+--- androidx.vectordrawable:vectordrawable:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.viewpager2:viewpager2:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.lifecycle:lifecycle-common:{strictly 2.2.0} -> 2.2.0 (c)
+--- androidx.lifecycle:lifecycle-common-java8:{strictly 2.2.0} -> 2.2.0 (c)
+--- androidx.versionedparcelable:versionedparcelable:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.collection:collection:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.viewpager:viewpager:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.loader:loader:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.activity:activity:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.lifecycle:lifecycle-viewmodel:{strictly 2.1.0} -> 2.1.0 (c)
+--- androidx.vectordrawable:vectordrawable-animated:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.customview:customview:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.constraintlayout:constraintlayout-solver:{strictly 2.0.1} -> 2.0.1 (c)
+--- androidx.legacy:legacy-support-core-utils:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.arch.core:core-common:{strictly 2.1.0} -> 2.1.0 (c)
+--- androidx.lifecycle:lifecycle-livedata:{strictly 2.0.0} -> 2.0.0 (c)
+--- androidx.savedstate:savedstate:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.interpolator:interpolator:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.documentfile:documentfile:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.localbroadcastmanager:localbroadcastmanager:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.print:print:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.arch.core:core-runtime:{strictly 2.0.0} -> 2.0.0 (c)
\--- androidx.lifecycle:lifecycle-livedata-core:{strictly 2.0.0} -> 2.0.0 (c)

debugAndroidTestRuntimeClasspath - Resolved configuration for runtime for variant: debugAndroidTest
+--- project :flutter
|    +--- io.flutter:flutter_embedding_debug:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
|    |    +--- androidx.lifecycle:lifecycle-common:2.2.0
|    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.lifecycle:lifecycle-common-java8:2.2.0
|    |    |    +--- androidx.lifecycle:lifecycle-common:2.2.0 (*)
|    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.lifecycle:lifecycle-runtime:2.2.0
|    |    |    +--- androidx.lifecycle:lifecycle-common:2.2.0 (*)
|    |    |    +--- androidx.arch.core:core-common:2.1.0
|    |    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.fragment:fragment:1.1.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.core:core:1.1.0 -> 1.3.1
|    |    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    |    +--- androidx.lifecycle:lifecycle-runtime:2.0.0 -> 2.2.0 (*)
|    |    |    |    +--- androidx.versionedparcelable:versionedparcelable:1.1.0
|    |    |    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    |    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0
|    |    |    |    |         \--- androidx.annotation:annotation:1.1.0
|    |    |    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    |    |    +--- androidx.collection:collection:1.1.0 (*)
|    |    |    +--- androidx.viewpager:viewpager:1.0.0
|    |    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    |    |    \--- androidx.customview:customview:1.0.0
|    |    |    |         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    |         \--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    |    +--- androidx.loader:loader:1.0.0
|    |    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    |    |    +--- androidx.lifecycle:lifecycle-livedata:2.0.0
|    |    |    |    |    +--- androidx.arch.core:core-runtime:2.0.0
|    |    |    |    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    |    +--- androidx.lifecycle:lifecycle-livedata-core:2.0.0
|    |    |    |    |    |    +--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.2.0 (*)
|    |    |    |    |    |    +--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    |    |    \--- androidx.arch.core:core-runtime:2.0.0 (*)
|    |    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0
|    |    |    |         \--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.activity:activity:1.0.0
|    |    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    |    |    +--- androidx.lifecycle:lifecycle-runtime:2.1.0 -> 2.2.0 (*)
|    |    |    |    +--- androidx.lifecycle:lifecycle-viewmodel:2.1.0 (*)
|    |    |    |    \--- androidx.savedstate:savedstate:1.0.0
|    |    |    |         +--- androidx.annotation:annotation:1.1.0
|    |    |    |         +--- androidx.arch.core:core-common:2.0.1 -> 2.1.0 (*)
|    |    |    |         \--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.2.0 (*)
|    |    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0 (*)
|    |    \--- androidx.annotation:annotation:1.1.0
|    +--- io.flutter:armeabi_v7a_debug:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
|    +--- io.flutter:arm64_v8a_debug:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
|    +--- io.flutter:x86_64_debug:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
|    \--- io.flutter:x86_debug:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
+--- androidx.appcompat:appcompat:1.2.0
|    +--- androidx.annotation:annotation:1.1.0
|    +--- androidx.core:core:1.3.0 -> 1.3.1 (*)
|    +--- androidx.cursoradapter:cursoradapter:1.0.0
|    |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    +--- androidx.fragment:fragment:1.1.0 (*)
|    +--- androidx.appcompat:appcompat-resources:1.2.0
|    |    +--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.0.1 -> 1.3.1 (*)
|    |    +--- androidx.vectordrawable:vectordrawable:1.1.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    |    \--- androidx.collection:collection:1.1.0 (*)
|    |    \--- androidx.vectordrawable:vectordrawable-animated:1.1.0
|    |         +--- androidx.vectordrawable:vectordrawable:1.1.0 (*)
|    |         +--- androidx.interpolator:interpolator:1.0.0
|    |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         \--- androidx.collection:collection:1.1.0 (*)
|    +--- androidx.drawerlayout:drawerlayout:1.0.0
|    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    \--- androidx.customview:customview:1.0.0 (*)
|    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
+--- com.google.android.material:material:1.3.0
|    +--- androidx.annotation:annotation:1.0.1 -> 1.1.0
|    +--- androidx.appcompat:appcompat:1.1.0 -> 1.2.0 (*)
|    +--- androidx.cardview:cardview:1.0.0
|    |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    +--- androidx.coordinatorlayout:coordinatorlayout:1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    +--- androidx.customview:customview:1.0.0 (*)
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.constraintlayout:constraintlayout:2.0.1
|    |    +--- androidx.appcompat:appcompat:1.2.0 (*)
|    |    +--- androidx.core:core:1.3.1 (*)
|    |    \--- androidx.constraintlayout:constraintlayout-solver:2.0.1
|    +--- androidx.core:core:1.2.0 -> 1.3.1 (*)
|    +--- androidx.dynamicanimation:dynamicanimation:1.0.0
|    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    +--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    |    \--- androidx.legacy:legacy-support-core-utils:1.0.0
|    |         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |         +--- androidx.documentfile:documentfile:1.0.0
|    |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         +--- androidx.loader:loader:1.0.0 (*)
|    |         +--- androidx.localbroadcastmanager:localbroadcastmanager:1.0.0
|    |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         \--- androidx.print:print:1.0.0
|    |              \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    +--- androidx.annotation:annotation-experimental:1.0.0
|    +--- androidx.fragment:fragment:1.0.0 -> 1.1.0 (*)
|    +--- androidx.lifecycle:lifecycle-runtime:2.0.0 -> 2.2.0 (*)
|    +--- androidx.recyclerview:recyclerview:1.0.0 -> 1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    +--- androidx.customview:customview:1.0.0 (*)
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.transition:transition:1.2.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.0.1 -> 1.3.1 (*)
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.vectordrawable:vectordrawable:1.1.0 (*)
|    \--- androidx.viewpager2:viewpager2:1.0.0
|         +--- androidx.annotation:annotation:1.1.0
|         +--- androidx.fragment:fragment:1.1.0 (*)
|         +--- androidx.recyclerview:recyclerview:1.1.0 (*)
|         +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|         \--- androidx.collection:collection:1.1.0 (*)
+--- androidx.appcompat:appcompat:{strictly 1.2.0} -> 1.2.0 (c)
+--- com.google.android.material:material:{strictly 1.3.0} -> 1.3.0 (c)
+--- io.flutter:flutter_embedding_debug:{strictly 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8} -> 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8 (c)
+--- io.flutter:armeabi_v7a_debug:{strictly 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8} -> 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8 (c)
+--- io.flutter:arm64_v8a_debug:{strictly 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8} -> 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8 (c)
+--- io.flutter:x86_64_debug:{strictly 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8} -> 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8 (c)
+--- io.flutter:x86_debug:{strictly 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8} -> 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8 (c)
+--- androidx.annotation:annotation:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.core:core:{strictly 1.3.1} -> 1.3.1 (c)
+--- androidx.cursoradapter:cursoradapter:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.fragment:fragment:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.appcompat:appcompat-resources:{strictly 1.2.0} -> 1.2.0 (c)
+--- androidx.drawerlayout:drawerlayout:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.collection:collection:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.cardview:cardview:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.coordinatorlayout:coordinatorlayout:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.constraintlayout:constraintlayout:{strictly 2.0.1} -> 2.0.1 (c)
+--- androidx.dynamicanimation:dynamicanimation:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.annotation:annotation-experimental:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.lifecycle:lifecycle-runtime:{strictly 2.2.0} -> 2.2.0 (c)
+--- androidx.recyclerview:recyclerview:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.transition:transition:{strictly 1.2.0} -> 1.2.0 (c)
+--- androidx.vectordrawable:vectordrawable:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.viewpager2:viewpager2:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.lifecycle:lifecycle-common:{strictly 2.2.0} -> 2.2.0 (c)
+--- androidx.lifecycle:lifecycle-common-java8:{strictly 2.2.0} -> 2.2.0 (c)
+--- androidx.versionedparcelable:versionedparcelable:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.viewpager:viewpager:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.loader:loader:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.activity:activity:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.lifecycle:lifecycle-viewmodel:{strictly 2.1.0} -> 2.1.0 (c)
+--- androidx.vectordrawable:vectordrawable-animated:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.customview:customview:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.constraintlayout:constraintlayout-solver:{strictly 2.0.1} -> 2.0.1 (c)
+--- androidx.legacy:legacy-support-core-utils:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.arch.core:core-common:{strictly 2.1.0} -> 2.1.0 (c)
+--- androidx.lifecycle:lifecycle-livedata:{strictly 2.0.0} -> 2.0.0 (c)
+--- androidx.savedstate:savedstate:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.interpolator:interpolator:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.documentfile:documentfile:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.localbroadcastmanager:localbroadcastmanager:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.print:print:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.arch.core:core-runtime:{strictly 2.0.0} -> 2.0.0 (c)
\--- androidx.lifecycle:lifecycle-livedata-core:{strictly 2.0.0} -> 2.0.0 (c)

debugAnnotationProcessor - Classpath for the annotation processor for 'debug'. (n)
No dependencies

debugAnnotationProcessorClasspath - Resolved configuration for annotation-processor for variant: debug
No dependencies

debugApi - API dependencies for 'debug' sources. (n)
No dependencies

debugApiElements - API elements for debug (n)
No dependencies

debugApiPublication - API publication for debug (n)
No dependencies

debugCompile - Compile dependencies for 'debug' sources (deprecated: use 'debugImplementation' instead). (n)
No dependencies

debugCompileClasspath - Resolved configuration for compilation for variant: debug
+--- project :flutter
|    +--- io.flutter:flutter_embedding_debug:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
|    |    +--- androidx.lifecycle:lifecycle-common:2.2.0
|    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.lifecycle:lifecycle-common-java8:2.2.0
|    |    |    +--- androidx.lifecycle:lifecycle-common:2.2.0 (*)
|    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.lifecycle:lifecycle-runtime:2.2.0
|    |    |    +--- androidx.lifecycle:lifecycle-common:2.2.0 (*)
|    |    |    +--- androidx.arch.core:core-common:2.1.0
|    |    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.fragment:fragment:1.1.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.core:core:1.1.0 -> 1.3.1
|    |    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    |    +--- androidx.lifecycle:lifecycle-runtime:2.0.0 -> 2.2.0 (*)
|    |    |    |    \--- androidx.versionedparcelable:versionedparcelable:1.1.0
|    |    |    |         +--- androidx.annotation:annotation:1.1.0
|    |    |    |         \--- androidx.collection:collection:1.0.0 -> 1.1.0
|    |    |    |              \--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.collection:collection:1.1.0 (*)
|    |    |    +--- androidx.viewpager:viewpager:1.0.0
|    |    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    |    |    \--- androidx.customview:customview:1.0.0
|    |    |    |         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    |         \--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    |    +--- androidx.loader:loader:1.0.0
|    |    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    |    |    +--- androidx.lifecycle:lifecycle-livedata:2.0.0
|    |    |    |    |    +--- androidx.arch.core:core-runtime:2.0.0
|    |    |    |    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    |    +--- androidx.lifecycle:lifecycle-livedata-core:2.0.0
|    |    |    |    |    |    +--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.2.0 (*)
|    |    |    |    |    |    +--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    |    |    \--- androidx.arch.core:core-runtime:2.0.0 (*)
|    |    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0
|    |    |    |         \--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.activity:activity:1.0.0
|    |    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    |    |    +--- androidx.lifecycle:lifecycle-runtime:2.1.0 -> 2.2.0 (*)
|    |    |    |    +--- androidx.lifecycle:lifecycle-viewmodel:2.1.0 (*)
|    |    |    |    \--- androidx.savedstate:savedstate:1.0.0
|    |    |    |         +--- androidx.annotation:annotation:1.1.0
|    |    |    |         +--- androidx.arch.core:core-common:2.0.1 -> 2.1.0 (*)
|    |    |    |         \--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.2.0 (*)
|    |    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0 (*)
|    |    \--- androidx.annotation:annotation:1.1.0
|    +--- io.flutter:armeabi_v7a_debug:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
|    +--- io.flutter:arm64_v8a_debug:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
|    +--- io.flutter:x86_64_debug:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
|    \--- io.flutter:x86_debug:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
+--- androidx.appcompat:appcompat:1.2.0
|    +--- androidx.annotation:annotation:1.1.0
|    +--- androidx.core:core:1.3.0 -> 1.3.1 (*)
|    +--- androidx.cursoradapter:cursoradapter:1.0.0
|    |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    +--- androidx.fragment:fragment:1.1.0 (*)
|    +--- androidx.appcompat:appcompat-resources:1.2.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.0.1 -> 1.3.1 (*)
|    |    +--- androidx.vectordrawable:vectordrawable:1.1.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    |    \--- androidx.collection:collection:1.1.0 (*)
|    |    \--- androidx.vectordrawable:vectordrawable-animated:1.1.0
|    |         +--- androidx.vectordrawable:vectordrawable:1.1.0 (*)
|    |         +--- androidx.interpolator:interpolator:1.0.0
|    |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         \--- androidx.collection:collection:1.1.0 (*)
|    \--- androidx.drawerlayout:drawerlayout:1.0.0
|         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|         +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|         \--- androidx.customview:customview:1.0.0 (*)
+--- com.google.android.material:material:1.3.0
|    +--- androidx.annotation:annotation:1.0.1 -> 1.1.0
|    +--- androidx.appcompat:appcompat:1.1.0 -> 1.2.0 (*)
|    +--- androidx.cardview:cardview:1.0.0
|    |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    +--- androidx.coordinatorlayout:coordinatorlayout:1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    +--- androidx.customview:customview:1.0.0 (*)
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.constraintlayout:constraintlayout:2.0.1
|    |    +--- androidx.appcompat:appcompat:1.2.0 (*)
|    |    +--- androidx.core:core:1.3.1 (*)
|    |    \--- androidx.constraintlayout:constraintlayout-solver:2.0.1
|    +--- androidx.core:core:1.2.0 -> 1.3.1 (*)
|    +--- androidx.dynamicanimation:dynamicanimation:1.0.0
|    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    +--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    |    \--- androidx.legacy:legacy-support-core-utils:1.0.0
|    |         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |         +--- androidx.documentfile:documentfile:1.0.0
|    |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         +--- androidx.loader:loader:1.0.0 (*)
|    |         +--- androidx.localbroadcastmanager:localbroadcastmanager:1.0.0
|    |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         \--- androidx.print:print:1.0.0
|    |              \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    +--- androidx.annotation:annotation-experimental:1.0.0
|    +--- androidx.fragment:fragment:1.0.0 -> 1.1.0 (*)
|    +--- androidx.lifecycle:lifecycle-runtime:2.0.0 -> 2.2.0 (*)
|    +--- androidx.recyclerview:recyclerview:1.0.0 -> 1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    +--- androidx.customview:customview:1.0.0 (*)
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.transition:transition:1.2.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.0.1 -> 1.3.1 (*)
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.vectordrawable:vectordrawable:1.1.0 (*)
|    \--- androidx.viewpager2:viewpager2:1.0.0
|         +--- androidx.annotation:annotation:1.1.0
|         +--- androidx.fragment:fragment:1.1.0 (*)
|         +--- androidx.recyclerview:recyclerview:1.1.0 (*)
|         +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|         \--- androidx.collection:collection:1.1.0 (*)
+--- androidx.appcompat:appcompat:{strictly 1.2.0} -> 1.2.0 (c)
+--- com.google.android.material:material:{strictly 1.3.0} -> 1.3.0 (c)
+--- io.flutter:flutter_embedding_debug:{strictly 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8} -> 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8 (c)
+--- io.flutter:armeabi_v7a_debug:{strictly 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8} -> 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8 (c)
+--- io.flutter:arm64_v8a_debug:{strictly 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8} -> 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8 (c)
+--- io.flutter:x86_64_debug:{strictly 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8} -> 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8 (c)
+--- io.flutter:x86_debug:{strictly 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8} -> 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8 (c)
+--- androidx.annotation:annotation:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.core:core:{strictly 1.3.1} -> 1.3.1 (c)
+--- androidx.cursoradapter:cursoradapter:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.fragment:fragment:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.appcompat:appcompat-resources:{strictly 1.2.0} -> 1.2.0 (c)
+--- androidx.drawerlayout:drawerlayout:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.cardview:cardview:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.coordinatorlayout:coordinatorlayout:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.constraintlayout:constraintlayout:{strictly 2.0.1} -> 2.0.1 (c)
+--- androidx.dynamicanimation:dynamicanimation:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.annotation:annotation-experimental:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.lifecycle:lifecycle-runtime:{strictly 2.2.0} -> 2.2.0 (c)
+--- androidx.recyclerview:recyclerview:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.transition:transition:{strictly 1.2.0} -> 1.2.0 (c)
+--- androidx.vectordrawable:vectordrawable:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.viewpager2:viewpager2:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.lifecycle:lifecycle-common:{strictly 2.2.0} -> 2.2.0 (c)
+--- androidx.lifecycle:lifecycle-common-java8:{strictly 2.2.0} -> 2.2.0 (c)
+--- androidx.versionedparcelable:versionedparcelable:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.collection:collection:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.viewpager:viewpager:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.loader:loader:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.activity:activity:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.lifecycle:lifecycle-viewmodel:{strictly 2.1.0} -> 2.1.0 (c)
+--- androidx.vectordrawable:vectordrawable-animated:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.customview:customview:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.constraintlayout:constraintlayout-solver:{strictly 2.0.1} -> 2.0.1 (c)
+--- androidx.legacy:legacy-support-core-utils:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.arch.core:core-common:{strictly 2.1.0} -> 2.1.0 (c)
+--- androidx.lifecycle:lifecycle-livedata:{strictly 2.0.0} -> 2.0.0 (c)
+--- androidx.savedstate:savedstate:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.interpolator:interpolator:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.documentfile:documentfile:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.localbroadcastmanager:localbroadcastmanager:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.print:print:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.arch.core:core-runtime:{strictly 2.0.0} -> 2.0.0 (c)
\--- androidx.lifecycle:lifecycle-livedata-core:{strictly 2.0.0} -> 2.0.0 (c)

debugCompileOnly - Compile only dependencies for 'debug' sources. (n)
No dependencies

debugImplementation - Implementation only dependencies for 'debug' sources. (n)
No dependencies

debugProvided - Provided dependencies for 'debug' sources (deprecated: use 'debugCompileOnly' instead). (n)
No dependencies

debugPublish - Publish dependencies for 'debug' sources (deprecated: use 'debugRuntimeOnly' instead). (n)
No dependencies

debugRuntimeClasspath - Resolved configuration for runtime for variant: debug
+--- project :flutter
|    +--- io.flutter:flutter_embedding_debug:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
|    |    +--- androidx.lifecycle:lifecycle-common:2.2.0
|    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.lifecycle:lifecycle-common-java8:2.2.0
|    |    |    +--- androidx.lifecycle:lifecycle-common:2.2.0 (*)
|    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.lifecycle:lifecycle-runtime:2.2.0
|    |    |    +--- androidx.lifecycle:lifecycle-common:2.2.0 (*)
|    |    |    +--- androidx.arch.core:core-common:2.1.0
|    |    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.fragment:fragment:1.1.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.core:core:1.1.0 -> 1.3.1
|    |    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    |    +--- androidx.lifecycle:lifecycle-runtime:2.0.0 -> 2.2.0 (*)
|    |    |    |    +--- androidx.versionedparcelable:versionedparcelable:1.1.0
|    |    |    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    |    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0
|    |    |    |    |         \--- androidx.annotation:annotation:1.1.0
|    |    |    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    |    |    +--- androidx.collection:collection:1.1.0 (*)
|    |    |    +--- androidx.viewpager:viewpager:1.0.0
|    |    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    |    |    \--- androidx.customview:customview:1.0.0
|    |    |    |         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    |         \--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    |    +--- androidx.loader:loader:1.0.0
|    |    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    |    |    +--- androidx.lifecycle:lifecycle-livedata:2.0.0
|    |    |    |    |    +--- androidx.arch.core:core-runtime:2.0.0
|    |    |    |    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    |    +--- androidx.lifecycle:lifecycle-livedata-core:2.0.0
|    |    |    |    |    |    +--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.2.0 (*)
|    |    |    |    |    |    +--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    |    |    \--- androidx.arch.core:core-runtime:2.0.0 (*)
|    |    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0
|    |    |    |         \--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.activity:activity:1.0.0
|    |    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    |    |    +--- androidx.lifecycle:lifecycle-runtime:2.1.0 -> 2.2.0 (*)
|    |    |    |    +--- androidx.lifecycle:lifecycle-viewmodel:2.1.0 (*)
|    |    |    |    \--- androidx.savedstate:savedstate:1.0.0
|    |    |    |         +--- androidx.annotation:annotation:1.1.0
|    |    |    |         +--- androidx.arch.core:core-common:2.0.1 -> 2.1.0 (*)
|    |    |    |         \--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.2.0 (*)
|    |    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0 (*)
|    |    \--- androidx.annotation:annotation:1.1.0
|    +--- io.flutter:armeabi_v7a_debug:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
|    +--- io.flutter:arm64_v8a_debug:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
|    +--- io.flutter:x86_64_debug:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
|    \--- io.flutter:x86_debug:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
+--- androidx.appcompat:appcompat:1.2.0
|    +--- androidx.annotation:annotation:1.1.0
|    +--- androidx.core:core:1.3.0 -> 1.3.1 (*)
|    +--- androidx.cursoradapter:cursoradapter:1.0.0
|    |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    +--- androidx.fragment:fragment:1.1.0 (*)
|    +--- androidx.appcompat:appcompat-resources:1.2.0
|    |    +--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.0.1 -> 1.3.1 (*)
|    |    +--- androidx.vectordrawable:vectordrawable:1.1.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    |    \--- androidx.collection:collection:1.1.0 (*)
|    |    \--- androidx.vectordrawable:vectordrawable-animated:1.1.0
|    |         +--- androidx.vectordrawable:vectordrawable:1.1.0 (*)
|    |         +--- androidx.interpolator:interpolator:1.0.0
|    |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         \--- androidx.collection:collection:1.1.0 (*)
|    +--- androidx.drawerlayout:drawerlayout:1.0.0
|    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    \--- androidx.customview:customview:1.0.0 (*)
|    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
\--- com.google.android.material:material:1.3.0
     +--- androidx.annotation:annotation:1.0.1 -> 1.1.0
     +--- androidx.appcompat:appcompat:1.1.0 -> 1.2.0 (*)
     +--- androidx.cardview:cardview:1.0.0
     |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
     +--- androidx.coordinatorlayout:coordinatorlayout:1.1.0
     |    +--- androidx.annotation:annotation:1.1.0
     |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
     |    +--- androidx.customview:customview:1.0.0 (*)
     |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
     +--- androidx.constraintlayout:constraintlayout:2.0.1
     |    +--- androidx.appcompat:appcompat:1.2.0 (*)
     |    +--- androidx.core:core:1.3.1 (*)
     |    \--- androidx.constraintlayout:constraintlayout-solver:2.0.1
     +--- androidx.core:core:1.2.0 -> 1.3.1 (*)
     +--- androidx.dynamicanimation:dynamicanimation:1.0.0
     |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
     |    +--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
     |    \--- androidx.legacy:legacy-support-core-utils:1.0.0
     |         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
     |         +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
     |         +--- androidx.documentfile:documentfile:1.0.0
     |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
     |         +--- androidx.loader:loader:1.0.0 (*)
     |         +--- androidx.localbroadcastmanager:localbroadcastmanager:1.0.0
     |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
     |         \--- androidx.print:print:1.0.0
     |              \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
     +--- androidx.annotation:annotation-experimental:1.0.0
     +--- androidx.fragment:fragment:1.0.0 -> 1.1.0 (*)
     +--- androidx.lifecycle:lifecycle-runtime:2.0.0 -> 2.2.0 (*)
     +--- androidx.recyclerview:recyclerview:1.0.0 -> 1.1.0
     |    +--- androidx.annotation:annotation:1.1.0
     |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
     |    +--- androidx.customview:customview:1.0.0 (*)
     |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
     +--- androidx.transition:transition:1.2.0
     |    +--- androidx.annotation:annotation:1.1.0
     |    +--- androidx.core:core:1.0.1 -> 1.3.1 (*)
     |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
     +--- androidx.vectordrawable:vectordrawable:1.1.0 (*)
     \--- androidx.viewpager2:viewpager2:1.0.0
          +--- androidx.annotation:annotation:1.1.0
          +--- androidx.fragment:fragment:1.1.0 (*)
          +--- androidx.recyclerview:recyclerview:1.1.0 (*)
          +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
          \--- androidx.collection:collection:1.1.0 (*)

debugRuntimeElements - Runtime elements for debug (n)
No dependencies

debugRuntimeOnly - Runtime only dependencies for 'debug' sources. (n)
No dependencies

debugRuntimePublication - Runtime publication for debug (n)
No dependencies

debugUnitTestAnnotationProcessorClasspath - Resolved configuration for annotation-processor for variant: debugUnitTest
No dependencies

debugUnitTestCompileClasspath - Resolved configuration for compilation for variant: debugUnitTest
+--- project :flutter
|    +--- io.flutter:flutter_embedding_debug:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
|    |    +--- androidx.lifecycle:lifecycle-common:2.2.0
|    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.lifecycle:lifecycle-common-java8:2.2.0
|    |    |    +--- androidx.lifecycle:lifecycle-common:2.2.0 (*)
|    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.lifecycle:lifecycle-runtime:2.2.0
|    |    |    +--- androidx.lifecycle:lifecycle-common:2.2.0 (*)
|    |    |    +--- androidx.arch.core:core-common:2.1.0
|    |    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.fragment:fragment:1.1.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.core:core:1.1.0 -> 1.3.1
|    |    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    |    +--- androidx.lifecycle:lifecycle-runtime:2.0.0 -> 2.2.0 (*)
|    |    |    |    \--- androidx.versionedparcelable:versionedparcelable:1.1.0
|    |    |    |         +--- androidx.annotation:annotation:1.1.0
|    |    |    |         \--- androidx.collection:collection:1.0.0 -> 1.1.0
|    |    |    |              \--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.collection:collection:1.1.0 (*)
|    |    |    +--- androidx.viewpager:viewpager:1.0.0
|    |    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    |    |    \--- androidx.customview:customview:1.0.0
|    |    |    |         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    |         \--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    |    +--- androidx.loader:loader:1.0.0
|    |    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    |    |    +--- androidx.lifecycle:lifecycle-livedata:2.0.0
|    |    |    |    |    +--- androidx.arch.core:core-runtime:2.0.0
|    |    |    |    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    |    +--- androidx.lifecycle:lifecycle-livedata-core:2.0.0
|    |    |    |    |    |    +--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.2.0 (*)
|    |    |    |    |    |    +--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    |    |    \--- androidx.arch.core:core-runtime:2.0.0 (*)
|    |    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0
|    |    |    |         \--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.activity:activity:1.0.0
|    |    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    |    |    +--- androidx.lifecycle:lifecycle-runtime:2.1.0 -> 2.2.0 (*)
|    |    |    |    +--- androidx.lifecycle:lifecycle-viewmodel:2.1.0 (*)
|    |    |    |    \--- androidx.savedstate:savedstate:1.0.0
|    |    |    |         +--- androidx.annotation:annotation:1.1.0
|    |    |    |         +--- androidx.arch.core:core-common:2.0.1 -> 2.1.0 (*)
|    |    |    |         \--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.2.0 (*)
|    |    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0 (*)
|    |    \--- androidx.annotation:annotation:1.1.0
|    +--- io.flutter:armeabi_v7a_debug:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
|    +--- io.flutter:arm64_v8a_debug:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
|    +--- io.flutter:x86_64_debug:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
|    \--- io.flutter:x86_debug:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
+--- androidx.appcompat:appcompat:1.2.0
|    +--- androidx.annotation:annotation:1.1.0
|    +--- androidx.core:core:1.3.0 -> 1.3.1 (*)
|    +--- androidx.cursoradapter:cursoradapter:1.0.0
|    |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    +--- androidx.fragment:fragment:1.1.0 (*)
|    +--- androidx.appcompat:appcompat-resources:1.2.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.0.1 -> 1.3.1 (*)
|    |    +--- androidx.vectordrawable:vectordrawable:1.1.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    |    \--- androidx.collection:collection:1.1.0 (*)
|    |    \--- androidx.vectordrawable:vectordrawable-animated:1.1.0
|    |         +--- androidx.vectordrawable:vectordrawable:1.1.0 (*)
|    |         +--- androidx.interpolator:interpolator:1.0.0
|    |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         \--- androidx.collection:collection:1.1.0 (*)
|    \--- androidx.drawerlayout:drawerlayout:1.0.0
|         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|         +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|         \--- androidx.customview:customview:1.0.0 (*)
+--- com.google.android.material:material:1.3.0
|    +--- androidx.annotation:annotation:1.0.1 -> 1.1.0
|    +--- androidx.appcompat:appcompat:1.1.0 -> 1.2.0 (*)
|    +--- androidx.cardview:cardview:1.0.0
|    |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    +--- androidx.coordinatorlayout:coordinatorlayout:1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    +--- androidx.customview:customview:1.0.0 (*)
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.constraintlayout:constraintlayout:2.0.1
|    |    +--- androidx.appcompat:appcompat:1.2.0 (*)
|    |    +--- androidx.core:core:1.3.1 (*)
|    |    \--- androidx.constraintlayout:constraintlayout-solver:2.0.1
|    +--- androidx.core:core:1.2.0 -> 1.3.1 (*)
|    +--- androidx.dynamicanimation:dynamicanimation:1.0.0
|    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    +--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    |    \--- androidx.legacy:legacy-support-core-utils:1.0.0
|    |         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |         +--- androidx.documentfile:documentfile:1.0.0
|    |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         +--- androidx.loader:loader:1.0.0 (*)
|    |         +--- androidx.localbroadcastmanager:localbroadcastmanager:1.0.0
|    |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         \--- androidx.print:print:1.0.0
|    |              \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    +--- androidx.annotation:annotation-experimental:1.0.0
|    +--- androidx.fragment:fragment:1.0.0 -> 1.1.0 (*)
|    +--- androidx.lifecycle:lifecycle-runtime:2.0.0 -> 2.2.0 (*)
|    +--- androidx.recyclerview:recyclerview:1.0.0 -> 1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    +--- androidx.customview:customview:1.0.0 (*)
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.transition:transition:1.2.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.0.1 -> 1.3.1 (*)
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.vectordrawable:vectordrawable:1.1.0 (*)
|    \--- androidx.viewpager2:viewpager2:1.0.0
|         +--- androidx.annotation:annotation:1.1.0
|         +--- androidx.fragment:fragment:1.1.0 (*)
|         +--- androidx.recyclerview:recyclerview:1.1.0 (*)
|         +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|         \--- androidx.collection:collection:1.1.0 (*)
+--- androidx.appcompat:appcompat:{strictly 1.2.0} -> 1.2.0 (c)
+--- com.google.android.material:material:{strictly 1.3.0} -> 1.3.0 (c)
+--- io.flutter:flutter_embedding_debug:{strictly 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8} -> 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8 (c)
+--- io.flutter:armeabi_v7a_debug:{strictly 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8} -> 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8 (c)
+--- io.flutter:arm64_v8a_debug:{strictly 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8} -> 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8 (c)
+--- io.flutter:x86_64_debug:{strictly 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8} -> 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8 (c)
+--- io.flutter:x86_debug:{strictly 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8} -> 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8 (c)
+--- androidx.annotation:annotation:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.core:core:{strictly 1.3.1} -> 1.3.1 (c)
+--- androidx.cursoradapter:cursoradapter:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.fragment:fragment:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.appcompat:appcompat-resources:{strictly 1.2.0} -> 1.2.0 (c)
+--- androidx.drawerlayout:drawerlayout:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.cardview:cardview:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.coordinatorlayout:coordinatorlayout:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.constraintlayout:constraintlayout:{strictly 2.0.1} -> 2.0.1 (c)
+--- androidx.dynamicanimation:dynamicanimation:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.annotation:annotation-experimental:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.lifecycle:lifecycle-runtime:{strictly 2.2.0} -> 2.2.0 (c)
+--- androidx.recyclerview:recyclerview:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.transition:transition:{strictly 1.2.0} -> 1.2.0 (c)
+--- androidx.vectordrawable:vectordrawable:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.viewpager2:viewpager2:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.lifecycle:lifecycle-common:{strictly 2.2.0} -> 2.2.0 (c)
+--- androidx.lifecycle:lifecycle-common-java8:{strictly 2.2.0} -> 2.2.0 (c)
+--- androidx.versionedparcelable:versionedparcelable:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.collection:collection:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.viewpager:viewpager:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.loader:loader:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.activity:activity:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.lifecycle:lifecycle-viewmodel:{strictly 2.1.0} -> 2.1.0 (c)
+--- androidx.vectordrawable:vectordrawable-animated:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.customview:customview:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.constraintlayout:constraintlayout-solver:{strictly 2.0.1} -> 2.0.1 (c)
+--- androidx.legacy:legacy-support-core-utils:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.arch.core:core-common:{strictly 2.1.0} -> 2.1.0 (c)
+--- androidx.lifecycle:lifecycle-livedata:{strictly 2.0.0} -> 2.0.0 (c)
+--- androidx.savedstate:savedstate:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.interpolator:interpolator:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.documentfile:documentfile:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.localbroadcastmanager:localbroadcastmanager:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.print:print:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.arch.core:core-runtime:{strictly 2.0.0} -> 2.0.0 (c)
\--- androidx.lifecycle:lifecycle-livedata-core:{strictly 2.0.0} -> 2.0.0 (c)

debugUnitTestRuntimeClasspath - Resolved configuration for runtime for variant: debugUnitTest
+--- project :flutter
|    +--- io.flutter:flutter_embedding_debug:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
|    |    +--- androidx.lifecycle:lifecycle-common:2.2.0
|    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.lifecycle:lifecycle-common-java8:2.2.0
|    |    |    +--- androidx.lifecycle:lifecycle-common:2.2.0 (*)
|    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.lifecycle:lifecycle-runtime:2.2.0
|    |    |    +--- androidx.lifecycle:lifecycle-common:2.2.0 (*)
|    |    |    +--- androidx.arch.core:core-common:2.1.0
|    |    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.fragment:fragment:1.1.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.core:core:1.1.0 -> 1.3.1
|    |    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    |    +--- androidx.lifecycle:lifecycle-runtime:2.0.0 -> 2.2.0 (*)
|    |    |    |    +--- androidx.versionedparcelable:versionedparcelable:1.1.0
|    |    |    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    |    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0
|    |    |    |    |         \--- androidx.annotation:annotation:1.1.0
|    |    |    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    |    |    +--- androidx.collection:collection:1.1.0 (*)
|    |    |    +--- androidx.viewpager:viewpager:1.0.0
|    |    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    |    |    \--- androidx.customview:customview:1.0.0
|    |    |    |         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    |         \--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    |    +--- androidx.loader:loader:1.0.0
|    |    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    |    |    +--- androidx.lifecycle:lifecycle-livedata:2.0.0
|    |    |    |    |    +--- androidx.arch.core:core-runtime:2.0.0
|    |    |    |    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    |    +--- androidx.lifecycle:lifecycle-livedata-core:2.0.0
|    |    |    |    |    |    +--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.2.0 (*)
|    |    |    |    |    |    +--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    |    |    \--- androidx.arch.core:core-runtime:2.0.0 (*)
|    |    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0
|    |    |    |         \--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.activity:activity:1.0.0
|    |    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    |    |    +--- androidx.lifecycle:lifecycle-runtime:2.1.0 -> 2.2.0 (*)
|    |    |    |    +--- androidx.lifecycle:lifecycle-viewmodel:2.1.0 (*)
|    |    |    |    \--- androidx.savedstate:savedstate:1.0.0
|    |    |    |         +--- androidx.annotation:annotation:1.1.0
|    |    |    |         +--- androidx.arch.core:core-common:2.0.1 -> 2.1.0 (*)
|    |    |    |         \--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.2.0 (*)
|    |    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0 (*)
|    |    \--- androidx.annotation:annotation:1.1.0
|    +--- io.flutter:armeabi_v7a_debug:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
|    +--- io.flutter:arm64_v8a_debug:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
|    +--- io.flutter:x86_64_debug:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
|    \--- io.flutter:x86_debug:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
+--- androidx.appcompat:appcompat:1.2.0
|    +--- androidx.annotation:annotation:1.1.0
|    +--- androidx.core:core:1.3.0 -> 1.3.1 (*)
|    +--- androidx.cursoradapter:cursoradapter:1.0.0
|    |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    +--- androidx.fragment:fragment:1.1.0 (*)
|    +--- androidx.appcompat:appcompat-resources:1.2.0
|    |    +--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.0.1 -> 1.3.1 (*)
|    |    +--- androidx.vectordrawable:vectordrawable:1.1.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    |    \--- androidx.collection:collection:1.1.0 (*)
|    |    \--- androidx.vectordrawable:vectordrawable-animated:1.1.0
|    |         +--- androidx.vectordrawable:vectordrawable:1.1.0 (*)
|    |         +--- androidx.interpolator:interpolator:1.0.0
|    |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         \--- androidx.collection:collection:1.1.0 (*)
|    +--- androidx.drawerlayout:drawerlayout:1.0.0
|    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    \--- androidx.customview:customview:1.0.0 (*)
|    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
\--- com.google.android.material:material:1.3.0
     +--- androidx.annotation:annotation:1.0.1 -> 1.1.0
     +--- androidx.appcompat:appcompat:1.1.0 -> 1.2.0 (*)
     +--- androidx.cardview:cardview:1.0.0
     |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
     +--- androidx.coordinatorlayout:coordinatorlayout:1.1.0
     |    +--- androidx.annotation:annotation:1.1.0
     |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
     |    +--- androidx.customview:customview:1.0.0 (*)
     |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
     +--- androidx.constraintlayout:constraintlayout:2.0.1
     |    +--- androidx.appcompat:appcompat:1.2.0 (*)
     |    +--- androidx.core:core:1.3.1 (*)
     |    \--- androidx.constraintlayout:constraintlayout-solver:2.0.1
     +--- androidx.core:core:1.2.0 -> 1.3.1 (*)
     +--- androidx.dynamicanimation:dynamicanimation:1.0.0
     |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
     |    +--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
     |    \--- androidx.legacy:legacy-support-core-utils:1.0.0
     |         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
     |         +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
     |         +--- androidx.documentfile:documentfile:1.0.0
     |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
     |         +--- androidx.loader:loader:1.0.0 (*)
     |         +--- androidx.localbroadcastmanager:localbroadcastmanager:1.0.0
     |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
     |         \--- androidx.print:print:1.0.0
     |              \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
     +--- androidx.annotation:annotation-experimental:1.0.0
     +--- androidx.fragment:fragment:1.0.0 -> 1.1.0 (*)
     +--- androidx.lifecycle:lifecycle-runtime:2.0.0 -> 2.2.0 (*)
     +--- androidx.recyclerview:recyclerview:1.0.0 -> 1.1.0
     |    +--- androidx.annotation:annotation:1.1.0
     |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
     |    +--- androidx.customview:customview:1.0.0 (*)
     |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
     +--- androidx.transition:transition:1.2.0
     |    +--- androidx.annotation:annotation:1.1.0
     |    +--- androidx.core:core:1.0.1 -> 1.3.1 (*)
     |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
     +--- androidx.vectordrawable:vectordrawable:1.1.0 (*)
     \--- androidx.viewpager2:viewpager2:1.0.0
          +--- androidx.annotation:annotation:1.1.0
          +--- androidx.fragment:fragment:1.1.0 (*)
          +--- androidx.recyclerview:recyclerview:1.1.0 (*)
          +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
          \--- androidx.collection:collection:1.1.0 (*)

debugWearApp - Link to a wear app to embed for object 'debug'. (n)
No dependencies

default - Configuration for default artifacts.
No dependencies

implementation - Implementation only dependencies for 'main' sources. (n)
+--- androidx.appcompat:appcompat:1.2.0 (n)
\--- com.google.android.material:material:1.3.0 (n)

lintChecks - Configuration to apply external lint check jar
No dependencies

lintClassPath - The lint embedded classpath
\--- com.android.tools.lint:lint-gradle:27.0.1
     +--- com.android.tools:sdk-common:27.0.1
     |    +--- com.android.tools:sdklib:27.0.1
     |    |    +--- com.android.tools.layoutlib:layoutlib-api:27.0.1
     |    |    |    +--- com.android.tools:common:27.0.1
     |    |    |    |    +--- com.android.tools:annotations:27.0.1
     |    |    |    |    +--- com.google.guava:guava:28.1-jre
     |    |    |    |    |    +--- com.google.guava:failureaccess:1.0.1
     |    |    |    |    |    +--- com.google.guava:listenablefuture:9999.0-empty-to-avoid-conflict-with-guava
     |    |    |    |    |    +--- com.google.code.findbugs:jsr305:3.0.2
     |    |    |    |    |    +--- org.checkerframework:checker-qual:2.8.1
     |    |    |    |    |    +--- com.google.errorprone:error_prone_annotations:2.3.2
     |    |    |    |    |    +--- com.google.j2objc:j2objc-annotations:1.3
     |    |    |    |    |    \--- org.codehaus.mojo:animal-sniffer-annotations:1.18
     |    |    |    |    \--- org.jetbrains.kotlin:kotlin-stdlib-jdk8:1.3.72
     |    |    |    |         +--- org.jetbrains.kotlin:kotlin-stdlib:1.3.72
     |    |    |    |         |    +--- org.jetbrains.kotlin:kotlin-stdlib-common:1.3.72
     |    |    |    |         |    \--- org.jetbrains:annotations:13.0
     |    |    |    |         \--- org.jetbrains.kotlin:kotlin-stdlib-jdk7:1.3.72
     |    |    |    |              \--- org.jetbrains.kotlin:kotlin-stdlib:1.3.72 (*)
     |    |    |    +--- net.sf.kxml:kxml2:2.3.0
     |    |    |    +--- com.android.tools:annotations:27.0.1
     |    |    |    \--- org.jetbrains:annotations:13.0
     |    |    +--- com.android.tools:dvlib:27.0.1
     |    |    |    \--- com.android.tools:common:27.0.1 (*)
     |    |    +--- com.android.tools:repository:27.0.1
     |    |    |    +--- com.android.tools:common:27.0.1 (*)
     |    |    |    +--- com.sun.activation:javax.activation:1.2.0
     |    |    |    +--- org.apache.commons:commons-compress:1.12
     |    |    |    +--- org.glassfish.jaxb:jaxb-runtime:2.3.1
     |    |    |    |    +--- javax.xml.bind:jaxb-api:2.3.1
     |    |    |    |    |    \--- javax.activation:javax.activation-api:1.2.0
     |    |    |    |    +--- org.glassfish.jaxb:txw2:2.3.1
     |    |    |    |    +--- com.sun.istack:istack-commons-runtime:3.0.7
     |    |    |    |    +--- org.jvnet.staxex:stax-ex:1.8
     |    |    |    |    +--- com.sun.xml.fastinfoset:FastInfoset:1.2.15
     |    |    |    |    \--- javax.activation:javax.activation-api:1.2.0
     |    |    |    +--- com.google.jimfs:jimfs:1.1
     |    |    |    |    \--- com.google.guava:guava:18.0 -> 28.1-jre (*)
     |    |    |    \--- org.jetbrains.kotlin:kotlin-stdlib-jdk8:1.3.72 (*)
     |    |    +--- com.google.code.gson:gson:2.8.5
     |    |    +--- org.apache.commons:commons-compress:1.12
     |    |    +--- org.apache.httpcomponents:httpmime:4.5.6
     |    |    |    \--- org.apache.httpcomponents:httpclient:4.5.6
     |    |    |         +--- org.apache.httpcomponents:httpcore:4.4.10
     |    |    |         +--- commons-logging:commons-logging:1.2
     |    |    |         \--- commons-codec:commons-codec:1.10
     |    |    \--- org.apache.httpcomponents:httpcore:4.4.10
     |    +--- com.android.tools.build:builder-test-api:4.0.1
     |    |    \--- com.android.tools.ddms:ddmlib:27.0.1
     |    |         +--- com.android.tools:common:27.0.1 (*)
     |    |         \--- net.sf.kxml:kxml2:2.3.0
     |    +--- com.android.tools.build:builder-model:4.0.1
     |    |    \--- com.android.tools:annotations:27.0.1
     |    +--- com.android.tools.ddms:ddmlib:27.0.1 (*)
     |    +--- com.android.tools.analytics-library:shared:27.0.1
     |    |    +--- com.android.tools.analytics-library:protos:27.0.1
     |    |    |    \--- com.google.protobuf:protobuf-java:3.10.0
     |    |    +--- com.android.tools:annotations:27.0.1
     |    |    +--- com.android.tools:common:27.0.1 (*)
     |    |    +--- com.google.guava:guava:28.1-jre (*)
     |    |    +--- com.google.code.gson:gson:2.8.5
     |    |    \--- org.jetbrains.kotlin:kotlin-stdlib-jdk8:1.3.72 (*)
     |    +--- org.bouncycastle:bcpkix-jdk15on:1.56
     |    |    \--- org.bouncycastle:bcprov-jdk15on:1.56
     |    +--- org.bouncycastle:bcprov-jdk15on:1.56
     |    +--- org.jetbrains.kotlin:kotlin-stdlib-jdk8:1.3.72 (*)
     |    +--- org.jetbrains.kotlin:kotlin-reflect:1.3.72
     |    |    \--- org.jetbrains.kotlin:kotlin-stdlib:1.3.72 (*)
     |    +--- com.google.protobuf:protobuf-java:3.10.0
     |    +--- javax.inject:javax.inject:1
     |    +--- org.jetbrains.trove4j:trove4j:20160824
     |    \--- com.android.tools.build:aapt2-proto:0.4.0
     |         \--- com.google.protobuf:protobuf-java:3.4.0 -> 3.10.0
     +--- com.android.tools.build:builder:4.0.1
     |    +--- com.android.tools.build:builder-model:4.0.1 (*)
     |    +--- com.android.tools.build:builder-test-api:4.0.1 (*)
     |    +--- com.android.tools:sdklib:27.0.1 (*)
     |    +--- com.android.tools:sdk-common:27.0.1 (*)
     |    +--- com.android.tools:common:27.0.1 (*)
     |    +--- com.android.tools.build:manifest-merger:27.0.1
     |    |    +--- com.android.tools:common:27.0.1 (*)
     |    |    +--- com.android.tools:sdklib:27.0.1 (*)
     |    |    +--- com.android.tools:sdk-common:27.0.1 (*)
     |    |    +--- com.google.code.gson:gson:2.8.5
     |    |    +--- org.jetbrains.kotlin:kotlin-stdlib-jdk8:1.3.72 (*)
     |    |    \--- net.sf.kxml:kxml2:2.3.0
     |    +--- com.android.tools.ddms:ddmlib:27.0.1 (*)
     |    +--- com.android:zipflinger:4.0.1
     |    |    +--- com.google.guava:guava:27.0.1-jre -> 28.1-jre (*)
     |    |    \--- com.android.tools:common:27.0.1 (*)
     |    +--- com.android:signflinger:4.0.1
     |    |    +--- com.android.tools.build:apksig:4.0.1
     |    |    \--- com.android:zipflinger:4.0.1 (*)
     |    +--- com.android.tools.analytics-library:protos:27.0.1 (*)
     |    +--- com.android.tools.analytics-library:tracker:27.0.1
     |    |    +--- com.android.tools:annotations:27.0.1
     |    |    +--- com.android.tools:common:27.0.1 (*)
     |    |    +--- com.android.tools.analytics-library:protos:27.0.1 (*)
     |    |    +--- com.android.tools.analytics-library:shared:27.0.1 (*)
     |    |    +--- com.google.protobuf:protobuf-java:3.10.0
     |    |    +--- com.google.guava:guava:28.1-jre (*)
     |    |    \--- org.jetbrains.kotlin:kotlin-stdlib-jdk8:1.3.72 (*)
     |    +--- com.android.tools.build:apksig:4.0.1
     |    +--- com.android.tools.build:apkzlib:4.0.1
     |    |    +--- com.google.code.findbugs:jsr305:1.3.9 -> 3.0.2
     |    |    +--- com.google.guava:guava:23.0 -> 28.1-jre (*)
     |    |    +--- org.bouncycastle:bcpkix-jdk15on:1.56 (*)
     |    |    +--- org.bouncycastle:bcprov-jdk15on:1.56
     |    |    \--- com.android.tools.build:apksig:4.0.1
     |    +--- org.jetbrains.kotlin:kotlin-stdlib-jdk8:1.3.72 (*)
     |    +--- com.squareup:javawriter:2.5.0
     |    +--- org.bouncycastle:bcpkix-jdk15on:1.56 (*)
     |    +--- org.bouncycastle:bcprov-jdk15on:1.56
     |    +--- org.ow2.asm:asm:7.0
     |    +--- org.ow2.asm:asm-tree:7.0
     |    |    \--- org.ow2.asm:asm:7.0
     |    +--- javax.inject:javax.inject:1
     |    +--- org.ow2.asm:asm-commons:7.0
     |    |    +--- org.ow2.asm:asm:7.0
     |    |    +--- org.ow2.asm:asm-tree:7.0 (*)
     |    |    \--- org.ow2.asm:asm-analysis:7.0
     |    |         \--- org.ow2.asm:asm-tree:7.0 (*)
     |    +--- org.ow2.asm:asm-util:7.0
     |    |    +--- org.ow2.asm:asm:7.0
     |    |    +--- org.ow2.asm:asm-tree:7.0 (*)
     |    |    \--- org.ow2.asm:asm-analysis:7.0 (*)
     |    +--- it.unimi.dsi:fastutil:7.2.0
     |    +--- net.sf.jopt-simple:jopt-simple:4.9
     |    \--- com.googlecode.json-simple:json-simple:1.1
     +--- com.android.tools.build:builder-model:4.0.1 (*)
     +--- com.android.tools.external.com-intellij:intellij-core:27.0.1
     |    \--- org.jetbrains.trove4j:trove4j:20160824
     +--- com.android.tools.external.com-intellij:kotlin-compiler:27.0.1
     +--- com.android.tools.external.org-jetbrains:uast:27.0.1
     +--- com.android.tools.build:manifest-merger:27.0.1 (*)
     +--- com.android.tools.lint:lint:27.0.1
     |    +--- com.android.tools.lint:lint-checks:27.0.1
     |    |    +--- com.android.tools.lint:lint-api:27.0.1
     |    |    |    +--- com.android.tools:sdk-common:27.0.1 (*)
     |    |    |    +--- com.android.tools.build:builder-model:4.0.1 (*)
     |    |    |    +--- com.google.guava:guava:28.1-jre (*)
     |    |    |    +--- com.android.tools.external.com-intellij:intellij-core:27.0.1 (*)
     |    |    |    +--- com.android.tools.external.com-intellij:kotlin-compiler:27.0.1
     |    |    |    +--- com.android.tools.external.org-jetbrains:uast:27.0.1
     |    |    |    +--- com.android.tools.build:manifest-merger:27.0.1 (*)
     |    |    |    +--- org.ow2.asm:asm:7.0
     |    |    |    +--- org.ow2.asm:asm-tree:7.0 (*)
     |    |    |    +--- org.jetbrains.kotlin:kotlin-reflect:1.3.72 (*)
     |    |    |    \--- org.jetbrains.kotlin:kotlin-stdlib-jdk8:1.3.72 (*)
     |    |    +--- com.google.guava:guava:28.1-jre (*)
     |    |    +--- com.android.tools.external.com-intellij:intellij-core:27.0.1 (*)
     |    |    +--- com.android.tools.external.com-intellij:kotlin-compiler:27.0.1
     |    |    +--- com.android.tools.external.org-jetbrains:uast:27.0.1
     |    |    \--- org.ow2.asm:asm-analysis:7.0 (*)
     |    +--- com.google.guava:guava:28.1-jre (*)
     |    +--- com.android.tools.external.org-jetbrains:uast:27.0.1
     |    +--- com.android.tools.external.com-intellij:kotlin-compiler:27.0.1
     |    +--- com.android.tools.build:manifest-merger:27.0.1 (*)
     |    +--- com.android.tools.analytics-library:shared:27.0.1 (*)
     |    +--- com.android.tools.analytics-library:protos:27.0.1 (*)
     |    +--- com.android.tools.analytics-library:tracker:27.0.1 (*)
     |    +--- org.jetbrains.kotlin:kotlin-reflect:1.3.72 (*)
     |    \--- org.jetbrains.kotlin:kotlin-stdlib-jdk8:1.3.72 (*)
     +--- com.android.tools.lint:lint-gradle-api:27.0.1
     |    +--- com.android.tools:sdklib:27.0.1 (*)
     |    +--- com.android.tools.build:builder-model:4.0.1 (*)
     |    +--- com.android.tools.build:gradle-api:4.0.1
     |    |    +--- com.android.tools.build:builder-test-api:4.0.1 (*)
     |    |    +--- com.google.guava:guava:28.1-jre (*)
     |    |    \--- org.jetbrains.kotlin:kotlin-stdlib-jdk8:1.3.72 (*)
     |    +--- org.jetbrains.kotlin:kotlin-reflect:1.3.72 (*)
     |    +--- org.jetbrains.kotlin:kotlin-stdlib-jdk8:1.3.72 (*)
     |    \--- com.google.guava:guava:28.1-jre (*)
     +--- com.android:zipflinger:4.0.1 (*)
     +--- org.codehaus.groovy:groovy-all:2.4.15
     +--- org.jetbrains.kotlin:kotlin-reflect:1.3.72 (*)
     \--- org.jetbrains.kotlin:kotlin-stdlib-jdk8:1.3.72 (*)

lintPublish - Configuration to publish external lint check jar
No dependencies

provided - Provided dependencies for 'main' sources (deprecated: use 'compileOnly' instead). (n)
No dependencies

publish - Publish dependencies for 'main' sources (deprecated: use 'runtimeOnly' instead). (n)
No dependencies

releaseAllApiPublication - All API publication for release (n)
No dependencies

releaseAllRuntimePublication - All runtime publication for release (n)
No dependencies

releaseAnnotationProcessor - Classpath for the annotation processor for 'release'. (n)
No dependencies

releaseAnnotationProcessorClasspath - Resolved configuration for annotation-processor for variant: release
No dependencies

releaseApi - API dependencies for 'release' sources. (n)
No dependencies

releaseApiElements - API elements for release (n)
No dependencies

releaseApiPublication - API publication for release (n)
No dependencies

releaseCompile - Compile dependencies for 'release' sources (deprecated: use 'releaseImplementation' instead). (n)
No dependencies

releaseCompileClasspath - Resolved configuration for compilation for variant: release
+--- project :flutter
|    +--- io.flutter:flutter_embedding_release:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
|    |    +--- androidx.lifecycle:lifecycle-common:2.2.0
|    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.lifecycle:lifecycle-common-java8:2.2.0
|    |    |    +--- androidx.lifecycle:lifecycle-common:2.2.0 (*)
|    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.lifecycle:lifecycle-runtime:2.2.0
|    |    |    +--- androidx.lifecycle:lifecycle-common:2.2.0 (*)
|    |    |    +--- androidx.arch.core:core-common:2.1.0
|    |    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.fragment:fragment:1.1.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.core:core:1.1.0 -> 1.3.1
|    |    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    |    +--- androidx.lifecycle:lifecycle-runtime:2.0.0 -> 2.2.0 (*)
|    |    |    |    \--- androidx.versionedparcelable:versionedparcelable:1.1.0
|    |    |    |         +--- androidx.annotation:annotation:1.1.0
|    |    |    |         \--- androidx.collection:collection:1.0.0 -> 1.1.0
|    |    |    |              \--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.collection:collection:1.1.0 (*)
|    |    |    +--- androidx.viewpager:viewpager:1.0.0
|    |    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    |    |    \--- androidx.customview:customview:1.0.0
|    |    |    |         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    |         \--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    |    +--- androidx.loader:loader:1.0.0
|    |    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    |    |    +--- androidx.lifecycle:lifecycle-livedata:2.0.0
|    |    |    |    |    +--- androidx.arch.core:core-runtime:2.0.0
|    |    |    |    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    |    +--- androidx.lifecycle:lifecycle-livedata-core:2.0.0
|    |    |    |    |    |    +--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.2.0 (*)
|    |    |    |    |    |    +--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    |    |    \--- androidx.arch.core:core-runtime:2.0.0 (*)
|    |    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0
|    |    |    |         \--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.activity:activity:1.0.0
|    |    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    |    |    +--- androidx.lifecycle:lifecycle-runtime:2.1.0 -> 2.2.0 (*)
|    |    |    |    +--- androidx.lifecycle:lifecycle-viewmodel:2.1.0 (*)
|    |    |    |    \--- androidx.savedstate:savedstate:1.0.0
|    |    |    |         +--- androidx.annotation:annotation:1.1.0
|    |    |    |         +--- androidx.arch.core:core-common:2.0.1 -> 2.1.0 (*)
|    |    |    |         \--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.2.0 (*)
|    |    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0 (*)
|    |    \--- androidx.annotation:annotation:1.1.0
|    +--- io.flutter:armeabi_v7a_release:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
|    +--- io.flutter:arm64_v8a_release:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
|    \--- io.flutter:x86_64_release:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
+--- androidx.appcompat:appcompat:1.2.0
|    +--- androidx.annotation:annotation:1.1.0
|    +--- androidx.core:core:1.3.0 -> 1.3.1 (*)
|    +--- androidx.cursoradapter:cursoradapter:1.0.0
|    |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    +--- androidx.fragment:fragment:1.1.0 (*)
|    +--- androidx.appcompat:appcompat-resources:1.2.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.0.1 -> 1.3.1 (*)
|    |    +--- androidx.vectordrawable:vectordrawable:1.1.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    |    \--- androidx.collection:collection:1.1.0 (*)
|    |    \--- androidx.vectordrawable:vectordrawable-animated:1.1.0
|    |         +--- androidx.vectordrawable:vectordrawable:1.1.0 (*)
|    |         +--- androidx.interpolator:interpolator:1.0.0
|    |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         \--- androidx.collection:collection:1.1.0 (*)
|    \--- androidx.drawerlayout:drawerlayout:1.0.0
|         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|         +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|         \--- androidx.customview:customview:1.0.0 (*)
+--- com.google.android.material:material:1.3.0
|    +--- androidx.annotation:annotation:1.0.1 -> 1.1.0
|    +--- androidx.appcompat:appcompat:1.1.0 -> 1.2.0 (*)
|    +--- androidx.cardview:cardview:1.0.0
|    |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    +--- androidx.coordinatorlayout:coordinatorlayout:1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    +--- androidx.customview:customview:1.0.0 (*)
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.constraintlayout:constraintlayout:2.0.1
|    |    +--- androidx.appcompat:appcompat:1.2.0 (*)
|    |    +--- androidx.core:core:1.3.1 (*)
|    |    \--- androidx.constraintlayout:constraintlayout-solver:2.0.1
|    +--- androidx.core:core:1.2.0 -> 1.3.1 (*)
|    +--- androidx.dynamicanimation:dynamicanimation:1.0.0
|    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    +--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    |    \--- androidx.legacy:legacy-support-core-utils:1.0.0
|    |         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |         +--- androidx.documentfile:documentfile:1.0.0
|    |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         +--- androidx.loader:loader:1.0.0 (*)
|    |         +--- androidx.localbroadcastmanager:localbroadcastmanager:1.0.0
|    |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         \--- androidx.print:print:1.0.0
|    |              \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    +--- androidx.annotation:annotation-experimental:1.0.0
|    +--- androidx.fragment:fragment:1.0.0 -> 1.1.0 (*)
|    +--- androidx.lifecycle:lifecycle-runtime:2.0.0 -> 2.2.0 (*)
|    +--- androidx.recyclerview:recyclerview:1.0.0 -> 1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    +--- androidx.customview:customview:1.0.0 (*)
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.transition:transition:1.2.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.0.1 -> 1.3.1 (*)
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.vectordrawable:vectordrawable:1.1.0 (*)
|    \--- androidx.viewpager2:viewpager2:1.0.0
|         +--- androidx.annotation:annotation:1.1.0
|         +--- androidx.fragment:fragment:1.1.0 (*)
|         +--- androidx.recyclerview:recyclerview:1.1.0 (*)
|         +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|         \--- androidx.collection:collection:1.1.0 (*)
+--- androidx.appcompat:appcompat:{strictly 1.2.0} -> 1.2.0 (c)
+--- com.google.android.material:material:{strictly 1.3.0} -> 1.3.0 (c)
+--- io.flutter:flutter_embedding_release:{strictly 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8} -> 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8 (c)
+--- io.flutter:armeabi_v7a_release:{strictly 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8} -> 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8 (c)
+--- io.flutter:arm64_v8a_release:{strictly 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8} -> 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8 (c)
+--- io.flutter:x86_64_release:{strictly 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8} -> 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8 (c)
+--- androidx.annotation:annotation:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.core:core:{strictly 1.3.1} -> 1.3.1 (c)
+--- androidx.cursoradapter:cursoradapter:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.fragment:fragment:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.appcompat:appcompat-resources:{strictly 1.2.0} -> 1.2.0 (c)
+--- androidx.drawerlayout:drawerlayout:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.cardview:cardview:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.coordinatorlayout:coordinatorlayout:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.constraintlayout:constraintlayout:{strictly 2.0.1} -> 2.0.1 (c)
+--- androidx.dynamicanimation:dynamicanimation:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.annotation:annotation-experimental:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.lifecycle:lifecycle-runtime:{strictly 2.2.0} -> 2.2.0 (c)
+--- androidx.recyclerview:recyclerview:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.transition:transition:{strictly 1.2.0} -> 1.2.0 (c)
+--- androidx.vectordrawable:vectordrawable:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.viewpager2:viewpager2:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.lifecycle:lifecycle-common:{strictly 2.2.0} -> 2.2.0 (c)
+--- androidx.lifecycle:lifecycle-common-java8:{strictly 2.2.0} -> 2.2.0 (c)
+--- androidx.versionedparcelable:versionedparcelable:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.collection:collection:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.viewpager:viewpager:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.loader:loader:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.activity:activity:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.lifecycle:lifecycle-viewmodel:{strictly 2.1.0} -> 2.1.0 (c)
+--- androidx.vectordrawable:vectordrawable-animated:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.customview:customview:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.constraintlayout:constraintlayout-solver:{strictly 2.0.1} -> 2.0.1 (c)
+--- androidx.legacy:legacy-support-core-utils:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.arch.core:core-common:{strictly 2.1.0} -> 2.1.0 (c)
+--- androidx.lifecycle:lifecycle-livedata:{strictly 2.0.0} -> 2.0.0 (c)
+--- androidx.savedstate:savedstate:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.interpolator:interpolator:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.documentfile:documentfile:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.localbroadcastmanager:localbroadcastmanager:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.print:print:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.arch.core:core-runtime:{strictly 2.0.0} -> 2.0.0 (c)
\--- androidx.lifecycle:lifecycle-livedata-core:{strictly 2.0.0} -> 2.0.0 (c)

releaseCompileOnly - Compile only dependencies for 'release' sources. (n)
No dependencies

releaseImplementation - Implementation only dependencies for 'release' sources. (n)
No dependencies

releaseProvided - Provided dependencies for 'release' sources (deprecated: use 'releaseCompileOnly' instead). (n)
No dependencies

releasePublish - Publish dependencies for 'release' sources (deprecated: use 'releaseRuntimeOnly' instead). (n)
No dependencies

releaseRuntimeClasspath - Resolved configuration for runtime for variant: release
+--- project :flutter
|    +--- io.flutter:flutter_embedding_release:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
|    |    +--- androidx.lifecycle:lifecycle-common:2.2.0
|    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.lifecycle:lifecycle-common-java8:2.2.0
|    |    |    +--- androidx.lifecycle:lifecycle-common:2.2.0 (*)
|    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.lifecycle:lifecycle-runtime:2.2.0
|    |    |    +--- androidx.lifecycle:lifecycle-common:2.2.0 (*)
|    |    |    +--- androidx.arch.core:core-common:2.1.0
|    |    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.fragment:fragment:1.1.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.core:core:1.1.0 -> 1.3.1
|    |    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    |    +--- androidx.lifecycle:lifecycle-runtime:2.0.0 -> 2.2.0 (*)
|    |    |    |    +--- androidx.versionedparcelable:versionedparcelable:1.1.0
|    |    |    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    |    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0
|    |    |    |    |         \--- androidx.annotation:annotation:1.1.0
|    |    |    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    |    |    +--- androidx.collection:collection:1.1.0 (*)
|    |    |    +--- androidx.viewpager:viewpager:1.0.0
|    |    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    |    |    \--- androidx.customview:customview:1.0.0
|    |    |    |         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    |         \--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    |    +--- androidx.loader:loader:1.0.0
|    |    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    |    |    +--- androidx.lifecycle:lifecycle-livedata:2.0.0
|    |    |    |    |    +--- androidx.arch.core:core-runtime:2.0.0
|    |    |    |    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    |    +--- androidx.lifecycle:lifecycle-livedata-core:2.0.0
|    |    |    |    |    |    +--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.2.0 (*)
|    |    |    |    |    |    +--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    |    |    \--- androidx.arch.core:core-runtime:2.0.0 (*)
|    |    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0
|    |    |    |         \--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.activity:activity:1.0.0
|    |    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    |    |    +--- androidx.lifecycle:lifecycle-runtime:2.1.0 -> 2.2.0 (*)
|    |    |    |    +--- androidx.lifecycle:lifecycle-viewmodel:2.1.0 (*)
|    |    |    |    \--- androidx.savedstate:savedstate:1.0.0
|    |    |    |         +--- androidx.annotation:annotation:1.1.0
|    |    |    |         +--- androidx.arch.core:core-common:2.0.1 -> 2.1.0 (*)
|    |    |    |         \--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.2.0 (*)
|    |    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0 (*)
|    |    \--- androidx.annotation:annotation:1.1.0
|    +--- io.flutter:armeabi_v7a_release:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
|    +--- io.flutter:arm64_v8a_release:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
|    \--- io.flutter:x86_64_release:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
+--- androidx.appcompat:appcompat:1.2.0
|    +--- androidx.annotation:annotation:1.1.0
|    +--- androidx.core:core:1.3.0 -> 1.3.1 (*)
|    +--- androidx.cursoradapter:cursoradapter:1.0.0
|    |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    +--- androidx.fragment:fragment:1.1.0 (*)
|    +--- androidx.appcompat:appcompat-resources:1.2.0
|    |    +--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.0.1 -> 1.3.1 (*)
|    |    +--- androidx.vectordrawable:vectordrawable:1.1.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    |    \--- androidx.collection:collection:1.1.0 (*)
|    |    \--- androidx.vectordrawable:vectordrawable-animated:1.1.0
|    |         +--- androidx.vectordrawable:vectordrawable:1.1.0 (*)
|    |         +--- androidx.interpolator:interpolator:1.0.0
|    |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         \--- androidx.collection:collection:1.1.0 (*)
|    +--- androidx.drawerlayout:drawerlayout:1.0.0
|    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    \--- androidx.customview:customview:1.0.0 (*)
|    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
\--- com.google.android.material:material:1.3.0
     +--- androidx.annotation:annotation:1.0.1 -> 1.1.0
     +--- androidx.appcompat:appcompat:1.1.0 -> 1.2.0 (*)
     +--- androidx.cardview:cardview:1.0.0
     |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
     +--- androidx.coordinatorlayout:coordinatorlayout:1.1.0
     |    +--- androidx.annotation:annotation:1.1.0
     |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
     |    +--- androidx.customview:customview:1.0.0 (*)
     |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
     +--- androidx.constraintlayout:constraintlayout:2.0.1
     |    +--- androidx.appcompat:appcompat:1.2.0 (*)
     |    +--- androidx.core:core:1.3.1 (*)
     |    \--- androidx.constraintlayout:constraintlayout-solver:2.0.1
     +--- androidx.core:core:1.2.0 -> 1.3.1 (*)
     +--- androidx.dynamicanimation:dynamicanimation:1.0.0
     |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
     |    +--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
     |    \--- androidx.legacy:legacy-support-core-utils:1.0.0
     |         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
     |         +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
     |         +--- androidx.documentfile:documentfile:1.0.0
     |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
     |         +--- androidx.loader:loader:1.0.0 (*)
     |         +--- androidx.localbroadcastmanager:localbroadcastmanager:1.0.0
     |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
     |         \--- androidx.print:print:1.0.0
     |              \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
     +--- androidx.annotation:annotation-experimental:1.0.0
     +--- androidx.fragment:fragment:1.0.0 -> 1.1.0 (*)
     +--- androidx.lifecycle:lifecycle-runtime:2.0.0 -> 2.2.0 (*)
     +--- androidx.recyclerview:recyclerview:1.0.0 -> 1.1.0
     |    +--- androidx.annotation:annotation:1.1.0
     |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
     |    +--- androidx.customview:customview:1.0.0 (*)
     |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
     +--- androidx.transition:transition:1.2.0
     |    +--- androidx.annotation:annotation:1.1.0
     |    +--- androidx.core:core:1.0.1 -> 1.3.1 (*)
     |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
     +--- androidx.vectordrawable:vectordrawable:1.1.0 (*)
     \--- androidx.viewpager2:viewpager2:1.0.0
          +--- androidx.annotation:annotation:1.1.0
          +--- androidx.fragment:fragment:1.1.0 (*)
          +--- androidx.recyclerview:recyclerview:1.1.0 (*)
          +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
          \--- androidx.collection:collection:1.1.0 (*)

releaseRuntimeElements - Runtime elements for release (n)
No dependencies

releaseRuntimeOnly - Runtime only dependencies for 'release' sources. (n)
No dependencies

releaseRuntimePublication - Runtime publication for release (n)
No dependencies

releaseUnitTestAnnotationProcessorClasspath - Resolved configuration for annotation-processor for variant: releaseUnitTest
No dependencies

releaseUnitTestCompileClasspath - Resolved configuration for compilation for variant: releaseUnitTest
+--- project :flutter
|    +--- io.flutter:flutter_embedding_release:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
|    |    +--- androidx.lifecycle:lifecycle-common:2.2.0
|    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.lifecycle:lifecycle-common-java8:2.2.0
|    |    |    +--- androidx.lifecycle:lifecycle-common:2.2.0 (*)
|    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.lifecycle:lifecycle-runtime:2.2.0
|    |    |    +--- androidx.lifecycle:lifecycle-common:2.2.0 (*)
|    |    |    +--- androidx.arch.core:core-common:2.1.0
|    |    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.fragment:fragment:1.1.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.core:core:1.1.0 -> 1.3.1
|    |    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    |    +--- androidx.lifecycle:lifecycle-runtime:2.0.0 -> 2.2.0 (*)
|    |    |    |    \--- androidx.versionedparcelable:versionedparcelable:1.1.0
|    |    |    |         +--- androidx.annotation:annotation:1.1.0
|    |    |    |         \--- androidx.collection:collection:1.0.0 -> 1.1.0
|    |    |    |              \--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.collection:collection:1.1.0 (*)
|    |    |    +--- androidx.viewpager:viewpager:1.0.0
|    |    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    |    |    \--- androidx.customview:customview:1.0.0
|    |    |    |         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    |         \--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    |    +--- androidx.loader:loader:1.0.0
|    |    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    |    |    +--- androidx.lifecycle:lifecycle-livedata:2.0.0
|    |    |    |    |    +--- androidx.arch.core:core-runtime:2.0.0
|    |    |    |    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    |    +--- androidx.lifecycle:lifecycle-livedata-core:2.0.0
|    |    |    |    |    |    +--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.2.0 (*)
|    |    |    |    |    |    +--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    |    |    \--- androidx.arch.core:core-runtime:2.0.0 (*)
|    |    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0
|    |    |    |         \--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.activity:activity:1.0.0
|    |    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    |    |    +--- androidx.lifecycle:lifecycle-runtime:2.1.0 -> 2.2.0 (*)
|    |    |    |    +--- androidx.lifecycle:lifecycle-viewmodel:2.1.0 (*)
|    |    |    |    \--- androidx.savedstate:savedstate:1.0.0
|    |    |    |         +--- androidx.annotation:annotation:1.1.0
|    |    |    |         +--- androidx.arch.core:core-common:2.0.1 -> 2.1.0 (*)
|    |    |    |         \--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.2.0 (*)
|    |    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0 (*)
|    |    \--- androidx.annotation:annotation:1.1.0
|    +--- io.flutter:armeabi_v7a_release:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
|    +--- io.flutter:arm64_v8a_release:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
|    \--- io.flutter:x86_64_release:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
+--- androidx.appcompat:appcompat:1.2.0
|    +--- androidx.annotation:annotation:1.1.0
|    +--- androidx.core:core:1.3.0 -> 1.3.1 (*)
|    +--- androidx.cursoradapter:cursoradapter:1.0.0
|    |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    +--- androidx.fragment:fragment:1.1.0 (*)
|    +--- androidx.appcompat:appcompat-resources:1.2.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.0.1 -> 1.3.1 (*)
|    |    +--- androidx.vectordrawable:vectordrawable:1.1.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    |    \--- androidx.collection:collection:1.1.0 (*)
|    |    \--- androidx.vectordrawable:vectordrawable-animated:1.1.0
|    |         +--- androidx.vectordrawable:vectordrawable:1.1.0 (*)
|    |         +--- androidx.interpolator:interpolator:1.0.0
|    |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         \--- androidx.collection:collection:1.1.0 (*)
|    \--- androidx.drawerlayout:drawerlayout:1.0.0
|         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|         +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|         \--- androidx.customview:customview:1.0.0 (*)
+--- com.google.android.material:material:1.3.0
|    +--- androidx.annotation:annotation:1.0.1 -> 1.1.0
|    +--- androidx.appcompat:appcompat:1.1.0 -> 1.2.0 (*)
|    +--- androidx.cardview:cardview:1.0.0
|    |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    +--- androidx.coordinatorlayout:coordinatorlayout:1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    +--- androidx.customview:customview:1.0.0 (*)
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.constraintlayout:constraintlayout:2.0.1
|    |    +--- androidx.appcompat:appcompat:1.2.0 (*)
|    |    +--- androidx.core:core:1.3.1 (*)
|    |    \--- androidx.constraintlayout:constraintlayout-solver:2.0.1
|    +--- androidx.core:core:1.2.0 -> 1.3.1 (*)
|    +--- androidx.dynamicanimation:dynamicanimation:1.0.0
|    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    +--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    |    \--- androidx.legacy:legacy-support-core-utils:1.0.0
|    |         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |         +--- androidx.documentfile:documentfile:1.0.0
|    |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         +--- androidx.loader:loader:1.0.0 (*)
|    |         +--- androidx.localbroadcastmanager:localbroadcastmanager:1.0.0
|    |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         \--- androidx.print:print:1.0.0
|    |              \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    +--- androidx.annotation:annotation-experimental:1.0.0
|    +--- androidx.fragment:fragment:1.0.0 -> 1.1.0 (*)
|    +--- androidx.lifecycle:lifecycle-runtime:2.0.0 -> 2.2.0 (*)
|    +--- androidx.recyclerview:recyclerview:1.0.0 -> 1.1.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    +--- androidx.customview:customview:1.0.0 (*)
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.transition:transition:1.2.0
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.0.1 -> 1.3.1 (*)
|    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    +--- androidx.vectordrawable:vectordrawable:1.1.0 (*)
|    \--- androidx.viewpager2:viewpager2:1.0.0
|         +--- androidx.annotation:annotation:1.1.0
|         +--- androidx.fragment:fragment:1.1.0 (*)
|         +--- androidx.recyclerview:recyclerview:1.1.0 (*)
|         +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|         \--- androidx.collection:collection:1.1.0 (*)
+--- androidx.appcompat:appcompat:{strictly 1.2.0} -> 1.2.0 (c)
+--- com.google.android.material:material:{strictly 1.3.0} -> 1.3.0 (c)
+--- io.flutter:flutter_embedding_release:{strictly 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8} -> 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8 (c)
+--- io.flutter:armeabi_v7a_release:{strictly 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8} -> 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8 (c)
+--- io.flutter:arm64_v8a_release:{strictly 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8} -> 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8 (c)
+--- io.flutter:x86_64_release:{strictly 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8} -> 1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8 (c)
+--- androidx.annotation:annotation:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.core:core:{strictly 1.3.1} -> 1.3.1 (c)
+--- androidx.cursoradapter:cursoradapter:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.fragment:fragment:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.appcompat:appcompat-resources:{strictly 1.2.0} -> 1.2.0 (c)
+--- androidx.drawerlayout:drawerlayout:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.cardview:cardview:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.coordinatorlayout:coordinatorlayout:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.constraintlayout:constraintlayout:{strictly 2.0.1} -> 2.0.1 (c)
+--- androidx.dynamicanimation:dynamicanimation:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.annotation:annotation-experimental:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.lifecycle:lifecycle-runtime:{strictly 2.2.0} -> 2.2.0 (c)
+--- androidx.recyclerview:recyclerview:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.transition:transition:{strictly 1.2.0} -> 1.2.0 (c)
+--- androidx.vectordrawable:vectordrawable:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.viewpager2:viewpager2:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.lifecycle:lifecycle-common:{strictly 2.2.0} -> 2.2.0 (c)
+--- androidx.lifecycle:lifecycle-common-java8:{strictly 2.2.0} -> 2.2.0 (c)
+--- androidx.versionedparcelable:versionedparcelable:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.collection:collection:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.viewpager:viewpager:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.loader:loader:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.activity:activity:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.lifecycle:lifecycle-viewmodel:{strictly 2.1.0} -> 2.1.0 (c)
+--- androidx.vectordrawable:vectordrawable-animated:{strictly 1.1.0} -> 1.1.0 (c)
+--- androidx.customview:customview:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.constraintlayout:constraintlayout-solver:{strictly 2.0.1} -> 2.0.1 (c)
+--- androidx.legacy:legacy-support-core-utils:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.arch.core:core-common:{strictly 2.1.0} -> 2.1.0 (c)
+--- androidx.lifecycle:lifecycle-livedata:{strictly 2.0.0} -> 2.0.0 (c)
+--- androidx.savedstate:savedstate:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.interpolator:interpolator:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.documentfile:documentfile:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.localbroadcastmanager:localbroadcastmanager:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.print:print:{strictly 1.0.0} -> 1.0.0 (c)
+--- androidx.arch.core:core-runtime:{strictly 2.0.0} -> 2.0.0 (c)
\--- androidx.lifecycle:lifecycle-livedata-core:{strictly 2.0.0} -> 2.0.0 (c)

releaseUnitTestRuntimeClasspath - Resolved configuration for runtime for variant: releaseUnitTest
+--- project :flutter
|    +--- io.flutter:flutter_embedding_release:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
|    |    +--- androidx.lifecycle:lifecycle-common:2.2.0
|    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.lifecycle:lifecycle-common-java8:2.2.0
|    |    |    +--- androidx.lifecycle:lifecycle-common:2.2.0 (*)
|    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.lifecycle:lifecycle-runtime:2.2.0
|    |    |    +--- androidx.lifecycle:lifecycle-common:2.2.0 (*)
|    |    |    +--- androidx.arch.core:core-common:2.1.0
|    |    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    |    \--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.fragment:fragment:1.1.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.core:core:1.1.0 -> 1.3.1
|    |    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    |    +--- androidx.lifecycle:lifecycle-runtime:2.0.0 -> 2.2.0 (*)
|    |    |    |    +--- androidx.versionedparcelable:versionedparcelable:1.1.0
|    |    |    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    |    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0
|    |    |    |    |         \--- androidx.annotation:annotation:1.1.0
|    |    |    |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    |    |    +--- androidx.collection:collection:1.1.0 (*)
|    |    |    +--- androidx.viewpager:viewpager:1.0.0
|    |    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    |    |    \--- androidx.customview:customview:1.0.0
|    |    |    |         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    |         \--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    |    +--- androidx.loader:loader:1.0.0
|    |    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    |    |    +--- androidx.lifecycle:lifecycle-livedata:2.0.0
|    |    |    |    |    +--- androidx.arch.core:core-runtime:2.0.0
|    |    |    |    |    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    |    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    |    +--- androidx.lifecycle:lifecycle-livedata-core:2.0.0
|    |    |    |    |    |    +--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.2.0 (*)
|    |    |    |    |    |    +--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    |    |    \--- androidx.arch.core:core-runtime:2.0.0 (*)
|    |    |    |    |    \--- androidx.arch.core:core-common:2.0.0 -> 2.1.0 (*)
|    |    |    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0
|    |    |    |         \--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.activity:activity:1.0.0
|    |    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    |    |    +--- androidx.lifecycle:lifecycle-runtime:2.1.0 -> 2.2.0 (*)
|    |    |    |    +--- androidx.lifecycle:lifecycle-viewmodel:2.1.0 (*)
|    |    |    |    \--- androidx.savedstate:savedstate:1.0.0
|    |    |    |         +--- androidx.annotation:annotation:1.1.0
|    |    |    |         +--- androidx.arch.core:core-common:2.0.1 -> 2.1.0 (*)
|    |    |    |         \--- androidx.lifecycle:lifecycle-common:2.0.0 -> 2.2.0 (*)
|    |    |    \--- androidx.lifecycle:lifecycle-viewmodel:2.0.0 -> 2.1.0 (*)
|    |    \--- androidx.annotation:annotation:1.1.0
|    +--- io.flutter:armeabi_v7a_release:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
|    +--- io.flutter:arm64_v8a_release:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
|    \--- io.flutter:x86_64_release:1.0.0-b3af521a050e6ef076778bcaf16e27b2521df8f8
+--- androidx.appcompat:appcompat:1.2.0
|    +--- androidx.annotation:annotation:1.1.0
|    +--- androidx.core:core:1.3.0 -> 1.3.1 (*)
|    +--- androidx.cursoradapter:cursoradapter:1.0.0
|    |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    +--- androidx.fragment:fragment:1.1.0 (*)
|    +--- androidx.appcompat:appcompat-resources:1.2.0
|    |    +--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
|    |    +--- androidx.annotation:annotation:1.1.0
|    |    +--- androidx.core:core:1.0.1 -> 1.3.1 (*)
|    |    +--- androidx.vectordrawable:vectordrawable:1.1.0
|    |    |    +--- androidx.annotation:annotation:1.1.0
|    |    |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
|    |    |    \--- androidx.collection:collection:1.1.0 (*)
|    |    \--- androidx.vectordrawable:vectordrawable-animated:1.1.0
|    |         +--- androidx.vectordrawable:vectordrawable:1.1.0 (*)
|    |         +--- androidx.interpolator:interpolator:1.0.0
|    |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |         \--- androidx.collection:collection:1.1.0 (*)
|    +--- androidx.drawerlayout:drawerlayout:1.0.0
|    |    +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
|    |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
|    |    \--- androidx.customview:customview:1.0.0 (*)
|    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
\--- com.google.android.material:material:1.3.0
     +--- androidx.annotation:annotation:1.0.1 -> 1.1.0
     +--- androidx.appcompat:appcompat:1.1.0 -> 1.2.0 (*)
     +--- androidx.cardview:cardview:1.0.0
     |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
     +--- androidx.coordinatorlayout:coordinatorlayout:1.1.0
     |    +--- androidx.annotation:annotation:1.1.0
     |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
     |    +--- androidx.customview:customview:1.0.0 (*)
     |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
     +--- androidx.constraintlayout:constraintlayout:2.0.1
     |    +--- androidx.appcompat:appcompat:1.2.0 (*)
     |    +--- androidx.core:core:1.3.1 (*)
     |    \--- androidx.constraintlayout:constraintlayout-solver:2.0.1
     +--- androidx.core:core:1.2.0 -> 1.3.1 (*)
     +--- androidx.dynamicanimation:dynamicanimation:1.0.0
     |    +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
     |    +--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
     |    \--- androidx.legacy:legacy-support-core-utils:1.0.0
     |         +--- androidx.annotation:annotation:1.0.0 -> 1.1.0
     |         +--- androidx.core:core:1.0.0 -> 1.3.1 (*)
     |         +--- androidx.documentfile:documentfile:1.0.0
     |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
     |         +--- androidx.loader:loader:1.0.0 (*)
     |         +--- androidx.localbroadcastmanager:localbroadcastmanager:1.0.0
     |         |    \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
     |         \--- androidx.print:print:1.0.0
     |              \--- androidx.annotation:annotation:1.0.0 -> 1.1.0
     +--- androidx.annotation:annotation-experimental:1.0.0
     +--- androidx.fragment:fragment:1.0.0 -> 1.1.0 (*)
     +--- androidx.lifecycle:lifecycle-runtime:2.0.0 -> 2.2.0 (*)
     +--- androidx.recyclerview:recyclerview:1.0.0 -> 1.1.0
     |    +--- androidx.annotation:annotation:1.1.0
     |    +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
     |    +--- androidx.customview:customview:1.0.0 (*)
     |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
     +--- androidx.transition:transition:1.2.0
     |    +--- androidx.annotation:annotation:1.1.0
     |    +--- androidx.core:core:1.0.1 -> 1.3.1 (*)
     |    \--- androidx.collection:collection:1.0.0 -> 1.1.0 (*)
     +--- androidx.vectordrawable:vectordrawable:1.1.0 (*)
     \--- androidx.viewpager2:viewpager2:1.0.0
          +--- androidx.annotation:annotation:1.1.0
          +--- androidx.fragment:fragment:1.1.0 (*)
          +--- androidx.recyclerview:recyclerview:1.1.0 (*)
          +--- androidx.core:core:1.1.0 -> 1.3.1 (*)
          \--- androidx.collection:collection:1.1.0 (*)

releaseWearApp - Link to a wear app to embed for object 'release'. (n)
No dependencies

runtimeOnly - Runtime only dependencies for 'main' sources. (n)
No dependencies

testAnnotationProcessor - Classpath for the annotation processor for 'test'. (n)
No dependencies

testApi - API dependencies for 'test' sources. (n)
No dependencies

testCompile - Compile dependencies for 'test' sources (deprecated: use 'testImplementation' instead).
No dependencies

testCompileOnly - Compile only dependencies for 'test' sources. (n)
No dependencies

testDebugAnnotationProcessor - Classpath for the annotation processor for 'testDebug'. (n)
No dependencies

testDebugApi - API dependencies for 'testDebug' sources. (n)
No dependencies

testDebugCompile - Compile dependencies for 'testDebug' sources (deprecated: use 'testDebugImplementation' instead). (n)
No dependencies

testDebugCompileOnly - Compile only dependencies for 'testDebug' sources. (n)
No dependencies

testDebugImplementation - Implementation only dependencies for 'testDebug' sources. (n)
No dependencies

testDebugProvided - Provided dependencies for 'testDebug' sources (deprecated: use 'testDebugCompileOnly' instead). (n)
No dependencies

testDebugPublish - Publish dependencies for 'testDebug' sources (deprecated: use 'testDebugRuntimeOnly' instead). (n)
No dependencies

testDebugRuntimeOnly - Runtime only dependencies for 'testDebug' sources. (n)
No dependencies

testDebugWearApp - Link to a wear app to embed for object 'testDebug'. (n)
No dependencies

testImplementation - Implementation only dependencies for 'test' sources. (n)
No dependencies

testProvided - Provided dependencies for 'test' sources (deprecated: use 'testCompileOnly' instead). (n)
No dependencies

testPublish - Publish dependencies for 'test' sources (deprecated: use 'testRuntimeOnly' instead). (n)
No dependencies

testReleaseAnnotationProcessor - Classpath for the annotation processor for 'testRelease'. (n)
No dependencies

testReleaseApi - API dependencies for 'testRelease' sources. (n)
No dependencies

testReleaseCompile - Compile dependencies for 'testRelease' sources (deprecated: use 'testReleaseImplementation' instead). (n)
No dependencies

testReleaseCompileOnly - Compile only dependencies for 'testRelease' sources. (n)
No dependencies

testReleaseImplementation - Implementation only dependencies for 'testRelease' sources. (n)
No dependencies

testReleaseProvided - Provided dependencies for 'testRelease' sources (deprecated: use 'testReleaseCompileOnly' instead). (n)
No dependencies

testReleasePublish - Publish dependencies for 'testRelease' sources (deprecated: use 'testReleaseRuntimeOnly' instead). (n)
No dependencies

testReleaseRuntimeOnly - Runtime only dependencies for 'testRelease' sources. (n)
No dependencies

testReleaseWearApp - Link to a wear app to embed for object 'testRelease'. (n)
No dependencies

testRuntimeOnly - Runtime only dependencies for 'test' sources. (n)
No dependencies

testWearApp - Link to a wear app to embed for object 'test'. (n)
No dependencies

wearApp - Link to a wear app to embed for object 'main'. (n)
No dependencies

(c) - dependency constraint
(*) - dependencies omitted (listed previously)

(n) - Not resolved (configuration is not meant to be resolved)

A web-based, searchable dependency report is available by adding the --scan option.

Deprecated Gradle features were used in this build, making it incompatible with Gradle 7.0.
Use '--warning-mode all' to show the individual deprecation warnings.
See https://docs.gradle.org/6.1.1/userguide/command_line_interface.html#sec:command_line_warnings

BUILD SUCCESSFUL in 983ms
1 actionable task: 1 executed
generateLockfiles

> Configure project :app
WARNING: DSL element 'annotationProcessorOptions.includeCompileClasspath' is obsolete.
It will be removed in version 5.0 of the Android Gradle plugin.
It does not do anything and AGP no longer includes annotation processors added on your project's compile classpath

FAILURE: Build failed with an exception.

* What went wrong:
Project 'AlivcMedia' not found in root project 'issueSimpleProject'.

* Try:
Run with --stacktrace option to get the stack trace. Run with --info or --debug option to get more log output. Run with --scan to get full insights.

* Get more help at https://help.gradle.org

Deprecated Gradle features were used in this build, making it incompatible with Gradle 7.0.
Use '--warning-mode all' to show the individual deprecation warnings.
See https://docs.gradle.org/6.1.1/userguide/command_line_interface.html#sec:command_line_warnings

BUILD FAILED in 750ms

FAILURE: Build failed with an exception.

* Where:
Script '/usr/local/libs/flutter_sdk/packages/flutter_tools/gradle/flutter.gradle' line: 111

* What went wrong:
Could not create task ':generateLockfiles'.
> Process 'command '/Volumes/Storage/AS_WS/issueSimpleProject/gradlew'' finished with non-zero exit value 1

* Try:
Run with --stacktrace option to get the stack trace. Run with --info or --debug option to get more log output. Run with --scan to get full insights.

* Get more help at https://help.gradle.org

Deprecated Gradle features were used in this build, making it incompatible with Gradle 7.0.
Use '--warning-mode all' to show the individual deprecation warnings.
See https://docs.gradle.org/6.1.1/userguide/command_line_interface.html#sec:command_line_warnings

BUILD FAILED in 21s
61 actionable tasks: 4 executed, 57 up-to-date

```
