# Anotações

## Workshop 1 - Acelerando sua evolução

`https://www.youtube.com/watch?v=JL-__ngSTcA`

**AMBIENTE** - `https://www.notion.so/Configurando-o-ambiente-953aad022cda4fbcb149be2bfe793995`

**LAYOUT** - `https://www.notion.so/Layout-Happy-OmniStack-faac4d4d638343fe8bab627125a7557c`

```bash
# Iniciar projeto web React
yarn create react-app web --template typescript

# Colocar Icones no React
yarn add react-icons

# Rotas
yarn add react-router-dom
yarn add @types/react-router-dom -D

# Adicionar mapa
yarn add leaflet react-leaflet
yarn add @types/react-leaflet -D
```

## Workshop 2 - Olhando as oportunidades

`https://www.youtube.com/watch?v=QArToKrgBNs`

**Visualizar dados do sqlite**:
https://www.beekeeperstudio.io

```bash
# Iniciar projeto
mkdir backend
yarn init -y

# Instalar express
yarn add express
yarn add @types/express -D

# Configurar typescript
yarn add typescript -D
yarn tsc --init
# No arquivo tsconfig.json
# "target": "es5", -> "target": "es2017",

# Executar node com typescript
yarn add ts-node-dev -D
ts-node-dev src/server.ts

# Configurar banco de dados
yarn add typeorm sqlite3

# Criar migrações pelo typeorm
yarn typeorm migration:create -n create_orphanages
yarn typeorm migration:run
yarn typeorm migration:revert

yarn typeorm migration:create -n create_images

# Biblioteca para upload de images
yarn add multer
yarn add @types/multer -D

# Lidando com exceções
yarn add express-async-errors

# Validação
yarn add yup
yarn add @types/yup -D

# Permitir aplicação ser acessada de diferentes dominios
yarn add cors
yarn add @types/cors -D

```

## Workshop 3 - A escolha da stack

`https://www.youtube.com/watch?v=eVTmT1g9bmg`

```bash
# Conectar com backend
yarn add axios
```

## Workshop 4 - Até 2 anos em 2 meses

`https://www.youtube.com/watch?v=CJI4ltmHLeo`

**Recursos que o Expo não suporta**:
https://expo.canny.io

```bash
# Instalar o expo globalmente
yarn global add expo-cli

# Mapa no expo
expo install react-native-maps

# Adicionar fontes
https://github.com/expo/google-fonts

expo install @expo-google-fonts/nunito expo-font

# Adicionar navegação
# https://reactnavigation.org/docs/getting-started

yarn add @react-navigation/native
expo install react-native-gesture-handler react-native-reanimated react-native-screens react-native-safe-area-context @react-native-community/masked-view

yarn add @react-navigation/stack
```

## Workshop 5 - A milha extra

`https://www.youtube.com/watch?v=esluWJwQb8I`

```bash
yarn add axios

# Lidando com importação de imagens
expo install expo-image-picker
```
