# Open Claw 🦞
<blockquote style="background-color: #3e1a1a; border-left: 5px solid #ff4d4d; padding: 10px; color: #ffcccc;">
  ⚠️ <strong>Ojo (costos AWS):</strong> Si no vas a utilizar la instancia en AWS, elimínala cuando termines. Se cobra por hora.
</blockquote>

### Donde poder tener una VPS casi gratuita
<p align="center">
  <a>
    <img src="https://skillicons.dev/icons?i=aws,azure,gcp" />
  </a>
</p>

### **Links de VPS gratuitas**

- [AWS](https://aws.amazon.com/es/free/)
- [Azure](https://azure.microsoft.com/es-es/free/)
- [Google Cloud](https://cloud.google.com/free?hl=es-419)

### **Links de VPS gratuitas con tarjeta de crédito**
- [Oracle Cloud](https://www.oracle.com/cloud/free/)
- [Digital Ocean](https://www.digitalocean.com/try/freebalanceline)
- [Linode](https://www.linode.com/lp/free-credit/)

### Forma de obtener una VPS gratuita con el Pack education de GIT HUB con Digital Ocean
<p align="center">
  <a href="https://education.github.com/pack">
    <img src="https://skillicons.dev/icons?i=github" />
  </a>
</p>

Link de video de Youtube como obtener la VPS gratuita con el Pack education de GIT HUB con Digital Ocean
### 📺 Tutorial de Configuración
[![Ver video](https://img.youtube.com/vi/XDSsqncpEzA/maxresdefault.jpg)](https://www.youtube.com/watch?v=XDSsqncpEzA)

*Haz clic en la imagen para ver el proceso paso a paso.*

# Pasos para lanzar instancia en AWS
### 1) Crear la instancia (EC2)

1. Lanzar instancia **EC2**
2. Imagen: **Ubuntu**
3. Tipo de instancia: **c7i-flex.large**
4. Crear **claves privadas**
5. Storage: **30 GiB**
#### 1.1) Como conectarse por SSH
### 📺 Tutorial de Configuración
[![Ver video](https://img.youtube.com/vi/bbKcUJVUHzM/maxresdefault.jpg)](https://www.youtube.com/watch?v=bbKcUJVUHzM)
```bash
ssh -i "clave-privada.pem" ubuntu@ip-publica
```

### 2) Actualizar el sistema

```bash
sudo apt update
sudo apt upgrade
```