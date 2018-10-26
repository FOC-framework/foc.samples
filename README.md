# foc.samples
FOC Samples

  foc.samples contains a project called **myfocapplication**

How to install foc.samples:

1- clone the foc.sample repository
git clone https://github.com/FOC-framework/foc.samples.git

2- Open an empty eclipse workspace and load the project myfocapplication

3- adjust your **settings.xml**:

  <servers>
    ...
  </servers>
	<profiles>
    ...
		<profile>
			<id>allow-snapshots</id>
			<activation><activeByDefault>true</activeByDefault></activation>
			<repositories>
				<repository>
					<id>snapshots-repo</id>
					<url>https://oss.sonatype.org/content/repositories/snapshots</url>
					<releases><enabled>false</enabled></releases>
					<snapshots><enabled>true</enabled></snapshots>
				</repository>
			</repositories>
		</profile>
	</profiles>




