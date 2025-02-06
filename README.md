## Hi, I'm Godless 👋

```csharp
public class Godless {
    public string name;
    public string[] languages;
    public string favourite_lang;
    public string currently_learning;
    public string current_company;
    public int age;
    public string study_at;

    public Godless {
        this.name = "Godless";
        this.languages = {"C#", "C++", "C", "Go"};
        this.favourite_lang = "C#";
        this.currently_learning = "Go";
        this.current_company = "Recovery Toolbox Inc."
        this.age = 18;
        this.study_at = "Central University'28";
    }

    public void welcome(){
        Console.WriteLine($"Hi, I'm {name}. I've lost my god");
    }
}

Godless me = new Godless();
me.welcome();
```
