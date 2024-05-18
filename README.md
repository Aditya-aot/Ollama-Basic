# Ollama-Basic
--------------------------------------------------
Ollama is a tool that allows you to run open-source large language models (LLMs) locally on your machine. It supports a variety of models, including Llama 2, Code Llama, and others.

Ollama allows you to run open-source large language models, such as Llama 2, locally.

Ollama bundles model weights, configuration, and data into a single package, defined by a Modelfile.

It optimizes setup and configuration details, including GPU usage.
---------------------------------------------------------
#
For a complete list of supported models and model variants, see the Ollama model library.
-------------------------------------------------------
-
```sh
pip install ollama
```
<img src='https://github.com/Aditya-aot/Ollama-Basic/assets/67204555/427b81bf-03f9-421b-a7e0-a7d7896a3004' alt='github' width='150' height='150'>

## Usage
--------------------------------------------------------
```python
import ollama
response = ollama.chat(model='llama2', messages=[
  {
    'role': 'user',
    'content': 'Why is the sky blue?',
  },
])
print(response['message']['content'])
```

<details>
  <summary>... fix most crashes on startup?</summary>

> You may have multiple mods loaded. Forge loads mods in alphabetical order, so you can change the name of the Mod jar to make it load earlier or later. Add for example an exclamation mark to lambda jar to make it load first.
> If you got `Error: java.lang.IllegalAccessError: tried to access field net.minecraft.util.math.Vec3i.field_177962_a from class baritone.k` remove the `-noverify` tag from your arguments.

</details>

<details>
  <summary>... fix most crashes on startup?</summary>

> You may have multiple mods loaded. Forge loads mods in alphabetical order, so you can change the name of the Mod jar to make it load earlier or later. Add for example an exclamation mark to lambda jar to make it load first.
> If you got `Error: java.lang.IllegalAccessError: tried to access field net.minecraft.util.math.Vec3i.field_177962_a from class baritone.k` remove the `-noverify` tag from your arguments.

</details>
