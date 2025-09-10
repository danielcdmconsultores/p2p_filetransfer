# p2p_filetransfer

- Transferencia de ficheros entre equipos de forma fiable, sin rastro, sin servidor, de equipo a equipo p2p.
- Encriptación en tránsito. mediante ssl.
- Super url bien ofuscada, dificil de adivinar.
- Se usa WebRTC, un protocolo de transmisión directa que los navegadores modernos tienen activado de forma nativa. WebRTC (Comunicación Web en Tiempo Real) es una tecnología de código abierto que permite a los navegadores web y aplicaciones móviles capturar, reproducir y transmitir audio y video, así como intercambiar datos, directamente entre usuarios (punto a punto) y sin necesidad de instalar complementos o software adicional.
- No requiere ningún servidor intermedio, excepto para el intercambio de información de conexión PeerServer ver: https://webrtc.org/getting-started/turn-server?hl=es-419
- Usa PeerServer para intermediar las conexiones, PeerJS se conecta a un PeerServer. Ningún dato peer-to-peer pasa por el servidor; el servidor actúa únicamente como intermediario de conexiones, a la hora de inicializar la comunicación.
- Unico archivo html, no requiere más, es simple.
