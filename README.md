# Laboratorio de informática: red en 3D y AR

Maqueta 3D interactiva de la red del laboratorio **«Frente»**, armada a partir del trabajo práctico *Conozco mi laboratorio* (Redes II, 5°, E.P.E.T N° 38, 2026).

**Alumna:** Anger Micaela · **Grupo:** Acosta Ximena y Nuñez Mia · **Profesora:** Pellegrini Natalia

## Qué muestra

- 19 PC (`Lab-1-Prof` y `Lab-1-1` a `Lab-1-18`), 2 switches, 1 router, 1 servidor y 1 impresora.
- Los 23 cables de la topología, coloreados por tipo de conexión.
- Direccionamiento: red `192.168.56.0/24`, máscara `255.255.255.0`, clase C.
- Al tocar un equipo se ve su tipo, modelo, IP y a qué está conectado.
- Botón **Tabla de IP** con los 19 hosts, y botón **Ver en AR** para verlo en el celular.

## Cómo se hizo

1. La topología (equipos, posiciones y enlaces) se extrajo del archivo de Cisco Packet Tracer `conozco_mi_laboratorio_1_Anger.pkt`.
2. Las direcciones IP, máscaras y clase de red salen del documento del trabajo práctico.
3. La escena 3D usa [three.js](https://threejs.org/) y la realidad aumentada usa [model-viewer](https://modelviewer.dev/) de Google. Todo es software gratuito y corre en el navegador, sin instalar nada.

## Cómo usarlo

Abrí la página y arrastrá para girar, usá la rueda o el pellizco para acercar y tocá un equipo para ver sus datos. Para AR, abrila desde un celular Android (Chrome) o iPhone (Safari) y tocá **Ver en AR**. También podés bajar el modelo con **Descargar .glb**.

## Archivos

- `index.html`: la página completa (un solo archivo).
