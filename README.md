# ⚽ El Fulbo y Yo

> **"Mi historia, mis colores, mi potrero."**

**El Fulbo y Yo** es un portafolio interactivo y red social diseñado para el futbolista amateur. Permite documentar cada club, cada gol y cada etapa de tu carrera, desde el baby fútbol hasta los torneos de veteranos, con una estética inspirada en los grandes clásicos del gaming.

---

## 🚀 Vision del Proyecto
El objetivo es transformar la nostalgia del fútbol en una ficha técnica profesional. La app permite generar un **Timeline de Carrera** y una **Player Card** con atributos dinámicos, posicionándose como el "LinkedIn del fútbol amateur argentino".

## 🎮 Modos de Interfaz (Multi-Theme)
La plataforma permite alternar entre 3 experiencias visuales únicas:
* **Retro Mode:** Inspirado en la mística del **PES 6** (Pixel art, fuentes clásicas, alta saturación).
* **Gaming Modern:** Estética tipo Discord/Twitch con vidrios (Glassmorphism) y neones.
* **Minimalist:** Un enfoque limpio, tipográfico y funcional para uso diario.

## 🛠️ Stack Tecnológico
Para garantizar escalabilidad y una experiencia premium, utilizamos:
* **Framework:** [Next.js 15](https://nextjs.org/) (App Router).
* **Optimización:** [React Compiler](https://react.dev/learn/react-compiler) (Beta) para un renderizado ultra-eficiente.
* **Base de Datos:** [Supabase](https://supabase.com/) (PostgreSQL + Auth + Storage).
* **Estilos:** CSS Modules (Preparado para la transición a React Native).
* **Animaciones:** Framer Motion.

## 📦 Estructura de Monorepo
Diseñado para evolucionar de Web a Mobile sin fricción:
- `apps/web`: Aplicación principal en Next.js.
- `apps/mobile`: (Próximamente) App nativa con Expo.
- `packages/ui`: Componentes compartidos y Design System propio.
- `packages/utils`: Lógica de cálculo de estadísticas y constantes.

---
*Desarrollado con ❤️ por [Leonardo Romero](https://github.com/leoromero97)*
