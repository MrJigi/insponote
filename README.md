# insponote
C# .NET application that allows users to create various templates for notes, picture refferences to allow better visualization

The Tech stack considerations:

* ASP.NET Core (Web API)
* Blazor (WASM)

Next phase implementation

* .NET MAUI (Native integration)

📚 Learning Curve Overview
Tech	Learning Curve	Job Value
ASP.NET Core (Web API)	Moderate	⭐⭐⭐⭐ (Industry standard)
Blazor (WASM)	Easy–Moderate	⭐⭐⭐ (Growing adoption)
.NET MAUI	Moderate–High	⭐⭐ (Newer, fewer jobs but future-proof)
React/Flutter	High (JS/Dart)	⭐⭐⭐⭐ (Outside .NET scope)

--- Reasons ---

🎯 ASP.NET Core

    Purpose: Build web apps (traditional websites, REST APIs, Razor pages, Blazor Server/WebAssembly).

    Runs on: Web browsers (desktop/mobile).

    Key Benefit: Backend skills widely used in enterprise.

    Used For: REST APIs, web portals, admin dashboards, Blazor apps.

 📱.NET MAUI (Multi-platform App UI)

    Purpose: Build native apps for Android, iOS, Windows, macOS with a single C# codebase.

    Runs on: Mobile and desktop.

    Key Benefit: Mobile experience in C#, tightly integrated with .NET.

    Used For: Mobile apps, native UIs, Blazor Hybrid apps.
    
--- Phases ---

✅ Phase 1: Start With ASP.NET Core + Blazor WebAssembly

    Create your visual note/task board UI with drag-and-drop.

    Use Blazor for interactivity, stay in C# and Razor.

    Build the backend as a Web API (or just use local storage initially).

    Deploy as a PWA so it works on mobile browsers.

✅ Benefits:

    100% in C#, no JavaScript required.

    Can later wrap in MAUI or migrate to MAUI Hybrid.

    Easiest way to get started and show off your app on GitHub.

✅ Phase 2: Add .NET MAUI Version (optional)

    Reuse some of the logic/UI from Blazor.

    Use MAUI to build a native shell and embed your Blazor app (Hybrid).

    Connect to your ASP.NET Core backend for real data syncing.
