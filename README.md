### loginRegisterInterface

## Requirements
- Java 11
- Spring Boot
- Spring Data Jpa
- Spring Security
- Javascript
- React.js V5
- ReactStrap
- BootStrap

## Development for Java

# - IntelliJ IDEA

1. Open IntelliJ IDEA and select _File > Open..._.
2. Choose the java-maven-starter-project directory and click _OK_.
3. Select _File > Project Structure..._ and ensure that the Project SDK and language level are set to use Java 11.
4. Open the Maven view with _View > Tool Windows > Maven_.
5. In the Maven view, under _Plugins > dependency_, double-click the `dependency:unpack` goal. This will unpack the native libraries into $USER_HOME/.arcgis.
6. In the Maven view, run the `compile` phase under _Lifecycle_ and then the `exec:java` goal to run the app.


## Development for React

Pull requests are encouraged and always welcome. [Pick an issue](https://github.com/sveltejs/svelte/issues?q=is%3Aissue+is%3Aopen+sort%3Aupdated-desc) and help us out!

To install and work on Svelte locally:

```bash
git clone   https://github.com/melihaycicek/loginRegisterInterface
cd svelte
npm install
```


To build the compiler and all the other modules included in the package:

```bash
npm run build
```

```bash
npm run dev
```



### Running Tests

```bash
npm run test
```


```bash
npm run test -- -g transition
```


##### (Port)
```
Backend :  http://localhost:8081
```

```
Frontend : http://localhost:3000
```

