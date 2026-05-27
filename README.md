# Graphics

A WinForms app that renders an interactive 3D torus wireframe. Supports rotation via right-click drag and panning via left-click drag.

## Tech Stack

C#, .NET Framework 4.7.2, WinForms, System.Drawing

## Quick Start

**Via Visual Studio:**

```
1. Open Graphics/Graphics.sln
2. Build → Start (F5)
```

**Via CLI (MSBuild):**

```bash
msbuild Graphics/Graphics.csproj /p:Configuration=Release
Graphics\Graphics\bin\Release\Graphics.exe
```

## Controls

| Input | Action |
|---|---|
| Right-click drag | Rotate torus (X/Y axis) |
| Left-click drag | Pan |
| Window resize | Recalculates geometry |
