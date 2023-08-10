# Serving a Scalable Fast API application leveraging Celery and Redis

### Pre-requisites:

- You must deploy it on a GPU with ~16GB of memory
- You will need `docker compose` (HINT: Do not use `docker-compose`)
    - [Documentation](https://docs.docker.com/compose/install/linux/#install-the-plugin-manually)
- You will need to ensure `nvidia-ctk --version` provides a valid output
    - [Documentation](https://docs.nvidia.com/datacenter/cloud-native/container-toolkit/latest/install-guide.html)
- You will need to select a model (the default is [LLaMA 2 7B Chat (HF weights)](https://huggingface.co/meta-llama/Llama-2-7b-chat-hf))
 
### Tasks:

1. Provide a simple system diagram (created in whatever format you feel best communicates the flow) for the application
2. Provide an example output from the model. Include any and all requests made to the endpoint
    - NOTE: Getting an output is a multi-step process
    - NOTE: If you're using the LLaMA 2 default model - please pay attention to the prompt tokens - see the model card for more details

This is meant to be a challenging task - so you might need to spend some time troubleshooting and tinkering!
