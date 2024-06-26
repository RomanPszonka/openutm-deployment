# OpenUTM Deployment
A repository to help with deployment of the OpenUTM toolset in your cloud.

## Steps
1. Understand the general architecture of the system by reviewing the [OAUTH Infrastructure](oauth_infrastructure.md) document.
2. Step 1: Deploy Flight Passport via Docker or other mechanisms using and customizing the [Passport environment file](env.examples/.passport.env.example)
3. Step 2: Create your own environment files by reviewing the [constructing environment files](constructing_environment_files.md)
4. Deploy Flight Blender and Flight Spotlight using the environment files provided. 
