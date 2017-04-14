Purpose
=======

Dependency declarations for the [tomcat](http://tomcat.apache.org/) container.


Contact
=======

* daniel.kasmeroglu@kasisoft.net


Maven
=====

I assume that you're familiar with Maven. If not I suggest to visit the following page:

* https://maven.apache.org/


Importing
---------

     <dependencyManagement>
     
        <dependency>
          <groupId>com.kasisoft</groupId>
          <artifactId>com.kasisoft.pom.tomcat</artifactId>
          <version>7.0.57</version>
          <type>pom</type>
          <scope>import</scope>
        </dependency>
     
     </dependencyManagement>


License
=======

MIT License

Copyright (c) 2017 Daniel Kasmeroglu (Kasisoft)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
