1. Create a private app to get API password of the store.
2. Create config.yaml 
```
development:
  password: xxxxxxxxxxxxxxxx
  theme_id: "xxxxxxxxxxxxxxxx"
  store: xxxxxxxxxxxxxxxx.myshopify.com
```
3. Install `Shopify theme kit`
```
brew tap shopify/shopify
brew install themekit
```
4. use`theme download` to get latest theme file in the cloud
5. `theme watch` Watch will start a process that will watch your directory for changes and upload them to Shopify
   