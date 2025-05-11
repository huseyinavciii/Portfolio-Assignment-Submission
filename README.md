# 💻 C# .NET Developer Portfolio

[![GitHub followers](https://img.shields.io/github/followers/huseyinavciii?style=social)](https://github.com/huseyinavciii)
[![GitHub stars](https://img.shields.io/github/stars/huseyinavciii/Portfolio-Assignment-Submission?style=social)](https://github.com/huseyinavciii/Portfolio-Assignment-Submission/stargazers)

<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/csharp/csharp-original.svg" alt="csharp" width="50" height="50"/>

*This portfolio showcases my journey into C# and .NET development through a series of progressive projects*

---

## 🚀 Projects

<!-- PROJECT LIST START -->
<div align="center">
  <a href="https://github.com/huseyinavciii/Polymorphism-Assignment-Submission">
    <img src="https://img.shields.io/badge/Polymorphism%20Project-4B275F?style=for-the-badge&logo=csharp&logoColor=white" alt="Polymorphism Project"/>
  </a>
  <a href="https://github.com/huseyinavciii/Operators-Assignment-Submission">
    <img src="https://img.shields.io/badge/Operator%20Overloading-FF9E0F?style=for-the-badge&logo=csharp&logoColor=white" alt="Operators Project"/>
  </a>
  <a href="https://github.com/huseyinavciii/Method-Class-Assignment-Submission">
    <img src="https://img.shields.io/badge/Methods%20%26%20Classes-00C853?style=for-the-badge&logo=csharp&logoColor=white" alt="Methods & Classes Project"/>
  </a>
  <a href="https://github.com/huseyinavciii/ASP.NET-MVC-Entity-Framework">
    <img src="https://img.shields.io/badge/ASP.NET%20MVC-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" alt="ASP.NET MVC Project"/>
  </a>
  <a href="https://github.com/huseyinavciii/Final-Assignment-Submission">
    <img src="https://img.shields.io/badge/Final%20Project-1565C0?style=for-the-badge&logo=csharp&logoColor=white" alt="Final Project"/>
  </a>
</div>
<!-- PROJECT LIST END -->

## 📊 Project Highlights

<div class="project-grid">

<details>
<summary><h3>🔹 Polymorphism Implementation</h3></summary>

```csharp
// Sample code demonstration
public interface IQuittable
{
    void Quit();
}

public class Employee : IQuittable
{
    public void Quit()
    {
        Console.WriteLine("Employee is quitting the job...");
    }
}

// Usage example
IQuittable quittableObject = new Employee();
quittableObject.Quit(); // Polymorphism in action
```

**Key Features:**
- Implementation of interfaces for polymorphic behavior
- Demonstration of object abstraction
- Runtime type identification

[View Project →](https://github.com/huseyinavciii/Polymorphism-Assignment-Submission)
</details>

<details>
<summary><h3>🔹 Operator Overloading</h3></summary>

```csharp
// Sample code demonstration
public class Employee
{
    public int Id { get; set; }
    
    public static bool operator ==(Employee employee1, Employee employee2)
    {
        return employee1.Id == employee2.Id;
    }
    
    public static bool operator !=(Employee employee1, Employee employee2)
    {
        return !(employee1 == employee2);
    }
}
```

**Key Features:**
- Custom operator implementation
- Equality comparison logic
- Proper GetHashCode and Equals overrides

[View Project →](https://github.com/huseyinavciii/Operators-Assignment-Submission)
</details>

<details>
<summary><h3>🔹 Methods & Classes</h3></summary>

```csharp
// Sample code demonstration
public class MathOperations
{
    public int Add(int a, int b)
    {
        return a + b;
    }
    
    public int Add(int a, int b, int c)
    {
        return a + b + c;
    }
    
    public double Add(double a, double b)
    {
        return a + b;
    }
}
```

**Key Features:**
- Method overloading demonstrations
- Class structure and design
- Parameter handling variations

[View Project →](https://github.com/huseyinavciii/Method-Class-Assignment-Submission)
</details>

<details>
<summary><h3>🔹 ASP.NET MVC Application</h3></summary>

```csharp
// Sample code demonstration
public class HomeController : Controller
{
    private readonly ApplicationDbContext _context;
    
    public HomeController(ApplicationDbContext context)
    {
        _context = context;
    }
    
    public IActionResult Index()
    {
        var items = _context.Items.ToList();
        return View(items);
    }
}
```

**Key Features:**
- Model-View-Controller architecture
- Entity Framework database integration
- Responsive web interface design

[View Project →](https://github.com/huseyinavciii/ASP.NET-MVC-Entity-Framework)
</details>

<details>
<summary><h3>🔹 Final Project</h3></summary>

This comprehensive project combines multiple aspects of C# development including:

- Advanced object-oriented programming techniques
- Design patterns implementation
- Data access and management
- User interface design
- Error handling and logging

[View Project →](https://github.com/huseyinavciii/Final-Assignment-Submission)
</details>

</div>

## 🛠️ Technologies & Tools

<div align="center">
  
![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=c-sharp&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-5C2D91?style=flat-square&logo=.net&logoColor=white)
![ASP.NET](https://img.shields.io/badge/ASP.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Entity Framework](https://img.shields.io/badge/Entity%20Framework-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Visual Studio](https://img.shields.io/badge/Visual%20Studio-5C2D91?style=flat-square&logo=visual-studio&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?style=flat-square&logo=microsoft-sql-server&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
  
</div>

## 📋 About This Portfolio

This repository serves as a central hub for my C# projects, showcasing my progression from fundamental concepts to complex applications:

1. **Beginning with C# Basics**: Understanding core language features
2. **Advancing to OOP Principles**: Implementing polymorphism, inheritance, and encapsulation
3. **Building Web Applications**: Creating dynamic websites with ASP.NET MVC
4. **Database Integration**: Working with data persistence using Entity Framework
5. **Project Architecture**: Applying proper design patterns and software architecture

## 📚 Installation & Setup

```bash
# Clone any project repository
git clone https://github.com/huseyinavciii/[repository-name]

# Open in Visual Studio or use .NET CLI
dotnet restore
dotnet build
dotnet run
```

---

<div align="center">
  <sub>Created with ❤️ by Hüseyin Avcı</sub>
  <p>Connect with me on GitHub: <a href="https://github.com/huseyinavciii">@huseyinavciii</a></p>
</div>
