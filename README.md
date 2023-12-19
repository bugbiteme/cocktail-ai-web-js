# Web Front End for cocktail-ai RestAPI

## Test locally
- Set the `API_URL` environment variable on your system to the `generate-recipe` endpoint/path  
(Example)
```
export API_URL="https://cocktail-ai/generate-recipe/"
```  
  
- Launch app from command line from within the `CocktailAiWeb` directory  
  
```
npx expo start
```

## Deploy and run in a container

```
podman build -t my-react-app .

podman run -p 3000:3000 my-react-app
```
