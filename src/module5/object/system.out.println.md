# `System.out.println("Developer");`

## System

```java
//classe
public final class System  {
    
}
```

- classe
- java.lang
- acesso público

## out

```java
public final class System  {
    
    //atributo da classe System do tipo PrintStream
    public static final PrintStream out = null;
    
}
```

- atributo
- público
- referência
- static

## println
```java
public class PrintStream extends FilterOutputStream implements Appendable, Closeable {
    
    //sobrecarga de método
    public void println() {
        newLine();
    }
}
```
- método
- público
- não estático
- sobrecarga
- não lança exceções do tipo checked