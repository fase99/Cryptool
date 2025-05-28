# 🔐 Cryptool CLI – Herramienta de cifrado AES / DES / 3DES en Python

Cryptool es una herramienta de línea de comandos escrita en Python que permite **cifrar y descifrar textos** utilizando tres algoritmos clásicos de criptografía simétrica:

- AES-256 (CBC)
- DES (CBC)
- 3DES (CBC)

---

## ✨ Características

- Soporta cifrado y descifrado con **AES-256**, **DES**, y **3DES**
- Modo CBC con padding automático
- Claves e IVs adaptadas automáticamente al tamaño requerido
- Soporte completo de **Base64** para entradas y salidas cifradas
- Interfaz interactiva por terminal
- Comando disponible globalmente al instalar con `pipx`

---

## 📦 Requisitos

- Python 3.8 o superior
- [`pipx`](https://pypa.github.io/pipx/) instalado

---

## ⚙️ Instalación (Linux)

### 1. Instala `pipx` (si no lo tienes):

```bash
sudo apt update
sudo apt install pipx -y
pipx ensurepath
source ~/.bashrc  # o reinicia la terminal
```

### 2. Clonar repositorio:
```bash
git clone https://github.com/fase99/Cryptool
```

### 3. Instalar herramienta: 
```bash
cd Cryptool
pipx install .
```

