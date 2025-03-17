### **Filtrare Adaptivă a Imaginilor**  
**Procesor utilizat:** Raspberry Pi Pico 2 (RP2040)  

**Algoritm analizat:** Implementarea și optimizarea filtrului **LLMMSE (Locally Linear Minimal Mean Squared Error)** pentru reducerea zgomotului din imagini. Acest filtru aplică o combinație liniară adaptivă între imaginea originală afectată de zgomot și o versiune filtrată prin netezire, ajustând coeficientul de ponderare în funcție de variabilitatea locală.  

### **Obiectivele proiectului:**  
- **Implementarea filtrului LLMMSE** pe Raspberry Pi Pico 2, valorificând setul de instrucțiuni DSP pentru optimizare.  
- **Compararea performanței** metodei LLMMSE cu alte tehnici de filtrare, precum median sau Gaussian.  
- **Testarea eficienței filtrului** pe imagini afectate de zgomot artificial, inclusiv zgomot gaussian și impulsiv.  
- **Evaluarea impactului filtrării** prin metrici obiective precum PSNR și SSIM pentru a cuantifica îmbunătățirea calității imaginii.  
- În funcție de progresul realizat, pot fi investigate și implementate **alte tehnici de filtrare adaptivă**, toate actualizările urmând a fi documentate pe GitHub.  





