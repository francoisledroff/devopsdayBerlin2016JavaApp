This is the github `repo` used for an Hands-On session at DevopsDays Berlin 2016, 

named [`Chef versus Ansible`](http://www.slideshare.net/francoisledroff/devops-days-berlin2016)

Among other things, the [`Chef`](https://github.com/francoisledroff/devopsdayberlin2016) part demonstrated
  
* the use of a **Chef custom `resource`** named `fat_jar`, 
  * `fat_jar` allows you to treat any given java fat jar (that is runnable jar, typically a `springboot` jar) as a resource, 
    * it assumes the jar is made available through a maven artifact repository

This sample project is to be used in the above concept, the `cli`
    
    mvn -s settings.xml clean deploy
    
will build and deploy the files in artifactory the pom and jar files expected by the Chef cookbooks 
   
