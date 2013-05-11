maven-repo
==========

Maven repository

Use in pom.xml :

	<repositories>
		<repository>
			<id>eolya-snapshots</id>
			<url>https://raw.github.com/bejean/maven-repo/master/snapshots</url>
			<releases>
				<enabled>false</enabled>
			</releases>
			<snapshots>
				<enabled>true</enabled>
			</snapshots>
		</repository>
		<repository>
			<id>eolya-releases</id>
			<releases>
				<enabled>true</enabled>
			</releases>
			<snapshots>
				<enabled>false</enabled>
			</snapshots>
			<url>https://raw.github.com/bejean/maven-repo/master/releases</url>
		</repository>
	</repositories>


How to :

http://coffeecoders.de/2011/09/using-github-as-a-personal-maven-repository/
http://dev.clojure.org/display/doc/Maven+Settings+and+Repositories



