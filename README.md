```
[INFO] Scanning for projects...
[INFO] 
[INFO] ------------------------------------------------------------------------
[INFO] Building spotbugs-bug-20180518 0.0.1
[INFO] ------------------------------------------------------------------------
[INFO] 
[INFO] --- maven-clean-plugin:2.5:clean (default-clean) @ spotbugs-bug-20180518 ---
[INFO] Deleting /home/rm/git/com.github/io7m/spotbugs-bug-20180518/target
[INFO] 
[INFO] --- maven-resources-plugin:2.6:resources (default-resources) @ spotbugs-bug-20180518 ---
[WARNING] Using platform encoding (UTF-8 actually) to copy filtered resources, i.e. build is platform dependent!
[INFO] skip non existing resourceDirectory /home/rm/git/com.github/io7m/spotbugs-bug-20180518/src/main/resources
[INFO] 
[INFO] --- maven-compiler-plugin:3.7.0:compile (default-compile) @ spotbugs-bug-20180518 ---
[INFO] Changes detected - recompiling the module!
[WARNING] File encoding has not been set, using platform encoding UTF-8, i.e. build is platform dependent!
[INFO] Compiling 1 source file to /home/rm/git/com.github/io7m/spotbugs-bug-20180518/target/classes
[INFO] 
[INFO] >>> spotbugs-maven-plugin:3.1.3.1:check (unreadable-xml) > :spotbugs @ spotbugs-bug-20180518 >>>
[INFO] 
[INFO] --- spotbugs-maven-plugin:3.1.3.1:spotbugs (spotbugs) @ spotbugs-bug-20180518 ---
WARNING: An illegal reflective access operation has occurred
WARNING: Illegal reflective access by org.codehaus.groovy.reflection.CachedClass (file:/home/rm/.m2/repository/org/codehaus/groovy/groovy/2.4.15/groovy-2.4.15.jar) to method java.lang.Object.finalize()
WARNING: Please consider reporting this to the maintainers of org.codehaus.groovy.reflection.CachedClass
WARNING: Use --illegal-access=warn to enable warnings of further illegal reflective access operations
WARNING: All illegal access operations will be denied in a future release
[INFO] Fork Value is false
     [java] JVM args ignored when same JVM is used.
     [java] The following errors occurred during analysis:
     [java]   Unable to read filter: /home/rm/git/com.github/io7m/spotbugs-bug-20180518/target/spotbugs-filter.xml : Failing reading /home/rm/git/com.github/io7m/spotbugs-bug-20180518/target/spotbugs-filter.xml
     [java]     org.dom4j.DocumentException: Failing reading /home/rm/git/com.github/io7m/spotbugs-bug-20180518/target/spotbugs-filter.xml
     [java]       At edu.umd.cs.findbugs.SortedBugCollection.readXML(SortedBugCollection.java:276)
     [java]       At edu.umd.cs.findbugs.SortedBugCollection.readXML(SortedBugCollection.java:257)
     [java]       At edu.umd.cs.findbugs.ExcludingHashesBugReporter.addToExcludedInstanceHashes(ExcludingHashesBugReporter.java:57)
     [java]       At edu.umd.cs.findbugs.ExcludingHashesBugReporter.<init>(ExcludingHashesBugReporter.java:44)
     [java]       At edu.umd.cs.findbugs.FindBugs.configureBaselineFilter(FindBugs.java:519)
     [java]       At edu.umd.cs.findbugs.FindBugs2.excludeBaselineBugs(FindBugs2.java:376)
     [java]       At edu.umd.cs.findbugs.FindBugs2.configureFilters(FindBugs2.java:483)
     [java]       At edu.umd.cs.findbugs.FindBugs2.setUserPreferences(FindBugs2.java:472)
     [java]       At edu.umd.cs.findbugs.TextUICommandLine.configureEngine(TextUICommandLine.java:670)
     [java]       At edu.umd.cs.findbugs.FindBugs.processCommandLine(FindBugs.java:365)
     [java]       At edu.umd.cs.findbugs.FindBugs2.main(FindBugs2.java:1175)
     [java]       At java.base/jdk.internal.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
     [java]       At java.base/jdk.internal.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
     [java]       At java.base/jdk.internal.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
     [java]       At java.base/java.lang.reflect.Method.invoke(Method.java:564)
     [java]       At org.apache.tools.ant.taskdefs.ExecuteJava.run(ExecuteJava.java:223)
     [java]       At java.base/java.lang.Thread.run(Thread.java:844)
[INFO] Done SpotBugs Analysis....
[INFO] 
[INFO] <<< spotbugs-maven-plugin:3.1.3.1:check (unreadable-xml) < :spotbugs @ spotbugs-bug-20180518 <<<
[INFO] 
[INFO] 
[INFO] --- spotbugs-maven-plugin:3.1.3.1:check (unreadable-xml) @ spotbugs-bug-20180518 ---
[INFO] BugInstance size is 0
[INFO] Error size is 1
[INFO] No errors/warnings found
[INFO] 
[INFO] --- maven-resources-plugin:2.6:testResources (default-testResources) @ spotbugs-bug-20180518 ---
[WARNING] Using platform encoding (UTF-8 actually) to copy filtered resources, i.e. build is platform dependent!
[INFO] skip non existing resourceDirectory /home/rm/git/com.github/io7m/spotbugs-bug-20180518/src/test/resources
[INFO] 
[INFO] --- maven-compiler-plugin:3.7.0:testCompile (default-testCompile) @ spotbugs-bug-20180518 ---
[INFO] No sources to compile
[INFO] 
[INFO] --- maven-surefire-plugin:2.12.4:test (default-test) @ spotbugs-bug-20180518 ---
[INFO] No tests to run.
[INFO] 
[INFO] --- maven-jar-plugin:2.4:jar (default-jar) @ spotbugs-bug-20180518 ---
[INFO] Building jar: /home/rm/git/com.github/io7m/spotbugs-bug-20180518/target/spotbugs-bug-20180518-0.0.1.jar
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time: 6.527 s
[INFO] Finished at: 2018-05-18T20:15:11+01:00
[INFO] Final Memory: 28M/104M
[INFO] ------------------------------------------------------------------------
```
