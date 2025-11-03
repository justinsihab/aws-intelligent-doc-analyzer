# aws-intelligent-doc-analyzer
La conception une app qui lit des PDF, comprend leur contenu et génère un résumé pro automatiquement.
Textract → Comprehend → SageMaker → Bedrock, orchestré par Lambda + Step Functions. Upload d’un PDF → résumé, entités, type de document, JSON exporté dans S3.
