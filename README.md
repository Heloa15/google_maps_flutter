# 🗺️ Flutter Maps

Aplicação desenvolvida em **Flutter** utilizando o pacote `flutter_map` e o **OpenStreetMap** para criação de um mapa interativo.

O projeto permite que o usuário selecione um ponto no mapa, visualize um marcador no local selecionado e consulte as coordenadas de latitude e longitude.

---

## 📱 Funcionalidades

- 🗺️ Exibição de um mapa interativo
- 📍 Seleção de um ponto através de toque no mapa
- 📌 Exibição de marcador no ponto selecionado
- 🌎 Captura da latitude e longitude
- 💬 Exibição das coordenadas através de um `SnackBar`
- 🔍 Configuração de posição e zoom inicial
- 🎨 Interface utilizando Material 3

---

## 🛠️ Tecnologias utilizadas

- **Flutter**
- **Dart**
- **flutter_map**
- **latlong2**
- **OpenStreetMap**

---

## 📦 Dependências

As principais dependências utilizadas no projeto são:

```yaml
dependencies:
  flutter:
    sdk: flutter

  flutter_map: ^8.2.2
  latlong2: ^0.9.1

 ```
 ## Estrutura dos Arquivos

  flutter_maps/
│
├── android/
│
├── assets/
│   └── Flutter Maps.png
│
├── ios/
│
├── lib/
│   └── main.dart
│
├── linux/
├── macos/
├── web/
├── windows/
│
├── pubspec.yaml
├── pubspec.lock
├── analysis_options.yaml
├── .gitignore
└── README.md

```

 ```
 ## Print da Tela 
 ![Tela do aplicativo](assets/Flutter%20Maps.png)