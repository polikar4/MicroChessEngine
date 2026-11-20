# MicroСhessEngine

## Сборка

Нужен **WinLibs** (gcc/clang в PATH) — ставится, например:

```powershell
winget install BrechtSanders.WinLibs.POSIX.UCRT.LLVM
```

Из корня репо:

```powershell
gcc -std=c11 -Wall -O2 -o build/micro.exe core/main.c
```