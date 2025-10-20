# 🏠 Home Assistant Blueprints Collection

[![GitHub stars](https://img.shields.io/github/stars/danimart1991/home-assistant-blueprints?style=flat)](https://github.com/danimart1991/home-assistant-blueprints/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/danimart1991/home-assistant-blueprints?style=flat)](https://github.com/danimart1991/home-assistant-blueprints/network/members)
[![GitHub issues](https://img.shields.io/github/issues/danimart1991/home-assistant-blueprints)](https://github.com/danimart1991/home-assistant-blueprints/issues)
[![GitHub license](https://img.shields.io/github/license/danimart1991/home-assistant-blueprints)](https://github.com/danimart1991/home-assistant-blueprints/blob/main/LICENSE)

[![Tip Me via PayPal](https://img.shields.io/badge/PayPal-tip%20me-blue.svg?logo=paypal&style=flat)](https://www.paypal.me/danimart1991)
[![Sponsor Me via GitHub](https://img.shields.io/badge/GitHub-sponsor%20me-blue.svg?logo=github&style=flat)](https://github.com/sponsors/danimart1991)

A curated collection of powerful and practical Home Assistant blueprints designed to solve common automation challenges. Each blueprint includes detailed documentation in multiple languages and real-world use cases.

## ✨ Features

- 🔄 **Ready-to-use automations** for common smart home problems
- 🌍 **Multi-language support** (English & Spanish)
- 📱 **One-click import** with Home Assistant badges
- 💡 **Detailed documentation** with examples and use cases
- 🚀 **Production-ready** configurations tested in real environments
- 🔗 **Additional resources** with links to detailed guides

## 📋 Available Blueprints

### 🔄 Reload Integrations Automatically / Recargar Integraciones Automáticamente

#### 🇺🇸 English Version

Automatic recovery system for integrations that get "stuck" or become unavailable in Home Assistant. Perfect for AEMET weather integration, Xiaomi/Roborock devices, external APIs, and Wi-Fi sensors.

[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fraw.githubusercontent.com%2Fdanimart1991%2Fhome-assistant-blueprints%2Fmain%2Fautomation%2Freload-integrations%2Freload-integrations.en.yaml)

- **📁 File:** [`reload-integrations.en.yaml`](automation/reload-integrations/reload-integrations.en.yaml)
- **📖 Documentation:** [Reload Integrations Automation Guide](https://domoticarte.com/p/reload-integrations-automation/)

#### 🇪🇸 Versión en Español

Sistema de recuperación automática para integraciones que se quedan "colgadas" o se vuelven no disponibles en Home Assistant. Perfecto para la integración de AEMET, dispositivos Xiaomi/Roborock, APIs externas y sensores Wi-Fi.

[![Abre tu instancia de Home Assistant y muestra el diálogo de importación de blueprint con un blueprint específico pre-completado.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fraw.githubusercontent.com%2Fdanimart1991%2Fhome-assistant-blueprints%2Fmain%2Fautomation%2Freload-integrations%2Freload-integrations.es.yaml)

- **📁 Archivo:** [`reload-integrations.es.yaml`](automation/reload-integrations/reload-integrations.es.yaml)
- **📖 Documentación:** [Guía de Automatización Recargar Integraciones](https://domoticarte.com/p/recargar-integrationes-automatizacion/)

---

## 🚀 Quick Start

### Method 1: One-Click Import (Recommended)

1. Click on any of the Home Assistant import badges above
2. Your Home Assistant instance will open with the blueprint pre-loaded
3. Click "Import Blueprint"
4. Configure your automation with the blueprint

### Method 2: Manual Import

1. Copy the raw URL of the blueprint you want to use:
   ```
   https://raw.githubusercontent.com/danimart1991/home-assistant-blueprints/main/automation/reload-integrations/reload-integrations.en.yaml
   ```

2. In Home Assistant, go to **Configuration** → **Blueprints** → **Import Blueprint**

3. Paste the URL and click "Import"

4. Create a new automation using the imported blueprint

### Method 3: Local Installation

1. Download the blueprint file to your Home Assistant `blueprints/automation/` directory
2. Restart Home Assistant or reload automations
3. The blueprint will appear in your blueprints list

## 🛠️ Requirements

- **Home Assistant:** 2024.6.0 or later
- **Blueprint Support:** Enabled (default in recent versions)

## 💡 Usage Tips

- **Start small:** Begin with one or two entities to test the automation
- **Timing matters:** Adjust check duration based on your integration stability
- **Monitor logs:** Check Home Assistant logs for successful reloads
- **Customize notifications:** Modify notification actions to fit your setup

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **🐛 Report Issues:** Found a bug? [Open an issue](https://github.com/danimart1991/home-assistant-blueprints/issues)
2. **💡 Suggest Features:** Have an idea? [Start a discussion](https://github.com/danimart1991/home-assistant-blueprints/discussions)
3. **🔧 Submit PRs:** 
   - Fork the repository
   - Create a feature branch
   - Add your blueprint with documentation
   - Submit a pull request

### Blueprint Submission Guidelines

When contributing new blueprints:

- ✅ Include both English and Spanish versions
- ✅ Add comprehensive documentation
- ✅ Provide real-world use cases
- ✅ Test thoroughly before submission
- ✅ Follow the existing file structure

## 📚 Additional Resources

- 🏠 **Home Assistant:** [Official Website](https://www.home-assistant.io/)
- 📖 **Blueprint Documentation:** [Official Docs](https://www.home-assistant.io/docs/automation/using_blueprints/)
- 🎓 **My Blog:** [domoticarte.com](https://domoticarte.com/)
- 💬 **Community:** [Home Assistant Community](https://community.home-assistant.io/)

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Thanks to the Home Assistant community for inspiration and feedback
- Special thanks to all contributors who help improve these blueprints

---

<div align="center">

**⭐ If you find these blueprints helpful, please consider giving this repository a star!**

[🐛 Report Bug](https://github.com/danimart1991/home-assistant-blueprints/issues) • [💡 Request Feature](https://github.com/danimart1991/home-assistant-blueprints/discussions) • [🤝 Contribute](https://github.com/danimart1991/home-assistant-blueprints/pulls) • [💖 Sponsor](https://github.com/sponsors/danimart1991)

</div>