
# 🌐 Vistametric v2.0

![Next.js](https://img.shields.io/badge/Next.js-16-blue?logo=next.js)
![Three.js](https://img.shields.io/badge/Three.js-3D-black?logo=three.js)
![React](https://img.shields.io/badge/React-18-blue?logo=react)
![Vercel](https://img.shields.io/badge/Deploy-Vercel-black?logo=vercel)
![License](https://img.shields.io/badge/license-MIT-green)

<p align="center">
    <img src="https://vistametric.vercel.app/banner.png" alt="Vistametric Banner" width="80%"/>
</p>

<p align="center">
    <b>Visualização e mapeamento 3D imersivo para ambientes profissionais.</b>
</p>

---

## 📑 Sumário

- [Visão Geral](#visão-geral)
- [Stacks Utilizadas](#stacks-utilizadas)
- [Demonstração Visual](#demonstração-visual)
- [Guia do Usuário](#guia-do-usuário)
- [Guia do Desenvolvedor](#guia-do-desenvolvedor)
- [Como Funciona](#como-funciona)
- [Testar Online](#testar-online)
- [Estrutura de Pastas](#estrutura-de-pastas)
- [Licença e Créditos](#licença-e-créditos)

---


## 👁️ Visão Geral

O **Vistametric** é um sistema para visualização, navegação e documentação de modelos 3D georreferenciados, com foco em setores como imobiliário, industrial e patrimonial. Permite criar experiências interativas, pontos panorâmicos e navegação inteligente entre ambientes, com interface adaptável para edição e visualização.

---


## 🛠️ Stacks Utilizadas

<p>
    <img src="https://img.shields.io/badge/Next.js-16-blue?logo=next.js"/>
    <img src="https://img.shields.io/badge/Three.js-3D-black?logo=three.js"/>
    <img src="https://img.shields.io/badge/React-18-blue?logo=react"/>
    <img src="https://img.shields.io/badge/Deploy-Vercel-black?logo=vercel"/>
    <img src="https://img.shields.io/badge/IndexedDB-Local%20Storage-yellow"/>
</p>

---


## 🎬 Demonstração Visual

<p align="center">
    <img src="/public/assets/app-demo.png" alt="Vistametric App Demo" width="80%"/>
</p>

---


## 👤 Guia do Usuário

### Hotspots e Endpoints

**Hotspots** são pontos interativos sobre o modelo 3D, podendo abrir panoramas 360º, exibir informações ou fotos. **Endpoints** são posições salvas para navegação rápida, facilitando a movimentação entre ambientes ou setores do modelo.

### Como usar
1. Faça upload do modelo 3D (`.glb`).
2. Clique no modelo para adicionar Hotspot ou Endpoint.
3. Edite propriedades (nome, posição, imagem, orientação).
4. Salve no projeto.
5. Navegue entre endpoints e acesse hotspots pelas abas:
    - **Modelos**: Troca de modelos 3D
    - **Endpoints**: Navegação rápida
    - **Hotspots**: Gerenciamento dos pontos

---


## 👨‍💻 Guia do Desenvolvedor

### Instalação e Execução
```bash
git clone https://github.com/seu-usuario/vistametric.git
cd vistametric
npm install
npm run dev
```
### Build de Produção
```bash
npm run build
# O build estará otimizado e em modo visualizador
```
### Estrutura
- `/app/components/`: Componentes visuais e 3D
- `/app/hooks/`: Lógica de navegação e storage
- `/app/api/`: Endpoints backend
- `/public/assets/models/`: Modelos 3D
- `/public/assets/hotspots/`: Panoramas 360º
- `/public/data/project_config.json`: Configurações persistidas

---


## ⚙️ Como Funciona

O Vistametric opera em dois modos:
- **Desenvolvedor**: Upload, criação e edição de pontos, persistência local.
- **Visualizador**: Interface limpa, apenas navegação e visualização.
Toda configuração é salva em `project_config.json` e os arquivos são armazenados em pastas públicas.

---


## 🚀 Testar Online

👉 [Acesse a aplicação online](https://vistametric.vercel.app/)

---


<!-- Estrutura de pastas já detalhada acima -->


## 📄 Licença e Créditos

Projeto para visualização patrimonial e industrial. Imagens e modelos processados localmente ou via servidor autorizado.


---

> [!IMPORTANT]
> **Nota de Experimento**: Este projeto foi desenvolvido 100% usando Inteligência Artificial via Antigravity (Google DeepMind) para testar a capacidade, precisão e velocidade extrema na criação de um MVP complexo em regime no-code assistido.

---

