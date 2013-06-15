<!--

    Copyright (c) 2007-2013, the original author or authors.

    This program is licensed to you under the Apache License Version 2.0,
    and you may not use this file except in compliance with the Apache License Version 2.0.
    You may obtain a copy of the Apache License Version 2.0 at http://www.apache.org/licenses/LICENSE-2.0.

    Unless required by applicable law or agreed to in writing,
    software distributed under the Apache License Version 2.0 is distributed on an
    "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the Apache License Version 2.0 for the specific language governing permissions and limitations there under.

-->
# Console

GMaven supports opening up the GUI [Groovy Console](http://groovy.codehaus.org/Groovy+Console)
with the [console](console-mojo.html) goal:

    mvn groovy:console

This goal works with and without a project.  When a project is available additional [classpath](classpath.html)
configuration options are avaiable.

All context [variables](variables.html) are availble for use in the console.



