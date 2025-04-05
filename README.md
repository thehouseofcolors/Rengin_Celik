/*
 * ===== RENGIN ÇELIK | UNITY DEVELOPER (MOBILE GAMES) =====
 * Focus: Hyper-Casual, Puzzle, Optimization, UI/UX
 */

[System.Serializable]
public class Skills {
    [Header("Core Development")]
    public bool Unity;
    public bool CSharp;
    public bool MobileGameDev;

    [Header("Game Systems")]
    public bool HyperCasualMechanics;
    public bool PuzzleDesign;
    public bool GridBasedSystems;
    public bool UIUX_Development;

    [Header("Optimization")]
    public bool ObjectPooling;
    public bool StateMachines;
    public bool EventDrivenArchitecture;
    public bool MemoryManagement;
}

public class Projects {
    public string EndlessRunner = "Optimized endless runner with procedural mechanics";
    public string SimulationGame = "Resource management + inventory system";
}

public class Contact {
    public const string Email = "rengin.celik97@gmail.com";
    public const string LinkedIn = "linkedin.com/in/rengincelik";
}

// ===== OBJECTIVE =====
// Goal: Build high-performance mobile games with clean mechanics and smooth UX.
// Seeking collaborations, tech discussions, and challenging projects.

#if UNITY_EDITOR
[ContextMenu("Reach Out")]
void OpenContactLinks() {
    Application.OpenURL("mailto:" + Contact.Email);
    Application.OpenURL("https://" + Contact.LinkedIn);
}
#endif

/* 
 * Let's connect and create something fun! 🎮
 * - Rengin
 */
