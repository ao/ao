<h1 align="center">whoami</h1>

```python
class Engineer:
    def __init__(self):
        self.focus = ["distributed systems", "developer tooling", "cloud infra"]
        self.stack = ["Python", "Go", "Rust", "Java", "TypeScript"]
        self.status = "always building"

    def __repr__(self):
        return "curious. pragmatic. ships things."
```

---

### 🧩 Puzzle of the moment

The same loop, four languages. Three of them print the **same** number. One is the odd one out.

<table>
<tr>
<td>

```python
# Python
x = 0
for i in range(5):
    x += i
print(x)
```

</td>
<td>

```go
// Go
x := 0
for i := 0; i < 5; i++ {
    x += i
}
fmt.Println(x)
```

</td>
</tr>
<tr>
<td>

```java
// Java
int x = 0;
for (int i = 1; i <= 5; i++) {
    x += i;
}
System.out.println(x);
```

</td>
<td>

```javascript
// JavaScript
let x = 0;
for (let i = 0; i < 5; i++) {
  x += i;
}
console.log(x);
```

</td>
</tr>
</table>

**Which one is the odd one out — and what does it print?**

<details>
<summary>💡 Reveal answer</summary>

<br>

**Java** is the odd one out. Its loop runs `i` from **1 through 5** (`0+1+2+3+4+5` = **15**), while Python, Go, and JavaScript all run `i` from **0 through 4** (`0+1+2+3+4` = **10**).

```
Python → 10
Go     → 10
JS     → 10
Java   → 15   ← odd one out
```

Off-by-one bugs: the reason code review exists. 🐛

</details>

---

### 🧰 Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)

---

### 🚀 Featured Projects

| Project | Description | Stack |
| :--- | :--- | :--- |
| **[ktmm-py](https://github.com/ao/ktmm-py)** | Keep That Mouse Moving — cross-platform utility to keep your machine awake | `Python` |
| **[Serengeti](https://github.com/ao/Serengeti)** | An autonomous, self-managing distributed database | `Java` |
| **[hivemind](https://github.com/ao/hivemind)** | Lightweight distributed container orchestration platform | `Go` |
| **[pyroid](https://github.com/ao/pyroid)** | Blazing-fast Rust-powered utilities to eliminate Python's bottlenecks | `Rust` |
| **[favicons](https://github.com/ao/favicons)** | Favicons for all — simple, reliable favicon serving | `PHP` |
| **[RunJavascript](https://github.com/ao/RunJavascript_ChromeExtension)** | Chrome extension to run custom JavaScript on any page | `JavaScript` |

<br>

```bash
$ echo "thanks for stopping by" | figlet
```
