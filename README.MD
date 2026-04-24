# Generate with default Java version

## Unix / Linux
`mvn archetype:generate -DarchetypeGroupId=org.sterl -DarchetypeArtifactId=java-minimal`

## Windows
`mvn archetype:generate "-DarchetypeGroupId=org.sterl" "-DarchetypeArtifactId=java-minimal"`

# Generate with custom Java version
`mvn archetype:generate -DarchetypeGroupId=org.sterl -DarchetypeArtifactId=java-minimal -Djava_version=17`
