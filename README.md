# PipelineIQ AI Service

Independent repository staging folder for the PipelineIQ Gemini/Azure AI service.

## Build

```bash
docker build -t nimeshsv814/pipelineiq-gemini-ai-service:v1.0.0 -f services/gemini-ai-service/Dockerfile .
```

## Run

This service expects PipelineIQ environment variables from Kubernetes ConfigMap and Key Vault secrets.
