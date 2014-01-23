Play GPars
==================================

[GPars](http://gpars.codehaus.org) [example code](http://gpars.org/download/1.1.0/gpars-samples-1.1.0.zip) at [GPars Demos Page](http://gpars.codehaus.org/Demos).

You can check out code and run. 

FAQ
----------------------------------

### `Maven` complication error

\# Complication by `IntelliJ Idea` is OK.

```bash
/path/to/play-gpars/src/main/java/groovyx/gpars/samples/actors/reactor/DemoSleepingBarber.groovy: 1. ERROR in /path/to/play-gpars/src/main/java/groovyx/gpars/samples/actors/reactor/DemoSleepingBarber.groovy (at line 0)
	// GPars - Groovy Parallel Systems
	^
Internal compiler error: java.lang.NullPointerException at org.codehaus.jdt.groovy.internal.compiler.ast.JDTClassNodeBuilder.configureType(JDTClassNodeBuilder.java:62)

Found 1 error and 0 warnings.

[INFO] ------------------------------------------------------------------------
[INFO] Trace
org.apache.maven.BuildFailureException: Compilation failure
	at org.apache.maven.lifecycle.DefaultLifecycleExecutor.executeGoals(DefaultLifecycleExecutor.java:715)
	at org.apache.maven.lifecycle.DefaultLifecycleExecutor.executeGoalWithLifecycle(DefaultLifecycleExecutor.java:556)
	at org.apache.maven.lifecycle.DefaultLifecycleExecutor.executeGoal(DefaultLifecycleExecutor.java:535)
	at org.apache.maven.lifecycle.DefaultLifecycleExecutor.executeGoalAndHandleFailures(DefaultLifecycleExecutor.java:387)
	at org.apache.maven.lifecycle.DefaultLifecycleExecutor.executeTaskSegments(DefaultLifecycleExecutor.java:348)
	at org.apache.maven.lifecycle.DefaultLifecycleExecutor.execute(DefaultLifecycleExecutor.java:180)
	at org.apache.maven.DefaultMaven.doExecute(DefaultMaven.java:328)
	at org.apache.maven.DefaultMaven.execute(DefaultMaven.java:138)
	at org.apache.maven.cli.MavenCli.main(MavenCli.java:362)
	at org.apache.maven.cli.compat.CompatibleMain.main(CompatibleMain.java:60)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:57)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:606)
	at org.codehaus.classworlds.Launcher.launchEnhanced(Launcher.java:315)
	at org.codehaus.classworlds.Launcher.launch(Launcher.java:255)
	at org.codehaus.classworlds.Launcher.mainWithExitCode(Launcher.java:430)
	at org.codehaus.classworlds.Launcher.main(Launcher.java:375)
Caused by: org.apache.maven.plugin.compiler.CompilationFailureException: Compilation failure
	at org.apache.maven.plugin.compiler.AbstractCompilerMojo.execute(AbstractCompilerMojo.java:858)
	at org.apache.maven.plugin.compiler.CompilerMojo.execute(CompilerMojo.java:129)
	at org.apache.maven.plugin.DefaultPluginManager.executeMojo(DefaultPluginManager.java:490)
	at org.apache.maven.lifecycle.DefaultLifecycleExecutor.executeGoals(DefaultLifecycleExecutor.java:694)
	... 17 more
```


Related Resource
----------------------------------

- [Groovy-Eclipse compiler plugin for Maven](http://groovy.codehaus.org/Groovy-Eclipse+compiler+plugin+for+Maven)
