Инструкция — это команда для компьютера. Код на Java — это набор инструкций, которые, обычно, отделяются друг от друга символом `;`. Вот пример кода с двумя инструкциями:

```java
System.out.println("Mother of Dragons");
System.out.println("Dracarys!");
```

При запуске этого кода на экран последовательно выводятся два предложения:

<pre class='hexlet-basics-output'>
Mother of Dragons
Dracarys!
</pre>

Почему это важно знать? Инструкция — это единица исполнения. Программа, которая запускает код на Java, выполняет инструкции строго по очереди. Разработчики должны понимать этот порядок и уметь мысленно разделять программу на независимые части, удобные для анализа.

Теоретически инструкции можно написать последовательно друг за другом без переноса на новую строчку:

```java
System.out.println("Mother of Dragons."); System.out.println("Dracarys!");
```

Результат на экране будет таким же, но на практике такой подход считается плохим.