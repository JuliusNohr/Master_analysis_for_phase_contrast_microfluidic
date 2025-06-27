The code is the master script controling two other scripts Scaling_Analysis.ipynb and Growth_Rate_oscillation.ipynb.
Those scripts will be published later by Forshungzentrum Jülich.
The code is designed to run on a Jupiter Lab with Python ipkernel3. 

The purpose of this script is the controling of a pipeline analysing Phase contrast timelapse images from microfluidic research on Synechocystis sp. PCC 6803. 
It was designed working with an Omero server as data storage. 


The Starter.ipynb creates a needed folder structure inside the Jupiter Lab for running the pipeline.
To use this script, simply place it in your main folder where you want the pipeline to work and run it ones.

The recursive_delete.ipynb delets folders backwards in the system, enableing the user to also create folders that are not empty. This is usefull when having many subfolders. This action can not be redone.
To use this script, place it in the folder that needs to be deleted. Run the script. Afterwards there will be only empty folders in that folder. Delete those and the script manually and you can delete the folder.

MIT License

Copyright (c) 2025 Julius

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
