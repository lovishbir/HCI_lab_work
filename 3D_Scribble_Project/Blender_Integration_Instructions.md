# Blender Integration Instructions

To run the 3D Scribble Project with the Blender Python API (`bpy`), follow these instructions:

## Method 1: Running Code in Blender

1. Open Blender.
2. Switch to the "Scripting" workspace.
3. Create a new text file in the text editor.
4. Copy and paste the code from the Jupyter Notebook into the Blender text editor.
5. Run the script by clicking the "Run Script" button.

## Method 2: Using Blender's Python Interpreter with Jupyter

1. Locate Blender's Python executable. It is usually found in:
   ```
   /Applications/Blender.app/Contents/Resources/4.3/python/bin/python3.11
   ```
   (Adjust the path according to your Blender version and installation location.)

2. Install the `ipykernel` package if it is not already installed:
   ```bash
   /path/to/blender/python -m pip install ipykernel
   ```

3. Create a new Jupyter kernel that uses Blender's Python:
   ```bash
   /path/to/blender/python -m ipykernel install --user --name blender --display-name "Blender Python"
   ```

4. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

5. When creating a new notebook, select the "Blender Python" kernel.

Now you can run the 3D Scribble Project code in Jupyter Notebook with access to the `bpy` module.
