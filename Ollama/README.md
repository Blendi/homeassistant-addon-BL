# Ollama Addon for Home Assistant by BLENDI

## Model Directory

All downloaded models are stored `/share/ollama`. Please make sure that you have sufficient space available.

## Ollama Integration

[![Add Ollama Integration](https://my.home-assistant.io/badges/brand.svg)](https://my.home-assistant.io/redirect/config_flow_start/?domain=ollama)

To integrate with the default [Ollama](https://www.home-assistant.io/integrations/ollama/) integration use the following data:

- URL: `http://f708789e-ollama:11434`

## Note

By default the container runs with CPU acceleration only. If you are interesting in getting GPU support, please check the [Website of the Ollama Container Image](https://hub.docker.com/r/ollama/ollama).
