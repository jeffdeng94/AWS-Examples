# Create a new Maven Project
```sh
mvn -B archetype:generate \
 -DarchetypeGroupId=software.amazon.awssdk \
 -DarchetypeArtifactId=archetype-lambda -Dservice=s3 -Dregion=AP_SOUTHEAST_2 \
 -DarchetypeVersion=2.30.26 \
 -DgroupId=com.example.myapp \
 -DartifactId=myapp
```