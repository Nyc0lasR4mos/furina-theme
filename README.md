# 𝓕𝓾𝓻𝓲𝓷𝓪 𝓣𝓱𝓮𝓶𝓮

[![PowerShell](https://img.shields.io/badge/PowerShell-7.6.3-blue?logo=powershell)](https://github.com/PowerShell/PowerShell)
[![Oh My Posh](https://img.shields.io/badge/Oh_My_Posh-Theme-03A9F4?logo=powershell)](https://ohmyposh.dev/)
[![FastFetch](https://img.shields.io/badge/FastFetch-2.65.2-29B6F6)](https://github.com/fastfetch-cli/fastfetch)
[![License](https://img.shields.io/badge/License-MIT-yellow)](LICENSE)
[![Windows](https://img.shields.io/badge/Windows-11-blue?logo=windows)](https://www.microsoft.com/windows)
[![Genshin](https://img.shields.io/badge/Genshin_Impact-Furina-4FC3F7)](https://genshin-impact.fandom.com/wiki/Furina)

> *"A Hydro Archon of Fontaine, bringing elegance to your terminal."*

E aí! Depois de criar o Ghoul Theme, quis fazer algo completamente diferente — algo que trouxesse a elegância e a leveza da **Furina** de Genshin Impact. E foi assim que nasceu o **Furina Theme**.

Feito com **Oh My Posh** rodando no **PowerShell 7.6.3**, esse tema é uma mistura de:
-  Estética suave e profissional com tons de azul
-  Inspiração na Hydro Archon de Fontaine
-  Paleta "Fantasy Blue" personalizada
-  Detalhes que trazem a vibe do universo de Genshin

Queria algo que fosse mais "pessoal" sabe? Profissional, claro, mas com aquela vibe única de quem fez com carinho. E é isso que você vai ver aqui.

##  Preview

<img width="1365" height="735" alt="Furina Theme Preview" src="screenshots/terminal-preview.png" />

<img width="1364" height="568" alt="FastFetch Preview" src="screenshots/fastfetch-preview.png" />

##  Componentes

- **Oh My Posh** - Prompt personalizado com paleta suave
- **FastFetch** - Info do sistema com tema Hydro/Fontaine
- **Nerd Fonts** - JetBrainsMono Nerd Font + FiraCode Nerd Font Mono
- **Windows Terminal** - Background personalizado com esquema Fantasy Blue

## 📦 Instalação

### Pré-requisitos

- [PowerShell 7+](https://github.com/PowerShell/PowerShell)
- [Oh My Posh](https://ohmyposh.dev/)
- [FastFetch](https://github.com/fastfetch-cli/fastfetch)
- [JetBrainsMono Nerd Font](https://www.nerdfonts.com/)
- [FiraCode Nerd Font](https://www.nerdfonts.com/)
- [Git](https://git-scm.com/)

### 1. Clonar o repositório

```bash
git clone https://github.com/Nyc0lasR4mos/furina-theme.git
cd furina-theme
```
### 2. Instalar o tema Oh My Posh

Copie o arquivo powershell/FurinaTheme.omp.json para:

C:\Users\SEU-USUARIO\PowerShell\FurinaTheme.omp.json

### 3. Configurar o PowerShell Profile

Copie powershell/Microsoft.PowerShell_profile.ps1 para:

C:\Users\SEU-USUARIO\Documents\PowerShell\Microsoft.PowerShell_profile.ps1

### 4. Configurar o FastFetch

Copie os arquivos da pasta fastfetch/ para:

C:\Users\SEU-USUARIO\.config\fastfetch\

### 5. Configurar o Windows Terminal

Abra o windows-terminal/settings.json e adicione o esquema de cores Fantasy Blue na seção "schemes":

{
  "name": "Fantasy Blue",
  "background": "#0A1523",
  "foreground": "#D4F4FF",
  "cursorColor": "#FFFFFF",
  "selectionBackground": "#2E5575",
  "black": "#0A1523",
  "red": "#4A7DA2",
  "green": "#67B8D9",
  "yellow": "#A4E7FF",
  "blue": "#3F83B8",
  "purple": "#6AB8FF",
  "cyan": "#5FE4FF",
  "white": "#D4F4FF",
  "brightBlack": "#304A63",
  "brightRed": "#6FA9CF",
  "brightGreen": "#8FD5F5",
  "brightYellow": "#C9F5FF",
  "brightBlue": "#6FC7FF",
  "brightPurple": "#98D8FF",
  "brightCyan": "#B5F5FF",
  "brightWhite": "#FFFFFF"
}

Depois, no perfil do PowerShell, adicione:

"colorScheme": "Fantasy Blue"

### 6 Recarregar

& $PROFILE

### Funcionalidades
 Prompt com separadores powerline suaves
 Paleta de cores "Fantasy Blue" personalizada
 FastFetch com tema Hydro e Fontaine
 ASCII art personalizado da Furina (versão completa e mini)
 Ícones personalizados das Nerd Fonts
 Versão completa e minimalista do FastFetch
 Cores suaves e harmoniosas

 ### Paleta de Cores (Fantasy Blue)

 ### Esquema de Cores (Windows Terminal)

### Licença

MIT License - Sinta-se livre para usar e modificar!

### Créditos

ASCII art da Furina baseado em arte da comunidade
Tema inspirado na Furina de Genshin Impact (miHoYo/HoYoverse)
Paleta "Fantasy Blue" personalizada
Conceito Hydro/Fontaine do universo de Teyvat

### Nycolas Ramos

[![LinkedIn](https://img.shields.io/badge/LinkedIn-000000?style=for-the-badge\&logo=linkedin\&logoColor=7c1919)](https://www.linkedin.com/in/nycolas-ramos-483810399/) [![GitHub](https://img.shields.io/badge/GitHub-000000?style=for-the-badge\&logo=github\&logoColor=7c1919)](https://github.com/Nyc0lasR4mos)
