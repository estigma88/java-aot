# Getting Started

./gradlew :test -Paot="-XX:AOTMode=record,-XX:AOTConfiguration=app.aotconf"

./gradlew :test -Paot="-XX:AOTMode=create,-XX:AOTConfiguration=app.aotconf,-XX:AOTCache=app.aot"
