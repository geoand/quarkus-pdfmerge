# pdfmerge

## Build

```bash
./mvnw package
```

## Run 

```bash
java -jar target/quarkus-app/quarkus-run.jar --input=/location/f1.pdf --input=/location/f2.pdf
```

## Native

### Build

```bash
./mvnw package -Dnative
```

### Run

```bash
target/pdfmerge --input=/location/f1.pdf --input=/location/f2.pdf
```

