# Master Thesis - Dataset Stefan Kamenica

This repository contains all Github test projects used to evaluate the three dependency detection approaches.
Each test project is maintained in a separate branch. The required modifications to the CI/CD pipeline configuration have already been applied, allowing SBOM generation and detector evaluation to be performed consistently across all projects.

## How to generate a sbom-output.json file:
1. Navigate to `Actions`
2. In `Actions` choose the desired workflow file for which the sbom-output.json should be generated.
3. Click on `Run workflow`
4. Choose the corresponding branch (e.g. g-helper Release should be triggered in g-helper branch) and click `Run workflow`
5. When the `generating-sbom` job is finished, click into it
6. Choose the `Upload SBOM` step and click on the download URL
