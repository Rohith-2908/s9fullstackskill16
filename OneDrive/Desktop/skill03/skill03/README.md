# Hibernate Inventory Project

Maven-based Java application demonstrating Hibernate ORM with MySQL for inventory management.

## Tech Stack
- Java 17
- Maven
- Hibernate 6.4
- MySQL Connector 8.3

## Structure
- `src/main/java/com/inventory/`: Core entities, DAOs, utils, main app.
- `src/main/resources/hibernate.cfg.xml`: Hibernate config.

## Run
1. Update DB config in `hibernate.cfg.xml`.
2. `mvn clean install`
3. `mvn exec:java -Dexec.mainClass="com.inventory.main.App"`

See pom.xml for deps.

