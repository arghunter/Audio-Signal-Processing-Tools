# Audio-Signal-Processing-Tools

This is a kit of various audio signal proecessing tools and experiments gto base further experimentation off of. 

While a number of the tools are still undner devlopment, DesignTest.py is allows tone to test how a certain microphone beamforming array would perform with O(1) delay and sum beamforming under vairous conditions. Because the array is designed in a way such that interpolation is not required it can run beamforming incredibly quickly. 

Steps to run

1) Install dependencies with the requirements.txt
2) Replace the input audio files with your own. Lines 12, 18, and 24 as of now
3) Set the angles you want each sound source to be positioned at. Lines 16, 22, and 28
4) Set the path of the output files. Lines 45 and 77.
5) Run the file.


