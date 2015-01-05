Task4Maven_TwoProfiles_Invoker
==============================

In this project I try to invoke assembly:single goal two times - with "Profile1" and "Profile2" profiles.
If I just invoke assembly:single goal with Profile1 or Profile2 it's working fine. But if I invoke iterator:invoker, I get error

Failed to execute goal com.soebes.maven.plugins:iterator-maven-plugin:0.3:invoker (default-cli) on project Task4Maven_TwoProfiles_Invoker: Unable to parse configuration of mojo com.soebes.maven.plugins:iterator-maven-plugin:0.3:invoker for parameter goals: Cannot assign configuration entry 'goals' with value 'assembly:single' of type java.lang.String to property of type java.util.List -> [Help 1]

Task of this project - to get two archives containing filtered file A in one archive and filtered file B in another archive.
