### Book: Crafting Interpreters (Robert Nystrom)

- To run the interpreter:
   - Ensure you have **Java 17>** and **Maven** installed.
   - `mvn clean package` on the root directory
   - `java -jar target/*.jar` to run the jar as REPL
      - `java -jar target/*.jar <filename.lox>` to interpret Lox code

- Development:
   - ` mvn exec:java -Dexec.mainClass="tool.GenerateAst" -Dexec.args="src/main/java/jlox"` To generate the AST
