

# Sample commands to create a Scala project by using [maven] (http://maven.apache.org/)

  mvn archetype:generate \
      -DarchetypeGroupId=org.scala-tools.archetypes \
      -DarchetypeArtifactId=scala-archetype-simple  \
      -DremoteRepositories=http://scala-tools.org/repo-releases \
      -DgroupId=org.glassfish.samples \
      -DartifactId=scala-helloworld \
      -Dversion=1.0-SNAPSHOT
