# 🚀 Java Spring Boot Starter (Java 17, Maven)

এই প্রোজেক্টটি একটি **Spring Boot Starter Template**  
যেখানে ব্যবহার করা হয়েছে **Java 17 (LTS)** + **Maven** + **Spring Boot Web** + **JUnit 5**।  
রিপোটি "Clone → Run" করার জন্য তৈরি করা হয়েছে, Maven ইনস্টল না থাকলেও **mvnw** দিয়ে চালানো যাবে।

---

## ✨ Features
- ✅ **Java 17 (LTS)**
- ✅ **Spring Boot 3.x (Web REST API)**
- ✅ **Maven build system**
- ✅ **Maven Wrapper (mvnw) included**
- ✅ **JUnit 5** টেস্ট
- ✅ **Dockerfile** for container build
- ✅ **GitHub Actions CI** (Build + Test)

---

## 📦 প্রোজেক্ট রান করার উপায়

### 1️⃣ লোকালি রান করা
```bash
./mvnw spring-boot:run
```
তারপর ব্রাউজারে খুলুন → [http://localhost:8080/api/hello](http://localhost:8080/api/hello)

---

### 2️⃣ JAR বানিয়ে রান করা
```bash
./mvnw package
java -jar target/java-spring-starter-0.0.1-SNAPSHOT.jar
```

---

### 3️⃣ Docker দিয়ে রান করা
```bash
# Build Docker image
docker build -t java-spring-starter:latest .

# Run container
docker run -p 8080:8080 java-spring-starter:latest
```

---

## 🧪 টেস্ট চালানো
```bash
./mvnw test
```

---

## 📁 ফোল্ডার স্ট্রাকচার
```
java-spring-starter/
├── .github/workflows/ci.yml      # GitHub Actions pipeline
├── Dockerfile                    # Docker build config
├── mvnw / mvnw.cmd               # Maven wrapper scripts
├── pom.xml                       # Maven config
├── src/main/java/...             # Main application source
├── src/test/java/...             # Unit tests
└── README.md                     # Project documentation
```

---

## 📜 License
MIT License — আপনি চাইলে কপি/পরিবর্তন/ব্যবহার করতে পারবেন।
