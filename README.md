# gymex-analytics-service

mvn clean package -DskipTests
docker build -t gymex/attendance-analytics-service:latest .
docker run -p 8082:8082 gymex/attendance-analytics-service:latest