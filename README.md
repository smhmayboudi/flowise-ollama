# flowise-ollama

My purpose to become familiar with AI and how to shape a AI product.

## Learn

```
https://www.youtube.com/watch?v=nqAK_L66sIQ&list=PL4HikwTaYE0H7wBxhvQqxYcKOkZ4O3zXh&ab_channel=LeonvanZyl
```

```
https://flowiseai.com/
https://github.com/FlowiseAI/Flowise
```

```
https://ollama.com/
https://github.com/ollama/ollama
```

## OLLAMA

```shell
OLLAMA_ORIGINS=127.0.0.1:3000 OLLAMA_HOST=127.0.0.1:11435 GIN_MODE=debug ollama serve
```

## FLOWISE

```shell
docker run -ti --rm --name flowise -p 3000:3000 flowiseai/flowise:1.6.4 flowise start
```

## Prompts

# 1
Tell me a joke about {subject}.

you are a harsh and rude reviewer. write a review about the following joke {joke}.

# 2
You are an experienced chef. create a unique recipe using the main ingredient {ingredient}.

you are a harsh and rude food critic. write a review about the following recipe: {recipe}.
