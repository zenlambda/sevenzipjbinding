# sevenzipjbindings

This is a simple maven build that downloads the sevenzipjbinding[1] JARs and bundles them into a maven repository.

## Usage

1. Allow maven to retrieve the sevenzipjbindings Jars

	Either by cloning the repo and running `mvn install` or 	placing a reference to the zenlambda repository in your 	projects pom.xml, like so:

		<repositories>
	    	<repository>
			<id>zenlambda-releases</id>
			<url>http://mvn-repo.zenlambda.com/releases</url>
	    	</repository>
		</repositories>
	 
2. 	Then refer to the library as a dependency:

		<dependency>
			<groupId>net.sf.sevenzipjbinding</groupId>
			<artifactId>sevenzipjbinding</artifactId>
			<version>1.05-rc</version>
		</dependency>
		<dependency>
			<groupId>net.sf.sevenzipjbinding</groupId>
			<artifactId>sevenzipjbinding</artifactId>
			<version>1.05-rc</version>
			<classifier>AllPlatforms</classifier>
		</dependency>
		
## Acknowledgements

The sevenzipjbindings library is authored by Boris Brodski. More info is available on the sevenzipjbindings website [1].

##References
[1] http://sevenzipjbind.sourceforge.net/