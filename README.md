# 3D-artist-test-

# Task Details: High Poly and Low Poly Modeling

## High Poly Model
- **Create a detailed high poly model based on the provided reference image.**
- Ensure that all features, details, and contours from the reference are accurately represented.
- Save and name the file as `HighPoly_Model`.

## Low Poly Model
- **Create a simplified version of the high poly model.**
- Maintain the overall shape and essential features while reducing the poly count for mobile optimization.
- Save and name the file as `LowPoly_Model`.

## Baking Maps
### Normal Map
- Bake the normal map from the high poly model to the low poly model.

### Ambient Occlusion Map
- Bake the ambient occlusion map to add depth and shadow details to the texture.

### Roughness Map
- Create a roughness map to define the reflective properties of different surfaces.

### Export
- Save the baked maps in PNG format with appropriate naming conventions (e.g., `NormalMap.png`, `AOMAP.png`, `RoughnessMap.png`).

## Texturing
- **Use the baked maps to texture the low poly model.**
- Create realistic and game-ready textures, ensuring they are optimized for mobile use.
- Include the following texture maps:
  - Albedo (Base Color) Map
  - Normal Map
  - Roughness Map
  - Ambient Occlusion Map
- Texture resolution should be 1024x1024.

## Submission Requirements
- **High Poly Model File:** `HighPoly_Model.blend`
- **Low Poly Model File:** `LowPoly_Model.blend`
- **Baked Maps:**
  - `NormalMap.png`
  - `AOMAP.png`
  - `RoughnessMap.png`
- **Textures:**
  - `AlbedoMap.png`
  - `NormalMap.png`
  - `RoughnessMap.png`
  - `AOMAP.png`
- **Final Low Poly Model with Textures:** Provide the final low poly model in FBX or OBJ format with embedded or attached textures.
- **Documentation:** A brief document (PDF) explaining your workflow, tools used, and any challenges faced and how they were resolved.

  # How to Contribute

We welcome your contributions! Please follow these steps to push your changes to the repository:

### 1. Fork the Repository

1. Navigate to the main page of the repository.
2. Click the `Fork` button at the top right corner of the page.
3. This will create a copy of the repository in your GitHub account.

### 2. Clone Your Fork

1. Open your terminal or command prompt.
2. Clone your forked repository to your local machine using the following command:

    ```bash
    git clone https://github.com/your-username/3D-artist-test-.git
    ```

3. Change into the repository directory:

    ```bash
    cd 3D-artist-test-
    ```

### 3. Create a New Branch

1. Create a new branch for your changes:

    ```bash
    git checkout -b your-branch-name
    ```

### 4. Make Changes and Commit

1. Make your desired changes to the code.
2. Stage the changes for commit:

    ```bash
    git add .
    ```

3. Commit the changes with a descriptive message:

    ```bash
    git commit -m "Description of the changes"
    ```

### 5. Push Changes to Your Fork

1. Push your changes to your forked repository on GitHub:

    ```bash
    git push origin your-branch-name
    ```

### 6. Create a Pull Request

1. Navigate to the original repository (the one you forked from).
2. Click on the `Pull requests` tab.
3. Click the `New pull request` button.
4. Select the branch you just pushed to your forked repository.
5. Fill in the details of the pull request, providing a clear title and description of your changes.
6. Click `Create pull request`.

## Note

Please ensure that all files and documentation are properly named and organized according to the submission requirements before pushing your changes.

Thank you for contributing!

## Deadline
The entire task must be completed and submitted within 2 days from the start of the test.

