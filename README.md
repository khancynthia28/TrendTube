# youtubeAnalytics

### Team:
- Cynthia Khan
- Jack Terrell
- Nashid Islam

### Platforms:
- Java 1.7
- Apache Spark 2.11
- Maven 3.5.1

### Maven Build
mvn --file pom-file.xml clean

mvn --file pom-file.xml package

### To Run
$SPARK_HOME/bin/spark-submit --class Driver ./target/youtubeAnalytics-0.0.1.jar

### Code Snippet
public class Snippet {

	private String channelId;
	private String title;
	boolean assignable;
	
	@Override
	public String toString() {
		return title;
	}
}
