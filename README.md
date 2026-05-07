<h1 align="center">Heyyy I'm Calebe 👾</h1>

```java
import java.time.DayOfWeek;
import java.time.LocalDateTime;
import java.time.Year;
import java.util.List;

class Me extends Programmer {

    String name = "Calebe";
    String username = "canotdev";

    List<String> languages = List.of(
            "English",
            "Brazilian Portuguese"
    );

    int age = Year.now().getValue() - 2005;

    void work() {
        DayOfWeek today = LocalDateTime.now().getDayOfWeek();

        String beverage =
                today == DayOfWeek.FRIDAY
                        ? "beer"
                        : "coffee";

        drink(beverage);
        code();
        sleep();
    }

    public static void main(String[] args) {
        Me me = new Me();
        me.work();
    }
}
```
<p align="center">
  <a href="https://github.com/cntoliveira">
    <img height="180em" src="https://github-readme-stats-sigma-five.vercel.app/api?username=cntoliveira&show_icons=true&bg_color=00000000&title_color=FFD700&text_color=FFD700&icon_color=FFD700&border_color=FFFFFF"/>
  </a>
  
  <a href="https://github.com/cntoliveira">
    <img height="180em" src="https://github-readme-stats-sigma-five.vercel.app/api/top-langs/?username=cntoliveira&layout=compact&langs_count=8&bg_color=00000000&title_color=FFD700&text_color=FFD700&border_color=FFFFFF"/>
  </a>
</p>
