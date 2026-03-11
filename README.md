# devops-practice-app

DevOps CI/CD pipeline, this project demnostrates:
  Node.js application containerized with Docker
  Automated CI/CD pipeline using GitHub Actions [first_pipeline](https://github.com/user-attachments/assets/1880ad07-7a2a-4809-9a28-6fe760273b49)
  Docker image automatically published to Docker Hub on every push (https://hub.docker.com/repository/docker/devaldo26/devops-practice-app/general)!

So, I have been learning Azure cloud fundamentals, and since i no longer have access to the free tier azure portal, I can't build and deploy on there anymore, so I decided to use Gemini deep learning as a teacher alongside the tutorials, and ChatGPT also as a hands on mentor/teacher. So Gemini helps me with the concepts and tests my knowledge, and then ChatGPT helps me with the practical work and debugging.

Workflow:
Developer Push
      ↓
GitHub Actions (CI)
      ↓
Docker Build
      ↓
Docker Hub Push
      ↓
Ready for Deployment

The pipeline automatically builds and pushes Docker images to Docker Hub using both the latest tag and a commit specific tag for traceability and rollback.
