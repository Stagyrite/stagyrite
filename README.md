## Certifications

### Professional certifications

[![box](box.png)](https://eltikia.github.io/eltikia/ "Java skills &#124; Stagyrite")

* ⌛ **Time Range:** 2024-2025
* 🗺️ **Location:** [Oracle University](https://www.oracle.com/education/ "Oracle University")
* 👨🏻‍💻 **Person:** [Maciej Matiaszowski](https://stagyrite.github.io/ "Stagyrite &#124; Private Homepage")
* 📈 **Tasks:**
  - [x] [Oracle Certified Associate, Java SE 8 Programmer](https://catalog-education.oracle.com/pls/certview/sharebadge?id=119D68447A8A3235F7FC3C87ACCA5DEA732C69A05A676D39979BDE45FDF81DE1 "Oracle Certified Associate, Java SE 8 Programmer")
  - [x] [Oracle Certified Professional, Java SE 8 Programmer](https://catalog-education.oracle.com/pls/certview/sharebadge?id=9975082503C1283F2B41AA028D2DFA4763196DD3CB7F09D0B0D7BF65DCFCEABA "Oracle Certified Professional, Java SE 8 Programmer") 
  - [x] (Optional) [OCD](https://en.wikipedia.org/wiki/List_of_professional_designations_in_the_United_States "List of professional designations in the United States - Wikipedia") 

### Common in certifications

| 🔢 | 🎯 | Skill |
| :---: | :---: | :---: |
| 1️⃣ | [🧑🏻‍💻](https://www.theserverside.com/ "TheServerSide &#124; Your Java Community discussing server side development") | [Java](https://www.theserverside.com/ "TheServerSide &#124; Your Java Community discussing server side development") |
| 2️⃣ | [🕜](https://docs.oracle.com/javase/8/docs/api/java/time/Clock.html "Clock (Java Platform SE 8 )") | [Java 8 Date And Time API](https://docs.oracle.com/javase/8/docs/api/java/time/Clock.html "Clock (Java Platform SE 8 )") |
| 3️⃣ | ☕ | Java SE 8 |
| 4️⃣ | 🧰 | JDK 8 |
| 5️⃣ | [λ𝑥.𝑥](https://docs.oracle.com/javase/8/docs/api/java/util/function/Predicate.html "Predicate (Java Platform SE 8 )") | [Lambda Expressions](https://docs.oracle.com/javase/8/docs/api/java/util/function/Predicate.html "Predicate (Java Platform SE 8 )") |

```ruby
# speaking Streem
#
# output:
# -- Certifications --
# [*] OCA
# [*] OCP
# [*] OCD

tasksCsv = "OCA,OCP,OCD"
tasks = split(tasksCsv, ",") | map { x -> "[*] " + x }
header = ["-- Certifications --"]
concat(header, tasks) | stdout
```

---
[Maciej Matiaszowski](https://stagyrite.github.io/stagyrite "Certifications &#124; Stagyrite")
