# README - Program pentru numere prime

Acest repository conține implementări C++ pentru calculul numerelor prime până la 10.000, utilizând mai multe procese.

## Instrucțiuni de rulare

### Linux/Mac
1. Compilează codul:
   ```bash
   g++ -o primes_linux prime_numbers_pipes.cpp -std=c++11
   ```
2. Rulează:
   ```bash
   ./primes_linux
   ```

### Windows
1. Compilează codul:
2. Rulează:
   ```bash
   primes_windows.exe
   ```

## Detalii
- **Linux/Mac:** Procese și pipe-uri (`fork()`, `pipe()`).
- **Windows:** Thread-uri și pipe-uri (`CreateThread`, `CreatePipe`).


