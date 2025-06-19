# ⚡ ZAPdos - Scanner ZAP via API

![image](https://github.com/user-attachments/assets/99ffd328-e7e9-4f2d-b53d-d83a2438bc7e)


ZAPdos est un outil Python simple et rapide pour automatiser des scans de sécurité avec **OWASP ZAP** via son API REST, sans dépendre de `zap-cli`.  
Idéal pour les pentesters, DevSecOps, ou les intégrations CI/CD.

---

## 🎯 Fonctionnalités

- 🔍 Scan web ou API (spider + active scan)
- 📦 Support de fichiers de cibles multiples
- 🔑 Authentification supportée (basique + API key)
- 📊 Génération automatique de rapports HTML & JSON
- 🚀 Progression visuelle grâce à `tqdm`
- 💻 Sans dépendance lourde (pas besoin de zap-cli)

---

## 🧱 Prérequis

- [OWASP ZAP](https://www.zaproxy.org/download/) installé et en mode **daemon** (`zap.sh -daemon`)
- Python 3.x
- `curl`, `tqdm` installés

> ⚠️ Le démon ZAP doit être en cours d'exécution avant d'utiliser ZAPdos.

---

## ⚙️ Installation

Clone du dépôt :

```bash
git clone https://github.com/tonutilisateur/ZAPdos.git
cd ZAPdos
