# Donya

Donya (the Javanese word for "the world") is a declarative internationalization framework for Java.

You use annotations in a class to identify fields which need to be localized.  

The current implementation uses these annotations to add the localized text when serializing an object
into JSON using the Jackson JSON library.  However, other implementations can be implemented that use
other mechanisms to automatically format the localized text.

You can build using standard maven.  There is also an Eclipse project file.

See the org.donyasource.dony.examples directory for examples of how this is used.

Feedback and contributions welcome!

## Getting Started
	
To build, go to the top level directory and run:
	
	mvn package

To run the simple example, run 

        ./simple_example.sh en
        
Then try

        ./simple_example.sh jv
        
Enjoy!

## License

Copyright (c) 2014 Castlight Health. See the LICENSE file for license rights and limitations.

This project is licensed under the [MIT license](http://opensource.org/licenses/MIT).

This project uses [Jackson] (http://jackson.codehaus.org/), [Apache Commons Lang](http://commons.apache.org/proper/commons-lang/), and [Guava](https://code.google.com/p/guava-libraries/) which are all under the [Apache 2.0 license](http://www.apache.org/licenses/LICENSE-2.0)

For testing we use [Mockito](https://code.google.com/p/mockito/) which uses the [MIT license](http://opensource.org/licenses/MIT) and [Junit](http://junit.org/) which uses the [Eclipse Public License] (https://github.com/junit-team/junit/blob/master/LICENSE.txt)

