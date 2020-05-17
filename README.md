# SimpleDB
A simple database project from MIT 6.380

## References
1. Course: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-830-database-systems-fall-2010/index.htm
2. Labs: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-830-database-systems-fall-2010/assignments/
3. Doc: https://dsf.berkeley.edu/papers/fntdb07-architecture.pdf
4. UC Berkeley: https://cs186berkeley.net/
5. Youtube: https://www.youtube.com/playlist?list=PLfciLKR3SgqOxCy1TIXXyfTqKzX2enDjK
6. https://github.com/DevinZ1993/SimpleDB-Database-System

## Build and Test
This is a standard ant project, so you can run `ant` under the root dictionary, and the test can be run by `ant test`.

## Help
If you use IDEA to run this project, you can change the .idea/xxx.imp file to:

```xml
<?xml version="1.0" encoding="UTF-8"?>
<module type="JAVA_MODULE" version="4">
  <component name="NewModuleRootManager" inherit-compiler-output="true">
    <exclude-output />
    <content url="file://$MODULE_DIR$">
      <sourceFolder url="file://$MODULE_DIR$/src" isTestSource="false" />
      <sourceFolder url="file://$MODULE_DIR$/test" isTestSource="true" />
    </content>
    <orderEntry type="inheritedJdk" />
    <orderEntry type="sourceFolder" forTests="false" />
    <orderEntry type="library" name="junit-4.5" level="project" />
    <orderEntry type="library" name="ant-contrib-1.0b3" level="project" />
  </component>
</module>
```
