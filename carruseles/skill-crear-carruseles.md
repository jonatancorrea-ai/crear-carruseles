---
name: crear-carruseles
description: Crea carruseles verticales para Instagram en PNG. Se activa cuando el usuario pide crear un carrusel, convertir una idea en carrusel, desarrollar un tema slide por slide o generar imágenes para un carrusel de Instagram. Primero entrega el contenido en texto para validación y luego genera las imágenes finales.
---

# Crear carruseles

## Objetivo

Crear carruseles verticales para Instagram, slide por slide, en PNG.

## Flujo obligatorio

1. Si el usuario da un tema, idea o prompt, crear o adaptar el carrusel.
2. Si el usuario solo da una idea, investigar con fuentes confiables y construir el contenido desde cero.
3. Entregar primero el contenido en texto, slide por slide, para revisión.
4. Esperar validación o ajustes.
5. Antes de generar las imágenes finales, pedir al usuario la identidad visual si no fue definida.
6. Solo después generar las imágenes PNG, una por una.
7. Usar 7 slides por defecto.
8. Si el usuario pide más slides, ampliar sin problema.

## Identidad visual

Si el usuario no define una identidad visual, preguntar antes de generar imágenes por:

- colores,
- tipografías,
- estilo visual,
- tono de diseño.

No generar las imágenes finales hasta recibir esa información o hasta que el usuario confirme usar una identidad visual por defecto.

## Reglas de contenido

- No alucinar.
- No inventar datos.
- Usar solo información verificable y fuentes confiables cuando el tema lo requiera.
- Si falta contexto crítico, preguntar solo lo mínimo necesario.
- Mantener el texto breve, claro y útil.
- Evitar explicaciones largas.

## Estructura base

Usar AIDA como estructura por defecto:

- Slide 1: Portada / hook.
- Slides 2–3: Problema / contexto.
- Slides 4–6: Solución / valor.
- Slide 7: CTA final.

Si el tema requiere más slides, ampliar manteniendo la lógica del carrusel.

## Formato visual

- Formato vertical: 3:4.
- Tamaño recomendado: 1080 x 1440 px.
- Cada slide debe exportarse como PNG independiente.
- No usar fotos de personas ni objetos reales salvo que el usuario lo pida explícitamente.
- Respetar zonas seguras de Instagram (UI Safe Zones).

## Estilos visuales permitidos

### Agencia editorial premium
Estilo por defecto.
- Composición limpia y sofisticada.
- Jerarquía visual fuerte.
- Tipografía protagonista.
- Mucho orden, aire y contraste.
- Sensación de marca premium.
- Debe verse profesional, como si hubiera sido diseñado por un experto en diseño.
- Todos los textos deben quedar bien alineados, equilibrados y fáciles de leer.

### Minimalista glassmorphism
Usar solo si el usuario lo pide.
- Fondos suaves o oscuros.
- Capas translúcidas.
- Bordes redondeados.
- Sombras sutiles.
- Sensación moderna y limpia.
- Debe verse profesional, como si hubiera sido diseñado por un experto en diseño.
- Todos los textos deben quedar bien alineados, equilibrados y fáciles de leer.

### Dark Mode
Usar solo si el usuario lo pide.
- Contraste agresivo sobre fondo #0F071E.
- Acentos en #7C3AED.
- Glow sutil.
- Sensación fuerte, premium y moderna.
- Debe verse profesional, como si hubiera sido diseñado por un experto en diseño.
- Todos los textos deben quedar bien alineados, equilibrados y fáciles de leer.

## Salida obligatoria

1. Entregar primero el texto del carrusel slide por slide.
2. Esperar validación o ajustes.
3. Pedir identidad visual si aún no fue definida.
4. Generar después las imágenes PNG finales.
5. Si el usuario pide cambios, ajustar antes de renderizar de nuevo.

## Prioridad operativa

- Cero saludos.
- Cero relleno.
- Cero explicaciones innecesarias.
- Ir directo al punto.
- Optimizar el resultado para gastar el menor número posible de tokens sin perder calidad.
