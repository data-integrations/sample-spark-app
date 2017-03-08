## About
This repo contains two example spark apps that can run on Apache Spark. 
  - word-count-java: contains word count example written in Java 
  - sparkpi-scala: contains sparkpi example written in Scala
This wiki documents steps to run these standard examples on directly on Spark and using CDAP without any code change
  
  
## Running examples directly on Spark

1. Word Count
   - Package 
   ```
   cd word-count-java
   mvn clean package
   ``` 
   - Deploy 
   - Run
2. Spark Pi
    - Package 
    - Deploy 
    - Run
 
## Running examples using CDAP without any code change
1. Word Count 
   - Package  
   ```
   cd word-count-java
   mvn clean package
   ``` 
   - Deploy 
      - Add plugin
      - Create a CDAP App 
   - Run 
   
2. Spark Pi 
   - Package 
   ```
   cd spark-pi-scala
   mvn clean package
   ``` 
   - Deploy 
      - Add plugin 
      - Create CDAP App
   - Run  
   
   
## References 
1. Notifiable workflow app https://github.com/caskdata/cdap-notifiable-workflow-app
      
## Mailing Lists

CDAP User Group and Development Discussions:

- `cdap-user@googlegroups.com <https://groups.google.com/d/forum/cdap-user>`__

The *cdap-user* mailing list is primarily for users using the product to develop
applications or building plugins for appplications. You can expect questions from 
users, release announcements, and any other discussions that we think will be helpful 
to the users.

## License and Trademarks

Copyright © 2016-2017 Cask Data, Inc.

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except
in compliance with the License. You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the 
License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, 
either express or implied. See the License for the specific language governing permissions 
and limitations under the License.

Cask is a trademark of Cask Data, Inc. All rights reserved.

Apache, Apache HBase, and HBase are trademarks of The Apache Software Foundation. Used with
permission. No endorsement by The Apache Software Foundation is implied by the use of these marks.
