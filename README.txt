DB
--
CREATE SCHEMA `test` ;


$ mvn archetype:generate


Choose a number or apply filter (format: [groupId:]artifactId, case sensitive contains): 1027: 1769
Define value for property 'groupId': com.test.springboot.jpa
Define value for property 'artifactId': springbootjpatestproject
Define value for property 'version' 1.0-SNAPSHOT: : 1
Define value for property 'package' com.test.springboot.jpa: : war


$ mvn eclipse:eclipse

$ mvn package -Dmaven.test.skip=true



http://patorjk.com/software/taag/#p=display&h=1&f=Soft&t=Planets%20Server