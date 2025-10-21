# Process-Explorer Preview

[![Language: C++](https://img.shields.io/badge/Lang-C%2B%2B-lightgrey.svg)](https://isocpp.org)
[![Language: C%23](https://img.shields.io/badge/Lang-C%23-blue.svg)](https://docs.microsoft.com/dotnet/csharp/)

<p align="center">
<img width="2338" height="897" alt="Снимок экрана 2025-08-11 003554" src="https://github.com/user-attachments/assets/efd99090-de9d-43cb-860d-0399e285c90f" />
</p>

## Summary

Process Explorer is an in‑development tool for monitoring and managing Windows processes. It combines a WinUI 3 front end with managed (C#) and native (C++) back ends to provide real‑time metrics and process control. An experimental branch exposes deeper capabilities via NTAPI for research and advanced diagnostics.

**Status:** Alpha (in development)

# ScreensShots

<p align="center">
  <img width="2879" height="1521" alt="Снимок экрана 2025-08-05 131532" src="https://github.com/user-attachments/assets/9f43a0fd-3422-4e97-8845-0fda091ada4f" />
  <img width="2879" height="1517" alt="Снимок экрана 2025-08-05 131521" src="https://github.com/user-attachments/assets/fa341e48-fa33-44ef-9cfc-5a3c5fad8223" />
</p>

## Key Features

* Live process metrics: CPU, memory, basic GPU statistics
* Process control: start, suspend, resume, terminate
* Native C++ backend for low‑level system integration
* Experimental NTAPI branch for advanced diagnostics (unstable)

Select the appropriate platform (x64) and configuration (Debug/Release) and run from Visual Studio.

## Pages

* **Metrics**: aggregated CPU/memory usage and per‑process statistics
* **Actions**: launch, suspend, resume, and terminate processes
