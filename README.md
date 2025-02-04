# 4100901-Final_Project_2024_2

## Guía de Git

### **Configuración**
1. **Haz un fork del repositorio** en GitHub.
2. **Clona tu fork** en tu computadora:
   ```sh
   git clone https://github.com/TU-USUARIO/reponame.git
   cd reponame
   ```
3. **Agrega el repositorio de Sam como upstream** (para obtener actualizaciones):
   ```sh
   git remote add upstream https://github.com/INSTRUCTOR-USERNAME/reponame.git
   git fetch upstream
   ```

### **Manteniendo Tu Rama `main` Actualizada**
1. **Cambia a `main`**:
   ```sh
   git checkout main
   ```
2. **Obtén actualizaciones del repositorio del instructor**:
   ```sh
   git fetch upstream
   git merge upstream/main
   git push origin main
   ```

### **Trabajando en una Nueva Funcionalidad o Tarea**
1. **Crea una nueva rama**:
   ```sh
   git checkout -b feature-branch
   ```
2. **Realiza cambios y confirma los cambios**:
   ```sh
   git add .
   git commit -m "Describe tu cambio"
   ```
3. **Sube la rama a tu fork**:
   ```sh
   git push origin feature-branch
   ```

## **Buenas Prácticas**
✅ Mantén `main` limpio y actualizado.  
✅ Siempre crea una nueva rama para cambios.  
✅ Escribe mensajes de confirmación claros.  
✅ ¡Pide ayuda si algo no está claro! 🚀
