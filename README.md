[Установить плагин](https://360.topomatic.ru?extensionInstallPath=https%3A%2F%2Fvs-kovelev-prm.github.io%2Ft360.sandbox%2F)

# Установка зависимостей

```sh
npm install
```

# Сборка

```sh
npm run build
```

# Отладка

```sh
npm run serve
```

# Установка

```typescript
const extensionPath = 'https://vs-kovelev-prm.github.io/t360.sanbox/'
const href = `https://360.topomatic.ru?extensionInstallPath=${encodeURIComponent(extensionPath)}`;
```
