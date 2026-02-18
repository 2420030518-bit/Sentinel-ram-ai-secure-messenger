# SentinelRAM – AI Secure Ephemeral Messenger

SentinelRAM is an AI-powered RAM-only secure communication platform built for high-risk environments.

## Key Features

- RAM-only architecture (no disk persistence)
- Post-Quantum Encryption (X25519 + ChaCha20-Poly1305)
- AI-powered face verification
- Intrusion detection auto-lock
- Periodic re-authentication
- Emergency memory purge (F12)

## Architecture

Client → Encrypted Channel → Secure Relay Server → Client

All encryption is performed client-side.

## Technologies

- Python
- FastAPI
- PyNaCl
- OpenCV
- CustomTkinter
- AMD GPU Acceleration

## Usage

1. Install dependencies
2. Start server
3. Launch client
4. Register face
5. Begin secure communication

