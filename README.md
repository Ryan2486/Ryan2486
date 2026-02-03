# 👋 Hey there, I'm Ryan

> "It's prime time to clucht up".

## About Me

Master’s student in Software Engineering & Databases at ENI  
Passionate about Artificial Intelligence — not for the buzz, but for the **real** magic behind it  
I love to break things down, understand them, and rebuild better. Systems, ideas… even myself.  
Joker main in Smash Bros (yes, I dodge roll too much), and a bit of a philosopher on the side  
"I think so I'm", I like conversations with people who see the bigger picture and ask the real questions

## What I work with

- **Languages**: Java, Python, TypeScript, SQL  
- **Frameworks**: Spring Boot, Next JS, FastAPI  
- **Databases**: PostgreSQL, MySQL  
- **Other tools**: Docker, Git, Postman

## Currently working on...

```java
public class Main {
    public static void main(String[] args) {
        LearningPath path = new LearningPath();

        path.append(new PatternNode(Patterns.SINGLETON, "One instance to rule them all."));
        path.append(new PatternNode(Patterns.STRATEGY, "Behavioral flexibility, I choose my weapon."));
        path.append(new PatternNode(Patterns.OBSERVER, "Reactive mind — I see, therefore I respond."));
        path.append(new PatternNode(Patterns.NEURAL_NETWORK, "Imitating the brain. Learning from data."));
        path.append(new PatternNode(Patterns.DEEP_REFLECTION, "Code, like thought, is about structure."));

        path.traverse();
    }
}
```
```java
public class PatternNode {
    Patterns pattern;
    String message;
    PatternNode next;

    public PatternNode(Patterns pattern, String message) {
        this.pattern = pattern;
        this.message = message;
    }

    public void display() {
        System.out.println("🔹 " + pattern + " → " + message);
    }
}
```
```java
public class LearningPath {
    private PatternNode head;

    public void append(PatternNode node) {
        if (head == null) {
            head = node;
        } else {
            PatternNode current = head;
            while (current.next != null) {
                current = current.next;
            }
            current.next = node;
        }
    }

    public void traverse() {
        System.out.println("My Learning Journey:");
        PatternNode current = head;
        while (current != null) {
            current.display();
            current = current.next;
        }
        System.out.println("🔚 Journey continues...\n");
    }
}
```
```java
public enum Patterns {
    SINGLETON,
    STRATEGY,
    OBSERVER,
    NEURAL_NETWORK,
    DEEP_REFLECTION
}
```

## What I believe

I believe that **every system has its flaws** — technical or human.  
But that’s what makes it interesting.  
I don’t trust default answers. I trust well-asked questions.  
> Are we coding for performance, or just to avoid waste?  
> Are we building something that works, or something people understand?  
Maybe both. Maybe neither. Maybe it depends.

## Random facts

- I keep a journal sometimes — somewhere between philosophy and debugging life  
- I often smile for no reason.
- I ask a thousand questions just to find sometime nothing.

## 📫 Wanna chat AI, backend, life questions, or Smash Bros combos?

Ping me here or [on LinkedIn](https://www.linkedin.com/in/ryan-ashny-rasoarimanana-lai-4406b4310/), or open an issue — who knows, it could be the start of something great.

---

_"It’s not really code that fascinates me — it’s what it reveals about us."_
