
FROM openjdk:latest

RUN curl https://github.com/adoptium/temurin11-binaries/releases/download/jdk-11.0.13%2B8/OpenJDK11U-debugimage_aarch64_linux_hotspot_11.0.13_8.tar.gz

mkdir -p /app/java/openjdk
cd /app/java/openjdk
tar -xvf OpenJDK11U-debugimage_aarch64_linux_hotspot_11.0.13_8.tar.gz

ENV java_Home=/app/java/openjdk
path="/app/java/openjdk/bin:$PATH"

USER root



