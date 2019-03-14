# aos-regression-test-web
AOS Regression Test Suite for Nimbus

This test shows a simple test of navigating through AOS and spotchecking 
various values of the application

To run this test using SRF, first configure your SRF configuration in IntelliJ 
by going to LeanFT > Engine and Object Identification Settings, then going to
the Lab tab and setting your SRF connection details. You can then set the run.srf 
property to true by running the
following

```
test -Drun.srf=true
```

If you want this to persist in Jenkins without having to change the configuration
of the build, you can modify the default value of the run.srf property to true by
editing the pom.xml file.

```
<systemPropertyVariables>
    <run.srf>true</run.srf>
</systemPropertyVariables>
```

