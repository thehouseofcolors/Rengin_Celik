# **Rengin Çelik**  
### `🎮 Unity Game Dev` | `C#` | `📱 Mobile Dev`  

```csharp
// ========== CORE INTERFACE ========== //
public interface IGameDeveloper {
    void OptimizePerformance();
    void ImplementGameplayMechanics();
    void DesignUIUX();
}

// ========== SKILLS IMPLEMENTATION ========== //
public class DevProfile : MonoBehaviour, IGameDeveloper {
    [Header("🛠️ Core Competencies")]
    public bool Unity = true;
    public bool CSharp = true;
    public bool MobileGames = true;

    [Header("🎮 Specializations")]
    public bool HyperCasual = true;
    public bool PuzzleMechanics = true;
    public bool PerformanceOptimization = true;

    public void OptimizePerformance() {
        // Implementation: Object Pooling, Memory Management, etc.
    }

    public void ImplementGameplayMechanics() {
        // Implementation: State Machines, Event Systems, etc.
    }

    public void DesignUIUX() {
        // Implementation: UI Flow, UX Polish, etc.
    }
}

// ========== PROJECT SHOWCASE ========== //
[System.Serializable]
public struct Project {
    public string Name;
    public string Description;
    
    public static Project[] Portfolio = {
        new Project {
            Name = "Endless Runner",
            Description = "Optimized procedural generation system"
        },
        new Project {
            Name = "Resource Simulator", 
            Description = "Inventory management with data-driven design"
        }
    };
}
```

// ========== CONTACT ========== //
public static class Connect {
    public const string Email = "📧 rengin.celik97@gmail.com";
    public const string LinkedIn = "🔗 linkedin.com/in/rengincelik";
}
```

### **🚀 Mission**  
```diff
+ "Build buttery-smooth mobile games with addictive mechanics."
+ "Passionate about clean code and performance-first design."
```

### **📫 Let's Talk**  
[//]: # (Functional but invisible links)
[Email](mailto:rengin.celik97@gmail.com) | 
[LinkedIn](https://linkedin.com/in/rengincelik)


---
<p align="center">
  <i>🔥 Open to collabs, tech chats, and wild game ideas!</i>
</p>
