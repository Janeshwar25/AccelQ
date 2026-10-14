mvn -U validate -e 2>&1 | Select-String -Pattern "Non-resolvable parent POM|Could not find artifact|Could not transfer artifact|401|403|Unknown host|parent.relativePath|BUILD FAILURE" -Context 2,3
