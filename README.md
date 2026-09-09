# 📺 EL CHACO 22 - IPTV MUNDIAL PREMIUM

<p align="center">
  <img src="./assets/elchaco22_logo_transparent.png" width="200" alt="EL CHACO 22 Logo"/>
</p>

<p align="center">
  <b>TV gratis para tu Smart TV que se actualiza sola todos los días</b><br>
  Argentina, Brasil, Chile, México, España, USA y 100+ países
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Argentina-elchaco22-green?style=for-the-badge&logo=tv" />
  <img src="https://img.shields.io/badge/Actualiza-3AM%20UTC-blue?style=for-the-badge&logo=github" />
  <img src="https://img.shields.io/badge/Auto--limpia-Canales%20muertos-orange?style=for-the-badge" />
</p>

---

## 🚀 Links directos para Smart TV (pega esto en TiviMate / SS IPTV / VLC)

> ✅ **Se actualizan automáticamente cada día a las 3 AM UTC por GitHub Actions. No necesitas re-escanear.**

### 🇦🇷 Argentina (Recomendado)

```
https://elchaco22.github.io/iptv-mundial/Argentina_ACTIVOS.m3u
```

### 🌍 Mundial - Todos los países

```
https://elchaco22.github.io/iptv-mundial/MUNDIAL_ACTIVOS.m3u
```

### 📋 Todos los países

| País | Link ACTIVOS (solo los que andan) | Link completo |
|------|-----------------------------------|---------------|
| 🇦🇷 Argentina | [`Argentina_ACTIVOS.m3u`](https://elchaco22.github.io/iptv-mundial/Argentina_ACTIVOS.m3u) | [`Argentina.m3u`](https://elchaco22.github.io/iptv-mundial/Argentina.m3u) |
| 🇧🇷 Brasil | [`Brasil_ACTIVOS.m3u`](https://elchaco22.github.io/iptv-mundial/Brasil_ACTIVOS.m3u) | [`Brasil.m3u`](https://elchaco22.github.io/iptv-mundial/Brasil.m3u) |
| 🇨🇱 Chile | [`Chile_ACTIVOS.m3u`](https://elchaco22.github.io/iptv-mundial/Chile_ACTIVOS.m3u) | [`Chile.m3u`](https://elchaco22.github.io/iptv-mundial/Chile.m3u) |
| 🇲🇽 México | [`Mexico_ACTIVOS.m3u`](https://elchaco22.github.io/iptv-mundial/Mexico_ACTIVOS.m3u) | [`Mexico.m3u`](https://elchaco22.github.io/iptv-mundial/Mexico.m3u) |
| 🇪🇸 España | [`Espana_ACTIVOS.m3u`](https://elchaco22.github.io/iptv-mundial/Espana_ACTIVOS.m3u) | [`Espana.m3u`](https://elchaco22.github.io/iptv-mundial/Espana.m3u) |
| 🇺🇸 USA | [`Estados_Unidos_ACTIVOS.m3u`](https://elchaco22.github.io/iptv-mundial/Estados_Unidos_ACTIVOS.m3u) | [`Estados_Unidos.m3u`](https://elchaco22.github.io/iptv-mundial/Estados_Unidos.m3u) |
| 🌍 Mundial | [`MUNDIAL_ACTIVOS.m3u`](https://elchaco22.github.io/iptv-mundial/MUNDIAL_ACTIVOS.m3u) | [`MUNDIAL.m3u`](https://elchaco22.github.io/iptv-mundial/MUNDIAL.m3u) |

**Página con todos:** 👉 https://elchaco22.github.io/iptv-mundial/

---

## 📱 QR para escanear con el celular

<p align="center">
  <img src="./assets/QR_Argentina_elchaco22.png" width="250" />
  <img src="./assets/QR_Mundial_elchaco22.png" width="250" />
</p>

- **Argentina:** `assets/QR_Argentina_elchaco22.png`
- **Mundial:** `assets/QR_Mundial_elchaco22.png`
- **Todos:** `assets/QR_Pagina_elchaco22.png`

---

## 🖨️ Material para imprimir

- [Póster A4 con todos los QR](./assets/POSTER_ELCHACO22_PREMIUM_A4.png) - Para pegar al lado de la tele
- [Póster A4 PDF](./assets/POSTER_ELCHACO22_PREMIUM_A4.pdf)
- [Tarjeta billetera Argentina](./assets/TARJETA_ELCHACO22_PREMIUM.png) - Tamaño tarjeta de crédito
- [Tarjeta PDF](./assets/TARJETA_ELCHACO22_PREMIUM.pdf)

---

## 📺 Cómo usar en tu Smart TV

1. **Copiá** el link de Argentina: `https://elchaco22.github.io/iptv-mundial/Argentina_ACTIVOS.m3u`
2. **Abrí** en tu TV: SS IPTV / Smart IPTV / TiviMate / VLC > Añadir lista > Añadir URL
3. **Pegá** el link y guardá
4. **¡Listo!** 100+ canales argentinos. Se limpia solo cada día.

### Apps recomendadas:

- **Android TV / Firestick:** TiviMate (la mejor), IPTV Smarters Pro
- **Samsung / LG:** SS IPTV, Smart IPTV, IPTV
- **PC / Celular:** VLC > Medio > Abrir ubicación de red
- **Kodi:** PVR IPTV Simple Client

---

## ⚙️ Cómo funciona (tecnología)

Este repo usa:

- **Fuente:** [iptv-org/iptv](https://github.com/iptv-org/iptv) - 10.000+ canales
- **Verificación:** 40 hilos paralelos que testean que el stream responde
- **GitHub Actions:** Corre todos los días a las 3 AM UTC
- **GitHub Pages:** Publica automáticamente los `.m3u` filtrados
- **Auto-limpieza:** Solo quedan los canales que responden HTTP 200

Código fuente del autopublish: https://github.com/elchaco22/iptv-mundial

---

## 🔧 Instalación de tu propio autopublish

Si querés tener tu propia versión:

```bash
git clone https://github.com/elchaco22/iptv-mundial.git
cd iptv-mundial
pip install -r requirements.txt
python app.py --update  # Descarga y verifica
python app.py           # Levanta web en localhost:5000
```

Ver [VIDEO_GUIA_PASOS.md](./VIDEO_GUIA_PASOS.md) y usar `push_elchaco22.sh`

---

## 📄 Licencia y Disclaimer

Listas de canales públicos de [iptv-org](https://github.com/iptv-org/iptv). Solo se enlazan streams gratuitos y legales. No alojamos contenido. Si un canal no te pertenece, contactá al dueño del stream.

---

<p align="center">
  <b>EL CHACO 22 - IPTV MUNDIAL PREMIUM</b><br>
  Hecho con ❤️ en Resistencia, Chaco, Argentina<br>
  <a href="https://elchaco22.github.io/iptv-mundial/">https://elchaco22.github.io/iptv-mundial/</a>
</p>
